# cp

The cp command is short for '**c**o**p**y'. It is used to copy files or directories from one location to another.

**Example**

`cp projects/test.html live/test.html`

This will copy the test.html file from the projects folder to the live folder.

**R option \(-R\)**

This option will recursively copy all files and directories referenced in the path given to the new location.

**Example**

`cp projects backups`

This will copy all files and directories from the 'projects' directory into the 'backups' directory.

**star symbol \(\*\)**

This is a wildcard operator that will match one or more of any character when selecting what files to copy.

**Example**

`cp projects/*.html projects/html`

This will copy all the files in the projects directory with .html in the file name into a directory called html in the projects directory.

