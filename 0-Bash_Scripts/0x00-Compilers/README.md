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
