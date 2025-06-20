# 🧠 EigenLayer Staking Intelligence Platform

A **full-stack blockchain analytics system** built to process real EigenLayer events, analyze staking behavior, estimate rewards/APR, and expose everything through a robust REST API.

---

## 🎯 Complete Implementation Includes:

### 🟩 Node.js API Server (Express.js)
- ✅ REST API with 3 core endpoints
- ✅ SQLite database with optimized schema + indexes
- ✅ Middleware: rate limiting, security headers, CORS, input validation, error handling
- ✅ Pagination support for scalable responses
- ✅ Cron-based scheduled sync from Python backend

### 🟦 Python Data Processing Engine
- ✅ Blockchain event processor via `Web3.py`
- ✅ EigenLayer subgraph integration
- ✅ Staking pattern recognition
- ✅ APR & reward estimation logic
- ✅ Automated sync scheduler

---

## 🔑 Key Features

- 🔄 **Live data sync** from blockchain + subgraphs  
- 🧪 **Mock reward simulation** for demo environments  
- 🛡️ **Security-first architecture** (rate limits, validation, error handling)  
- 📈 **Analytics-ready endpoints** for APR & staking trends  
- 🗃️ **Optimized SQLite** storage with auto-indexing  
- 🧾 **End-to-end documentation** for setup & usage

---

## 🚀 Quick Start

### 1️⃣ Environment Setup
```bash
cp .env.example .env
npm install
cd scripts && pip install -r requirements.txt
