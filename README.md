# <p align="center">🪙 Bokcoin (BOK)</p>

<p align="center">
    <!-- License -->
    <a href="LICENSE">
        <img src="https://img.shields.io/badge/license-BSD3-blue.svg?style=flat-square" alt="License">
    </a>
    <!-- Build Status -->
    <a href="#">
        <img src="https://img.shields.io/badge/build-passing-brightgreen.svg?style=flat-square" alt="Build Status">
    </a>
    <!-- Version -->
    <a href="#">
        <img src="https://img.shields.io/badge/version-v1.0.0-orange.svg?style=flat-square" alt="Version">
    </a>
    <!-- PRs Welcome -->
     <a href="#">
        <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome">
    </a>
</p>

<p align="center">
  <b>Secure. Private. Untraceable.</b><br>
  <i>The cryptocurrency for the future of decentralized finance.</i>
</p>

---

## 🚀 Introduction

**Bokcoin** is a private, decentralized cryptocurrency that keeps your finances confidential and secure. Built on the robust Cryptonote protocol, Bokcoin ensures that you are the only one who controls and sees your funds.

In a world of transparent ledgers, Bokcoin stands apart by using:

- **Ring Signatures**: To obscure the sender.
- **Stealth Addresses**: To hide the receiver.
- **RingCT (Ring Confidential Transactions)**: To hide the amount.

## ✨ Features

- **🔒 True Privacy**: Transactions are untraceable and unlinkable.
- **🛡️ Security First**: Network integrity is protected by proof-of-work.
- **🌍 Decentralized**: No central authority controls the network.
- **💸 Fungibility**: Every unit of currency is interchangeable with another.

## 🛠️ Build & Installation

### Dependencies

Ensure you have the following installed on your system (Ubuntu/Debian example):

```bash
sudo apt update && sudo apt install build-essential cmake pkg-config libboost-all-dev libssl-dev libzmq3-dev libunbound-dev libsodium-dev libunwind8-dev liblzma-dev libreadline6-dev libldns-dev libexpat1-dev doxygen graphviz libpgm-dev qttools5-dev-tools libhidapi-dev libusb-1.0-0-dev libprotobuf-dev protobuf-compiler libudev-dev
```

### Compiling from Source

Clone the repository and build:

```bash
git clone --recursive https://github.com/yourusername/bok-coin.git
cd bok-coin
mkdir build && cd build
cmake ..
make -j$(nproc)
```

The binaries will be located in the `bin/` directory.

## 💻 Usage

### Running the Daemon

Start the daemon to sync with the network:

```bash
./bin/bokcoind
```

### Running the Wallet

Once the daemon is synced (or using a remote node), use the CLI wallet:

```bash
./bin/bokcoin-wallet-cli
```

## 🤝 Contributing

We welcome contributions from the community! Please look at our [CONTRIBUTING.md](CONTRIBUTING.md) file for more details on how to get started.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📄 License

Distributed under the **BSD 3-Clause License**. See [LICENSE](LICENSE) for more information.

---

<p align="center">
  Made with ❤️ by the Bokcoin Team
</p>
