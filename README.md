# ⚡ Kade's Street Cred (The Neynar Spice Engine)

**Because your corporate reputation score is boring and you know it.**

`Kade's Street Cred` is a Farcaster-native reputation engine built to separate the "Power Users" from the actual legends. While Neynar tells you if a user is a bot, this engine tells you if they have any actual flavor.

## 🛠️ How it Works
This project pulls data from the **Neynar API**, analyzes user bios and activity for specific "High-Value" markers (Cybersecurity, Hacking, Apothecary, and $DEGEN culture), and generates a dynamic badge using Python's Pillow library.

### The Scoring Logic (The "Spice")
- **Neynar Base:** We start with their confidence score.
- **Cyber Multiplier:** +25 points for any mention of SIGIL, security, or hacking.
- **Apothecary Bonus:** +25 points for the healers and the herb-wise.
- **Degen Weight:** Followers and on-chain activity scale the final output.

## 🚀 Getting Started

### 1. Prerequisites
You’ll need a **Neynar API Key**. Get one [here](https://neynar.com/).

### 2. Installation
```bash
git clone [https://github.com/YOUR_USERNAME/kade-street-cred.git](https://github.com/YOUR_USERNAME/kade-street-cred.git)
cd kade-street-cred
pip install -r requirements.txt
