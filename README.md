# Linux Command Line Cheat Sheet

This cheat sheet contains commonly used commands for the Linux operating system. Below is a list of essential commands.

## File and Directory Operations

- `ls`: Lists files and folders in the current directory.
- `cd <directory>`: Changes the current directory.
- `pwd`: Displays the current directory path.
- `touch <file_name>`: Creates a new file or updates the timestamp of an existing one.
- `mkdir <folder_name>`: Creates a new folder.
- `rm <file_name>`: Deletes a file (use with caution, it's irreversible).
- `rmdir <folder_name>`: Deletes a folder (must be empty).
- `cp <source_file> <destination_file>`: Copies a file.
- `mv <source> <destination>`: Moves or renames a file or folder.

## File Content Operations

- `cat <file_name>`: Displays the contents of a file.
- `less <file_name>`: Displays file content page by page.
- `head <file_name>`: Displays the beginning of a file.
- `tail <file_name>`: Displays the end of a file.
- `grep "<search_text>" <file>`: Searches for text in a file.

## Permissions and User Operations

- `chmod <permissions> <file_name>`: Changes file permissions.
- `chown <user>:<group> <file_name>`: Changes the file's owner and group.
- `useradd <user>`: Adds a new user.
- `userdel <user>`: Deletes a user.
- `passwd <user>`: Changes a user's password.
- `groups <user>`: Lists the groups a user belongs to.

## Package Management

- `apt-get install <package_name>`: Installs a package.
- `apt-get remove <package_name>`: Removes a package.
- `apt-get update`: Updates the package list.
- `apt-get upgrade`: Upgrades existing packages.

These commands cover some of the fundamental Linux commands that are frequently used. You can refer to the manual page for each command by using `man command` for more information.


