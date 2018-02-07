# Working with the Embedded Terminal

IntelliJ IDEA provides an embedded terminal that allows you to work with command line tools available in your operating system. For instance, these can be PowerShell or cmd.exe on Windows, Shell or Bash on Linux. You can also use the terminal to work with a Git command line.

![terminal-example](https://user-images.githubusercontent.com/35970470/35732900-52fca588-082c-11e8-965d-48b4369c0486.png)

Do one of the following to run the terminal:
* Press ```Alt+F12```.
* Hover the mouse pointer over the ![icon](https://user-images.githubusercontent.com/35970470/35734067-dbfa1f2e-0830-11e8-87bf-f48be1027792.png) button in the IDE's lower left corner and select **Terminal** in the [invoked menu](https://www.jetbrains.com/help/idea/working-with-tool-windows.html#tool_window_quick_access).


## Configure Terminal Type
To use the specific terminal type, go to [File | Settings | Tools | Terminal](https://www.jetbrains.com/help/idea/terminal.html) and provide a path to the required shell executable in the **Shell path** field. Click the ![ellipsis-button](https://user-images.githubusercontent.com/35970470/35767054-6b6532d8-08f5-11e8-97e3-b8e0da50c6a5.png) button next to **Shell path** and locate the corresponding file in the invoked dialog:

![shell-executable-path](https://user-images.githubusercontent.com/35970470/35766911-0aaec43e-08f2-11e8-87ca-39db9ca44ea3.png)

The table below lists common shell executables and their default locations for Windows:

Shell Type | Default Shell Path
------------ | -------------
Command Prompt | C:\Windows\System32\cmd.exe
PowerShell | C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe
Git Bash | C:\Program Files\Git\bin\bash.exe

Fox Linux:

Shell Type | Default Shell Path
------------ | -------------
Bash | /bin/bash
Shell | /bin/sh


## Work with Terminal

To run a command in the terminal, press ```Enter```. The ```Up``` and ```Down``` arrow keys allows you to navigate through the history of commands.

You can work within terminal using specified shortcuts or a context menu available by right-clicking the terminal's surface. Below are the main commands provided by IntelliJ IDEA:

Context Menu Item | Shortcut | Description
------------ | ------------- | -------------
Find | ```Ctrl-F``` | Invokes the search panel that allows you to find the specified text.
Open as URL |  | Opens the selected URL in a default browser.
Copy | ```Ctrl-C``` | Copies the selected text to the clipboard.
Paste | ```Ctrl-V``` | Pastes the text from the clipboard.
Clear Buffer | ```Ctrl-K``` | Clears the terminal.
Page Up | ```Shift-Page Up``` | Scrolls page up.
Page Down | ```Shift-Page Down``` | Scrolls page down.



## Manage Multiple Sessions
The embedded terminal allows you to open different sessions and navigate between them.

To create a new session, do one of the following:
* Click the ![plus-button](https://user-images.githubusercontent.com/35970470/35767442-63e34c54-08fd-11e8-8f7c-99af774d947c.png) button on the terminal's toolbar.
* Right-click a current session window (or a session tab) and choose **New Session** in the context menu (```Ctrl+Shift-T```).
A new session opens in a separate tab:

![terminal-tabs](https://user-images.githubusercontent.com/35970470/35767570-959bf32a-08ff-11e8-998a-8026f92b2b2e.png)

To close an active session, use the ![cross-button](https://user-images.githubusercontent.com/35970470/35767540-e515b752-08fe-11e8-9347-8ced8e78e229.png) button on the terminal's toolbar.
Below are the context menu commands and corresponding shortcuts allowing you to work with sessions:

Context Menu Item | Shortcut | Description
------------ | ------------- | -------------
New Session | ```Ctrl+Shift-T``` | Creates a new session.
Close Session | ```Ctrl+Shift-W``` | Closes the active session.
Next Tab | ```Alt-Right``` | Switches to the next session.
Previous Tab | ```Alt-Left``` | Switches to the previous session.
Rename Tab |  | Allows you to rename the session tab.


## Manage Terminal Settings
* [Tools | Terminal](https://www.jetbrains.com/help/idea/terminal.html) - provides access various terminal-specific settings. For instance, you can change the default working directory, the default name of a session tab, etc.
* The following global IDE settings are also applied to the terminal:
    * [Keymap](https://www.jetbrains.com/help/idea/keymap.html) - the ```Ctrl+C``` and ```Ctrl+V``` shortcuts.
    * [Editor | General | Appearance](https://www.jetbrains.com/help/idea/appearance-2.html) - the **Caret blinking** option.
      > Note that the **Use block caret** option is not in effect for the terminal because its caret is always block.
    * [Appearance and Behavior | Appearance](https://www.jetbrains.com/help/idea/appearance.html) - the **Antialiasing | IDE** option.
    * **Editor | Color Scheme | Console Font** - terminal font settings.
    * **Editor | Color Scheme | Console Colors** - terminal colors.
    * **Editor | Color Scheme | General** - the **Editor | Selection background** and **Selection foreground** options.

      > Note that applying new settings related to the terminal color and font settings may require restarting IDE.
