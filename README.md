# NASM Assembly Coursework

This repository contains projects / mini-projects for a NASM assembly course.

## Contents

## Prerequisites
To assembly and run the programs, you will need:
- NASM
- A Linux environment (or Windows with WSL) to execute the assembled binaries.
    - Alternatively, use an online compiler like [OnlineGDB](https://www.onlinegdb.com/) for testing.

## How to Assemble and Run
1. Assemble the .asm file using NASM: nasm -f elf32 -g -F dwarf file.asm
2. Link the object file to create an executable: ld -m elf_i386 file.o -o file
3. Run the executable: ./[file name]

## Alternatively, using 'build' script:
build file.asm  
Run KDBG:  
kdbg file
