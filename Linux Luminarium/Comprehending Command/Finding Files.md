# Challenge: Finding Files

1. **Find Command Usage:**
   - You attempted to find specific directories and files using `find`, but it seems that the paths you were checking either didn't exist or you didn't have the right permissions to access them.
   - Example: 
     ```bash
     find my_directory/my_subdirectory
     ```
     resulted in "No such file or directory," indicating that the specified path doesn't exist.

2. **Navigating Directories:**
   - You tried to use `cd` with `find`, which resulted in an error because `cd` cannot take the output of `find` as arguments. `cd` is used to change directories, and it expects a single path.
   - Correct usage would be something like:
     ```bash
     cd my_directory/my_subdirectory
     ```

3. **Permission Denied Errors:**
   - Many of your `find` commands resulted in "Permission denied" errors when searching in system directories. This is common when you do not have the necessary permissions to access certain directories. You can use `sudo` before your `find` command if you need to search directories that require higher privileges:
     ```bash
     sudo find / -name hacker
     ```

4. **Finding Files:**
   - You successfully found some files named `flag` in various directories, and you were able to view one of them (the path is `/opt/radare2/libr/arch/p/vax/flag`). The output seems to indicate that you found a flag in a CTF (Capture the Flag) style challenge:
     ```
     pwn.college{omDOTM-XwRnzgp8a_ODHiob5TFv.dJzM4QDLwITO0czW}
     ```

5. **Viewing Contents:**
   - The command `cat` showed that you tried to read a directory as a file, which is why you got the error "Is a directory." Make sure to check for files within directories instead.

If you have any specific questions or need further clarification on any of the commands or outputs, feel free to ask!


```bash
 hacker@commands~finding-files:/home$ find my_directory/my_subdirectory
find: ‘my_directory/my_subdirectory’: No such file or directory
hacker@commands~finding-files:/home$ cd find my_directory/my_subdirectory
bash: cd: too many arguments
hacker@commands~finding-files:/home$ find -name my_subfile
hacker@commands~finding-files:/home$ cd find -name my_subfile
bash: cd: too many arguments
hacker@commands~finding-files:/home$ cd
hacker@commands~finding-files:~$ find -name my_subfile
hacker@commands~finding-files:~$ find / -name hacker
/home/hacker
find: ‘/tmp/tmp.MiOQGWw5Zc’: Permission denied
find: ‘/etc/ssl/private’: Permission denied
find: ‘/var/cache/apt/archives/partial’: Permission denied
find: ‘/var/cache/ldconfig’: Permission denied
find: ‘/var/cache/private’: Permission denied
find: ‘/var/lib/apt/lists/partial’: Permission denied
find: ‘/var/lib/mysql-files’: Permission denied
find: ‘/var/lib/private’: Permission denied
find: ‘/var/lib/mysql’: Permission denied
find: ‘/var/lib/mysql-keyring’: Permission denied
find: ‘/var/lib/php/sessions’: Permission denied
find: ‘/var/log/private’: Permission denied
find: ‘/var/log/apache2’: Permission denied
find: ‘/var/log/mysql’: Permission denied
find: ‘/run/mysqld’: Permission denied
find: ‘/run/sudo’: Permission denied
find: ‘/root’: Permission denied
find: ‘/proc/tty/driver’: Permission denied
find: ‘/proc/1/task/1/fd’: Permission denied
find: ‘/proc/1/task/1/fdinfo’: Permission denied
find: ‘/proc/1/task/1/ns’: Permission denied
find: ‘/proc/1/fd’: Permission denied
find: ‘/proc/1/map_files’: Permission denied
find: ‘/proc/1/fdinfo’: Permission denied
find: ‘/proc/1/ns’: Permission denied
find: ‘/proc/7/task/7/fd’: Permission denied
find: ‘/proc/7/task/7/fdinfo’: Permission denied
find: ‘/proc/7/task/7/ns’: Permission denied
find: ‘/proc/7/fd’: Permission denied
find: ‘/proc/7/map_files’: Permission denied
find: ‘/proc/7/fdinfo’: Permission denied
find: ‘/proc/7/ns’: Permission denied
hacker@commands~finding-files:~$ find / -name flag
find: ‘/tmp/tmp.MiOQGWw5Zc’: Permission denied
find: ‘/etc/ssl/private’: Permission denied
/usr/local/lib/python3.8/dist-packages/pwnlib/flag
/usr/local/share/radare2/5.9.5/flag
find: ‘/var/cache/apt/archives/partial’: Permission denied
find: ‘/var/cache/ldconfig’: Permission denied
find: ‘/var/cache/private’: Permission denied
find: ‘/var/lib/apt/lists/partial’: Permission denied
find: ‘/var/lib/mysql-files’: Permission denied
find: ‘/var/lib/private’: Permission denied
find: ‘/var/lib/mysql’: Permission denied
find: ‘/var/lib/mysql-keyring’: Permission denied
find: ‘/var/lib/php/sessions’: Permission denied
find: ‘/var/log/private’: Permission denied
find: ‘/var/log/apache2’: Permission denied
find: ‘/var/log/mysql’: Permission denied
find: ‘/run/mysqld’: Permission denied
find: ‘/run/sudo’: Permission denied
find: ‘/root’: Permission denied
/opt/radare2/libr/arch/p/vax/flag
/opt/radare2/libr/flag
/opt/pwndbg/.venv/lib/python3.8/site-packages/pwnlib/flag
find: ‘/proc/tty/driver’: Permission denied
find: ‘/proc/1/task/1/fd’: Permission denied
find: ‘/proc/1/task/1/fdinfo’: Permission denied
find: ‘/proc/1/task/1/ns’: Permission denied
find: ‘/proc/1/fd’: Permission denied
find: ‘/proc/1/map_files’: Permission denied
find: ‘/proc/1/fdinfo’: Permission denied
find: ‘/proc/1/ns’: Permission denied
find: ‘/proc/7/task/7/fd’: Permission denied
find: ‘/proc/7/task/7/fdinfo’: Permission denied
find: ‘/proc/7/task/7/ns’: Permission denied
find: ‘/proc/7/fd’: Permission denied
find: ‘/proc/7/map_files’: Permission denied
find: ‘/proc/7/fdinfo’: Permission denied
find: ‘/proc/7/ns’: Permission denied
find: ‘/proc/942’: No such file or directory
find: ‘/proc/943’: No such file or directory
find: ‘/proc/947’: No such file or directory
/nix/store/1yagn5s8sf7kcs2hkccgf8d0wxlrv5sz-radare2-5.9.0/share/radare2/5.9.0/flag
/nix/store/pmvk2bk4p550w182rjfm529kfqddnvh3-python3.11-pwntools-4.12.0/lib/python3.11/site-packages/pwnlib/flag
hacker@commands~finding-files:~$ cat /opt/pwndbg/.venv/lib/python3.8/site-packages/pwnlib/flag
cat: /opt/pwndbg/.venv/lib/python3.8/site-packages/pwnlib/flag: Is a directory
hacker@commands~finding-files:~$ cat /opt/radare2/libr/arch/p/vax/flag
hacker@commands~finding-files:~$ cat /opt/radare2/libr/arch/p/vax/flag
pwn.college{omDOTM-XwRnzgp8a_ODHiob5TFv.dJzM4QDLwITO0czW}hacker@commands~finding-files:~$

```
