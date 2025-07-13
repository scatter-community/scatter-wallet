# Scatter Wallet Desktop


A self‑custodial, cross‑platform blockchain wallet and local‑machine authentication hub.

  <a href="https://github.com/scatter-community/scatter-wallet/releases/latest">
    <img src="https://img.shields.io/badge/Windows-Download-0078D6?style=for-the-badge" alt="Download for Windows">
  </a>
  <a href="https://github.com/scatter-community/scatter-wallet/releases/latest">
    <img src="https://img.shields.io/badge/macOS-Download-000000?style=for-the-badge" alt="Download for macOS">
  </a>
  <a href="https://github.com/scatter-community/scatter-wallet/releases/latest">
    <img src="https://img.shields.io/badge/Linux-Download-FCC624?style=for-the-badge" alt="Download for Linux">
  </a>

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
