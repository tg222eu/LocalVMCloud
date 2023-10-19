# LocalVMCloud

Prerequisit: Registered Azure account

This guide will upload a VM thats either already installed or new deployment

The process is Prepare local VHD - > Upload to Azure blob storage -> Convert to Imanaged image -> Deploy a VM

Prepare local VHD

We are going to use sysprep. Sysprep will clean the machine from unique characteristics, like host name, OS activation status, TCP/IP configuration. Its a crucial step for preparing a image file

Run command in cmd: C:\windows\system32\sysprep\sysprep.exe
Choose OOBE, Generalize and shutdown
