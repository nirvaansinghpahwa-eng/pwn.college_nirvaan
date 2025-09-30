# Challenge 3: Matching with []
In this challenge, I had to use [] to enter an argument of specifi files to /challenge/run. The files were file_b,file_a,file_s,file_h.

## My solve
**Flag:** ` pwn.college{MVgQ8SUXgdebiGyVJnQaTCScYbv.QXzIDO0wCN2MzNzEzW}’


```
hacker@globbing~matching-with-:~$ cd /challenge/files
hacker@globbing~matching-with-:/challenge/files$ ls
file_a  file_c  file_e  file_g  file_i  file_k  file_m  file_o  file_q  file_s  file_u  file_w  file_y
file_b  file_d  file_f  file_h  file_j  file_l  file_n  file_p  file_r  file_t  file_v  file_x  file_z
hacker@globbing~matching-with-:/challenge/files$ /challenge/run file_[bash]
You got it! Here is your flag!
pwn.college{MVgQ8SUXgdebiGyVJnQaTCScYbv.QXzIDO0wCN2MzNzEzW}
```

## What I learned
Usage of [] in file globbing.

## Incorrect tangents
None

## References
None
