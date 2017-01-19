# Cpp-project
Source code of airship program

# Steps to Run the Project
1. Download Code::Blocks:
Go to this website: http://www.codeblocks.org/downloads
Follow the link to "Download the binary release" (direct link)
Go to the Windows 2000 / XP / Vista / 7 section
Look for the file that includes mingw in the name. (The name as of this writing was codeblocks-16.01mingw-setup.exe)
Save the file to your desktop.
2. Install Code::Blocks:
Double click the installer.
Hit next several times. Other setup tutorials will assume you have installed in C:\Program Files\CodeBlocks (the default install location), but you may install elsewhere if you like
Do a Full Installation
Launch Code::Blocks
3. Running in Code::Blocks:
choose "GNU GCC Compiler" when you are prompted with a Compilers auto-detection window
Code::Blocks may ask if you want to associate it as the default viewer for C/C++ files--I'd suggest you do. Click on the File menu, and under "New", select "Project..."
Launch the Project Wizard through File->New->Project... to start a new project. Here there are many pre-configured templates for various types of projects, including the option to create custom templates. Select Console application, as this is the most common for general purposes, an click Go.

![](http://wiki.codeblocks.org/images/8/8f/ProjectWizard.png)

Note: red text instead of black text below any of the icons signifies it is using a customized wizard script.

The console application wizard will appear next. Continue through the menus, selecting C++ when prompted for a language. In the next screen, give the project a name and type or select a destination folder. As seen below, Code::Blocks will generate the remaining entries from these two.

![](http://wiki.codeblocks.org/images/b/be/ConsoleApplication.png)

Finally, the wizard will ask if this project should use the default compiler (normally GCC) and the two default builds: Debug and Release. All of these settings are fine. Press finish and the project will be generated. The main window will turn gray, but that is not a problem, the source file needs only to be opened. In the Projects tab of the Management pane on the left expand the folders and double click on the source file main.cpp to open it in the editor.

![](http://wiki.codeblocks.org/images/e/e7/SelectSource.png)

You can now open the main.cpp file on the left: 
![](http://www.cprogramming.com/code_blocks/c.PNG)

_At this point, you will have your main.cpp file, which you can modify if you like. For now, it just says "Hello World!", so we can run it as is. Hit F9, which will first compile it and then run it._



![](http://www.cprogramming.com/code_blocks/d.PNG) 


***

# For further information related to configuring and running codeblocks, please follow this link: http://www.cprogramming.com/code_blocks/
