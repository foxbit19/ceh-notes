# module 7 - malware threats

## concepts
- major types of malware (trojan, virus, ransomware, worm, fileless)
- components of malware
- APT
- trojan:
    - major trojans port numbers (exam)
    - types
    - infection steps
    - signature base detection
- bind vs reverse connection
- cover channels
- exploit kits
- sheep tip computer
- malware analysis (static vs dynamic)
    - step to prepare testbed
- monitoring
    - registry
    - windows services
    - startup program
    - event log (see splunk)
    - file and folders
    - network traffic
    - dns
- virus detection method

## tools
- beast (windows, create trojans)
- DELmE virus maker
- internet worm maker thing
- virustotal
- bitext (for malware analysis)
- PEid (windows, identify signatures of malware)
- PE Explorer (Portable Executable information)
- Dependency walker
- IDA (disassembly tool for win, linux and mac)
- procmon
- netcat: set up a listener and send all to bash (or cmd) :
    - nc -L -p 79 -d -e cmd.exe
- process explorer (virus total integration)
- jv16 PowerTools
- splunk
- PA file sight
- solarwinds netflow
- tcpview
- DNSQuerySniffer