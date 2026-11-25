# GTA-V-100-file
GTA V 100% Story Mode Save File for PS4 HEN
# GTA V 100% Save File (PS4 HEN / Jailbreak)

A complete 100% Story Mode save file for Grand Theft Auto V on PlayStation 4 (HEN / Jailbreak). Includes instructions on how to install via **Apollo Save Tool** and how to change the **CUSA Region ID**.

*(File save mode cerita 100% lengkap untuk Grand Theft Auto V di PlayStation 4 (HEN / Jailbreak). Dilengkapi panduan pemasangan lewat **Apollo Save Tool** dan cara mengubah **kode region CUSA**.)*

---

## 🇬🇧 English Instructions

### 📋 Prerequisites
* Jailbroken PS4 (HEN / GoldHEN enabled).
* **Apollo Save Tool** installed on your PS4.
* A USB Flash Drive (formatted as **FAT32** or **exFAT**).
* An existing GTA V save file on your PS4 (recommended, so you know your exact CUSA ID).

### 🔄 Step 1: Check & Change CUSA Region ID (If Needed)
Different game regions use different CUSA codes (e.g., `CUSA00419` for EU/Asia, `CUSA00411` for US).
1. **Find your game's CUSA code:**
   * Check your GTA V game icon on the PS4 home screen (press **Options > Information** to see the Title ID, or check the folder name inside `/user/home/<User_ID>/savedata/`).
2. **Prepare the folder on your USB drive:**
   * Create the following folder structure on your USB drive:
     `PS4\APOLLO\SAVEDATA\<Your_CUSA_ID>\`
     *(Example: `PS4\APOLLO\SAVEDATA\CUSA00419\`)*
   * **Important:** If the downloaded save folder has a different CUSA name (e.g., `CUSA00411`), simply **rename the folder** to match your game's CUSA ID (`CUSA00419`), then place the save files inside it.

### 🚀 Step 2: Install & Resign via Apollo Save Tool
1. **Plug the USB drive** into your PS4 and launch **Apollo Save Tool**.
2. Go to **USB Saves** (make sure your save appears in the list).
3. Select the **Grand Theft Auto V (100% Save)** entry.
4. Choose **Copy save game to HDD** (Apollo will automatically resign it to your current PS4 user profile).
   * *(Optional)* If you still get a region error in-game, go to **HDD Saves** in Apollo, select the GTA V save, and choose **Apply Changes & Resign** to ensure the `PARAM.SFO` matches your account and CUSA ID.
5. **Launch GTA V:** Open the game, press **Options**, go to **Game > Load Game**, and select the 100% save slot.

---

## 🇮🇩 Panduan Bahasa Indonesia

### 📋 Persiapan
* PS4 HEN / GoldHEN yang sudah aktif.
* Aplikasi **Apollo Save Tool** terpasang di PS4.
* USB Flashdisk (format **FAT32** atau **exFAT**).
* File save GTA V bawaan di PS4 kamu (disarankan sudah ada minimal 1 save agar kode CUSA game kamu mudah dicek).

### 🔄 Langkah 1: Cek & Ubah Kode Region CUSA (Jika Berbeda)
Setiap region game memiliki kode CUSA yang berbeda (contohnya `CUSA00419` untuk region Asia/Eropa atau `CUSA00411` untuk region US).
1. **Cek kode CUSA game kamu:**
   * Arahkan kursor ke ikon game GTA V di menu utama PS4, tekan tombol **Options > Information** untuk melihat Title ID (kode CUSA), atau cek lewat folder `/user/home/<ID_User>/savedata/`.
2. **Siapkan struktur folder di Flashdisk:**
   * Buat susunan folder berikut di dalam flashdisk:
     `PS4\APOLLO\SAVEDATA\<Kode_CUSA_Kamu>\`
     *(Contoh: `PS4\APOLLO\SAVEDATA\CUSA00419\`)*
   * **Penting:** Jika folder save yang kamu unduh memiliki kode CUSA berbeda (misalnya `CUSA00411`), cukup **ubah nama foldernya (Rename)** sesuai kode CUSA game kamu (`CUSA00419`), lalu masukkan isi file save ke dalamnya.

### 🚀 Langkah 2: Pasang & Resign via Apollo Save Tool
1. **Colokkan flashdisk** ke PS4 lalu buka aplikasi **Apollo Save Tool**.
2. Masuk ke menu **USB Saves** (pastikan save GTA V dari flashdisk terbaca).
3. Pilih daftar **Grand Theft Auto V (100% Save)**.
4. Pilih **Copy save game to HDD** (Apollo akan otomatis me-*resign* file tersebut agar cocok dengan akun user PS4 kamu).
   * *(Opsional)* Jika saat masuk game save masih belum terbaca karena perbedaan region, buka menu **HDD Saves** di Apollo, pilih save GTA V tersebut, lalu pilih **Apply Changes & Resign** agar data `PARAM.SFO` menyesuaikan akun dan kode CUSA kamu.
5. **Jalankan GTA V:** Buka game, tekan **Options**, masuk ke **Game > Load Game**, lalu muat slot save 100%.

---

### 💡 Notes / Catatan
* **Decrypted vs Encrypted Saves:** Apollo Save Tool works best with decrypted save files placed in `PS4\APOLLO\SAVEDATA\`. If the save is encrypted (`PS4\SAVEDATA\<PSN_ID>\<CUSA>\`), Apollo can still detect it under **USB Saves** and resign it directly to your HDD. *(Apollo Save Tool paling optimal membaca save hasil decrypt di folder `PS4\APOLLO\SAVEDATA\`. Namun jika file save masih terenkripsi di folder `PS4\SAVEDATA\<ID_PSN>\<CUSA>\`, Apollo tetap bisa mendeteksinya di menu **USB Saves** dan langsung menyalinnya ke HDD).*
* **Backup:** Always back up your existing GTA V save in **HDD Saves > Copy save game to USB** before overwriting. *(Selalu backup save lama kamu lewat menu **HDD Saves > Copy save game to USB** sebelum menimpa data).*
