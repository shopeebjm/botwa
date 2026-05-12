<img src="https://readme-typing-svg.herokuapp.com?color=%2336BCF7&center=true&vCenter=true&lines=YouTube+@shopee_banjarmasin" />
</p>
<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?color=%2336BCF7&center=true&vCenter=true&lines=s+h+o+p+e+e+b+j+m" />
</p>

<h2 align="center">
  
[![Powered By:shopeebjm](https://img.shields.io/badge/PoweredBy:shopeebjm-7%2B-blue.svg?style=flat)](http://linktr.ee/kiplymacho)

# Persyaratan
- Pasang Aplikasi Termux Di Android Tetapi Untuk Aplikasi Termux Jangan Di Unduh Di Playstore Karena Bisa Menyebabkan Error
<h2 align="center">

Unduh Aplikasi Termux Nya Dibawah Ini

👇👇

[![termux](https://img.shields.io/badge/termux-83%2B-yellow.svg?style=flat)](https://sfile.co/eZK8yBBtOiv)

[![Android](https://img.shields.io/badge/Android-15-yellow.svg?style=flat)](https://developer.android.com/about/versions/15?hl=id)


## Information

<div align="center">
<a href="https://github.com/nazedev/hitori/watchers"><img title="Watchers" src="https://img.shields.io/github/watchers/nazedev/hitori?label=Watchers&color=green&style=flat-square"></a>
<a href="https://github.com/nazedev/hitori/network/members"><img title="Forks" src="https://img.shields.io/github/forks/nazedev/hitori?label=Forks&color=blue&style=flat-square"></a>
<a href="https://github.com/nazedev/hitori/stargazers"><img title="Stars" src="https://img.shields.io/github/stars/nazedev/hitori?label=Stars&color=yellow&style=flat-square"></a>
<a href="https://github.com/nazedev/hitori/issues"><img title="Issues" src="https://img.shields.io/github/issues/nazedev/hitori?label=Issues&color=success&style=flat-square"></a>
<a href="https://github.com/nazedev/hitori/issues?q=is%3Aissue+is%3Aclosed"><img title="Issues" src="https://img.shields.io/github/issues-closed/nazedev/hitori?label=Issues&color=red&style=flat-square"></a>
<a href="https://github.com/nazedev/hitori/pulls"><img title="Pull Request" src="https://img.shields.io/github/issues-pr/nazedev/hitori?label=PullRequest&color=success&style=flat-square"></a>
<a href="https://github.com/nazedev/hitori/pulls?q=is%3Apr+is%3Aclosed"><img title="Pull Request" src="https://img.shields.io/github/issues-pr-closed/nazedev/hitori?label=PullRequest&color=red&style=flat-square"></a>
</div>

This script is created by [Nazedev](https://github.com/nazedev) using Node.js and the [WhiskeySocket/Baileys](https://github.com/WhiskeySockets/Baileys) library. The script is currently in the development phase (BETA), so there may still be some errors that can be ignored. If errors persist even after debugging, please contact the owner for assistance. ~ By Naze

#### Join Group
[![Grup WhatsApp](https://img.shields.io/badge/WhatsApp%20Group-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://chat.whatsapp.com/EApQZ65s9wF1UG5nD6Pinm?mode=gi_t) 

---
## 📦 Requirements

Minimum requirements:
- **Node.js** v20 or higher
- **Git**

System dependencies (handled automatically by `install.sh`):
- ffmpeg
- imagemagick
- yarn / npm
---
## 📱 Termux (Android)
```
pkg update && pkg upgrade -y
```
```
pkg install git -y
```
```
pkg install nodejs
```
```
pkg install ffmpeg
```
```
pkg install imagemagick
```
```
git clone https://github.com/shopeebjm/botwa.git
```
```
cd botwa
```
```
npm install
```
```
bash install.sh
```
```
pkg install yarn
```
```
yarn
```
```
yarn install
```
```
yarn start
```

> Make sure `nodejs` and `yarn` are installed. The `install.sh` script already handles this.

---
## 💻 Laptop / Ubuntu / VPS / SSH
* Download And Install Git [`Click Here`](https://git-scm.com/downloads)
* Download And Install NodeJS [`Click Here`](https://nodejs.org/en/download)
* Download And Install FFmpeg [`Click Here`](https://ffmpeg.org/download.html) (**Don't Forget Add FFmpeg to PATH enviroment variables**)
* Download And Install ImageMagick [`Click Here`](https://imagemagick.org/script/download.php)

Use **npm**:

```bash
npm install
npm start
```
---
## ▶️ Running the Bot

```bash
npm start
# or
yarn start
```

Scan the QR Code or use Pairing Code, and the bot is ready to use.

---

## 🌐 API Integration

This bot is fully integrated with the **Naze API Service**:

🔗 https://naze.biz.id

Many features (such as downloader, AI tools, utilities, and media processing) rely on this external API.

### API Key Requirement

To use all features properly, you **must provide your own API key**.

The API key is configured in:

📁 **[settings.js](https://github.com/nazedev/hitori/blob/master/settings.js)**  

Example configuration:

```js
global.APIKeys = {
  'https://api.naze.biz.id': 'YOUR_API_KEY_HERE'
}
```

⚠️ If the API key is invalid or not set:
- Some commands will not work
- API-based features may return errors

Make sure you register and obtain a valid API key from the official website before using the bot.

---
## ⚙️ Bot Configuration

All main configurations are located in:

📁 **[settings.js](https://github.com/nazedev/hitori/blob/master/settings.js)**

### Editable Settings

#### Owner Number
```js
global.owner = ['628xxxxxxxxxx']
```

#### Bot Identity
```js
global.botname = 'Hitori Bot'
global.author = 'Nazedev'
```

#### Command Prefix
```js
global.listprefix = ['!', '.', '+']
```

#### User Limits & Balance
```js
global.limit.free = 20
global.money.free = 10000
```

#### Pairing Code / Bot Number
```js
global.pairing_code = true
global.number_bot = '628xxxxxxxxxx'
```

> Any change in [settings.js](https://github.com/nazedev/hitori/blob/master/settings.js) will be **auto-reloaded** without restarting the bot.

---

## 🧩 Editing & Adding Features

All bot features are implemented in:

📁 **[naze.js](https://github.com/nazedev/hitori/blob/master/naze.js)**

Look for the **[switch (command)](https://github.com/nazedev/hitori/blob/61052a01ea8e8975a99f0db7f5d40bad5ee39a5b/naze.js#L742)** section.

### Where to Add New Features

Add or edit commands inside the [switch (command)](https://github.com/nazedev/hitori/blob/61052a01ea8e8975a99f0db7f5d40bad5ee39a5b/naze.js#L742) block.

### Example: Adding a New Command

```js
case 'ping': {
  reply('pong 🏓')
}
break
```

Guidelines:
- Always add new commands using `case`
- Do not remove the main switch structure
- Place feature logic inside each `case`

---

## 🔌 Connector & Core Handler

To understand the WhatsApp connection flow and event handling, see:

📁 **[index.js](https://github.com/nazedev/hitori/blob/master/index.js)**
This file is responsible for:
- Initializing Baileys connection
- Handling WhatsApp events
- Loading [settings.js](https://github.com/nazedev/hitori/blob/master/settings.js)
- Dispatching messages to [naze.js](https://github.com/nazedev/hitori/blob/master/naze.js)

⚠️ **Editing [index.js](https://github.com/nazedev/hitori/blob/master/index.js) is not recommended unless you fully understand the bot flow.**

---
## 🗂 Structure Project
```
├── Dockerfile
├── LICENSE
├── Procfile
├── README.md
├── app.json
├── database
│   ├── jadibot
│   │   └── Naze
│   └── temp
│       └── A
├── docker-compose.yml
├── heroku.yml
├── index.js
├── install.sh
├── lib
│   ├── converter.js
│   ├── exif.js
│   ├── function.js
│   ├── game.js
│   ├── math.js
│   ├── template_menu.js
│   ├── tictactoe.js
│   └── uploader.js
├── naze.js
├── nodemon.json
├── package.json
├── railway.json
├── replit.nix
├── settings.js
├── speed.py
├── src
│   ├── antispam.js
│   ├── database.js
│   ├── jadibot.js
│   ├── media
│   │   ├── fake.pdf
│   │   └── naze.png
│   ├── message.js
│   └── server.js
└── start.js
```
---
#### Deploy to Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/nazedev/hitori)

#### Heroku Buildpack
| Build Pack | LINK |
|--------|--------|
| **NODEJS** | heroku/nodejs |
| **FFMPEG** | [here](https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest) |
| **IMAGEMAGICK** | [here](https://github.com/DuckyTeam/heroku-buildpack-imagemagick) |

---
### Features
| Menu     | Bot | Group | Search | Download | Tools | Ai | Game | Fun | Owner |
| -------- | --- | ----- | ------ | -------- | ----- | -- | ---- | --- | ----- |
| Work     |  ✅  |   ✅   |    ✅    |     ✅     |   ✅   | ✅ |   ✅   |  ✅  |    ✅    |


License: [MIT](https://choosealicense.com/licenses/mit/)

#### Support Me
- [Saweria](https://saweria.co/naze)

## Contributor

- [NazeDev](https://github.com/nazedev) (Pembuat)
- [Zaynn](https://github.com/ZaynRcK) (Penyedia Layanan API)
- [Dani](https://github.com/nazedev) (Penyumbang Code)

## Thanks to

| [![Nazedev](https://github.com/nazedev.png?size=100)](https://github.com/nazedev) | [![Zaynn](https://github.com/ZaynRcK.png?size=100)](https://github.com/ZaynRcK) | [![Dani](https://github.com/nazedev.png?size=100)](https://github.com/nazedev) | [![WhiskeySockets](https://github.com/WhiskeySockets.png?size=100)](https://github.com/WhiskeySockets) |
| --- | --- | --- | --- |
| [NazeDev](https://github.com/nazedev) | [Zaynn](https://github.com/ZaynRcK) | [Dani](https://github.com/dani) | [WhiskeySockets](https://github.com/WhiskeySockets) |

# Social Media

<h2 align="center">

[![shopee](https://img.shields.io/badge/shopee-200%2B-yellow.svg?style=flat)](https://shopee.co.id/infinixnote40bjm)

[![Youtube shopee_banjarmasin](https://img.shields.io/badge/YouTube-200%2B-yellow.svg?style=flat)](https://www.youtube.com/@shopee_banjarmasin)

[![Instagram shopee_banjarmasn](https://img.shields.io/badge/Instagram-2K%2B-yellow.svg?style=flat)](https://www.instagram.com/shopee_banjarmasin)

[![Twitter KipyMacho](https://img.shields.io/badge/Twitter-350%2B-yellow.svg?style=flat)](https://www.twitter.com/shopeebjm)
  
[![Tiktok Shopeebjm](https://img.shields.io/badge/TikTok-80%2B-yellow.svg?style=flat)](https://www.tiktok.com/@shopee.bjm)

[![Facebook shopee.bjm](https://img.shields.io/badge/Facebook-199%2B-yellow.svg?style=flat)](https://www.facebook.com/shopee.bjm)

[![Telegram](https://img.shields.io/badge/Telegram-77%2B-yellow.svg?style=flat)](http://t.me/shopeebjm)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-80%2B-yellow.svg?style=flat)](http://www.linkedin.com/in/kiplymacho)

</p>
<div height='45' align="center">
<h2>Contact me: <br>
<a href="https://github.com/shopeebjm"> <img src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg" height='50'> </a>
<a href="https://facebook.com/shopee.bjm"> <img src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/facebook.svg" height='50'> </a>
  
<a href="https://paypal.me/kiplymacho"> <img src="https://cdn.trakteer.id/images/embed/trbtn-red-6.png" height='50'> </a>
</h2>
</div>

# Follow Me :
‎‎[![Messenger](https://img.shields.io/badge/Messengers-blue?style=for-the-badge&logo=messenger)](https://fb.me/shopee.bjm)
‎<a href="https://tiktok.com/@shopee.bjm"><img title="TikTok" src="https://img.shields.io/badge/-black?style=for-the-badge&logo=Tiktok"></a>
‎<a href="https://linktr.ee/kiplymacho" target="_blank"><img src="https://img.shields.io/badge/Socials-grey?style=for-the-badge&logo=linktree"></a>
‎<a href="https://github.com/shopeebjm" target="_blank"><img src="https://img.shields.io/badge/Github-blue?style=for-the-badge&logo=github"></a>
‎</p>
‎‎[![Instagram](https://img.shields.io/badge/Instagram-Follow-red?style=for-the-badge&logo=instagram)](https://instagram.com/shopee_banjarmasin)
‎[![Blog](https://img.shields.io/badge/Website-Visit-yellow?style=for-the-badge&logo=blogger)](https://kiplymacho.blogspot.com)
‎[![Facebook](https://img.shields.io/badge/Facebook-Like-red?style=for-the-badge&logo=facebook)](https://facebook.com/shopee.bjm)
‎[![HalamanFacebook](https://img.shields.io/badge/Halaman-Facebook-sky?style=for-the-badge&logo=facebook)](https://facebook.com/httpcustomkiplymacho)
‎[![WhatsApp](https://img.shields.io/badge/WhatsApp-red?style=for-the-badge&logo=whatsapp)](https://wa.me/6285751032225)
‎[![Telegram](https://img.shields.io/badge/Forum-Diskusi-blue?style=for-the-badge&logo=forum)](https://t.me/shopeebjm)
‎<a href="https://youtube.com/@shopee_banjarmasin"><img title="YouTube" src="https://img.shields.io/badge/YouTube-@Shopee_Banjarmasin-red?style=for-the-badge&logo=Youtube"></a>
