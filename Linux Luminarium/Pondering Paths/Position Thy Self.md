# Challenge: Absolute Path Execution

## Challenge Overview

In this challenge, the task was to successfully execute a program located at an absolute path after navigating to the appropriate directory. The program checks whether the user is in the correct directory (`/sys`) before allowing execution.

## Steps Taken

1. **Initial Prompt**: 
   Upon trying to run `/challenge/run` from the home directory (`~`), the challenge returned an error:
   ```bash
   Incorrect...
   You are not currently in the /sys directory.
   Please use the `cd` utility to change directory appropriately.
   ```

2. **Changing to the Correct Directory**:
   Based on the error message, I realized the program expected me to be in the `/sys` directory. I used the `cd` command to change to the required directory:
   ```bash
   cd /sys
   ```

3. **Executing the Program**:
   After moving to `/sys`, I executed the program again using the absolute path:
   ```bash
   /challenge/run
   ```

4. **Flag Retrieval**:
   Upon successful execution, the challenge returned the flag:
   ```bash
   Correct!!!
   /challenge/run is an absolute path, invoked from the right directory!
   Here is your flag:
   pwn.college{0DIW8j8J7yBiMjGuGUZbnSpCU_R.dZDN1QDLwITO0czW}
   ```
```bash
hacker@paths~position-thy-self:/home$ cd
hacker@paths~position-thy-self:~$ /challenge/run
Incorrect...
You are not currently in the /sys directory.
Please use the `cd` utility to change directory appropriately.
hacker@paths~position-thy-self:~$ cd /sys
hacker@paths~position-thy-self:/sys$ /challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
pwn.college{0DIW8j8J7yBiMjGuGUZbnSpCU_R.dZDN1QDLwITO0czW}
hacker@paths~position-thy-self:/sys$ 
```


<img width="452" alt="image" src="https://github.com/user-attachments/assets/c0689339-d939-4ad8-b0f8-a9123b7f4911">
