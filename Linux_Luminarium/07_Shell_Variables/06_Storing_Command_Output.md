# Challenge 6: Storing Command Output
Read the output of the /challenge/run command directly into a variable called PWN, and it will contain the flag.

## My solve
**Flag:** ` pwn.college{sQcojj8XQrFYY8W0YvQUKISrx4D.QX1cDN1wCN2MzNzEzW}’


```
hacker@variables~storing-command-output:~$ PWN=$(/challenge/run)
Congratulations! You have read the flag into the PWN variable. Now print it out 
and submit it!
hacker@variables~storing-command-output:~$ echo $PWN
pwn.college{sQcojj8XQrFYY8W0YvQUKISrx4D.QX1cDN1wCN2MzNzEzW}
```

## What I learned
How to store the output of a process in a variable and access it later.

## Incorrect tangents
None

## References
None
