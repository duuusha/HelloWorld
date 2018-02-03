# Working with Embedded Terminal

Intellij IDEA provides an embedded terminal that allows you to work with command line tools available in your operation system. By default, this can be PowerShell or cmd.exe on Windows, Shell or Bash on Linux. You can also run Git Bash in the terminal.

![111](https://user-images.githubusercontent.com/35970470/35732900-52fca588-082c-11e8-965d-48b4369c0486.png)

Do one of the following to run the terminal:
* Press ```Alt+F12```.
* Hover the mouse pointer over the ![icon](https://user-images.githubusercontent.com/35970470/35734067-dbfa1f2e-0830-11e8-87bf-f48be1027792.png) button in the IDE's lower left corner and select **Terminal** in the [invoked menu](https://www.jetbrains.com/help/idea/working-with-tool-windows.html#tool_window_quick_access).


## Configure Terminal Type
To use the specific terminal type, go to [File | Settings | Tools | Terminal](https://www.jetbrains.com/help/idea/terminal.html) and provide a path to the required shell executable in the **Shell path** field. Click the ellipsis button next to **Shell path** and locate the corresponding file in the invoked dialog:

![shell-execulable-path](https://user-images.githubusercontent.com/35970470/35766911-0aaec43e-08f2-11e8-87ca-39db9ca44ea3.png)

The table below lists common shell executables and their locations (Windows):

Shell Type | Default Location
------------ | -------------
Command Prompt | C:\Windows\System32\cmd.exe
PowerShell | C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe
Git Bash | C:\Program Files\Git\bin\bash.exe

## Terminal Display Settings

See also: [Working with Tool Windows](https://www.jetbrains.com/help/idea/working-with-tool-windows.html)

## Managing Multiple Sessions
