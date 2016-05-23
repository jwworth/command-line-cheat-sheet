# Command Line Cheat Sheet

> 'The less effort, the faster and more powerful you will be.' —Bruce Lee

The goal of this document is to be the most exhaustive UNIX command line cheat sheet on the internet.

### Contents

* [Basics](#basics)
* [File Management](#file-management)
* [Directory Management](#directory-management)
* [Network Management](#network-management)
* [OS Management](#os-management)
* [Manipulate Commands](#manipulate-commands)
* [Etc.](#etc)
* [License](#license)

---

### Basics

| Description | Command |
| ----------- | ----------- |
| Format and display the online manual pages | `$ man <command>` |

### File Management

| Description | Command |
| ----------- | ----------- |
| Copy a file | `$ cp <source_file> <target_file>` |
| Move a file | `$ mv <source> <target>` |
| Concatenate and print a file | `$ cat <file>` |
| Display the last part of a file | `$ tail <file>` |
| Display the last part of a file, and wait for additional data (useful for logs) | `$ tail -f <file>` |
| Display the first lines of a file | `$ head <file>` |
| Remove a file | `$ rm <file>` |
| Securely remove a file | `$ srm <file>` |
| Open a file | `$ open <file>` |
| Creates a file, or update the timestamp on a file if it already exists | `$ touch <file>` |
| Direct the output of a command to a file | `$ <cmd> > <file>` |
| Append the output of a command to a file | `$ <cmd> >> <file>` |
| Print a file | `$ lpr <file>` |
| Count the words in a file | `$ wc <file>` |
| Secure copy a file to a remote host | `$ scp <file> <user>@<host>:/some/path` |
| Replace a word in a file with the stream editor | `$ sed s/maine/california/g states` |
| Find a file | `$ locate <file>` |
| Find a pattern in a file | `$ grep <pattern> <file>` |

### Directory Management

| Description | Command |
| ----------- | ----------- |
| Return working directory name | `$ pwd` |
| List directory contents | `$ ls` |
| List directory contents with extra details | `$ ls -l` |
| List directory contents including names that begin with `.` | `$ ls -a` |
| Change directories | `$ cd <directory>` |
| Change directory to your home directory | `$ cd ~` |
| Change directories one level up | `$ cd ..` |
| Make a directory | `$ mkdir <name>` |
| Remove a directory | `$ rmdir <name>` |
| Remove a non-empty directory | `$ rm -rf <name>` |

### Network Management

| Description | Command |
| ----------- | ----------- |
| Send a packet to a network host | `$ ping http://some.place` |
| Establish an SSH connection | `$ ssh <username>@<host>` |
| Learn about your network | `$ ifconfig` |
| Transfer data from a URL | `$ curl <url>` |
| Transfer data from a URL (alternate) | `$ wget <url>` |

### OS Management

| Description | Command |
| ----------- | ----------- |
| Terminate a signal or process | `$ kill <pid>` |
| Continue a program | `fg` |
| Display free disk space | `$ df` |
| Locate a program file in the user's path | `$ which <program>` |
| Locate a program file, or multiple files, in the user's path (alternate) | `$ type <program_1> <program_2>` |
| Locate a program | `$ whereis <program>` |
| Search the whatis databse for system comands | `$ whatis <command>` |
| Searches the whatis database for strings | `$ apropos <command>` |
| Determine the type of a program (bash) | `$ type -t <program>` |
| Display who is logged in | `$ who` |
| Change a user's password | `$ passwd <user>` |
| Print operating system name | `$ uname -a` |
| Display the current username | `$ whoami` |
| Display currently running processes | `$ ps aux` |
| Display sorted information about currently running processes | `$ top` |
| Show how long system has been running | `$ uptime` |
| End text input for many UNIX programs (kills man programs) | `CTRL-d` |
| Execute a command as another user | `$ sudo <command>` |

### Manipulate Commands

| Description | Command |
| ----------- | ----------- |
| Interrupt a running program | `CTRL-c` |
| Delete the last character typed | `CTRL-h` |
| Delete the last word typed | `CTRL-w` |
| Delete the last line typed | `CTRL-u` |
| Yank back the last item erased | `CTRL-y` |
| Delete the rest of the line | `CTRL-k` |
| Go to the start of the line | `CTRL-a` |
| Go to the end of the line | `CTRL-e` |
| Go backward without deleting | `CTRL-b` |
| Go forward without deleting | `CTRL-f` |
| Show the last line typed | `CTRL-p` |
| Go forward in the history of commands | `CTRL-n` |
| Complete filename or command up to the point of uniqueness | `TAB` |
| Search through previously typed commands | `CTRL-r` |
| Clear the window | `$ clear` |
| Clear the window (alternate) | `CTRL-l` |
| Send ('pipe') the output of one command to another command | `$ <commmand_1> <commmand_2>` |
| Repeat the previous command | `!! ` |
| Repeat the last command that starts with a pattern | `!<pattern>` |


### Etc.

| Description | Command |
| ----------- | ----------- |
| Show the current date and time | `$ date` |
| Show the current calendar | `$ cal` |
| Show the current calendar for the year | `$ cal -y` |
| Time any command | `$ time <commmand>` |
| Match any character | `$ *` |
| Match any character in the brackets (will `cat` 'hat.txt' or 'bat.txt') | `$ cat [hb]at.txt` |
| Execute a program periodically, with output | `$ watch <commmand>` |
| Repeat a command | `$ repeat <n> <command>` |

### License

This project is released under the [MIT License](http://www.opensource.org/licenses/MIT).
