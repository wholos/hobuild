# hobuild
[![C](https://img.shields.io/badge/C-00599C?logo=c&logoColor=white)](#)

Build system for unix!

hobuild - has a file extension of ```.hob```, and should always be named ```build.hob```, the syntax is simple

```
p = variable
block; = block
!() = variable reference in brackets
```

Example build.hob
```
p INT = "echo"

test;
    !(INT) 'hi'
```
and write in terminal ```hobuild test```

How to build?
``` sh
gcc hobuild.c -o hobuild
```

How to install?

AUR (ArchLinux):
``` sh
yay -S hobuild
```

Any unix systems:
``` sh
sudo cp hobuild /usr/bin/hobuild
```
