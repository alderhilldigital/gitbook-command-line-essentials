# grep

The grep command is short for **g**lobally search for** re**gular expression and **p**rint. It is used to search for text or a regular expression in a file or output specified when calling the command.

**Example**

`grep "test" info.log`

This will display each line, from the info.log file, that contain the text "test".

**x option \(-x\)**

This option will display only lines that have an exact match to a word e.g. "apple" will not get a match on "apples".

**v option \(-v\)**

This option will display the inverse results i.e. all the results that do **not** include the search term.

**i option \(-i\)**

This option will make the search case insensitive e.g. "APPLE" will get a match on "apple"

**ABC options \(-A -B -C\)**

These options return the lines before and after the line containing the matching search

**Examples**

`grep "test" -A 2 -B 3 info.log`

This example will return any line containing the text "test" and the 2 lines before it and the 3 lines after it.

`grep "test" -C 3 info.log`

This example will return any line containing the text "test" and the 3 lines before and after it.

