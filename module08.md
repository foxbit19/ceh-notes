# Module 8 - Sniffing

## concepts
- passive sniffing (hub environment)
- active sniffing (switch environment)
- vulnerable (that send info in clear text)
    - telnet
    - rlogin
    - http
    - pop
    - imap
    - smtp
    - nntp
    - ftp
- span port
- mac 
    - flooding
    - spoofing (and defense technique using snooping table)
- dhcp
    - starvation attack
    - rogue server attack
- arp
    - poisoning attack
- VLAN Hopping
- STP attack
- DNS
    - poisoning
    - spoofing
    - difference between intranet and internet
    - cache poisoning
- sniffing detection
    - nmap 'sniffer-detect' script (promiscious)

### wireshark special
- filters
    - 'pop' to filter by protocol
    - 'ip.addr' to filter by ip address
    - 'ip.src' to filter by ip address
    - 'ip.dst' to filter by ip address

## tools
- macof
- yearsinia (DHCP starvation attack)
- XArp
- wireshark