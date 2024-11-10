# Level 25 -> Level 26

make the terminal as small as possible and ssh using private key

```bash
ssh bandit26@localhost -p2220 -i bandit26.sshkey 
```

press **v** to bring up **vim** inside **more**

get password of bandit26 using this command in vim

```bash
:e /etc/bandit_pass/bandit26
```

now get shell using this command in vim

```bash
:set shell=/bin/bash
:shell
```
now you have shell of bandit26


