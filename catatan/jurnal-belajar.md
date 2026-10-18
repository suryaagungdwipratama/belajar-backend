# Jurnal Belajar

Tulis beberapa baris setiap selesai belajar. Tidak perlu panjang, yang penting jujur dan rutin. Catatan terbaru taruh di paling atas.

---

## Template (salin untuk setiap hari)

### YYYY-MM-DD | Fase X | Topik

- **Yang saya pelajari:**
- **Yang saya buat / commit:**
- **Yang masih membingungkan:**
- **Rencana berikutnya:**

---

## Catatan

### 2026-10-17 | Fase 0 | Memulai

- **Yang saya pelajari:** menyusun roadmap backend developer.
- **Yang saya buat / commit:** membuat repository `belajar-backend`.
- **Yang masih membingungkan:** belum ada, baru mulai.
- **Rencana berikutnya:** pasang Node.js dan Git, lalu mulai dasar JavaScript.

### 2026-10-17 | Fase 1 | Variabel dan tipe data

- **Yang saya pelajari:** const dan let, template literal, typeof
- **Yang saya buat / commit:** latihan-variabel
- **Yang masih membingungkan:**
  - Tulisan `${nama}` tampil apa adanya, bukan isi variabelnya. Ternyata saya memakai tanda kutip biasa, padahal template literal harus memakai backtick.
  - Setelah `semester = 4`, kedua `console.log` menampilkan 4. Ternyata JavaScript membaca kode dari atas ke bawah, jadi `semester = 4` sudah dijalankan sebelum kedua `console.log`. Supaya perubahan 3 ke 4 terlihat, `semester = 4` harus ditaruh di antara dua `console.log`.
- **Rencana berikutnya:** latihan percabangan if/else

### 2026-10-18 | Fase 1 | Percabangan (if / else if / else)

* Yang saya pelajari:
  - Operator perbandingan: `>` lebih besar, `<` lebih kecil, `>=` lebih besar atau sama dengan, `<=` lebih kecil atau sama dengan, `===` sama dengan
  - Cara kerja `if`, `else if`, dan `else`
  - `else if` dicek berurutan dari atas, berhenti begitu ada satu kondisi yang benar
* Yang saya buat / commit:
  - latihan-percabangan: cek umur untuk KTP dan huruf mutu, semua angka batas sudah diuji
* Yang masih membingungkan:
  - Tadinya bingung alur pintu 1, 2, 3, sekarang paham karena JavaScript membaca dari atas dan berhenti di kondisi pertama yang benar
* Rencana berikutnya:
  - Perulangan (loop)