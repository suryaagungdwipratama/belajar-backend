# Roadmap Backend Developer (JavaScript / Node.js)

Disusun untuk mahasiswa semester 3 Teknologi Informasi. Perkiraan total waktu: **12-18 bulan** dengan belajar konsisten 1-2 jam per hari. Targetnya siap melamar magang di sekitar bulan ke-8 sampai ke-10.

---

## Prinsip Belajar

1. **Satu hal dalam satu waktu.** Jangan loncat bahasa atau framework sebelum yang sekarang bisa dipakai membuat sesuatu.
2. **Proyek lebih penting daripada tutorial.** Tiap tahap harus diakhiri dengan sesuatu yang kamu bangun sendiri.
3. **Baca dokumentasi resmi.** Video bagus untuk pengenalan, dokumentasi bagus untuk pemahaman.
4. **Commit ke GitHub tiap hari belajar.** Riwayat commit adalah portofolio yang jujur.
5. **Konsisten mengalahkan intensitas.** 1 jam tiap hari lebih baik daripada 10 jam sekali seminggu.

---

## Fase 0: Persiapan (Minggu 1-2)

**Yang dipelajari**
- Terminal / command line dasar (`cd`, `ls`, `mkdir`, `cp`, `mv`, `rm`)
- Git dan GitHub: `init`, `add`, `commit`, `push`, `pull`, `branch`, `merge`
- Code editor (VS Code) dan ekstensi dasarnya
- Instalasi Node.js (versi LTS)

**Target selesai**
- Punya akun GitHub dengan 1 repository berisi README
- Nyaman membuat branch dan melakukan merge

---

## Fase 1: Dasar JavaScript (Minggu 3-8)

**Yang dipelajari**
- Variabel (`let`, `const`), tipe data, operator
- Percabangan dan perulangan
- Function, arrow function, scope, closure
- Array dan object, method `map`, `filter`, `reduce`, `find`, `some`, `every`
- Destructuring, spread/rest operator, template literal
- **Asynchronous:** callback, Promise, `async/await`
- Modul: `import` / `export` (ES Modules)
- Error handling: `try/catch`, melempar error sendiri
- Dasar Programming: struktur data (array, stack, queue, hash map) dan algoritma dasar (sorting, searching)

**Sumber**
- javascript.info
- MDN Web Docs
- freeCodeCamp (JavaScript Algorithms and Data Structures)

**Proyek**
- Kalkulator di terminal
- To-do list di command line
- Pengelola data mahasiswa sederhana (tambah, hapus, cari)

**Target selesai**
- Bisa menjelaskan perbedaan callback, Promise, dan async/await
- Bisa menyelesaikan soal latihan level mudah di LeetCode / HackerRank

---

## Fase 2: Node.js (Minggu 9-12)

**Yang dipelajari**
- Cara kerja Node.js, event loop (konsep dasar)
- npm, `package.json`, `package-lock.json`, dependency vs devDependency
- Modul bawaan: `fs`, `path`, `http`, `events`
- Membuat server HTTP tanpa framework
- Variabel lingkungan dengan `.env` (paket `dotenv`)
- Dasar HTTP: method, status code, header, body, request/response cycle
- Format JSON

**Proyek**
- Pencatat pengeluaran yang menyimpan data ke file JSON
- Server HTTP sederhana yang mengembalikan data JSON

**Target selesai**
- Bisa membuat server tanpa framework dan paham apa yang terjadi di dalamnya

---

## Fase 3: Database dan SQL (Minggu 13-18)

**Yang dipelajari**
- Konsep database relasional: tabel, baris, kolom, primary key, foreign key
- SQL: `SELECT`, `INSERT`, `UPDATE`, `DELETE`, `WHERE`, `ORDER BY`, `LIMIT`
- `JOIN` (inner, left), `GROUP BY`, `HAVING`, agregasi
- Relasi: one-to-one, one-to-many, many-to-many
- Normalisasi dasar
- Index dan kenapa index mempercepat query
- Transaction dan konsep ACID
- Migrasi database

**Pilihan database:** PostgreSQL (disarankan) atau MySQL.

**Sumber**
- Dokumentasi resmi PostgreSQL
- SQLBolt dan PGExercises (latihan interaktif)

**Proyek**
- Rancang database untuk perpustakaan atau toko online kecil (minimal 4 tabel berelasi), tulis query-nya langsung dengan SQL

**Target selesai**
- Bisa menulis query dengan beberapa `JOIN` tanpa melihat contekan
- Bisa menggambar ERD sederhana

---

## Fase 4: Express.js dan REST API (Minggu 19-26)

**Yang dipelajari**
- Routing, middleware, struktur folder (routes, controllers, services, models)
- Prinsip REST: resource, method, status code yang tepat
- Validasi input (Zod, Joi, atau express-validator)
- Error handling terpusat
- Menghubungkan ke database (driver `pg` / `mysql2`, lalu ORM seperti Prisma atau Sequelize)
- Autentikasi: hashing password (bcrypt), JWT, session
- Otorisasi: role dan kepemilikan data
- Pagination, filtering, sorting
- CORS, rate limiting, dan header keamanan dasar (Helmet)
- Dokumentasi API (Swagger / OpenAPI atau koleksi Postman)

**Proyek utama #1: REST API Catatan / To-Do**
- Register, login, logout
- CRUD catatan milik masing-masing pengguna
- Validasi, error handling, pagination
- Dokumentasi API dan README yang rapi
- Deploy ke layanan gratis (Render, Railway, atau sejenisnya)

**Target selesai**
- API berjalan online dan bisa diakses lewat Postman
- Tidak ada password tersimpan dalam bentuk teks biasa

---

