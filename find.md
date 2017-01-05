# find

The find command is used to search through a directory structure and find any files matching the term passed to it. The term will include a definition of what to search e.g. a name or file size

**Examples**

`find /usr/bin -name cd`

This will return the path to the cd executable.

`find /Users/jim -size +1048576`

This will return the paths to all files larger than 1048576 bytes = 1Mb

