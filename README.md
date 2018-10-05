# Jujube 
### __A Minimalist Text Editor__
Written entirely in C, this text editor supports opening, editing and saving files, 
syntax highlighting, and incremental search. 

Syntax highlighing currently only supports the C/C++ language, will be updated with other languages in the future. 

### __Steps to Run__
1. download jujube.c and the makefile
2. run `make` in the directory with jujube.c and the makefile
3. `./jujube.c` to open a new file, or `./jujube.c` [filename] to open an existing file.


## Changelog
v 1.0.1:
- Added Python and Ruby syntax highlighting.
- Included a sample .rb file where the new highlighting is demonstrated.

v 1.0:
- Initial upload
- fixed an issue where where opening a file after it had been saved would truncate the first line of the file. The culprit was a redundant getline() call in editorOpen() 