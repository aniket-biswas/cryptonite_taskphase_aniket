# Matching with `?`

This challenge demonstrates how to use shell globbing to match specific files within a directory and execute a command to retrieve a flag.

## Steps:

1. **Navigate to the `/challenge/files` directory:**

    Use the following command to change your current directory to where the challenge files are located:

    ```bash
    cd /challenge/files
    ```

2. **Run the challenge command using globbing:**

    In this step, use the globbing pattern `file_[absh]` to match files in the directory. Execute the command:

    ```bash
    /challenge/run file_[absh]
    ```

3. **Retrieve the flag:**

    After running the above command, you should see the following output with the flag:

    ```
    You got it! Here is your flag!
    pwn.college{MtSsmL7DM1uq_IqQby_yqmGsC6W.dNjM4QDLwITO0czW}
    ```

## Summary:

This challenge required navigating to a directory and using shell globbing to execute a specific command. The output included the flag which successfully completes the task.


![image](https://github.com/user-attachments/assets/92c0e795-0218-4cff-aba3-c97b937011e6)
