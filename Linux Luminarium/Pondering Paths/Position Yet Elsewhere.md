# Challenge: Position Yet Elsewhere

## Challenge Overview

In this challenge, the goal was to execute a program using an absolute path while being in the `/etc` directory. If attempted from any other directory, the program would not run and provide an error message.

## Steps Taken

1. **Initial Attempt**:
   While in the home directory (`~`), I tried to run the command:
   ```bash
   /challenge/run
   ```
   This resulted in the following error:
   ```bash
   Incorrect...
   You are not currently in the /etc directory.
   Please use the `cd` utility to change directory appropriately.
   ```

2. **Navigating to the Correct Directory**:
   To address this, I changed the directory to `/etc` by running:
   ```bash
   cd /etc
   ```

3. **Executing the Program**:
   After navigating to the `/etc` directory, I re-executed the program:
   ```bash
   /challenge/run
   ```

4. **Flag Retrieved**:
   This time, the program ran correctly, and the flag was provided:
   ```bash
   Correct!!!
   /challenge/run is an absolute path, invoked from the right directory!
   Here is your flag:
   pwn.college{YVS-g8FZNCLICjv3ftNdJyN2UN9.dhDN1QDLwITO0czW}
   ```



```bash
hacker@paths~position-yet-elsewhere:/home$ cd
hacker@paths~position-yet-elsewhere:~$ /challenge/run
Incorrect...
You are not currently in the /etc directory.
Please use the `cd` utility to change directory appropriately.
hacker@paths~position-yet-elsewhere:~$ cd /etc
hacker@paths~position-yet-elsewhere:/etc$ /challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
pwn.college{YVS-g8FZNCLICjv3ftNdJyN2UN9.dhDN1QDLwITO0czW}
hacker@paths~position-yet-elsewhere:/etc$ 

```

<img width="452" alt="image" src="https://github.com/user-attachments/assets/6055409a-12ec-446c-a753-40d1c0532cb5">
