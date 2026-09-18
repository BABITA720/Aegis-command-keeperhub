# 🛡️ Aegis Command

An end-to-end decentralized risk-management platform that combines a high-performance Vercel-hosted frontend interface with a robust KeeperHub-powered backend automation engine for continuous protocol monitoring.

---

## 🚀 Architecture Overview

Aegis Command is structured into two main layers:
1. **Frontend Interface (Vercel):** A modern, responsive dashboard (`Aegis Command`) providing live telemetry, risk metrics, AI assistant integration, and governance tracking.
2. **Automation Engine (KeeperHub):** A background workflow orchestration layer connected to **Aave V3 (Ethereum Sepolia Testnet)** that continuously monitors user health factors, executes conditional logic nodes, and handles automated risk mitigation.

---

## ✨ Key Features

* **Real-Time Health Factor Tracking:** Automatically reads and evaluates user health factors on Aave V3 via KeeperHub workflows.
* **Conditional Logic Execution:** Automated trigger-to-action pipeline that handles risk parameters deterministically.
* **Live Telemetry & Dashboard:** Real-time data streams, gas tracking, and precompile sync displayed on the Vercel-hosted UI.
* **Secure Audit Trail:** Complete execution logs and verification proofs for every automated run cycle.

---

## 🛠️ Tech Stack

* **Frontend:** Next.js / React deployed on **Vercel**
* **Automation & Keeper Nodes:** **KeeperHub** Visual Workflow Builder & MCP Server
* **Blockchain Network:** Ethereum Sepolia Testnet
* **Integrated Protocols:** Aave V3 Lending Pools

---

## 📂 Repository Structure

```text
├── src/                  # Frontend UI components and pages
├── public/               # Assets and static files
├── workflows/            # KeeperHub workflow configurations & execution logs
└── README.md             # Project documentation

