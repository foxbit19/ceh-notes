# Good to know concepts

## OSI Model (Open Systems Interconnection)
From top to bottom

- 7 - Application
- 6 - Presentation
- 5 - Session
- 4 - Transport
- 3 - Network
- 2 - Data link
- 1 - Physical

## Lockheed Martin kill chain
1. Reconnaissance
2. Weaponization
3. Delivery
4. Exploitation
5. Installation
6. Command and Control
7. Actions on Objective

## Main ways to manage risks
1. acceptance
2. avoidance
3. transference
4. mitigation
5. exploitation

## Diffie-Hellman (DH) groups
Determine the strength of the key used in the key exchange process

- DH Group 1: 768-bit
- DH Group 15: 3072-bit
- DH Group 2: 1024-bit
- DH Group 5: 1536-bit
- DH Group 14: 2048-bit

## Dns records
- `A ` -> host ip address
- `MX` -> domain's mail server
- `NS` -> host's name server
- `CNAME` -> aliases to host
- `SOA` -> Start of Authority
- `SRV` -> service records
- `PTR` -> ip address to hostname
- `RP` -> responsible person
- `HINFO` -> host information include CPU and OS
- `TXT` -> unstructured text record (usually used for comments)

> The SOA stores important information about a domain or zone such as the primary name server of the domain, the email address of the admin, the last update of domain, the time the server should wait before the refresh. 

> It can specify how long does a DNS poisoning will last.

> **When the serial number within the SOA record of the primary server is higher than the Serial number within the SOA record of the secondary DNS server, a zone transfer will take place**.

## Three-way handshake
Connection Establishment: `SYN`, `SYN-ACK`, `ACK`

Connection Termination: `FIN`, `ACK-FIN`, `ACK`