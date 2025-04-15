# 🪙 Solana Hello World Program

A minimal Rust-based smart contract deployed on the Solana Devnet that logs "Hello, Solana!".

---

## 📁 Project Structure

mysolanahelloworld/ ├── Cargo.toml ├── src/ │ └── lib.rs ├── screenshots/ │ ├── cli-version.png │ ├── wallet-address.png │ ├── airdrop.png │ └── deployment-success.png ├── target/ └── README.md


---

## ⚙️ Setup Instructions

### 1. Install Solana CLI

```bash
sh -c "$(curl -sSfL https://release.solana.com/stable/install)"

solana-keygen new
solana config set --url https://api.devnet.solana.com
solana airdrop 2

cargo build-sbf
solana program deploy target/deploy/mysolanahelloworld.so

🔑 Program Info
Program ID: 5fwysJM2AHPtde1YU4X2Vwt4Mh2FyFTcz6e8Pua8AzLA

Wallet Address: 3yXCpa8ik2cUjp2drgQSDeQqLp7i1yXBPfwY2yVWxy7X

📸 Screenshots
✅ CLI Version

✅ Wallet Address

✅ Airdrop

✅ Deployment Success


---

