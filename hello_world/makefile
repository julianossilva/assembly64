#makefile for hello.asm

hello: hello.o
	gcc -o hello.bin hello.o -no-pie
hello.o: hello.asm
	nasm -f elf64 -g -F dwarf hello.asm -l hello.lst
