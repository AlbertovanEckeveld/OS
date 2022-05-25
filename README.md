# OS
Trying to create my own Operating system

## Installation:

### Installation: 
```bash
sudo apt-get install g++ binutils libc6-dev-i386
```
#### In this case were are using virtualbox, if that doesn't work quit well. You can use everything you want except for qemu-system.
```bash
sudo apt-get install virtualbox grub-pc xorriso
```
#### Clone my repository
```bash
git clone https://github.com/AlbertovanEckeveld/OS
```

## Configuration:

### Run makefile

```bash
make
```
If you're getting "virtualbox --startvm" errors, you can use the ISO in for example vmware.