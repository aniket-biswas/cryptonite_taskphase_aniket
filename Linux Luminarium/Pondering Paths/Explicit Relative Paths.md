# Challenge: Explicit Relative Path Execution

## Challenge Overview

In this challenge, the task was to execute a program using an explicit relative path from the root directory (`/`). The challenge reinforced the concept of using `./` to run files that are located in the current working directory.

## Steps Taken

1. **Navigating to the Root Directory**:
   The program needed to be run from the root directory (`/`). I changed the directory to `/` using:
   ```bash
   cd /
   ```

2. **Executing the Program with Explicit Relative Path**:
   I executed the program using an explicit relative path (`./challenge/run`), where `./` indicates the current directory:
   ```bash
   ./challenge/run
   ```

3. **Flag Retrieved**:
   The program executed successfully, and the flag was revealed:
   ```bash
   Correct!!!
   ./challenge/run is a relative path, invoked from the right directory!
   Here is your flag:
   pwn.college{Q1nLNXkNxcEPW51zK11BPdFRTYE.dBTN1QDLwITO0czW}
   ```


```bash
hacker@paths~explicit-relative-paths-from-:/home$ cd /
hacker@paths~explicit-relative-paths-from-:/$ ./challenge/run
Correct!!!
./challenge/run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{Q1nLNXkNxcEPW51zK11BPdFRTYE.dBTN1QDLwITO0czW}
hacker@paths~explicit-relative-paths-from-:/$

```
