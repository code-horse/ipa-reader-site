---
layout: bare
title: Ekstensi IPA Reader - Panduan Pengguna
lang: id
---

# IPA Reader - Panduan Pengguna

> Versi: v1.4.0

## Pendahuluan

IPA Reader adalah ekstensi browser yang dirancang untuk pelajar bahasa Inggris. Ini menambahkan anotasi pengucapan IPA (Alfabet Fonetik Internasional) ke kata-kata bahasa Inggris di halaman web dan file PDF, mendukung aksen Amerika dan Inggris. Ekstensi ini juga mencakup kamus bahasa Inggris bawaan, teks-ke-suara, dan fitur terjemahan — membantu Anda mempelajari pengucapan bahasa Inggris dengan lebih mudah.

---

## Fitur Utama

- **Mode IPA seluruh halaman** — Tambahkan anotasi IPA ke semua kata bahasa Inggris di halaman dengan satu klik; simbol IPA dikode warna menurut jenis (vokal, konsonan, tanda tekanan) agar mudah dibaca
- **Kamus hover** — Arahkan kursor ke kata untuk melihat definisi bahasa Inggris (82.000+ kata dari WordNet), IPA dengan simbol berkode warna, dan tombol pengucapan; pilih mode Kamus, Tooltip, Hanya bicara, atau Mati
- **Pembaca PDF** — Pembaca PDF bawaan dengan anotasi IPA, kamus, ucapan, dan terjemahan; mendukung seret & lepas, muat URL, dan deteksi PDF otomatis dengan pengalihan cerdas
- **Bentuk lemah/kuat** — Tampilkan otomatis varian pelafalan lemah dan kuat kata fungsi (mis. „the”, „to”, „can”) untuk menguasai percakapan alami
- **Aksen Amerika & Inggris** — Beralih antara IPA bahasa Inggris Amerika (en-US) dan Inggris (en-GB)
- **Teks-ke-Suara** — Klik tombol speaker untuk mendengar pengucapan yang sesuai dengan aksen pilihan Anda
- **Ucapan pilihan dengan efek karaoke** — Pilih teks bahasa Inggris apa pun; bilah alat ringkas muncul dengan tombol bicara dan terjemahan; suara diputar dengan penyorotan kata per kata secara real time (efek karaoke), sinkron dengan audio
- **Terjemahan pilihan** — Pilih teks apa pun, klik tombol terjemahan di bilah alat untuk terjemahan instan melalui Bing atau Google Translate, ditampilkan dalam gelembung inline
- **Disambiguasi homograf** — Identifikasi otomatis kata dengan beberapa pelafalan (mis. read, live) dan pilihan yang tepat berdasarkan konteks
- **Pintasan keyboard** — Akses cepat ke fitur inti melalui pintasan yang dapat disesuaikan
- **Antarmuka multibahasa** — Mendukung 41 bahasa antarmuka

---

## Cara Menggunakan

### Langkah 1: Instal Ekstensi

