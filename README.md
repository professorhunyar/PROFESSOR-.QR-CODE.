# ⚡ PROFESSOR QR CODE — WhatsApp Bot

<p align="center">
  <strong>A clean, feature-focused WhatsApp companion built with Baileys.</strong><br/>
  <em>Smart status tools · View Once handling · Message recovery · Presence controls</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-%3E%3D20-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js 20+" />
  <img src="https://img.shields.io/badge/WhatsApp-Baileys-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp Baileys" />
  <img src="https://img.shields.io/badge/Version-1.7.0-6C63FF?style=for-the-badge" alt="Version 1.7.0" />
  <img src="https://img.shields.io/badge/Runtime-Node.js-222222?style=for-the-badge&logo=nodedotjs" alt="Node.js runtime" />
</p>

---

## ✨ Overview

**PROFESSOR QR CODE** is a WhatsApp automation project powered by **Node.js** and **Baileys**. It brings together status utilities, View Once handling, message-deletion recovery attempts, and presence controls in one linked-device bot.

The project is designed to be straightforward to configure and run from a terminal or a supported Node.js hosting environment.

## 🚀 Features

| Feature / Command | What it does |
|---|---|
| `.status on/off` | Automatically marks incoming WhatsApp statuses as viewed and copies supported status content to Message Yourself. |
| `.delete on/off` | Attempts to copy deleted messages to Message Yourself. Only messages received and cached while the bot is online may be recoverable. |
| Automatic View Once handling | Copies supported incoming View Once image, video, or audio content to Message Yourself when the message payload allows it. |
| `.autovv on/off` | Enables or disables automatic View Once copying. |
| `.online on/off` | Requests available/unavailable presence. WhatsApp may not keep a linked device continuously online. |
| `.typing on/off` | Sends a typing presence indicator when a message arrives. |
| `.recording on/off` | Sends a recording presence indicator when a message arrives. |

> **Note:** Actual behavior depends on WhatsApp and Baileys message payloads, device connectivity, and platform restrictions. Not every status, deletion, or View Once item is guaranteed to be accessible.

## 🧰 Requirements

- Node.js **20 or newer**
- npm
- A WhatsApp account for linked-device pairing
- A terminal or Node.js hosting environment

## ⚙️ Installation

1. Clone or download this repository.
2. Open a terminal in the project folder.
3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the bot:

   ```bash
   npm start
   ```

5. If pairing is required, scan the QR code using WhatsApp's **Linked devices** feature.

To check JavaScript syntax:

```bash
npm run check
```

## 🎮 Commands

Send commands from the linked account itself. The default command prefix is `.`.

| Command | Action |
|---|---|
| `.status on` | Turn status handling on |
| `.status off` | Turn status handling off |
| `.delete on` | Enable deletion-recovery attempts |
| `.delete off` | Disable deletion-recovery attempts |
| `.autovv on` | Enable automatic View Once handling |
| `.autovv off` | Disable automatic View Once handling |
| `.online on` | Request available presence |
| `.online off` | Request unavailable presence |
| `.typing on/off` | Toggle typing indicator |
| `.recording on/off` | Toggle recording indicator |

## 🔐 Session & Privacy

- Keep the `auth_info` session folder private and secure.
- **Never upload or share** session credentials, QR pairing secrets, tokens, or private configuration.
- Do not commit personal WhatsApp data or private logs to a public repository.
- Use message and media features only when you have the right to access and save that content.

## 🛠️ Tech Stack

- [Node.js](https://nodejs.org/) — JavaScript runtime
- [Baileys](https://github.com/WhiskeySockets/Baileys) — WhatsApp Web protocol library
- [qrcode](https://www.npmjs.com/package/qrcode) and [qrcode-terminal](https://www.npmjs.com/package/qrcode-terminal) — QR rendering

## ⚠️ Disclaimer

This is an independent community project and is not affiliated with, endorsed by, or officially supported by WhatsApp or Meta. WhatsApp/Baileys behavior and compatibility may change. The README documents the configured project features; it does not claim that every feature has been live-tested in every hosting environment.

## 🔎 Search & Discovery

Relevant project topics: `whatsapp-bot`, `baileys`, `nodejs`, `whatsapp-automation`, `status-saver`, `view-once`, `whatsapp-web`.

---

<p align="center">
  <strong>PROFESSOR QR CODE</strong><br/>
  <sub>Built with Node.js · Powered by Baileys</sub>
</p>
