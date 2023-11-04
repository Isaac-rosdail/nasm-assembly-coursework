# Building/Linking (w/debugging info):
  
nasm -f elf32 -g -F dwarf file.asm && ld -m elf_i386 file.o -o file

# Alternatively, using 'build' script:

build file.asm  

Run KDBG:  
kdbg file
