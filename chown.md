# chown

The chown command is short for '**ch**ange **own**er'. This is used to change the owner of a file and can also change the group of the file. A normal user cannot change the owner of a file as they do not have permissions for files they do not own and linux does not allow a user to 'give away' permissions. Change of owner can only be done by the [superuser](/sudo.md) or 'root' account.

**Examples**

`sudo chown jim:users test.txt`

This will set jim as the file owner and will give the users group permissions to test.txt.

`sudo chown root:root test.txt`

This will set the owner and group permissions for test.txt to the root account only.

**R option \(-R\)**

This is used to set the owner for all files in a folder structure recursively.

**Examples**

`sudo -R chown jim:users projects`

This will set jim as the owner and will give the users group permissions to all files in the projects directory.

