## Saad Baig

A security engineer having fun securing the digital world 😄

Here are some of the projects I'm currently working on:

* https://github.com/SaadBaig/pqcscan - This fork extends the original [pqcscan](https://github.com/anvilsecure/pqcscan) by Anvil Secure with full TLS handshake validation, negotiated behavior analysis, and downgrade attack detection. The tool validates ML-KEM key exchange across all NIST FIPS 203 variants — ML-KEM-512, ML-KEM-768, ML-KEM-1024, plus hybrid schemes (X25519MLKEM768, SECP256R1MLKEM768, SECP384R1MLKEM1024). The tool executes the full handshake lifecycle—key exchange, encrypted extensions, certificate verification, and Finished messages—moving beyond simple ClientHello/ServerHello inspection to confirm actual cryptographic behavior. This helps surface gaps between advertised PQC support and what servers actually negotiate in practice.

* https://github.com/SaadBaig/Pentesting-Methodology - What began as handwritten notes documenting my pentesting workflow has evolved into a structured, end-to-end testing methodology. This repository reflects how I approach real-world engagements—covering enumeration, exploitation, and post-exploitation in a practical, repeatable way.

* https://github.com/SaadBaig/DDoSing-DEFCON-2026 - A team of hackers setting up in the DDoS community at DEFCON 34 (2026). We're building a contest around hacked Temu WiFi repeaters — turning them into a DDoS botnet that offensive players can use to take down our targets. This repository documents our journey journal style :) 
