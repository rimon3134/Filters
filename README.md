<h1 align="left">🛡️ <strong>RK's Custom Filter Lists</strong></h1>
<p align="left">
  <em>Zero Noise. Zero Trackers. Zero Nonsense.</em><br>
  Precision-built filters — fast, reliable, and intentional.<br>
  Take full control of your web experience.
</p>

---

## 🔗 Live Page
🌐 **Interactive Hub:**  
👉 [https://rimon3134.github.io](https://rimon3134.github.io)  
<sub>Access live lists, examples, extended documentation, and updates.</sub>

---

## 📊 Badges
[![Repo Size](https://img.shields.io/github/repo-size/rimon3134/rimon3134.github.io?style=flat-square)](https://github.com/rimon3134/rimon3134.github.io) 
[![License](https://img.shields.io/github/license/rimon3134/rimon3134.github.io?style=flat-square)](https://github.com/rimon3134/rimon3134.github.io/blob/main/LICENSE) 
[![Last Commit](https://img.shields.io/github/last-commit/rimon3134/rimon3134.github.io?style=flat-square)](https://github.com/rimon3134/rimon3134.github.io/commits/main)

---

## ✨ Why RK’s Lists Exist
The modern web is noisy: ads, popups, overlays, telemetry, AI scripts, and anti-adblock mechanisms compete for your attention.

**RK’s Custom Filter Lists** were created to:

> **Silence the noise. Preserve functionality. Deliver speed without compromise.**

Every list is crafted intentionally:  
- ✔️ Performance-focused  
- ✔️ Tested on real-world sites  
- ✔️ Minimal, clean rules  
- ✔️ Stability-first — no reckless blocking  

> Not about blocking *everything*, just **what actually matters**.

---

## 📦 Core Lists

### 🏠 Hosts-Based Lists
| List | Status | Purpose |
|------|:------:|---------|
| **ZeroHosts** | 🟢 Safe | Broad hosts-level protection: ads, trackers, malware, phishing, spam.<br><em>Lean, stable, site-compatible.</em> |
| **uHosts** | 🟢 Safe | Optimized version of ZeroHosts for uBlock Origin.<br><em>Stable, minimal, compatible.</em> |
| **ZeroDNS** | 🟠 Lite | Compact, high-priority domain blocking.<br><em>Mobile-friendly, ~30K entries.</em> |

### 🔀 Hybrid Lists
| List | Status | Purpose |
|------|:------:|---------|
| **ZeroAds** | 🔵 Essential | Path-aware and token-based rules: block popups, redirects, widgets, overlays.<br><em>Modern annoyances tackled precisely.</em> |
| **AdGhost** | 🟣 Elite | Removes anti-adblock overlays, forced dialogs, and site lockouts before rendering.<br><em>Maintains functionality while silencing interruptions.</em> |
| **Phantom List** | 🔵 Essential | Eliminates heavy scripts, slow modules, widgets, cookies and more.<br><em>Pages breathe, browsers stop wheezing.</em> |

---

## ⚡ Why RK’s Lists Stand Out
| Feature | RK’s Lists | Typical Large Lists |
|--------|------------|-------------------|
| Domain-only coverage | ✅ | ✅ |
| Path & token hybrid rules | ✅ | ❌ |
| Modern annoyance blocking | ✅ | ❌ |
| Minimal false positives | ✅ | ⚠️ |
| Mobile-friendly | ✅ | Partial |
| Layered architecture (Hosts → DNS → Hybrid) | ✅ | ❌ |
| Real-world testing & performance-focused | ✅ | ✅ |

> TL;DR: Generic lists are good for privacy. RK’s lists go further, blocking modern annoyances while keeping false positives low and performance high.

---

## 🌐 Filter List URLs

### ZeroHosts
Comprehensive hosts-level protection against ads, trackers, malware, phishing, scam, and spam domains.
<em>Stable, site-compatible, and optimized for performance without aggressive blocking.</em>

```
https://raw.githubusercontent.com/rimon3134/Filters/main/ZeroHosts.txt
```
### ZeroAds
Hybrid filtering for modern web annoyances: popups, redirects, overlays, widgets, and scripts.
<em>Path-aware and token-based rules for a cleaner, quieter browsing experience.</em>

```
https://raw.githubusercontent.com/rimon3134/Filters/main/ZeroAds.txt
```
### ZeroDNS
Lightweight, high-priority domain blocking for ads, trackers, and telemetry.
<em>Designed for mobile and low-resource devices; fast, minimal, and effective (~30K entries).</em>

```
https://raw.githubusercontent.com/rimon3134/Filters/main/ZeroDNS.txt
```
### uHosts
Optimized version of ZeroHosts for uBlock Origin.
<em>Stable, site-compatible, and optimized for performance without aggressive blocking.</em>

```
https://raw.githubusercontent.com/rimon3134/Filters/main/uHosts.txt
```

### Phantom List
Removes heavy modules, slow scripts, widgets, and render-blocking elements using hybrid rules.
<em>Improves page performance and browsing smoothness.</em>

```
https://raw.githubusercontent.com/rimon3134/Filters/main/Phantom-List.txt
```

### AdGhost List
Prevents anti-adblock overlays, forced dialogs, and intrusive scripts from loading.
<em>Blocks aggressive interruptions while maintaining site functionality.</em>

```
https://raw.githubusercontent.com/rimon3134/Filters/main/AdGhost.txt
```

---

## 📘 Installation Guide

### 🟪 uBlock Origin
`Settings → Filter Lists → Custom → + Add → Paste URL → Update`

### 🟩 AdGuard
`Settings → Filters → Custom → Add URL → Save → Update`

### 🟥 AdBlock Plus
`Options → Advanced → Add new subscription → Paste → Apply`

### 🟧 1DM+
`Browser → Manage Adblock Hosts & Filters → Remove stock lists → Add → Force update`


<sub>🔄 Refresh occasionally — the web evolves constantly.</sub>

---

## 👤 About RiMoN
Optimizer. Debugger. Pattern-breaker.  
Believes digital experience should be: fast, quiet, efficient, fully under your control.

---

## 🧰 System-Level Protection
Browsers are one layer — the OS is deeper. System-level filtering blocks:  
- telemetry  
- ad networks  
- shady endpoints  
- background connection loops  
- silent I/O activity  

<em>Your system deserves the same clarity your browser gets.</em>

---

## 🛠️ Contributing
- Fork the repo  
- Test changes locally before PR  
- Keep hybrid rules **precise and intentional**  
- Avoid overlaps between ZeroDNS, ZeroHosts, and hybrid lists  
- Submit issues for bugs or suggested additions  

---

## ❓ FAQ

**Q: Why not rely only on large generic lists?**  
A: Domain-only lists are great for privacy, but **they can’t block same-domain annoyances** like popups, redirects, overlays, widgets. Hybrid rules are essential.

**Q: Will these lists break sites?**  
A: Minimal false positives — hybrid rules are tested carefully. Aggressive elements are removed **before rendering**.

**Q: How often are lists updated?**  
A: As needed — sometimes multiple times per day, sometimes weekly.

**Q: Can I use these on mobile?**  
A: Yes. ZeroDNS is optimized for low-resource devices; hybrid lists work in uBlock Origin, AdGuard, and compatible apps.

---

## ⚖️ License
MIT License © 2026 **Rimon Hossain**  
<sub>Crafted with intention, discipline, and a little midnight chaos ✨</sub>
