## Saad Baig

A security engineer having fun attacking & securing the digital world 😄

---

### Projects I'm Currently Working On

#### 🔐 [pqcscan](https://github.com/SaadBaig/pqcscan)

This fork extends the original [pqcscan](https://github.com/anvilsecure/pqcscan) by Anvil Secure. It's a TLS network scanner designed to verify that servers can actually handle next-generation **Post-Quantum Cryptography (PQC)**.

While basic scanners only check if a server *claims* to support quantum-safe algorithms in its initial greeting, this tool executes a **complete end-to-end TLS handshake** — processing everything from the key exchange and encrypted extensions down to certificate verification and the final `Finished` messages.

It validates both standalone PQC algorithms and **hybrid schemes** across these exact standards:

- **Pure Post-Quantum (NIST FIPS 203):** `ML-KEM-512`, `ML-KEM-768`, `ML-KEM-1024`
- **Hybrid Schemes (PQC + Classical ECC):** `X25519MLKEM768`, `SECP256R1MLKEM768`, `SECP384R1MLKEM1024`

By testing these specific configurations through the full connection lifecycle, the tool bridges the gap between advertised support and real-world negotiation — ensuring servers aren't vulnerable to **downgrade attacks** that strip away the post-quantum layer and fall back to weaker, classical security.

---

#### 🧪 [Pentesting-Methodology](https://github.com/SaadBaig/Pentesting-Methodology)

What began as handwritten notes documenting my pentesting workflow has evolved into a structured, end-to-end testing methodology. This repository reflects how I approach real-world engagements — covering enumeration, exploitation, and post-exploitation in a practical, repeatable way.

---

#### 💥 [DDoSing-DEFCON-2026](https://github.com/SaadBaig/DDoSing-DEFCON-2026)

A team of hackers setting up in the DDoS community at DEFCON 34 (2026). We're building a contest around hacked Temu WiFi repeaters — turning them into a DDoS botnet that offensive players can use to take down our targets. This repository documents our journey, journal style :)

---

#### 🎯 [Hack-the-Box-CPTS](https://github.com/SaadBaig/Hack-the-Box-CPTS)

My journey to get the CPTS :)
