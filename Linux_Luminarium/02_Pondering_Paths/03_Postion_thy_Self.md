# Challenge 3: Position thy Self
In this challenge I had to run /challenge/run from a specific path.

## My solve
**Flag:** ` pwn.college{Ygo86TViVb5znujniWnYtdv3L5_.QX2QTN0wCN2MzNzEzW}’

```
hacker@paths~position-thy-self:~$ /challenge/run
Incorrect...
You are not currently in the /usr/include directory.
Please use the `cd` utility to change directory appropriately.
hacker@paths~position-thy-self:~$ cd /usr/include
hacker@paths~position-thy-self:/usr/include$ /challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
pwn.college{Ygo86TViVb5znujniWnYtdv3L5_.QX2QTN0wCN2MzNzEzW}
```

## What I learned
How to run a file which is in a different directory by using cd.

## Incorrect tangents
None

## References
None
