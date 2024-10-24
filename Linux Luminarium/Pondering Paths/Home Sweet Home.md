# Challenge: Handling File Paths

## Challenge Overview

In this challenge, the task was to provide an absolute path as an argument to a program. The challenge emphasized the difference between relative and absolute paths and their usage when interacting with the file system.

## Steps Taken

1. **Creating a File**:
   I started by creating a simple file named `s` in my home directory (`~`) using the `touch` command:
   ```bash
   touch s
   ```

2. **Initial Attempt with a Relative Path**:
   I then tried running the program `/challenge/run` and provided the file `s` as an argument:
   ```bash
   /challenge/run s
   ```
   This resulted in an error because the program expected an absolute path:
   ```bash
   The argument you provided is not an absolute path!
   ```

3. **Using an Absolute Path**:
   To resolve this, I provided the full absolute path to the file using the `~/` notation:
   ```bash
   /challenge/run ~/s
   ```

4. **Flag Retrieved**:
   The program successfully wrote and read back the file, displaying the flag:
   ```bash
   Writing the file to /home/hacker/s!
   ... and reading it back to you:
   pwn.college{I5snc5BUf7pwQQUGzWGY4YVvwRJ.dNzM4QDLwITO0czW}
   ```


```bash
hacker@paths~home-sweet-home:/home$ cd ~
hacker@paths~home-sweet-home:~$ touch s
hacker@paths~home-sweet-home:~$ /challenge/run s
The argument you provided is not an absolute path!
hacker@paths~home-sweet-home:~$ /challenge/run ~/s
Writing the file to /home/hacker/s!
... and reading it back to you:
pwn.college{I5snc5BUf7pwQQUGzWGY4YVvwRJ.dNzM4QDLwITO0czW}
hacker@paths~home-sweet-home:~$ 
```

<img width="452" alt="image" src="https://github.com/user-attachments/assets/67ff6466-75ad-42a3-8a9b-628e0b0cf74c">
