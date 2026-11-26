# Day 0: WSL 2 & Ubuntu Setup

## Environment
- OS: Windows + WSL 2 (Ubuntu)
- Goal: Learning Linux Fundamentals & CLI

## Troubleshooting Log
1. **Error `requires elevation`**
   - Penyebab: PowerShell belum dijalankan sebagai Administrator.
   - Solusi: Jalankan PowerShell dengan *Run as administrator*.
2. **Error `Forbidden (403)` & Ubuntu belum ter-install**
   - Penyebab: Mesin WSL sudah aktif, tapi distribusi Ubuntu gagal ter-download otomatis.
   - Solusi: Install manual lewat PowerShell dengan perintah `wsl --install -d Ubuntu --web-download`.
