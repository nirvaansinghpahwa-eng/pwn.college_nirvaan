# Challenge 5: Redirecting Input
In this level, we will practice using /challenge/run, which will require you to redirect the PWN file to it and have the PWN file contain the value COLLEGE

## My solve
**Flag:** ` pwn.college{4sEAvqIiVJDi85h1P_NNcf76cES.QXwcTN0wCN2MzNzEzW}’


```
hacker@piping~redirecting-input:~$ echo COLLEGE > PWN
hacker@piping~redirecting-input:~$ /challenge/run < PWN
Reading from standard input...
Correct! You have redirected the PWN file into my standard input, and I read 
the value 'COLLEGE' out of it!
Here is your flag:
pwn.college{4sEAvqIiVJDi85h1P_NNcf76cES.QXwcTN0wCN2MzNzEzW}
```

## What I learned
< can be used to redirect input

## Incorrect tangents
None

## References
None
