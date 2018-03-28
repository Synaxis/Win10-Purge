# Win10-Purge
Synaxis
EDIT: This cause issues in build 1803 or newer , we will fix later

This project is made to improve and fix many issues in Windows 10(Bloatware;Telemetry;Privacy;DefaultApps) 

so we can have a stable and simple system like windows 7 
**There is no undo**
## How to use

1. Edit the scripts to fit your need.(remember there is no Undo!)

2. Hit WindowsKey type PowerShell -> rightMouse button -> open as Administrator

3. go to scripts folder -> right mouse button -> properties -> copy the local path
In Powershell type -> cd C:\Users\YOURNAME\Downloads\Win10-Purge-master\scripts

4. Execution
Open PowerShell(inside the scripts folder) :

    ``  Set-ExecutionPolicy -Scope CurrentUser Unrestricted   ``
    ``   ls -Recurse *.ps1 | Unblock-File    ``
    ``   ls -Recurse *.psm1 | Unblock-File    ``

6. Now you can run the scripts with ``./`` example: ``./defaultApps`` (no backsticks)

7. Enjoy! Share your improvements!

## FIX START MENU

[Start is Back]: <http://startisback.com/>

This is a rework project from https://github.com/W4RH4WK/Debloat-Windows-10/ Thank you!
