# Module 18 - IoT and OT Hacking

## concepts
- IoT definition
- IoT challenges
    - there are one big problems with IoT: they are vulnerable because they are difficult to update
- OWASP Top 10 IoT Threats
- DDoS attack
- Exploit HVAC (Heating Ventilation and Air Conditioning)
    1. shodan for vulnerable ICS (industrial control system)
    2. access to ICS system
    3. accesso to HVAC through ICS
    4. controls of temperature from HVAC
- SDR-Based Atacks
    - send message to connected IoT devices
- Identifying and accessing local IoT devices
- IoT Hacking methodology
    - information gathering
    - vuln scanning
    - launch attacks
    - gain remote access
    - mantain access
- firmware analysis and reverse engineering
    - identify passwords
    - API tokens
    - endpoint
- OT (Operation Technology)
    - detect or causes changes in industrial operations
    - ICS
    - SCADA (Supervisory Control and Data Acquisition)
    - one of the examples of malware of OT was Stuxnet
- OT main vulnerabilities
- OS Hacking methodology (same as IoT)
    - information gathering
    - vuln scanning
    - launch attacks
    - gain remote access
    - mantain access
- identify OT devices through Shodan
    - search modbus enabled ICS/SCADA on port 502
    - search SCADA system using PLC name "Schneider Electric"
    - search for SCADA system using geoloc: SCADA Country "US"
- it is possible to use Nessus to find vulnerability
- using wireshark it is possible to analyze Modbus/TCP traffic
- metasploit 'scanner/scada/modbus...'

## tools
- shodan
- nessus
- wireshark
- metasploit