# Challenge: Creating Directories and Executing a Program

## Challenge Overview

In this challenge, the objective was to create a directory, add a file within it, and execute a program to retrieve a flag. This exercise focused on directory manipulation and the execution of commands in a Linux environment.

## Steps Taken

1. **Creating a New Directory**:
   I started by creating a directory named `pwn` in the `/tmp` directory using the `mkdir` command:
   ```bash
   mkdir /tmp/pwn
   ```

2. **Navigating to the New Directory**:
   I then changed my working directory to the newly created `pwn` directory:
   ```bash
   cd /tmp/pwn
   ```

3. **Creating a File**:
   Inside the `pwn` directory, I created a file named `college` using the `touch` command:
   ```bash
   touch college
   ```

4. **Executing the Program**:
   I executed the program located at `/challenge/run` to retrieve the flag:
   ```bash
   /challenge/run
   ```

5. **Flag Retrieved**:
   The program executed successfully and displayed the flag:
   ```bash
   Success! Here is your flag:
   pwn.college{AzQ0xvY7KUYDFaUt41m-4ZkFkO9.dFzM4QDLwITO0czW}
   ```



```bash
hacker@commands~making-directories:/home$ cd
hacker@commands~making-directories:~$ mkdir /tmp/pwn
hacker@commands~making-directories:~$ cd /tmp/pwn
hacker@commands~making-directories:/tmp/pwn$ touch college
hacker@commands~making-directories:/tmp/pwn$ /challenge/run
Success! Here is your flag:
pwn.college{AzQ0xvY7KUYDFaUt41m-4ZkFkO9.dFzM4QDLwITO0czW}
hacker@commands~making-directories:/tmp/pwn$ 

```
<img width="452" alt="image" src="https://github.com/user-attachments/assets/de32c31e-8d2c-4547-8450-9e6b78ee80b3">
