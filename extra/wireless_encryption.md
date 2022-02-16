# Wireless encryption algorithms

- `802.11x` - is the IEEE Standard authentication mechanisms to devices wishing to attach to a Wireless LAN
- `WEP` - Wired Equivalent Privacy encryption standard was the original encryption standard for wireless, it uses the stream cipher RC4 for confidentiality and the CRC-32 checksum for integrity. It uses a 64-bit or 128-bit encryption key. It was deprecated in 2004.
- `WPA` - Wi-Fi Protected Access (sometimes referred to TKIP standard) became available in 2003. It dynamically generates a new 128-bit key for each packet
- `WPA2` - Ratified in 2004, it includes mandatory support for CCMP, an AES-based encryption mode.
- `WPA3` - In 2018, the Wi-Fi Alliance announced WPA3 as a replacement to WPA2. It uses an equivalent 192-bit cryptographic strength in WPA3-Enterprise mode (AES-256 in GCM mode with SHA-384 as HMAC), and still mandates the use of CCMP-128 (AES-128 in CCM mode) as the minimum encryption algorithm in WPA3-Personal mode. It replaces the pre-shared key (PSK) exchange with Simultaneous Authentication of Equals (SAE) exchange.
- `EAP` - Extensible Authentication Protocol is an authentication framework frequently used in network and internet connection. Extended EAP and is available in several versions: EAP-MD5, PEAPv0, PEAPv1, EAP-MSCHAPv2, LEAP, EAP-FAST, EAP-TLS, EAP-TTLS, MSCHAPv2, and EAP-SIM.
- `LEAP` - Lightweight Extensible Authentication Protocol.
- `CCMP` - Counter Mode Cipher Block Chaining Message Authentication Code Protocol is the standard encryption protocol for use with the WPA2. It provides Data confidentiality, authentication and access control