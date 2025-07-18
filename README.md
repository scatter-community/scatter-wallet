

# Scatter Wallet #LATEST



A self‑custodial, cross‑platform wallet and local‑machine authentication hub **for Antelope‑based blockchains** — including **EOS → Vaulta (`A`)**, **WAX**, **Telos**, and additional compatible networks.
<img width="2069" height="740" alt="better-on-boarding" src="https://github.com/user-attachments/assets/b2da63b9-a557-446f-ad37-688389c0372e" />


### Download Scatter Wallet


<table>
  <tr>
    <td>
      <a href="https://github.com/scatter-community/scatter-wallet/releases/latest">
        <img src="https://img.shields.io/badge/Windows-Download-0078D6?style=for-the-badge" alt="Download for Windows">
      </a>
    </td>
    <td>Windows 10/11 x64 installer (.exe), Microsoft‑signed</td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/scatter-community/scatter-wallet/releases/latest">
        <img src="https://img.shields.io/badge/macOS-Download-000000?style=for-the-badge" alt="Download for macOS">
      </a>
    </td>
    <td>Universal .dmg for macOS 12+ (Apple Silicon & Intel)</td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/scatter-community/scatter-wallet/releases/latest">
        <img src="https://img.shields.io/badge/Linux-Download-FCC624?style=for-the-badge" alt="Download for Linux">
      </a>
    </td>
    <td>AppImage and .tar.gz for Ubuntu, Debian, Fedora, and other distributions</td>
  </tr>
</table>



---

|                                                                          | Native Token(s)                | Transfers | Staking / PowerUp | Governance (Voting / REX) | Resource Mgmt. |
| --------------------------- | ------------------------------ | --------- | ----------------- | ------------------------- | -------------- |
| <img src="https://github.com/user-attachments/assets/639a4ffb-9c40-4f53-9faa-5c26f16a85f8" width="30" alt="EOS icon"> | `EOS` (legacy)<br>`A` (Vaulta) | ✅         | ✅                 | ✅                         | CPU / NET      |
| <img src="https://github.com/user-attachments/assets/016b5567-c17d-4a76-8a78-8ea950d55f9c" width="30" alt="WAX icon">         |                          | ✅         | ✅                 | ✅                         | CPU / NET      |
| <img src="https://github.com/user-attachments/assets/e424ba8d-a8d0-4634-b66e-989794f84386" width="30" alt="Telos icon">    |                         | ✅         | ✅                 | ✅                         | CPU / NET      |

---

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

---

## License

Distributed under the MIT License. See [LICENSE](./LICENSE).
