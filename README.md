## Basic Steps to follow to setup the Project.

### Step 1: Python Version

Check the python version in your local machine. Below is the command to check the python version -

python --version

Make sure the python version is 3.9. If not, then please upgrade the python version 3.9.

### Step 2: Create a virtual environment 

Let's call our virtual environment "env". Below is the command to create the virtual environment - 

python -m venv ./env

### Step 3: Activating the virtual environment

For Linux/MacOs:

source ./env/bin/activate

For Windows:

Command Prompt (cmd.exe) - .\env\Scripts\activate.bat
Powershell - .\env\Scripts\Activate.ps1

### Step 4: Installing the required packages

#### -> Upgrade the pip first. 

The command to upgrade pip is - 

python -m pip install --upgrade pip

If your machine doesn't have pip, then install it first. Here is the link that will help you in installing the pip. https://pip.pypa.io/en/stable/installation/

#### -> Install the packages.

Running the following command will install all the required packages in your virtual environment.

pip install -r requirements.txt





