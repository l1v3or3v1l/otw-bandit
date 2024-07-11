# Level 24 -> Level 25

```bash
mktemp -d
cd /tmp/tmp.Kzdx3LRrRY
nano script.py
```

**script.py** code

```python
passwd = "gb8KRRCsshuZXI0tUuR6ypOFjiZbf3G8"
output = ""

for i in range(0, 10000):
        code = '0' * (4 - len(str(i))) + str(i)
        output += passwd + " " + code + "\n"

open('codes', 'w').write(output)
```

run the script and use netcat to bruteforce

```bash
python3 script.py
cat codes | nc localhost 30002 > output
cat output | grep "bandit25 is"
```

