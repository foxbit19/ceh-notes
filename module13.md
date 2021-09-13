# Module 13 - Hacking web server

## concepts
- web servers
    - they are expecially vulnerable beacuse are publicy visible on the internet
- directory traversal attack (it uses '../' syntax to access private folders)
    - it is possibile to encode in unicode the character '/' with '%c0%'
    - there are many unicode exploits out there
- website defacement
- HTTP response-splitting attack
- web cache poisoning attack
- web server password cracking
- robots.txt
    - can give us useful information about folders that the administrator does not want to index on search engines
- directory bruteforcing: find default content of a web applications (nikto)
- metasploit
    - exploit module
- patch management (automated patch management system)

## tools
- brutus
- hydra
- nikto2
- metasploit
- armitage (graphical version of metasploit)