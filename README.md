# Barebones Unity Project Template for Unity 2021.3.17f1 & Entitas 1.14.1

How to Generate:

Open CMD or PowerShell from the root of the unity project then
CMD: dotnet Jenny/Jenny.Generator.Cli.dll gen
Powershell/Linux: dotnet .\Jenny\Jenny.Generator.Cli.dll gen


## Setup Steps For 1.14.1


1. Downloaded the Entitas release 1.14.1 Entitas.zip and Jenny.zip.
Unzipped Entitas, Removed the internal Jenny folder, moved the Entitas folder to my Unity Assets directroy.

2. Unzipped the Jenny.zip and placed at the root of my Unity project. (1 Level Above Assets)

3. Used this Jenny.properties to get started: https://github.com/sschmid/Match-One/blob/main/Jenny.properties

4. Copied over Jenny-AutoImport, Jenny-Auto-Import.bat, Jenny-Server and Jenny-Server.bat from same github. (Didn't end up using them, I ran into trouble with them.)

5. Updated the Jenny.SearchPath to lookd at Assets/Entitas/Entitas.


6. Using just terminal from root of unity project


- \working-barebones-entitas\unity-entitas> dotnet Jenny/Jenny.Generator.Cli.dll gen
- \working-barebones-entitas\unity-entitas> dotnet Jenny/Jenny.Generator.Cli.dll help




