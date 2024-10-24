# Challenge: Creating Files and Executing a Program

## Challenge Overview

In this challenge, the objective was to create files with specific names in the `/tmp` directory and execute a program to retrieve a flag. This exercise focused on file manipulation and command execution in a Linux environment.

## Steps Taken

1. **Navigating to the Temporary Directory**:
   I changed my working directory to `/tmp`:
   ```bash
   cd /tmp
   ```

2. **Creating Files**:
   I created files using the `touch` command. I created one file:
   - `pwn Command- touch college`
   
   This was done with the following command:
   ```bash
   touch pwn Command- touch college
   ```

3. **Listing the Files**:
   After creating the files, I listed the contents of the `/tmp` directory to verify their creation:
   ```bash
   ls
   ```

4. **Executing the Program**:
   I ran the program located at `/challenge/run`:
   ```bash
   /challenge/run
   ```

5. **Flag Retrieved**:
   The program executed successfully and returned the flag:
   ```bash
   Success! Here is your flag:
   pwn.college{sgrU-2fyMa-Ef1LtGs2K6iu89Ok.dBzM4QDLwITO0czW}
   ```


```bash
hacker@commands~touching-files:/home$ cd /tmp
hacker@commands~touching-files:/tmp$ touch pwn comma
hacker@commands~touching-files:/tmp$ touch pwn Command- touch college
hacker@commands~touching-files:/tmp$ ls
Command-  college  hsperfdata_root  tmp.MiOQGWw5Zc  vscode-git-bc8b5531dd.sock                            vscode-ipc-ce973b01-5ff4-4f46-b0fd-698dc094bba4.sock
bin       comma    pwn              touch           vscode-ipc-6e24777e-72ac-4a96-b1b9-90623cb818f7.sock
hacker@commands~touching-files:/tmp$ /challenge/run
Success! Here is your flag:
pwn.college{sgrU-2fyMa-Ef1LtGs2K6iu89Ok.dBzM4QDLwITO0czW}
hacker@commands~touching-files:/tmp$
```

<img width="452" alt="image" src="https://github.com/user-attachments/assets/57653a6f-fb46-4014-bb17-8a71d22c4070">
