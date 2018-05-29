# Netscanp
## Author: github.com/thelinuxchoice
## IG: instagram.com/thelinuxchoice

Netscanp is an shell script to perform Anonymous Port scan and Printer Spam using netcat and proxychains 

![netscan](https://user-images.githubusercontent.com/34893261/39967102-57501cd8-568c-11e8-8d97-7c031947cc3f.png)

### Features
- Multi-thread
- Save/Resume sessions
- Anonymous scan through TOR
- Printer Spammer

### Usage:
```
git clone https://github.com/thelinuxchoice/netscanp
cd netscanp
chmod +x netscanp.sh
service tor start
./netscanp.sh --scan
```
Resume Session:
```
./netscanp.sh --resume
```

Printer Spammer:
```
./netscanp.sh --printer
```

### Install requirements (Tor, Proxychains, Netcat):

```
sudo apt-get install -y tor netcat proxychains
```

### Donate!
Support the authors:

<noscript><a href="https://liberapay.com/thelinuxchoice/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a></noscript>
