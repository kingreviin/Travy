# Exwager - AI Automated Trading Platform for Deriv

> **"Use 100% free, high-performance AI deriv trading bots that will give you an edge to make profits consistently. No coding needed. Just click to load and trade."**

Exwager is an advanced, high-performance web platform built for Deriv synthetic indices, binary options, and digital contract automation.

---

## ⚡ Features
- **AI Auto-Trading Strategies**: Digit Over/Under, Even/Odd Quantum, Matches/Differs Sniper, Rise & Fall HMM Trend, Accumulator 1-5%, Dominant Digit Differs, and Speed Martingale Turbo.
- **Visual No-Code Bot Builder**: Drag and drop logic blocks, customize triggers, import and export standard Deriv XML bot files.
- **Real-Time Digit Analyzer**: Live WebSocket tick worms, 0-9 frequency distribution heatmap, even/odd ratio, over/under balance, and streak tracking.
- **Automated Risk Management**: Virtual loss filters (observe simulated losses before staking real capital), take-profit, stop-loss, and Martingale multipliers.
- **Deriv WebSocket API**: Live tick feeds directly from `wss://ws.derivws.com/websockets/v3?app_id=1089` with optional API Token authentication.

---

## 🚀 Quick Start (Local Development)

```bash
# 1. Install dependencies
npm install

# 2. Run local development server
npm run dev
```

---

## 📦 Deploy to GitHub & GitHub Pages

```bash
# Initialize git repository
git init
git add .
git commit -m "Initial commit: Exwager automated trading platform"
git branch -M main

# Link to your remote GitHub repository
git remote add origin https://github.com/YOUR_USERNAME/exwager.git
git push -u origin main
```

### One-Click Deployment Options:
- **GitHub Pages**: Automatically enabled via the included `.github/workflows/deploy.yml`.
- **Vercel / Netlify**: Connect your GitHub repo; builds automatically with `npm run build`.
