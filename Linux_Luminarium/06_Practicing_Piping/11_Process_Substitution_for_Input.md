# Challenge 11: Process substitution for input
In this challenge you'll diff two sets of command outputs: /challenge/print_decoys, which will print a bunch of decoy flags, and /challenge/print_decoys_and_flag which will print those same decoys plus the real flag.
Use process substitution with diff to compare the outputs of these two programs and find your flag

## My solve
**Flag:** ` pwn.college{AdVrOY_7IfLrkRt3z1nUOwkBj85.0lNwMDOxwCN2MzNzEzW}’


```
hacker@piping~process-substitution-for-input:~$ diff <(/challenge/print_decoys) <(/challenge/print_decoys_and_flag)
34a35
> pwn.college{AdVrOY_7IfLrkRt3z1nUOwkBj85.0lNwMDOxwCN2MzNzEzW}
```

## What I learned
How to use process substitution using <

## Incorrect tangents
None

## References
None
