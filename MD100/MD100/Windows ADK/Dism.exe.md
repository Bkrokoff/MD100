# DISM.EXE

Deployment Image Servicing and Management (DISM.exe) is a command-line tool that can be used to service and prepare Windows images, including those used for Windows PE, Windows Recovery Environment (Windows RE) and Windows Setup. DISM can be used to service a Windows image (.wim) or a virtual hard disk (.vhd or .vhdx).

DISM appears in Windows ADK installations in the `C:\Program Files (x86)\Windows Kits\<version>\Assessment and Deployment Kit\Deployment Tools\10\DISM` folder.

DISM Check Health Command (This will not fix any corruption, but it will report if there was one)
>Dism /Online /Cleanup-Image /CheckHealth

DISM Scan Health Command
>Dism /Online /Cleanup-Image /ScanHealth

DISM Restore Health Command
>Dism /Online /Cleanup-Image /RestoreHealth

Mount a WinPE Image
>Dism /Mount-Image /ImageFile:"C:\WinPE_amd64\media\sources\boot.wim" /index:1 /MountDir:"C:\WinPE_amd64\mount"
- Mounts the WinPE image to a temporary location on your PC

Unmount WinPE Image
>Dism /Unmount-Image /MountDir:"C:\WinPE_amd64\mount" /commit

Mounting - Before your computer can use any kind of storage device (such as a hard drive, CD-ROM, or network share), you or your operating system must make it accessible through the computer's file system. This process is called mounting. You can only access files on mounted media

