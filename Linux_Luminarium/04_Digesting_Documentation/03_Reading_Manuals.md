# Challenge 3: Reading Manuals
In this challenge, I had to use man command to find a secret argument to use for /challenge/challenge which would give me the flag.

## My solve
**Flag:** ` pwn.college{o7fFyKzEpS2h1sSrNn7uq3kWjZD.QX0EDO0wCN2MzNzEzW}’


```
hacker@man~reading-manuals:~$ man challenge
hacker@man~reading-manuals:~$ /challenge/challenge --ofyzph NUM
Incorrect usage! Please read the challenge man page!
hacker@man~reading-manuals:~$ /challenge/challenge --ofyzph 721
Correct usage! Your flag: pwn.college{o7fFyKzEpS2h1sSrNn7uq3kWjZD.QX0EDO0wCN2MzNzEzW}
```

## What I learned
How to access the manual for a specific command

## Incorrect tangents
I used NUM instead of 721 which the manual had stated to be used to get the flag.

## References
None
