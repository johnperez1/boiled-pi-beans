# 🫘 Boiled Pi Beans
**The Quantum Yield Protocol**

Optimize your Pi with the premier "Quantum Pot" miner. Experience a gamified 8% daily yield simulation, real-time strategy tips from Lil Bot AI, and a sustainable 6:1 compounding ecosystem. Boil, Re-Boil, and Harvest your way to the top of the node! Secure, native, and built for Pioneers.

---

## 🚀 Live App
**[https://johnperez1.github.io/boiled-pi-beans/](https://johnperez1.github.io/boiled-pi-beans/)**

> Open in [Pi Browser](https://minepi.com) for full functionality

---

## ✨ Features

- 🔐 **Pi Wallet Integration** - Secure authentication via Pi SDK
- 💰 **Stake & Earn** - "Boil" Pi beans to generate daily yields
- 📈 **8% Daily Yield Protocol** - Simulated compounding returns
- ♻️ **Auto-Compounding** - Re-Boil accumulated yields
- 🍴 **Harvest System** - Withdraw your earnings
- 👥 **Referral Program** - Share your node link and earn
- 📊 **Real-Time Dashboard** - Live yield ticker and sustainability meter
- 📱 **Mobile-First Design** - Fully responsive with notch support

---

## 🛠️ Tech Stack

- **Frontend:** Vanilla JavaScript (no dependencies)
- **Blockchain:** Pi Network SDK v2.0
- **Styling:** CSS with glassmorphism design
- **UI/UX:** Neon color scheme, smooth animations
- **Deployment:** GitHub Pages

---

## 📋 Getting Started

### Prerequisites
- Pi Network account
- Pi Browser (for payments)
- Modern web browser

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/johnperez1/boiled-pi-beans.git
   cd boiled-pi-beans
   ```

2. **Update your Pi App ID**
   Edit `index.html` and replace:
   ```javascript
   const APP_ID = 'YOUR_APP_ID'; // Replace with your Pi App ID
   ```

3. **Serve locally**
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   ```

4. **Test in Pi Browser**
   - Navigate to `http://localhost:8000`
   - Open in Pi Browser for full SDK functionality

---

## 🎮 How to Play

### 1. **Connect Wallet**
   - Click "Connect Pi Wallet"
   - Authenticate with Pi SDK
   - Grant payment permissions

### 2. **Boil Beans**
   - Enter amount (minimum 1 Pi)
   - Confirm payment in Pi Browser
   - Watch your yield accumulate in real-time

### 3. **Re-Boil (Compound)**
   - Click ♻️ Re-Boil to stake accumulated yields
   - Increases your principal for higher daily earnings

### 4. **Harvest**
   - Click 🍴 Harvest to withdraw earnings
   - Yields are converted and sent to your wallet

### 5. **Referrals**
   - Navigate to REFERRALS tab
   - Share your unique node link
   - Earn bonuses when pioneers use your link

---

## 🔧 Configuration

### Pi SDK Settings
```javascript
Pi.init({ version: "2.0", sandbox: true });
```

Change `sandbox: true` to `sandbox: false` for mainnet.

### Yield Rate
Current: 8% annual (0.08% daily)

To adjust, modify in `startEngine()`:
```javascript
yieldAcc += (staked * 0.08) / 86400 / 10;
```

### Referral URL
Default: `https://johnperez1.github.io/boiled-pi-beans/?ref={username}`

---

## 📦 Deployment

### GitHub Pages (Current)
Already deployed at: **https://johnperez1.github.io/boiled-pi-beans/**

To redeploy:
```bash
git push origin main
```

### Custom Domain
1. Add domain in repository Settings → Pages
2. Update referral URL in code
3. Wait for DNS propagation

### Vercel / Netlify
1. Connect repository
2. Deploy automatically on push
3. Update `APP_ID` for production

---

## 🏗️ Project Structure

```
boiled-pi-beans/
├── README.md           # This file
├── index.html          # Single-page app (HTML + CSS + JS)
├── LICENSE             # MIT License
└── .github/
    └── workflows/      # CI/CD (optional)
```

---

## ⚡ Performance

- **Size:** ~8KB (minified)
- **Load Time:** <1s on 4G
- **Dependencies:** 0 (except Pi SDK)
- **Browser Support:** All modern browsers

---

## 🛡️ Security

- ✅ Pi SDK authentication only
- ✅ No private keys handled
- ✅ Serverless architecture
- ✅ Read-only referral links
- ⚠️ Production: Set `sandbox: false` in Pi.init()

---

## 🐛 Troubleshooting

### "Open in Pi Browser" error
- App only works in Pi Browser on mobile
- Desktop testing: Use Pi SDK sandbox mode

### Payment fails
- Ensure Pi Browser is updated
- Check Pi Network connectivity
- Verify `APP_ID` is configured

### No yield accumulation
- Ensure amount staked > 0
- Check browser console for errors
- Verify JavaScript is enabled

---

## 📞 Support

- **Pi Network Docs:** https://docs.minepi.com
- **Issues:** Create a GitHub issue
- **Security:** Do not share your seed phrase

---

## 📄 License

MIT License - See [LICENSE](./LICENSE) file

---

## 🙏 Credits

Built for the Pi Network pioneer community.

**Made with ❤️ by johnperez1**

---

## 🚀 Roadmap

- [ ] Leaderboard system
- [ ] Advanced analytics
- [ ] Mobile app (native)
- [ ] DAO governance
- [ ] Multi-tier rewards
- [ ] NFT achievements

---

**Last Updated:** May 2, 2026

Visit us: **https://johnperez1.github.io/boiled-pi-beans/**
