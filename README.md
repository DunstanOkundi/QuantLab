# Quantitative Lab

A free, open-source desktop terminal for quantitative finance research —
Bloomberg-terminal breadth without the terminal price tag.

Watch, trade, learn, and build — all in one application. No subscriptions.
No watermarks. No artificial limits.

---

## What’s Inside

Eight dockable workspaces, each arranged for a different piece of the work.
Drag, resize, close, or tear off any panel. Your layout persists between
launches. The command palette (<kbd>⌘K</kbd>) opens any panel in a new tab.

| Workspace | Primary purpose | Default panels |
|-----------|-----------------|-----------------|
| **Markets** | Track the instruments you follow, monitor real-time releases | Watchlist, Quote Detail, Economic Calendar, Heatmap, Event Calendar |
| **Charts** | Candlestick and technical analysis with statistics overlays | Chart, ACF, Distribution, Comparison |
| **Options** | Option chain, volatility surface, Greeks, payoff modelling | Option Chain, IV Surface, Greeks, Payoff Designer |
| **Trade** | Paper trading blotter with full position and performance tracking | DOM, Positions, Blotter, Performance, Prop-monitor, Tear Sheet |
| **Research** | Notebook-based strategy development with AI assistance | Notebook, AI Chat, Hypothesis Builder, Data Quality, Results |
| **Macro** | Global macro data browser and economic release calendar | FRED Browser, Release Calendar, Economic News, News Feed, Event Calendar |
| **Maritime** | AIS ship tracking and chokepoint congestion for commodity flows | AIS Map, Chokepoints |
| **News** | Aggregated financial headlines mapped geospatially | News Feed, News Map |
| **Learn** | Interactive, graded curriculum from beginner Python to advanced quant | Curriculum, Lesson, Knowledge Base |

---

## Key Features

### 📈 **Real-time Market Monitor**
<img width="1920" height="1080" alt="Screenshot 2026-09-01 at 6 01 51 PM" src="https://github.com/user-attachments/assets/fa9a6d83-2b67-4b6c-85dc-2ada48425be4" />

- Live watchlists with custom symbols and groupings
- Quote detail panel with bid/ask, Greeks, and fundamental data
- Event calendar showing scheduled economic releases, earnings, and FRED updates
- Economic heatmap for macro condition overviews

### 📊 **Full Charting Suite**
<img width="1920" height="1080" alt="Screenshot 2026-09-01 at 5 58 21 PM" src="https://github.com/user-attachments/assets/a42be5b4-67f6-40c9-b95b-f1a545bf8347" />

- Lightweight-charts engine for interactive candlesticks
- Statistical overlays: autocorrelation (ACF), distribution histograms, comparative charts
- One-click comparison between symbols, sectors, or indices
- Export charts as PNG

### 🔧 **Options Analytics**
<img width="1920" height="1080" alt="Screenshot 2026-09-01 at 6 02 03 PM" src="https://github.com/user-attachments/assets/7ac45536-53f2-4f9e-8a98-b3eef0e6960d" />

- Live option chains with moneyness sorting
- Interactive implied volatility surface
- Real-time Greeks calculation and payoff designer
- Scenario testing for multi-leg strategies

### 💹 **Paper Trading & Risk**
- Simulated order book with realistic liquidity fills
- Position tracking with unrealized and realized P&L
- Performance metrics: Sharpe, Sortino, drawdown, VaR
- Proprietary-firm scoring dashboard for evaluation prep

### 🧪 **Strategy Research Environment**
<img width="1920" height="1080" alt="Screenshot 2026-08-31 at 11 04 15 AM" src="https://github.com/user-attachments/assets/f61833d3-a493-4e3d-b972-8d0b229695ea" />

- Jupyter-style notebook with integrated Python kernel
- AI assistant panel with token budget control
- Hypothesis builder for structured idea development
- Data quality reports identifying survivorship or stale-data issues

### 🌍 **Macro & Alternative Data**
<img width="1920" height="1080" alt="Screenshot 2026-09-01 at 5 59 32 PM" src="https://github.com/user-attachments/assets/003ba447-2adb-4501-a15f-19cfa91d97af" />


- Full FRED economic database browser with 800k+ series
- News map with geospatial visualization
- Global AIS ship tracking for commodity shipping intelligence
- Maritime chokepoint monitor (Suez, Panama, Hormuz, etc.)

### 🎓 **Learn By Doing**
<img width="1920" height="1080" alt="Screenshot 2026-09-01 at 6 00 07 PM" src="https://github.com/user-attachments/assets/e755073e-9599-442e-afac-1edf9a4b1253" />

- Kaggle-style interactive curriculum (Python → statistics → ML finance)
- Every lesson runs real code against live market data
- Inline grading with hints and progressive solutions
- Knowledge base with full-text search over textbooks

---

# How to Get Quantitative Lab

Quantitative Lab is **not free** and is available **only** via Gumroad.

1. **Visit our Gumroad page:**  
   👉 [https://quantlab.gumroad.com/l/quantlab](https://quantlab.gumroad.com/l/quantlab)

2. **Purchase the license** (one-time payment, includes all future updates).

3. **Download the macOS .dmg or .zip** from your Gumroad library after purchase.

4. **Install & launch:**
   - macOS: Open the .dmg and drag **Quantitative Lab** to your Applications folder.
   - First launch: Right-click the app and select **Open** to bypass Gatekeeper (unsigned build).

> **Note:** Core functionality works out-of-the-box using free Yahoo Finance data. FRED key unlocks the full 800k‑series macro database.

---

## Building from Source (for developers)

If you wish to inspect or modify the code, the source is available under a commercial license.  
Contact us via the Gumroad page for source access.

Requires Node.js 20+ and Python 3.11+.

```bash
git clone https://github.com/dokundi/quant-lab.git
cd quant-lab/ui
npm install
npm run dist
```

---

## Documentation

- [CHANGELOG.md](CHANGELOG.md) — Release notes

---

## License

Quantitative Lab is distributed under a **commercial license** purchased via Gumroad.  
See the Gumroad product page for full terms.

Attribution details are in [docs/ATTRIBUTION.md](docs/ATTRIBUTION.md).

---

## Support & Updates

All purchases include free lifetime updates.  
New features and bug fixes are announced via Gumroad email, the product page and github.

**Disclaimer:** This is research software, not investment advice.  
Historical performance is not indicative of future results. All data is free-tier sourced unless you provide your own API keys.

---

**Get Quantitative Lab now:**  
👉 [https://quantlab.gumroad.com/l/quantlab](https://quantlab.gumroad.com/l/quantlab)
