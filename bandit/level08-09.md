# Level 8 → Level 9  

```bash
sort data.txt | uniq -c | grep -w '1'
```

**sort** sorts the lines in data.txt and **uniq** gets the number of occurences using the flag **-c** and **grep** looks for the character **1** i.e. line with a singe occurence, and **-w** ensures that exact "1" is being matched from the piped input  
therefore you get the password for level 9