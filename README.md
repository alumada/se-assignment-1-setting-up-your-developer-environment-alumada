## Setting Up Your Developer Environment

### Objective
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

## Tasks and Instructions

### 1. Select Your Operating System (OS)

#### Step 1: Download and Install Windows 11
- Go to the [Windows 11 download page](https://www.microsoft.com/software-download/windows11).
- Click on "Download Now" and follow the on-screen instructions to install Windows 11.

### 2. Install a Text Editor or Integrated Development Environment (IDE)

#### Step 2: Download and Install Visual Studio Code
- Go to the [Visual Studio Code download page](https://code.visualstudio.com/Download).
- Choose the appropriate installer for your OS and follow the installation instructions.

### 3. Set Up Version Control System

#### Step 3: Install Git and Configure It
- Download Git from the [official Git website](https://git-scm.com/downloads).
- Follow the installation instructions for your operating system.
- Open Git Bash (or your preferred terminal) and configure Git with your details:
  ```sh
  git config --global user.name "Your Name"
  git config --global user.email "youremail@example.com"
  ```

#### Step 4: Create a GitHub Account
- Go to [GitHub](https://github.com) and sign up for an account if you don't already have one.

#### Step 5: Initialize a Git Repository
- Open Visual Studio Code.
- Open the terminal in Visual Studio Code (View > Terminal).
- Navigate to your project directory and initialize a Git repository:
  ```sh
  mkdir my-project
  cd my-project
  git init
  ```

### 4. Install Necessary Programming Languages and Runtimes

#### Step 6: Install Python
- Go to the [Python download page](https://www.python.org/downloads/).
- Download the latest version of Python and follow the installation instructions.
- Ensure Python is installed by running:
  ```sh
  python --version
  ```

### 5. Install Package Managers

#### Step 7: Install pip (Python Package Manager)
- pip is installed by default with Python. Ensure it's working by running:
  ```sh
  pip --version
  ```

### 6. Configure a Database (MySQL)

#### Step 8: Download and Install MySQL
- Go to the [MySQL download page](https://dev.mysql.com/downloads/windows/installer/5.7.html).
- Download the MySQL installer and follow the installation instructions.

### 7. Set Up Development Environments and Virtualization (Optional)

#### Step 9: Install Docker (Optional)
- Go to the [Docker download page](https://www.docker.com/products/docker-desktop).
- Download and install Docker Desktop.
- Verify the installation by running:
  ```sh
  docker --version
  ```

### 8. Explore Extensions and Plugins

#### Step 10: Install Extensions in Visual Studio Code
- Open Visual Studio Code.
- Go to the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window or by pressing `Ctrl+Shift+X`.
- Search for and install useful extensions like:
  - Python
  - GitLens
  - Docker
