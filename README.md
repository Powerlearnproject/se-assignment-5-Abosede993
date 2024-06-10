[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15250208&assignment_repo_type=AssignmentRepo)

# SE-Assignment-5

Installation and Navigation of Visual Studio Code (VS Code)
Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

Questions:

1. Installation of VS Code:

   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
     Download the Visual Studio Code installer for Windows.Once it is downloaded, run the installer (VSCodeUserSetup-{version}.exe). This will only take a minute. by default it is downloaded

2. First-time Setup:

   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
     for initial configuration and settings

3. Auto Save

4. Format on Save

5. Format on Paste

6. Customising Cursor

7. Bracket Pair Colorization

for important extensions, prettier,github copilot,llive server,settings sync e.t.c 3. User Interface Overview:

- Explain the main components of the VS Code user interface.Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

1 Editor - The main area to edit your files. You can open as many editors as you like side by side vertically and horizontally.

2 Primary Side Bar - Contains different views like the Explorer to assist you while working on your project.
Status Bar - Information about the opened project and the files you edit.

3 Activity Bar - Located on the far left-hand side. Lets you switch between views and gives you additional context-specific indicators, like the number of outgoing changes when Git is enabled. You can change the position of the Activity Bar.

4 Panel - An additional space for views below the editor region. By default, it contains output, debug information, errors and warnings, and an integrated terminal. The Panel can also be moved to the left or right for more vertical space.

4. Command Palette:

   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
     The Command Palette provides access to many commands and it can be accessed by typing Ctrl+Shift+P.
     You can run editor commands, open files, search for symbols, and see a quick outline of a file, all using the same interactive window.

5. Extensions in VS Code:

   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
     VS Code extensions let you add languages, debuggers, and tools to your installation to support your development workflow.
     user can find extension by clicking on the extension icon on the side of vs code and choosing the one the want to download.
     examples of essential extensions are
     Live Sass compiler.
     Debugger for Chrome.
     C#
     Live Server.
     ES Lint.
     Beautify.
     Better Comments.
     Quokka.

6. Integrated Terminal:

   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
     From there, select the "View" option and then click on "Terminal". Once the terminal window appears, you can start using it to run commands and scripts in various languages such as Bash, Python, JavaScript, Java, TypeScript, and more.
     advantages are

   1 It provides integration with the editor to support features like links and error detection.

   2 improve developer productivity thanks to fast setup and standardization across tools

7. File and Folder Management:

   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
     the explorer tool is used to open and manage files and folders in vs code.
     This can be done through both command-line interfaces (using commands like cd, dir, or ls) and graphical user interfaces (using file managers).

8. Settings and Preferences:

   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
     Use the Settings editor to review and change VS Code settings. To open the Settings editor, navigate to File > Preferences > Settings. Alternately, open the Settings editor from the Command Palette (Ctrl+Shift+P) with Preferences: Open Settings or use the keyboard shortcut (Ctrl+,).

   to change theme, Select the File > Preferences > Theme > Color Theme menu item, or use the Preferences: Color Theme command (Ctrl+K Ctrl+T) to display the Color Theme picker. Use the Up and Down keys to navigate through the list and preview the colors of the theme. Select the theme you want and press Enter.
   to change keybindings On the menu bar, choose Tools > Options. Expand Environment, and then choose Keyboard.

9. Debugging in VS Code:

   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

To run or debug a simple app in VS Code, select Run and Debug on the Debug start view or press F5 and VS Code will try to run your currently active file. However, for most debugging scenarios, creating a launch configuration file is beneficial because it allows you to configure and save debugging setup details.
some key debugging features are,
Debug configuration management.
Debug actions for starting/stopping and stepping.
Source-, function-, conditional-, inline breakpoints, and log points.
Stack traces, including multi-thread and multi-process support.

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
      If your workspace is on your local machine, you can enable Git source control by creating a Git repository with the Initialize Repository command. When VS Code doesn't detect an existing Git repository, the Source Control view will give you the options to Initialize Repository or Publish to GitHub.

Describe the process of initializing a repository, making commits, and pushing changes to GitHub is
Open Terminal .
Navigate to the root directory of your project.
Initialize the local directory as a Git repository. By default, the initial branch is called main . ...
Add the files in your new local repository. ...
Commit the files that you've staged in your local repository.
Submission Guidelines:

- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July
