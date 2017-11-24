# Setup Guide

* Install Atom Editor
* clone this repository
* backup and move/delete your existing atom config folder (typically found at ~/.atom)
* rename this cloned project folder to .atom and move it to your atom config location

## Font Setup

* install Fira Code https://github.com/tonsky/FiraCode#download-fira-code-v1102--follow-updates--firacode
* if you do not want to use Fira, click the top menu *Atom*, then *Stylesheet...* and remove the following lines:

   `// global font and ligatures`  
   `atom-workspace,`  
   `atom-text-editor {`  
   `  font-family: "Fira Code";`
   `  text-rendering: optimizeLegibility;`  
   `}`
