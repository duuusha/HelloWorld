# Launching JShell Interactive Console

IntelliJ IDEA includes an interactive JShell console that allows you to write and evaluate Java code snippets. This document describes how to launch the JShell console and use it to run a sample code snippet.
> Note that the JShell Console requires JDK 9.

![jshell_result](https://user-images.githubusercontent.com/35970470/35905994-111245e8-0bfa-11e8-9129-073576747b96.png)

1. Select **Tools | Groovy Console** on the main menu.

1. If your project consists of several modules, choose the module to use the classpath of:

    ![jshell_selectmodule](https://user-images.githubusercontent.com/35970470/35905048-a8c9e35e-0bf6-11e8-8ab3-40a21cd03eb2.png)

    The JShell console opens in a separate tab in the editor:

    ![jshell_empty](https://user-images.githubusercontent.com/35970470/35905619-dba17a6a-0bf8-11e8-8657-e21d6917370f.png)

1. Type a code snippet in the console after the prompt character:

    ![jshell_intellisense](https://user-images.githubusercontent.com/35970470/35905625-df170746-0bf8-11e8-926b-816a579e0957.png)

   Note that code completion and error highlighting is available.

1. Click ![playbutton](https://user-images.githubusercontent.com/35970470/35906125-7cfa8130-0bfa-11e8-9ef4-7b88cc6eabb5.png) to execute the entered code:

    ![jshell_result](https://user-images.githubusercontent.com/35970470/35905994-111245e8-0bfa-11e8-9129-073576747b96.png)

    Results will be displayed in the [Run Tool Window](https://www.jetbrains.com/help/idea/run-tool-window.html).