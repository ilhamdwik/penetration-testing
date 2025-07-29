# penetration-testing


## Physical Address using whois tool

nslookup etf.bg.ac.rs
nslookup facebook.com

whois etf.bg.ac.rs


## Whatweb stealthy scan

whatweb https://facebook.com -v


## Aggressive website technology discovery on ip range

whatweb 192.168.64.1-192.168.64.255 --aggression 3 -v

whatweb 192.168.64.1-192.168.64.255 --aggression 3 -v --no-errors


## Gathering emails using theharvester & hunter.io

theHarvester -d mas.bg.ac.rs

theHarvester -d mas.bg.ac.rs -b all


## Tools RED_HAWK and Sherlock

git clone https://github.com/Tuhinshubhra/RED_HAWK.git

cd RED_HAWK

php rhawk.php



git clone https://github.com/sherlock-project/sherlock.git

cd sherlock

pipx install sherlock_project

sherlock --help

sherlock ilhaskam

sherlock ilhaskam@gmail.com


## netdiscover

sudo netdiscover --help

sudo netdiscover

## NMAP

nmap 192.168.64.3

nmap -sS 192.168.64.3

nmap -sT 192.168.64.3

nmap -sU 192.168.64.3

nmap -sV 192.168.64.3


### Target Operating System

nmap -O 192.168.64.3

### Detecting Version Of Service Running On An Open Port

-- version-intensity defaultnya adalah 7

nmap -sV --version-intensity 9 192.168.64.3

### Mode Agressive
nmap -A 192.168.64.3

### Find Host Up 
nmap -sn 192.168.64.1-255

### Find Specific Port On Target
nmap -p 80 192.168.64.3

nmap -p 80,22,5432 192.168.64.3

nmap -p 1-100 192.168.64.3

### Jumlah Port Keseluruhan sampai dengan 65535
nmap -p 1-65535 192.168.64.3

### Menampilkan top 100 Port yg Dipakai Oleh Machine Target
nmap -F 192.168.64.3

sudo nmap -sS 192.168.64.3 >> outputscan.txt

sudo nmap -oN output -sS 192.168.64.3

### Using Decoys and Packet Fragmentation

sudo nmap -f 192.168.64.3

sudo nmap -D RND:5 192.168.64.3

sudo nmap -D RND:5 192.168.64.3 -sS

sudo nmap -D 192.168.64.4,192.168.64.5,192.168.64.6,192.168.64.7,ME 192.168.64.3