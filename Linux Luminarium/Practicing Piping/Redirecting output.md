# Challenge: Redirecting Output

In this challenge, the objective is to use an exclusionary globbing pattern to match files that do not start with specific characters in order to retrieve a flag.

## Steps:

1. **Navigate to the `/challenge/files` directory:**

    Begin by navigating to the directory where the challenge files are stored:

    ```bash
    cd /challenge/files
    ```

2. **Use an exclusionary globbing pattern:**

    The challenge requires using a globbing pattern that excludes certain characters. In this case, you need to exclude files that start with the characters `p`, `w`, or `n`. You can achieve this with the following command:

    ```bash
    /challenge/run [^pwn]*
    ```

    - `[^pwn]` is an exclusionary globbing pattern that matches any file that **does not** start with `p`, `w`, or `n`.

3. **Retrieve the flag:**

    Once you execute the correct command, you will receive the following output:

    ```
    You got it! Here is your flag!
    pwn.college{ow87zY_oTuyugqcPGFoJ_ccbejX.dZjM4QDLwITO0czW}
    ```

## Summary:

This challenge required using an exclusionary globbing pattern (`[^pwn]*`) to match files that do not begin with the specified characters (`p`, `w`, `n`). Running the correct command returns the flag.


# Challenge: Printing Exported Variables

In this challenge, the objective is to print all currently set environment variables, particularly to locate the `FLAG` variable.

## Steps:

1. **Print the environment variables:**

   Use the `env` command to display all currently set environment variables:

   ```bash
   env

<img width="452" alt="image" src="https://github.com/user-attachments/assets/d96cc6bd-92cf-4961-85bf-ad945510369a">
