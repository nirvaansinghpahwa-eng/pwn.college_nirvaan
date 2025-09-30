# Challenge 9: Filtering with grep -v
In this level, I had to use grep -v to filter out the flag from decoy flags which contained the word “DECOY”.

## My solve
**Flag:** ` pwn.college{U_NxCitVt3Awz_O9stt6S7ontB_.0FOxEzNxwCN2MzNzEzW}’


```
hacker@piping~filtering-with-grep-v:~$ /challenge/run | grep -v "DECOY"
pwn.college{U_NxCitVt3Awz_O9stt6S7ontB_.0FOxEzNxwCN2MzNzEzW}
```

## What I learned
grep -v  can filter out unwanted outputs.

## Incorrect tangents
None

## References
