# Challenge: Using `cat` with Absolute Paths

## Challenge Overview

In this challenge, the objective was to read the contents of a file named `flag` using the `cat` command with an absolute path. This exercise focused on understanding absolute paths and their application in accessing files.

## Steps Taken

1. **Changing to Home Directory**:
   I started by navigating to my home directory:
   ```bash
   cd
   ```

2. **Using the `cat` Command with an Absolute Path**:
   I executed the `cat` command with the absolute path to the file `flag`:
   ```bash
   cat /flag
   ```

3. **Flag Retrieved**:
   The command successfully displayed the contents of the file, which included the flag:
   ```bash
   pwn.college{Mzmzlu5qj136glvaGTfwalFQJjv.dlTM5QDLwITO0czW}
   ```



```bash
hacker@commands~catting-absolute-paths:/home$ cd
hacker@commands~catting-absolute-paths:~$ cat /flag
pwn.college{Mzmzlu5qj136glvaGTfwalFQJjv.dlTM5QDLwITO0czW}
hacker@commands~catting-absolute-paths:~$ 

```

<img width="452" alt="image" src="https://github.com/user-attachments/assets/2d385047-087b-4442-b712-88b551403aa7">
