# Challenge 6: Helpful Programs
In this challenge, I had to use the –help argument with challenge. Then I had to follow the given steps to get the flag.

## My solve
**Flag:** ` pwn.college{8zJXo-ftRBhRUgg6ovO2bwaO10g.QX3IDO0wCN2MzNzEzW}’


```
hacker@man~helpful-programs:~$ /challenge/challenge --help
usage: a challenge to make you ask for help [-h] [--fortune] [-v] [-g GIVE_THE_FLAG] [-p]

optional arguments:
  -h, --help            show this help message and exit
  --fortune             read your fortune
  -v, --version         get the version number
  -g GIVE_THE_FLAG, --give-the-flag GIVE_THE_FLAG
                        get the flag, if given the correct value
  -p, --print-value     print the value that will cause the -g option to give you the flag
hacker@man~helpful-programs:~$ /challenge/challenge -p
The secret value is: 862
hacker@man~helpful-programs:~$ /challenge/challenge -g 862
Correct usage! Your flag: pwn.college{8zJXo-ftRBhRUgg6ovO2bwaO10g.QX3IDO0wCN2MzNzEzW}
```

## What I learned
Use of –-help instead of man 

## Incorrect tangents
None

## References
None
