# TOKO GATGETIN — n8n Telegram AI Bot

Workflow otomatisasi customer service Toko Gatgetin menggunakan n8n, Telegram Bot, dan Google Sheets.

## Fitur
- Balas chat customer otomatis dari Telegram
- Cek produk dari Google Sheets
- Catat pesanan ke Google Sheets
- Notifikasi admin

## Arsitektur
Telegram → n8n → Google Sheets → Telegram
[Arsitektur Workflow](docs/workflow-gatgetin.png)

## Cara Pakai

1. Import file workflow:
   - Buka n8n
   - Import `workflows/Toko Gatgetin.json`

2. Buat ulang credentials di n8n:
   - Telegram API
   - Google Sheets OAuth

3. Jalankan workflow.

## Catatan Keamanan
File ini tidak menyertakan credentials. Semua API harus diisi ulang di n8n masing-masing.

---
Dibuat untuk kebutuhan Matkul Jaringan Syaraf Tiruan (JST) dan implementasi ke Dosennya Langsung.