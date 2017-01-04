# tail

The tail command is used to display the last 10 lines of any text passed to it.

**Example**

`tail info.log`

This will display the last 10 lines of the info.log file

**n option \(-n\)**

This option will display the number of lines following the option instead of the default 10 lines.

**Example**

`tail -n 5 info.log`

This will display the last 5 lines of the info.log file

**c option \(-c\)**

This option will display the number of bytes following the option instead of the default 10 lines.

**Example**

`tail -c 50 info.log`

This will display the last 50 bytes of the info.log file

f** option \(-\)**

This option will display the requested output from the file and continue to add any updates made to the file until the command is exited used \[ctrl+C\].

**Example**

`tail -f info.log`

This will display the last 10 lines of the info.log file and continue to add any new data added to the file.

