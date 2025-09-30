# Challenge 2: Redirecting more Output
In this challenge, I had to redirect the output of /challenge/run to myfile.

## My solve
**Flag:** ` pwn.college{UY8D3-RV9jjBIXF37MpqpGbXXF2.QX1YTN0wCN2MzNzEzW}’


```
hacker@piping~redirecting-more-output:~$ /challenge/run > myflag
hacker@piping~redirecting-more-output:~$ cat myflag

[FLAG] Here is your flag:
[FLAG] pwn.college{UY8D3-RV9jjBIXF37MpqpGbXXF2.QX1YTN0wCN2MzNzEzW}
```

## What I learned
Redirection of output takes place by using absolute path of program > (file).

## Incorrect tangents
None

## References
None
