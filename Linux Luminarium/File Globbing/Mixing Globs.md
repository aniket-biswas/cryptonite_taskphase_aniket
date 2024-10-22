# Mixing Globs

This challenge involves using globbing patterns to match file names and retrieve a flag. The goal is to use the correct glob pattern while ensuring you don't pass multiple arguments to the command.

## Steps:

1. **Navigate to the `/challenge/files` directory:**

    First, move to the directory where the files are located:

    ```bash
    cd /challenge/files
    ```

2. **Avoid passing multiple arguments to the command:**

    When running the command, ensure you don't pass multiple arguments. For example, the following attempt will fail:

    ```bash
    /challenge/run * in *
    ```

    This results in an error because globbing expanded to more than one argument. You must provide a single glob pattern.

3. **Use the correct globbing pattern:**

    The goal is to match files starting with one of the characters `[c]`, `[e]`, or `[p]`, followed by any sequence of characters. Use the following command:

    ```bash
    /challenge/run [cep]*
    ```

    This pattern matches files starting with any of the characters `c`, `e`, or `p`.

4. **Retrieve the flag:**

    After running the correct command, you will receive the following output:

    ```
    You got it! Here is your flag!
    pwn.college{sn9YDNmB_2MrGzCgLj-itd3QZO1.dVjM4QDLwITO0czW}
    ```

## Summary:

This challenge required careful use of globbing patterns to avoid passing multiple arguments and correctly match the required files. The globbing pattern `[cep]*` successfully matches the files, and running the command with this pattern returns the flag.


![image](https://github.com/user-attachments/assets/cd68dc41-07a3-442b-b879-3dfb107751e7)
