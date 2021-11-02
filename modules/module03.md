# module 3 - scanning networks

- tcp vs udp
- tcp flags
- tcp three-way handshake
- tcp session termination

## host discovery 
- ping scan types (e.g. ARP, ECHO, SYN, ACK, IP)
- ping sweep countermeasures

## port scanning
- inverse tcp flag scan (useless for windows system)
- xmas three packet
- xmas scan
- ack flag probe scan
- idle/ipid header scan (evade detection using zombie host)
- udp scanning (no response when port is open)
- sctp init scan
- sctp cookie echo
- ssdp scan
- list scan
- ipv6 scan (nmap use flag -4 to ipv4 and -6 to ipv6)
- service version discovery (nmap flag -sV)
- nmap timing options(flag -T)
- nmap stealth scan (flag -sS)
- nmap operating system detection options (-O)
- active vs passive banner grabbing
- active banner grabbing using netcat
- determining OS through TTL (time to live)
- nmap script engine
- packet fragmentation
- source routing (create custom chain of hops)
- source port manipulation
- ip address decoy and spoofing
- ip spoofing detection tencniques:
  - ttl may be different
  - ip identification number is different
  - tcp flow
- randomize host address
- sending bad checksum

## tools

- hping2/hping3
- metasploit
- mobile scanner: ip scanner/fing/network scanner
- nmap
- angry ip scanner
- netcat
- wireshark
- packet creation tool:
  - colasfot packet builder
  - netscantool pro