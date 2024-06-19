[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15285921&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
  1. CHECK FOR COMPATIBILITY
Windows 11 won’t work for every PC. At a minimum, your device must have the following specs:
64-bit processor with at least 2 cores and 1 GHz processing speed, 4GB RAM ,64GB storage space (in addition to the space for the operating system installation software), DirectX 12 or later graphics card with WDDM 2.0 driver, A high-def display of 720p,, TPM 2.0, Secure Boot-capable UEFI firmware
Can you still install Windows via USB if your PC isn't compatible? Possibly. You may still be able to download and install it on a computer that doesn't meet all of these requirements, but your experience may not be satisfactory.
2. CHECK YOUR DEVICE FOR AVAILABLE MEMORY
 You'll need at least 5.1GB of extra storage space on all of the devices involved in this process because that’s the Windows 11 ISO file size.You need 5.1GB free on the computer you’re downloading the file to, the USB drive, and the computer on which you’re installing the operating system. 
3. DOWNLOAD THE ISO FILE TO YOUR DEVICE (ANOTHER DEVICE)
Unlike prior versions of Microsoft Windows, you don’t need to sign in to your Microsoft account to download the ISO file. Just follow these steps:
Visit the Windows 11 product download page,Navigate to the Create Windows 11 installation media link, and click Download Now.,The download for the Media Creation Tool will begin.
Once the tool downloads, double-click on the file in your download and run it. You may be asked for permission to run the program, so go ahead and approve it.
Now that you have the Media Creation Tool running, follow the directions to download the ISO file (the file used to install Windows 11) to your device. Make sure you select USB Flash Drive when prompted to download the file directly to your USB drive and format it properly for installation later.
4. REMOVE THE USB
When you receive a notification that the file transfer is finished, use the "eject" function on your USB utility to prepare it for removal before you pull it out of the computer.
5. RUN WINDOWS 11 FROM A USB
Plug the USB drive into the computer and restart the computer.
Before the computer fully turns back on, hold the F8 key. The exact command will depend on your computer. Note: You must do this before the Windows or manufacturer's brand logo appears on your screen. If you see the logo, you waited too long and must restart again.
When prompted, choose the boot order and select the USB drive option as first. You’ll then be told to press any key to continue booting from your specified location.
Your computer should start up as normal, but with Windows 11 prepared to install and run at the startup screen.

3. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
   Download the Visual Studio Code installer for Windows.
Once it is downloaded, run the installer (VSCodeUserSetup-{version}.exe). This will only take a minute.
By default, VS Code is installed under C:\Users\{Username}\AppData\Local\Programs\Microsoft VS Code
5. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
   Initializing a Git repository
Open TerminalTerminalGit Bash.
Navigate to the root directory of your project.
Initialize the local directory as a Git repository. By default, the initial branch is called main . ...
Add the files in your new local repository
Commit the files that you've staged in your local repository.

7. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
Installation on Windows
Visit the link https://www.python.org/downloads to download the latest release ofPython. In this process, we will install Python 3.8.6 on ourWindows operating system. When we click on the above link, it will bring us the following page.
Step - 1: Select the Python's version to download.
Step - 2: Click on the Install Now, Double-click the executable file, which is downloaded;
, the following window will open.Select Customize installation and proceed.
Click on the Add Path check box, it will set the Python path automatically.
We can also click on the customize installation to choose desired location and features. Other important thing is install launcher for the all user must be checked.
Step - 3 Installation in Process
Now, try to run python on the command prompt. Type the command python -version in case of python3.

9. Install Package Managers:
   If applicable, install package managers like pip (Python).
  If you installed Python from source, with an installer from python.org, or via Homebrew you should already have pip. If you’re on Linux and installed using your OS package manager, you may have to install pip separately, see Installing pip/setuptools/wheel with Linux Package Managers.
If pip isn’t already installed, then first try to bootstrap it from the standard library: 
Ensure you can run Python from the command line
Before you go any further, make sure you have Python and that the expected version is available from your command line
Securely Download get-pip.py [1]
Run python get-pip.py . This will install or upgrade pip. Additionally, it will install Setuptools and wheel if they're not installed already. 

11. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
Step 1: Go to the official website of MySQL and download the community server edition software. Here, you will see the option to choose the Operating System, such as Windows.
Step 2: Next, there are two options available to download the setup. Choose the version number for the MySQL community server.
After downloading the setup, unzip it anywhere and double click the MSI installer .exe file.
In the next wizard, choose the Setup Type. There are several types available, and you need to choose the appropriate option to install MySQL product and features. Here, we are going to select the Full option and click on the Next button
Once we click on the Next button, it may give information about some features that may fail to install on your system due to a lack of requirements. We can resolve them by clicking on the Execute button that will install all requirements automatically or can skip them
 In the next wizard, we will see a dialog box that asks for our confirmation of a few products not getting installed. Here, we have to click on the Yes button.After clicking on the Yes button, we will see the list of the products which are going to be installed. So, if we need all products, click on the Execute button.

13. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
Benefits Of Virtual Machines
Isolation And Security: VMs provide strong isolation by running the applications on fully virtual Separate Operating Systems on a single physical machine. Isolation provides security for the applications in the environments.
Versatility And Compatibility: VM comes with supporting various operating systems allowing for a wide range of applications to run on the same physical hardware. Its versatility makes it suitable for hosting multiple applications as per their specified environments.
Snapshots And Rollbacks: Virtual machines facilitate taking snapshots and capturing the complete state of the VM at a specific point in time. It provides the facility for the users to roll back their known and required states in case of updates or any issues.
Resource Optimization: Virtualization provides efficient allocation and utilization of resources providing dynamic configuration of hardware resources such as RAM, CPU, and Storage for specific amounts. Its flexibility enhances resource management and scalability in virtualized environments.
Lightweight Isolation Is Sufficient: Docker is effective in situations where lightweight process isolation is sufficient. It is effective in usage with microservices architectures and for efficient containerized applications with minimal overhead.
Fast Deployment And Scaling: Docker containers will start the applications quickly, making them suitable for dynamic environments that require rapid deployment and scaling.
Consistent Development And Deployment: Docker provides consistency between development and deployment environments for applications. It ensures that applications behave in the same way across different stages of the development lifecycle.
2. Use The Virtual Machines In The Following Cases
Fully Operating System Isolation Is Required: If your application needs complete isolation as separate operating systems, then Virtual Machines are the preferable choice. VM provides a stronger isolation, making it suitable for applications to run on diverse OS requirements.
Legacy Applications And Compatability: VMs are preferable for hosting legacy type of applications that can’t be containerized easily. They support a wide range of Operating Systems making the applications compatible with specific OS versions and configurations.
Resource-Intensive Workloads: VM can be used in scenarios where there is a need for intensive computations for workloads, we can go for VM for having granular control over the resource allocations and making them better suited for the cases.
Conclusion
14. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
1. Visual Studio Code (VSCode)
2. Stackblitz
3. Sublime Text
4. JetBrains PyCharm
5. Notepad++

15. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process.
    Select your operating system: Selecting your operating system is the first step.  on personal taste, the majority of software development environments are compatible with Windows.
Decide on an IDE (integrated development environment): Setting up a software development environment requires choosing an IDE, which is a software programme for developing, testing, and debugging. IDEs that i have  well-liked Visual Studio Code.
Install the required software and packages: Installing the software development tools and packages required for your project is the next step. Compilers\extention, debuggers, programming languages like Python, and version control systems like Git can all fall under this category.

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
