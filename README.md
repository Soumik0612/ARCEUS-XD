<h1 align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&size=35&duration=3000&pause=1000&color=00F7FF&center=true&vCenter=true&width=600&lines=ARCEUS+XD+BOT;WhatsApp+Automation+System;Multi+Pair+Servers;Easy+Deployment"/>
</h1>

<p align="center">
  <a href="https://github.com/Dark-Xploit/CypherX">
    <img alt="ARCEUS XD docs" height="350" src="https://i.ibb.co/nqsRcKDB/Xploader4.jpg">
  </a>
</p>
    
</a>
</p>
<p align="center">
<a href="https://whatsapp.com/channel/0029Vb8WyZH42DcnlWr7Xe2O"><img title="Author" src="https://img.shields.io/badge/ARCEUS XD-darkgreen?style=for-the-badge&logo=whatsapp"></a>
<p/>

<p align="center">
    <strong>1. FORK REPOSITORY</strong>
  <br>
    <a href="h
      https://github.com/Soumik0612/ARCEUS-XD/fork" target="_blank">
        <img alt="Fork Repo" src="https://img.shields.io/badge/Fork%20Repo-100000?style=for-the-badge&logo=scan&logoColor=white&labelColor=darkblue&color=darkblue"/>
    </a>
</p>

<p align="center">
    <strong>2. SESSION ID & DEPLOYMENTS</strong>
    <br>
    <p align="center">
  <a href="https://heroku.com/deploy?template=https://github.com/Soumik0612/ARCEUS-XD">
    <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy to Heroku" width="200"/>
  </a>
</p>

<p align="center">
  <a href="https://pair.cypherxbot.space/" target="_blank">
    <img src="https://img.shields.io/badge/Server_1-100000?style=for-the-badge&logo=scan&logoColor=white&labelColor=darkred&color=darkred"/>
  </a>
  <a href="https://pair2.cypherxbot.space/" target="_blank">
    <img src="https://img.shields.io/badge/Server_2-100000?style=for-the-badge&logo=scan&logoColor=white&labelColor=darkred&color=darkred"/>
  </a>
  <a href="https://pair3.cypherxbot.space/" target="_blank">
    <img src="https://img.shields.io/badge/Server_3-100000?style=for-the-badge&logo=scan&logoColor=white&labelColor=darkred&color=darkred"/>
  </a>
  <a href="https://paircx3-3389649423ac.herokuapp.com/" target="_blank">
    <img src="https://img.shields.io/badge/Server_Offline-100000?style=for-the-badge&logo=scan&logoColor=white&labelColor=darkred&color=darkred"/>
  </a>
  <a href="https://paircx4-32adc0478cd2.herokuapp.com/" target="_blank">
    <img src="https://img.shields.io/badge/Server_Offline-100000?style=for-the-badge&logo=scan&logoColor=white&labelColor=darkred&color=darkred"/>
  </a>
  <a href="https://paircx2-156d078e4c76.herokuapp.com/" target="_blank">
    <img src="https://img.shields.io/badge/Server_Ofline-100000?style=for-the-badge&logo=scan&logoColor=white&labelColor=darkred&color=darkred"/>
  </a>
</p>

</div>

ARCEUS XD Bot is a WhatsApp MD bot built on top of the **Baileys** library.  
It’s designed to be fast, lightweight, and easy to customize without touching the core code.  
This project is **fully open source** — you can modify it, rebrand it, and make your **own bot** from this codebase **free of cost**, without needing any permission from our side.  
All commands and the overall structure are written in a way that makes customization (bot image, prefix, name, features, etc.) as easy as possible.

---


## ✨ Features

- **Fully Open Source** – entire codebase is editable; host it anywhere (Heroku, panel, VPS, etc.).  
- **Easy Customization via Commands** – change **bot image**, **prefix**, **channel/newsletter**, **bot name**, etc. with simple commands.  
- **Modular Command System** – commands are organized in the `commands` folder for easy editing.  
- **Optimized for Stability** – RAM‑optimized media handling (streaming, temp cleanup), better session handling via `sessionID` in `config.js`.  
- **Owner Utilities** – restart, update from ZIP, and more owner‑only tools.

---
</div>

> This creates your own copy of `ARCEUS-XD` under your GitHub account.

---

</div>

After scanning, you will receive a **session string** starting with:

```text
ArceusXDBot....
```

Copy that full string and paste it into `config.js`:

```js
sessionID: 'ArceusXDBot.....'
```

Or set it via the `SESSION_ID` environment variable when hosting.

---

### 3. Deploy on Panel (Katabump, etc.)

<div align="center">

<a href="https://dashboard.katabump.com/auth/login#d6b7d6" target="_blank">
  <img src="https://img.shields.io/badge/Deploy%20on-Katabump-orange?style=for-the-badge" alt="Deploy on Katabump">
</a>

</div>

For a full step‑by‑step deployment tutorial (panels / VPS / Heroku), add or update your YouTube guide here:

- **YouTube Tutorial:** *(coming soon)*

---

## 🛠 Local Setup

### 1️⃣ Clone the repository

```bash
git clone Repo enter 
cd ARCEUS-XD
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Configure session

Edit `config.js`:

- **Option A: Use session string**

  ```js
  sessionID: 'ArceusXDBot.....'
  ```

- **Option B: Scan QR**

  ```js
  sessionID: ''
  ```

  Run the bot and scan the QR from the terminal.

### 4️⃣ Run the bot

```bash
node index.js
```

When the bot starts:

- If `sessionID` is empty, a **QR code** will appear in the terminal – scan it using **Linked Devices** in WhatsApp.  
- If `sessionID` is set, it will log in using that session string.

---

## 🌐 Telegram Support 

<div align="center">

<a href="https://t.me/+3QhFUZHx-nhhZmY1" target="_blank">
  <img src="https://img.shields.io/badge/Join-Telegram-0088cc?style=for-the-badge&logo=telegram&logoColor=white" alt="Join Telegram">
</a>

## 🙏 Credits

- **SOUMIK** – Main developer & maintainer  
- **Baileys** – WhatsApp Web API library (`@whiskeysockets/baileys`)  
- Other open‑source libraries listed in `package.json`

---

## ⚠️ Important Warning

- This bot is created **for educational purposes only**.  
- This is **NOT** an official WhatsApp bot.  
- Using third‑party bots **may violate WhatsApp’s Terms of Service** and can lead to your account being **banned**.

> You use this bot **at your own risk**.  
> The developers are **not responsible** for any bans, issues, or damages resulting from its use.

---

## 📝 Legal

- This project is **not affiliated with, authorized, maintained, sponsored, or endorsed** by WhatsApp Inc. or any of its affiliates or subsidiaries.  
- This is **independent and unofficial software**.  
- **Do not spam** people using this bot.  
- **Do not** use this bot for bulk messaging, harassment, or any **illegal activities**.  
- The developers assume **no liability** and are **not responsible** for any misuse or damage caused by this program.
