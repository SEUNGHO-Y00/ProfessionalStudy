# Securing Windows and PowerShell Automation

## 1. Introduction to PowerShell

### 1. Overview and background of Windows PowerShell

1. Windows PowerShell overview
2. Windows PowerShell version
3. Windows PowerShell vs operating system
4. Two host applications
   * Console, ISE
5. Working in mixed-version environments
6. Precautions when opening Windows PowerShell
7. Configuring the console
8. Demonstration: Configuring the console
9. Configuring the ISE
10. Demonstration: Configuring the ISE

### 2. Understanding command syntax

1. Cmdlet structure
   * Verb-Noun
2. Tab completion
3. Parameters
   * Starting with a dash "-"
   * Optional, positional, and/or required
   * Multiple value, separated by commans
   * optional for positional parameters
4. Using Get-Help
   * -Examples, -Fulls, -Online, -Showwindow
5. Interpreting the help syntax
6. Demonstration: Viewing help
```PowerShell
Get-Help Get-NetFirewallRule -Examples
Get-Help Get-ADUser -Full
Get-Help Get-WinEvent -ShowWindow
```
7. Updating help
8. About files
   * about_
   * Get-Help about_*
9. Demonstration: Using About files
```PowerShell
Get-Help about_*
Get-Help about_Comparison_Operators
Get-Help about_Scopes
Get-Help about_Script_Blocks
```

### 3. Finding Commands

1. What are modules?
2. Demonstration: Viewing modules
3. Finding cmdlets
   * Get-Command, Get-Help
4. Demonstration: Searchiing for cmdlets
```PowerShell
Get-Command -Noun NetIPAddress
Get-Command -Noun AD*
Get-Help *net* -Category cmdlet
```
5. What are aliases?
6. Demonstration: Using aliases
7. Using Show-Command

## 2. Introduction to the Pipeline

### 1. Understanding the pipeline

1. What is the pipeline?
   * Separated by a pipe character "|"
2. Piepline output
3. Discovering object members
   * Properties, Methods, Events
   * Get-Member = a discovery tool like Get-Help
4. Demonstration: Viewing object members
```PowerShell
Get-Service | Get-Member
Get-Process | Get-Member
Get-ADUser -Filter * | Get-Member
Get-AdUser -Filter * -Properties * | Get-Member
```
5. Formatting pipeline output
6. Demonstration: Formatting pipeline output

## 3. Pipeline and Data Filtration

### 1. Format, Sort, Measure, and select objects

1. Formatting objects
  * Format pipeline = Format-List, Format-Table, Format-Wide
  * Parameter = -Property, -GroupBy, -Wrap
2. Demonstration: Formatting objects
```PowerShell
Get-ADUser -Filter *
Get-ADUser -Filter * -Property * | ft -Property Name, Department, Enabled, whenCreated, SmartcardLogonRequired -GroupBy Enabled
Get-EventLog -Logname Security
Get-EventLog Security -Newest 10 | fl -Property TimeWritten, EventID, EntryType, Message -GroupBy TimeWritten
```
3. Sorting objects by a property
   * Sort-Object, Group-Object
4. Demonstration: Sorting objects
```PowerShell
Get-EventLog -LogName Security -Newest 10
Get-EventLog Security -Newest 10 | Group EventID
Get-Process | Sort -Property CPU -Descending
Get-Process | Group ProcessName | Sort Count -Descending
```
5. Measuring objects
   * Measure-Object
6. Demonstration: Measuring objects
```PowerShell
Get-Service | Measure-Object
Get-Content .\helloworld.ps1 | Measure -Character -Line -Word
Get-ADUser -Filter * | Measure
Get-Process | Measure -Property CPU -Sum -Average -Maximum -Minimum
```
7. Selecting a subset of objects
   * Select-Object
     - -First, -Last, -Skip, -Unique
     - -Property
```PowerShell
Get-Process | Sort -Property CPU -Descending | Select -Last 10
Get-ADUser -Filter * -Properties * | Select -Property Name, Department, Enable
```
8. Selecting properties of objects
```PowerShell
Get-Date | Select-Object -Property DayofWeek
Get-Process | Sort -Property CPU -Descending | Select -Property Name,ID,VM,CPU | Format-Table
Get-ADUser -Filter * -Properties * | Select -Property Name,Department,City,State
Get-ADUSer -Filter * -Properties * | Select Name,Enabled,LastLogOnDate | fl -GroupBy Enabled
```
9. Demonstration: Selecting objects

### 2. Filtering Objects by comparison

1. Comparison operators

