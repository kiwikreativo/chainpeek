# ChainPeek

A Web3 dApp for connecting a MetaMask wallet, checking your balance, and sending funds to other accounts — a lightweight, no-frills wallet interface.

## ✨ Features

- 🔌 **Connect Wallet** — connect via MetaMask using the MetaMask SDK
- 💰 **View Balance** — see your wallet's balance at a glance
- 💸 **Transfer Funds** — send balance to another wallet address

## 🚧 Status

Early stage — currently scaffolded on top of Astro's starter template. Wallet connection, balance display, and transfer functionality are in active development.

## 🛠️ Tech Stack

- **[Astro](https://astro.build)** — site framework
- **[React](https://react.dev)** — interactive components
- **[TailwindCSS](https://tailwindcss.com)** — styling
- **[MetaMask SDK](https://docs.metamask.io/sdk/)** — wallet connection
- **[wagmi](https://wagmi.sh)** / **[viem](https://viem.sh)** — Ethereum interactions
- **[ethers.js](https://docs.ethers.org)** — blockchain reads/transactions
- **[TanStack Query](https://tanstack.com/query)** — async state/data fetching
- **[Netlify](https://www.netlify.com)** — deployment

## 🚀 Getting Started

```bash
pnpm install
pnpm run dev
```

Runs locally at `localhost:4321`.

## 📦 Available Scripts

| Command         | Action                          |
| --------------- | -------------------------------- |
| `pnpm dev`      | Start local dev server           |
| `pnpm build`    | Build for production             |
| `pnpm preview`  | Preview the production build     |

## 🗺️ Roadmap

- [X] Wallet connect flow (MetaMask)
- [X] Display wallet balance
- [ ] Send balance to another address
- [ ] Transaction history / confirmations

## 📄 License

MIT
