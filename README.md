# Linux-Boot-Process

NASM is used as the Assembler to run the asm file. 

For simulation of the built OS, qemu is used.

Now, once all the required dependencies are installed, the simulation can be started with the command

`make && qemu-system-i386 -fda build/main_floppy.img`



![image](https://user-images.githubusercontent.com/62979769/166200149-8f71dbcf-d8a6-4a5a-91ff-41f7ead131f6.png)
