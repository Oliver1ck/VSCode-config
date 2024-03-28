# VSCODE config
## Save extensions
```bash
code --list-extensions > extensions.txt
```
## install extensions in folder where location this file win
```bash
foreach ($line in Get-Content extensions.txt) { code --install-extension $line }
```
## install extensions in folder where location this file LINUX
```bash
cat extensions.txt | xargs -L 1 code --install-extension
```