| Comparison Type | Case-insensitive operator | Case-sensitive operator |
| --------------- |:-------------------------:| -----------------------:|
| Equality                 | -eq                       | -ceq                    |
| Inequality               | -ne                       | -cne                    |
| Greater than             | -gt                       | -cgt                    |
| less than                | -lt                       | -clt                    |
| Greater than or equal to | -ge                       | -cge                    |
| less than or equal to    | -le                       | -cle                    |
| Wildcard equality        | -like                     | -clike                  |

2. Basic filtering syntax
   * Where-Object = filtering
```powershell
Get-Service | Where-Object -Property Status -eq Running
Get-Process | Where CPU -gt 20
```
3. Advanced filtering syntax
   * -and & -or
```PowerShell
Verb-Noun | Where-Object -filterscript {$_.PropertyName -eq 'value' -or $_.PropertyName -eq 'Value'}
Get-Service | Where-Object -Filter {$PSItem.Status -eq 'Running'}
Get-Service | Where { $_.Status -eq 'Running'}
Get-Service | ?{$PSItem.Status -eq 'Running'}
Get-Volume | Where -filter { $PSItem.HealthStatus -ne 'Healthy' -or $PSItem.SizeRemaining -lt 100MB }
```
4. Demonstration: Filtering
```PowerShell
Get-Process | Where-Object CPU -ge 50
Get-ADUser -Filter * | Where -Filterscript {$_.Enabled -eq 'True'}
Get-ADUser -Filter * -Properties * | ? {$_.Enabled -eq $True -and $_.SmarcardLogonRequired -eq $false} | Select Name,Enabled,Deaprtment,SmartcardLogonRequired | ft -Property Name,Enabled,Department,SmartcardLogonRequired
```
5. Optimizing filtering performance

### 3. Enumerating objects in the pipeline

1. Purpose of enumeration
2. Basic enumeration syntax
   * Get-ChildItem
3. Demonstration: Basic enumeration
4. Advanced enumeration syntax
5. Demonstration: Advanced enumeration

### 4. Sending pipeline data as output

1. Writing output to a file
2. Converting output to CSV
   * ConvertTo-CSV, Export-CSV
3. Converting output to XML
   * ConvertTo-Xml, Export-CliXml
4. Converting output to JSON
   * ConvertTo-JSON
   * Not supported by an Export cmdlet
5. Converting output to HTML
   * ConvertTo-HTML
   * Not supported by an Export cmdlet
6. Demonstration: Exporting data
```PowerShell
Get-ADUser -Filter * -Properties * | ExportTo-CSV .\Users.csv
Get-Service | Export-Clixml .\Services.xml
Get-Process | ConvertTo-HTML | Out-File .\Processess.html
Get-WinEvent -LogName Security -MaxEvents 10 -Oldest | ConvertTo-JSON > .\security.json
```
7. Additional output options
   * Read-Host

## 4. PSProviders and PSDrives

### 1. Using PRProviders

1. What are Windows PowerShell providers?
2. Different provider capabilities
3. Accessing provider help
   * Get-PSProvider, Get-Help <provider-name>
4. Demonstration: Viewing PSProvider help
```PowerShell
Get-Help about_Providers
Get-PSProvider
Get-Help FileSystem
```

### 2. Using PSDrives

1. What are PSDrives?
   * PSProvider to connect to the store
   * New-PSDrive, Get-PSDrive
2. Cmdlets for using PSDrives
   * Get-Command -Noun Item (or ChildItem or ItemProperty)
   * Get-Command -Noun Location
   * -Name, -PSProvider, -Root
3. Working with the file system
   * New-Item = mkdir, md, ni / -Pate, -ItemType (Requires)
   * Remove-Item = del, erase, rd, ri, rm, rmdir / -Recurse (deleting folders)
   * Get-Item, Get-ChildItem = gi, gci, dir, ls / -Exclude, -Include, -Filter (Supports)
4. Demonstration: Managing the file system
```PowerShell
Set-Location C:\Windows
New-PSDrive -Name SANS -Root C:\SANS -PSProvider FileSystem
New-Item -Path SANS:\Test.txt -ItemType File
Set-Location SANS:
Get-ChildItem
```
5. Working with the registry
6. Demonstration: Managing the registry
7. Working with certificates
8. Working with other PSDrives

## 5. Variables & Arrays

### 1. Using variables

1. What are variables?
   * A variable stores a value or object in memory
   * Get-Variable, Get-ChildItem Variable:
2. Variable naming
   * Only alphanumeric characters
3. Assigning a value to a variable
```PowerShell
$num1 = 5
$logFile = C:\Logs\Log.txt
$user = Get-ADUser Administrator
$service = Get-Service W32Time
```
4. Variable types
   * String, Int32, Double, DateTime, Bool
