# Bash Cheatsheet

This is a "cheat sheet" of Bash commands I curently know and use:

<h3>Basic Console Commands</h3>

Command | Description | Options
------------ | ------------- | -------------
`cd <directory path>` | "change directory" - changes the folder you are operating in | `~` - to home directory<br>`../` - up one folder
`mkdir <folder name>` | "make directory" - creates a new folder |
`rm <file name>` | "remove file" - delete file | `-r` - delete folder and all contents inside
`pwd` | "print working directory" -<br>displays the file path of the folder you are working in. |
`ls` | "list" -<br>lists files and folders in the folder you are working in | `-a` - list hidden files too
`touch <filename>` | creates a new file |
`explorer` | Open the current folder in Windows Explorer |
`echo 'alias <alias-name>="<path>"' >> ~/.bashrc` | Add the specified line into my .bashrc file <br> this will create an shortcut for the specified program |
`vim <file>` | Open the specified file into vim text editor |
`ctrl+z` | Stops the process | `jobs` - view jobs you have running <br>`fg 1` - resume a stopped job, for just one job fg is enough
`man <command>` | To display the manual of a command |
`cp <file> <from/directory/path> <to/directory/path> | copy a file from a location to another location
`mv <from/directory/path> <to/directory/path> ` | move all files and folders from a location to another location
