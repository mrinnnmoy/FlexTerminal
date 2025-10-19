# FlexTerminal

Unified Trading Terminal for Stocks & Crypto — multi-exchange order routing, visual arbitrage detection and one-click strategies in a single app.

## ⚠️ Problem to Solve.

Traders today must juggle multiple platforms: broker terminals for stocks (MT-style), centralized crypto exchanges, and decentralized protocols. That fragmentation causes slow decision-making, missed arbitrage, fragmented portfolios, and repetitive manual order placement. There’s no single, polished terminal that lets users place synchronized orders across CEX/DEXs, visually track cross-venue price divergences, and trigger one-click strategies.

## ✅ Possible Solution.

**FlexTerminal** is a desktop/web trading terminal that aggregates market data and order routing across centralized exchanges, decentralized exchanges and traditional brokers (MT5/FX brokers, retail broker APIs). It provides a single UI to place linked orders, visualize arbitrage opportunities, run prebuilt one-click strategies and backtest or simulate strategies across assets. With core capabilities including:

1. Unified order placement (route the same strategy to Binance, Coinbase, Alpaca, and AMMs).
2. Visual arbitrage heatmaps and pair comparators across CEX ↔️ DEX ↔️ Brokers.
3. One-click strategies: copyable templates (market-making, triangular arbitrage, paired trades).
4. Smart order sizing and risk controls (per-trade and portfolio-level limits).
5. Real-time streaming market data, orderbook & depth visualization.
6. Portfolio aggregation and PnL across venues (realized/unrealized).
7. Backtest & paper trading environment.

---

## ⚙️ Architecture.

![FlexTerminal Architecture](./)
[Excalidraw File](./)

---

## 🛠 Tools, Languages & Frameworks used.

- **Electron / ReactJS:** Desktop UI (Electron) + React (TypeScript) for building a responsive, real-time terminal UI and charting workspace.
- **TypeScript:** Primary language for frontend and backend services for type-safety and developer ergonomics.
- **Node.js:** Backend runtime to orchestrate gateway APIs, adapters, and user sessions.
- **Express.js / Fastify:** Framework for building RESTful and internal APIs between UI and backend services.
- **CCXT:** Unified library for interacting with many centralized crypto exchanges (order placement, market data).
- **FIX Engine / MT5 Bridge:** Integration layer for brokers and MT5-style execution (FIX protocol or broker SDKs).
- **ethers.js / web3.js / @solana/web3.js:** On-chain libraries for composing and signing DEX transactions on EVM chains and Solana.
- **Redis:** Fast cache and ephemeral state store for orderbooks, rate-limiting, and session data.
- **PostgreSQL / TimescaleDB:** Persistent storage and time-series DB for historical tick data, trades, and PnL calculations.
- **Rust / Go (optional):** Low-latency microservices for execution engine, market data normalization, or strategy runner.
- **Python (Pandas / Backtesting libs):** Strategy backtesting, analytics, and quant research modules.
- **WebSockets:** Real-time streaming of market data, order updates, and UI push messages.
- **Charting Library (TradingView / Lightweight custom):** High-performance candlestick charts, depth charts, and custom arbitrage visualizations.
- **WalletConnect / MetaMask / Custodial SDKs:** Wallet connections for signing on-chain DEX trades.
- **CI/CD & Containerization:** Docker, Kubernetes for deployment of microservices and scaling market-data pipelines.

---

## 📂 Folder Structure.

- **client**: Contains the frontend codebase.
- **server**: Contains the backend code and API integrations.

---

## 🧑‍💻 Contributions to this repo are WELCOME.👋

- 🎨 Any improvements to the design and UI are welcome.
- 🔨 Try to break the website by testing it to find any bugs. If you find any, check if there is an issue already open for it, if there is none, then report it.

---

## 🔃 Steps to be followed in order to make valid contributions to this repo.

**1.** Fork the [FlexTerminal](https://github.com/mrinnnmoy/FlexTerminal) repo by clicking on the fork button on the top of the page. This will create a copy of this repository in your account.

**2.** Clone the forked repository

        git clone "https://github.com/<your-github-username>/FlexTerminal"

- Download and install Node JS v16.16.0
- Download and install Git.
- Go to the terminal of your code editor and run "npm install" to download packages.
- Run "npm run dev" to start a local server.

**3.** Make necessary changes and commit those changes. <br />
Remember never push anything to the Main branch. <br />

Always change your branch to "develop" using:

    git checkout develop

Again check your current branch using:

    git branch

It should point \*develop

Now add your changes using:

    git add files-you-edited

If there are multiple files you can use:

    git add .

Now create a commit message using:

    git commit -m "<commit-message-goes-here>"

**4.** Push changes to GitHub

    git push origin develop

**5.** Create a Pull Request 👋<br>

Now you go to your repository on GitHub, you’ll see a `Compare & pull request` button. Click on that button and now write a summary of what changes you have done. (Attach images if required). I will review your code and merge it if it passes all the tests.❤️
