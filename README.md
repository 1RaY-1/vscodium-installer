# About

VSCodium istalled for Linux, Mac and Windows.

# Note
***Sometimes the commands to install Vscodium can be changed by the Devs, so at some point my script will become outdated.*** 

***And scince I don't monitor the commands (from the official site) that often, I would recommend first checking them, and after that only running my scripts.***

***I will eventually check and if needed, edit (update) my scripts.***

***My scripts just contain this official commands, plus a bunch of if's, functions and a switch case to make it all function correctly***

# Linux/Mac
On Linux or Mac you have to run 'install-vscodium.sh'.

It contains shell commands to install VSCodium from:
- https://vscodium.com

## Usage
```
bash install-vscodium.sh
```
After executing this script you'll have to:
1. Enter sudo password ( on linux only ).
2. confirm the installation.
3. Wait until the script will install vscodium.

# Windows
On Windows you have to run 'windows-install-vscodium.ps1' .

It installs VSCodium with choco package manager.

## Usage
First of all open PowerShell as administrator, then just type this:
```
.\windows-install-vscodium.ps1
```

# Also Note
If VSCodium isn't installing properly with this script, visit 'https://vscodium.com' and install it by your self.
