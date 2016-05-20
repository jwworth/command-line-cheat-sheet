# Command Line Cheat Sheet

> 'The less effort, the faster and more powerful you will be.' —Bruce Lee

The goal of this document is to be the most exhaustive UNIX command line cheat sheet on the internet.

[White Belt](#white-belt)
[Yellow Belt](#yellow-belt)
[Green Belt](#green-belt)

---

### White Belt

Format and display the online manual pages:

```
$ man <command>
```

Return working directory name:

```
$ pwd
```

List directory contents:

```
$ ls
```

List directory contents with extra details:

```
$ ls -l
```

List directory contents including names that begin with `.`:

```
$ ls -a
```

Change directories:

```
$ cd <directory>
```

Change directory to your home directory:

```
$ cd ~
```

Copy a file:

```
$ cp <source_file> <target_file>
```

Move a file:

```
$ mv <source> <target>
```

Change directories one level up:

```
$ cd ..
```

Make a directory:

```
$ mkdir <name>
```

Remove a directory:

```
$ rmdir <name>
```

Remove a non-empty directory:

```
$ rm -rf <name>
```

Concatenate and print a file:

```
$ cat <file>
```

Display the last part of a file:

```
$ tail <file>
```

Display the first lines of a file:

```
$ head <file>
```

Remove a file:

```
$ rm <file>
```

Securely remove a file:

```
$ srm <file>
```

### Yellow Belt

Interrupt a running program:

```
CTRL-c
```

Continue a program:

```
fg
```

Delete the last character typed:

```
CTRL-h
```

Delete the last word typed:

```
CTRL-w
```

Delete the last line typed:

```
CTRL-u
```

End text input for many UNIX programs (kills man programs):

```
CTRL-d
```

Delete the rest of the line:

```
CTRL-k
```

Go to the start of the line:

```
CTRL-a
```

Go to the end of the line:

```
CTRL-e
```

Go backward without deleting:

```
CTRL-b
```

Go forward without deleting:

```
CTRL-f
```

Show the last line typed:

```
CTRL-p
```

Go forward in the history of commands:

```
CTRL-n
```

Complete filename or command up to the point of uniqueness

```
TAB
```

Repeate the previous command:

```
!!
```

Repeat the last command that starts with a pattern:

```
!<pattern>
```

Terminate a signal or process:

```
$ kill <pid>
```

Execute a command as another user:

```
$ sudo <command>
```

Show the current date and time:

```
$ date
```

Show the current calendar:

```
$ cal
```

Show the current calendar for the year:

```
$ cal -y
```

Time any command:

```
$ time <commmand>
```

Creates a file, or update the timestamp on a file if it already exists:

```
$ touch <file>
```

Send ('pipe') the output of one command to another command:

```
$ <commmand_1> | <commmand_2>
```

Match any character:

```
$ *
```

Match any character in the brackets (will `cat` 'hat.txt' or 'bat.txt'):

```
$ cat [hb]at.txt
```

### Green Belt

Locate a program file in the user's path:

```
$ which <program>
```

Locate a program file, or multiple files, in the user's path (alternate):

```
$ type <program_1> <program_2>
```

Determine the type of a program (bash):

```
$ type -t <program>
```

### License

This project is released under the [MIT License](http://www.opensource.org/licenses/MIT).
