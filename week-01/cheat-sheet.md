# Week 1: Linux CLI Cheat Sheet

## Navigasi & Struktur Folder
- `pwd` : Cek lokasi folder saat ini (*Print Working Directory*)
- `ls` : Lihat isi folder (`ls -la` untuk detail + file tersembunyi)
- `cd nama-folder` : Masuk ke folder (`cd ..` untuk mundur 1 tingkat)

## Manipulasi File & Folder
- `mkdir nama-folder` : Bikin folder baru
- `touch nama-file` : Bikin file kosong baru
- `cp asal tujuan` : Copy file (tambah `-r` untuk copy folder)
- `mv asal tujuan` : Pindah atau rename file/folder (`.` = folder saat ini)
- `rm nama-file` : Hapus file permanen (`rm -r nama-folder` untuk hapus folder)

## Baca & Edit File
- `nano nama-file` : Edit file (`Ctrl+O` lalu `Enter` untuk save, `Ctrl+X` untuk keluar)
- `cat nama-file` : Tampilkan isi file langsung di terminal

## Alur Push ke GitHub
- `git status` : Cek perubahan file
- `git add .` : Siapkan semua perubahan
- `git commit -m "pesan"` : Simpan catatan perubahan
- `git push` : Kirim ke GitHub
