# Matching with `?`

This repository documents the solution to a shell-based globbing challenge.

## Challenge Description

The task required running a binary located inside a directory named `challenge` using a combination of shell commands and globbing techniques. The program needed to be invoked using an absolute path to display the flag.

### Steps to Solve

1. **Globbing to Access the Directory:**
   The directory `/challenge` could be accessed by using the globbing pattern `/?ha??enge`. This pattern uses `?` to match any single character in place of letters. By running the following command, I was able to navigate to the correct directory:
   
   ```bash
   cd /?ha??enge

![image](https://github.com/user-attachments/assets/92c0e795-0218-4cff-aba3-c97b937011e6)
