# Challenge: Redirecting More Output

In this challenge, the objective is to successfully redirect output from a command into a file while navigating permission constraints.

 ```bash
hacker@piping~redirecting-output:/home$ echo PWN > COLLEGE
bash: COLLEGE: Permission denied
hacker@piping~redirecting-output:/home$ echo hi > asdf
bash: asdf: Permission denied

hacker@piping~redirecting-output:/home$ cd

hacker@piping~redirecting-output:~$ echo PWN > COLLEGE
Correct! You successfully redirected 'PWN' to the file 'COLLEGE'! Here is your flag
```

## Flag
pwn.college{At4UuAobVrqxTWtJLRqH743-8dx.dRjN1QDLwITO0czW}
hacker@piping~redirecting-output:~$ 
