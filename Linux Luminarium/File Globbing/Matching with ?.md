# Matching with `?`
# Challenge: Globbing with Path Matching

In this challenge, the objective is to use globbing techniques to match a directory name and execute a command in a specific working directory.

## Steps:

1. **Navigate to the `/challenge` directory using globbing:**

    Instead of directly typing the full path, we use globbing to match the directory name. The `?` wildcard matches a single character, so use the following command:

    ```bash
    cd /?ha??enge
    ```

    This will navigate to the `/challenge` directory.

2. **Run the challenge command:**

    Once you're in the `/challenge` directory, simply run the challenge command:

    ```bash
    /challenge/run
    ```

3. **Retrieve the flag:**

    After successfully running the command, the output will be:

    ```
    You ran me with the working directory of /challenge! Here is your flag:
    pwn.college{YCLnF0gf2Et37aYmnMRBz2sDoIZ.dJjM4QDLwITO0czW}
    ```

## Summary:

This challenge required using globbing (`?`) to match specific parts of a directory name and running a command from the correct working directory. Successfully doing so returns the flag.



![image](https://github.com/user-attachments/assets/55433575-225d-4f97-949b-1e0a9fb99fbd)

