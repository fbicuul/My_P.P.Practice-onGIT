COMPILER ///////////////////////
Script that compiles a C file but does not link
#!/bin/bash
gcc -c $CFILE


ASSEMBLER //////////////////////
Script that generates the assembly code of a C code
#!/bin/bash
gcc -S $CFILE


NAMING ///////////////////////
Script that compiles a C file and creates an executable named cisfun
#!/bin/bash
gcc -o cisfun $CFILE

GCC stands for “GNU Compiler Collection”. GCC is an integrated distribution of compilers for several major programming languages. These languages currently include C, C++, Objective-C, Objective-C++, Fortran, Ada, D, and Go.

It is a compiler system for the various programming languages. It is mainly used to compile the C and C++ programs. It takes the name of the source program as a necessary argument; rest arguments are optional such as debugging, warning, object file, and linking libraries. GCC is a core component of the GNU toolchain.

GCC - C
G++ - C++
