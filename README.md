# ai-cat-door
Deep learning cat door auto lock cat with prey

## Installation guide for Windows for re-training (fine tune) you own cat door model.
### Install WSL on you windows machine
1. Open PowerShell as Administrator:

2. Right-click on the Start button and select Windows PowerShell (Admin).

3. Install WSL

```
wsl --install
```
This command will enable the necessary features and install the default Linux distribution (usually Ubuntu). Your PC will need to restart.

3. Set Up Your Linux Distribution:
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

### Install Anaconda
#### Download Anaconda
Open your Linux terminal and download the Anaconda installer with:
```
wget https://repo.anaconda.com/archive/Anaconda3-2023.07-Linux-x86_64.sh
```

#### Install Anaconda:
Run the installer:
```
bash Anaconda3-2023.07-Linux-x86_64.sh
```


