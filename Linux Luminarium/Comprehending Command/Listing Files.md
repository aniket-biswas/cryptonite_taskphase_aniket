# Challenge: Listing Files and Executing Programs

## Challenge Overview

In this challenge, the objective was to navigate to a specific directory, list its contents, and execute a hidden program to retrieve a flag. This exercise focused on understanding directory navigation and file execution in a command-line environment.

## Steps Taken

1. **Navigating to the Challenge Directory**:
   I changed my working directory to `/challenge`:
   ```bash
   cd /challenge
   ```

2. **Listing the Files**:
   I listed the contents of the `/challenge` directory to see the available files:
   ```bash
   ls /challenge
   ```

   The output displayed two files:
   ```
   14184-renamed-run-17886  DESCRIPTION.md
   ```

3. **Executing the Program**:
   I executed the program `14184-renamed-run-17886`:
   ```bash
   ./14184-renamed-run-17886
   ```

4. **Flag Retrieved**:
   The program ran successfully and revealed the flag:
   ```bash
   Yahaha, you found me! Here is your flag:
   pwn.college{sGq8vukNJ7SiWHaQK0McDj6XimD.dhjM4QDLwITO0czW}
   ```


```bash
hacker@commands~listing-files:/home$ cd /challenge
hacker@commands~listing-files:/challenge$ ls /challenge
14184-renamed-run-17886  DESCRIPTION.md
hacker@commands~listing-files:/challenge$ ./14184-renamed-run-17886
Yahaha, you found me! Here is your flag:
pwn.college{sGq8vukNJ7SiWHaQK0McDj6XimD.dhjM4QDLwITO0czW}
hacker@commands~listing-files:/challenge$
```
<img width="452" alt="image" src="https://github.com/user-attachments/assets/7d170c6d-b3b4-4688-a512-1fdd3798a514">
