# Oldest-Linux-Ever
 Linux Initial Version With Minimal Running Environment.

## Introdution ##

Linux 0.01 is the first release of Linux kernel，It is only around 5900 lines of ANSI C, 2500 lines of C headers and 1450 lines of i386 assembler.
http://www.oldlinux.org/Linux.old/docs/history/Master.html

This is a good start of leaning Linux kernel.

This git repository contains two branches :-

Original branch which i pulled original source code  [linux-0.01.tar.gz](https://www.kernel.org/pub/linux/kernel/Historic/linux-0.01.tar.gz "linux-0.01.tar.gz").

And This Main branch which i had compilable patched kernel ver 0.01 [Linux 0.01 remake](http://draconux.free.fr/os_dev/linux0.01.html "Linux 0.01 remake").
Thanks to @Abdel Benamrouche

## Running Linux 0.01 ##

This is compliable Patched version of First Kernel ever Linux 0.01.

It can be compiled with GCC on machines with Ubuntu 18.04/20.04 64 and 32 bit versions on Intel/AMD.

I uploaded updated bochsrc.bxrc so can be run in latest bochs emulator ver 2.7

I also uploaded compiled Image of [Linux 0.01.img](https://github.com/Retro-Linux/Oldest-Linux-Ever/releases/download/0.01/Linux.0.01.img.zip).

With Minimal working filesystem for Linux 0.01 [Minimal_FS.img](https://github.com/Retro-Linux/Oldest-Linux-Ever/releases/download/0.01/Minimal_FS.zip).

## Usage ##

Download Source Code [Oldest Linux Ever](https://github.com/Retro-Linux/Oldest-Linux-Ever.git).

Build the Source code $make

## Running ## 

Unzip [Images](https://github.com/Retro-Linux/Oldest-Linux-Ever/releases/latest).

Run Bochs with bochsrc.bxrc and VOILAAA!

## Tutorial ##

https://www.youtube.com/watch?v=9ccU0SFKGHs

![Screenshot 2023-03-11 010329](https://user-images.githubusercontent.com/117750238/224467107-6dc44806-7daf-4c7a-b12f-a966c7fcde69.png)


## Notes ##

For more modern code there is Isoux fork of Linux-0.01 is compilable using NASM assembler and LLVM's Clang compiler with a few more changes

https://github.com/isoux/linux-0.01

## Thanks to ##

[isoux](https://github.com/isoux).
[mariuz](https://github.com/mariuz).
