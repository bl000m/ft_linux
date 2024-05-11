## Introduction
Welcome to ft_linux. This project entails the construction of a functional Linux distribution, pivotal for subsequent kernel projects. While not centered on kernel programming, this endeavor provides a crucial environment for executing kernel code.

## Goals
- Develop a Linux Kernel
- Install essential binaries
- Implement a filesystem hierarchy compliant with standards
- Establish internet connectivity

### Instructions
- Utilize a virtual machine, preferably VirtualBox or VMWare.
- Recommended reading materials are provided but not mandatory.
- Utilize a kernel version >= 4.0.
- Organize kernel sources in /usr/src/kernel-$(version).
- Utilize at least three partitions (root, /boot, and swap).
- Implement a kernel module loader similar to udev.
- Customize the kernel version to include your student login.
- Set the distribution hostname as your student login.
- Choose between a 32 or 64-bit system.
- Implement software for central management and configuration (SysV or SystemD).
- Ensure bootloader (LILO or GRUB) configuration adheres to specified naming conventions.
