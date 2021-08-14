## My first attempt at ASSEMBLY 

Since there is a WASM and WAT, guess I should know about  ASM 

```bash

BUILD : nasm -f macho64 hello_world.asm 

LINK  : ld -macosx_version_min 10.7.0 -lSystem -o hello_world hello_world.o 

RUN    : ./hello_world

```
