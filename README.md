# Blockchain Ajo / Esusu DApp 💰

A decentralized cooperative savings platform built to bring transparency, trust, and automation to traditional group savings (Ajo/Esusu) systems using **blockchain technology**.

This project is a collaboration between:
- **Ikechi Emmanuel Chiemela** – Full-Stack Developer & Ethical Hacker  
- **Chukwuemeka Precious** – Blockchain Engineer  

---

## 🚀 Project Overview

**Blockchain Ajo/Esusu** enables users to collectively contribute funds into shared pools with clearly defined goals, schedules, and payout structures — all managed by **smart contracts**.  
Every transaction is **immutable**, **auditable**, and **transparent** on the blockchain, eliminating the risk of mismanagement or fraud.

This system blends **decentralized finance (DeFi)** concepts with real-world cooperative culture.

---

## 🧩 Core Features

| Feature | Description |
|----------|-------------|
| **Decentralized Groups** | Users can create or join savings groups (Ajo/Esusu cycles). |
| **Smart Contract Automation** | Deposits, payouts, and penalties are handled by Ethereum smart contracts. |
| **Wallet Integration** | MetaMask or WalletConnect used for identity and transactions. |
| **Activity Dashboard** | Real-time tracking of contributions and payouts. |
| **Transaction Ledger** | Transparent record of every contribution and withdrawal. |
| **Security Layer** | Includes smart-contract auditing, penetration testing, and event-based monitoring. |

---

## 🧠 System Architecture

### **High-Level Flow**
1. **User Registration:** Connects wallet, sets up identity (Web3 login).  
2. **Group Creation:** User defines group rules — amount, participants, payout order.  
3. **Smart Contract Deployment:** Automatically generates a new contract for that group.  
4. **Contribution Cycle:** Users send funds via blockchain transactions.  
5. **Automated Payout:** Contract verifies contributions and releases payout to next recipient.  
6. **Security Auditing Layer:** Logs every transaction and anomaly for review.

### **System Diagram**
```mermaid
flowchart TD
    A[User Wallet] -->|Connects| B[DApp Frontend]
    B -->|API Calls| C[Node.js Backend]
    C -->|Deploys| D[Smart Contract]
    D --> E[Blockchain Network]
    D --> F[Security Monitor / Logger]
    F --> G[Admin Dashboard]
