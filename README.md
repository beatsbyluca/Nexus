# 🔷 NEXUS

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.1-blue.svg)
![Python](https://img.shields.io/badge/python-3.9+-green.svg)
![License](https://img.shields.io/badge/license-MIT-orange.svg)

**Automatic Discord Bot for Server Management**

[Installation](#-installation) • [Features](#-features) • [Usage](#-usage) • [Configuration](#-configuration)

</div>

---

## 📸 Preview

```
                            _   __                    V1.0.1
                           / | / /__  _  ____  _______
                          /  |/ / _ \| |/_/ / / / ___/
                         / /|  /  __/>  </ /_/ (__  ) 
                        /_/ |_/\___/_/|_|\__,_/____/  
                                                      
                                            Beatsbyluca
```

*Beautiful blue gradient terminal interface*

---

## 🚀 Installation

### Prerequisites
- Python 3.9+
- Discord Bot Token
- Bot with Administrator permissions

### Quick Start

```bash
# Clone the repository
git clone https://github.com/beatsbyluca/Nexus
cd Nexus

# Install dependencies
pip install -r requirements.txt

# Run the bot
python main.py
```

### Dependencies
```
discord.py
pystyle
requests
```

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🎯 **Nuke** | Delete all channels and roles |
| 📝 **Create Channels** | Mass create text/voice channels |
| 💬 **Spam Channels** | Send messages to all channels |
| 🔗 **Webhook Spam** | Create webhooks and spam |
| 👢 **Kick All** | Kick all members |
| 🚫 **Ban All** | Ban all members |
| 🎭 **Create Roles** | Mass create roles |
| 👑 **Get Admin** | Grant admin permissions |
| ⚙️ **Change Server** | Modify server settings |
| 📨 **DM All** | Send DMs to all members |
| 🤖 **Auto Raid** | Automated raid sequence |

---

## 📖 Usage

1. **Start the bot:**
   ```bash
   python main.py
   ```

2. **Enter credentials:**
   - Bot Token (when prompted)
   - Server ID (when prompted)

3. **Select command from menu:**
   ```
   ╔═══════════════════════════════╦═══════════════════════════════╦═══════════════════════════════╗
   ║           1 - Nuke            ║       2 - Create Channels     ║      3 - Spam Channels        ║
   ╠═══════════════════════════════╬═══════════════════════════════╬═══════════════════════════════╣
   ║        4 - Webhook Spam       ║         5 - Kick All          ║          6 - Ban All          ║
   ╠═══════════════════════════════╬═══════════════════════════════╬═══════════════════════════════╣
   ║        7 - Create Roles       ║         8 - Get Admin         ║       9 - Change Server       ║
   ╚═══════════════╦═══════════════╩═══════════════╦═══════════════╩═══════════════╦═══════════════╝
                   ║        10 - DM All            ║         11 - Auto Raid        ║    
                   ╚═══════════════════════════════╩═══════════════════════════════╝
   ```

---

## ⚙️ Configuration

Edit `config.py` to customize:

### Auto Raid Config
```python
AUTO_RAID_CONFIG = {
    'num_channels': 100,
    'channel_type': 'text',
    'channel_name': 'your-channel-name',
    'num_messages': 500,
    'message_content': 'Your message'
}
```

### Embed Config
```python
EMBED_CONFIG = {
    "title": "Your Title",
    "description": "Your Description",
    "color": 0x5117ff,
    "image": "https://your-image-url.com/image.png",
    "footer": "Footer Text"
}
```

### Server Config
```python
SERVER_CONFIG = {
    "new_name": "New Server Name",
    "new_icon": "https://your-icon-url.com/icon.png",
    "new_description": "Server Description"
}
```

### Whitelist
```python
NO_BAN_KICK_ID = {
    123456789012345678,  # User IDs to exclude
}
```

---

## 🛡️ Bot Permissions

The bot requires:
- ✅ Administrator (recommended)
- Or individual permissions:
  - Manage Channels
  - Manage Roles
  - Manage Server
  - Ban Members
  - Kick Members
  - Send Messages
  - Manage Webhooks

---

## ⚠️ Disclaimer

**This tool is for educational purposes only.**

- ⚠️ Do not use on servers without permission
- ⚠️ May violate Discord's Terms of Service
- ⚠️ Misuse can result in account termination
- ⚠️ Use at your own risk

---

## 📄 License

This project is licensed under the MIT License.

---

## 👤 Credits

**Developer:** [Beatsbyluca](https://github.com/beatsbyluca)  
**Version:** 1.0.1

---

<div align="center">

**⭐ Star this repo if you find it useful!**

[🔗 Repository](https://github.com/beatsbyluca/Nexus)

</div>
