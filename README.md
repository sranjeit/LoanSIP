# 🎯 LoanSIP — Loan Freedom Sweet Spot Calculator

> Find the exact loan tenure where your SIP investments grow enough to cover your entire loan — making your loan **effectively free**.

**🔗 Live App → [https://sranjeit.github.io/loansip/](https://sranjeit.github.io/loansip/)**

---

## 💡 The Core Idea

Most people with loans think in one dimension — just repay it. LoanSIP shows you a smarter path:

```
Your Monthly Capacity = New EMI + SIP Investment
```

By extending your loan tenure slightly:
- EMI drops → more money freed up each month
- That freed money goes into a Mutual Fund as SIP
- SIP compounds over the same tenure
- **Sweet Spot** = the tenure where MF Corpus ≥ Total EMI paid → Loan is FREE 🎉

---

## ✨ Features

| Feature | Description |
|---|---|
| 🎯 Sweet Spot Finder | Auto-calculates the exact tenure for loan freedom |
| 📈 Step-Up SIP | Model annual SIP increases as your salary grows |
| 🔄 Reverse Calculator | "I want to be free in 5 years — what do I need?" |
| 🧾 Tax Shield | Sec 24b + 80C home loan tax benefit calculator |
| 💰 Prepayment Simulator | What if you make a lump-sum prepayment at month X? |
| ⚡ Rate Sensitivity | How does a 1-2% rate hike affect your EMI? |
| ⚖️ Scenario Compare | Compare up to 3 loan scenarios side-by-side |
| 🔥 Sweet Spot Heatmap | Visualise sweet spot across capacity vs MF return |
| 📊 Wealth Trajectory | 3-path chart: Loan+SIP vs No-Loan SIP vs Outgo |
| 💾 Save Scenarios | Save/load named scenarios via localStorage |
| 🔗 Share via URL | Share exact scenarios via URL parameters |
| 🌙 Dark/Light Theme | Toggle between themes, persists across sessions |
| 📱 PWA | Install on mobile, works offline |
| 📋 Amortization Table | Full month-by-month breakdown with SIP tracking |

---

## 🚀 Hosting (GitHub Pages)

This is a **single HTML file** — no build step, no dependencies, no server needed.

1. Fork or clone this repo
2. Make sure `index.html` is in the root
3. Go to **Settings → Pages → Deploy from branch → main**
4. Your app is live at `https://yourusername.github.io/loansip/`

---

## 🛠️ Tech Stack

- **Pure HTML + CSS + JavaScript** — zero frameworks, zero dependencies
- **Canvas API** — all charts drawn natively
- **localStorage** — scenario saving, theme preference
- **Service Worker** — offline PWA support
- **URL params** — shareable scenario links

---

## 📁 File Structure

```
loansip/
├── index.html     ← entire app (single file)
└── README.md      ← this file
```

---

## ⚠️ Disclaimer

LoanSIP is a financial planning tool for **illustration purposes only**. Mutual Fund returns are not guaranteed. Past performance does not indicate future results. Please consult a SEBI-registered financial advisor before making investment decisions.

---

## 📄 License

MIT License — free to use, modify and distribute.

---

*Built with ❤️ for financial clarity*
