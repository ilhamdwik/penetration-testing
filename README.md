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