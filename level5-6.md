# Level 5 → Level 6  

password can be found by using this command  

```bash
find inhere/ -type f -size 1033c
```

of type 'f' file and size '1033' bytes

optionally you could also look for the other conditions as well i.e. Human readable and not executable  

```bash
find . -type f -size 1033c ! -executable -exec file {} + | grep -w text
```

Here ! -executable is not executable and -exec executes the command **file** on each file and greps for the **text** in them  
You can **cat** the file to the get the password  