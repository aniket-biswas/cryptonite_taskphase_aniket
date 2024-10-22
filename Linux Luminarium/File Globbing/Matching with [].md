# Matching with []

This challenge involves using globbing patterns and understanding how to handle working directories properly to retrieve a flag.

## Steps:

1. **Ensure the working directory is set to `/home/hacker`:**

    Before running the command, your current working directory must be `/home/hacker`. You can verify this by running:

    ```bash
    pwd
    ```

    If you are not in `/home/hacker`, use the following command to navigate there:

    ```bash
    cd
    ```

2. **Run the command with the correct file path:**

    Since the files are in a different directory, you need to specify the absolute path to the files. Use the following command to run the challenge:

    ```bash
    /challenge/run /challenge/files/file_[bash]
    ```

3. **Retrieve the flag:**

    After running the command correctly, the output will be:

    ```
    You got it! Here is your flag!
    pwn.college{o9qeYgzXOPkNEXwkGYCfZOq3wb6.dRjM4QDLwITO0czW}
    ```

## Summary:

This challenge required understanding the importance of being in the correct working directory and using absolute paths for files located outside of the current directory. Once the correct path is specified, the command will successfully return the flag.

![image](https://github.com/user-attachments/assets/d0b4cd3a-3ece-4d96-bd30-60d23a7c7f8f)
