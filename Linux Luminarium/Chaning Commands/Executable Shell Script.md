### Challenge: Executable Shell Scripts

The objective of this challenge was to create and execute a shell script directly without explicitly using the `bash` command, and to retrieve a flag.

### Problem Breakdown
1. **Create a Shell Script**: You needed to create a shell script (`x.sh`) that performs a specific action.
2. **Make It Executable**: The script had to be made executable so that it could be run directly.
3. **Execute the Script**: You executed the script using its relative path (`./x.sh`) to obtain the flag.

### Step-by-Step Solution

#### 1. **Navigate to the Home Directory**
You started by navigating to your home directory:

```bash
cd
```

#### 2. **Create the Shell Script (`x.sh`)**
Next, you created the shell script using a text editor (in this case, `nano`):

```bash
nano x.sh
```

Inside the `x.sh` file, you likely wrote a command or sequence of commands that would eventually lead to the flag output.

#### 3. **Make the Script Executable**
After saving and closing the `x.sh` file, you used the `chmod` command to make the script executable:

```bash
chmod +x x.sh
```

This grants the script the necessary permission to be executed directly from the terminal.

#### 4. **Execute the Script**
Finally, you ran the script using the relative path `./x.sh`:

```bash
./x.sh
```

This executed the script, and you received the following output:

```
Congratulations on your shell script execution! Your flag:
pwn.college{UuBhiZfsZprWoDIiu13hNNMaDJ5.dRzNyUDLwITO0czW}
```

### General Approach

1. **Create the shell script**: Use a text editor to create a `.sh` file containing the required commands.
2. **Make the script executable**: Use `chmod +x` to grant executable permissions.
3. **Execute the script**: Run the script using `./` followed by the script name (`./x.sh`) to execute it.
4. **Receive the flag**: Upon successful execution, the script outputs the flag.

This method demonstrates how to write, modify permissions, and execute a shell script directly from the terminal in Linux/Unix environments.

```bash
hacker@chaining~executable-shell-scripts:/home$ cd
hacker@chaining~executable-shell-scripts:~$ nano x.sh
hacker@chaining~executable-shell-scripts:~$ chmod +x x.sh
hacker@chaining~executable-shell-scripts:~$ ./x.sh
Congratulations on your shell script execution! Your flag:
pwn.college{UuBhiZfsZprWoDIiu13hNNMaDJ5.dRzNyUDLwITO0czW}
hacker@chaining~executable-shell-scripts:~$

```

![image](https://github.com/user-attachments/assets/8d62adfd-f543-42ef-8dcf-cf84bb14c618)

