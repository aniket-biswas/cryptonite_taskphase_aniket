# Matching paths with []

This challenge focuses on understanding how to use globbing to match file names and handle different working directories properly in order to retrieve the flag.

## Steps:

1. **Ensure your working directory is `/home/hacker`:**

    The challenge requires that you run the command from the `/home/hacker` directory. If you're not already there, you can navigate to it by running:

    ```bash
    cd
    ```

2. **Run the command with the correct file path:**

    Since the files are located in a different directory (`/challenge/files`), you need to specify the absolute path when using the globbing pattern. The correct command is:

    ```bash
    /challenge/run /challenge/files/file_[bash]
    ```

    This pattern matches files in the `/challenge/files` directory that end with one of the characters `b`, `a`, `s`, or `h`.

3. **Retrieve the flag:**

    After running the command with the correct working directory and file path, you will receive the following output:

    ```
    You got it! Here is your flag!
    pwn.college{o9qeYgzXOPkNEXwkGYCfZOq3wb6.dRjM4QDLwITO0czW}
    ```

## Summary:

This challenge required being in the correct working directory (`/home/hacker`) and using the absolute file path for globbing when files are in a different directory. Executing the command correctly yields the flag.

![Uploading image.png…]()
