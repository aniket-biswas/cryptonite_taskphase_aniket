# Challenge: Removing Files

## Challenge Overview

In this challenge, the objective was to create a file and then remove it using the `rm` command. Successfully removing the file would allow me to execute a program that checks the removal and provides a reward.

## Steps Taken

1. **Creating a File**:
   I started by creating a file named `delete_me` in my home directory using the `touch` command:
   ```bash
   touch delete_me
   ```

2. **Removing the File**:
   I then removed the file using the `rm` command:
   ```bash
   rm delete_me
   ```

3. **Checking Removal**:
   After successfully removing the file, I executed the check program located at `/challenge/check`:
   ```bash
   /challenge/check
   ```

4. **Flag Retrieved**:
   The program confirmed the successful removal of the file and displayed the reward:
   ```bash
   Excellent removal. Here is your reward:
   pwn.college{42X7bzl9t0nAklfJZU0LgzCqQm5.dZTOwUDLwITO0czW}
   ```


```bash
hacker@commands~removing-files:/home$ cd
hacker@commands~removing-files:~$ touch delete_me
hacker@commands~removing-files:~$ rm delete_me
hacker@commands~removing-files:~$ /challenge/check
Excellent removal. Here is your reward:
pwn.college{42X7bzl9t0nAklfJZU0LgzCqQm5.dZTOwUDLwITO0czW}
hacker@commands~removing-files:~$

```
<img width="452" alt="image" src="https://github.com/user-attachments/assets/863fb6bf-045a-479a-b8b5-2678bf9eefef">
