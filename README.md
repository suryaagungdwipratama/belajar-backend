# Belajar Backend

Repository ini adalah catatan perjalanan saya belajar menjadi backend developer dengan JavaScript / Node.js. Semua latihan dan proyek kecil disimpan di sini, dipisah per fase.

Mulai: Oktober 2026

## Aturan Main

- Commit setiap selesai belajar atau menyelesaikan satu hal kecil.
- Pesan commit harus jelas, contoh: `tambah fungsi hapus tugas di todo-cli`.
- Satu latihan atau proyek kecil = satu folder sendiri di dalam folder fase.
- Proyek besar (mulai Fase 4) dibuat di repository terpisah, lalu ditautkan di bagian "Proyek Utama" di bawah.
- Jangan pernah commit `.env`, password, atau API key.

## Daftar Fase

| Fase | Topik | Folder | Status |
|------|-------|--------|--------|
| 0 | Terminal, Git, persiapan | [fase-0-persiapan](fase-0-persiapan) | [ ] |
| 1 | Dasar JavaScript | [fase-1-javascript](fase-1-javascript) | [ ] |
| 2 | Node.js | [fase-2-nodejs](fase-2-nodejs) | [ ] |
| 3 | Database dan SQL | [fase-3-database-sql](fase-3-database-sql) | [ ] |
| 4 | Express dan REST API | [fase-4-express-rest-api](fase-4-express-rest-api) | [ ] |
| 5 | Testing | [fase-5-testing](fase-5-testing) | [ ] |
| 6 | TypeScript | [fase-6-typescript](fase-6-typescript) | [ ] |
| 7 | Docker, Redis, CI/CD, deployment | [fase-7-tools-profesional](fase-7-tools-profesional) | [ ] |
| 8 | Konsep lanjutan | [fase-8-lanjutan](fase-8-lanjutan) | [ ] |

Ganti `[ ]` menjadi `[x]` kalau satu fase sudah selesai.

## Proyek Utama (Repository Terpisah)

| Proyek | Tautan | Status |
|--------|--------|--------|
| REST API Catatan / To-Do | (isi nanti) | Belum mulai |
| Proyek utama #2 | (isi nanti) | Belum mulai |

## Jurnal Belajar

Catatan harian ada di [catatan/jurnal-belajar.md](catatan/jurnal-belajar.md).

## Roadmap

Roadmap lengkap ada di [roadmap-backend-developer.md](roadmap-backend-developer.md).

## Cara Menjalankan Tiap Latihan

Setiap folder latihan punya instruksinya sendiri. Secara umum:

```bash
cd fase-1-javascript/nama-latihan
npm install   # kalau ada package.json
node index.js
```
