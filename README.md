# Linux Inside

[Linux Inside](https://0xax.gitbooks.io/linux-insides/content/)

## Setup

```
sudo apt install --yes nasm
```

## Compile

```
nasm -f elf64 -o hello.o hello.asm
ld -o hello hello.o
```
