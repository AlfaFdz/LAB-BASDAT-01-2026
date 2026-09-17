# LAB-BASDAT-01-2026

Repositori Resmi Pengumpulan Tugas Praktikum **Lab Basis Data 2026**
**Program Studi Sistem Informasi — Universitas Hasanuddin**

---

## Persyaratan Perangkat Lunak (Lab Requirements)

Sebelum memulai praktikum dan mengerjakan tugas, pastikan Anda telah memasang perangkat lunak berikut:

1. [GitHub](https://github.com/) — Akun pribadi
2. [PostgreSQL](https://www.postgresql.org/download/)
3. [pgAdmin 4](https://www.pgadmin.org/download/) — atau SQL Editor pilihan Anda

---

## Aturan & Alur Pengumpulan Tugas via GitHub

> **Catatan Penting:**
> Teks yang dibungkus dengan `< >` harus diganti sesuai dengan data Anda masing-masing.
> *Contoh:* `mkdir <NIM>` → `mkdir H071221001`

---

### 1. Fork Repository

1. Buka repositori utama ini di GitHub.
2. Klik tombol **Fork** di pojok kanan atas.
3. Repositori hasil *fork* akan otomatis muncul di akun GitHub Anda.

---

### 2. Clone Repository Hasil Fork

Buka Terminal atau Git Bash, lalu jalankan perintah berikut:

```bash
git clone <url-repositori-hasil-fork>
```

**Contoh:**

```bash
git clone https://github.com/username/LAB-BASDAT-01-2026.git
```

> Ganti `username` dengan username GitHub Anda.

---

### 3. Masuk ke Folder Repository

```bash
cd LAB-BASDAT-01-2026
```

---

### 4. Buat Folder Sesuai NIM

Buat folder utama menggunakan NIM Anda. Folder ini cukup dibuat **satu kali di awal pengumpulan tugas**.

```bash
mkdir <NIM>
```

**Contoh:**

```bash
mkdir H071221001
```

---

### 5. Tambahkan Folder Tugas Praktikum (TP)

Setiap tugas per minggu dikumpulkan dalam folder tersendiri di dalam folder NIM masing-masing.

Gunakan format nama folder:

```text
TP<tugas-keberapa>-<NIM>
```

**Contoh struktur repository:**

```text
LAB-BASDAT-01-2026/
├── H071221001/
│   ├── TP1-H071221001/
│   │   └── tugas1.sql
│   └── TP2-H071221001/
│       └── tugas2.sql
└── H071221002/
    ├── TP1-H071221002/
    └── TP2-H071221002/
```

> **Catatan:** Pastikan tugas yang dikumpulkan telah mendapatkan **ACC dari asisten** sebelum melakukan commit dan push.

---

### 6. Add, Commit, dan Push

Setiap kali menambahkan atau memperbarui file tugas yang **sudah di-ACC**, jalankan:

```bash
git add .
git commit -m "<type>(<scope>): <deskripsi singkat>"
git push origin main
```

#### 📝 Format Commit Message (Conventional Commits)

Gunakan format **Conventional Commits** agar riwayat commit lebih rapi dan profesional.

**Struktur:**

```text
<type>(<scope>): <deskripsi singkat>
```

**Jenis commit (`type`) yang digunakan:**

* `feat` : Menambahkan tugas, query, atau fitur baru
* `fix` : Memperbaiki kesalahan syntax query atau typo pada tugas
* `docs` : Mengubah atau memperbarui dokumentasi
* `refactor` : Merapikan struktur query tanpa mengubah logika atau hasil
* `style` : Menyesuaikan format atau gaya penulisan kode SQL
* `chore` : Perubahan lain yang tidak memengaruhi isi tugas utama

**Contoh commit message:**

```bash
feat(tp1): menambahkan TP1-H071221001
fix(tp2): memperbaiki syntax JOIN pada TP2-H071221002
```

---

### 7. Buat Pull Request (PR)

Setelah melakukan **push**, buat Pull Request untuk mengumpulkan tugas:

1. Buka repositori hasil *fork* di akun GitHub Anda.
2. Klik **Contribute** → **Open Pull Request**.
3. Judul PR **wajib** menggunakan format:

```text
TP<tugas-keberapa>-<NIM>
```

**Contoh:**

```text
TP1-H071221001
```

4. Deskripsi PR wajib mencantumkan daftar file yang ditambahkan atau diperbarui pada tugas tersebut.
5. Pastikan semua informasi sudah benar, kemudian klik **Create Pull Request**.

---

## ⚠️ Catatan Pengumpulan

* Pastikan tugas telah mendapatkan **ACC dari asisten** sebelum dikumpulkan.
* Pastikan file tugas berada pada folder NIM dan folder TP yang sesuai.
* Pastikan nama folder dan format Pull Request mengikuti ketentuan yang telah ditentukan.
* Jangan mengubah atau menghapus file milik mahasiswa lain.
* Pastikan proses **add → commit → push → pull request** dilakukan dengan benar.
