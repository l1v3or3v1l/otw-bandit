# Level 6 → Level 7  

```bash
find / -user bandit7 -group bandit6 -size 33c 2> /dev/null
```

this command finds the file owned by user bandit7, bandit6 group, size of 33 bytes  

**2>** - **2** means error, and **>** is to redirect stdout to some file  

so error of that command is being redirected to the file **/dev/null** which is basically ignoring the errors

**cat** the file displayed from the command output to get the password  
