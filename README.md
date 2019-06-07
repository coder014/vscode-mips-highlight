# RISC-V Support

This project is copied and adapted from [MIPS Support](https://github.com/kdarkhan/vscode-mips-support)

## Features
This VSCode extension provides basic RISC-V colorization and snippets support.

### Colors

![colors](images/vscode-riscv-colors.png)

#### Supported
- RV32GC and RV64GC syntax highlight (G = IMAFD)
- Assembler directives
- Preprocessors like `#include` and `#define`
- Comments: `#`, `//` and `/* */`


### Snippets

~The extension is based on Textmate's [MIPS bundle](https://github.com/textmate/mips.tmbundle)~

## Release Notes

### 0.0.6

* Add more instructions (C extensions)
* Fix block comment
* Add preprocessor support

### 0.0.5

* Add more instructions (A/F/D extensions and 64-bit instructions)
* Add assembler directives described in https://rv8.io/asm.html

### 0.0.4

* Add more instructions
* Update Logo
* Add demo image

### 0.0.3

* Branches into RISC-V

### 0.0.2

* Add syntax for singly-quoted characters
* Switch svg logo to png

### 0.0.1

* Initial release
