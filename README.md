[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15282676&assignment_repo_type=AssignmentRepo)
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

--- ANSWERS ---
- WINDOWS 10 INSTALLATION

1. **Prepare Installation Media:**
   - Download the Windows 10 Installation Media Creation Tool from Microsoft's website.
   - Create a bootable USB drive using Rufus

2. **Boot from Installation Media:**
   - Insert the bootable USB drive.
   - Restart your computer and enter BIOS/UEFI settings to set the USB drive.

3. **Install Windows 10:**
   - Follow the on-screen prompts to install Windows 10, choosing your language, time, and keyboard preferences.
   - Enter your product key if necessary when prompted and select the installation partition.

4. **Complete Setup:**
   - Follow the prompts to personalize settings, create a user account, and connect to a network.
   - Windows will finalize installation, restart several times, and prompt for updates.

5. **Driver Installation and Updates:**
   - Install necessary drivers for hardware components if not automatically done by Windows Update.
   - Check for and install any pending updates.

6. **Finish:**
   - Customize your desktop and settings as needed.
   - Restore backed-up files from external storage.

- Installing Visual Studio Text Editor

**Download Visual Studio:**
Visit the Visual Studio website and click on "Download Visual Studio."
Follow the on-screen instructions to download the installer.
**Run the Installer:**
Run the downloaded installer.
Choose the "Visual Studio" workload during installation, which includes the necessary components for general development.
**Select Workloads and Components:**
In the Visual Studio Installer, select the workloads and components you need based on your development requirements. Common workloads include ".NET Desktop Development" or "Web Development."
**Install:**
Click the "Install" button to start the installation process.
This may take some time, as it involves downloading and installing the selected components.
**Launch Visual Studio:**
Once the installation is complete, launch Visual Studio.
**Start Coding:**

- Installing Git
Sure, here's a step-by-step guide to install Git, configure it, initialize a Git repository for your project, and make your first commit:

### Install Git and Configure it:

1. **Download Git:**
   - Visit the official Git website
   - Download the installer for Windows(my OS)

2. **Install Git:**
   - Run the downloaded installer.
   - Follow the installation wizard instructions, leaving default settings unless you have specific preferences.

3. **Configure Git:**
   - Open a terminal or command prompt.
   - Set your username and email address for Git (use the email associated with Github):
     ```
     git config --global user.name "Your Name"
     git config --global user.email "your.email@example.com"
     ```

4. **Verify Git Installation:**
   - To verify that Git has been installed correctly, run:
     ```
     git --version
     ```
   - This command should display the installed Git version.

### Initialize a Git Repository and Make Your First Commit:

5. **Navigate to Your Project Directory:**
   - Open a terminal or command prompt.
   - Change directory (`cd`) to your project folder where you want to initialize the Git repository.

6. **Initialize Git Repository:**
   - Inside your project directory, initialize a new Git repository:
     ```
     git init
     ```
   - This command initializes a new Git repository in the current directory.

7. **Add Files to the Staging Area:**
   - Add your project files to the Git staging area to track changes:
     ```
     git add .
     ```
   - The `.` adds all files. You can specify individual files by replacing `.` with their names.

8. **Commit Your Changes:**
   - Commit the added files with a descriptive message:
     ```
     git commit -m "Initial commit"
     ```
   - Replace `"Initial commit"` with a meaningful message describing your changes.

9. **Set Up Remote Repository (Optional):**
   - If you want to push your repository to GitHub, follow their instructions to create a new repository and connect it to your local Git repository.

10. **Push Changes to Remote (Optional):**
    - If you have set up a remote repository, push your committed changes to it:
      ```
      git push origin master
      ```
    - Replace `origin` with your remote's name (if different) and `master` with your branch name.
 - Below is the link to my repository showing my first commit
 https://github.com/Powerlearnproject/se-assignment-2-introduction-to-software-engineering-sndili.git

 - Installing Python on Windows:
