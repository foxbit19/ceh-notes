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

## OWASP top 10 (2017)

1. Injection
2. Broken authentication
3. Sensitive data exposure
4. XML External Entity (XXE)
5. Broken access control
6. Security misconfiguration
7. Cross Site Sripting (XSS)
8. Insecure deserialization
9. Use components with know vulnerabilities
10. Insufficient logging and monitoring

##  N-tier architecture
- presentation tier - user interface
- logic tier - coordinates apps, commands
- data tier - storage

Tier-1: Developer machines - image creation, testing and accreditation

Tier-2: Testing and accreditation systems - verification and validation of image contents, signing images and sending them to the registries

Tier-3: Registries - storing images and disseminating images to the orchestrators based on requests

Tier-4: Orchestrators - transforming images into containers and deploying containers to hosts

Tier-5: Hosts - operating and managing containers as instructed by the orchestrator


## IoT architecture (from top to bottom)

- `application layer` - Delivery of various applications to different users in IoT
- `middleware layer` - Device management and information management
- `internet layer` - Connection between endpoints
- `access gateway layer` - Protocol translation and messaging
- `edge technology layer` - Sensors, devices, machines, and intelligent edge nodes of various types