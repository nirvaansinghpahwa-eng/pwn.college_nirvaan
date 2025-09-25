# Challenge 5: Position yet Elsewhere
In this challenge I had to run /challenge/run from a specific path.

## My solve
**Flag:** ` pwn.college{EwKo6I_DNKy0IkSV4dSLJLdBJ2T.QX4QTN0wCN2MzNzEzW}’

```
hacker@paths~position-yet-elsewhere:~$ /challenge/run
Incorrect...
You are not currently in the /usr/aarch64-linux-gnu/include/gnu directory.
Please use the `cd` utility to change directory appropriately.
hacker@paths~position-yet-elsewhere:~$ cd /usr/aarch64-linux-gnu/include/gnu
hacker@paths~position-yet-elsewhere:/usr/aarch64-linux-gnu/include/gnu$ /challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
pwn.college{EwKo6I_DNKy0IkSV4dSLJLdBJ2T.QX4QTN0wCN2MzNzEzW}
```

## What I learned
How to run a file which is in a different directory by using cd.

## Incorrect tangents
None

## References
None
