# [![Static Badge](https://img.shields.io/badge/Telegram-Bot%20Link-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/Vanilla_Finance_Bot/Vanillafinance?startapp=inviteId10332005) || [![Static Badge](https://img.shields.io/badge/Telegram-Channel%20Link-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/Lootersera_th)

## **Vanilla Finance Bot**

![Vanilla Finance Bot](https://github.com/Ashuxd-X/Vanilla-finance/blob/main/Vanilla%20Bot.png?raw=true)

# **Devloped and Managed By** 

@khondokerXhasan and @Ashuxd-X


> **Recommendation**: Use **Python 3.10**

---

# Features
| Feature                           | Supported |
|-----------------------------------|:---------:|
| Multithreading                    |     ✅     |
| Proxy Support    |     ✅     |
| User-Agent binding to session     |     ✅     |
| Support for `pyrogram session` files      |     ✅     |
| Auto registration in bot          |     ✅     |
| Auto-tasks                        |     ✅     |
| Daily rewards                     |     ✅     |
| Auto tap                |     ✅     |
| Auto upgrade level                |     ✅     |
| Advanced anti-detection           |     ✅     |

---

## [Settings](https://github.com/Ashuxd-X/Vanilla-finance-BOT/blob/master/.env-example/)
| Setting                  | Description                                                                                               | Default Value           |
|--------------------------|-----------------------------------------------------------------------------------------------------------|-------------------------|
| **API_ID / API_HASH**    | Platform data from which to run the Telegram session.                                                     | Required for operation  |
| **USE_RANDOM_DELAY_IN_RUN** | Enables random delays during task execution to avoid detection.                                           | `True`                 |
| **START_DELAY**          | Delay (in seconds) between session starts.                                                               | `[30, 60]`             |
| **AUTO_TAP**             | Enable or disable automatic tap.                                                                         | `True`                 |
| **TAP_COUNT**            | Range for the number of taps.                                                                            | `[80, 100]`            |
| **UPGRADE_LEVEL_WITH_SUGAR** | Enable or disable upgrading level with sugar.                                                        | `False`                |
| **AUTO_TASK**            | Enable or disable automatic task execution.                                                              | `True`                 |
| **REF_ID**               | Referral ID.                                                                                             | `''`    |
| **SAVE_JS_FILES**        | Save JavaScript files (experimental).                                                                    | `False`                |
| **ADVANCED_ANTI_DETECTION** | Enable advanced anti-detection measures.                                                              | `True`                 |
| **ENABLE_SSL**           | Enable or disable SSL.                                                                                   | `True`                 |
| **USE_PROXY_FROM_FILE**  | Use proxy from file.                                                                                     | `False`                |
| **CHECK_FOR_UPDATE=**   | Check For New Updates.                                                                               | `True`                 |
---
## Quick Start 📚

To install dependencies and run the bot quickly, use the provided batch file (`run.bat`) for Windows or the shell script (`run.sh`) for Linux.

### Prerequisites
Ensure you have **Python 3.10 or Greater** installed.

### Obtaining API Keys
1. Go to [my.telegram.org](https://my.telegram.org) and log in.
2. Under **API development tools**, create a new application to get your `API_ID` and `API_HASH`, and add these to your `.env` file.

---

<div style="background-color: #FFFACD; padding: 15px; border: 1px solid #F5E79E; border-radius: 5px;">

# Important Warning ⚠️

### Telegram Account Login Using Pyrogram

**Notice:**  
Recently, Telegram has implemented stricter measures regarding account sessions. When you log in to your Telegram account using **Pyrogram**, your existing sessions may be **logged out automatically**. This has become a common issue with recent updates.  

### Solution  
To avoid this, we recommend the following workaround:

1. **Create a Session Using Telethon:**  
   Use the [Telethon](https://github.com/LonamiWebs/Telethon) library to generate a session file.

2. **Convert the Session to Pyrogram Format:**  
   Once the session is created, convert it to be compatible with Pyrogram using session conversion tools.

3. **Use the Converted Session in Your Script:**  
   Load the converted session in your Pyrogram-based script to avoid being logged out.

---

This workaround ensures that your Telegram sessions remain intact while using Pyrogram. If you face any issues, feel free to contact the repository maintainers for further assistance.

</div>

## Installation

### Clone the Repository
```shell
git clone https://github.com/Ashuxd-X/Vanilla-finance
cd Vanilla-finance
```

Then you can do automatic installation by typing:

Windows:
```shell
run.bat
```

Linux:
```shell
run.sh
```

# Linux manual installation
```shell
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
cp .env-example .env
nano .env  # Here you must specify your API_ID and API_HASH, the rest is taken by default
python3 main.py
```

You can also use arguments for quick start, for example:
```shell
~/Vanilla-finance >>> python3 main.py --action (1/2)
# Or
~/Vanilla-finance >>> python3 main.py -a (1/2)

# 1 - Run clicker
# 2 - Creates a session
```

# Windows manual installation
```shell
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
copy .env-example .env
# Here you must specify your API_ID and API_HASH, the rest is taken by default
python main.py
```

You can also use arguments for quick start, for example:
```shell
~/Vanilla-finance >>> python main.py --action (1/2)
# Or
~/Vanilla-finance >>> python main.py -a (1/2)

# 1 - Run clicker
# 2 - Creates a session
```

## Usage
1. **First Launch**: Create a session with the `--action 2` option. This will create a `sessions` folder for storing all accounts and an `accounts.json` configuration file.
2. **Existing Sessions**: If you already have sessions, add them to the `sessions` folder and run the bot with the clicker mode.

### Example of `accounts.json`
```json
[
  {
    "session_name": "name_example",
    "user_agent": "Mozilla/5.0 (Linux; Android 14) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/125.0.6422.165 Mobile Safari/537.36",
    "proxy": "type://user:pass:ip:port"  // "proxy": "" if no proxy
  }
]
```

### Contacts

[Join our Telegram Channel](https://t.me/Lootersera_Th)
