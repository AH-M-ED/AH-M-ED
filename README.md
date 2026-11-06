
<div align="center">

# Telecommunications Security Research

### Security Engineering · Vulnerability Research · Protocol Fuzzing

**2G / GSM · 3G / UMTS · 4G / LTE · 5G**

[![Research Portfolio](https://img.shields.io/badge/Security-Research%20Portfolio-334155?style=flat-square)](https://github.com/AH-M-ED/Telco-security-research)
[![Security Advisories](https://img.shields.io/badge/GitHub-Security%20Advisories-0369a1?style=flat-square)](https://github.com/advisories?query=credit%3Ap1-aji)

</div>

---

## About

Telecommunications security engineer and vulnerability researcher specializing in **2G, 3G, 4G/LTE, and 5G network security**.

My work focuses on identifying and analyzing security vulnerabilities in mobile network infrastructure, telecom signaling protocols, radio access and core network components, and cloud-native telecommunications platforms.

Key areas of expertise:

- **Telecom Security:** Security assessments of mobile core networks, RAN components, and signaling infrastructure.
- **Vulnerability Research:** Discovery, analysis, and coordinated disclosure of security vulnerabilities.
- **Protocol Fuzzing:** Identifying implementation weaknesses through malformed signaling messages and protocol state-machine testing.
- **Offensive Security:** Penetration testing, attack surface analysis, and security validation.
- **Cloud-Native Security:** Kubernetes, OpenShift, containerized network functions, and infrastructure security.

---

## Published Security Research

My public vulnerability research includes findings affecting open-source mobile core implementations and commercial telecommunications products.

### Ella Core — 5G Core Network

Research focused on NGAP/NAS message handling, input validation, and denial-of-service vulnerabilities affecting 5G Core Network Functions.

| CVE | Vulnerability | Advisory |
|---|---|---|
| **CVE-2026-32319** | AMF DoS via undersized integrity-protected NAS payload | [GHSA-m9pm-w3gv-c68f](https://github.com/advisories/GHSA-m9pm-w3gv-c68f) |
| **CVE-2026-32320** | AMF DoS via malformed NGAP PathSwitchRequest | [GHSA-j478-p7vq-3347](https://github.com/advisories/GHSA-j478-p7vq-3347) |
| **CVE-2026-33281** | AMF panic triggered by invalid PDU Session IDs | [GHSA-q669-4gmv-g8mf](https://github.com/advisories/GHSA-q669-4gmv-g8mf) |
| **CVE-2026-33282** | AMF panic triggered by malformed NGAP Location Report | [GHSA-826q-wrq4-p23x](https://github.com/advisories/GHSA-826q-wrq4-p23x) |
| **CVE-2026-33283** | AMF panic triggered by malformed ULNASTransport messages | [GHSA-3366-gw57-fcm5](https://github.com/advisories/GHSA-3366-gw57-fcm5) |

[View original GitHub researcher credits](https://github.com/advisories?query=credit%3Ap1-aji)

### free5GC — 5G Core Network

**CVE-2022-38870 — Unauthenticated Subscriber Information Disclosure**

Identified an authentication weakness in the free5GC webconsole that exposed sensitive information, including registered UEs, subscriber data, tenants, and user information.

- [CVE-2022-38870 — NVD](https://nvd.nist.gov/vuln/detail/CVE-2022-38870)
- [Original Vulnerability Report — Issue #387](https://github.com/free5gc/free5gc/issues/387)

### Ericsson Packet Core Controller (PCC)

**CVE-2025-59180 — Hardcoded Credentials in the Alarm System**

Vendor security disclosure concerning hardcoded credentials within the Ericsson PCC alarm system.

- [CVE-2025-59180 — Official CVE Record](https://www.cve.org/CVERecord?id=CVE-2025-59180)

*Individual researcher attribution for this disclosure is not established in the public record.*

---

## Open-Source Vulnerability Reports

### Open5GS — 4G/5G Core Network

Security issues identified through malformed protocol message testing and robustness assessments.

| Report | Description | Reference |
|---|---|---|
| SMF Crash | Crash when parsing malformed Extended Protocol Configuration Options (EPCO) in a PDU Session Establishment Request | [Issue #4341](https://github.com/open5gs/open5gs/issues/4341) |
| MME Crash | Crash triggered by a malformed S1AP/NAS Attach Request | [Issue #4357](https://github.com/open5gs/open5gs/issues/4357) |

### free5GC

| Report | Description | Reference |
|---|---|---|
| Webconsole Information Disclosure | Unauthenticated access to registered UE and subscriber information | [Issue #387](https://github.com/free5gc/free5gc/issues/387) |

For additional research details:

**[Explore the Telecom Security Research Portfolio](https://github.com/AH-M-ED/Telco-security-research)**

---

## Publications & Technical Writing

### Fuzzing the Mobile Core: How Malformed 5G/4G Signaling Crashes Production Networks

**P1 Security | May 7, 2026**

A technical research article I authored during my time at P1 Security, examining how malformed signaling messages can expose implementation weaknesses and trigger service disruptions in mobile core network functions.

The article covers:

- Fuzzing approaches for mobile core signaling protocols.
- Security testing of NGAP, NAS, PFCP, and other interfaces.
- Case studies involving vulnerabilities discovered in Ella Core.
- Root causes of parser crashes, application panics, and denial-of-service conditions.
- Security implications for mobile network availability and resilience.

**[Read the full research article on P1 Security](https://www.p1sec.com/blog/fuzzing-the-mobile-core-how-malformed-5g-4g-signaling-crashes-production-networks)**

---

## Technical Expertise

### Mobile Network Security

| Generation | Technologies & Protocols |
|---|---|
| **2G / GSM** | GSM, GPRS, SS7, MAP, SCCP, SIGTRAN |
| **3G / UMTS** | UMTS, SGSN, GGSN, SS7, MAP, GTP |
| **4G / LTE** | EPC, MME, SGW, PGW, HSS, S1AP, NAS, Diameter, GTP |
| **5G** | 5GC, AMF, SMF, UPF, NRF, AUSF, UDM, NGAP, PFCP, SBI |

### Security Research & Testing

- **Protocol Security:** SS7, Diameter, GTP, PFCP, SCTP, NAS, NGAP, S1AP, X2AP.
- **Fuzzing:** Protocol mutation, malformed message testing, robustness analysis, and crash investigation.
- **Infrastructure Security:** Linux, Kubernetes, OpenShift, container security, and network segmentation.
- **API Security:** REST APIs, HTTP/2, gRPC, and service-based interfaces.
- **Vulnerability Analysis:** Root cause analysis, proof-of-concept validation, and coordinated vulnerability disclosure.

### Tools & Technologies

`Python` · `Scapy` · `Wireshark` · `tcpdump` · `Nmap` · `Burp Suite` · `boofuzz` · `Linux` · `Docker` · `Kubernetes` · `OpenShift` · `Open5GS` · `UERANSIM`

---

## Research Portfolio & References

| Resource | Link |
|---|---|
| Telecom Security Research | [GitHub Repository](https://github.com/AH-M-ED/Telco-security-research) |
| Published GitHub Advisories | [Researcher Credits](https://github.com/advisories?query=credit%3Ap1-aji) |
| Open5GS Vulnerability Research | [Open5GS Issues](https://github.com/open5gs/open5gs/issues?q=author%3Ap1-aji) |
| free5GC Vulnerability Disclosure | [Issue #387](https://github.com/free5gc/free5gc/issues/387) |
| Mobile Core Fuzzing Publication | [P1 Security Blog](https://www.p1sec.com/blog/fuzzing-the-mobile-core-how-malformed-5g-4g-signaling-crashes-production-networks) |

---

## Research Attribution & Disclosure

Some of the vulnerabilities and security reports referenced here were originally disclosed through my professional GitHub account [@p1-aji](https://github.com/p1-aji) during my work at P1 Security.

The original GitHub issues, published security advisories, and vendor disclosures remain the authoritative records for vulnerability details and researcher attribution.

This profile serves as a personal index of publicly disclosed security research and technical publications.

---

<div align="center">

**Telecommunications Security · Vulnerability Research · Protocol Fuzzing**

[Research Portfolio](https://github.com/AH-M-ED/Telco-security-research) · [Published Advisories](https://github.com/advisories?query=credit%3Ap1-aji) · [Technical Publication](https://www.p1sec.com/blog/fuzzing-the-mobile-core-how-malformed-5g-4g-signaling-crashes-production-networks)

</div>
