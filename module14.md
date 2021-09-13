# Module 14 - Hacking web application

## concepts
- web services
    - rest
    - soap
- owasp top 10 (2017)
    - injection flaws (SQL, Command, LDAP injections)
    - broken authentication (Session ID in URL, Password and Timeout exploitation)
    - Sensitive data exposure
    - Security misconfiguration
    - Cross-site scripting (XSS)
        - stored vs reflected
- Unvalidated redirects and forwards
- Cross-site Request Forgery (CSRF)
- Cookie/Session poisoning
- Hidden Field Manipulation Attack
- Clickjacking attack 
- footprinting web infrastructure
    - proxy/firewall detection
    - hidden content discovery
    - detect load balancer
- authorization attack
- Perform local file inclusion (LFI)
- API
- Web hooks
- Web shells
## tools
- trace (identify proxy changes to a request)
- wafw00f (to detecting a web application firewall)
- OWASP Zed attack proxy
- web scarab
- vega
- appspider
- arachni
