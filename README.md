# vcd2wavedrom

Python script to transform a VCD file to [wavedrom](https://wavedrom.com/) format

```
usage: vcd2wavedrom.py [-h] --input [INPUT] [--format html] [--output [OUTPUT]] [--exclude [excludeliist.txt]] 

Transform VCD to wavedrom

optional arguments:
  -h, --help           show this help message and exit
  --config CONFIGFILE
  --input [INPUT]
  --output [OUTPUT]
  
```
Example
```
vcd2wavedrom.py --input tb_sw_decode.vcd --format html --out tb_sw_decode.html --exclude exclude.txt
```
