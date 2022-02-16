# Tools

- `nmap` - is a powerful active reconnaissance tool
- `hping` - assembles and sends custom ICMP, UDP, or TCP packets and then displays any replies
- `vindicate` - detects name service spoofing
- `immunity debugger` - tool to write exploits, analyze malware
- `Netcraft` - whois complete tool
- `Fortify WebInspect` - Find and fix exploitable web application vulnerabilities with automated dynamic application security testing (DAST)
- `Retina CS` - Vulnerability Management Software
- `NetIQ secure configuration manager` - helps to enforce security configuration policy across critical systems
- `Burp suite` - Session analysis, session hijacking tool
- `Netscan tool Pro` - collection of internet information gathering and network troubleshooting utilities, SMTP Email Generator tool tests the process of sending an email message through an SMTP server
- `OpUtils` - IP address and switch port management software (it uses SNMP)
- `Hyena` - active directory enumeration
- `JXplorer` - LDAP browser and editor, LDAP enumeration
- `NSauditor` - scanning and detecting vulnerabilities, Monitoring access from network to shared files and folders, Detecting and controlling network data access policy violations, NETbios enumeration
- `keygrabber` - hardware keylogger
- `OllyDbg` - 32-bit assembler level analysing debugger for Windows
- `Dependency Walker` - free utility that scans any 32-bit or 64-bit Windows module (exe, dll, ocx, sys, etc.) and builds a hierarchical tree diagram of all dependent modules
- `RPCscan` - Tool to communicate with RPC services and check misconfigurations on NFS shares
- `snmpcheck` - permits to enumerate information via SNMP protocol
- `smtp-user-enum` - Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.
    - `-U file` - Select the file containing usernames to check via the SMTP service
    - `-t host` - Specify the server host running the SMTP service
    - `-T file` - Select the file containing hostnames running the SMTP service
    - `-u user` - Check if a user exists on the remote system
- `enyx` - Enyx SNMP IPv6 Enumeration Tool
- `finger` - is a user information lookup command which gives details of all the users logged in
    - `-m`: Prevents the matching of usernames.
    - `-s`: Displays the user’s login name, real name, terminal name, idle time, login time, office location, and office phone number
    - `-l`: Produces a multi-line format displaying all of the information described for the -s option as well as the user’s home directory, home phone number, login shell, mail status, and the contents of the files “.plan,” “.project,” “.pgpkey,” and “.forward” from the user’s home directory
    - `-p`: Prevents the -l option of finger from displaying the contents of the “.plan,” “.project,” and “.pgpkey” files.
- `DNSrecon` - DNS recoinnaissance tool
- `Xplico` - is a network forensics analysis tool (NFAT), which is a software that reconstructs the contents of acquisitions performed with a packet sniffer (e.g. Wireshark, tcpdump, Netsniff-ng).
- `whonix` - is software designed to preserve privacy and anonymity by helping users run applications anonymously
- `suricata` - threat detection engine
- `DerbNSpoof` - DNS Spoofing tool made in Python 3 with Scapy
- `Robber` - tool to manage DLL
- `Powersploit` - tool to manage DLL
- `GMER` - is an application that detects and removes rootkits
- `NetVizor` - it records everything on a host: chats, keystrokes and emails, site and on-line search activity, application usage, file usage, uploads and downloads, computer software setups, and web traffic.
- `Stream Armor` - is the sophisticated tool to discover Hidden Alternate Data Streams (ADS) and clean them completely from your system
- `snow` - whitespace steganografy tool
- `Cipher.exe` - is a command-line tool (included with Windows 2000) that you can use to manage encrypted data
- `BeEF` - is short for The Browser Exploitation Framework. It is a penetration testing tool that focuses on the web browser
- `USB dumper` - is a tool designed to silently copy the files and folders of any USB devices connected in your computer
- `Wireshark` - free and open-source packet analyzer (in the past was called `Ethereal`)
    - `WinPcap` - tool for link-layer network access in Windows environments, allowing applications to capture and transmit network packets bypassing the protocol stack, and including kernel-level packet filtering, a network statistics engine and support for remote packet capture
