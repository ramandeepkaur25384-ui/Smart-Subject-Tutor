## Topic 1: CIA Triad – Confidentiality, Integrity, and Availability
The CIA Triad is the fundamental security model used in Cyber Security to protect information and information systems. It consists of three core principles:

Confidentiality: Ensures that sensitive information is accessible only to authorized users. Techniques such as encryption, authentication, and access control help maintain confidentiality.

Integrity: Ensures that data remains accurate, consistent, and unaltered during storage or transmission. Hashing, digital signatures, and checksums help maintain data integrity.

Availability: Ensures that systems, networks, and data remain accessible to authorized users whenever required. Backups, redundancy, disaster recovery, and protection against Denial-of-Service (DoS) attacks help maintain availability.

## Topic 2: Authentication, Authorization, and Accounting (AAA)
AAA is a security framework used to control and monitor user access to computer systems and networks.

Authentication: Verifies the identity of a user before granting access. Common methods include passwords, biometrics, OTPs, and Multi-Factor Authentication (MFA).

Authorization: Determines what an authenticated user is allowed to access or perform. Role-Based Access Control (RBAC) is a common authorization technique.

Accounting: Records and monitors user activities, including login times, resource usage, and system operations. These records help in auditing and detecting suspicious activities.

## Topic 3: Cryptography, Encryption, and Hashing
Cryptography is the technique of securing information by converting readable data (Plaintext) into an unreadable format (Ciphertext) to prevent unauthorized access.

Symmetric Encryption: Uses the same secret key for both encryption and decryption. It is fast and suitable for encrypting large amounts of data. Example: AES.

Asymmetric Encryption: Uses two mathematically related keys: a Public Key and a Private Key. The public key is shared openly, while the private key is kept secret. Examples: RSA and ECC.

Hashing: Converts input data into a fixed-length hash value using a one-way mathematical function. It is commonly used for password storage and data integrity verification. Examples: SHA-256 and SHA-3.

Digital Signature: Uses cryptographic techniques to verify the authenticity and integrity of digital messages or documents and provides evidence of origin.

## Topic 4: Network Security – Firewall, IDS, IPS, and VPN
Network Security involves protecting computer networks from unauthorized access, attacks, misuse, and data theft.

Firewall: A security system that monitors and filters incoming and outgoing network traffic based on predefined security rules. It can be implemented using hardware or software.

Intrusion Detection System (IDS): Monitors network or system activities to identify suspicious behavior and potential security threats. It generates alerts but generally does not automatically block attacks.

Intrusion Prevention System (IPS): Monitors network traffic and automatically blocks or prevents detected malicious activities based on configured security rules.

Virtual Private Network (VPN): Creates an encrypted connection over an untrusted network, such as the Internet, to protect data during transmission and provide secure remote access.

## Topic 5: Common Cyber Attacks – Phishing, Malware, DoS, and SQL Injection
Cyber Attacks are malicious activities performed by attackers to steal information, damage systems, disrupt services, or gain unauthorized access.

Phishing: A social engineering attack in which attackers use fake emails, messages, or websites to trick users into revealing sensitive information such as passwords and banking details.

Malware: Malicious software designed to damage, disrupt, or gain unauthorized access to computer systems. Common types include viruses, worms, Trojans, ransomware, and spyware.

Denial-of-Service (DoS): An attack that attempts to make a server or network unavailable by overwhelming it with excessive requests or traffic. A Distributed Denial-of-Service (DDoS) attack uses multiple compromised systems to launch the attack.

SQL Injection: A vulnerability in which malicious SQL input is improperly handled by an application, potentially allowing unauthorized database access or modification. Parameterized queries and input validation help prevent this vulnerability.