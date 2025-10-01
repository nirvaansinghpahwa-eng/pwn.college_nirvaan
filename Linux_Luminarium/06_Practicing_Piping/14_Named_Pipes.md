# Challenge 14: Named pipes
In this challenge, create a /tmp/flag_fifo file and redirect the stdout of /challenge/run to it. If you're successful, /challenge/run will write the flag into the FIFO

## My solve
**Flag:** ` pwn.college{EHaPjLhx4PpJXgf-wLALnYoGDFJ.01MzMDOxwCN2MzNzEzW}’


```
hacker@piping~named-pipes:~$ mkfifo /tmp/flag_fifo
hacker@piping~named-pipes:~$ /challenge/run > /tmp/flag_fifo

“in other terminal”

hacker@piping~named-pipes:~$ cat /tmp/flag_fifo
You've correctly redirected /challenge/run's stdout to a FIFO at 
/tmp/flag_fifo! Here is your flag:
pwn.college{EHaPjLhx4PpJXgf-wLALnYoGDFJ.01MzMDOxwCN2MzNzEzW}
```

## What I learned
About FIFOs and how they work, also how they are different from files and have to be written and read at the same time to be accessed.

## Incorrect tangents
None

## References
None
