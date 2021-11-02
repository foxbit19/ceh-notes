# Module 19 - Cloud computing

## concepts
- one of the benefits of cloud computing is that you don't need to mantain your environment
- types of cloud computing
    - IaaS
    - PaaS
    - SaaS
    - IDaaS
    - SECaaS
    - CaaS
    - FaaS
- Cloud deployment models
    - public
    - private
    - community
    - hybrid
    - multi
- NIST cloud architecture
- cloud storage architecture
- container vs virtual machines
- attacks
    - service hijacking
        - social engineering
        - network sniffing
    - side-channel attacks or cross-guest vm breaches
        - attacker's vm near victim's vm (on the same phisical host): share resources and attackers can gain cryptographic keys
    - wrapping (compromised SOAP message)
    - MITC (Man-in-the-cloud)
    - cloud hopper
    - cloud cryptojacking
    - cloudborne
- cloud hacking definition
- vulnerability scanning using trivy
- aws
    - enumerate s3 buckets
    - enumerate aws accounts
    - enumerate iam
- hacking container volumes

## tools
- trivy
- clair
- dadga
- spyse (to enumerate S3 buckets)
- s3scanners
- GCPBucketBrute (for escalate privileges on google buckets)
- AWS pwn