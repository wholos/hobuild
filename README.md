# hobuild
[![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)](https://gnu.org/)
![GitHub License](https://img.shields.io/github/license/ruzen42/harkpkg?style=for-the-badge)
#
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
``` sh
sudo cp hobuild /usr/bin/hobuild
```