## Fase 5: Testing dan Kualitas Kode (Minggu 27-30)

**Yang dipelajari**
- Unit test dan integration test (Jest atau Vitest, Supertest untuk API)
- Konsep test yang baik: arrange, act, assert
- ESLint dan Prettier
- Konvensi commit dan pesan commit yang jelas
- Dasar code review: membaca dan mengomentari kode orang lain

**Latihan**
- Tambahkan test ke proyek #1 hingga mencakup endpoint utama

**Target selesai**
- Test bisa dijalankan dengan satu perintah dan lolos

---

## Fase 6: TypeScript (Minggu 31-34)

**Yang dipelajari**
- Tipe dasar, interface, type alias
- Generic dasar
- Union dan intersection type
- Konfigurasi `tsconfig.json`
- Memakai TypeScript di proyek Express

**Latihan**
- Tulis ulang proyek #1 dengan TypeScript

**Catatan:** mulai fase ini hanya setelah JavaScript terasa kokoh. Banyak perusahaan memakai TypeScript, jadi ini nilai tambah besar.

---

## Fase 7: Tools Profesional (Minggu 35-42)

**Yang dipelajari**
- **Linux:** perintah dasar, permission, proses, log
- **Docker:** image, container, `Dockerfile`, `docker-compose` (aplikasi + database)
- **Redis:** konsep cache, menyimpan sesi, rate limiting
- **CI/CD dasar:** GitHub Actions untuk menjalankan test otomatis
- **Deployment:** VPS dasar, reverse proxy (Nginx), HTTPS, environment production
- **Logging dan monitoring dasar**

**Proyek utama #2: Aplikasi Lebih Kompleks**
Pilih salah satu:
- Sistem e-commerce sederhana (produk, keranjang, pesanan, pembayaran simulasi)
- Sistem reservasi (jadwal, pemesanan, pembatalan)
- Platform blog / forum (user, post, komentar, like)

Syaratnya:
- Berjalan dengan Docker Compose
- Ada test otomatis yang jalan di GitHub Actions
- Memakai caching di minimal satu endpoint
- Dokumentasi lengkap (README, diagram arsitektur, ERD, cara menjalankan)

---

## Fase 8: Konsep Lanjutan (Bulan ke-10 dan seterusnya)

**Yang dipelajari bertahap**
- Desain sistem dasar: load balancer, caching, replikasi, antrian pesan
- Message queue (RabbitMQ atau BullMQ)
- WebSocket untuk fitur real-time
- Upload file dan penyimpanan objek (S3-compatible)
- Arsitektur: monolith vs microservices (pahami trade-off-nya)
- GraphQL (sebagai tambahan wawasan)
- Database NoSQL (MongoDB) dan kapan memakainya
- Keamanan lanjutan: OWASP Top 10
- Optimasi query dan profiling performa

---

## Persiapan Karir

**Portofolio (minimal)**
- 2 proyek utama yang sudah dideploy dan terdokumentasi
- 3-5 proyek kecil sebagai bukti kebiasaan membangun
- Profil GitHub rapi: foto, bio, pinned repository

**Persiapan lamaran magang**
- CV 1 halaman, fokus pada proyek dan teknologi yang dikuasai
- Latihan soal algoritma level mudah-menengah secara rutin
- Latihan menjelaskan proyekmu sendiri: kenapa memilih teknologi itu, apa tantangannya, apa yang akan diperbaiki
- Profil LinkedIn aktif
- Ikut komunitas, hackathon, atau kontribusi open source kecil (perbaikan dokumentasi pun dihitung)

**Soft skill**
- Menulis dokumentasi yang jelas
- Bertanya dengan baik: jelaskan masalah, apa yang sudah dicoba, error yang muncul
- Terbiasa menerima masukan saat code review

---

## Ringkasan Linimasa

| Fase | Topik | Perkiraan Waktu |
|------|-------|-----------------|
| 0 | Terminal, Git, persiapan | Minggu 1-2 |
| 1 | Dasar JavaScript | Minggu 3-8 |
| 2 | Node.js | Minggu 9-12 |
| 3 | Database dan SQL | Minggu 13-18 |
| 4 | Express dan REST API | Minggu 19-26 |
| 5 | Testing | Minggu 27-30 |
| 6 | TypeScript | Minggu 31-34 |
| 7 | Docker, Redis, CI/CD, deployment | Minggu 35-42 |
| 8 | Konsep lanjutan | Bulan ke-10 dan seterusnya |

---

## Checklist Kemajuan

- [ ] Akun GitHub aktif dan rutin commit
- [ ] Dasar JavaScript dan async/await dikuasai
- [ ] Server Node.js pertama berjalan
- [ ] Bisa menulis SQL dengan JOIN dan GROUP BY
- [ ] REST API dengan autentikasi JWT selesai
- [ ] API pertama sudah dideploy online
- [ ] Test otomatis berjalan
- [ ] Proyek ditulis ulang dengan TypeScript
- [ ] Aplikasi berjalan dengan Docker Compose
- [ ] Pipeline CI di GitHub Actions
- [ ] Proyek utama #2 selesai dan terdokumentasi
- [ ] CV dan portofolio siap
- [ ] Mengirim lamaran magang pertama

---

## Catatan Penting

- Roadmap ini fleksibel. Kalau satu fase terasa lebih sulit, perpanjang saja waktunya, jangan dipaksa lanjut.
- Jangan membandingkan kecepatanmu dengan orang lain di media sosial.
- Sesekali berhenti belajar materi baru dan rapikan proyek lama. Itu juga bagian dari belajar.
- Mulai melamar magang sebelum merasa "siap sepenuhnya". Wawancara pertama biasanya gagal, dan itu normal serta berguna sebagai pengalaman.
