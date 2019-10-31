
# Powershell Rosetta Stone


| DOS      | Unix        | Powershell               | Synopsis                                                                                       |
| -------- | ----------- | ------------------------ | ---------------------------------------------------------------------------------------------- |
| HELP     | man         | [Get-Help]               | Displays information about PowerShell commands and concepts.                                   |
|          | apropos     | [Get-Command]            | Gets all commands.                                                                             |
|          |             |                          |                                                                                                |
|          | pwd         | [Get-Location]           | Gets information about the current working location or a location stack.                       |
| CD       | cd          | [Set-Location]           | Sets the current working location to a specified location.                                     |
| MD       | mkdir       | [New-Item]               | Creates a new item. (-ItemType Directory)                                                      |
| PUSHD    | pushd       | [Push-Location]          | Adds the current location to the top of a location stack.                                      |
| POPD     | popd        | [Pop-Location]           | Changes the current location to the one most recently pushed onto the stack.                   |
|          |             |                          |                                                                                                |
| DIR      | ls          | [Get-ChildItem]          | Gets the files and folders in a file system drive.                                             |
|          | find        | [Get-ChildItem]          | Gets the files and folders in a file system drive. (-Name)                                     |
| CP       | cp          | [Copy-Item]              | Copies an item from one location to another.                                                   |
| REN      | mv          | [Rename-Item]            | Renames an item in a Windows PowerShell provider namespace.                                    |
| MV       | mv          | [Move-Item]              | Moves an item from one location to another.                                                    |
|          | touch       | [New-Item]               | Creates a new item. (-ItemType File)                                                           |
| DEL      | rm          | [Remove-Item]            | Deletes files and folders.                                                                     |
|          |             |                          |                                                                                                |
| CLS      | clear       | [Clear-Host]             | Clears the display in the host program.                                                        |
| SET /P   | read        | [Read-Host]              | Reads a line of input from the console.                                                        |
| ECHO     | echo        | [Write-Host]             | Writes customized output to a host.                                                            |
| TYPE     | cat         | [Get-Content]            | Gets the contents of a file.                                                                   |
|          | tail        | [Get-Content]            | Gets the contents of a file. (-Tail 10)                                                        |
|          | tee         | [Tee-Object]             | Saves command output in a file or variable and also sends it down the pipeline.                |
| FINDSTR  | grep        | [Select-String]          | Finds text in strings and files.                                                               |
|          | grep        | [Where-Object]           | Selects objects from a collection based on their property values.                              |
|          | cut         | [Select-Object]          | Selects objects from a collection based on their property values.                              |
| SORT     | sort        | [Sort-Object]            | Sorts objects by property values. (-Unique)                                                    |
|          | uniq        | [Get-Unique]             | Returns unique items from a sorted list.                                                       |
|          | wc          | [Measure-Object]         | Calculates the numeric properties of objects, and the characters, words, and lines in strings. |
|          | diff        | [Compare-Object]         | Compares two sets of objects.                                                                  |
|          | column      | [Format-Table]           | Formats the output as a table.                                                                 |
|          |             |                          |                                                                                                |
|          | jq          | [ConvertFrom-Json]       | Converts a JSON-formatted string to a custom object.                                           |
|          | csvtool     | [ConvertFrom-Csv]        | Converts object properties in comma-separated value format.                                    |
|          |             |                          |                                                                                                |
| TASKLIST | ps          | [Get-Process]            | Gets the processes that are running on the local computer or a remote computer.                |
| TASKKILL | kill        | [Stop-Process]           | Stops one or more running processes.                                                           |
|          | time        | [Measure-Command]        | Measures the time it takes to run script blocks and cmdlets.                                   |
|          | strace      | [Trace-Command]          | Configures and starts a trace of the specified expression or command.                          |
| TIMEOUT  | sleep       | [Start-Sleep]            | Suspends the activity in a script or session for the specified period of time.                 |
|          |             |                          |                                                                                                |
| PING     | ping        | [Test-Connection]        | Sends ICMP echo request packets ("pings") to one or more computers.                            |
| TRACERT  | traceroute  | [Test-Connection]        | Sends ICMP echo request packets ("pings") to one or more computers.                            |
| NSLOOKUP | dig         | [Resolve-DnsName]        |                                                                                                |
| IPCONFIG | ip addr     | [Get-NetIPConfiguration] | Gets IP network configuration.                                                                 |
|          |             | [Get-NetIPAddress]       | Gets the IP address configuration.                                                             |
| ROUTE    | ip route    | [Get-NetRoute]           | Gets the IP route information from the IP routing table.                                       |
| ARP      | ip neighbor | [Get-NetNeighbor]        | Gets neighbor cache entries.                                                                   |
| NETSTAT  | ss          | [Get-NetTCPConnection]   | Gets TCP connections.                                                                          |
|          |             |                          |                                                                                                |
|          | curl        | [Invoke-WebRequest]      | Gets content from a web page on the Internet.                                                  |
|          |             |                          |                                                                                                |
|          |             | [Get-Member]             | Gets the properties and methods of objects.                                                    |

