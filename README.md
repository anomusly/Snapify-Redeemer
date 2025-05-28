# ⚡ SNAPIFY-REDEEMER v1

<p align="center">
  <img src="https://img.shields.io/badge/Status-FREE%20TOOL-green?style=for-the-badge" alt="status" />
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-blue?style=for-the-badge" alt="platform" />
  <img src="https://img.shields.io/badge/Language-Python-yellow?style=for-the-badge" alt="language" />
</p>

<p align="center">
  <b>🔥 Automated Discord Nitro Claimer using Snapify Campaign Promotions</b><br>
  🎉 Made with ❤️ by <a href="https://github.com/anomusly">@AnomusLY</a> | Discord: <a href="https://discord.com/users/1136625769628581928">@Anomus.ly</a>
</p>

---

## ✨ Features

- 🤖 **Auto-login** using valid Discord tokens  
- 🎁 **Redeems Nitro** via Snapify promotional links  
- 💳 **Supports VCC input** for automated Nitro claiming  
- 📂 **Batch mode** for multiple tokens and VCCs  
- 🔧 **Configurable** through simple `config.json`  
- 🌐 **Optional proxy support** to avoid rate limiting  
- 📊 **CLI-based status updates** during claim process  
- 📜 **Organized logging** with output files for each session  

---

## 🗂️ Folder Structure

```

Snapify-Redeemer/
│
├── input/
│   ├── tokens.txt         # List of Discord tokens
│   ├── vccs.txt           # List of VCCs (CARD|MM|YY|CVV)
│   └── proxies.txt        # Optional HTTP/HTTPS proxies
│
├── config.json            # Tool configuration
├── main.py                # Main script
├── keyauth.py             # License system
└── README.md              # This file

````

---

## 💾 Installation

```bash
git clone https://github.com/anomusly/Snapify-Redeemer.git
cd Snapify-Redeemer
pip install -r requirements.txt
````

---

## ⚙️ Configuration

Edit the `config.json` file:

```json
{
  "redeem_url": "https://discord.com/billing/partner-promotions/snap",
  "threads": 5,
  "use_proxies": true,
  "logging": true
}
```

---

## 🚀 Usage

### 🔧 Step-by-step

1. **Prepare inputs**:

   * `input/tokens.txt`: one Discord token per line
   * `input/vccs.txt`: format `CARD|MM|YY|CVV`
   * `input/proxies.txt`: (optional) one proxy per line

2. **Run the tool**:

   ```bash
   python main.py
   ```

3. **Watch real-time output** as tokens attempt to redeem Nitro

4. **Check logs/output files** for successful redemptions

---

## 🛑 Important Notes

* ⚠️ Use **alt accounts only** — main accounts risk being banned
* 🔁 Rotate proxies and tokens to prevent rate limiting
* 🔐 Keep your tokens and VCCs private
* 💥 Misuse of this tool violates Discord’s Terms of Service

---

## 🧾 Example Claim Flow

1. 🔓 Log into Discord with token
2. 🔗 Access Snapify promotion URL
3. 💳 Enter VCC details
4. 🎉 Redeem Discord Nitro
5. ✅ Log success or failure to output file

---

## 💬 Support & Contact

* Discord: `anomus.ly`
* GitHub: [AnomusLY](https://github.com/anomusly)
* Custom Tools: DM for commissions

---

<p align="center">
  <b>⭐ If this tool helped you, drop a star! ⭐</b>
</p>

---

## ⚖️ Disclaimer

> This repository is for **educational purposes only**.
> The developer is **not responsible** for any misuse, abuse, or violations.
> You are solely responsible for complying with **Discord’s Terms of Service** and all applicable laws.

```
