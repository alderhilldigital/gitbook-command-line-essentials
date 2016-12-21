# cd

The cd command is short for **'c**hange **d**irectory'. It is used to move from one directory to another similar to double clicking on a folder icon in a window based explorer.

**Example**

`cd project`

This will look for a directory called 'project' in the current directory and, if it exists, make it the current directory.

If the directory does not exist the following error will be displayed:

`cd: no such file or directory: project`



**Forward Slash \(/\)**

Using a forward slash when entering a directory path with make it an 'absolute' path. This means that it will start in the [root directory](/root-directory.md).

**Example**

`cd /project`

This will look for a directory called 'project' in the [operating system](/operating-system.md)'s [root directory](/root-directory.md).



**Tilde \(~\)**

Using a tilde when entering a directory path will start the path in the current user's home directory.

**Example**

`cd ~/project`



**Full stop \(.\)**

A full stop is used to indicate the current directory. This could be used when trying to reference a file in the current directory.

**Example**

`./project.zip`



**Double Full Stop \(..\)**

The double full stop is used to reference a directory's parent directory.

**Example**

`cd ../project`

This will look for the directory that contains the 'project' directory and will set it as the current directory.

