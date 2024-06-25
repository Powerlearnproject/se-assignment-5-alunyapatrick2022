[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15237830&assignment_repo_type=AssignmentRepo)

# SE-Assignment-5

# SE - ASSIGNMENT-5 ANSWERS COMPLETE WITH SCREENSHOTS ON THE Important settings and configurations screenshots FOLDER.

Installation and Navigation of Visual Studio Code (VS Code)
Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

Setting up Visual Studio involves a few steps. Here's a concise step-by-step guide:
Download Visual Studio:
Visit the Visual Studio website that is https://www.google.com/url?client=internal-element-cse&cx=0a95731fe4679f836&q=https://code.visualstudio.com/&sa=U&ved=2ahUKEwij2YSKw8qGAxWsUKQEHTRwCr4QFnoECAkQAQ&usg=AOvVaw2pFZeV9tyf5P6sxv7VhFEn&fexp=72519171,72519168 and click on "Download Visual Studio.

Follow the on-screen instructions to download the installer.
Run the Installer:
Run the downloaded installer.
Choose the "Visual Studio" workload during installation, which includes the necessary components for general development.

Select Workloads and Components:

In the Visual Studio Installer, select the workloads and components you need based on your development requirements. Common workloads include ".NET Desktop Development" or "Web Development."

Modify Installation (Optional):

If needed, you can customize the installation by clicking on the "Individual components" tab in the installer and selecting or deselecting specific components.

Install:

Click the "Install" button to start the installation process.
This may take some time, as it involves downloading and installing the selected components.

Launch Visual Studio:

Once the installation is complete, launch Visual Studio.
Sign in with your Microsoft account or create one if prompted.

Choose Development Environment:

On the welcome screen, select your development environment. For example, you can choose "Development Settings" based on your preferred coding style.

Start Coding:

You're now ready to start coding! Create a new project or open an existing one to begin your development work.

2. First-time Setup:

   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

   1. Navigate to settings icon on the bottom left and click settings. Go to github enterprise server configurations and add the github server url. This usally help to allow authentication when interracting with visual studio code and github.

   2. Also repeat process 1 and then click extensions. Search for python extension to run python files,search for prettier and install then sync it, this extension help in formatting codes to help the look good and well organised.

3. User Interface Overview:

   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

   Top right navigation bar - This side contains a buttons for toggling primary side bar,panel, secondary side bar, customizing layout,minimize display, remove display,close vscode.

   Top left naigation bar - This side contains the following buttons:

   file button - onclick it displays shortcuts for creating new file, opening recent files, opening a folder, saving a file, saving a workspace, adding folder to worksapce, exit button, closing window.

   edit button - onclick it displays the following shortcuts: undo changes, redo changes, cut, copy, copy as, paste, find, replace, find in files, replace in files, toggle line comment, toggle block comment.

   View button - onclick it displays the following shortcuts : command palette, open view, appearance, edit layout, explorer, search, source control, run, extensions, problems, output, debug console, terminal, word wrap.

   Go button - onclick it displays the following shortcuts: back, forward, last edit location, swtch editor, switch group, go to file, go to symbol in workspace, go to definition, go to declaration, go to type definition, go to implementations, go to preferences, go to line/column, go to bracket, next problem, previous problem, next change.

   run button - onclick, it displays the following shortcuts: start debugging, run without debugging, stop debugging, restart debugging, open configs, step over, step into, step out, continue, toggle breakpoint, new breakpoint, enable all breakpoint, disable all breakpoint,remove all breakpoints

Activity Bar and its uses.

- Activity Bar: Located on the left side, provides access to different views like Explorer, Search,
  Source Control, Run, and Extensions.

- Side Bar: Displays different views and their contents, like the file explorer.
- Editor Group: Where you edit your files. Multiple files can be opened in tabs.
- Status Bar: Located at the bottom, shows information about the current file and project.
- Command Palette: Accessed via `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (macOS), allows
  you to run commands.

4. Command Palette:

   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
     Command Palette is located on the left activity bar.When a user clicks the view button he or she is able to see the command palette shortcut.

   Accessed via `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (macOS),
   The command palette allows you to run commands.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

Extesnions allows you to manage files for different programming languages.
Allows for easy code formatting.
Allows for debugging for errors in codes for different programming language.
Development Tools: They provide tools and functionalities that aid in the development process, such as linters, debuggers, formatters, and testing tools.

Users can find, install, and manage extensions in VS Code through the Extensions view, accessible via the sidebar(bottom left) or by pressing Ctrl+Shift+X (Cmd+Shift+X on macOS).
Users can install the extension by searching the name of the extension on the extension search bar and then click install.

Managing Extensions
View Installed Extensions: In the Extensions view, you can see a list of all installed extensions under the "Installed" section.
Disable/Enable Extensions: Click the gear icon next to an extension and choose Disable or Enable from the context menu.
Uninstall Extensions: Click the gear icon next to an extension and select Uninstall to remove it from VS Code.

Examples for popular development extensions.
Prettier - Code formatter: Automatically formats your code to ensure consistency. It supports multiple languages and is highly configurable.

Extension ID: esbenp.prettier-vscode
ESLint: Integrates ESLint JavaScript into VS Code. Provides real-time linting feedback to help you write cleaner code.

Extension ID: dbaeumer.vscode-eslint
Live Server: Launches a local development server with live reload feature for static and dynamic pages.

