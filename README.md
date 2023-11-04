# nasm-assembly-coursework

Build & Assemble (w/ debugging info):
nasm -f elf32 -g -F dwarf file.asm

Link normally:
ld -m elf_i386 file.o -o file

Run KDBG:
kdbg file