[Clear-Host]:            	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Core/Clear-Host
[Compare-Object]:        	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Utility/Compare-Object
[ConvertFrom-Csv]:       	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Utility/ConvertFrom-Csv
[ConvertFrom-Json]:      	https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.utility/ConvertFrom-json
[Copy-Item]:             	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Management/Copy-Item
[Format-Table]:          	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Utility/Format-Table
[Get-ChildItem]:         	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Management/Get-ChildItem
[Get-Command]:           	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Core/Get-Command
[Get-Content]:           	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Management/Get-Content
[Get-Member]:            	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Utility/Get-Member
[Get-Help]:              	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Core/Get-Help
[Get-Location]:          	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Management/Get-Location
[Get-NetIPAddress]:      	https://docs.microsoft.com/en-us/powershell/module/nettcpip/Get-NetIPAddress
[Get-NetIPConfiguration]:	https://docs.microsoft.com/en-us/powershell/module/nettcpip/Get-NetIPConfiguration
[Get-NetNeighbor]:       	https://docs.microsoft.com/en-us/powershell/module/nettcpip/Get-NetNeighbor
[Get-NetRoute]:          	https://docs.microsoft.com/en-us/powershell/module/nettcpip/Get-NetRoute
[Get-NetTCPConnection]:  	https://docs.microsoft.com/en-us/powershell/module/nettcpip/Get-NetTCPConnection
[Get-Process]:           	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Management/Get-Process
[Get-Unique]:            	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Utility/Get-Unique
[Invoke-WebRequest]:     	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Utility/Invoke-WebRequest
[Measure-Command]:       	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Utility/Measure-Command
[Measure-Object]:        	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Utility/Measure-Object
[Move-Item]:             	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Management/Move-Item
[New-Item]:              	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Management/New-Item
[Pop-Location]:          	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Management/Pop-Location
[Push-Location]:         	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Management/Push-Location
[Read-Host]:             	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Utility/Read-Host
[Remove-Item]:           	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Management/Remove-Item
[Rename-Item]:           	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Management/Rename-Item
[Resolve-DnsName]:       	https://docs.microsoft.com/en-us/powershell/module/dnsclient/Resolve-DnsName
[Select-Object]:         	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Utility/Select-Object
[Select-String]:         	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Utility/Select-String
[Set-Location]:          	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Management/Set-Location
[Sort-Object]:           	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Utility/Sort-Object
[Start-Sleep]:           	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Utility/Start-Sleep
[Stop-Process]:          	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Management/Stop-Process
[Tee-Object]:            	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Utility/Tee-Object
[Test-Connection]:       	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Management/Test-Connection
[Trace-Command]:         	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Utility/Trace-Command
[Where-Object]:          	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Core/Where-Object
[Write-Host]:            	https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Utility/Write-Host