- `Tcpdump` - it is similar to `Wireshark` (also defined ad wireshark for CLI)
- `Scout Suite` - is an open source multi-cloud security-auditing tool, which enables security posture assessment of cloud environments
- `Unified Threat Management (UTM)` - is one that enforces a variety of security-related measures, combining the work of a firewall, malware scanner, and intrusion detection/prevention
- `Tripwire` - a product for configuration control by detecting, assessing, reporting and remediating file and configuration changes
- `Metasploit` - a tool for developing and executing exploit code against a remote target machine
- `Armitage` - GUI for metasploit
- `Metagoofil` - is an information gathering tool designed for extracting metadata of public documents (pdf,doc,xls,ppt,docx,pptx,xlsx) belonging to a target company
- `Tcptrace` is a tool for the analysis of TCP dump files. It can take as input the files produced by several popular packet-capture programs, including tcpdump/WinDump/Wireshark, snoop, EtherPeek, and Agilent NetMetrix.
- `Maltego` - connect data and functionalities from diverse sources using Transforms
- `Infoga` - is a tool gathering email accounts information (IP, hostname, country,...) from a different public source (search engines, PGP key servers, and shodan) and checks if emails were leaked using haveibeenpwned.com API
- `tcp-over-dns` - contains a special dns server and a special dns client. The client and server work in tandem to provide a TCP (and UDP!) tunnel through the standard DNS protocol ([website](https://github.com/sunapi386/tcp-over-dns)).
- `NCollector studio` - windows tool to download content from the web to your computer
- `Syhunt Hybrid` - combines comprehensive static and dynamic security scans to detect vulnerabilities like XSS, File Inclusion, SQL Injection, Command Execution and many more, including inferential, in-band and out-of-band attacks through Hybrid-Augmented Analysis (HAST).
- `CeWL` - is a ruby app which spiders a given url to a specified depth, optionally following external links, and returns a list of words which can then be used for password crackers such as John the Ripper.
- `WAFW00F` - allows one to identify and fingerprint Web Application Firewall (WAF) products protecting a website[^6]
- `web-stat` - Observe your visitors in real time as they interact with your site & optimize your landing pages and navigation[^7]
- Guardster - offers various services to let you use the Internet anonymously and securely. From our popular free web proxy service, to our secure SSH tunnel proxy, we have a variety of services to suit your needs[^8]
- wget - is a free software package for retrieving files using HTTP, HTTPS, FTP and FTPS, the most widely used Internet protocols
    - `-S` get timestamp from server
    - `-q` quiet mode (does not print wget info output)

## MiTM
- `Ettercap` is a comprehensive suite for man-in-the-middle attacks. It features sniffing of live connections, content filtering on the fly, and many other interesting tricks. It supports active and passive dissection of many protocols and includes many features for network and host analysis.
- `SMBRelay` - it can be used to carry out SMB man-in-the-middle (mitm) attacks on Windows machines
- `Evilginx` - is a man-in-the-middle attack framework used for phishing credentials and session cookies of any web service. It's core runs on Nginx HTTP server, which utilizes proxy_pass and sub_filter to proxy and modify HTTP content, while intercepting traffic between client and server.

## Scanners
- `Nessus` - vulnerability scanner
- `OpenVAS` - vulnerability scanner
- `N-Stalker X` - vulnerability scanner
- `SuperScan` - TCP/UDP port scanner, can be used to perform netBIOS enumeration
- `SoftPerfect network scanner` - can ping computers, scan ports, discover shared folders and retrieve practically any information about network devices via WMI, SNMP, HTTP, SSH and PowerShell, NETbios enumeration
- `Svmap` - network scanner for SIP (Session Initiator Protocol) similar to nmap
- `GFI LanGuard` - network security scanner and patch management
- `nikto/nikto2` - Website Vulnerability Scanner which performs vulnerability scanning against web servers for multiple items and checks for default passwords (also incorporates IDS evasion techniques)
- `Netsparker` - is an automated, yet fully configurable, web application security scanner that enables you to scan websites, web applications, and web services, and identify security flaws. Netsparker can scan all types of web applications, regardless of the platform or the language with which they are built.
- `whisker` - web vulnerability scanner that incorporates IDS evasion techinques

## Mobile
- `DroidSheep` - is an open-source Android application made by Corsin Camichel that allows you to intercept unprotected web-browser sessions using WiFi
- `AndroRAT` - is a tool designed to give the control of the android system remotely and retrieve informations from it. Androrat is a client/server application developed in Java Android for the client side and the Server is in Python.
- `FaceNiff` - is an Android app that allows you to sniff and intercept web session profiles over the WiFi
- `AnDOSid` - is an android tool that you can use to launch DoS attacks from your mobile phone

## DoS
- `XOIC` is a DDoS attacking tool
- `PyLoris` - DoS tool which enables the attacker to craft its own HTTP request headers.
- `HULK` - DDoS Tool

## IoT
- `IoT seeker `- This scanner will scan a network for specific types of IoT devices to detect if they are using the default, factory set credentials. The recent Internet outage has been attributed to use the IoT devices (CCTV Cameras, DVRs and others) with default credentials[^1]
- `Bullguard IoT` - Check if your internet-connected devices at home are public on Shodan. If they are, this means they are accessible to the public, and hackers.[^2]
- `Azure IoT central` - is highly secure, scales with your business as it grows, ensures your investments are repeatable, and integrates with your existing business apps[^3]
- `Cloud IoT Core` - Google’s Internet of Things (IoT) solutions make it easy to build connected devices. We can help you create secure, innovative connected products through integration with Google services and technologies[^4]
- `Flowmon` - IoT monitoring and diagnostic toolset. Empowers manufacturers and utility companies to ensure the reliability of their industrial networks to avoid downtime and disruption of service continuity

## Password-related
- `CHNTPW` - is a linux-based software utility for resetting or blanking local passwords used by Windows NT, 2000, XP, Vista, 7, 8, 8.1 and 10. It does this by editing the SAM database where Windows stores password hashes.
- `Cain and Abel` - password recovery tool for Microsoft Windows. It could recover many kinds of passwords using methods such as network packet sniffing, cracking various password hashes by using methods such as dictionary attacks, brute force and cryptanalysis attacks
- `L0phtCrack` - is a password auditing and recovery application used to test password strength and sometimes to recover lost Microsoft Windows passwords, by using dictionary, brute-force, hybrid attacks, and rainbow tables
- `Mimikatz` - password, hash, kerberos tickets extacting tool
- `Medusa` - is a speedy, parallel, and modular, login brute-forcer[^5]




## Wireless
- `Kismet` - is a wireless network and device detector, sniffer, wardriving tool, and WIDS (wireless intrusion detection) framework
- `betterCAP` - the Swiss Army knife for WiFi, Bluetooth Low Energy, wireless HID hijacking and IPv4 and IPv6 networks reconnaissance and MITM attacks
- `Wireshark` - free and open-source packet analyzer (in the past was called `Ethereal`)
    - `Airpcap` - Riverbed AirPcap USB-based adapters capture 802.11 wireless traffic for analysis
- `reaver` - performs a brute force attack against an access point’s WiFi Protected Setup pin number
- `WIBR+` - WIfi BRuteforce is an application for testing of security of the wpa wpa2 psk wifi networks
- `BBProxy` - allows the attacker to use a BlackBerry device as a proxy between the Internet and the internal network. It is used for Blackjacking
- `wash` - tool to find WPS-enabled APs


[^1]: [https://github.com/rapid7/IoTSeeker](https://github.com/rapid7/IoTSeeker)
[^2]: [https://iotscanner.azurewebsites.net/](https://iotscanner.azurewebsites.net/)
[^3]: [https://azure.microsoft.com/en-us/services/iot-central/#overview](https://azure.microsoft.com/en-us/services/iot-central/#overview)
[^4]: [https://developers.google.com/iot](https://developers.google.com/iot)
[^5]: [https://github.com/jmk-foofus/medusa](https://github.com/jmk-foofus/medusa)
[^6]: [https://github.com/EnableSecurity/wafw00f](https://github.com/EnableSecurity/wafw00f)
[^7]: [https://www.web-stat.com/](https://www.web-stat.com/)
[^8]: [https://www.guardster.com/](https://www.guardster.com/)