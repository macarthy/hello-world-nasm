## My first attempt at ASSEMBLY 

If there is a WASM, guess I should know about the ASM 

BUILD : nasm -f macho64 hello_world.asm 
LINK  : ld -macosx_version_min 10.7.0 -lSystem -o hello_world hello_world.o 
RUN    : ./hello_world
