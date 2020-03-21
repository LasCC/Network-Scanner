# Network Scanner

- Scan all the current IP on your network with their MAC address

# Tech part

This script uses a number of open source projects to work properly:

- scapy
- argparse
- python

### Installation

```
pip install scapy 
pip install argparse
```

### Usage

```
usage: main.py [-h] [-i TARGET]

optional arguments:
  -h, --help            show this help message and exit
  -i TARGET, --ip TARGET
                        Target IP / IP Range
```

```
python main.py -i 192.168.1.1/24
```

### Pictures

[![N|Solid](https://i.imgur.com/a3xkBsU.png)](https://i.imgur.com/a3xkBsU.png)

@LasCC
