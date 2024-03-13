# VSCODE config
## Save extionsions
```bash
code --list-extensions > extensions.txt
```
## install extensions in folder where location this file
```bash
cat extensions.txt | xargs -L 1 code --install-extension 
```
