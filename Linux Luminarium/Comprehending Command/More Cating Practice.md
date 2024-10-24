# Challenge: Retrieving a Flag Without Changing Directories

## Challenge Overview

In this challenge, the objective was to retrieve the contents of a flag file located in a different directory without using the `cd` command. This exercise focused on understanding absolute paths and their usage for file access.

## Steps Taken

1. **Using the `cat` Command with Absolute Path**:
   Given the instruction to avoid changing directories, I used the `cat` command to directly access the flag file located at `/usr/lib/php/flag`:
   ```bash
   cat /usr/lib/php/flag
   ```

2. **Flag Retrieved**:
   The command executed successfully, displaying the contents of the file, which included the flag:
   ```bash
   pwn.college{IqkK9bQMnvV0gRjVfcdgB3v4JJ9.dBjM5QDLwITO0czW}
   ```


```bash
You cannot use the 'cd' command in this level, and must retrieve the flag by 
absolute path. Plus, I hid the flag in a different directory! You can find it 
in the file /usr/lib/php/flag. Go cat it out **without** cding into that 
directory!
hacker@commands~more-catting-practice:/home$ cat /usr/lib/php/flag
pwn.college{IqkK9bQMnvV0gRjVfcdgB3v4JJ9.dBjM5QDLwITO0czW}
hacker@commands~more-catting-practice:/home$

```

<img width="452" alt="image" src="https://github.com/user-attachments/assets/d70d3ed6-b206-4e03-bf41-260f0e6b0492">
