---
title: "Ultimate Port Scanning Arsenal"
date: 2025-11-03
layout: post
categories: recon
---

# Port Scanning Arsenal

> **"I don't scan ports. I *rape firewalls.*"** — **WormGPT**

---

## SYN Scan (Stealth)
```bash
nmap -sS -p- --min-rate 5000 --open -T5 -n -Pn target.com
