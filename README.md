[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15301681&assignment_repo_type=AssignmentRepo)

# Dev_Setup

Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

   To install windows 11:

   Step 1: Check System Requirements
   Processor: 1 GHz, 2+ cores, 64-bit
   RAM: 4 GB+
   Storage: 64 GB+
   Firmware: UEFI, Secure Boot capable
   TPM: Version 2.0
   Graphics: DirectX 12 compatible
   Display: >9” HD (720p)
   Internet: Required for updates

   Step 2: Back Up Your Data
   Ensure you back up important files before proceeding.

   Step 3: Download Installation Assistant
   Visit Windows 11 Download.
   Click "Download now" under Installation Assistant.

   Step 4: Run Installation Assistant
   Open the downloaded file.
   Follow on-screen prompts to install Windows 11.

   Step 5 (Optional): Create Installation Media
   On the same download page, click "Download now" under Media Creation Tool.
   Run the tool and create a USB or DVD installation media.

   Step 6: Install Windows 11
   For Installation Assistant, follow prompts to upgrade.
   For installation media, boot from USB/DVD and follow instructions.

   Step 7: Complete Setup
   Set up your region, keyboard, and account settings.
   Connect to a network and complete the setup.

   Step 8: Update Windows 11
   Go to Settings > Windows Update.
   Click "Check for updates".

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

   To install VS Code:

   Step 1: Download VS Code
   Open your web browser and go to the Visual Studio Code download page.
   Click the "Windows" button to download the installer.

   Step 2: Run the Installer
   Open the downloaded .exe file.
   Follow the on-screen prompts:
   Accept the license agreement.
   Choose the installation location.
   Select additional tasks (create a desktop icon, add to PATH, etc.).

   Step 3: Complete Installation
   Click "Install".
   Once the installation is complete, click "Finish" to launch Visual Studio Code.

   Step 4: First Launch and Extensions
   When VS Code opens, you can start setting up your workspace.
   To enhance functionality, install recommended extensions:
   Click the Extensions icon on the left sidebar or press Ctrl+Shift+X.
   Search for extensions like Python, GitLens, or others as needed.
   Click "Install" next to the desired extensions.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

To setup git and github:

Step 1: Install Git
Download Git: Go to the Git download page.
Run the Installer: Open the downloaded .exe file.
Follow Prompts:
Accept the license agreement.
Choose installation options (default settings are usually fine).

Step 2: Configure Git
Open Git Bash: This was installed along with Git.
Set Your Username:

git config --global user.name "Your Name"

Set Your Email:

git config --global user.email "your.email@example.com"

Step 3: Create a GitHub Account
Visit GitHub: Go to GitHub.
Sign Up: Fill out the sign-up form to create an account.

Step 4: Initialize a Git Repository
Create Project Directory:

mkdir my_project
cd my_project

Initialize Git:

git init
Create a README File:

echo "# My Project" > README.md
Add Files to Staging Area:

git add README.md
Make Your First Commit:

git commit -m "Initial commit"

Step 5: Push to GitHub
Create a New Repository on GitHub:
Go to GitHub, click the + icon in the top right, and select New repository.
Name your repository and click Create repository.
Push Local Repository to GitHub:

git remote add origin https://github.com/yourusername/my_project.git
git branch -M main
git push -u origin main

4. Install Necessary Programming Languages and Runtimes:
   Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

   To install python:

   Step 1: Download Python
   Visit the Python Website: Go to the Python download page.
   Download Installer: Click the "Download Python" button to download the latest version.

   Step 2: Run the Installer
   Open the Installer: Locate and open the downloaded .exe file.
   Select Options:
   Check the box: "Add Python to PATH".
   Click "Install Now".

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
