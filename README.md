# Stellar Uzima Healthcare Platform

> 🚀 **MIGRATION IN PROGRESS TO V2!** 
> 
> We're upgrading to a completely new architecture for Drip Open Source.
> See [MIGRATION-V2.md](MIGRATION-V2.md) for details.

---

## 🎯 About Stellar Uzima

A healthcare knowledge-sharing platform that rewards users with Stellar (XLM) tokens for quality medical content.

### Key Features
- 💊 Medical professionals and patients share knowledge
- 💰 Earn XLM tokens, convert to USDT
- ⭐ Quality content gets better rewards
- 🔒 Secure authentication and rate limiting
- 📈 Modular, scalable architecture

---

## 📂 Current Project Structure

### 🆕 V2 (Active Development - v2-redesign branch)
```
frontend-v2/          # New Next.js frontend
├── app/             # Next.js app directory
├── components/      # React components
├── hooks/           # Custom React hooks
├── lib/             # Utilities and configs
├── public/          # Static assets
├── styles/          # Global styles
└── ...
```

**To run V2:**
```bash
cd frontend-v2
npm install
npm run dev
```

### 📦 V1 (Legacy)
- Root directory contains V1 code (main branch)
- Fully backed up in `archive/v1` branch
- See `CONTRIBUTORS-V1.md` for all V1 contributors

---

## 🚀 Quick Start (V2)
```bash
# Clone the repository
git clone https://github.com/Stellar-Uzima/Uzima-Frontend.git
cd Uzima-Frontend

# Switch to v2 development branch
git checkout v2-redesign

# Install and run
cd frontend-v2
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to see the app.

---

## 🏗️ Tech Stack

### V2
- **Framework**: Next.js 14+ (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: shadcn/ui
- **Blockchain**: Stellar SDK

### V1 (Legacy)
- Next.js
- TypeScript
- Tailwind CSS

---

## 🤝 Contributing

We're transitioning to **Drip Open Source**! 

- Check out [MIGRATION-V2.md](MIGRATION-V2.md) to understand the changes
- New contribution guidelines coming soon
- For now, focus contributions on the `frontend-v2/` directory in the `v2-redesign` branch

### Development Workflow
1. Fork the repository
2. Create a feature branch from `v2-redesign`
3. Make your changes in `frontend-v2/`
4. Submit a pull request

---

## 🙏 Acknowledgments

**V1 Contributors**: See [CONTRIBUTORS-V1.md](CONTRIBUTORS-V1.md) for all the amazing people who built our foundation during Hacktoberfest!

Your contributions during Hacktoberfest helped shape this project. Thank you! 🎉

---

## 📜 License

[Your License Here]

---

## 🔗 Links

- **GitHub**: https://github.com/Stellar-Uzima/Uzima-Frontend
- **Inspired by**: https://wazimahealth.com/services/
- **Stellar**: https://stellar.org

---

## 📊 Project Status

- ✅ V1 Completed (Hacktoberfest)
- ✅ V1 Archived
- 🔄 V2 In Development (Drip Open Source)
- ⏳ V2 Testing Phase
- ⏳ Full Migration

---

## 💡 About Drip Open Source

This project is being prepared for Drip Open Source, which provides better rewards and recognition for quality contributions.

Stay tuned for more updates!