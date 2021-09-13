# Module 15 - SQL injection

## concepts
- types of sql injection
- OWASP web pages contains a lot of examples about SQL injections payloads
- blind sql injection
    - you can use 'delay' db command to wait n number of seconds ti determine how long it is an username for example
- bypass firewalls using sql injection
- evading IDS 
    - when we use `/*` `*/` they are removed from the message by iDS
    - at the same time, if the IDS was configured to trigger on specific words (like `SELECT` or `UNION`), we can fragment the data like this `/*SEL*//*ECT*/`
    - upper and lower case variations
    - ... other techniques

## tools
- sqlmap
- mole