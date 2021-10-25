# Module 4 - enumeration

## concepts
- netbios
- SID (windows) - last number is important (500, 501, ...)
- SNMP
- LDAP 
    - on port 389
    - on port 636 encrypted version
- NTP (UDP port 123)
- NFS
- SMTP
- DNS
    - cache snooping
    - DNSSEC zone walking
- IPsec
- VoIP
- RPC
- telnet (usually on port 23)
- SMB (port 445)
- FTP (port 21)
- TFTP (same as FTP, different port, but requires no auth)
- BGP (Border Gateway Protocol)

## tools
- nbtstat (windows)
- net use
- pstools
- ip network browser
- ntptrace/ntpdc
- dig (for dns zone transfer analysis and dns cache snooping)
- nslookup
- ldns-walk
- dnsrecon
- ike-scan
- rusers
- rwho
- finger