# Challenge: Split-piping stderr and stdout

```bash
hacker@piping~split-piping-stderr-and-stdout:/home$ /challenge/hack 2>/challenge/the >/challenge/planet
bash: /challenge/the: Permission denied
hacker@piping~split-piping-stderr-and-stdout:/home$ /challenge/hack 2>/challenge/the >/challenge/planet
bash: /challenge/the: Permission denied
hacker@piping~split-piping-stderr-and-stdout:/home$ / challenge/hack › ›(/challenge/planet) 2› ›(/challenge/the)
bash: syntax error near unexpected token `('
hacker@piping~split-piping-stderr-and-stdout:/home$ / challenge/hack › ›( /challenge/planet) 2› ›(/challenge/the)
bash: syntax error near unexpected token `('
hacker@piping~split-piping-stderr-and-stdout:/home$ /challenge/hack > >( /challenge/planet) 2> >(/challenge/the)
Congratulations, you have learned a redirection technique that even experts 
struggle with! Here is your flag:
pwn.college{4aTjxDLf5eUWGJ24UmL41JqvAR2.dFDNwYDLwITO0czW}
hacker@piping~split-piping-stderr-and-stdout:/home$ 

```
## Flag

pwn.college{4aTjxDLf5eUWGJ24UmL41JqvAR2.dFDNwYDLwITO0czW}

<img width="452" alt="image" src="https://github.com/user-attachments/assets/206ab049-bea2-47cb-8f49-1011ce381bf5">
