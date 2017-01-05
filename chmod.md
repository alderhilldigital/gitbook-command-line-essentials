# chmod

The chmod command is short for '**ch**ange **mod**e'. It is used to set the read, write and execute permissions of a file for the file owner, those in the file group and everyone else. The file owner and group are set using the [chown](/chown.md) command.

**Numerical **

File permissions can be set numerically where numbers between 0 and 7 correspond to the 8 combinations of read \(r\), write \(w\) and execute \(x\).

| Number | Permissions |
| :--- | :--- |
| 0 | no permissions \(---\) |
| 1 | only execute \(--x\) |
| 2 | only write \(-w-\) |
| 3 | write and execute \(-wx\) |
| 4 | read only \(r--\) |
| 5 | read and execute \(r-x\) |
| 6 | read and write \(rw-\) |
| 7 | read, write and execute \(rwx\) |

**Examples**

`chmod 777 test.txt`

This will give read, write and execute permissions to the owner, the group and others.

`chmod 664 test.txt`

This will give read and write permissions to the owner and group and only read permissions to others.

**Symbols**

The file permissions can also be set using symbols for read \(r\), write \(w\), execute \(x\), owner \(u\), group \(g\), others \(o\), adding permissions \(+\), removing permissions \(-\) and setting permissions \(=\).

**Examples**

`chmod +x test.sh`

This will add execute permissions for everyone for test.sh

`chmod ug+x,o=r test.txt`

This will add execute permissions for the owner and group and set others' permissions to only read.



