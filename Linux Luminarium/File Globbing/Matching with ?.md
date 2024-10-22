# Step 1: Navigating to the target directory
# In this case, the challenge directory is named 'challenge', but instead of typing it out fully,
# we're using globbing. The `?` matches any single character, allowing flexibility in the pattern.
cd /?ha??enge

# Step 2: Running the program
# Once we're in the '/challenge' directory, we run the program 'run', located in the same directory.
# We execute the program using its absolute path, which is '/challenge/run'. 
# This ensures that the program runs with the correct working directory.

# Running the following command
/challenge/run

# Expected Output:
# The program detects that the working directory is '/challenge' and prints the flag:
# pwn.college{YCLnF0gf2Et37aYmnMRBz2sDoIZ.dJjM4QDLwITO0czW}
![image](https://github.com/user-attachments/assets/f35a4ae6-0e69-41a4-afc6-0ee682b00cbb)