Instal **IPA Reader** dari [Chrome Web Store](https://chromewebstore.google.com/), atau muat secara lokal dalam mode pengembang.

### Langkah 2: Buka Halaman Web Apa Pun

Kunjungi halaman web apa pun yang berisi konten bahasa Inggris.

### Langkah 3: Aktifkan IPA

Klik ikon ekstensi di bilah alat browser. Aktifkan „Aktifkan IPA”, lalu „IPA seluruh halaman” untuk menganotasi semua kata di halaman. Anda juga dapat menggunakan tombol mengambang di kanan bawah.

### Langkah 4: Lihat IPA

Arahkan kursor ke kata untuk melihat tooltip IPA dengan simbol fonetik berkode warna. Klik ikon speaker untuk mendengar pengucapan. Untuk kata dengan bentuk lemah/kuat, tooltip menampilkan kedua varian.

### Langkah 5: Ucapkan dan terjemahkan teks yang dipilih

Pilih teks bahasa Inggris apa pun dengan mouse. Bilah alat ringkas muncul di dekat pilihan dengan dua tombol:
- **🔊 Bicara** — membacakan pilihan dengan penyorotan kata per kata bergaya karaoke
- **🌐 Terjemahkan** — menampilkan gelembung terjemahan inline di bawah bilah alat

Anda juga dapat klik kanan dan memilih „IPA Reader > Speak Selection” atau „IPA Reader > Translate Selection”.

> **Tip:** Klik ikon ekstensi di bilah alat untuk membuka panel pengaturan: jenis aksen, kecepatan bicara, mode hover, mesin terjemahan, dan lainnya.

---

## Mode IPA seluruh halaman

Saat mode IPA seluruh halaman aktif, setiap kata bahasa Inggris di halaman mendapat anotasi IPA di atasnya sebagai teks ruby. Simbol IPA dikode warna agar mudah dibaca:

- **Vokal** — disorot biru
- **Konsonan** — abu-abu
- **Tanda tekanan** (ˈ ˌ) — disorot merah
- **Tanda panjang** (ː) — disorot ungu

Ekstensi menyesuaikan tinggi baris secara otomatis agar anotasi tidak bertumpuk dengan teks, dan menskalakan ukuran font IPA berdasarkan panjang kata.

---

## Kamus hover

Ekstensi menyertakan kamus bahasa Inggris bawaan berbasis WordNet (82.000+ kata). Anda dapat memilih beberapa mode hover di pengaturan:

| Mode | Perilaku |
|------|----------|
| **Kamus** | Hover menampilkan IPA + definisi bahasa Inggris + tombol pengucapan |
| **Tooltip** | Hover menampilkan IPA + tombol pengucapan (tanpa definisi) |
| **Hanya bicara** | Klik kata untuk mendengar pengucapan (tanpa tooltip) |
| **Mati** | Tidak ada efek hover |

Dalam **mode Kamus**, tooltip menampilkan:
- Kata dan transkripsi IPA-nya
- Tombol pengucapan (klik untuk mendengar)
- Definisi bahasa Inggris dari WordNet

> **Tip:** Data kamus dimuat sesuai kebutuhan saat mode Kamus diaktifkan, dan dibongkar saat beralih ke mode lain untuk menghemat memori.

---

## Pembaca PDF

IPA Reader menyertakan pembaca PDF bawaan sehingga Anda dapat membaca dokumen PDF dengan anotasi IPA, kamus, ucapan, dan terjemahan — fitur yang sama seperti di halaman web, kini untuk PDF.

### Membuka PDF

**Metode 1: Dari popup**  
Klik ikon ekstensi, lalu klik „Buka Pembaca PDF”. Seret & lepas file PDF atau klik „Pilih File” untuk membuka PDF lokal. Anda juga dapat menempel URL PDF.

**Metode 2: Menu konteks**  
Klik kanan tautan `.pdf` di halaman web dan pilih „Buka PDF dengan IPA Reader”.

**Metode 3: Deteksi otomatis**  
Saat „Deteksi PDF cerdas” diaktifkan di pengaturan, ekstensi secara otomatis mengalihkan URL `.pdf` ke pembaca bawaan. Jika PDF terdeteksi tetapi tidak dialihkan (mis. penampil bawaan Chrome), Anda akan melihat notifikasi dan petunjuk untuk membukanya di IPA Reader.

### Fitur Pembaca PDF

- **Anotasi IPA** — Semua fitur IPA berfungsi pada teks PDF, termasuk mode seluruh halaman dan tooltip hover
- **Kamus klik** — Klik kata apa pun untuk melihat definisinya (di PDF, klik dipakai alih-alih hover agar membaca lebih fokus)
- **Bilah pilihan** — Pilih teks untuk berbicara, menerjemahkan, atau menyalin
- **Bilah sisi** — Kerangka isi dan gambar mini halaman
- **Cari** — Cari teks dalam PDF
- **Tema** — Tema baca Gelap, Terang, dan Sepia
- **Zoom** — Beberapa tingkat zoom termasuk Otomatis, Pas Halaman, dan Lebar Halaman
- **Pintasan keyboard** — Panah untuk navigasi, +/- untuk zoom, Ctrl/Cmd+F untuk mencari

---

## Bentuk lemah/kuat

Banyak kata fungsi umum yang memiliki dua pelafalan:

- **Bentuk lemah** — pelafalan tereduksi dalam ucapan alami (mis. „the” → /ðə/)
- **Bentuk kuat** — pelafalan penuh saat penekanan atau terisolasi (mis. „the” → /ðiː/)

Saat „Tampilkan bentuk lemah/kuat” diaktifkan, mengarahkan kursor ke kata-kata ini menampilkan kedua varian di tooltip, berlabel „WEAK” dan „STRONG”. Ini membantu memahami bagaimana pelafalan berubah dalam ucapan alami.

Mencakup antara lain: artikel (the, a, an), preposisi (to, for, of, from, at, as, than), konjungsi (and, or, but), kata ganti (you, your, her, him, his, them, us, our, there), kata kerja bantu (am, is, are, was, were, been, can, could, would, should, must, shall, will, do, does, have, has, had), dan lainnya.

---

## Ucapan pilihan & karaoke

Fitur ucapan pilihan memungkinkan Anda memilih teks bahasa Inggris apa pun dan membacanya dengan lantang dengan satu klik — cocok untuk mempelajari pengucapan kalimat dan latihan membaca.

**Metode 1: Bilah pilihan**  
Pilih teks bahasa Inggris dengan mouse. Bilah ringkas muncul di dekat pilihan dengan tombol 🔊 bicara dan 🌐 terjemahkan. Klik bicara untuk memutar. Saat teks dibaca, setiap kata disorot secara real time (efek karaoke).

**Metode 2: Menu klik kanan**  
Setelah memilih teks bahasa Inggris, klik kanan dan pilih „IPA Reader > Speak Selection”.

**Metode 3: Pintasan keyboard**  
Pilih teks dan tekan `Alt+Shift+S` (Mac: `Ctrl+Shift+S`) untuk membaca dengan suara.

> **Tip:** Penyorotan karaoke berfungsi paling baik jika browser mendukung peristiwa batas kata TTS. Jika tidak, ekstensi menggunakan fallback berbasis waktu untuk penyorotan yang halus.

---

## Terjemahan

Pilih teks apa pun di halaman dan gunakan fitur terjemahan untuk hasil instan.

**Metode 1: Bilah pilihan**  
Pilih teks, lalu klik tombol 🌐 terjemahkan di bilah. Gelembung terjemahan muncul di bawah dengan tombol salin.

**Metode 2: Menu klik kanan**  
Pilih teks, klik kanan dan pilih „IPA Reader > Translate Selection”.

**Metode 3: Pintasan keyboard**  
Pilih teks dan tekan `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) untuk menerjemahkan.

**Mesin terjemahan:**
- **Bing Translate** (default) — Microsoft Translator
- **Google Translate** — Google

Kedua mesin mendukung **108 bahasa target**.

Anda dapat mengganti mesin terjemahan dan bahasa target di pengaturan ekstensi. Bahasa target secara default terdeteksi dari bahasa browser.

> **Tip:** Klik di luar bilah atau gelembung untuk menutupnya.

---

## Pintasan keyboard

| Pintasan | Mac | Tindakan |
|----------|-----|----------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | Aktifkan/nonaktifkan anotasi IPA |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Bicarakan teks yang dipilih |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Terjemahkan teks yang dipilih |

> **Tip:** Sesuaikan pintasan di Chrome di `chrome://extensions/shortcuts`.

---

## Panduan Pengaturan

| Pengaturan | Deskripsi |
|------------|------------|
| **Aktifkan IPA** | Saklar utama untuk mengaktifkan atau menonaktifkan fitur anotasi IPA |
| **IPA seluruh halaman** | Saat diaktifkan, menampilkan IPA berkode warna untuk semua kata bahasa Inggris di atas teks |
| **Gaya IPA** | Pilih antara IPA dan pengucapan bahasa Inggris Amerika dan Inggris |
| **Mode hover** | Pilih perilaku hover: Kamus (IPA + definisi + audio), Tooltip (IPA + audio), Hanya bicara (klik untuk mendengar), atau Mati |
| **Tampilkan bentuk lemah/kuat** | Varian pelafalan lemah dan kuat kata fungsi |
| **Kecepatan ucapan kalimat** | Sesuaikan kecepatan pembacaan kalimat (ucapan satu kata tidak terpengaruh) |
| **Mesin terjemahan** | Pilih antara Bing Translate dan Google Translate |
| **Bahasa target** | Atur bahasa target terjemahan (terdeteksi otomatis dari bahasa browser) |
| **Deteksi PDF cerdas** | Saat diaktifkan, secara otomatis mengalihkan URL PDF ke pembaca bawaan dan menampilkan notifikasi saat PDF terdeteksi |

---

## FAQ

**T: Mengapa tidak berfungsi di beberapa halaman?**  
J: Karena alasan keamanan, ekstensi browser tidak dapat berjalan di halaman khusus seperti `chrome://`, pengaturan browser, atau Chrome Web Store.

**T: Bagaimana jika IPA hilang untuk beberapa kata?**  
J: Kamus IPA mencakup lebih dari 134.000 kata bahasa Inggris Amerika dan lebih dari 67.000 kata Inggris Britania. Untuk kata di luar kamus, ekstensi menghasilkan IPA perkiraan melalui lematisasi dan G2P berbasis aturan, ditandai dengan ≈ atau ~ di tooltip.

**T: Tidak ada suara dari teks-ke-suara?**  
J: Silakan periksa pengaturan volume sistem Anda dan pastikan paket suara bahasa Inggris terpasang. Dukungan suara bervariasi di berbagai browser dan sistem operasi.

**T: Mode seluruh halaman memengaruhi tata letak?**  
J: Anotasi IPA memerlukan ruang ekstra. Ekstensi menyesuaikan tinggi baris untuk meminimalkan dampak. Jika masih mengganggu, nonaktifkan mode seluruh halaman dan gunakan mode hover (Kamus atau Tooltip).

**T: Apa arti simbol ~ dan ≈ di tooltip?**  
J: ~ berarti IPA dihasilkan oleh aturan (G2P), bukan dari kamus. ≈ berarti diturunkan dari kata dasar terkait melalui lematisasi. Ini mungkin kurang akurat dibandingkan entri kamus.

**T: Terjemahan tidak berfungsi?**  
J: Terjemahan memerlukan koneksi internet. Jika Bing Translate gagal, coba beralih ke Google Translate di pengaturan. Beberapa lingkungan jaringan mungkin memblokir akses ke layanan terjemahan.

**T: Bagaimana cara membuka PDF dengan IPA Reader?**  
J: Anda dapat membuka PDF dengan beberapa cara: klik „Buka Pembaca PDF” di popup, klik kanan tautan PDF dan pilih „Buka PDF dengan IPA Reader”, atau aktifkan „Deteksi PDF cerdas” di pengaturan untuk mengalihkan URL PDF ke pembaca bawaan secara otomatis.

**T: Deteksi PDF cerdas diaktifkan tetapi beberapa PDF tidak dialihkan?**  
J: Pengalihan otomatis berfungsi untuk URL yang berakhiran `.pdf`. Untuk PDF yang dilayani tanpa ekstensi `.pdf` atau dibuka di penampil bawaan Chrome, Anda akan melihat notifikasi dan lencana yang mengarahkan untuk membukanya di IPA Reader.

**T: Bisakah saya menggunakan kamus secara offline?**  
J: Ya. Kamus WordNet (82.000+ kata) sepenuhnya disertakan dalam ekstensi. Semua pencarian dilakukan secara lokal tanpa koneksi jaringan.

---

## Tautan Terkait

- [Privacy Policy](../privacy-policy)
- [Support & Feedback](../support)

---
