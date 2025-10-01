# Challenge 13: Split piping stderr and stdout
In this challenge, you have:
•	/challenge/hack: this produces data on stdout and stderr
•	/challenge/the: you must redirect hack's stderr to this program
•	/challenge/planet: you must redirect hack's stdout to this program
Go get the flag!

## My solve
**Flag:** ` pwn.college{cU5yQGd7w5j3zPH8D3cMjK9FbK0.QXxQDM2wCN2MzNzEzW}’


```
hacker@piping~split-piping-stderr-and-stdout:~$ /challenge/hack 2> >(/challenge/the) > >(/challenge/planet)
Congratulations, you have learned a redirection technique that even experts 
struggle with! Here is your flag:
pwn.college{cU5yQGd7w5j3zPH8D3cMjK9FbK0.QXxQDM2wCN2MzNzEzW}
```

## What I learned
How to redirect stdout to one program and stderr to another using >() and >2.

## Incorrect tangents
None

## References
None