**Download Python Installer:**
Visit the official Python website: 
Navigate to the Downloads section and click on "Download Python(depending on latest version)
**Run Python Installer:**
Once the installer is downloaded, double-click to run it.
Important: Check the box that says "Add Python X.X to PATH" during the installation setup. This ensures Python is added to your system PATH, making it easier to run Python from the command line.
**Install Python:**
Click on "Install Now" to begin the installation process.
The installer will extract and install Python on your system. This may take a few minutes.
**Verify Installation:**
Once the installation is complete, open a command prompt:
Press Win + R, type cmd, and press Enter.
In the command prompt, type:
python --version
This command should display the installed Python version. 

- Installing pip package manager on Windows
**Download get-pip.py Script:**
Open a web browser and go to the get-pip.py page.
Right-click on the page and select "Save As" to download the get-pip.py script to your computer.
**Open Command Prompt:**
Press Win + R, type cmd, and press Enter to open the Command Prompt.
**Navigate to the Directory:**
Use the cd command to navigate to the directory where you downloaded get-pip.py.
bash
cd path\to\directory
Replace path\to\directory with the actual path where get-pip.py is located.
**Install pip:**
In the Command Prompt, run the following command to install pip:
python get-pip.py
This command will execute the get-pip.py script and install pip along with setuptools and wheel.
**Verify pip Installation:**
After the installation is complete, verify pip installation by checking its version:
pip --version
This command should display the installed pip version.

- Setting Up a Virtual Environment:
**Install virtualenv using pip:**
pip install virtualenv
**Create a Virtual Environment:**
**Navigate to your project directory in the command prompt:**
cd path\to\your\project
**Create a new virtual environment:**
virtualenv venv
Replace venv with your preferred environment name.
**Activate the Virtual Environment:**
On Windows, in the command prompt within your project directory:
venv\Scripts\activate
Your command prompt will now show the active virtual environment name.
**Deactivate the Virtual Environment:**
To deactivate the virtual environment and return to the global Python environment, simply type:
deactivate

- Installing and configuring MySQL on Windows
Installing MySQL on Windows involves several steps to ensure it's properly configured and ready to use. Here's a detailed step-by-step procedure:

### Installing MySQL on Windows:

1. **Download MySQL Installer:**
   - Visit the MySQL Community Downloads page: 
   - Select the MySQL Community Server edition for Windows 

2. **Run MySQL Installer:**
   - Once the installer is downloaded, double-click to run it.
   - Select "Developer Default" or "Server only" setup type. "Developer Default" includes MySQL Server, MySQL Workbench, and other tools.
   - Click "Next" to proceed.

3. **Choose Setup Type:**
   - Select "Standalone MySQL Server / Classic MySQL Replication" and click "Next".
   - Optionally, you can choose to customize the setup by selecting specific MySQL products and features. Click "Next" to continue.

4. **Installation:**
   - The installer will download and install MySQL and other selected components.
   - During installation, you will be prompted to configure MySQL Server. Choose a strong root password for the MySQL root user.
   - Click "Next" to proceed with the installation.

5. **Configure MySQL Server:**
   - Choose "Standalone MySQL Server / Classic MySQL Replication" and click "Next".
   - Configure MySQL Server as a Windows Service. You can also set it to start automatically or manually. Click "Next" to continue.

6. **Apply Configuration:**
   - Review the configuration summary and click "Execute" to apply the configuration settings.
   - The installer will configure MySQL Server and create necessary directories.

7. **Complete Installation:**
   - Once the configuration is applied successfully, click "Finish" to complete the installation process.

8. **Verify MySQL Installation:**
   - Open MySQL Workbench from the Start Menu or desktop shortcut.
   - Connect to the MySQL Server using the root account and the password you set during installation.

-- Challenges encountered
- It was very difficult to install mysql. I had to manually install mysql workbench. Also I had to go through the steps twice and change the port.




