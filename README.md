
# Setup your dev environment

## Install the Chocolatey package manager

### Requirements
  - Windows 7+ / Windows Server 2003+
  - PowerShell v2+ (not PowerShell Core yet though)
  - .NET Framework 4+ (the installation will attempt to install .NET 4.0 if you do not have it installed)

### Instructions
Follow the installation instructions found [here](https://chocolatey.org/install)


## Install packages using Chocolatey
1. Download the contents of this repo (click code on the upper right, then download ZIP)
2. Create a folder in your home directory (your user folder) and name it `dev`
3. Unpack the ZIP in the `dev` folder
4. Open your PowerShell terminal as an admin (you can search for PowerShell in the start menu and click on the 'Run as Administrator' option)
5. Type `cd ~/dev/windows-setup-script-master`
6. Type `choco install packages.config`
7. Everything will be installed properly 🤞
8. You will be required to restart you computer for WSL2 to be installed fully
