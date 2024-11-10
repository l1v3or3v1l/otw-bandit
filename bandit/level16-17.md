# Level 16 -> Level 17  

```bash
nmap -p31000-32000 localhost
nmap -p31046,31518,31691,31790,31960 -sV localhost
openssl s_client -connect localhost:31790 -quiet
```
