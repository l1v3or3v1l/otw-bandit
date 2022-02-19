# Level 1 → Level 2

The password is in the file named as **"-"** (dash)  

you can see the file exists by using the **ls** command

to view the file contents again here we will use cat  

but since **"-"** is an operator in bash used for **"redirection from/to stdin or stdout"** it's a bit tricky  

we can display the file contents in two ways

```bash
cat ./-
```
**OR**
```bash
cat < -
```

Then you will get the password to **bandit2** user on the same server same port. Connect to it.