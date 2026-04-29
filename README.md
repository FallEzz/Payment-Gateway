
# 🚀 PAYMENT GATEWAY QRIS
### by <b>FallZx Store</b>

<p align="center">
  <img src="https://img2.pixhost.to/images/7526/720139624_marin-kitagawa.jpg" alt="Thumbnail" width="80%" />
</p>

<p align="center">
  <b>Automatic Panel Creator • QRIS Payment • Fast & Simple</b>
</p>

---

## 👑 About Project

<b>buy pansl</b> adalah sistem otomatis untuk membuat panel <b>Pterodactyl</b> menggunakan <b>Express.js</b> yang terintegrasi dengan <b>Payment Gateway QRIS (Pakasir)</b>.

> User bayar → Sistem verifikasi → Panel langsung dibuat otomatis ⚡

### Cocok untuk:
- Jualan panel hosting  
- Auto store  
- Reseller panel  
- Integrasi bot / website  

---

## 🏷️ Credits

- 🏪 Remake & Development: <b>FallZx Store</b>  
- 🎯 Original Creator: <b>Fik Projects</b>

<b>Note:</b> Bebas digunakan & dimodifikasi, wajib menyertakan credit.

---

## ✨ Features

- ⚡ Auto Create User & Server Pterodactyl  
- 💳 Payment Gateway QRIS (Pakasir)  
- 🔄 Auto Check Payment (Webhook & Manual)  
- 📊 Status transaksi:
  - <b>pending</b>
  - <b>success</b>
  - <b>failed</b>
  - <b>canceled</b>
- 🤖 Notifikasi Telegram realtime  
- 👑 Support Admin & Reseller Panel  
- 📦 Multi produk (1GB – Unlimited)  
- 🔌 API Ready (Frontend & Backend)  
- 🛠️ Auto detect panel maintenance  
- 🧠 In-memory database (Map)  
- 🌐 Webhook Support  

---

## 🧠 System Flow

1. User memilih produk  
2. Sistem generate <b>Order ID</b>  
3. QRIS dibuat dari Pakasir  
4. Status: <b>PENDING</b>  
5. User melakukan pembayaran  
6. Sistem cek via API / Webhook  
7. Jika <b>SUCCESS</b>:
   - Create user panel  
   - Create server  
   - Kirim credential login  
   - Notifikasi Telegram  
8. Done ✅  

---

## 📦 Product List

| Code  | Deskripsi |
|------|----------|
| 1gb  | 1GB Panel |
| 2gb  | 2GB Panel |
| 3gb  | 3GB Panel |
| 4gb  | 4GB Panel |
| 5gb  | 5GB Panel |
| unli | Unlimited Panel |
| admin | Admin Panel |

---

## 🗂️ Project Structure

```bash
project/
├─ public/
│  ├─ home.html
│  ├─ payment.html
│  ├─ success.html
│  └─ history.html
├─ server.js
├─ package.json
├─ .env
└─ README.md
