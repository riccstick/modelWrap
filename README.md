# modelWrap
wrapper for automatized homology modeling of multiple number of sequences on one template structure using "modeller_9.x"
# Requirements
- [modeller_9.x](https://salilab.org/modeller/download_installation.html)
- python3 *(modeller is also executable without installed python3, however this has to be changed in the script (python3 <-> mod9.x))*
# Installation
Bash script, just make it executable and run
## SourceCode compiling with Argbash - argument parser generator
template file can be changed and converted to executable code (tested with argbash_2.8.1; Ubuntu_16.04)

`argbash modelWrap_template -o modelWrap`
