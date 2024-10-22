# Challenge: Duplicating Piped Data with Tee

```bash
hacker@piping~duplicating-piped-data-with-tee:/home$ cd
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn | tee output1 | /challenge/college
Processing...
WARNING: you are overwriting file output1 with tee's output...
The input to 'college' does not contain the correct secret code! This code 
should be provided by the 'pwn' command. HINT: use 'tee' to intercept the 
output of 'pwn' and figure out what the code needs to be.
hacker@piping~duplicating-piped-data-with-tee:~$ cat output1
Usage: /challenge/pwn --secret [SECRET_ARG]

SECRET_ARG should be "QHCtnNDy"
hacker@piping~duplicating-piped-data-with-tee:~$  /challenge/pwn --secret QHCtnNDy | /challenge/college
Processing...
Correct! Passing secret value to /challenge/college...
Great job! Here is your flag:
pwn.college{QHCtnNDywSMo7aRZkDCoU_NnFsT.dFjM5QDLwITO0czW}
hacker@piping~duplicating-piped-data-with-tee:~$

```
## Flag
<img width="452" alt="image" src="https://github.com/user-attachments/assets/2ec38de1-9acb-4105-8dc2-2a91104c6696">
