# Challenge 6: Implicit Relative Paths, from /
In this challenge I had to run /challenge/run using a relative path while having a current working directory of /. 

## My solve
**Flag:** ` pwn.college{MzYj2F9OmbxcgTsN_ppDBsVh920.QX5QTN0wCN2MzNzEzW}’

```
hacker@paths~implicit-relative-paths-from-:~$ cd /
hacker@paths~implicit-relative-paths-from-:/$ challenge/run
Correct!!!
challenge/run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{MzYj2F9OmbxcgTsN_ppDBsVh920.QX5QTN0wCN2MzNzEzW}
```

## What I learned
How to use relative path to invoke a file.

## Incorrect tangents
None

## References
None
