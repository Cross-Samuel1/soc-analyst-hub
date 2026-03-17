# 🛡️ SOC Analyst Hub — Tier 1 Toolkit

> A free, fully offline interactive toolkit for Tier 1 SOC analysts — covering incident response, alert triage, threat hunting, and analyst onboarding. Zero dependencies. Single HTML file. Open in any browser.

**[🚀 Live Demo →](https://cross-samuel1.github.io/soc-analyst-hub/index.html)**

---

## 📦 What's Inside

### ⚡ Incident Response Checklists
Step-by-step interactive checklists for the most common incident types. Check off steps as you work — progress saves automatically.

- Phishing Email Investigation (12 steps)
- Malware / Endpoint Compromise (12 steps)
- Brute Force / Credential Attack (12 steps)
- Data Exfiltration Alert (12 steps)
- Suspicious PowerShell Activity (12 steps)

### 🔍 Alert Triage Playbooks
Decision-tree flows for assessing, classifying, and escalating alerts — with YES/NO branching logic and clear escalation thresholds.

- High-Volume Failed Logins
- Impossible Travel Alert
- Suspicious Process Execution
- DNS Beaconing Alert
- Lateral Movement Detected
- Cloud Storage Data Exposure

### 🎯 Threat Hunting Guides
Structured hunting hypotheses with MITRE ATT&CK tags, data sources, and ready-to-use Splunk / Elastic queries.

- LOLBAS Command Execution (T1218)
- Scheduled Task Persistence (TA0003)
- Kerberoasting Attempts (T1558.003)
- Outbound Connections on Non-Standard Ports (T1571)
- Pass-the-Hash Detection (T1550.002)

### 📡 Analyst Onboarding & Training
A structured 4-week learning path for new Tier 1 analysts — 4 modules, 20 lessons, click-to-complete progress tracking.

| Week | Module |
|------|--------|
| 1 | SOC Fundamentals — roles, toolchain, kill chain, ATT&CK |
| 2 | Alert Handling & Triage — severity, FP/TP, escalation |
| 3 | Investigation Skills — SIEM queries, process trees, threat intel |
| 4 | Incident Response Basics — NIST lifecycle, evidence, comms |

---

## 🚀 Usage

**Option A — Use the live demo (no install needed):**
👉 [https://cross-samuel1.github.io/soc-analyst-hub/](https://cross-samuel1.github.io/soc-analyst-hub/)

**Option B — Run locally:**
```bash
git clone https://github.com/cross-samuel1/soc-analyst-hub.git
cd soc-analyst-hub
# Open soc_hub.html in any browser — no server required
```

**Option C — Download directly:**
Click `soc_hub.html` → **Download raw file** → open in browser.

---

## 🔧 Features

- ✅ **Fully offline** — no internet required after first load
- ✅ **Zero dependencies** — no npm, no build step, no framework
- ✅ **Progress persistence** — checklist and training state saves via localStorage
- ✅ **Tier 1 focused** — built for analysts starting from scratch
- ✅ **Real queries** — Splunk and Elastic SPL included
- ✅ **MITRE ATT&CK aligned** — technique IDs referenced throughout

---

## 🗂️ File Structure

```
soc-analyst-hub/
└── soc_hub.html     # The entire app — HTML + CSS + JS in one file
└── README.md
```

---

## 🤝 Contributing

Contributions welcome — new playbooks, additional hunt queries, updated techniques, or UI improvements.

1. Fork the repo
2. Create a branch: `git checkout -b add-new-playbook`
3. Make your changes to `soc_hub.html`
4. Submit a Pull Request with a description of what you added

Ideas for contributions:
- [ ] Ransomware IR checklist
- [ ] Cloud-native threat hunting queries (AWS CloudTrail, Azure Sentinel)
- [ ] SOAR integration notes
- [ ] Additional MITRE ATT&CK coverage

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

## 👤 Author

**Samuel Cross**
- GitHub: [@cross-samuel1](https://github.com/cross-samuel1)
- Project: [SOC Analyst Hub](https://cross-samuel1.github.io/soc-analyst-hub/)

---

*Built for the blue team community. If this helped you, give it a ⭐ — it helps others find it.*
