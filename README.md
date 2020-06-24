# Choco Auto Installer
Powershell script that automatically installs chocolatey packages mentioned in `packages.txt`.

Before running the script, execute the following command in powershell to allow the script to execute:

`Set-ExecutionPolicy Unrestriced`

You may change it later after running the script:

`Set-ExecutionPolicy AllSigned`

The official package names must be written in the following way in `packages.txt`:

```txt
firefox
vscode
git
zoom
```
