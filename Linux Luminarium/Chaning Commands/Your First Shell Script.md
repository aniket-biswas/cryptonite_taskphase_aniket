# Challenge: Your First Shell Script

```bash
acker@chaining~your-first-shell-script:/home$ cd
hacker@chaining~your-first-shell-script:~$ nano x.sh
hacker@chaining~your-first-shell-script:~$ chmod +x x.sh
chmod: cannot access 'x.sh': No such file or directory
hacker@chaining~your-first-shell-script:~$ cat x.sh
cat: x.sh: No such file or directory
hacker@chaining~your-first-shell-script:~$ cat pwn.sh
cat: pwn.sh: No such file or directory
hacker@chaining~your-first-shell-script:~$ nano x.sh
hacker@chaining~your-first-shell-script:~$ chmod +x x.sh
chmod: cannot access 'x.sh': No such file or directory
hacker@chaining~your-first-shell-script:~$ nano x.sh
hacker@chaining~your-first-shell-script:~$ 
hacker@chaining~your-first-shell-script:~$ cat x.sh
cat: x.sh: No such file or directory
hacker@chaining~your-first-shell-script:~$ cat x.shma
/challenge/pwn
/challenge/college

hacker@chaining~your-first-shell-script:~$ chmod +x x.shma
hacker@chaining~your-first-shell-script:~$ bash  x.shma

Please name your script with an '.sh' extension. This isn't strictly necessary 
eventually, but we'll keep things explicit for the next few levels.
hacker@chaining~your-first-shell-script:~$ nano x.sh


Use "fg" to return to nano.

[1]+  Stopped                 nano x.sh
hacker@chaining~your-first-shell-script:~$ fg
nano x.sh
hacker@chaining~your-first-shell-script:~$ cat x.sh
/challenge/pwn
/challenge/college

hacker@chaining~your-first-shell-script:~$ bash x.sh
Great job, you've written your first shell script! Here is the flag:
pwn.college{IFCwe46pClPfEQ6PKINCbiAmRRg.dFzN4QDLwITO0czW}
hacker@chaining~your-first-shell-script:~$

```

## Flag
`pwn.college{IFCwe46pClPfEQ6PKINCbiAmRRg.dFzN4QDLwITO0czW}`

![image](https://github.com/user-attachments/assets/1888eb96-f421-4df3-a6ed-2f60bd8addc0)
