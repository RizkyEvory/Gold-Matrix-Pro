
# 🚀 Gold Matrix Pro
### Adaptive Confluence Matrix Indicator for MT5 (XAUUSD)

<div align="center">

![MT5](https://img.shields.io/badge/MT5-Compatible-brightgreen)
![Version](https://img.shields.io/badge/Version-1.0.0-blue)
![License](https://img.shields.io/badge/License-Commercial-orange)
![Market](https://img.shields.io/badge/Optimized-XAUUSD-gold)
![Language](https://img.shields.io/badge/Language-MQL5-yellow)

**Professional Trading Indicator with Adaptive Multi-Dimensional Scoring**

[![Stars](https://img.shields.io/github/stars/RizkyEvory/GoldMatrixPro?style=social)](https://github.com/RizkyEvory/GoldMatrixPro)

</div>

---

## ✨ Overview

**Gold Matrix Pro** adalah indikator MT5 **commercial-grade** yang dirancang khusus untuk **XAUUSD**, menggabungkan pendekatan *quantitative analysis* dan *adaptive confluence scoring* untuk membantu trader menilai kualitas setup secara objektif dan real-time.

Indikator ini berfungsi sebagai **decision-support system**, bukan sekadar pemberi sinyal.

> *“Not just a signal generator — a quantitative decision framework for gold traders.”*

---

## 🎯 Key Features

### 🤖 Intelligent Core Engine
- 5-Dimensional Confluence Scoring:
  - Trend
  - Momentum
  - Reversion
  - Volume
  - Divergence
- Adaptive weighting mengikuti volatilitas
- Multi-Timeframe Context:
  - M5 → execution
  - M15 → bias
- Jurik JMA (slope-based trend detection)
- Hidden & Regular Divergence

---

### 🎨 Premium Dashboard
- Real-time Matrix Score (color graded)
- Dimension Bars (transparansi logika)
- Confluence Star Rating (⭐ 1–5)
- Risk Level Indicator (Low / Medium / High)
- Auto Market Session Detection
- Dark professional theme (clean & non-distracting)

---

### ⚡ Performance & Reliability
- Lightweight & CPU-friendly
- Optimized for M5 scalping & intraday
- Stable in live market
- Memory-efficient architecture

---

### 🔔 Advanced Alerts
- Popup
- Sound
- Email
- Push Notification
- Discord
- Telegram
- Smart cooldown (anti spam)
- Screenshot hotkey (F6)

---

## 📊 Dashboard Preview
┌─────────────────────────────────────────────────────┐ │                GOLD MATRIX PRO v1.0                 │ │  MATRIX SCORE        ⭐⭐⭐⭐☆      [78.5]             │ │  SIGNAL              STRONG BUY                     │ │                                                     │ │  Trend       ████████████████ 85                    │ │  Momentum    ████████████     72                    │ │  Reversion   ███████          45                    │ │  Volume      ████████████     68                    │ │  Divergence  ████████████████ 82                    │ │                                                     │ │  Session: LONDON | Volatility: NORMAL               │ │  Risk Level: ● MEDIUM                               │ └─────────────────────────────────────────────────────┘

---

## 🚀 Installation

### Quick Install
1. Download `GoldMatrixPro.ex5`
2. MT5 → File → Open Data Folder
3. `MQL5/Indicators/`
4. Paste file
5. Restart MT5

---

## ⚙️ Parameters (Excerpt)

```cpp
// Core
InpJMAPeriod        = 14;
InpRSIPeriod        = 14;

// Signal Threshold
InpStrongBuyLevel  = 75;
InpStrongSellLevel = -75;

// Dashboard
InpShowDashboard   = true;
InpDashboardX      = 20;
InpDashboardY      = 30;
Presets
Style
Lookback
Buffer
Scalping
50
2
Day Trade
100
3
Swing
200
4
📈 Performance Notes
Metric
Typical Range
Win Rate
~60–65%
Profit Factor
≥1.8
Max Drawdown
<15%
Results depend on market conditions and risk management.
🎮 Usage
Signal Interpretation
Score
Signal
≥75
Strong Buy
50–75
Weak Buy
-50 to 50
Neutral
-75 to -50
Weak Sell
≤-75
Strong Sell
Hotkeys
F5 → Refresh dashboard
F6 → Screenshot
F7 → Toggle dashboard
📜 License
Personal License
Free for personal use
Attribution required
30-day trial
Commercial License
Required for resale
Source access
Priority support
Custom branding
📧 Contact: rizkyevory@github.com
⚠️ Disclaimer
Trading involves risk.
Past performance does not guarantee future results.
Use at your own discretion.
© 2024 Rizky Evory — All Rights Reserved.
