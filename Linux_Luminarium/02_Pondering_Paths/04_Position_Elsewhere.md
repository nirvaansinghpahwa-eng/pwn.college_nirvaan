# Challenge 4: Position Elsewhere
In this challenge I had to run /challenge/run from a specific path.

## My solve
**Flag:** ` pwn.college{ECCDS15N2xQD8VUeBASnMzRTiwD.QX3QTN0wCN2MzNzEzW}’

```
hacker@paths~position-elsewhere:~$ /challenge/run
Incorrect...
You are not currently in the /var/lib/apt/lists directory.
Please use the `cd` utility to change directory appropriately.
hacker@paths~position-elsewhere:~$ cd /var/lib/apt/lists
hacker@paths~position-elsewhere:/var/lib/apt/lists$ /challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
pwn.college{ECCDS15N2xQD8VUeBASnMzRTiwD.QX3QTN0wCN2MzNzEzW}
```

## What I learned
How to run a file which is in a different directory by using cd.

## Incorrect tangents
None

## References
None
