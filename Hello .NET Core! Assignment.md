***Hello .NET Core!***
## Objectives

-   To ensure installation is functioning properly, and that the correct SDK version is installed
-   Get familiar with the dotnet CLI
-   To witness the output of your compiled source code
-   To understand the differences between `dotnet build`, `dotnet run`, and `dotnet /path/to/YourProject.dll`

## *For this assignment, just copy the output of your console into a file, and upload.

 - [ ] run 'dotnet --version' to verify sdk is installed and in your system path
 - [ ] create/cd into a new project directory
 - [ ] run 'dotnet new console' to spin up a new console application
 - [ ] run 'dotnet build' to compile your C# files (here, just Program.cs) into a .dll file. note console output as to the location of this .dll file
 - [ ] execute your program by running the 'dotnet' command, followed by a path to your compiled .dll file
 - [ ] run 'dotnet run' to combine the previous two steps!

***Terminal***

JDMPro:NewProject jdmead$ dotnet

Usage: dotnet [options]
Usage: dotnet [path-to-application]

Options:
  -h|--help         Display help.
  --info            Display .NET Core information.
  --list-sdks       Display the installed SDKs.
  --list-runtimes   Display the installed runtimes.

path-to-application:
  The path to an application .dll file to execute.
JDMPro:NewProject jdmead$ dotnet run
Hello World!
JDMPro:NewProject jdmead$ ls
NewProject.csproj       Program.cs              bin                     obj
JDMPro:NewProject jdmead$ dotnet /Users/jdmead/Library/Mobile\ Documents/com~apple~CloudDocs/Coding\ Dojo/C#/NewProject/bin/Debug/netcoreapp2.2/NewProject.dll
Hello World!
JDMPro:NewProject jdmead$ dotnet run
**Hello World!
JDMPro:NewProject jdmead$** 
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTI2OTg2MTA4MF19
-->