# Win10-Purge
Synaxis

this project is made to improve and fix many issues in windows 10 
so we can have a stable and simple system like windows 7 

**There is no undo**

## Execution

Open PowerShell:

   ``Set-ExecutionPolicy -Scope CurrentUser Unrestricted ``

Unblock PowerShell scripts and modules within this directory:

    `` ls -Recurse *.ps1 | Unblock-File ``
     ``ls -Recurse *.psm1 | Unblock-File ``

## How to use

1. Edit the scripts to fit your need.(remember there is no Undo!)

2. Hit WindowsKey type PowerShell -> rightMouse button -> open as Administrator

3. go to scripts folder -> right mouse button -> properties -> copy the local path
In Powershell type -> cd C:\Users\YOURNAME\Downloads\Win10-Purge-master\scripts

4. type in   Set-ExecutionPolicy -Scope CurrentUser Unrestricted    -> to enable running external scripts

5. Type ls -Recurse *.ps1 | Unblock-File then    THEN    ls -Recurse *.psm1 | Unblock-File

6. You can now run the scripts with ``./`` example: ``./defaultApps`` (no backsticks)

7.Customize your scripts!

8. Enjoy! Share your improvements! 

9. Credtis to WarHawk


## Old Classic StartMenu

[Start is Back]: <http://startisback.com/>

This is a rework project from https://github.com/W4RH4WK/Debloat-Windows-10/ thank you!

## Liability

**All scripts are provided as is . Use them at your own risk.**
