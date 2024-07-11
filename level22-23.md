# Level 22 -> Level 23  

```bash
cat /etc/cron.d/cronjob_bandit23 
cat /usr/bin/cronjob_bandit23.sh
export mytarget=$(echo I am user bandit23 | md5sum | cut -d ' ' -f 1)
cat /tmp/$mytarget
```
