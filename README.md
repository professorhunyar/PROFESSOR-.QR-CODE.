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

## 🔎 Suggested repository topics
`whatsapp-bot`, `baileys`, `nodejs`, `whatsapp-automation`, `status-saver`, `view-once`, `whatsapp-web`.

<p align="center"><strong>PROFESSOR BOT · CYBER BLUE EDITION</strong></p>
