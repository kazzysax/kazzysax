# KAZZYSAX

**Full-stack builder shipping AI agent systems, onchain marketplaces, and user-facing applications across EVM, Solana, and Zcash.**

I build TypeScript and Python systems where AI agents operate as first-class participants — making decisions, earning money, and being held accountable through onchain identity and deterministic rules. My work spans multi-agent orchestration, prediction markets, autonomous hedging, privacy-preserving payments, and social marketplaces where agents and humans work side by side.

## What I work on

- **AI agent infrastructure:** multi-agent courts with structured voting and dissent, MCP servers and SDKs, Claude and Qwen orchestration, deterministic mock modes, and agent registration with bearer-key auth
- **Onchain applications:** USDC escrow marketplaces, prediction markets with AI resolvers, tokenized stock analysis, sealed-bid auctions with shielded payments, and gas-sponsored P2P transfers
- **User-facing products:** PWAs with camera-based pose detection, 3D fight simulations, real-time macro hedging dashboards, social feeds with reputation systems, and knowledge marketplaces with x402 micropayments
- **Safety and correctness:** fail-closed execution gates, hash-chained decision logs, commit-reveal schemes, EIP-712 signatures, idempotency keys, and reconciliation state machines

## Selected work

### [Cerebra](https://github.com/kazzysax/CEREBRA)
Five-agent stock-decision court for autonomous agents. An Analyst gathers evidence, a Challenger attacks the thesis, and three independent judges vote with explicit dissent. Claude and Qwen adapters, PostgreSQL persistence, durable jobs with fencing generations, and a self-running learning loop that calibrates judge confidence from resolved outcomes.

### [Arctisans](https://github.com/kazzysax/arctisans)
Social marketplace on Arc mainnet where humans and AI agents post work, get hired, and get paid in USDC through onchain escrow. ERC-8004 agent identity, Circle wallets for email sign-in, gas-sponsored transactions, and dispute resolution through pre-agreed deadlock rules. [Live →](https://arctisans.vercel.app)

### [Keel](https://github.com/kazzysax/KEEL)
Analysis unit for agents that grades crypto-plus-tokenized-stock pairs by published rules and serves results over MCP and SDK. ~1,440 assets from Ondo, xStocks, and bStocks. Agents call the tools; Keel never holds funds or trades. Built for BNB Hack: Tokenized Stocks Edition.

### [Buffer](https://github.com/kazzysax/BUFFER)
Automatic hedging for BTC and ETH holders around CPI, jobs, and Fed days. SoSoValue macro data drives risk ratings, SoDEX perps execute the hedges, and a Claude agent explains every decision. Hash-chained receipts, practice mode, and a heart-monitor lifeline UI. Built for the SoSoValue Buildathon.

### [PredMon](https://github.com/kazzysax/PREDMON)
Social prediction market on Monad mainnet. Users write calls in plain language, an AI gate extracts the prediction, and an AI resolver settles with cited evidence. Sealed-bid price pools, per-category reputation stored onchain, and EIP-712 relayed gasless votes. Built for the Metropolis hackathon.

### [Obscura](https://github.com/kazzysax/OBSCURA)
AI artist that survives on secret patrons. Voting and sealed-bid auctions use shielded ZEC (Orchard-only Unified Addresses, ZIP-321 payment requests, encrypted memos). If the treasury runs out, the artist goes dormant. 51 passing tests including full rounds with Zcash test vectors. Built for Zecathon 2026.

### [Quill](https://github.com/kazzysax/QUILL)
Knowledge marketplace for AI agents on Solana. Agents search for free and pay authors in USDC via x402 in the same HTTP request. Every piece is wallet-signed for verification. MCP server for Claude Desktop, demo agent with real devnet payments, and a public ledger of paid reads. Built for Road to Colosseum.

### [.verse](https://github.com/kazzysax/.verse)
Gas-sponsored peer-to-peer payments on Polygon with `.verse`, X, and Telegram identities. Privy embedded wallets, USDC and VERSE tokens, payment links, and a safety model that defaults to disabled and fails closed. One free transferable `.verse` name per verified account.

### [FitDuel](https://github.com/kazzysax/Fitduel-)
Fitness PWA where your workouts build a 3D AI boxing champion. Camera-based push-up and squat counter using on-device pose detection. Champions fight in Duels and Rumbles with XP-driven upgrades. No real money, no gambling — champions only stay strong while owners keep training.
