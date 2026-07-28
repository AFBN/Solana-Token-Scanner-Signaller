# Solana-Token-Scanner-Signaller

Sentinel is a comprehensive, real-time token scanning and trading signal generation platform built specifically for the Solana blockchain[cite: 3]. It aggregates deep data batches from multiple decentralized exchanges and APIs to surface high-probability trading setups, evaluate safety metrics, and track market sentiment.

## Getting Started

Open `index.html` in your browser. No build tools required.

## License

MIT © 2026 AFBN

# Sentinel · Solana Token Scanner & Signaller

Sentinel is a comprehensive, real-time token scanning and trading signal generation platform built specifically for the Solana blockchain[cite: 3]. It aggregates deep data batches from multiple decentralized exchanges and APIs to surface high-probability trading setups, evaluate safety metrics, and track market sentiment[cite: 3].

## Architecture & Deployment
The application is engineered as a self-contained, single-file environment utilizing vanilla JavaScript, CSS, and HTML[cite: 3]. This lightweight structure ensures zero framework overhead (avoiding React or similar libraries) and is intentionally designed to be embedded directly into custom HTML blocks within WordPress environments[cite: 3]. It includes absolute CSS overrides to bypass standard WordPress theme constraints, locking the viewport to create a seamless, full-screen Single Page Application (SPA) experience[cite: 3]. Furthermore, the UI is highly responsive, accommodating workflows and token analysis managed entirely via mobile phone screens[cite: 3].

## Key Features

*   **Dual-Mode Alpha Signals:** Features automated sequential batch scanning to identify tokens based on two distinct strategies.[cite: 3] The first is "Most Likely to Run," which favors momentum, high volume, and young tokens.[cite: 3] The second is "Safe to HODL," which favors established safety, liquidity, and wider holder distribution.[cite: 3]
*   **Multi-Tier Analysis:** Categorizes tokens by market cap into specific operational tiers (New <10k, Low <50k, Mid <150k, Transition 150-500k, High >500k) for highly targeted scanning.[cite: 3]
*   **Advanced Safety Scoring:** Evaluates rug pull risks by querying the Solsniffer API and utilizing fallback open-source heuristics to generate a reliable 0-100 safety score.[cite: 3]
*   **Clone Detection:** Includes a built-in algorithm designed to identify potential scam copy-cat tokens by analyzing naming patterns, symbol length, and the repetition of common scam keywords.[cite: 3]
*   **Market Sentiment Tracker:** Features a live Greed & Fear Index gauge powered by the Alternative.me API to contextualize overall market conditions.[cite: 3]
*   **Comprehensive Data Aggregation:** Fetches real-time price, volume, and liquidity data by combining the Birdeye and DexScreener APIs into a unified dashboard.[cite: 3]
*   **Premium RPC Integration:** Allows users to input custom premium RPC URLs (such as QuickNode) for deep, on-chain evaluation of top-20 wallet concentration.[cite: 3] 
*   **Customizable Filtering:** Users can refine the scanner's output by adjusting token age, minimum 24-hour volume, maximum holder concentration, and specific launchpads (including Pump.fun, Raydium, Moonshot, Orca, and Meteora).[cite: 3]

## Security & Privacy
Sentinel respects user privacy and data security by keeping all sensitive configurations strictly local[cite: 3]. Custom filter settings and premium RPC URLs are saved exclusively within the browser's `localStorage` and are never transmitted to unauthorized external databases[cite: 3].

## Disclaimer
**For Educational Purposes Only.**[cite: 3] Cryptocurrency trading, particularly involving low-market-cap tokens on decentralized exchanges, carries extreme financial risk[cite: 3]. Sentinel provides aggregated data and heuristic evaluations, not financial advice[cite: 3]. Users are solely responsible for conducting their own research (DYOR) and managing their own trading decisions[cite: 3].