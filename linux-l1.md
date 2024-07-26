# Linux Baasic Commands

## `ls`

List files and directories in the current working directory


## `pwd`

print the current working directory


## `cd`

change directory


## `mkdir`

create directories


## `cp`

Copy

`cp <source> <destination>` Copy source file/dir to destination directory


## `mv`

Move or rename

`mv <source> <destination>` Move source file/dir to destination directory


## `rm`

Delete files and folders

`rm -r <folder/directory name>` delete specified directory and all of its subdirectories and the files within those subdirectories recursively.

`-i` flag in conjunction with the `-r` flag, will prompt for confirmation before deleting each file and directory.


## `touch`

Creates an empty file or updates the timestamp of an existing file

`touch <file name>`
Create file with given name.


## `clear`

Clears the terminal screen

Alternatively, `Alt + L` achieves a similar result.


## `cat`

Prints the contents of the file


## `less`

used when the output printed by any command is larger than the screen space and needs scrolling

`-S` flag with less to enable line wrapping

`-N` flag with less to display line numbers


## `man`
Display the manual page for a specific command. It provides detailed information about the command, including its syntax, options, and examples.


## `uname`

Displays information about the system’s kernel, including the kernel name, hostname, kernel release, kernel version, and machine hardware name.

`-a` with uname command stands for “all”, prints out the complete information.
`-s` to display the kernel name.
`-n` to display the hostname.
`-r` to display the kernel release.
`-v` to display the kernel version.
`-m` to display the machine hardware name.


## `whoami`

returns the current user’s username.


## `grep`

a powerful and versatile text search tool in Linux and Unix-based operating systems. It can search for specific patterns or strings in one or more files and filter the output of other commands.

The `grep` command stands for “global regular expression print,” which reflects its ability to search for regular expressions across multiple lines and files.


## `head` and `tail`
head and tail commands display the first 10 lines of a file by default.

`-n` option, followed by the number of lines you want to display.


## `chmod`

Change the permissions of a file or directory.


## `chown` 
Change the ownership of a file or directory.


## `sudo`

Escalate privileges. This command is equivalent to logging in as root.


## `cal`

Displays a well-presented calendar on the terminal.


## `whereis`

Locates the binary, source, and manual pages for a specific command or program.


## `whatis`

Displays a short description of a command or program.


## `useradd`

Create a new user in Linux.


## `usermod`

Used to modify existing users. Modify any value of the user including the groups, the permissions, etc.


## `passwd`
Set the password for your own account, or if you have the permissions, set the password for other accounts.


