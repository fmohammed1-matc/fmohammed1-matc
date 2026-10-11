![Defensive Cybersecurity — Fahad](assets/hero.webp)

# 👋 Hi, I'm Fahad

<img src="assets/fahad.jpg" width="110" align="left" />

Aspiring security engineer. I got into cybersecurity because I wanted to understand how attacks actually work, not just read about them — so I started building. Everything here is **defensive**: tools that catch intruders, kill ransomware mid-attack, expose phishing, and find leaked secrets before the bad guys do.

<br clear="both"/>

---

## 🛡️ Projects

### [sentinel-dns](https://github.com/fmohammed1-matc/sentinel-dns) — DNS Tunneling & Exfiltration Detector

![sentinel-dns showcase](assets/sentinel-dns.mp4)

Finds DNS tunneling, data exfiltration over DNS, and DGA activity hiding in resolver logs. Transparent weighted heuristics (entropy, query length, beaconing rate, NXDOMAIN ratio) — every score ships with its reasons. Cinematic 3D globe dashboard with a live feed.

### [canarytrip](https://github.com/fmohammed1-matc/canarytrip) — Ransomware Canary Tripwire

![canarytrip showcase](assets/canarytrip.mp4)

Behavioral endpoint defense: plants canary files and watches for the entropy burst + mass-rename pattern of ransomware, killing the process before your real files are gone. Safe burst simulator included (touches `/tmp` only).

### [phishlens](https://github.com/fmohammed1-matc/phishlens) — Phishing Email Forensics

![phishlens showcase](assets/phishlens.mp4)

Upload a `.eml`, get the full story: Received-chain analysis, SPF/DKIM/DMARC authentication, homoglyph & typosquat detection, URL reputation. One-click demo samples bundled in.

### [airguard](https://github.com/fmohammed1-matc/airguard) — Rogue Access Point Detector

![airguard showcase](assets/airguard.mp4)

Catches evil-twin attacks with 802.11 beacon analysis — flags spoofed BSSIDs, signal anomalies, and impersonated SSIDs. 3D radar dashboard with live replay of a planted evil twin.

### [intelfusion](https://github.com/fmohammed1-matc/intelfusion) — Threat-Intel Correlation Engine

![intelfusion showcase](assets/intelfusion.mp4)

A mini-SIEM: correlates OSINT threat-intel feeds against your local logs, scores IOCs, and maps everything geographically. Fully offline demo mode with fixture data.

### [honeymesh](https://github.com/fmohammed1-matc/honeymesh) — SSH Honeypot Mesh

![honeymesh showcase](assets/honeymesh.mp4)

Distributed fake SSH servers that fingerprint attackers — client versions, sprayed credentials, reconnect timing — and score their intent 0–100. Live 3D globe with attack arcs and a top-attackers feed.

### [usbsentinel](https://github.com/fmohammed1-matc/usbsentinel) — USB Attack Monitor

![usbsentinel showcase](assets/usbsentinel.mp4)

Watches USB insertions: device allowlist, BadUSB keystroke-injection heuristics (inhuman typing bursts), `autorun.inf` detection, and rapid-write exfiltration alerts. 3D device timeline dashboard.

### [lateralens](https://github.com/fmohammed1-matc/lateralens) — Lateral Movement Detector

![lateralens showcase](assets/lateralens.mp4)

Builds a host→host session graph from auth logs and catches hackers hopping between machines: RDP/WinRM chains, impossible travel, off-hours jumps. 3D network graph with attack paths in red.

### [leakguard](https://github.com/fmohammed1-matc/leakguard) — Secret Leak Scanner

![leakguard showcase](assets/leakguard.mp4)

Hunts exposed secrets with entropy + pattern detection across files *and* git history (finds secrets "deleted" in later commits). `--redact` mode masks everything. 3D file-risk treemap.

### [bgpwatch](https://github.com/fmohammed1-matc/bgpwatch) — BGP Hijack Monitor

![bgpwatch showcase](assets/bgpwatch.mp4)

Watches internet routing for hijacks: origin-AS changes, suspicious more-specifics, and abnormal AS paths against trust anchors. 3D AS-path flow visualization with animated hijack arcs.

---

## 🧰 Skills

Python · Network security · DNS analysis · Threat intelligence · Malware behavior detection · Email authentication (SPF/DKIM/DMARC) · 3D data visualization · Honeypots · Lateral movement detection · BGP security · Secrets management

---

## 📫 Connect

<img src="assets/fahad.jpg" width="80" align="left" />

Everything here is designed, built, and maintained by me — Fahad. If a project helped you, a ⭐ is always appreciated.

**GitHub:** [@fmohammed1-matc](https://github.com/fmohammed1-matc)
