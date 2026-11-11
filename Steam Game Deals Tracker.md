# 🏷️ Steam Sale Price Tracker

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=17,0,25&height=210&section=header&text=Steam%20Sale%20Price%20Tracker&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Never%20Miss%20a%20Deal%20Again&descAlignY=56&descSize=19" width="100%"/>

<br/>

[![Version](https://img.shields.io/badge/version-3.6.0-FF6B00?style=for-the-badge&logo=semanticrelease&logoColor=white)](https://github.com)
[![Stack](https://img.shields.io/badge/React%20%7C%20Node%20%7C%20SQLite-FF8C42?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://github.com)
[![License](https://img.shields.io/badge/license-MIT-FFA552?style=for-the-badge&logo=opensourceinitiative&logoColor=black)](LICENSE)
[![Alerts](https://img.shields.io/badge/alerts-email%20%7C%20telegram-FFC15E?style=for-the-badge&logo=telegram&logoColor=black)](https://github.com)

<br/>

### 🔔 Track prices, spot historic lows & get alerts the moment a deal drops

*📉 Price History • 🎯 Custom Thresholds • 📧 Email & Telegram • 🎮 Wishlist Sync*

<br/>

<a href="https://share.google/egEEMxBx4aEe2Gt2K">
  <img src="https://img.shields.io/badge/🚀_OPEN_TRACKER-FF6B00?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=CC5600" alt="Open Tracker" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/egEEMxBx4aEe2Gt2K">
  <img src="https://img.shields.io/badge/📥_GET_SOURCE-FF8C42?style=for-the-badge&logo=github&logoColor=white&labelColor=CC7035" alt="Get Source" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/egEEMxBx4aEe2Gt2K">
  <img src="https://img.shields.io/badge/📚_DOCS-FFC15E?style=for-the-badge&logo=readthedocs&logoColor=black&labelColor=CC9A4B" alt="Docs" height="45"/>
</a>

</div>


<img width="1920" height="1080" alt="Sales-Tracker-Steam-VR-Games-and-Apps-True-North-VR" src="https://github.com/user-attachments/assets/de3e1529-5ead-4709-967c-e5b1e5c7d058" />

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**Steam Sale Price Tracker** is a **self-hosted price monitoring tool** for your Steam library and wishlist. It watches game prices across every Steam sale, records full price history, and **notifies you instantly** when a game hits your target price or a historic low.

No more manually checking the store during every seasonal sale — set your thresholds once and let the tracker do the work.

> 💡 **Perfect for:** Patient gamers, wishlist hoarders, deal hunters, and anyone who's ever said "I'll wait for the next sale."

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Key Features

<div align="center">

| 📉 **Price History** | 🎯 **Custom Targets** | 📧 **Instant Alerts** |
|:---:|:---:|:---:|
| Full charts of every<br/>price change | Set your own<br/>target price per game | Email + Telegram<br/>notifications |

| 🎮 **Wishlist Sync** | 🏆 **Historic Lows** | 📊 **Deal Insights** |
|:---:|:---:|:---:|
| Auto-import from<br/>your Steam wishlist | Detect all-time<br/>low prices | Discount %, savings<br/>& forecast trends |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why This Tracker

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| 🔔 **Never Miss a Deal** | Alerts fire within minutes of a price drop going live |
| 📉 **Complete History** | Every recorded price on a clean, interactive chart |
| 🎯 **Precise Targets** | Track games at custom prices — not just percentages off |
| 🎮 **Steam Integration** | Import your wishlist and library with one click |
| 🛡️ **Private & Self-Hosted** | Runs on your own hardware — no account, no cloud, no ads |
| 📊 **Smart Insights** | See how low a game usually goes before you buy |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 Tracker Preview

<div align="center">

```ascii
╔══════════════════════════════════════════════════╗
║  🏷️  Steam Sale Price Tracker  v3.6.0            ║
╠══════════════════════════════════════════════════╣
║  📚 Tracked games: 42   🎯 Below target: 5       ║
║  ──────────────────────────────────────────      ║
║  🎮 Game                 Now      Target   Low   ║
║  ──────────────────────────────────────────      ║
║  🟢 Hollow Knight      $2.99     $5.00  $2.99   ║
║  🟢 Hades              $9.99    $10.00  $9.99   ║
║  🟡 Elden Ring        $29.99    $25.00 $29.99   ║
║  🟡 Cyberpunk 2077    $19.99    $15.00 $19.99   ║
║  🔴 Factorio          $35.00    $20.00 $30.00   ║
║                                                  ║
║  📉 Price drop detected!                         ║
║  🎉 Hollow Knight is now $2.99 (historic low)   ║
║  📧 Alert sent via email + Telegram             ║
║                                                  ║
║  [ 📊 History ]  [ ⚙️ Targets ]  [ 🔔 Alerts ]   ║
╚══════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
🏷️ steam-sale-price-tracker/
├── 🎯 src/
│   ├── scraper/               # Steam price fetching
│   │   ├── store-api.ts
│   │   └── history.ts
│   ├── watcher/               # Scheduled price checks
│   ├── alerts/                # Email & Telegram
│   │   ├── email.ts
│   │   └── telegram.ts
│   ├── dashboard/             # React UI & charts
│   └── db/                    # SQLite / price history
├── 🧪 tests/                  # Unit & integration
└── 📖 docs/                   # Setup & API reference
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Found a game whose price isn't updating? Want a new alert channel (Discord, Pushover)?

<div align="center">

<a href="https://share.google/egEEMxBx4aEe2Gt2K">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/egEEMxBx4aEe2Gt2K">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-FF6B00?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/egEEMxBx4aEe2Gt2K">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-FFC15E?style=for-the-badge&logo=github&logoColor=black" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.


<br/>

<div align="center">

### 🏷️ Made with 🔔 by the Steam Tracker Team

*If this tracker saved you money — star the repo!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=17,0,25&height=120&section=footer" width="100%"/>

</div>
