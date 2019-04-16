# Chip-8 emualtor
CHIP-8 is an interpretted programming language developed by Joseph Weisbecker in the mid 70s and was initally used on the COSMAC VIP and Telmac 1800 8-bit microcomputers to make game programming easier. CHIP-8 programs are run using a CHIP-8 virtual machine.

# Requirements

Requires sdl2 and cmake

```
sudo pacman -S libsdl2-dev #might differ for you, please refer to documentation for you OS/Distro
```

#Compiling and Running

Compile:
```
$ mkdir build
$ cd build
$ cmake ..
$ make
```

Run:
```
./chip8 <ROM File>
```

#References

- emulator101.com
- http://lazyfoo.net/tutorials/SDL/