5. Demonstration: Assigning a variable type
   * $(valiralbe).GetType()

### 2. Manipulating variables

1. Identifying methods and properties
   * Only default properties are transferred to a variable by default
   * If you wish to modify the value assigned to a variable, you must assign the new value to it!!
2. Working with strings
   * Length = only property available for string
   * Contains, Insert, Remove, Replace, Split, ToLower(), ToUpper()
3. Demonstration: Manipulating strings
```PowerShell
$string = "Left Face!"
$string.Length
$string.Insert(0,"Half-")
$string.Replace("Left","Right")
$string.Split(" ")
```
4. Working with dates
5. Demonstration: Manipulating dates

### 3. Manipulating arrays & hash tables

1. What is an array?
   * An array contains multiple values or objects
```PowerShell
$computers = "LON-DC1","LON-RV1","LON-CL1"
$users = Get-ADUser -Filter *
$newUser = @()
[Array]$computers = "LON-DC1"
```
2. Working with arrays
   * Get-Member = To identify what you can do with the array contents
3. Working with arraylists
   * Create an arraylist
```PowerShell
$computers = New-Object System.Collections.ArrayList
[System.Collections.ArrayList]$computers = "LON-DC1","LON-SRV1"
```
   * Add or Remove
```PowerShell
$computers.Add("LON-SVR2")
$computers.Remove("LON-CL1")
$computers.RemoveAt(1)
```
4. Demonstration: Manipulating arrays and arraylists
5. What is a hash table?
   * a list of key-value pairs
6. Working with hash tables
   * Define
```PowerShell
$servers = @{"LON-DC1"="172.16.0.10";"LON-SRV1"="172.16.0.11"}
```
7. Demonstration: Manipulating hash tables
```PowerShell
$servers.Add("LON-SRV2","172.16.0.12")
$servers.Remove("LON-DC1")
$servers.'LON-SRV2'="172.16.0.100"
```

## 6. Flow Control and Decision Structures

### 1. Introduction to scripting

1. Overview of Windows PowerShell scripts
2. Modifying scripts
3. Creating scripts
4. What is the PowerShellGet module?
5. Running scripts
   * Open, Run with PowerShell, Edit
6. The script execution policy
   * Restricted, AllSigned, RemoteSigned, Unrestricted, ByPass
7. Demonstration: Setting the script execution policy
```PowerShell
Get-ExecutionPolicy
Set-ExecutionPolicy -ExecutionPolicy Restricted
.\Documents\HelloWorld.ps1

Set-ExecutionPolicy Bypass
.\Documents\HelloWorld.ps1
```
8. Digitally signing scripts
9. Demonstration: Digitally signing a script

### 2. Scripting constructs

1. Understanding ForEach loops
   * ForEach ($item in $collection){ perform action(s) }
2. Demonstration: Using a ForEach loop
```PowerShell
$users = Get-ADUser -Filter * -Properties *
ForEach ($user in $users)
{
  $date = Get-Date
  Set-ADUser -Identity $user -AccountExpirationDate $date.AddDays(365)
  Set-ADUser -Identity $user -Enabled $True
  Set-ADUser -Identity $user -SmartcardLogonRequired $True
}
```
3. Understanding the For loop
   * Initial state, Condition, Action
4. Demonstration: Using For the loop
```PowerShell
For($i=1; $i -le 10; $i++)
{
  New ADComputer -Name "EISENWKSTNSLDC$I"
}
Get-ADComputer -Filter * | Select-Object Name
```
5. Understanding the If construct
   * If (condition -eq $True) {Perform Action}
   * Else {Perform Action}
   * ElseIf (other condition -eq $true) {Perform Action}
     Else {Perform Action}
6. Understanding Break and Continue
   * Continue stops processing the current iteration of a loop
   * Break completely stops loop processing
7. Demonstration: Using the If construct
```PowerShell
ForEach ($user in $users)
{
  If ($user.PasswordExpired -eq $True)
  { Set-ADUser -Identity $user -Enabled $False
    $Name = $user.Name
    Write-Host "$Name has been disabled due to expired password"
  } Else {
    $Name = $user.Name
    Write-Host "$Name has a valid password"
  }
```
8. Understanding the Switch construct
   * a list of values
9. Understanding other loop constructs
   * Do..While (Loop, guaranteed once), Do..Until, While (Processes, no guaranteed)

### 3. Importing data from files

1. Using Get-Content
   * Content from a text file
   * -TotalCount, -Tail
2. Using Import-CSV
3. Using Import-Clixml
   * -First, -Skip
4. Using ConvertFrom-Json
5. Demonstration: Importing data

