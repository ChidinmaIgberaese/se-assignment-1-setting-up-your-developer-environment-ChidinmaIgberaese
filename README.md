[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15253493&assignment_repo_type=AssignmentRepo)

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

#Evaluation Criteria:\*\*

- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.

# SOLUTIONS

# Title: Developer Environment Setup

## Objective

This document provides detailed instructions to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

## The Setup Process

1. Operating System:
   I installed Windows 11 from Windows 11 Download.
   <img src="Windows 11 Installation screenshots.png">

2. Text Editor/IDE:
   Installed Visual Studio Code from VS Code Download.
   Downloaded the installer for Windows 11 operating system.
   Run the installer and follow the on-screen instructions to install Visual Studio Code.
   

3. Version Control System:
   Installed Git from Git Download.
   Configured Git with name and email.
   Created a GitHub account.
   Initialized a Git repository in project directory and made the first commit.
   <img src="Git download screenshot.png">

See project directory and process
cd C:\Django_plp\plp_ecommerce

git init
git add .
git commit -m "Initial commit"

git config --global user.name "My Name"
git config --global user.email "My Email"

4. Programming Languages and Runtimes:
   I installed Python from Python Download.
   Verified installation of Python , Django and pip.
   <img src="Python download.png">

python --version
pip --version

5. Package Managers:
   Verified pip installation with pip --version.
   <img src="Pip version.png" width="400px">

6. Database Configuration:
   Installed MySQL from MySQL Download.
   Development Environments and Virtualization, Mysql workbench also.

7. Extensions and Plugins:
   Installed VS Code extensions: Python, pylance, Numpy, Matplotlib, Python Image Preview, Pillow, Prettier, Material Icon theme.
   <img src="Python image preview.png">

8. GitHub Repository and sample project:
   I created a repository on GitHub.
   Initialized the repository in local project directory.
   Made the initial commit with a message.I created a gitignore file and added .vscode, virtualenv, env in my gitignore file.

## Reflection on Challenges Setting Up Developer Environment

Challenges Faced:

1. Issue with Python installation due to PATH not being set correctly. Resolved by reinstalling and ensuring the "Add Python to PATH" option was checked.

2. Difficulty in configuring Git with the correct email. Resolved by carefully following the documentation.

Strategies to Overcome Challenges:

1. Used online resources and forums to troubleshoot issues.
2. Referred to official documentation for accurate steps.

3. Disabled firewall and anti-virus at some point and enabled afterwards.
