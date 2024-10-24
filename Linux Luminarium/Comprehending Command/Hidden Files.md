# Challenge: Accessing Hidden Files

## Challenge Overview

In this challenge, the objective was to locate and read a hidden file within the root directory using the command line. This exercise emphasized the importance of recognizing and accessing hidden files in a Linux environment.

## Steps Taken

1. **Navigating to the Root Directory**:
   I changed my working directory to the root directory:
   ```bash
   cd /
   ```

2. **Listing All Files, Including Hidden Ones**:
   To locate hidden files, I used the `ls` command with the `-a` flag, which lists all files, including those that start with a dot:
   ```bash
   ls -a
   ```

   The output included the hidden file `.flag-257731780922907`.

3. **Accessing the Hidden File**:
   I used the `cat` command to read the contents of the hidden file:
   ```bash
   cat .flag-257731780922907
   ```

4. **Flag Retrieved**:
   The command successfully displayed the contents of the file, which included the flag:
   ```bash
   pwn.college{A1SV-OUNVn-1Yw7sRLvq_jblI3w.dBTN4QDLwITO0czW}
   ```



```bash
hacker@commands~hidden-files:/home$ cd /
hacker@commands~hidden-files:/$ ls -a
.  ..  .dockerenv  .flag-257731780922907  bin  boot  challenge  dev  etc  home  lib  lib32  lib64  libx32  media  mnt  nix  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
hacker@commands~hidden-files:/$ cat .flag-257731780922907
pwn.college{A1SV-OUNVn-1Yw7sRLvq_jblI3w.dBTN4QDLwITO0czW}
hacker@commands~hidden-files:/$ 

```
<img width="452" alt="image" src="https://github.com/user-attachments/assets/318b4230-8633-4ede-9f72-5ae22a279bf2">
