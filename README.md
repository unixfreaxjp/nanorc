# nanorc

Create a new directory in `/usr/local/share/` called `nano` like this:
```
sudo mkdir /usr/local/share/nano
```

Code or use this repo `nanorc` file, i.e. for C and ASM syntax is like this:
```
sudo nano /usr/local/share/nano/c.nanorc
sudo nano /usr/local/share/nano/asm.nanorc
```

Edit your user’s nano resource file `~/.nanorc` to `include` your new `nanorc path`
```
include "/usr/local/share/nano/c.nanorc"
include "/usr/local/share/nano/asm.nanorc"
```
## notes:

This is the modified version by @unixfreaxjp, first backup your previous nanorc if already exists.
Compatibiliy is tested on Mac, FreeBSD and Linux.
