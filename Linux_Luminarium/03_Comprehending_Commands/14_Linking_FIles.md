# Challenge 14: Linking Files
In this challenge the flag was in /flag, but /challenge/catflag will instead read out /home/hacker/not-the-flag. I had to use symlink (ln -s), and fool it into giving me the flag!

## My solve
**Flag:** `pwn.college{0rG-jrtb0kyQxTHVLauLpZiYgnq.QX5ETN1wCN2MzNzEzW} ’


```
hacker@commands~linking-files:~$ ln -s /flag /home/hacker/not-the-flag
hacker@commands~linking-files:~$ /challenge/catflag
About to read out the /home/hacker/not-the-flag file!
pwn.college{0rG-jrtb0kyQxTHVLauLpZiYgnq.QX5ETN1wCN2MzNzEzW}
```

## What I learned
What is soft linking and hard linking and how one file can have multiple addresses.

## Incorrect tangents
None

## References
None
