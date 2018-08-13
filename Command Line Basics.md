# Command Line Basics

The command line is a text interface for interacting with your computer.  Learning the basics of how to use the command line is generally necessary for programming and developing software.

This guide will cover the basics of how to open and use the command prompt, `cmd.exe`, command line interface on Windows PCs.  Other operating systems have their own command line interfaces which are similar, but have some differences.

## Opening a command prompt

To open a command prompt, open the start menu and type `cmd.exe`.  Open the first result - the `cmd.exe` program.  The window that opens should look something like this:

![](https://upload.wikimedia.org/wikipedia/commons/b/b3/Command_Prompt_on_Windows_10_RTM.png)

This is the window command prompt.  Once it is open you can type commands which execute with the context of the "current directory", which is listed before the `>` symbol.

## Command basics

When using the command line you will type a command followed by a space and then the arguments for the comamnd.  Note that if an argument has spaces in it you will need to surround it in double quotes.  To execute a command once you've typed it, simply press <kbd>Enter</kbd>.

If you ever need information on a command you can type `command /?`, replacing `command` with the name of the command you want information about.  Note: this only works for commands from the Windows operating system.

Whenever you provide a path to a command, the path is considered relative to the current directory unless you provide an absolute path, which starts with a disk letter (e.g. `C:\Program Files`).

Examples:

- `cls` - clears the console window.
- `cd "Program Files (x86)"` - if a "Program Files (x86)" folder is present in the current directory, the current directory is changed to it.
- `find /I "function" *.js` - Searches all files ending in `.js` for the string "function", ignoring case.


## Essential commands

### `cd`

The `cd` command can be used to change the current directory of the command window.

- To traverse up a directory type `cd ..`
- `cd` cannot be used to switch to switch to a directory on a different disk.  To switch to a different disk, type the disk drive letter for the disk you want to switch to followed by a colon.  E.g. `E:`
- To traverse up to the root of the current disk, type `cd \ `.
- Traverse a path by separating folder/file names with a backslash.  E.g. `cd ..\test\abc` traverses up a directory, then into the `test` directory, and finally into the `abc` directory inside the `test` directory.
 

### `cls`

The `cls` command clears all messages from the command line and presents a fresh prompt.

## Additional commands

You don't *need* to know these, but they can come in handy in certain situations.

### `find`

The `find` command can be used to search for a file or multiple files for a string.

### `dir`

The `dir` command lists all files and folders in the current directory.

### `del`

The `del` command can be used to delete a file.

### `mkdir`

The `mkdir` command can be used to create a new directory.

### `rmdir`

The `rmdir` command bcan be used to a delete an empty directory.

## Advanced Tweaks

### Cmder

[Cmder](http://cmder.net/) is an enhanced command line interface which you can use instead of `cmd.exe`.  It supports having multiple tabs, colors, and more.

![](http://puu.sh/BdkdZ.jpg)

### Open command window here

*NOTE: This option was removed from Windows 10.  If you're on Windows 10 and want to use it you'll have to [apply a registry tweak](https://www.howtogeek.com/302408/how-to-put-open-command-window-here-back-on-the-windows-right-click-menu/).*

In addition to opening the command prompt by starting `cmd.exe` directly, you can open a command window in a specific folder through a right-click context menu option.  To do this, open a folder in Windows Explorer, then hold <kbd>Shift</kbd> and right-click in the folder (not on a file), then click the "Open command window here" option.

![](http://puu.sh/Bdk55.png)