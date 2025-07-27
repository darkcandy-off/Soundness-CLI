# 🚀 Soundness Node Setup Guide

Easily install and manage your Soundness node with the following commands. Whether you're just getting started or updating your setup — this guide has you covered

```🔧 System Update
sudo apt update && sudo apt upgrade -y
```

```📦 Install Soundness Layer
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
```
```🦀 Install Rust (required)
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs/ | sh
```
```Then reload your shell environment:
source ~/.bashrc
```
# ⚙️ Manage Soundness Layer
```✅ Install
soundnessup install
```
```🔄 Update
soundnessup update
```
# 🔐 Key Management
```bash
soundness-cli generate-key --name my-key
```
```bash
soundness-cli export-key --name my-key
```
