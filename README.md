<!--
#️⃣ Tags:
AIS spoofing simulator, vessel identity manipulator, oil tanker stealth, ship ghost tool, AIS NMEA spoofer, cargo ship cloaking, SDR spoof simulator, maritime cyber ops, AIS red teaming, ghost fleet generator, RedRepo, stealth vessel sim, dark sea tools, spoofed location marine, illegal AIS activity analysis

📚 Keywords:
AIS vessel spoof tool, fake ship AIS signal, oil tanker hiding tool, ship tracking deception simulator, ghost fleet simulator GitHub, maritime threat simulator, AIS SDR fake packets, RedRepo AIS project, AIS security tool, spoof marine tracker, stealth ship creator, AIS location override API
-->

##AIS Vessel Spoofing Simulator — Oil Tanker Stealth Ops

> ⚠️ This project is for **educational and research** purposes **only**. No real AIS transmissions are sent.  
> Contact via Telegram: [@RedRepo](https://t.me/RedRepo)

---

## Overview

This simulator mimics **AIS spoofing techniques** used in stealth maritime operations by oil tankers, cargo ships, and naval vessels.  
It demonstrates how AIS data can be simulated, manipulated, and visualized for cybersecurity awareness and training.

AIS spoofing GitHub, vessel spoof tool, oil tanker stealth, ship tracking simulator, maritime cybersecurity, AIS simulator, ghost vessel generator, cargo ship AIS fake, automatic identification system override

<blockquote style="border-left: 4px solid #A855F7; padding: 1em; background: #2c2c2c; color: #e0d4ff;">
  <strong>📌 Important</strong><br>
  Since the GitHub API only <a href="https://docs.github.com/en/rest/overview/resources-in-the-rest-api#rate-limiting">allows 5k requests per hour</a>,<br>
  the Vercel instance might hit the rate limit. Use your own instance to avoid this.<br>
  ➕ <a href="https://github.com/anuraghazra/github-readme-stats#deploy-on-your-own-vercel-instance">Deploy your own</a>
</blockquote>

---

## 🧰 Features

- 📍 Fake vessel location generation
- 🛢️ Oil tanker AIS identity cloning
- ⚓ Ghost ship spawning (custom name, IMO, coordinates)
- 🛰️ AIS NMEA sentence formatter
- 📡 Broadcast simulator via SDR (disabled in public version)
- 🧾 Event logger (spoof vs real)
- 📊 Dashboard-ready data JSON endpoints

```bash
# Clone this AIS spoofing simulator project
git clone https://github.com/youruser/AIS-Vessel-Spoofing-Simulator-OilTanker-StealthOps.git
cd AIS-Vessel-Spoofing-Simulator-OilTanker-StealthOps

# Install dependencies
pip install -r requirements.txt

# Run simulator (base mode)
python3 simulator.py

# Simulate spoofed AIS packet (PREVIEW ONLY)
from ais_spoofer.generator import generate_ais_message

spoofed_msg = generate_ais_message(
    name="SEA GHOST", 
    imo="9329999", 
    lat=24.12345, 
    lon=54.98765, 
    speed=13.7, 
    course=278.5, 
    ship_type="Oil Tanker"
)

print(spoofed_msg)

# OUTPUT:
# !AIVDM,1,1,,A,55NB8G02>?1D@<1B8UQ@9U700000,0*5F

# 🔒 FULL spoofing engine & radio integration is PRIVATE

# To access the full codebase including:
# - Real-time spoof message engine
# - AIS SDR transmission module
# - Dashboard with ghost ship fleet visualizer

📩 Contact on Telegram: [@RedRepo](https://t.me/RedRepo)
