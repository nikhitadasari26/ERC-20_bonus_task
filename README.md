# MyToken (MTK) – ERC-20 Token Smart Contract

## 📝 Overview
MyToken (MTK) is a simple ERC-20 token implemented in Solidity.  
It demonstrates the core behavior of Ethereum-based digital assets, including sending tokens, checking balances, and using allowances for delegated transfers.  
The contract follows the ERC-20 standard and is fully compatible with wallets and dApps.

---

## 🪙 Token Information
- **Name:** MyToken  
- **Symbol:** MTK  
- **Decimals:** 18  
- **Total Supply:** 1,000,000 MTK  
- **Standard:** ERC-20  

---

## ⚡ Key Features
- **Transfer:** Send MTK between accounts.  
- **Balance Tracking:** View token balances using `balanceOf`.  
- **Allowances:** Approve another wallet to spend tokens for you.  
- **Delegated Transfers:** Execute spending via `transferFrom`.  
- **Events:** Emits `Transfer` and `Approval` events for transparency.  
- **Safety Checks:** Prevents zero-address transfers and insufficient balance errors.

---

## 🛠️ Technology Used
- **Solidity (v0.8.x)**  
- **Remix IDE**  
- **Remix VM (Local Test Blockchain)**  

---

## 🚀 How to Deploy
1. Open **Remix IDE** → https://remix.ethereum.org/  
2. Create a new file named **MyToken.sol**  
3. Go to the **Solidity Compiler** and select version **0.8.x**  
4. Click **Compile MyToken.sol**  
5. Open **Deploy & Run Transactions**  
   - Environment: **Remix VM**
   - Enter total supply: `1000000000000000000000000` (1 million MTK with 18 decimals)  
   - Click **Deploy**

---

## 📘 Usage Examples

### **1. Transfer Tokens**
Send tokens to another address:
- Function: `transfer(recipient, amount)`
- Amount for 1 MTK: `1000000000000000000`
- Click **transact**

### **2. Check Balance**
- Function: `balanceOf(address)`
- Shows token holdings of any wallet.

### **3. Approve a Spender**
Authorize another wallet to spend tokens:
- Function: `approve(spender, amount)`
- Click **transact**

### **4. Delegated Transfer**
Using the approved allowance:
- Switch to the spender account  
- Function: `transferFrom(from, to, amount)`  
- Click **transact**

---

## 🎯 What I Learned
- Understanding ERC-20 token architecture  
- How smart contracts store balances and allowances  
- Importance of blockchain events  
- Secure coding practices for token transfers  
- How Remix simulates blockchain interactions

---

## 📄 License
This project is licensed under the **MIT License**.
