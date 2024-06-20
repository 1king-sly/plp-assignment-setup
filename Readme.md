1.Operating System (OS)
Chosen OS: Windows 10
Reason: Already installed and comfortable working with it.
2. Install a Text Editor or Integrated Development Environment (IDE)
Chosen IDE: Visual Studio Code
Status: Already installed and I have been using it for a while.
3. Set Up Version Control System
Git Installation: Already installed and configured.
GitHub Account: Already created and linked to the local machine.
Git Repository Initialization steps followed:

    git init plp-assignment-setup
    cd dev_setup_project
    git remote add origin https://github.com/1king-sly/plp-assignment-setup
    git add .
    git commit -m "Initial commit"
    git push -u origin master
4. Install Necessary Programming Languages and Runtimes
Python Installation:
Download Link: Python Download
Installation Steps:
Download the installer from the Python website.
Run the installer and follow the prompts.
Ensured the "Add Python to PATH" option is selected.
Verification:

    python --version : 3.12.4
    pip --version :23.2.1
5. Install Package Managers
Pip Installation:
Pip is included with Python installations 
Verified installation with:

pip --version : 3.12.4

6. Configure a Database (MySQL)
MySQL Installation:
Download Link: MySQL Installer 5.7
Installation Steps:
    Download the MySQL installer.
    Run the installer and choose the "server only" installation type.
    Configure MySQL server:
    Set root password and create a user.
    Configure the server to start automatically.
    Complete the installation.
    Troubleshooting: Check the 'Log' tab for detailed error messages if the installation fails.
7. Setting Up Development Environments and Virtualization 
Virtualization Tools: Docker  for containerization.
Docker Installation:
Download Link: Docker Desktop
Installation Steps:
Downloaded Docker Desktop.
Run the installer and followed the prompts.
Ensured  Docker is running by executing:
    docker --version
8.Extensions and Plugins

Opened Visual Studio Code.
wnet to the Extensions view by clicking the Extensions icon in the Activity Bar or by pressing Ctrl+Shift+X.
Search for the extensions and click "Install".

Visual Studio Code Extensions:
Python: Microsoft’s extension for Python development.
GitLens: Enhances Git capabilities in VS Code.
Docker: Adds Docker support for VS Code.
Prettier: Code formatter.
ESLint: Linting for JavaScript code.

