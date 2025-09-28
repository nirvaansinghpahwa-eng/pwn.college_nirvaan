# Challenge 5: Comparing Files
In this challenge, there were two files in /challenge:
/challenge/decoys_only.txt contains 100 fake flags
/challenge/decoys_and_real.txt contains all 100 fake flags plus the one real flag.
I had to use diff to find what's different between these files and get the flag.


## My solve
**Flag:** ` pwn.college{0Eq85HjznU_ANKEC4Fm4RpPNsml.01MwMDOxwCN2MzNzEzW}’


```
hacker@commands~comparing-files:~$ cd /challenge
hacker@commands~comparing-files:/challenge$ diff decoys_only.txt decoys_and_real.txt
18a19
> pwn.college{0Eq85HjznU_ANKEC4Fm4RpPNsml.01MwMDOxwCN2MzNzEzW}
```

## What I learned
How to find differences in two files and interpret it.

## Incorrect tangents
None

## References
None
