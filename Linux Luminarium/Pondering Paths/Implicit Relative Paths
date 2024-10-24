# Challenge: Implicit Relative Path Execution

## Challenge Overview

In this challenge, the objective was to execute a program located at a relative path while navigating through directories. The challenge tested understanding of relative paths and their relationship with the current working directory.

## Steps Taken

1. **Initial Attempts**:
   I initially tried executing the command directly, assuming it was in the root directory (`/`), but I encountered the following error:
   ```bash
   bash: hacker@dojo:/$: No such file or directory
   ```

2. **Trying to Run from Home Directory**:
   I attempted running the program from my home directory (`~`), but this also failed:
   ```bash
   challenge/run
   bash: challenge/run: No such file or directory
   ```

3. **Navigating to the Correct Directory**:
   Based on the implicit hint that the program might be in a different directory, I navigated to the root (`/`) and attempted to navigate deeper into `tmp/a/b` directory and run a file `my_file`, but again hit an error:
   ```bash
   bash: cd: tmp/a/b: No such file or directory
   bash: ./my_file: No such file or directory
   ```

4. **Executing the Program**:
   Finally, while in the root directory (`/`), I ran the `challenge/run` command directly:
   ```bash
   challenge/run
   ```

5. **Flag Retrieved**:
   The program ran successfully, and the flag was displayed:
   ```bash
   Correct!!!
   challenge/run is a relative path, invoked from the right directory!
   Here is your flag:
   pwn.college{Us1pJkmUyOcp6KcAXOn5yRmIYwh.dlDN1QDLwITO0czW}
   ```



```bash
hacker@paths~implicit-relative-paths-from-:/home$ hacker@dojo:/$ challenge/run
bash: hacker@dojo:/$: No such file or directory
hacker@paths~implicit-relative-paths-from-:/home$ cd
hacker@paths~implicit-relative-paths-from-:~$ challenge/run
bash: challenge/run: No such file or directory
hacker@paths~implicit-relative-paths-from-:~$ cd /
hacker@paths~implicit-relative-paths-from-:/$ cd tmp/a/b
./my_file
bash: cd: tmp/a/b: No such file or directory
bash: ./my_file: No such file or directory
hacker@paths~implicit-relative-paths-from-:/$ challenge/run
Correct!!!
challenge/run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{Us1pJkmUyOcp6KcAXOn5yRmIYwh.dlDN1QDLwITO0czW}
hacker@paths~implicit-relative-paths-from-:/$ 

```
