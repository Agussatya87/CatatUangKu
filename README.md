# 🛍️ CatatUangKu – Telegram Expense Tracker

CatatUangKu adalah bot Telegram yang membantu mencatat pengeluaran belanja dengan dua cara:
- 📸 Membaca struk belanja (OCR + AI parsing).
- ✍️ Input manual melalui chat.
- Bot ini menyimpan data ke PostgreSQL dan menyediakan laporan harian, mingguan, bulanan, serta fitur download laporan dalam format Excel.

## ✨ Fitur Utama

- 📸 Scan Struk Belanja – Kirim foto struk, bot akan membaca toko, total, daftar barang, dan tanggal transaksi.
- ✍️ Input Manual – Tulis langsung pembelian (misalnya: beli telur 20000 di Toko Mbak Ita).
- 📊 Laporan Otomatis – Cek laporan dengan perintah /laporan hari ini, /laporan minggu ini, atau /laporan bulan ini.
- 📥 Download Excel – Ambil laporan dalam bentuk file .xlsx.
- 🗑️ Reset Data – Hapus semua catatan belanja dengan /reset.
- 🤖 Integrasi AI – Menggunakan Google Gemini untuk parsing struk dan input teks agar lebih fleksibel.

## 🛠️ Tech Stack

- Automation: n8n
- Database: PostgreSQL
- Messaging Platform: Telegram Bot API
- AI Model: Google Gemini (Vision + NLP)
- File Export: XLSX via n8n

## 📌 Command Bot

- /start → Intro bot
- /help → Panduan penggunaan
- /laporan hari ini → Laporan harian
- /laporan minggu ini → Laporan mingguan
- /laporan bulan ini → Laporan bulanan
- download laporan → Kirim file Excel laporan
- /reset → Hapus semua data

[👉 Coba Bot di Telegram](https://t.me/LaporanBelanjaHarian1_bot)
