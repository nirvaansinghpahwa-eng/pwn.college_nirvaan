# Challenge 12: Writing to multiple programs
In this challenge, we have /challenge/hack, /challenge/the, and /challenge/planet. Run the /challenge/hack command, and duplicate its output as input to both the /challenge/the and the /challenge/planet commands.

## My solve
**Flag:** ` pwn.college{wTdU-Yz9Hhm6oeX2bRVDzpmlz4M.QXwgDN1wCN2MzNzEzW}’


```
hacker@piping~writing-to-multiple-programs:~$ /challenge/hack | tee /challenge/the | /challenge/planet
WARNING: it looks like you passed the path /challenge/the, instead of the 
substituted process, to tee. This will cause tee to try to write to the 
/challenge/the file, rather than have the shell launch the /challenge/the 
command and redirect tee's output to it.
/usr/bin/tee: /challenge/the: Permission denied

hacker@piping~writing-to-multiple-programs:~$ /challenge/hack | tee >(/challenge/the) >(/challenge/planet)
Congratulations, you have duplicated data into the input of two programs! Here 
is your flag:
pwn.college{wTdU-Yz9Hhm6oeX2bRVDzpmlz4M.QXwgDN1wCN2MzNzEzW}
```

## What I learned
How to write data in multiple programs using process substitution and duplication.

## Incorrect tangents
I tried to only use duplication first, forgetting about process substitution.

## References
None
