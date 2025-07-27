# 🚀 Soundness Node Setup Guide

Easily install and manage your Soundness node with the following commands. Whether you're just getting started or updating your setup — this guide has you covered

**🔧 System Update**
```bash
sudo apt update && sudo apt upgrade -y
```
**📦 Install Soundness Layer**
```bash
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
```
**🦀 Install Rust (required)**
```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs/ | sh
```
**Then reload your shell environment:**
```bash
source ~/.bashrc
```
# ⚙️ Manage Soundness Layer
**✅ Install**
```bash
soundnessup install
```
**🔄 Update**
```bash
soundnessup update
```
# 🔐 Key Management
```bash
soundness-cli generate-key --name my-key
```
```bash
soundness-cli export-key --name my-key
```
**👾 Made with ❤️ by Darkcandy**
