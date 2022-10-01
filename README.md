# simple_bootloader

This is a very basic bootloader that clears the boot info from the screen and prints a message using interrupts to trigger BIOS methods. It has been tested on QEMU with the Q35 chipset (`qemu-system-i386 -machine q35`) and you can compile using `nasm -f bin bootloader.asm`.
