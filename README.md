[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15300870&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.




Developer Environment Setup Documentation
Overview
This document outlines the steps I took to set up my developer environment, including
necessary software installations, configurations, and any customizations applied.
Troubleshooting steps for the issues I encountered during the setup are also provided.
My System Specifications
● Operating System: Windows 10 Pro, Version 20H2
● Processor: Intel Core i7-9750H
● RAM: 16GB
● Storage: 512GB SSD
Software Installation
1. Visual Studio Code
○ Download: Visual Studio Code
○ Installation: Standard installation with default options.
○ Extensions Installed:
○ Python
○ ESLint
○ Prettier
○ Docker
2. Git
○ Download: Git for Windows
○ Installation: Included additional components such as Git Bash, and
configured Git to use MinTTY as the terminal emulator for Git Bash.
3. Node.js
○ Download: Node.js
○ Version: 14.15.1 LTS
○ Installation: Used the default installation options.
4. Docker
○ Download: Docker Desktop for Windows
○ Installation: Enabled the WSL 2 based engine and integrated it with
existing WSL 2 Linux distributions.
Configuration
1. Visual Studio Code
○ Settings Sync: Enabled syncing via GitHub to maintain consistent
settings across machines.
○ Custom Settings:
json
DownloadCopy code
1{
2 "editor.tabSize": 2,
3 "editor.formatOnSave": true,
4 "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe"
5}
2. Git Configuration
○ Global Git Ignore:
○ Created a .gitignore_global file and configured Git to use it.
○ Command: git config --global core.excludesfile ~/.gitignore_global
○ User Information:
○ Set global user name and email.
○ Commands:
DownloadCopy code
1git config --global user.name "Ian Biwot”"
2git config --global user.email "iankimeli22@gmail.com"
Customizations
● Bash Profile Customizations:
● Added aliases and functions to .bashrc for convenience.
● Example:
bash
DownloadCopy code
1alias ll='ls -lah'
Troubleshooting
1. Node.js Installation Issues
○ Problem: Node.js commands not recognized in terminal.
○ Solution: Added Node.js path to system environment variables.
2. Docker Desktop Errors
○ Problem: Docker fails to start with errors related to WSL 2.
○ Solution: Ensured that the WSL 2 feature is enabled in Windows
Features and updated the Linux kernel package for WSL 2.
Conclusion
This document provides a detailed guide on how I set up my developer environment
tailored for software development using Visual Studio Code, Git, Node.js, and Docker..