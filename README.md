# Scatter Wallet Desktop

![Version](https://img.shields.io/github/v/release/scatter-community/scatter-wallet?label=latest) ![License](https://img.shields.io/github/license/scatter-community/scatter-wallet)

A self‑custodial, cross‑platform blockchain wallet and local‑machine authentication hub.

---

## Installation

Download the latest release for **Windows**, **macOS** or **Linux** from [Releases](https://github.com/scatter-community/scatter-wallet/releases), then install or unpack and launch.

## Development

```bash
git clone https://github.com/scatter-community/scatter-wallet.git
cd scatter-wallet
yarn install      # or npm install
electron .        # ensure ScatterEmbed is running or configure .env
```

## Build

Run the appropriate script on the target platform:

```bash
npm run release-mac
npm run release-windows
npm run release-linux
```

## License

Distributed under the MIT License. See [LICENSE](./LICENSE).
