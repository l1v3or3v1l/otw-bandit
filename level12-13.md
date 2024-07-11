# Level 12 -> Level 13  

```bash
mktemp -d
cp data.txt /tmp/tmp.0O9EZagbld
cd /tmp/tmp.0O9EZagbld
xxd -r data.txt > data
mv data data.gz
gunzip data
bzip2 -d data
mv data.out data.gz
gunzip data
tar -xf data
tar -xf data5.bin
bzip2 -d data6.bn
tar -xf data6.bin.out
mv data8.bin data8.gz
gunzip data8
cat data8
```
