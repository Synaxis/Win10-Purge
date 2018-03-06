# Win10-Purge
Synaxis

this project is made to improve and fix many issues in windows 10 
so we can have a stable and simple system like windows 7 

**There is no undo**

## Execution

Open PowerShell:

   Set-ExecutionPolicy -Scope CurrentUser Unrestricted

Unblock PowerShell scripts and modules within this directory:

    ls -Recurse *.ps1 | Unblock-File
    ls -Recurse *.psm1 | Unblock-File

## How to use

1. Edit the scripts to fit your need.
2. Open PowerShell as Administrator 
3. Change directory to the path cd  C:\Users\YOURNAME\Downloads\Win10-Purge-master  
4. Restart Computer

## Startmenu

[Start is Back]: <http://startisback.com/>

### XBox Wireless Adapter

Apprently running the stock `remove-default-apps` script will cause XBox
Wireless Adapters to stop functioning. I suspenc one should not remove the XBox
App when wanting to use one. But I haven't confirmed this yet, and there is a
workaround to re-enable it afterwards. See
[#78](https://github.com/W4RH4WK/Debloat-Windows-10/issues/78).

## Liability

**All scripts are provided as is . Use them at your own risk.**
