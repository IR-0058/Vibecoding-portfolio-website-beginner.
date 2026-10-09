# Perbandingan Kualitas 4 Agentic AI (Free Tier)

Proyek ini dibuat untuk menguji dan membandingkan kinerja 4 model AI berbasis agen (*Free Tier*) dalam membangun sebuah struktur website portofolio berbasis instruksi **PRD (Product Requirement Document)** yang sama.

Pengujian dilakukan dari sudut pandang pemula yang **tidak memiliki latar belakang koding**, tetapi ingin memahami cara membuat *prompt* yang konsisten dan terstruktur.

---

## 🏆 Peringkat & Hasil Pengujian

Berdasarkan uji coba eksekusi *prompt* PRD oleh `@IR_`, berikut adalah urutan AI gratis terbaik untuk pemula:

1. 🥇 **Claude** — Output paling rapi, konsisten, dan mendekati instruksi PRD.
2. 🥈 **OpenCode.ai** — Sangat baik dalam mengeksekusi struktur dasar koding.
3. 🥉 **ChatGPT** — Cukup baik, namun masih memerlukan beberapa kali perbaikan (*refactoring*).
4. 🏅 **Gemini** — Membutuhkan arahan manual paling banyak untuk mendekati struktur yang diinginkan.

> 📢 **Pemberitahuan:** Meskipun keluaran dari **Claude** mendapatkan nilai terbaik, hasil komputasi dan berkas kodenya **tidak dapat dipublikasikan kepada publik** atas alasan privasi/lisensi pemilik.

---

## 📌 Catatan & Evaluasi Penguji

* **Belum 100% Sempurna:** Walaupun *prompt* PRD sudah dibuat sangat rinci dan terstruktur, hasil akhir dari seluruh AI belum ada yang 100% sesuai ekspektasi tanpa revisi.
* **Kurang Kreatif (*Out of the Box*):** Seluruh model AI masih bertindak kaku sesuai instruksi mentah. AI belum memiliki kemampuan berpikir kreatif secara mandiri di luar apa yang tertulis pada *prompt*.
* **Perlu Arahan Aktif:** Pengguna tetap harus membimbing AI secara bertahap (*step-by-step*) untuk memperbaiki *layout* dan fungsi yang tidak berjalan.

---

## 📐 Contoh Struktur Arsitektur & Relasi Halaman (PRD)

Berikut adalah cetak biru (*blueprint*) arsitektur tata letak dan hubungan antarhalaman yang digunakan sebagai panduan acuan *prompt* kepada setiap AI:

```text
                           [ LOBBY MAIN PAGE ]
                               (index.html)
                                    │
                                    ▼
            ┌───────────────────────┴───────────────────────┐
            ▼                                               ▼
[ Teks Bio / Pengguna ]                         [ Interactive Circle Icon ]
   (Sisi Kiri Layout)                          (16 Slice Pizza Wheel Diagram)
            │                                               │
            └───────────────────────┬───────────────────────┘
                                    │
                                    ▼
                           [ HERO & PROFILE ]
                       (Tengah Layar / Fokus Utama)
                                    │
                                    ▼
                 // Satu Frame Kompak (Pisahkan Kiri / Kanan)
            ┌───────────────────────┴───────────────────────┐
            ▼                                               ▼
   [ PHOTO PREVIEW ]                               [ VIDEO PREVIEW ]
 (Vertical Aspect)                                 (Vertical Aspect)
            │                                               │
  [ Lihat Semua Foto ]                            [ Lihat Semua Video ]
            │                                               │
            ▼                                               ▼
    [ GALERI FOTO ]                                 [ GALERI VIDEO ]
(pages/gallery-foto.html)                       (pages/gallery-video.html)
            │                                               │
            └───────────────────────┬───────────────────────┘
                                    │
                                    ▼
                         [ DASHBOARD & DIAGRAM ]
                                    │
                                    ▼
                            [ FOOTER SECTION ]
                                    │
            ┌───────────────────────┴───────────────────────┐
            ▼                                               ▼
[Sisi Kiri: Ringkasan Brand]               [Sisi Kanan: Meta Info & Hak Cipta]
```

*Disclaimer: Arsitektur di atas merupakan salah satu cuplikan bagian dari struktur kompleks prompt PRD yang diujikan.*

---

## 💡 Kesimpulan

Bagi pemula tanpa keahlian koding, memahami teknik pembentukan *prompt* (PRD) yang terstruktur adalah kunci utama. **Claude** dan **OpenCode.ai** menjadi pilihan paling direkomendasikan untuk membantu membangun struktur awal proyek web secara instan, meskipun penyempurnaan manual tetap diperlukan.
