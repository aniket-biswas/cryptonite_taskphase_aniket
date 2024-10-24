# Challenge: Linking Files

## Challenge Overview

In this challenge, the objective was to create a symbolic link to a file and then read its contents using a provided command. This exercise emphasized the concept of linking files in a Linux environment.

## Steps Taken

1. **Creating a Symbolic Link**:
   I started by creating a symbolic link to the `/flag` file, naming it `not-the-flag` in my home directory. This was done using the `ln` command with the `-s` option:
   ```bash
   ln -s /flag /home/hacker/not-the-flag
   ```

2. **Executing the Cat Flag Program**:
   I then executed the program located at `/challenge/catflag`, which was designed to read the contents of the linked file:
   ```bash
   /challenge/catflag
   ```

3. **Flag Retrieved**:
   The program successfully read the contents of the `not-the-flag` file (which pointed to `/flag`) and displayed the flag:
   ```bash
   About to read out the /home/hacker/not-the-flag file!
   pwn.college{sf8SpdHqlai5Zjcf1jFJjTymZ2m.dlTM1UDLwITO0czW}
   ```
<img width="452" alt="image" src="https://github.com/user-attachments/assets/ad588e38-b53f-4b5e-a4f0-60c5d8555823">
