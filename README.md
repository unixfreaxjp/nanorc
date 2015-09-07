# nanorc

Create a new directory in /usr/local/share/ called 'nano' like this:
```
mkdir /usr/local/share/nano
```

Using nano, make a nano resource file for your C syntax like this:
```
nano /usr/local/share/nano/c.nanorc
```

Now put i.e. your C code highlighting in this file and save it. Here is a link to some possible C syntax highlighting:
```
/syntax-nanorc/c.nanorc
```

Save that file and now open your user’s nano resource file by typing:
```
nano ~/.nanorc
```

In this file, add a reference to the c.nanorc file you just made like this:
```
include "/usr/local/share/nano/c.nanorc"
```
## notes:
Save your user resource file. Now, when you open up C files, you should see syntax highlighting. 
You can add additional syntax highlighting for different types of files using the same method. 
Just add more lines to your ~/.nanorc file.
