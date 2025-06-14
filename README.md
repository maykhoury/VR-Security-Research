# Copying Sessions in Oculus VR

> _Originally conducted as an academic research project by May Khoury and Yasmin Irshied, under the mentorship of Dr. Ori Shacham-Barr._  
> _This repository contains the final version of our research paper exploring the security of Oculus Quest casting and communication mechanisms._

---

##  Abstract

This research investigates whether it is possible to duplicate or intercept Oculus Quest casting sessions. The Oculus Quest's wireless casting feature introduces potential security concerns, especially regarding Datagram Transport Layer Security (DTLS) and STUN-based communication. Through network analysis, firmware extraction, and trusted execution environment exploration, we examine the feasibility of session interception and identify opportunities for future security research.

---

## Topics Covered

- Oculus Quest casting architecture and DTLS handshake behavior
- STUN protocol usage in casting communication
- Reverse engineering Oculus firmware using binwalk
- Trusted Execution Environment (TEE) and Qualcomm Secure Execution Environment (QSEE)
- Android Keystore and Keymaster HAL
- Android Debug Bridge (ADB) file system analysis and attack vectors
- Future research directions including ADB exploits and QSEE vulnerabilities

---
May Khoury and Yasmin Irshied, "Copying Sessions in Oculus VR", 2025.
Conducted under the supervision of Dr. Ori Shacham-Barr.
