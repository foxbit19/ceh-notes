# module 6 - system hacking

## concepts
- remember the 6 phases of attack
    - recoinissance
    - scanning
    - gaining access
    - mantaining access
    - covering tracks
- SAM (security account manager) database
    - located ad c:\windows\system32\config\sam
- LM
- NTLM (the auth process)
- Kerberos
- social engineering
- shoulder surfing
- dumpster diving
- dictionary attack
- brute-force attack
- rule-based attack
- pass the hash attack (PtH)
- LLMNR/NBT-NS poisoning
- Kerberos - cracking TGS
    - AS-REP Roasting
    - Kerberoasting
- Pass the ticket attack
- wire sniffing
- rainbow table attack
- password salting
- vulnerability -> exploit -> payload -> remote access
- buffer overflow
- privilege escalation (vertical vs horizontal)
- pivoting vs relaying
- keylogger
- spyware
- rootkit
- NTFS data stream
- steganography
    - LSB
    - watermarks
    - math
- covering tracks
    - clear_event_viewer_logs file 
    - clearev in meterpreter session
    - event viewer in windows 
    - /var/log in linux


## tools
- oxid
- responder (python script)
- mimikatz
- pwdump7
- powershell empire
- ntdextract
- john the ripper
- hashcat
- hydra
- medusa
- rainbowcrack
- fu (rootkit to hide process from process manager)
- adspy
- shred command to shredding the history