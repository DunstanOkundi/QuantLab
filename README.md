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
<img width="1920" height="1080" alt="Screenshot 2026-08-31 at 10 37 02 AM" src="https://github.com/user-attachments/assets/036cbbc8-9b58-4f20-930a-e08d11cb2941" />
- Live watchlists with custom symbols and groupings
- Quote detail panel with bid/ask, Greeks, and fundamental data
- Event calendar showing scheduled economic releases, earnings, and FRED updates
- Economic heatmap for macro condition overviews

### 📊 **Full Charting Suite**
- Lightweight-charts engine for interactive candlesticks
- Statistical overlays: autocorrelation (ACF), distribution histograms, comparative charts
- One-click comparison between symbols, sectors, or indices
- Export charts as PNG

### 🔧 **Options Analytics**
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
- Jupyter-style notebook with integrated Python kernel
- AI assistant panel with token budget control
- Hypothesis builder for structured idea development
- Data quality reports identifying survivorship or stale-data issues

### 🌍 **Macro & Alternative Data**
<img width="1920" height="1080" alt="Screenshot 2026-08-31 at 10 40 30 AM" src="https://github.com/user-attachments/assets/3f3f6753-63f4-497b-a6ff-22d9b3b865ac" />
- Full FRED economic database browser with 800k+ series
- News map with geospatial visualization
- Global AIS ship tracking for commodity shipping intelligence
- Maritime chokepoint monitor (Suez, Panama, Hormuz, etc.)

### 🎓 **Learn By Doing**
<img width="1920" height="1080" alt="Screenshot 2026-08-31 at 10 44 53 AM" src="https://github.com/user-attachments/assets/4703ff6f-9c09-4af4-8621-74ae44e39bd6" />
- Kaggle-style interactive curriculum (Python → statistics → ML finance)
- Every lesson runs real code against live market data
- Inline grading with hints and progressive solutions
- Knowledge base with full-text search over textbooks

---

## Quick Start

### macOS
1. Download `Quantitative Lab-X.X.X-mac.zip` from the releases page.
2. Unzip and drag **Quantitative Lab** to your `Applications` folder.
3. Launch the app (first-time: right-click and **Open** to bypass Gatekeeper).
4. For FRED economic data, add your (free) FRED API key to `~/.quantlab/.env`:
   ```
   FRED_API_KEY=your_key_here
   ```

### Windows
1. Download the `.msi` installer from releases.
2. Run the installer.
3. Launch from the Start Menu.

> **Note:** Market data and charts work out of the box using free tiers of Yahoo Finance and FRED. Optional API keys for extended limits can be added to `~/.quantlab/.env`.

---

## Documentation

- [CHANGELOG.md](CHANGELOG.md) — Release notes

---

## License

Distributed under the MIT License. See `LICENSE` for details.

Attribution details are in [docs/ATTRIBUTION.md](docs/ATTRIBUTION.md).

---

## Support Development

If you find value in Quantitative Lab, consider sponsoring development via
[Gumroad](https://gumroad.com) or sharing it with your network.

**Disclaimer:** This is research software, not investment advice. Historical
performance is not indicative of future results. All data is free-tier sourced
unless you provide your own API keys.
