# Challenge 5: Searching for Manuals
In this challenge, I had to use man man to find out a seacret placeholder word for challenge. Then I had to use man challenge to get the flag.

## My solve
**Flag:** ` pwn.college{Y9a8Wn1ctLJhfJB109WYPdOF3LY.QX2EDO0wCN2MzNzEzW}’


```
hacker@man~searching-for-manuals:~$ man man
hacker@man~searching-for-manuals:~$ man -k challenge
ancthfdwzz (1)       - print the flag!
hacker@man~searching-for-manuals:~$ man ancthfdwzz
hacker@man~searching-for-manuals:~$ /challenge/challenge --ancthf 981
Correct usage! Your flag: pwn.college{Y9a8Wn1ctLJhfJB109WYPdOF3LY.QX2EDO0wCN2MzNzEzW}
```

## What I learned
Advanced use of man and various arguments of man.

## Incorrect tangents
None

## References
None
