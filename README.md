# Instalasi Windows 7 Super Lite di Proxmox 🚀

Panduan singkat dan praktis untuk menginstall Windows 7 Super Lite di Proxmox agar disk VirtIO bisa terbaca dengan lancar!

---

## Langkah 1: Siapkan ISO 📁
- ISO *Windows 7 Super Lite*
- ISO *VirtIO Drivers* (disarankan: virtio-win-0.1.171.iso)

---

## Langkah 2: Buat VM di Proxmox ⚙
- OS Type: *Microsoft Windows*
- Version: *7/2008R2 (64-bit)*
- Tambahkan *2 CD-ROM*:
  - CD pertama: ISO Windows
  - CD kedua: ISO VirtIO

---

## Langkah 3: Mulai Instalasi 💿
- Boot dari ISO Windows
- Saat masuk pemilihan disk, klik *"Load Driver"*
- Pilih folder:  
  vioscsi > w7 > amd64 ✅
- Klik *OK*, disk akan muncul!

---

## Langkah 4: Lanjutkan Instalasi ▶
- Pilih disk → Klik *Next*
- Tunggu hingga instalasi selesai

---

## Langkah 5: Install Driver Tambahan 🧰
Setelah masuk desktop:
- Buka CD VirtIO di Windows Explorer
- Jalankan: virtio-win-gt-x64.exe
- Install semua driver (LAN, VGA, dll)

---

## Done! Selamat menikmati Windows 7 Super Lite di Proxmox! 🎉
