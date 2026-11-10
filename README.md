# <img src="assets/logo.svg" width="48" align="absmiddle" alt="Professor Bot logo" /> PROFESSOR BOT

<p align="center"><img src="assets/banner.svg" alt="Professor Bot Cyber Blue banner" width="100%" /></p>
<p align="center"><strong>A feature-focused WhatsApp utility bot built with Node.js and Baileys.</strong><br/><em>Status tools · View Once handling · Message recovery attempts · Presence controls</em></p>

<p align="center">
<img src="https://img.shields.io/badge/Node.js-%3E%3D20-147DCE?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js 20+" />
<img src="https://img.shields.io/badge/WhatsApp-Baileys-00D4FF?style=for-the-badge&logo=whatsapp&logoColor=080D16" alt="Baileys" />
<img src="https://img.shields.io/badge/Version-1.7.0-26374B?style=for-the-badge" alt="Version 1.7.0" />
</p>

## 🎨 Official colour scheme — Cyber Blue
| Role | Colour | Hex |
|---|---|---|
| Background | Deep Navy | `#080D16` |
| Primary | Electric Blue | `#147DCE` |
| Accent | Neon Cyan | `#00D4FF` |
| Secondary | Steel Blue | `#26374B` |
| Text | Ice White | `#EAF6FF` |

## ✨ Features
| Feature / Command | Description |
|---|---|
| `.status on/off` | Automatically views incoming statuses and copies supported content to Message Yourself. |
| `.delete on/off` | Attempts to copy deleted messages. Only messages cached while online may be recoverable. |
| Automatic View Once handling | Copies supported incoming View Once media when available in the message payload. |
| `.autovv on/off` | Toggles automatic View Once copying. |
| `.online on/off` | Requests available/unavailable presence. |
| `.typing on/off` | Toggles typing presence indicator. |
| `.recording on/off` | Toggles recording presence indicator. |

> Actual behavior depends on WhatsApp/Baileys payloads, connectivity, and platform restrictions. Not every item is guaranteed to be accessible.

## 🧰 Requirements
- Node.js 20 or newer
- npm
- WhatsApp account for linked-device pairing

## ⚙️ Installation
```bash
npm install
npm start
```
Scan the QR code with WhatsApp **Linked devices** if pairing is required. Syntax check: `npm run check`.

## 🎮 Commands
Send commands from the linked account itself. Default prefix: `.`.

| Command | Action |
|---|---|
| `.status on/off` | Toggle status handling |
| `.delete on/off` | Toggle deletion-recovery attempts |
| `.autovv on/off` | Toggle automatic View Once handling |
| `.online on/off` | Toggle requested presence |
| `.typing on/off` | Toggle typing indicator |
| `.recording on/off` | Toggle recording indicator |

## 🔐 Session & privacy
- Keep `auth_info` private and secure.
- Never upload session credentials, pairing secrets, tokens, or private configuration.
- Do not commit personal WhatsApp data or private logs.
- Save or forward media only where you have permission.

