# 🚀 GoldEngineV5: Institutional Momentum Sniper Edition

**GoldEngineV5** is the flagship quantitative trading engine for Gold (`XAUUSD`), engineered specifically for MetaTrader 5.

---

## ✨ Key Technical Upgrades in V5:

1. **🎯 Institutional Momentum Sniper Engine**:
   * **`InpMinCandleBodyPips` (Default = 5.0 Pips)**: Automatically **BLOCKS** entries on small, sleepy, low-movement candles (< 5.0 pips), eliminating low-volume chop.
   * **`InpMinVolumeRatio` (Default = 1.2x MA)**: Requires real institutional tick volume surge (>1.2x 20-period MA) before any order is placed.

2. **🛡️ Harmonized +25 Pip Delayed Unchoked Profit Lock**:
   * **0 to +24.9 Pips**: Unchoked breathing room so normal 3-pip pullbacks never trigger premature micro-exits.
   * **+25.0 Pips**: Triggers BreakEven (+5.0 Pips locked).
   * **+40.0 Pips**: Locks +25.0 Pips profit.
   * **+60.0 Pips**: Locks +40.0 Pips profit, letting the runner hit maximum target!

3. **💰 $20 Capital Lock Floor Protection**:
   * Lowered capital floor to **$20.00** so small accounts ($50–$100) never get blocked after a minor initial loss.

4. **📈 Dynamic Compounding Lot Ladder**:
   * Automatically scales lot sizes ($50 balance = 0.01 lot step: $200 $\rightarrow$ 0.04, $250 $\rightarrow$ 0.05).

---

## 🛠️ Main Source Files:
* `Experts/GoldEngineV5.mq5` — Full modular expert advisor.
* `Experts/GoldEngineV5_Decoupled.mq5` — Standalone production EA binary source.
* `Include/GoldEngineV4/` — Core quantitative engines, classifier, and risk guardian.

---

## 🔒 Intellectual Property & Security Notice
All source code, quant architecture, and proprietary algorithms are protected. Unauthorized copying, distribution, or decompilation is strictly prohibited.
