# NVM installation

We recommend setting up Node Version Manager to be able to switch vertions for various projects

## NVM on Windows 10 or 11
Follow [Node JS on Windows](https://docs.microsoft.com/en-us/windows/dev-environment/javascript/nodejs-on-windows) document. To run nvm under your user account you can change the defaults with the follow:
- Select an installation folder in your regular user profile (not the admin user profile). For example ```C:\Users\{User}\AppData\Roaming\npm```.
- Set up the links folder in your regular user profile (not the system path). For example ```C:\Users\{User}\AppData\Roaming\nodejs```.
- Add the installation and the links folders to your user path and restart. 
- Open a powershell as user and test by listing installed versions (should be empty for initial install)
```
nvm ls
```

## Mac OS X
Contributors needed. Create a pull request to suggest cotent.

## Linux 
Contributors needed. Create a pull request to suggest content.

# Node JS Installation

We will install and use Long Term Support (LTS) version for Node JS using NVM.
```
nvm list available
nvm install lts (on windows)
nvm install --lts (on linux or WSL)
```
