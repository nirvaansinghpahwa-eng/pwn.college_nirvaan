# Challenge 7: Help for Builtins
In this challenge, I had to use help to gain information about challenge, which was a buitin function.

## My solve
**Flag:** ` pwn.college{Yyu4LKlUrj6kz80-nQOxuRJf8ll.QX0ETO0wCN2MzNzEzW}’


```
hacker@man~help-for-builtins:~$ help challenge
challenge: challenge [--fortune] [--version] [--secret SECRET]
    This builtin command will read you the flag, given the right arguments!
    
    Options:
      --fortune         display a fortune
      --version         display the version
      --secret VALUE    prints the flag, if VALUE is correct

    You must be sure to provide the right value to --secret. That value
    is "Yyu4LKlU".
hacker@man~help-for-builtins:~$ challenge --secret Yyu4LKlU
Correct! Here is your flag!
pwn.college{Yyu4LKlUrj6kz80-nQOxuRJf8ll.QX0ETO0wCN2MzNzEzW}
```

## What I learned
How to access builtin variables and use help to gain information about them. 

## Incorrect tangents
None

## References
None