Extension ID: ritwickdey.LiveServer
Debugger for Chrome: Debug your JavaScript code running in the Google Chrome browser directly from VS Code.

Extension ID: msjsdiag.debugger-for-chrome
VS Code Icons: Adds a set of file icons to your VS Code for easier navigation and file recognition.

Extension ID: vscode-icons-team.vscode-icons
Path Intellisense: Provides path completion for local files, making it easier to navigate and reference files within your project.

Extension ID: christian-kohler.path-intellisense
GitLens: Enhances Git capabilities within VS Code, offering features like blame, history, and visualizations of code authorship.

Extension ID: eamodio.gitlens

6. Integrated Terminal:

   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
     Opening the Integrated Terminal
     Using the Menu:

- Go to the View menu at the top of the screen.
  Select Terminal from the dropdown menu.
  Using the Shortcut:
  On Windows/Linux: Press `Ctrl+``
  -Using the Command Palette:
  Open the Command Palette by pressing Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (macOS).
  Type "Terminal: Create New Integrated Terminal" and select the command from the list.

  Benefits for using Integrated terminal over external terminals

  1.  Convenience and Efficiency
      Single Interface
      Single Interface: The integrated terminal allows you to perform all tasks within one application, reducing the need to switch between VS Code and an external terminal.

2. Integrated Workflow
   Context Awareness: The integrated terminal opens in the context of your current workspace, automatically setting the working directory to your project's root.

3. Integration with VS Code Features
   Code Navigation: Errors and outputs in the terminal can often be clicked to navigate directly to the relevant line in your code. This feature speeds up debugging and error resolution.

4. File and Folder Management:

   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
   - To create a new file a user can use the shortcut ctrl + n or use `File > New File`.
   - Open a File: Use `File > Open File` or drag and drop a file into the editor.

- Open a Folder: Use `File > Open Folder` to open a project directory.
- File Explorer: Use the Explorer view in the Activity Bar to navigate your project files.
- Tabs and Groups: Organize files in tabs and split editor views to compare or edit multiple files
  simultaneously.
  Reference: Class Notes by Anne Veronica.

5. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

Users can navigate to settings icon at the bottom left, then click settings. you will be displayed with settings for users and settings for workspace.

To change themes user navigate to settings icon on the left side bar then `theme > color theme, file icon theme, product icon theme`

To change font size user navigate to settings then fonts and adjust font size as needed.Refer to font size screenshot on the importants and configuration settings folder.

To change keybindings user can do the shortcut Cmd+Shift+P
Type Preferences:
Open Keyboard Shortcuts in the Command Palette and press Enter.
-In the Keyboard Shortcuts editor, you can search for the command you want to change the keybinding for by typing the command name in the search bar.
Change Keybinding:
Once you find the command, you can change its keybinding by clicking on the pencil icon that appears when you hover over the current keybinding.

6. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

Steps to Set Up and Start Debugging a Simple Program in VS Code
Install VS Code:

Download and install Visual Studio Code from the official website.
Install Required Extensions:

Depending on the programming language you are using, you may need to install specific extensions. For example, for Python, install the Python extension by Microsoft. Go to the Extensions view (Ctrl+Shift+X or Cmd+Shift+X) and search for the required extension.
Open Your Project:

Open your project folder in VSCode by selecting File > Open Folder and navigating to your project directory.
Set Up a Debug Configuration:

Open the Debug view by clicking the Debug icon in the Activity Bar on the side of the window or by pressing Ctrl+Shift+D (Windows/Linux) or Cmd+Shift+D (Mac).
Click on the gear icon to open the launch.json file. If it doesn’t exist, VSCode will prompt you to create one. Select the appropriate environment for your application (e.g., Python, Node.js).

7.  Using Source Control:
    -How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

        Prerequisites
        Install Git:
        Ensure Git is installed on your system. You can download it from git-scm.com.
        After Downloading make, run the istaller and choose the options to use vscode as default text editor.
        Install VS Code:
        Download and install Visual Studio Code from code.visualstudio.com.
        GitHub Account: Create a GitHub account if you don't have one.

        Next Steps:

        1.  Initialize a Repository
            Open VS Code: Launch VS Code and open your project folder.
            Open the Source Control View:
            Click on the Source Control icon in the Activity Bar on the side of the window (or press Ctrl+Shift+G).
            Initialize Repository:
            Click on the "Initialize Repository" button. This will create a new Git repository in your project folder.

        2.  Making Commits
            Track Changes: Once the repository is initialized, any changes in your project will show up in the Source Control view.
            Stage Changes: To stage changes, click the + icon next to the file you want to stage. Alternatively, you can stage all changes by clicking the + icon at the top of the Source Control view.
            Commit Changes: Enter a commit message in the message box at the top of the Source Control view and click the checkmark icon (or press Ctrl+Enter) to commit the staged changes.
        3.  Pushing Changes to GitHub
            Sign In to GitHub: If you haven't already, you need to sign in to your GitHub account. You can do this through the command palette (Ctrl+Shift+P) by searching for GitHub: Sign In.
            Add Remote Repository:
            Create a new repository on GitHub.
            Copy the repository URL.
            In VS Code, open the command palette (Ctrl+Shift+P) and type Git: Add Remote.
            Enter a name for the remote (usually origin) and paste the repository URL.

         4. Push Changes:
          Open the Source Control view.
           Click on the ellipsis (...) in the top right corner and select Push (or use the command palette Ctrl+Shift+P and type Git: Push).

Submission Guidelines:

- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July.
