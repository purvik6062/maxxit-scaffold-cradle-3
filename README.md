# My Dapp

A Web3 application - foundation built with Cradle

## Getting Started

### Prerequisites

- Node.js >= 20.0.0
- pnpm >= 9.0.0
- Rust (for Stylus contracts)

### Installation

```bash
pnpm install
```

### Environment Variables

Copy `.env.example` to `.env` and fill in the required values:

```bash
cp .env.example .env
```

Required variables:
- `NEXT_PUBLIC_WALLETCONNECT_PROJECT_ID`: WalletConnect Cloud project ID
- `NEXT_PUBLIC_OSTIUM_NETWORK`: Network for Ostium trading (arbitrum or arbitrum-sepolia)
- `ALCHEMY_API_KEY`: Alchemy API key for fetching onchain activity
- `NEXT_PUBLIC_ONCHAIN_NETWORK`: Network for onchain activity (arbitrum or arbitrum-sepolia)
- `NEXT_PUBLIC_WALLETCONNECT_PROJECT_ID`: WalletConnect Cloud project ID for wallet connections

### Development

```bash
pnpm dev
```

### Available Scripts

- `pnpm wallet:setup`: Instructions for wallet setup
- `pnpm maxxit:setup`: Maxxit setup instructions
- `pnpm ostium:setup`: Ostium setup instructions
- `pnpm onchain:setup`: Onchain activity setup instructions
- `pnpm dev`: Start development server
- `pnpm build`: Build for production
- `pnpm start`: Start production server
- `pnpm lint`: Run ESLint

## Project Structure

```
├── src/                 # Application source code
├── contracts/           # Stylus smart contracts
├── docs/               # Documentation
├── .github/            # GitHub Actions workflows
└── package.json
```

## License

MIT

---

Generated with ❤️ by [Cradle](https://cradle-web-eight.vercel.app)
