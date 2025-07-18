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
