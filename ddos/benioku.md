# Python2/3-SYN-Flood-Attack-Tool



Python SYN Flood Attack Tool

Bu script egitim amacli yazilmistir.


## Pluginler
```

apt install python3-scapy
```

## Kurulum

```

cd ddos
```

## Kullanimi

```
python3 ddos.py -t 10.20.30.40 -p 8080 -c 5
python3 synflood.py

```
```
usage: ddos.py [--target TARGET] [--port PORT]
                           [--count COUNT] [--version]

optional arguments:
  -h, --help            show this help message and exit
  --target TARGET, -t TARGET
                        target IP address
  --port PORT, -p PORT  target port number
  --count COUNT, -c COUNT
                        number of packets
  --version, -v         show program's version number and exit

kullanim: python3 ddos.py -t 10.20.30.40 -p 8080 -c 1
```

![alt tag](https://github.com/nihilwyd)

