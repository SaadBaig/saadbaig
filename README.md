## Saad Baig

A security engineer having fun securing the digital world 😄

Here are some of the projects I'm currently working on:

* https://github.com/SaadBaig/pqcscan - Forked pqcscan and extended it beyond passive capability detection to actively validate full TLS 1.3 handshakes for Post-Quantum Cryptography (PQC).

The tool now exercises real negotiation behavior—verifying ML-KEM key exchange across all NIST FIPS 203 variants (ML-KEM-512/768/1024) as well as hybrid schemes like X25519MLKEM768, SECP256R1MLKEM768, and SECP384R1MLKEM1024.

Built on rustls with rustls-post-quantum, it performs two complete TLS 1.3 handshakes per target:
• PQC-enabled handshake — offers hybrid ML-KEM (e.g., X25519MLKEM768) alongside classical groups
• Classical-only handshake — restricts negotiation to traditional ECDH groups

Both paths execute the full handshake lifecycle—key exchange, encrypted extensions, certificate verification, and Finished messages—moving beyond simple ClientHello/ServerHello inspection to confirm actual cryptographic behavior. This helps surface gaps between advertised PQC support and what servers actually negotiate in practice.

* https://github.com/SaadBaig/Pentesting-Methodology - What began as handwritten notes documenting my pentesting workflow has evolved into a structured, end-to-end testing methodology. This repository reflects how I approach real-world engagements—covering enumeration, exploitation, and post-exploitation in a practical, repeatable way.
