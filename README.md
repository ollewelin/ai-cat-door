# ai-cat-door
Deep learning cat door auto lock cat with prey

## Step 1. Installation guide for Windows for re-training (fine tune) you own cat door model. 
NOTE: If you running Linux (Ubuntu) skip WSL jump directly to Install Ananconda
### Install WSL on you windows machine
1.1. Open PowerShell as Administrator:

1.2. Right-click on the Start button and select Windows PowerShell (Admin).

1.3. Install WSL

```
wsl --install
```
This command will enable the necessary features and install the default Linux distribution (usually Ubuntu). Your PC will need to restart.

1.3. Set Up Your Linux Distribution:
After restarting, open the Linux distribution from the Start menu and follow the on-screen instructions to set up your Linux user account.

Example
```
PS C:\Users\olle_> wsl --install
The requested operation requires elevation.
Installing: Virtual Machine Platform
Virtual Machine Platform has been installed.
Installing: Windows Subsystem for Linux
Windows Subsystem for Linux has been installed.
Installing: Ubuntu
Ubuntu has been installed.
The requested operation is successful. Changes will not be effective until the system is rebooted.
PS C:\Users\olle_>
```

## Step 2. Install Anaconda
### Download Anaconda
Open your Linux terminal and download the Anaconda installer with:
```
wget https://repo.anaconda.com/archive/Anaconda3-2023.07-Linux-x86_64.sh
```

### Install Anaconda:
Run the installer:
```
bash Anaconda3-2023.07-Linux-x86_64.sh
```
Follow the prompts to complete the installation. You may need to restart your terminal or source your .bashrc file:
```
source ~/.bashrc
```

## Step 3: Set Up a Conda Environment for PyTorch
### 3.1 Create a New Conda Environment:
In your terminal, create a new environment:
```
conda create --name pytorch_env python=3.8
```
Activate the environment:
```
conda activate pytorch_env
```
### 3.2 Install PyTorch:



