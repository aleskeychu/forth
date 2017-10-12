# Forth interpreter
Project as part of ITMO courseware
# Compiling and running
```
nasm -felf64 -g forth.asm -o forth.o
ld -o forth forth.o
chmod +x forth
./forth
```