# Level 3 → Level 4  

see what files/folders are there using **"ls"** command  

The password is in **inhere** directory  

you can look inside the directory without going inside it using  

```bash
ls inhere/
```  

But you see nothing in it  
List all files (incl. hidden ones) using the "**-a**" flag  

```bash
ls -a inhere/
```

you will see a file named "**.hidden**"  
[Note. Hidden files and folders start with **.** (dot) symbol eg: **.config**]  

see the contents of the file using  

```bash
cat inhere/.hidden
```  

Connect to **bandit4** using the password obtained