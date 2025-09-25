# Challenge 7: Explicit Relative Paths, from /
In this challenge I had to run /challenge/run using an explicit relative path while having a current working directory of / and using . to access the same directory

## My solve
**Flag:** ` pwn.college{srXGTu55Qc0zkwzUVRJHFWXAgYc.QXwUTN0wCN2MzNzEzW}’

```
hacker@paths~explicit-relative-paths-from-:~$ cd /
hacker@paths~explicit-relative-paths-from-:/$ ./challenge/run
Correct!!!
./challenge/run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{srXGTu55Qc0zkwzUVRJHFWXAgYc.QXwUTN0wCN2MzNzEzW}
```

## What I learned
How to invoke a file in the same directory by using ‘.’

## Incorrect tangents
None

## References
None
