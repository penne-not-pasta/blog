+++
date = '2025-11-17'
draft = false
title = 'Making My Own OS'
author = 'Penelope (Penne)'
tags = ['2025', 'Updates', 'OS Dev', 'C/C++', 'Penny-DOS']
+++

# Hello, World.

Hey guys, Penne here! Today I'm going through the basics of making my own DOS! Without further ado, lets begin. 

I do want to not if you are not me and you happen to be reading this this more like notes for me lmao.

*post 1 of many posts*

---

## Requirements.

To make a DOS based OS you will need quite a bit of stuff. Let me make that list below.

1. A Computer, To code on. (**REQUIRED.**)
    - preferably running Linux, windows WSL/macOS is okay too, however this project is made from Debian 13 Trixie.
    - optionally another computer to use as the test machine. (**optional.**)
    - USB stick (**optional.**)
2. A virtual machine, if you dont want to use actual hardware. (**REQUIRED.**)
    - The VM needs at minimum 512 MB of ram, & input/output abilities. I am using QEMU but you do not need that one, use what you are comfortable with.
3. Knowledge in C (**REQUIRED.**)
4. Knowledge in Assembly + NASM (**REQUIRED.**)
5. GCC knowlege (**REQUIRED.**)
6. a terminal. (**REQUIRED.**)
    - I use Konsole, however you can use any terminal.
7. Basic terminal knowledge. (**REQUIRED.**)
8. Git(Hub) knowledge (**optional.**)
    - Only if you want to publish to github.

---

## Notes for author.

---

### Commands Masterlist.

Some basic commands you will need to run: (updated when i feel like updating it lol.)

```bash
# BASH
~$ cd Documents
/Documents$ git clone https://github.com/penne-not-pasta/penny-dos.git # clones to current working directory.
/Documents$ cd penny-dos
# commands to run in Penny-DOS directory.
/Documents/penny-dos$ make all # builds the project.
/Documents/penny-dos$ make clean # cleans up the build.
/Documents/penny-dos$ qemu-system-x86_64 -hda ./src/bin/boot.bin # runs in QEMU.
```