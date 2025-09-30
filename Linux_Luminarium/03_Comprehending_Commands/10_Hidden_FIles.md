# Challenge 10: Hidden Files
This challenge wants you to go find the flag, hidden as a dot-prepended file in /.

## My solve
**Flag:** ` pwn.college{QVrN6fGiJaQyfp2ZZaN7E6gNUHA.QXwUDO0wCN2MzNzEzW}’


```
hacker@commands~hidden-files:~$ cd /
hacker@commands~hidden-files:/$ ls -a
.   .dockerenv           bin   challenge  etc   lib    lib64   media  nix  proc  run   srv  tmp  var
..  .flag-9419609512012  boot  dev        home  lib32  libx32  mnt    opt  root  sbin  sys  usr
hacker@commands~hidden-files:/$ cat .flag-9419609512012
pwn.college{QVrN6fGiJaQyfp2ZZaN7E6gNUHA.QXwUDO0wCN2MzNzEzW}
```

## What I learned
How to access hidden files (files which start with .) using ls -a

## Incorrect tangents
None

## References
None
