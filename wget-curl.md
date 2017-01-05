# wget

The wget command is short for "**w**orld wide web **get**". It is used to download files via the http, https and ftp protocols.

**Example**

`wget https://www.gnu.org/software/wget/`

This will download the web page from the location specified and store it in a file named index.html

wget has many options to control what and how it will execute. The manual specifies all the available options and is available at [https://www.gnu.org/software/wget/manual/wget.html](https://www.gnu.org/software/wget/manual/wget.html). Here a few commonly used options.

**r option \(-r\)**

This is used to recursively download all linked files and directories up to 5 levels.

**o option \(-o\)**

This is used to specify the name of the output file when it is save locally.

**Example**

`wget https://www.gnu.org/software/wget/ -o wget.html`

This will download the web page from the location specified and store it in a file named wget.html

**user, password options \(--user, --password\)**

These options are used to specify a user name and password if they are required for authentication before being ablt o access a particular location

**Example**

`wget https://www.gnu.org/software/wget/secure/protected.html --user admin --password secretWord`

This will download the protected.html file if the user name and password are correct.

 

# curl

The curl command is short for "see url". Similar to wget, it is used to download files via the http, https and ftp protocols. In most cases wget and curl can be used interchangeable. Two of the main differences are that curl can use many more protocols, not just the http, https and ftp protocols. However, curl cannot do recursion which is a big strength for wget.