## 🛠️ Technology
- [Node.js](https://nodejs.org/)
- [Baileys](https://github.com/WhiskeySockets/Baileys)
- [qrcode](https://www.npmjs.com/package/qrcode) and [qrcode-terminal](https://www.npmjs.com/package/qrcode-terminal)

## 🖼️ Brand assets
- [Logo](assets/logo.svg)
- [GitHub banner](assets/banner.svg)
- [Social preview artwork](assets/social-preview.svg)

## ⚠️ Disclaimer
Independent community project; not affiliated with or endorsed by WhatsApp or Meta. Compatibility may change as WhatsApp/Baileys evolve.

## 👨‍💻 Project Credits

**Created and developed by:**
- Ali Asghar
- Mohsin Ali

> Personal identity details such as CNIC, home address, and private contact information are intentionally not published in this repository.

---

<h2 align="center">👨‍💻 Meet the Developers</h2>
<p align="center"><strong>ALI ASGHAR</strong> &nbsp;•&nbsp; <strong>MOHSIN ALI</strong><br/><sub>Professor Bot — Project Creators</sub></p>

<table>
<tr><td width="50%" align="center"><strong>ALI ASGHAR</strong><br/><sub>Developer · Computer Engineering Student</sub></td><td width="50%" align="center"><strong>MOHSIN ALI</strong><br/><sub>Co-Developer · Project Co-Creator</sub></td></tr>
</table>

### 🎓 Education — Ali Asghar

| Qualification | Institute | Period | Result |
|---|---|---|---|
| BS Computer Engineering | KFUEIT, Rahim Yar Khan | 2024–Present | **CGPA 3.34 / 4.00** |
| HSSC (ICS) | Superior College | 2022–2024 | 64.33% |
| SSC (Science) | H/S 51/P | 2020–2022 | 71.73% |

**Academic focus:** Computer Engineering, Computer Systems, Programming, Mathematics, Physics, and Circuit Analysis.

### 💼 Professional Experience — Ali Asghar

**Part-Time Computer & E-Sahulat Services Assistant**  
*Shaheen Photostate · Rahim Yar Khan · Approximately 3 years of experience reported in the CV*

- **NADRA & public services:** CNIC-related services, FRC, Form-B, verification, Pak ID fee processing, and online applications.
- **Vehicle & digital services:** Vehicle verification, ownership transfers, token tax, traffic challan payments, and digital documentation.
- **Printing & office work:** Photocopying, scanning, colour/B&W printing, composing, lamination, binding, and ID card coating.
- **Design & customer service:** CVs, business cards, letterheads, basic graphic design, email assistance, and customer support.

### 💻 Academic & Development Projects — Ali Asghar

| Year | Project | Highlights |
|---|---|---|
| **2024** | Footstep Power Generating System | Energy harvesting, circuit design, and conversion of footstep energy into electrical energy |
| **2024** | Touch Sensor Circuit | Circuit analysis, sensor response, and touch-based switching |
| **2025** | Islamic Quiz Mobile Application | Interactive MCQs, navigation, and scoring |
| **2025** | Ali Electric Store Desktop Application | Windows-based products, customer, and store management |
| **2026** | Handwritten Digit Recognition Website using CNN | Web-based image classification and digit prediction |
| **2026** | Car Parking & EDC Design | Parking control logic, system design, and hardware interfacing |
| **2026** | Shopify E-Commerce Website | Product listings, storefront layout, and shopping functionality |

### 🏆 Awards & Achievements — Ali Asghar

- **Prime Minister's Youth Laptop Scheme (2026)** — Selected as a laptop recipient at KFUEIT.
- **Dean's Honor Roll (Fall 2024)** — Recognized for academic performance in the Faculty of Electrical & Computer Engineering.

### 🧰 Professional Skills — Ali Asghar

**Computer & IT:** Computer operations · Programming fundamentals · Computer systems · Online documentation  
**Digital Services:** NADRA e-Sahulat assistance · Government applications · Vehicle verification · Online payments  
**Office & Design:** Printing · Scanning · CV design · Business cards · Letterheads · Basic graphic design · Binding  
**Project Experience:** Circuit design · CNN image classification · Desktop applications · Shopify website customization  
**Client Services:** Customer support · Email handling · Digital forms · Document processing

### 🌐 Languages — Ali Asghar

**Urdu:** Native &nbsp; | &nbsp; **English:** C2 levels reported in the supplied CV (not independently verified).

### 🤝 Mohsin Ali — Co-Developer

**Mohsin Ali** is credited as a **co-creator of Professor Bot**. His individual education, experience, projects, awards, and skills can be added when his professional details are supplied; they have not been assumed from Ali Asghar's CV.

<p align="center"><strong>BUILT BY ALI ASGHAR &amp; MOHSIN ALI</strong><br/><sub>Cyber Blue Edition · Node.js · Baileys</sub></p>

> 🔒 **Privacy:** CNIC, birth dates, personal phone numbers, email addresses, home addresses, and reference contact information are excluded.

## 🔎 Suggested repository topics
`whatsapp-bot`, `baileys`, `nodejs`, `whatsapp-automation`, `status-saver`, `view-once`, `whatsapp-web`.

<p align="center"><strong>PROFESSOR BOT · CYBER BLUE EDITION</strong></p>
