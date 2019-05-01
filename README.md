## Ghidra Sega Saturn Loader

A (WIP) loader and processor for Ghidra for Sega Saturn files. Currently able to:
- disassemble SH2 after manually specifying processor type. I used the instruction encodings availble from [Renesas SH Instruction Set Summary](http://shared-ptr.com/sh_insns.html) and related github project [shared-ptr/sh_insns](https://github.com/shared-ptr/sh_insns). 

Missing (basically everything else):
- P-code decompilation
- memory map
- automatic detection and loading of Sega Saturn files

## Screenshots

Loader screenshot  
![Loader](screenshot_loader.png)

Disassembly View (Decompiler not working yet)  
![Disassembly View](screenshot_loaded.png)

## Issues
I anticipate lots of bugs. 

## Installation
- Rename the root folder to SH2 and copy it to Ghidra/Processors/ and restart Ghidra

## Credits
- [shared-ptr/sh_insns](https://github.com/shared-ptr/sh_insns)
- [xyzz/ghidra-mep](https://github.com/xyzz/ghidra-mep)


