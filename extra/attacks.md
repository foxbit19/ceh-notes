# Main attacks

- `Mac flooding` - targeting network switches and it use MAC table “overflow”
- `ARP spoofing/Arp cache poisoning `- *switch attack* - the attacker sends (spoofed) Address Resolution Protocol (ARP) messages onto a local area network
- `Cognitive password attack` - if an employee reveals too much personal information it would be easy for miscreants to use the messages containing the personal information to work out possible passwords
- `RUDY (R-U-Dead-Yet?)` - denial-of-service attack tool that aims to keep a web server tied up by submitting form data at an absurdly slow pace
- `XSS (Cross Site Scripting)
`- `CSRF (Cross Site Request Forgery)`
- `SQL Injection`
- `Code injection` - it's a form of cyberattack where the cybercriminal injects malicious data into the code interpreter
- `PTW attack` - allows an attacker to recover the secret key in less than 60 seconds in some cases
- `Connection String Parameter Pollution (CSPP)` - poorly secured dynamic connections between Web apps and databases, namely ones that still use semicolons as separators between data such as the data source, user ID, and password associated with a connection to the database, for instance.
- `watering hole` - targeted attack designed to compromise users within a specific industry or group of users by infecting websites they typically visit and luring them to a malicious site. The end goal is to infect the users computer and gain access to the organizations network.
- `Rubber Hose `- The rubber hose attack is extracting secrets from people by use of torture or coercion.
- `Rainbow table` - precomputed list of password hashes. It's an efficient way of cracking passwords for Windows Server 2003 Active Directory (AD) users
- `Email spoofing` - is a technique used in spam and phishing attacks to trick users into thinking a message came from a person or entity they either know or can trust. In spoofing attacks, the sender forges email headers so that client software displays the fraudulent sender address, which most users take at face value
- `MarioNet` - A browser-based attack that allows hackers to run malicious code even if users’ exit a web page
- `Wrapping attacks` - aim at injecting a faked element into the message structure so that a valid signature covers the unmodified element while the faked one is processed by the application logic.
- `Cloudborne` - An attack scenario affecting various cloud providers could allow an attacker to implant persistent backdoors for data theft into bare-metal cloud servers, which would be able to remain intact as the cloud infrastructure moves from customer to customer.
- `The Sybil attack `- is an attack wherein a reputation system is subverted by creating multiple identities
- `aLTEr` - it is implemented using a fake eNodeB (the 4G cell tower), acting as Man-in-The-Middle (MiTM)
- `Meet-in-the-middle attack (MITM)` - a known plaintext attack, is a generic space–time tradeoff cryptographic attack against encryption schemes that rely on performing multiple encryption operations in sequence. The MITM attack is the primary reason why Double DES is not used and why a Triple DES key (168-bit) can be bruteforced by an attacker with 256 space and 2112 operations.
- `DROWN` (Decrypting RSA with Obsolete and Weakened eNcryption) - cross-protocol security bug that attacks servers supporting modern SSLv3/TLS protocol suites by using their support for the obsolete, insecure, SSL v2 protocol to leverage an attack on connections where the same public/private keys are shared between the servers.
- `SSL stripping` - also known as an HTTP downgrade attack, forces the client to communicate with the webserver in plain text (unencrypted) over HTTP instead of HTTPS
## DoS
- `SYN flood` - is a form of denial-of-service attack in which an attacker rapidly initiates a connection to a server without finalizing the connection. The server has to spend resources waiting for half-opened connections, which can consume enough resources to make the system unresponsive to legitimate traffic.
- `Smurf attack` - DDos attack that use ICMP packets. Amplification and reflection of spoofed ip can crash the target host

## Mobile
- `DroidDream` - is a mobile botnet that obtains root access to Google Android mobile devices in order to access unique identification information for the phone. Once compromised, a DroidDream-infected phone could also download additional malicious programs without the user s knowledge as well as open the phone up to control by hackers. It got its name from the fact that it was set up to run between the hours of 11pm and 8am when users were most likely to be sleeping and their phones less likely to be in use[^1]
- `Spearphone` - a speech privacy attack that exploits speech reverberations from a smartphone's inbuilt loudspeaker captured via a zero-permission motion sensor (accelerometer)[^2]
- `Smudge attack` - is an information extraction attack that discerns the password input of a touchscreen device such as a cell phone or tablet computer from fingerprint smudges
- `SIM swap scam` - (also known as port-out scam, SIM splitting, Smishing and simjacking, SIM swapping) is a type of account takeover fraud that generally targets a weakness in two-factor authentication and two-step verification in which the second factor or step is a text message (SMS) or call placed to a mobile telephone.

[^1]: [https://www.webopedia.com/definitions/droiddream/](https://www.webopedia.com/definitions/droiddream/)
[^2]: [https://dl.acm.org/doi/abs/10.1145/3448300.3468499](https://dl.acm.org/doi/abs/10.1145/3448300.3468499)