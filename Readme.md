```markdown
# Telegram Member Scraper

A Python tool to scrape members from one Telegram channel/group and add them to another channel/group automatically.

## 📋 Prerequisites

- Python 3.7+
- Termux (Android) or any Linux environment
- Telegram account
- API credentials from Telegram

## 🔧 Installation

### Step 1: Install Termux
Download from [F-Droid](https://f-droid.org/en/packages/com.termux/)

### Step 2: Update System
```bash
pkg update && pkg upgrade
pkg install python git
```

Step 3: Clone Repository

```bash
git clone https://github.com/creatorshyamchand/telegram-member-scraper.git
cd telegram-member-scraper
```

Step 4: Install Requirements

```bash
pip install telethon
```

Step 5: Get API Credentials

1. Visit my.telegram.org
2. Create app and get:
   · API ID
   · API Hash

🚀 Usage

```bash
python scraper.py
```

⚠️ Disclaimer

Use responsibly. Respect Telegram's Terms of Service.

👥 Credits

Developer: CREATORSHYAMCHAND
Team: CreatorDev Team

```

## Additional Files to Create:

### requirements.txt
```txt
telethon==1.28.5
```

.gitignore

```gitignore
__pycache__/
*.session
*.session-journal
.env
config.py
```
