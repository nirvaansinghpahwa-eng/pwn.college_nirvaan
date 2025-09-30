# Challenge 4: Redirecting Errors
In this challenge, I had to redirect the output of /challenge/run to myflag and the errors to instructions.

## My solve
**Flag:** ` pwn.college{w5HU5J1QI-RipcIEF-_CenLFfa5.QX3YTN0wCN2MzNzEzW}’


```
hacker@piping~redirecting-errors:~$ /challenge/run 1> myflag 2>instructions
hacker@piping~redirecting-errors:~$ cat myflag

[FLAG] Here is your flag:
[FLAG] pwn.college{w5HU5J1QI-RipcIEF-_CenLFfa5.QX3YTN0wCN2MzNzEzW}
```

## What I learned
1>	Is used to redirect output and FD1 data while 2> is used to redirect errors.

## Incorrect tangents
None

## References
None
