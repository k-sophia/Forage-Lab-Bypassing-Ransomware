# Forage-Lab-Bypassing-Ransomware
A lab from AIG Shields Up: Cybersecurity virtual experience program on Forage

## Scenario
An attacker exploited a vulnerability (Log4Shell) and began installing a ransomware virus. The Incident Detection & Response team prevented the ransomware virus from completely installing, so only one zip file was encrypted. 

The CISO does not want to pay the ransom, because there isn’t any guarantee that the decryption key will be provided or that the attackers won’t strike again. Therefore, I am tasked to bruteforce the decryption key.

## Tools
- Python 3
- zipfile module
- Rockyou.txt sublist

## Output
```
[+] Beginning bruteforce 
[+] Password found: b'SPONGEBOB'
```
