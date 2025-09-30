# Challenge 3: Appending Output
In this challenge, I had to append the output of /challenge/run to ./the-flag by using >>. Otherwise, the second half of the flag would have overwritten the first.

## My solve
**Flag:** ` pwn.college{8b52ocpbtC2MUIV34YZ8nTmoMxN.QX3ATO0wCN2MzNzEzW}’


```
hacker@piping~appending-output:~$ /challenge/run >> /home/hacker/the-flag
hacker@piping~appending-output:~$ cat /home/hacker/the-flag
 | 
\|/ This is the first half:
 v 
pwn.college{8b52ocpbtC2MUIV34YZ8nTmoMxN.QX3ATO0wCN2MzNzEzW}
                              ^
     that is the second half /|\
                              |
```

## What I learned
That >> is used to append the output while > overwrites the previously stored output.

## Incorrect tangents
None

## References
None
