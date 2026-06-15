# Network Architect — Mock Interview Engine

An interactive, self-contained mock-interview app for senior network engineers stepping up toward **Principal / Staff / Lead Network Architect** roles.

**▶ Live:** https://zephyrsai.github.io/network-architect-mock-interview/

## What it is

A single `index.html` file (no build, no dependencies, runs fully offline) with a **400-question** bank spanning 19 domains:

- **Routing:** BGP, OSPF/IS-IS/EIGRP, MPLS L3VPN, Segment Routing
- **Data center:** VXLAN/EVPN, Cisco Nexus / vPC, ACI / NDFC, Clos design
- **WAN/Edge:** Cisco SD-WAN (Viptela), Cloud & Hybrid connectivity
- **Security:** Multi-vendor NGFW (Palo Alto, FTD/FMC, FortiGate, Check Point), NAC / ISE / 802.1X / MACsec, Zero Trust & SASE
- **Foundations:** Switching & STP, QoS & Multicast, Network Services (DNS/DHCP/TLS), Wireless & Campus
- **Operations & leadership:** NOC / troubleshooting, Automation & Monitoring (NetDevOps), Architecture & Leadership, Behavioral (situational judgment)

## Features

- **Practice mode** (instant feedback + reasoning) and **Exam mode** (feedback at the end)
- **Adaptive difficulty** — climbs to Architect level on correct answers, drops on misses
- **Progress bar, timer, difficulty-weighted scoring**, per-domain and per-difficulty result breakdowns
- **Detailed reasoning on every wrong answer** — explains why the correct option is right and why the tempting ones fail
- **Persistent mastery map** in your browser (localStorage) — tracks lifetime accuracy and resurfaces unseen / previously-missed questions each run, so it keeps teaching new material
- **"Retry weak areas"** pulls your lowest-scoring domains

## Usage

Open the live link above, or clone and open `index.html` in any browser. Pick a mode, difficulty, length, and domains, then start. Keyboard: `1–4` to answer, `Enter` to advance, `F` to flag.

---

Built as a personalized interview-prep tool. Progress is stored only in your own browser.
