# Challenge 8: Grepping Errors
In this level, I had to grep the errors in /challenge/run using |.

## My solve
**Flag:** ` pwn.college{IhPfTR4iGff0rDDefn34P7NiuzN.QX5EDO0wCN2MzNzEzW}’


```
hacker@piping~grepping-errors:~$ /challenge/run 2>& 1 | grep "pwn.college"
pwn.college{wEOj-q0QYRVnSZzf86-sErgOoXN.QX1ATO0wCN2MzNzEzW}
```

## What I learned
Grep can only take FD1 data, however
&> creates a new file descriptor which combats this problem.

## Incorrect tangents
None

## References
None
