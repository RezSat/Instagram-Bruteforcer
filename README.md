# Instagram-Bruteforcer
[This program is not actively maintained]
Python based instagram brute forcer

This program will brute force any Instagram account you send it its way. Just give it a target,
a password list and a mode then press enter and forget about it. No need to worry about anonymity when using this program,
its highest priority is your anonymity, it only attacks when your identity is hidden.


### Requirements

-   Python _v3.x.x_
-   ~~Kali Linux 2.0~~
-   ~~TOR~~


### Install Dependencies

```
pip3 install -r requirements.txt
```

### Help
```
C:\Users\yehan\Desktop\Instagram>python3 instagram.py -h
usage: instagram.py [-h] [-m MODE] username wordlist

positional arguments:
  username              email or username
  wordlist              password list

optional arguments:
  -h, --help            show this help message and exit
  -m MODE, --mode MODE  modes: 0 => 32 bots; 1 => 16 bots; 2 => 8 bots; 3 => 4 bots
```

### Usage

```
python3 instagram.py <username> <wordlist> -m <mode>
```

### Bots(Threads)

-   4 bots: 64 passwords at a time
-   8 bots: 128 passwords at a time
-   16 bots: 256 passwords at a time
-   32 bots: 512 passwords at a time
