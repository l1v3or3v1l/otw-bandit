# Level 4 → Level 5  

password is stored in human readable file in **inhere** directory  

let's find the human readble file first  

```bash
ls -1 inhere/ | while read f; do file ./inhere/$f; done
```  

Lets disect this command and see what it does  

```bash
ls -1 inhere/
```  
This lists the files in the directory "**inhere**" each in a single line "**-1**" flag  

pipe operator ( | ) -  is used to pass the output of one command as input to another command.

command1 | command 2 - output from command1 is passed as input to command2

```bash
while read f; do file ./inhere/$f; done
```

This is a while loop which for every line passed to it, in this case every filename in that directory is being taken  

Let's disect this further  

```bash
file ./inhere/$f
```

what this does is determines the file type of the given filename, so here each filename is being passed and will display its filetype  

**./** is given because the file names contain ( - ) at the beginning  

    ./inhere/-file00: data
    ./inhere/-file01: data
    ./inhere/-file02: data
    ./inhere/-file03: data
    ./inhere/-file04: data
    ./inhere/-file05: data
    ./inhere/-file06: data
    ./inhere/-file07: ASCII text
    ./inhere/-file08: data
    ./inhere/-file09: data  

So we now know that "**-file07**" is the human readable file  

Displaying contents of the file we have,

```bash
cat ./inhere/-file07
```  

the password to connect to bandit5