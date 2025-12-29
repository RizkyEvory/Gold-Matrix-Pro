
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

# SND Hunter Pro – Smart Supply & Demand Zone Indicator

![MT5 Indicator](https://img.shields.io/badge/Platform-MetaTrader%205-blue)  
![Version](https://img.shields.io/badge/Version-3.0-brightgreen)  
![License](https://img.shields.io/badge/License-Free%20for%20Personal%20Use-orange)

**SND Hunter Pro** adalah indikator MetaTrader 5 yang secara otomatis mendeteksi dan menampilkan zona Supply & Demand berkualitas tinggi berdasarkan price action, volume, dan kekuatan rejection.

Indikator ini dirancang khusus untuk trader yang mengandalkan konsep Supply/Demand (SND) atau Smart Money Concept (SMC), terutama pada pair XAUUSD (Gold) dan pair mayor lainnya.

## Fitur Utama

- Deteksi otomatis zona **Supply** (merah) dan **Demand** (hijau) yang fresh & kuat
- Sistem scoring kekuatan zona (0–100%) berdasarkan:
  - Freshness (umur zona)
  - Volume spike
  - Rejection candle (pin bar, engulfing)
- Dashboard informatif real-time:
  - Jumlah zona aktif
  - Zona terkuat
  - Zona terdekat (dengan jarak dalam pips + arah ▲▼)
  - Market bias (Bullish/Bearish/Neutral)
- Alert saat harga mendekati zona penting (bisa diatur jaraknya)
- Zona otomatis expire setelah waktu tertentu atau setelah 3x touch
- Maksimal 8 zona per tipe (Supply/Demand) untuk menjaga chart tetap bersih
- Visual rectangle + label strength yang mudah dibaca

## Cara Install

1. Download file `SND_Hunter.ex5` dari folder **Release** atau langsung dari repository ini.
2. Buka MetaTrader 5 → File → Open Data Folder → MQL5 → Indicators
3. Paste file `SND_Hunter.ex5` ke folder Indicators
4. Restart MT5 atau refresh Navigator (klik kanan → Refresh)
5. Drag & drop indikator **SND Hunter Pro** ke chart yang diinginkan

## Pengaturan Input (Inputs)

| Parameter              | Default | Keterangan |
|-----------------------|---------|------------|
| LookbackBars          | 100     | Jumlah bar yang dianalisa untuk deteksi zona |
| MinZoneStrength       | 70.0    | Minimum strength (%) agar zona ditampilkan |
| ShowAlerts            | true    | Aktifkan alert saat harga mendekati zona |
| AlertPips             | 25      | Jarak maksimal (dalam pips) untuk trigger alert |
| ShowDashboard         | true    | Tampilkan panel informasi di pojok kiri atas |
| SupplyZoneColor       | Crimson | Warna zona Supply |
| DemandZoneColor       | ForestGreen | Warna zona Demand |
| MaxZonesPerType       | 8       | Maksimal zona Supply & Demand yang ditampilkan |
| ZoneExpireHours       | 24      | Zona otomatis hilang setelah berapa jam |

## Screenshot

*(Coming soon – akan ditambahkan gambar chart dengan zona Supply/Demand yang terdeteksi)*

# OrderFlow Matrix Pro – Advanced Market Structure & Order Flow Indicator

![MT5 Indicator](https://img.shields.io/badge/Platform-MetaTrader%205-blue)  
![Version](https://img.shields.io/badge/Version-1.01-brightgreen)  
![Optimized For](https://img.shields.io/badge/Optimized%20For-XAUUSD%20%7C%20GBPJPY-gold)  
![License](https://img.shields.io/badge/License-Free%20for%20Personal%20Use-orange)

**OrderFlow Matrix Pro** adalah indikator MetaTrader 5 canggih yang menggabungkan analisis **Market Structure**, **Breakout Detection**, **Order Flow (Volume Delta)**, **Liquidity Zones**, dan **Risk Management** otomatis dalam satu dashboard yang powerful.

Dirancang khusus untuk trader **Smart Money Concept (SMC)** / **ICT** yang fokus pada XAUUSD (Gold) dan GBPJPY, tapi bisa digunakan di pair lain.

## Visual Overview (Contoh Tampilan Serupa)

## Fitur Utama

- **Market Structure Detection**: Swing High/Low otomatis + Higher Highs/Lower Lows → Bullish/Bearish/Ranging + Phase (Markup, Decline, Accumulation, Distribution)
- **Breakout Signals**: Panah hijau (Bullish) / merah (Bearish) dengan filter volume spike, delta confirmation, spread, dan session
- **Order Flow Analysis**:
  - Volume Delta Histogram (real-time buy/sell pressure)
  - Cumulative Delta
  - Imbalance detection
  - Point of Control (POC) simplified
- **Liquidity Zones**: Deteksi pool liquidity + stop hunt probability
- **Dashboard Komprehensif**: Real-time info trend, breakout strength, delta, POC, liquidity, SL/TP, position size, session
- **Risk Management Otomatis**: Hitung SL berdasarkan ATR, TP 1:2 & 1:3, position sizing berdasarkan risk %
- **Alert System**: Terminal alert, push notification, email pada breakout, structure change, liquidity hunt
- **Multi-Timeframe Confirmation** & Session Filter (London/NY/Overlap)
- **Keyboard Shortcut**: Tekan **D** untuk toggle dashboard, **R** untuk reset analisis

## Cara Install

1. Download file `OrderFlowMatrixPro.ex5` dari repository ini (folder Release atau root).
2. Buka MT5 → File → Open Data Folder → MQL5 → Indicators
3. Paste file `.ex5` ke folder Indicators
4. Restart MT5 atau refresh Navigator
5. Drag indikator **OrderFlow Matrix Pro** ke chart (rekomendasi: XAUUSD atau GBPJPY, timeframe M15-H1)

## Pengaturan Input Utama

| Group                  | Parameter                     | Default | Keterangan |
|------------------------|-------------------------------|---------|------------|
| Market Structure      | InpSwingLookback              | 50      | Lookback deteksi swing |
|                        | InpUseMultiTF                 | true    | Konfirmasi higher timeframe |
| Breakout Detection    | InpVolumeSpikeMultiplier      | 2.0     | Minimal berapa kali volume spike |
|                        | InpFilterBySession            | true    | Hanya signal di session aktif |
| Order Flow            | InpDeltaPeriod                | 20      | Periode kalkulasi delta |
|                        | InpShowCumulativeDelta        | true    | Tampilkan cumulative delta |
| Liquidity Zones       | InpShowLiquidityZones         | true    | Tampilkan zona liquidity |
| Risk Management       | InpDefaultRiskPercent         | 1.0     | Risk per trade (%) |
|                        | InpAutoPositionSizing         | true    | Hitung lot otomatis |
| Visual                | InpShowDashboard              | true    | Tampilkan dashboard besar |
| Alert                 | InpAlertBreakout              | true    | Alert saat breakout confirmed |

## Catatan Penting

- Indikator ini **gratis untuk penggunaan pribadi**.
- Tidak boleh dijual ulang atau didistribusikan sebagai produk komersial tanpa izin.
- Optimalkan untuk **XAUUSD** dan **GBPJPY** – performa terbaik di pair volatil.
- Gunakan sebagai **confluence tool**, bukan sinyal tunggal.

## Credit & Support

Dibuat oleh **M4DI~UciH4**  
GitHub: https://github.com/RizkyEvory  

Jika kamu suka dengan indikator ini, beri ⭐ di repository!  
Feedback, saran, atau bug report sangat dihargai.

Happy trading & semoga cuan konsisten! 🚀💰
