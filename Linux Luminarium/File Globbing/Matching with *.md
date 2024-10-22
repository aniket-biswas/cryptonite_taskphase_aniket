# Globbing Challenge Solution

This repository documents the solution to a shell-based globbing challenge.

## Challenge Description

The task required running a binary located inside a directory named `challenge` using a combination of shell commands and globbing techniques. The program needed to be invoked using an absolute path to display the flag.

### Steps to Solve

1. **Globbing to Access the Directory:**
   The directory `/challenge` could be accessed by using the wildcard `*`, which is a common shell globbing technique. By running `cd /ch*`, I was able to match the directory and navigate inside it.

2. **Running the Program:**
   The command `./run` tried to invoke the binary with a relative path, but it failed due to a permission or directory structure issue.
   
   By using an absolute path `/challenge/run`, the program successfully executed and returned the flag:

##Flag
pwn.college{gIr7Qad35zha2n4t5J76fcTF40H.dFjM4QDLwITO0czW}

![image](https://github.com/user-attachments/assets/42b02f60-fc91-4230-a0cc-bcceadc0165b)
