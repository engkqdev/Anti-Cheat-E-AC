# 🛡️ E-AC (ENGKQ ANTI-CHEAT) - Information

Halo! Ini adalah sistem Anti-Cheat yang saya kembangkan sendiri (**Engkq**). Project ini dibuat untuk membantu para pemilik server SA-MP dalam memberantas cheater dengan sistem yang ringan namun tetap tangguh.

### ✨ Fitur Utama (v0.0.1):
* Kalian bisa check di**Releases**!

---

### 📥 Cara Download
Untuk mendapatkan versi terbaru yang stabil dan siap pakai, silakan ikuti langkah berikut:

1. Pergi ke tab **[Releases](https://github.com/engkqdev/Anti-Cheat-E-AC/releases)** dibagian kanan halaman ini.
2. Pilih versi terbaru (contoh: `Beta v0.0.1`).
3. Pada bagian **Assets**, klik file `eanticheat.inc` untuk mendownloadnya.

### 📝 Cara Pemasangan
1. Masukkan file `eanticheat.inc` yang sudah didownload ke folder `pawno/include/` server kamu.
2. Ganti structure `blacklist` dengan structure system banned didatabase kamu!
3. Tambahkan baris `#include <eanticheat>` dibagian atas script Gamemode kamu.
4. Pastikan koneksi MySQL kamu menggunakan variabel `g_SQL` agar sistem ban otomatis berjalan lancar.
5. *Compile* gamemode kamu dan jalankan servernya!

---
**Dibuat oleh Engkq.**
*Jika menemukan bug atau mau saran fitur, silakan buka 'Issue' direpository ini!*
