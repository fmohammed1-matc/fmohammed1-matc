![Defensive Cybersecurity — Fahad](assets/hero.webp)

# 👋 Hi, I'm Fahad

<img src="assets/fahad.jpg" width="110" align="left" />

Aspiring security engineer. I got into cybersecurity because I wanted to understand how attacks actually work, not just read about them — so I started building. Everything here is **defensive**: tools that catch intruders, kill ransomware mid-attack, expose phishing, and find leaked secrets before the bad guys do.

<br clear="both"/>

---

## 🛡️ Projects

### [sentinel-dns](https://github.com/fmohammed1-matc/sentinel-dns) — DNS Tunneling & Exfiltration Detector

![sentinel-dns showcase](assets/sentinel-dns.mp4)

Hackers sometimes hide stolen data inside ordinary internet address requests. This watches those requests and spots the hidden patterns — messages sent too regularly, addresses that look randomly generated — and explains exactly why each one looks suspicious.

### [canarytrip](https://github.com/fmohammed1-matc/canarytrip) — Ransomware Canary Tripwire

![canarytrip showcase](assets/canarytrip.mp4)

Ransomware locks your files and demands money. This plants invisible bait files on your computer and watches them — the moment something starts scrambling them, it kills the attacker before your real files are touched.

### [phishlens](https://github.com/fmohammed1-matc/phishlens) — Phishing Email Forensics

![phishlens showcase](assets/phishlens.mp4)

Fake emails are how most hacks start. Upload a suspicious email and this breaks it down like a detective: where it really came from, whether its security stamps check out, and which links are traps.

### [airguard](https://github.com/fmohammed1-matc/airguard) — Rogue Access Point Detector

![airguard showcase](assets/airguard.mp4)

Hackers set up fake Wi-Fi hotspots with familiar names to steal your passwords. This listens to the wireless signals around you and flags the fakes — wrong hardware IDs, strange signal behavior, copycat network names.

### [intelfusion](https://github.com/fmohammed1-matc/intelfusion) — Threat-Intel Correlation Engine

![intelfusion showcase](assets/intelfusion.mp4)

Security teams drown in threat reports. This pulls in public threat intelligence and matches it against your own logs, so you can see which known-bad addresses and files have actually touched your network — on a 3D map.

### [honeymesh](https://github.com/fmohammed1-matc/honeymesh) — SSH Honeypot Mesh

![honeymesh showcase](assets/honeymesh.mp4)

A honeypot is a trap — a fake server that looks easy to hack. This runs a network of them, studies how attackers try to break in (what usernames they guess, what tools they use), and scores how dangerous each attacker looks.

### [usbsentinel](https://github.com/fmohammed1-matc/usbsentinel) — USB Attack Monitor

![usbsentinel showcase](assets/usbsentinel.mp4)

A USB stick can be a weapon — some pretend to be keyboards and start typing malicious commands the second they're plugged in. This watches every USB device, flags the fakes, and spots rapid file copying that looks like data theft.

### [lateralens](https://github.com/fmohammed1-matc/lateralens) — Lateral Movement Detector

![lateralens showcase](assets/lateralens.mp4)

Once hackers get into one computer, they quietly hop to others. This maps how logins move between machines on a network and flags the suspicious hops — chained remote sessions, logins in two places at once, movement at 3am.

### [leakguard](https://github.com/fmohammed1-matc/leakguard) — Secret Leak Scanner

![leakguard showcase](assets/leakguard.mp4)

Developers accidentally publish passwords and API keys in their code — even "deleted" ones stay in the file history. This scans files and past versions, finds the leaked secrets, and can automatically black them out.

### [bgpwatch](https://github.com/fmohammed1-matc/bgpwatch) — BGP Hijack Monitor

![bgpwatch showcase](assets/bgpwatch.mp4)

The internet runs on trust between networks about who owns which addresses — and attackers sometimes lie to reroute traffic through themselves. This watches those routing announcements and flags the lies.