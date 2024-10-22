# Challenge: Exporting Variables

In this challenge, the objective is to set and export environment variables to retrieve a flag.

## Steps:

1. **Set the first environment variable:**

    Start by setting the `COLLEGE` variable to `PWN`:

    ```bash
    COLLEGE=PWN
    ```

    After setting the variable, you will see a confirmation message.

2. **Export the second environment variable:**

    Next, export the `PWN` variable by using the following command:

    ```bash
    export PWN=COLLEGE
    ```

    After exporting the variable, you should see another confirmation message.

3. **Run the challenge command:**

    Start a new shell session by typing `sh`, and then execute the command to check if the variables are set correctly:

    ```bash
    sh
    /challenge/run
    ```

4. **Retrieve the flag:**

    If everything is set up correctly, you will see the following output:

    ```
    CORRECT!
    You have exported PWN=COLLEGE and set, but not exported, COLLEGE=PWN. Great job! Here is your flag:
    pwn.college{MffWaezniiI_qq4AsKfjCoHNNuT.dJjN1QDLwITO0czW}
    ```

## Summary:

This challenge required setting and exporting environment variables. You successfully exported `PWN=COLLEGE` while `COLLEGE=PWN` remained unset. The correct setup allowed you to retrieve the flag.
