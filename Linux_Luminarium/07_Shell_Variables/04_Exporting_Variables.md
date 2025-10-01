# Challenge 4: Exporting Variables
In this challenge, I had to set the value of PWN to COLLEGE and export PWN and set the value of COLLEGE to PWN without exporting.

## My solve
**Flag:** ` pwn.college{YwZCrLpOZ_ZXVfCZgXHRfipW5TP.QXyYTN0wCN2MzNzEzW}’


```
hacker@variables~exporting-variables:~$ PWN=COLLEGE
You've set the PWN variable to the proper value!
hacker@variables~exporting-variables:~$ export PWN
You've set the PWN variable to the proper value!
hacker@variables~exporting-variables:~$ COLLEGE=PWN
You've set the PWN variable to the proper value!
You've set the COLLEGE variable to the proper value!
hacker@variables~exporting-variables:~$ /challenge/run
CORRECT!
You have exported PWN=COLLEGE and set, but not exported, COLLEGE=PWN. Great 
job! Here is your flag:
pwn.college{YwZCrLpOZ_ZXVfCZgXHRfipW5TP.QXyYTN0wCN2MzNzEzW}
```

## What I learned
How to export a variable so that it may be used in other shells.

## Incorrect tangents
None

## References
None
