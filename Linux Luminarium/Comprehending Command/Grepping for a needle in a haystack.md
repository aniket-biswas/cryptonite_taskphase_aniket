# Challenge: Using `grep` to Find a Flag

## Challenge Overview

In this challenge, the objective was to search for a specific string in a text file using the `grep` command. The goal was to locate a flag hidden within the contents of the file.

## Steps Taken

1. **Using the `grep` Command**:
   I executed the `grep` command to search for the string "pwn.college" within the specified file `/challenge/data.txt`:
   ```bash
   grep "pwn.college" /challenge/data.txt
   ```

2. **Flag Retrieved**:
   The command successfully found and displayed the line containing the flag:
   ```bash
   pwn.college{QXFnDisFKJu1Z7AC9AEoazWirge.ddTM4QDLwITO0czW}
   ```


```bash
hacker@commands~grepping-for-a-needle-in-a-haystack:/home$ grep "pwn.college" /challenge/data.txt
pwn.college{QXFnDisFKJu1Z7AC9AEoazWirge.ddTM4QDLwITO0czW}
hacker@commands~grepping-for-a-needle-in-a-haystack:/home$ 
```

<img width="452" alt="image" src="https://github.com/user-attachments/assets/7e647374-95d9-4e02-a4db-f466ae8ea541">
