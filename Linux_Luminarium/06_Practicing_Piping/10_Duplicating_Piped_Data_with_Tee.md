# Challenge 10: Duplicating piped data with tee
This process' /challenge/pwn must be piped into /challenge/college, but you'll need to intercept the data to see what pwn needs from you

## My solve
**Flag:** ` pwn.college{wh3G1r1Fg_wEI330lHT8PsN2a6U.QXxITO0wCN2MzNzEzW}’


```
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn --secret wh3G1r1F | /challenge/college
Processing...
Correct! Passing secret value to /challenge/college...
Great job! Here is your flag:
pwn.college{wh3G1r1Fg_wEI330lHT8PsN2a6U.QXxITO0wCN2MzNzEzW}
```

## What I learned
Data can be extracted while piping and copied by using tee. This can be used for debugging

## Incorrect tangents
None

## References
None
