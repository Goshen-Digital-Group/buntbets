# 🎰 buntbets Casino

![buntbets Logo](./public/logo.png)

A decentralized casino built on Solana blockchain, powered by the buntbets ecosystem. Experience provably fair gaming with transparent, on-chain mechanics.

## ✨ Features

- 🎲 **Provably Fair Gaming** - All game outcomes are verifiable on-chain
- 🏆 **Multiple Games** - Slots, dice, coin flip, and more
- 💰 **Jackpot System** - Community jackpot that grows with every bet
- 🎁 **Bonus System** - Free plays and rewards for players
- 📊 **Live Leaderboards** - Compete with other players
- 💬 **Real-time Chat** - Community trollbox for player interaction
- 📱 **Mobile Responsive** - Seamless experience across all devices
- 🔒 **Secure Wallet Integration** - Connect with popular Solana wallets

## 🚀 Tech Stack

- **Frontend**: React + TypeScript + Vite
- **Styling**: Styled Components
- **Blockchain**: Solana + Gamba Protocol
- **State Management**: React Hooks
- **Wallet Integration**: Solana Wallet Adapter
- **Deployment**: Vercel
- **Database**: Vercel KV (for chat)

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Goshen-Digital-Group/buntbets.git
   cd buntbets
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env
   ```
   
   Configure your `.env` file:
   ```env
   VITE_RPC_ENDPOINT="your-solana-rpc-endpoint"
   VITE_PLATFORM_CREATOR_ADDRESS="your-platform-address"
   ```

4. **Start development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to `http://localhost:4001`

## 🎮 Games Available

- **🎰 Slots** - Classic slot machine with multiple paylines
- **🎲 Dice** - Roll for multipliers up to 9900x
- **🪙 Coin Flip** - Simple heads or tails betting
- **🎯 Plinko** - Drop the ball and watch it bounce
- **💎 Mines** - Navigate the minefield for big wins
- **🎪 More games** - Constantly adding new games

## 📁 Project Structure

```
src/
├── components/          # Reusable UI components
├── games/              # Game implementations
├── sections/           # Page sections (Header, Footer, etc.)
├── hooks/              # Custom React hooks
├── constants/          # App configuration
├── styles/             # Global styles
└── App.tsx            # Main application component
```

## 🔧 Configuration

### Platform Settings
Edit `src/constants.ts` to configure:
- Platform creator address
- Supported tokens
- Game settings
- Feature flags

### Adding New Games
1. Create game component in `src/games/`
2. Export from `src/games/index.ts`
3. Add game metadata and configuration

## 🌐 Environment Variables

| Variable | Description | Required |
|----------|-------------|----------|
| `VITE_RPC_ENDPOINT` | Solana RPC endpoint | ✅ |
| `VITE_PLATFORM_CREATOR_ADDRESS` | Platform creator wallet | ✅ |
| `KV_REST_API_URL` | Vercel KV database URL | ⚠️ (for chat) |
| `KV_REST_API_TOKEN` | Vercel KV API token | ⚠️ (for chat) |

## 🚦 Available Scripts

```bash
# Development
npm run dev          # Start development server
npm run build        # Build for production
npm run preview      # Preview production build
npm run lint         # Run ESLint
npm run type-check   # TypeScript type checking
```

## 🪙 Token Listing

Want to list your token on buntbets for betting? 

**Contact us**: [@real0xteksage](https://t.me/real0xteksage) on Telegram

We're always looking to expand our supported token ecosystem and provide more betting options for our players.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Links

-- **Website**: [buntbets.live](https://buntbets.fun)
-- **Documentation**: [docs.buntbets.live](https://docs.buntbets.fun)
- **Discord**: [Join our community](https://discord.gg/QvYYUcwX)
- **Twitter**: [Follow us](https://x.com/i/communities/1958007698534068643/)

## ⚠️ Disclaimer

This software is provided for educational and entertainment purposes. Gambling involves risk and may not be legal in your jurisdiction. Please gamble responsibly and only with funds you can afford to lose.

## 🙏 Acknowledgments

- Built with [Gamba Protocol](https://gamba.so/)
- Powered by [Solana](https://solana.com/)
- Inspired by the [bunt.fun](bunt.fun) community
- Special thanks to [Bankk](https://github.com/BankkRoll), [Degen Serenade](https://github.com/degenwithheart), and the
[![Contributors](https://img.shields.io/github/contributors/Goshen-Digital-Group/buntbets?style=flat-square)](https://github.com/Goshen-Digital-Group/buntbets/graphs/contributors)


---

**Made with ❤️ by the buntbets Team**