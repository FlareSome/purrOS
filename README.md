# purrOS

Trying to build an OS from scratch in x86 assembly.

## What I'm Doing

Learning low-level systems programming by building a bootloader that can boot and display text.

## Build & Run

```bash
# Prerequisites
sudo apt update
sudo apt install nasm qemu-system-x86

# Build
make build/main_floppy.img

# Run in QEMU
qemu-system-x86_64 -fda build/main_floppy.img
```

## Progress

- [x] Printed "Hello World!" to screen
- [ ] Keyboard input
- [ ] Disk reading
- [ ] Protected mode
- [ ] Multitasking
- [ ] File system support
