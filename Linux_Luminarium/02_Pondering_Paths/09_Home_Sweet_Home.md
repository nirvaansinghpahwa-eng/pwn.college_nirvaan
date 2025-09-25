# Challenge 9: Home Sweet Home
In this challenge, /challenge/run will write a copy of the flag to any file you specify as an argument on the commandline, with these constraints:
1.	Your argument must be an absolute path.
2.	The path must be inside your home directory.
3.	Before expansion, your argument must be three characters or less.

## My solve
**Flag:** ` pwn.college{IlzTJ8Ed11yO_jvfdsSvgfh9d-O.QXzMDO0wCN2MzNzEzW}’


```
hacker@paths~home-sweet-home:~$ /challenge/run /home/hacker/hi/wow
The argument you provided must not have been longer than 3 characters (it's currently 19 characters long)!
hacker@paths~home-sweet-home:~$ /challenge/run ./i
The argument you provided is not an absolute path!
hacker@paths~home-sweet-home:~$ /challenge/run ~/i
Writing the file to /home/hacker/i!
... and reading it back to you:
pwn.college{IlzTJ8Ed11yO_jvfdsSvgfh9d-O.QXzMDO0wCN2MzNzEzW}
```

## What I learned


## Incorrect tangents
First I provided a path which contained too many characters. Then I tried using . but the challenge had stated to use absolute path only. Then I used ~/i which was the correct answer.

## References
None
