# pipe \(\|\)

The pipe command is executed by the \| symbol. It is used to "pipe" the output from one command into the input of another command

**Example**

`ls | grep ".txt"`

This will put all the output from the ls command into the input parameter of the grep command. If the the ls command on it's own were to return the following:

`one.txt  
two.log  
three.txt  
four.doc`

Then the above example would return only the line containing .txt

`one.txt  
three.txt`

The pipe command can be chained with multiple other commands as long as the output of one is valid for the input of the next.

