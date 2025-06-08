# 🧩 Office 2021 Installer & Activator Guide

Panduan lengkap untuk pemasangan Microsoft Office 2021 secara manual berserta aktivasi dan skrip pembaharuan automatik (auto-renewal).

---

## 📦 Kandungan

- `Office 2021/` — Folder pemasangan Office 2021
- `configuration.xml` — Konfigurasi pemasangan Office
- `Activation_Office.cmd` — Skrip aktivasi Office
- `Auto_Renew_Scripts.bat` — Skrip untuk renew aktivasi automatik
- `Cara Guna Office 2021.txt` — Panduan pemasangan langkah demi langkah

---

## 🛠 Cara Pasang

1. **Pindahkan folder "Office 2021":**
   ```
   Drag folder Office 2021 ke lokasi:
   C:\Program Files\Office 2021
   ```

2. **Buka CMD sebagai Administrator:**
   - Klik kanan pada Start
   - Pilih “Command Prompt (Admin)” atau “Windows Terminal (Admin)”

3. **Jalankan perintah berikut:**
   ```bash
   cd "C:\Program Files\Office 2021"
   setup /configure configuration.xml
   ```

4. **Tunggu proses pemasangan selesai.**

---

## 🔑 Cara Aktifkan

1. **Jalankan skrip `Activation_Office.cmd` sebagai Administrator.**
2. **Tunggu sehingga keluar mesej "Successful".**
3. **Tekan `N` untuk keluar.**

---

## ♻️ Auto Renew Activation

1. Jalankan skrip `Auto_Renew_Scripts.bat` sebagai Administrator.
2. Skrip ini akan aktifkan pembaharuan automatik supaya Office terus aktif.

---

## ⚠️ Nota Penting

- Semua skrip **wajib** dijalankan sebagai **Administrator**.
- Fail ini untuk tujuan pembelajaran. Sila gunakan lesen sah untuk penggunaan jangka panjang.

---

## 📄 Lesen

Projek ini disediakan untuk tujuan pembelajaran sahaja. Segala risiko ditanggung sendiri oleh pengguna.
