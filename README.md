# 🤖 MARCO MALIK MD

<div align="center">

```
███╗   ███╗ █████╗ ██████╗  ██████╗ ██████╗     
████╗ ████║██╔══██╗██╔══██╗██╔════╝██╔═══██╗    
██╔████╔██║███████║██████╔╝██║     ██║   ██║    
██║╚██╔╝██║██╔══██║██╔══██╗██║     ██║   ██║    
██║ ╚═╝ ██║██║  ██║██║  ██║╚██████╗╚██████╔╝    
╚═╝     ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝ ╚═════╝    
                                                  
███╗   ███╗ █████╗ ██╗     ██╗██╗  ██╗           
████╗ ████║██╔══██╗██║     ██║██║ ██╔╝           
██╔████╔██║███████║██║     ██║█████╔╝            
██║╚██╔╝██║██╔══██║██║     ██║██╔═██╗            
██║ ╚═╝ ██║██║  ██║███████╗██║██║  ██╗           
╚═╝     ╚═╝╚═╝  ╚═╝╚══════╝╚═╝╚═╝  ╚═╝          
```

**Advanced WhatsApp MD Bot with 300+ Commands**

![Node.js](https://img.shields.io/badge/Node.js-20+-green?style=flat-square&logo=node.js)
![Baileys](https://img.shields.io/badge/Baileys-6.7.9-blue?style=flat-square)
![Commands](https://img.shields.io/badge/Commands-300+-orange?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)

</div>

---

## ✨ Features

| Category | Count | Description |
|----------|-------|-------------|
| 👑 Owner Commands | 20+ | Full bot control |
| 👥 Group Management | 25+ | Complete group tools |
| 🤖 AI Commands | 15+ | Gemini, GPT, Llama, Claude |
| 🎨 Image Generator | 10+ | AI-powered image generation |
| 📥 Downloader | 10+ | YouTube, TikTok, Facebook, Instagram |
| 🎭 Entertainment | 25+ | Love, sad, kill, hang, etc. |
| 💑 Couple Commands | 15+ | Love meter, couples, proposals |
| 😂 Fun Commands | 20+ | Jokes, riddles, games |
| 🎨 Sticker Commands | 14+ | Create & manipulate stickers |
| 🔧 Utility Commands | 20+ | QR, screenshot, weather, etc. |
| 📊 Admin/Rank | 10+ | XP, coins, leaderboard |
| 🎌 Reactions | 15+ | Anime-style reactions |
| 🔤 Extra | 15+ | Wiki, morse, binary, etc. |

**Total: 300+ Commands!**

---

## 🚀 Quick Setup

### Prerequisites
- Node.js 18 or higher
- A WhatsApp account for the bot

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/your-username/marco-malik-md
cd marco-malik-md

# 2. Install dependencies
npm install

# 3. Configure the bot
cp .env.example .env
# Edit .env with your settings

# 4. Start the bot
npm start
```

### Scanning QR Code
1. Run `npm start`
2. A QR code will appear in the terminal
3. Open WhatsApp → Linked Devices → Link a Device
4. Scan the QR code
5. Bot is now connected! ✅

---

## ⚙️ Configuration

Edit the `.env` file:

```env
# Required
BOT_NAME=MARCO MALIK MD
PREFIX=.
OWNER_NUMBER=923001234567    # Your number without + or spaces
OWNER_NAME=Marco Malik

# AI Features (Optional but recommended)
GEMINI_API_KEY=your-key     # Free at aistudio.google.com
OPENAI_API_KEY=your-key     # Optional
TOGETHER_API_KEY=your-key   # Optional (for Llama/Claude)

# Auto Features
AUTO_READ=true
AUTO_STATUS_VIEW=true
AUTO_STATUS_REPLY=true
STATUS_REPLY_MESSAGE=Seen Your Status 👀 By Marco Malik

# Auto React
AUTO_REACT=true
AUTO_REACT_MODE=random      # random or fixed
FIXED_REACT_EMOJI=🔥

# Bot Mode
MODE=public                  # public or private
```

---

## 🌐 Deployment

### Railway (Recommended - Free)
[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template)

1. Push code to GitHub
2. Go to railway.app → New Project → Deploy from GitHub
3. Set environment variables from `.env`
4. Railway will auto-detect Node.js and deploy!

### Heroku
```bash
heroku create marco-malik-md
heroku config:set OWNER_NUMBER=923001234567
heroku config:set GEMINI_API_KEY=your-key
git push heroku main
```

### Render
1. Connect GitHub repo to Render
2. Build command: `npm install`
3. Start command: `node index.js`
4. Add environment variables

### VPS / Local Server
```bash
# Install PM2 for persistent running
npm install -g pm2
pm2 start index.js --name "marco-malik-md"
pm2 save
pm2 startup
```

---

## 📋 Command Reference

### 👑 Owner Commands
```
.menu owner          - Owner command list
.setprefix [char]    - Change prefix
.setname [name]      - Change bot name
.broadcast [msg]     - Broadcast to all groups
.ban @user           - Ban user from bot
.unban @user         - Unban user
.block @user         - Block on WhatsApp
.addsudo @user       - Add sudo user
.restart             - Restart bot
.eval [code]         - Run JavaScript
.exec [command]      - Run shell command
```

### 👥 Group Commands
```
.menu group          - Group command list
.kick @user          - Remove member
.add [number]        - Add member
.promote @user       - Make admin
.demote @admin       - Remove admin
.mute / .unmute      - Toggle group mute
.antilink            - Toggle anti-link
.tagall [msg]        - Tag all members
.warn @user          - Warn a member (3 = auto-kick)
.link                - Get invite link
.poll Q|Opt1|Opt2    - Create poll
```

### 🤖 AI Commands
```
.ai [question]       - AI chat (Gemini)
.gpt [prompt]        - GPT chat
.gemini [prompt]     - Gemini Pro
.llama [prompt]      - Llama 3
.imagine [prompt]    - Generate AI image
.devil [name]        - Devil-style image
.marco [name]        - Marco-style image
.waqar [name]        - Waqar-style image
.zahir [name]        - Zahir-style image
.saeed [name]        - Saeed-style image
.translate [lang] [text] - Translate text
.tts [text]          - Text to speech
```

### 📥 Downloader Commands
```
.play [song name]    - Download YouTube song
.ytmp4 [name/url]    - Download YouTube video
.tiktok [url]        - Download TikTok (no watermark)
.fb [url]            - Facebook video
.ig [url]            - Instagram reel/video
.movie [name]        - Search HD movies
```

### 🎭 Entertainment
```
.love @user1 @user2  - Love meter
.sad                 - Sad message
.achi                - Achi feeling
.hang @user          - Hang message
.kill @user          - Kill message (fun)
.gm / .gn            - Good morning/night
.gift @user          - Send virtual gift
.birthday @user      - Birthday wish
.motivate            - Motivational message
```

### 💑 Couple Commands
```
.couple @user1 @user2 - Couple card
.love @user          - Love percentage
.propose @user       - Send proposal
.kiss @user          - Send kiss
.hug @user           - Send hug
.marry @user         - Marriage proposal
.date                - Date ideas
.compatibility @u1 @u2 - Compatibility check
```

### 😂 Fun Commands
```
.dare / .truth       - Dare & Truth
.joke                - Random joke
.8ball [question]    - Magic 8 ball
.rps [rock/paper/scissors] - Rock Paper Scissors
.riddle              - Get a riddle
.quote               - Random quote
.fact                - Fun fact
.hack [target]       - Fake hack animation
.wyr                 - Would you rather?
```

### 🎨 Sticker Commands
```
.sticker / .s        - Image/GIF to sticker
.toimg               - Sticker to image
.ttp [text]          - Text to sticker
.attp [text]         - Animated text sticker
.circle              - Circle-shape sticker
.blur [level]        - Blur sticker
.memetext [text]     - Meme text on sticker
```

### 🔧 Utility Commands
```
.img2url             - Image to URL (reply to image)
.ss [url]            - Screenshot website
.qr [text]           - Generate QR code
.shorturl [url]      - Shorten URL
.weather [city]      - Weather info
.calc [expression]   - Calculator
.base64enc [text]    - Encode to Base64
.ip [address]        - IP lookup
.currency 100 USD PKR - Currency convert
.font [text]         - Fancy fonts
.wiki [topic]        - Wikipedia search
.define [word]       - Dictionary
```

---

## 🛡️ Auto Features

| Feature | Description |
|---------|-------------|
| **Auto Read** | Automatically reads all messages |
| **Auto Status View** | Views all statuses automatically |
| **Auto Status Reply** | Replies "Seen Your Status 👀 By Marco Malik" |
| **Auto React** | Reacts with random or fixed emoji |
| **Anti-Link** | Deletes links in groups (per group setting) |
| **Auto Welcome** | Welcomes new group members |
| **Auto Goodbye** | Says bye when member leaves |

---

## 📁 Project Structure

```
marco-malik-md/
├── index.js                 # Main bot entry point
├── config.js                # Configuration
├── .env                     # Environment variables
├── package.json
├── Procfile                 # Heroku deployment
├── railway.json             # Railway deployment
├── render.yaml              # Render deployment
├── Dockerfile               # Docker deployment
├── app.json                 # Heroku app config
├── commands/
│   ├── owner/owner.js       # Owner commands
│   ├── group/group.js       # Group management
│   ├── admin/admin.js       # Admin & rank system
│   ├── ai/ai.js             # AI & image gen
│   ├── entertainment/       # Entertainment cmds
│   ├── couple/couple.js     # Couple commands
│   ├── fun/fun.js           # Fun & games
│   ├── downloader/          # Download commands
│   ├── sticker/sticker.js   # Sticker commands
│   ├── utility/utility.js   # Utility commands
│   └── extra/               # Extra commands
├── lib/
│   ├── handler.js           # Message handler
│   ├── database.js          # JSON database
│   ├── functions.js         # Helper functions
│   └── menu.js              # Menu generator
├── session/                 # WhatsApp session (auto-created)
├── database/                # Bot database (auto-created)
└── assets/                  # Media assets
```

---

## 🔑 Getting Free API Keys

### Google Gemini (Recommended - Free)
1. Go to [aistudio.google.com](https://aistudio.google.com)
2. Sign in with Google account
3. Get API Key → Copy
4. Add to `.env`: `GEMINI_API_KEY=your-key`

### OpenAI (Paid)
1. Go to [platform.openai.com](https://platform.openai.com)
2. Create account → API Keys
3. Add to `.env`: `OPENAI_API_KEY=your-key`

### Together.ai (Free tier available)
1. Go to [together.ai](https://together.ai)
2. Sign up → API Keys
3. Add to `.env`: `TOGETHER_API_KEY=your-key`

---

## 🤝 Credits

- **Developer**: Marco Malik
- **Library**: [@whiskeysockets/baileys](https://github.com/WhiskeySockets/Baileys)
- **AI**: Google Gemini, OpenAI, Together.ai
- **Images**: Pollinations.ai

---

## ⚠️ Disclaimer

This bot is for educational purposes. Use responsibly and follow WhatsApp's Terms of Service. The developer is not responsible for misuse.

---

<div align="center">
Made with ❤️ by Marco Malik
</div>
