# whatis

The whatis command is used to give a brief description of what a command does.

**Example**

`whatis whatis`

This will return

`whatis(1) - search the whatis database for complete words`



_This will actually return all word matches on 'whatis', which is more than a single line entry. To do a closer match use the cap \(^\) symbol at the start of the search term to do a regular expression match where the line must begin with the search term._

_**Example**_

`whatis ^whatis`



