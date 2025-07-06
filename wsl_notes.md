# WSL Notes

## Backup WSL

From powershell

`wsl --export Ubuntu E:\Archive\wsl_backup\ubuntu-20230402.tar`

## Import WSL

From powershell

`wsl --import Ubuntu D:\wsl\ D:\backup\ubuntu.tar`

## Set default User

By default Ubuntu will use root as the default user, to switch back to previous user
Go to the Ubuntu App Folder run command to set default user

```
cd %userprofile%\AppData\Local\Microsoft\WindowsApps
ubuntu config --default-user <username>
```