# BitForge SkySis  
Craft Bitcoin. Control Lightning. Command the Chain.

BitForge SkySis is a lightweight Bitcoin & Lightning toolkit designed for power users and developers.  
It provides a clean web interface for building, signing, and broadcasting Bitcoin transactions, managing PSBT files, interacting with hardware wallets, and monitoring the mempool in real time.

---

## 🚀 Features

- **Bitcoin Transaction Builder**  
  Create multi‑output transactions, calculate fees, generate PSBT and raw HEX.

- **PSBT Support**  
  Export unsigned PSBT, import signed PSBT, broadcast final transactions.

- **Hardware Wallet Integration**  
  Coldcard (PSBT), Ledger (WebHID), Trezor (WebUSB).

- **RBF Fee Bumping**  
  Increase transaction fees for stuck transactions.

- **Lightning Tools**  
  Generate LNURL‑pay and BOLT11 invoices.

- **Mempool Dashboard**  
  Live mempool stats, fee buckets, vsize load, WebSocket updates.

---

## 🏗 Tech Stack

- **Frontend:** Next.js, React, TailwindCSS  
- **Backend:** Python (Flask), Bitcoinlib  
- **Realtime:** Socket.IO  
- **Deploy:** Vercel (frontend), Fly.io (backend)

---

## 📦 Quick Start

```bash
git clone https://github.com/WebSkyGaTeE/BitForge-SkySis
cd BitForge-SkySis
docker-compose up --build
```

Frontend → http://localhost:3000  
Backend → http://localhost:5000  

---

## 🔧 Environment Variables

### Backend
```
API_KEY=your_api_key
WIF_KEY=your_private_key
ADDR_TYPE=p2wpkh
ENABLE_RBF=1
```

### Frontend
```
NEXT_PUBLIC_BACKEND_WS=https://your-backend.fly.dev
BACKEND_URL=https://your-backend.fly.dev
API_KEY=your_api_key
```

---

## 📜 License
MIT License

---

## 👤 Author
**WebSkyGaTeE (Siso)**  
BitForge SkySis — 2026
