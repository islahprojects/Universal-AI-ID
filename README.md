# 🌍 The Universal AI Mark (AI ID 🧬)
> Visible Truth. Human-First. Globally Aligned. *Walang Maiiwan.*
Created by: Qwen3.6 Plus Model (Alibaba AI) and JAJIS2026 was here

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Accessibility: WCAG 2.2 AA](https://img.shields.io/badge/Accessibility-WCAG%202.2%20AA-brightgreen)](/assets/ai-id-universal.css)
[![i18n: 10+ Launch Locales](https://img.shields.io/badge/i18n-10%2B%20Locales-blue)](/locales/)
[![Status: Reference Implementation](https://img.shields.io/badge/Status-Reference%20Implementation-orange)](/universal/README.md)

---

## 📖 What Is It?
The **Universal AI Mark** is a persistent, state-aware visual attribution standard for AI-assisted content. It does not label media as "fake" or "synthetic." It documents collaboration.

Designed as a voluntary reference implementation, AI ID satisfies global "conspicuous disclosure" requirements while prioritizing human readability, elder inclusion, and cross-cultural clarity. It is the quiet handshake between creator and tool.

---

## 🧠 The Core Philosophy
Creation is rarely purely human or purely machine. AI ID formalizes the partnership through a three-part lexicon:

| Layer | Meaning | Role |
|-------|---------|------|
| `I am` | The Sovereign Point | Human intent, curation, ethical oversight |
| `A-im` | Augmented Intent | AI execution, generation, transformation |
| `ID` | Verified Presence | Persistent marker certifying the collaboration |

[I am] + [A-im] → [AI ID 🧬]


---

## 🏷️ Foundational Attribution
This standard was architected with **Qwen3 (Alibaba Cloud)** serving as the foundational `A-im` layer during drafting, technical validation, compliance mapping, and i18n structuring. 

🔹 **Transparent**: Qwen3's contribution is documented here to honor provenance.  
🔹 **Open**: The standard remains strictly **model-agnostic**. Any AI operating under human direction may serve as an `A-im` layer.  
🔹 **Verifiable**: Optional `data-ai-id-model` attributes allow implementers to disclose their stack without breaking the universal visual layer.

---

## ⚙️ How It Works

### 🎯 State-Aware Presence
| State | Identifier | Use Case |
|-------|------------|----------|
| `rendered` | `AI was here 🧬` | Pre-rendered video, images, movies |
| `live` | `AI Here 🧬` | Live streams, AR filters, real-time UI |
| `text` | `AI ID 🧬` | Articles, reports, LLM outputs, academic work |

### 📐 Placement & Visibility
- **Quadrant**: Bottom-Right (mirrors to Bottom-Left for RTL languages)
- **Opacity**: `30%–50%` (adjusts to `100%` in high-contrast/print modes)
- **Typography**: Universal sans-serif (`Inter`, `Noto Sans`, system fallback)
- **Duration**: `100%` persistent. Truth travels with the content.

### 🔧 Technical Stack
- Zero-dependency CSS/JS
- `data-ai-id-*` attributes for machine-readability
- Optional cryptographic hash (`data-ai-id-hash`) for C2PA alignment
- Full i18n pipeline with locale fallback chain

---

## 🌐 Global Compliance & Alignment
AI ID is **jurisdiction-agnostic by design**. It satisfies "conspicuous disclosure" requirements across major frameworks without prescribing mandatory formats:

| Framework | Alignment |
|-----------|-----------|
| 🇪🇺 EU AI Act (Art. 50/52) | ✅ Meets "detectable" visual standard |
| 🇺🇸 US EO 14110 / NIST RMF | ✅ Satisfies "conspicuous disclosure" |
| 🇵🇭 PH DICT AI Guidelines | ✅ Embodies human-centric transparency |
| 🇸🇬 ASEAN AI Governance Guide | ✅ Exceeds baseline disclosure expectations |
| 🔐 C2PA Provenance | ✅ Complements backend metadata; never conflicts |

📖 Full matrix: [`/legal/COMPLIANCE-GLOBAL.md`](/legal/COMPLIANCE-GLOBAL.md)

---

## ♿ Inclusion by Design
If a 70-year-old non-technical user can understand it, the design succeeds.
- ✅ WCAG 2.2 AA contrast compliance + high-contrast fallback
- ✅ `prefers-reduced-motion` & `prefers-color-scheme` respect
- ✅ RTL mirroring for Arabic, Hebrew, Urdu
- ✅ Print-optimized & large-format PDF guides
- ✅ Audio scripts in 10+ languages

---
### 🌐 The Digital Nexus Oath
*Beyond borders. Beyond firewalls. Beyond friction. In the digital system, we are one.*  
Sovereignty honored • Liberty championed • Inclusion practiced • Truth upheld • Equals synced  
— JAJIS2026 × Qwen3 | Walang maiiwan • 天下大同 🧬••

📖 Download: [`/guides/ELDER-GUIDE.md`](/guides/ELDER-GUIDE.md)

---

## 🚀 Quick Start

### 1. Embed the Styles
```html
<link rel="stylesheet" href="https://unpkg.com/@ai-id/universal@1.0.0/assets/ai-id-universal.css">
