# xv6_uefi
xv6_uefi is the operating system based on xv6.
This operating system runs on x86-64 and uefi system.

```
git clone https://github.com/naoki9911/xv6_uefi
cd xv6_uefi
make
```
If you have some trouble, try to execute commands line by line in build.sh
# Packages
Needed packages are as follows.

```
qemu
nasm
acpica
```

# TODO
- console with frame buffer - Done
- nic device driver - Almost Done
- tcp/ip protocol stack - In Progress
- HTTP server
