# Challenge: Implicit Relative Path Execution

## Challenge Overview

The goal of this challenge was to execute a program using an implicit relative path (`./`) from the correct directory. This tested the understanding of how relative paths work in relation to the current working directory.

## Steps Taken

1. **Navigating to the Correct Directory**:
   First, I navigated to the `/challenge` directory where the program was located using the following command:
   ```bash
   cd /challenge
   ```

2. **Executing the Program with Implicit Relative Path**:
   Once inside the `/challenge` directory, I executed the program using the implicit relative path:
   ```bash
   ./run
   ```

3. **Flag Retrieved**:
   The program ran successfully, and the flag was displayed:
   ```bash
   Correct!!!
   ./run is a relative path, invoked from the right directory!
   Here is your flag:
   pwn.college{QqPvJM3soLkS1M-5iAs25kRYjY4.dFTN1QDLwITO0czW}
   ```



```bash
hacker@paths~implicit-relative-path:/home$ cd /challenge
hacker@paths~implicit-relative-path:/challenge$ ./run
Correct!!!
./run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{QqPvJM3soLkS1M-5iAs25kRYjY4.dFTN1QDLwITO0czW}
hacker@paths~implicit-relative-path:/challenge$ 

```
