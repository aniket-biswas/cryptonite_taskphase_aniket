# Challenge: Printing Exported Variables

In this challenge, the objective is to print all currently set environment variables, particularly to locate the `FLAG` variable.

## Steps:

1. **Print the environment variables:**

    Use the `env` command to display all currently set environment variables:

    ```bash
    env
    ```

    This command will list all environment variables, along with their current values. The output will include various system-related variables, similar to the following:

    ```
    SHELL=/run/dojo/bin/bash
    COLORTERM=truecolor
    TERM_PROGRAM_VERSION=1.89.1
    HOSTNAME=variables~printing-exported-variables
    PWD=/home
    ...
    FLAG=pwn.college{UnVBkrgzicFPwwscQ-MBA-h0Fhc.dhTN1QDLwITO0czW}
    ...
    ```

2. **Identify the FLAG variable:**

    In the output, locate the `FLAG` variable. It should appear as follows:

    ```
    FLAG=pwn.college{UnVBkrgzicFPwwscQ-MBA-h0Fhc.dhTN1QDLwITO0czW}
    ```

3. **Retrieve the flag:**

    Once you have located the `FLAG` variable, you can take note of its value for further use or verification.

## Summary:

This challenge involved using the `env` command to print all environment variables, allowing you to locate the `FLAG` variable in your session.
