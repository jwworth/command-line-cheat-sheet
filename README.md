# Command Line Cheat Sheet

> 'The less effort, the faster and more powerful you will be.' —Bruce Lee

The goal of this document is to be the most exhaustive UNIX command line cheat sheet on the internet.

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

Change directories:

```
$ cd <directory>
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
$ tail
```

Display the first lines of a file:

```
$ head
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

### License

This project is released under the [MIT License](http://www.opensource.org/licenses/MIT).
