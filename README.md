# 💬 giscus-senimankode

**giscus-senimankode** adalah repositori khusus untuk menyimpan komentar dari pengunjung situs web [Seniman Kode](https://senimankode.id) yang dibangun menggunakan [Hugo](https://gohugo.io) dan menggunakan sistem komentar [Giscus](https://giscus.app).

---

## 📌 Tentang Proyek Ini

Giscus adalah sistem komentar ringan yang terintegrasi dengan GitHub Discussions. Komentar dari pengunjung situs web akan disimpan sebagai thread di dalam _repository_ ini, menjadikan GitHub sebagai backend komentar.

---

## 🛠️ Cara Kerja

- Setiap halaman pada situs Seniman Kode akan memiliki thread diskusi yang otomatis terbuat berdasarkan URL.
- Komentar ditampilkan langsung di situs menggunakan Giscus widget.
- Semua komentar disimpan sebagai **discussions** di repository ini.

---

## ⚙️ Konfigurasi Giscus

Pengaturan utama yang digunakan:

- **Repository:** `Orlinkzz/giscus-senimankode`
- **Discussion Category:** `Announcements`
- **Mapping:** `pathname` – setiap URL halaman dipetakan ke 1 thread
- **Tema:** Sinkronisasi dengan tema Hugo (light/dark)
- **Bahasa:** Bahasa Indonesia (`id`)

---

## 🧑‍💻 Cara Berpartisipasi (Bagi Pengunjung Situs)

1. Kunjungi salah satu artikel di situs [Seniman Kode](https://senimankode.id).
2. Scroll ke bagian komentar di bawah artikel.
3. Login dengan akun GitHub.
4. Tinggalkan komentar seperti biasa — komentar kamu akan tersimpan di thread di repository ini.

---

## 🔐 Hak Akses

- Pengunjung hanya dapat menulis komentar melalui GitHub login.
- Hanya pemilik dan kontributor yang dapat memoderasi komentar di GitHub Discussions.

---

## 💡 FAQ

### Apakah saya butuh akun GitHub untuk berkomentar?
Ya, Giscus menggunakan GitHub Discussions, jadi pengguna harus login dengan akun GitHub untuk meninggalkan komentar.

### Apakah komentar saya akan terlihat publik?
Ya, komentar akan tampil di halaman artikel dan juga di tab "Discussions" dari repositori ini.

---

## 📄 Lisensi

Repositori ini hanya digunakan untuk penyimpanan komentar publik. Konten komentar adalah milik masing-masing pengguna.

---

## 🤝 Kontribusi

Repositori ini tidak menerima pull request karena hanya untuk keperluan komentar. Namun, jika kamu punya saran atau pertanyaan, silakan buka [issue](https://github.com/Orlinkzz/giscus-senimankode/issues).

---

