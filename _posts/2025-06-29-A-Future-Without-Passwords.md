---
title: "A Future Without Passwords? How Quantum Tech Is Redefining Authentication - news article"
image: images/passwords_with-quantumn_tech_news.jpeg
author: Aditya Mitra, Professor Sibi Chakkaravarthy Sethuraman, Devi Priya V. S
Original paper: 
Source Code: 
tags: quantumn , password less , fido 

---

![news article](https://raw.githubusercontent.com/airvitap/airvitap.github.io/refs/heads/main/images/passwords_with-quantumn_tech_news.jpeg)


**A Future Without Passwords? How Quantum Tech Is Redefining Authentication**
*June 2025 – VIT‑AP Quantum Security Lab*

In an era where password leaks, reuse, and brute‑force attacks dominate headlines, our team at the VIT‑AP Quantum Security Lab is proud to unveil a **quantum‑resistant, passwordless authentication prototype** built on open standards. Led by student researcher **Aditya Mitra**, Professor **Sibi Chakkaravarthy Sethuraman**, and Researcher **Devi Priya V. S.**, our work tackles the twin challenges of usability and post‑quantum security head‑on.

---

### Why Passwords Are Holding Us Back

* **Reused and Cracked**: Most users rely on the same passwords across multiple sites, making a single breach catastrophic.
* **Vulnerable to Phishing and Key‐Logging**: Traditional passwords can be harvested with alarming ease.
* **Quantum Threats on the Horizon**: Widely deployed cryptosystems like RSA and ECC—cornerstones of today’s secure connections—will succumb to sufficiently powerful quantum computers.

---

### Our Quantum‑Safe Solution

1. **WebAuthn + FIDO2 Ecosystem**
   We leveraged the W3C’s Web Authentication (WebAuthn) standard together with FIDO2’s Client to Authenticator Protocol (CTAP2) to create a familiar “touch‑to‑login” experience.
2. **ML‑DSA: A Post‑Quantum Signature Scheme**
   At the heart of our design is ML‑DSA, a digital signature algorithm standardized in **FIPS 204**. ML‑DSA provides security even against adversaries wielding quantum hardware.
3. **Real‑World Prototype**

   * **Device‑Resident Keys**: Authentication keys are generated and stored within the user’s device hardware (e.g., secure enclave or TPM).
   * **Tamper‑Proof Login**: Biometric or PIN verification on the device unlocks the quantum‑safe key—without ever exposing it to the network.
   * **Interoperability**: Our prototype works seamlessly across browsers and operating systems that support FIDO2.

---

### Key Highlights & Impact

* **Phishing‑Resistant**: No shared secrets travel over the wire, eliminating phishing and man‑in‑the‑middle attacks.
* **Quantum‑Ready**: By eschewing RSA/ECC in favor of ML‑DSA, we future‑proof authentication workflows against the coming wave of quantum cracking tools.
* **User‑Friendly**: One touch (or glance) to log in—no more memorizing or managing complex passwords.

---

### What’s Next

* **Field Trials**: We are collaborating with partner organizations to deploy pilot programs in higher education and enterprise environments.
* **Open‑Source Toolkit**: Later this year, our complete FIDO2 ML‑DSA implementation will be published under an open‑source license for community review and integration.
* **Extending to IoT**: Work is already underway to adapt our approach to resource‑constrained Internet of Things devices.

---



> *“Our goal is to guide organizations toward a passwordless, quantum‑secure future—one tap at a time.”*
> — Aditya Mitra, Student Researcher, VIT‑AP University

Stay tuned to the VIT‑AP Quantum Security Lab for more updates on breaking research in post‑quantum cryptography and next‑generation authentication systems!
