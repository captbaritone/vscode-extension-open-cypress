# vscode-extension-open-cypress README
WIP: Allows you to open cypress specs

https://github.com/tnrich/vscode-extension-open-cypress

# Usage
### Running a single file
In a spec file open the cmd palette (cmd+p) and type "Run Cypress"
### Running a single it blockl 
In a spec file, place your cursor on an it() block line and open the cmd palette (cmd+p) and type "Run Cypress Single It Block"

# Todo: 
Eventually I'd like this extension to be able to 
- not just open but also be able to AUTOMATICALLY run a spec file (requires cypress team to add a way to make all specs run upon open or a single spec run on open)
- cypress team should add a way to grep to run a single it block IMO (that way the file itself doesn't need to be modified)


![cypressOpen](https://user-images.githubusercontent.com/2730609/63109187-764a4580-bf3d-11e9-9c6e-fbb5d1173737.gif)


