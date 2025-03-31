# Soundness Testnet Registration Guide

## Overview
This guide provides step-by-step instructions on how to register for the Soundness Testnet and generate your key.

## Registration Steps

### 1. Submit Your Email
Visit the registration link below and enter your email:
[Soundness Testnet Registration](https://soundness.xyz/)

### 2. Install Required Dependencies
Run the following commands to update your system and install the required dependencies:
```sh
sudo apt update && sudo apt upgrade -y
```

### 3. Install Soundness Layer
Execute the following command to install the Soundness Layer:
```sh
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
```

### 4. Install Rust
Run the following command to install Rust:
```sh
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs/ | sh
source ~/.bashrc
```

### 5. Install and Update Soundness CLI
```sh
soundnessup install
soundnessup update
```

### 6. Generate Your Key
Run the following command to generate your key:
```sh
soundness-cli generate-key --name my-key
```

### 7. View and Save Your Seed Phrase
To view your seed phrase and public key, use the command:
```sh
soundness-cli export-key --name my-key
```
Make sure to **save your seed phrase and public key** securely.

### 8. Join the Soundness Discord Server
Join the official Discord server using the link below:
[Soundness Discord](https://discord.gg/NbStGdsh)

### 9. Submit Your Public Key
Once inside the Discord server, navigate to `#Testnet-access` and submit your **public key**.

## 🎉 Done!
You have successfully registered for the Soundness Testnet!

---

## Additional Details
- Keep your seed phrase and public key safe; do not share them publicly.
- Stay active in the Discord server for updates and support.
- If you encounter any issues, refer to the community resources or ask for help in Discord.


