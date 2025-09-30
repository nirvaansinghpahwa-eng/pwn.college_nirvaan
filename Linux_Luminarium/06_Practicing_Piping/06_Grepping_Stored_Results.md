# Challenge 6: Grepping Stored Results
In this level, I had to redirect the output of /challenge/run to /tmp/data.txt and then search for the flag by using grep.

## My solve
**Flag:** ` pwn.college{ErHNqmuAmsU8c8y7pg_XmDSx-8W.QX4EDO0wCN2MzNzEzW}’


```
hacker@piping~grepping-stored-results:~$ /challenge/run > /tmp/data.txt
hacker@piping~grepping-stored-results:~$ grep "pwn.college" /tmp/data.txt
pwn.college{ErHNqmuAmsU8c8y7pg_XmDSx-8W.QX4EDO0wCN2MzNzEzW}
```

## What I learned
Redirected outputs can be searched for by using grep

## Incorrect tangents
None

## References
None
