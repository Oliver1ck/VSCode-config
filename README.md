# VSCODE config
## Save extensions
```bash
code --list-extensions > extensions.txt
```
## install extensions in folder where location this file
```bash
foreach ($line in Get-Content extensions.txt) { code --install-extension $line }
```
