# 01 · Data Lapangan

**Minggu:** PTS−4 · **Dinilai di:** PTS, kriteria *Pattern & data lapangan* (15 poin, bersama bagian pola di `03`)

> [!TIP]
> **Pilar CT yang dilatih: Pattern Recognition.** Pola hanya bisa ditemukan dari data yang nyata. Minggu ini kamu mengumpulkan bahan mentahnya: kejadian, angka, dan kutipan. Kamu belum menyimpulkan apa-apa; menghitung pola dilakukan di `03`.

## 1. Yang harus ada

Pilih **satu jalur**. Minimum terpenuhi kalau satu jalur lengkap. Dua jalur yang sama-sama setengah jadi (misalnya 2 narasumber dan 10 transaksi) **tidak** memenuhi minimum.

**Jalur A: minimal 3 narasumber**

- [ ] 3 orang berbeda (kode `N1`, `N2`, `N3`) yang benar-benar terlibat dengan jenis UMKM kasusmu: pemilik, karyawan, atau pelanggan tetap.
- [ ] Setiap narasumber menjawab **minimal 5 pertanyaan** tentang kejadian yang sudah terjadi (bukan pendapat atau rencana).
- [ ] Setiap narasumber punya **minimal 1 kutipan langsung**.

**Jalur B: minimal 20 data transaksi**

- [ ] **20 baris** transaksi nyata (kode `T01` sampai `T20`), dari catatan pemilik (dengan izin) atau dari pengamatanmu langsung.
- [ ] Setiap baris punya **minimal 5 kolom** terisi.

**Kedua jalur**

- [ ] Bagian "Sumber dan izin" terisi: dari mana data didapat, bagaimana caranya, dan izin yang diberikan.
- [ ] **Minimal 3 temuan awal**, masing-masing menyebut kode buktinya (misalnya `N2`, `T05`).
- [ ] Tidak ada data pribadi (lihat 2.3).

Data yang dikarang, oleh kamu sendiri atau oleh AI, tidak dihitung. Nilai plus: minimal satu narasumber (Jalur A) adalah **pemilik** UMKM nyata yang sejenis dengan kasusmu, dan izinnya tercatat. Plus ini menaikkan nilai satu tingkat, hanya kalau hitungan polamu di `03` cocok dengan data di file ini.

## 2. Cara mengerjakan

### 2.1 Wawancara singkat: tanya kejadian, bukan pendapat

Pakai tiga aturan dari Rob Fitzpatrick, *The Mom Test* (2013):

1. Bicarakan hidup dan pekerjaan mereka, bukan ide aplikasimu.
2. Tanyakan kejadian spesifik yang sudah terjadi, bukan pendapat atau rencana ke depan.
3. Lebih banyak mendengar daripada bicara.

Orang cenderung menjawab "iya, bagus" kalau ditanya pendapat, supaya sopan. Kejadian nyata lebih sulit dikarang. Bandingkan:

| Pertanyaan buruk (pendapat atau masa depan) | Pertanyaan baik (kejadian nyata) |
|---|---|
| "Bapak butuh aplikasi tiket servis?" | "Kapan terakhir ada jam pelanggan yang tertukar? Ceritakan dari awal." |
| "Janji ambil sering meleset, ya?" | "Minggu lalu, berapa pelanggan yang datang tapi jamnya belum jadi?" |
| "Berapa lama biasanya servis mesin?" | "Jam terakhir yang diservis mesinnya, masuk hari apa dan selesai hari apa?" |
| "Kalau ada aplikasinya, Bapak mau pakai?" | "Sekarang titipan jam dicatat di mana? Boleh saya lihat?" |

Tips praktis:

- 10 sampai 15 menit per narasumber cukup. Siapkan 6 sampai 8 pertanyaan, pakai minimal 5.
- Setiap jawaban yang menarik, susul dengan "Lalu apa yang Bapak/Ibu lakukan?" atau "Itu terjadi berapa kali bulan ini?"
- Catat angka, nama hari, dan kejadian. Jangan mencatat kesimpulanmu sendiri sebagai jawaban.
- Jangan menceritakan ide aplikasimu sampai wawancara selesai.

### 2.2 Mengumpulkan 20 transaksi

1. Tentukan kolom dulu (minimal 5), misalnya waktu, barang atau jasa, jumlah, harga, dan catatan masalah.
2. Ambil 20 transaksi **berturut-turut**, bukan memilih yang menarik saja. Pilihan yang disaring membuat pola palsu.
3. Tulis sumbernya: buku nota pemilik, rekap kasir, atau pengamatan langsung di jam tertentu.

### 2.3 Izin dan privasi

Repo kamu **public**. Siapa pun bisa membacanya.

- Minta izin lisan, jelaskan bahwa data dipakai untuk tugas kuliah dan akan tampil di internet tanpa nama. Tulis hasilnya: `Izin: ya (lisan)`.
- Pakai kode: narasumber `N1`, pelanggan `P-01`, transaksi `T01`.
- **Jangan** menulis nama lengkap, nomor HP, alamat rumah, plat nomor, atau foto wajah. Jangan mengunggah foto nota yang memuat nama atau nomor pelanggan.
- Nama usaha hanya ditulis kalau pemiliknya mengizinkan. Kalau tidak, tulis jenis dan wilayahnya, misalnya "laundry kiloan dekat kampus".

Dasar hukumnya: UU No. 27 Tahun 2022 tentang Pelindungan Data Pribadi.

> [!CAUTION]
> **Data pribadi nyata di repo menurunkan nilai.** Kalau nama lengkap, nomor HP, alamat rumah, plat nomor, atau foto wajah narasumber atau pelanggan ada di file mana pun di repo, kriteria *Pattern & data lapangan* di PTS langsung bernilai Kurang. Di PAS, data pribadi nyata di repo atau di video membuat kriteria *Prototipe* langsung Kurang.

### 2.4 Peran AI minggu ini

AI boleh membantu menyusun daftar pertanyaan atau memeriksa apakah pertanyaanmu menanyakan pendapat. AI **tidak boleh** mengarang jawaban atau transaksi. Catat pemakaiannya di `prompt-journal.md`.

## 3. Contoh pengisian

> [!NOTE]
> Kasus netral **Servis Jam Tangan Pak Darto** (kios servis jam kecil; masalahnya: jam pelanggan tertukar dan janji ambil sering meleset). Kasus ini tidak ada di bank kasus. **Data fiktif untuk keperluan pembelajaran.** Contoh ini memakai Jalur B.

**Jalur:** B (transaksi)

**Sumber dan izin:** buku nota Pak Darto, 20 tiket berturut-turut sejak Senin pekan pertama pengamatan. Disalin di kios dengan izin lisan Pak Darto (`Izin: ya (lisan)`). Nama dan nomor HP pelanggan tidak disalin. Hari ditulis sebagai "hari ke-": hari ke-1 = Senin, hari ke-7 = Minggu (kios tutup).

<details>
<summary><b>Lihat 20 baris transaksi contoh</b></summary>

| Kode | Masuk (hari ke-) | Pekerjaan | Ciri jam | Janji ambil (hari ke-) | Selesai (hari ke-) | Biaya (Rp) | Catatan |
|---|---|---|---|---|---|---|---|
| T01 | 1 | Baterai | analog perak, rantai | 1 | 1 | 25.000 | |
| T02 | 1 | Mesin | analog hitam, kulit | 3 | 4 | 150.000 | pelanggan datang hari ke-3, belum jadi |
| T03 | 2 | Tali | digital hitam, karet | 2 | 2 | 35.000 | |
| T04 | 2 | Kaca | analog emas, rantai | 4 | 3 | 60.000 | |
| T05 | 2 | Baterai | digital biru, karet | 2 | 2 | 25.000 | |
| T06 | 3 | Mesin | analog hitam, kulit | 5 | 8 | 150.000 | tertukar dengan T02 |
| T07 | 3 | Baterai | analog putih, kulit | 3 | 3 | 25.000 | |
| T08 | 4 | Kaca | digital hitam, karet | 6 | 5 | 60.000 | |
| T09 | 4 | Baterai | analog perak, rantai | 4 | 4 | 25.000 | |
| T10 | 4 | Tali | analog cokelat, kulit | 4 | 4 | 40.000 | |
| T11 | 5 | Mesin + Kaca | analog perak, rantai | 8 | 10 | 200.000 | pelanggan tanya lewat WA 2 kali |
| T12 | 5 | Baterai | digital hitam, karet | 5 | 5 | 25.000 | |
| T13 | 6 | Kaca | analog emas, kulit | 8 | 8 | 60.000 | |
| T14 | 6 | Baterai | analog hitam, kulit | 6 | 6 | 25.000 | |
| T15 | 8 | Mesin | analog hitam, kulit | 10 | 11 | 150.000 | hampir tertukar dengan T16 |
| T16 | 8 | Kaca | analog hitam, kulit | 10 | 9 | 60.000 | hampir tertukar dengan T15 |
| T17 | 9 | Tali | digital putih, karet | 9 | 9 | 35.000 | |
| T18 | 9 | Baterai | analog emas, rantai | 9 | 9 | 25.000 | |
| T19 | 10 | Mesin | digital hitam, karet | 12 | 13 | 150.000 | |
| T20 | 11 | Baterai | analog perak, kulit | 11 | 11 | 25.000 | |

</details>

**Temuan awal**

| Kode | Temuan | Bukti |
|---|---|---|
| TA1 | Ganti baterai dan ganti tali selalu selesai di hari yang sama dengan hari masuk. | T01, T03, T05, T07, T09, T10, T12, T14, T17, T18, T20 |
| TA2 | Janji ambil yang meleset selalu pekerjaan mesin. | T02, T06, T11, T15, T19 |
| TA3 | Jam yang tertukar atau hampir tertukar sama-sama analog hitam bertali kulit, dan semuanya menginap. | T02, T06, T15, T16 |

Perhatikan: temuan awal hanya menyebut apa yang terlihat. Menghitung dan menyimpulkan baru dilakukan di `03`.

## 4. Cek sebelum commit

- [ ] Satu jalur sudah lengkap: 3 narasumber dengan masing-masing 5 pertanyaan dan 1 kutipan, **atau** 20 baris transaksi dengan 5 kolom.
- [ ] Setiap pertanyaan menanyakan kejadian yang sudah terjadi, bukan pendapat atau rencana.
- [ ] Ada 3 temuan awal dan setiap temuan menyebut kode buktinya.
- [ ] Tidak ada nama lengkap, nomor HP, alamat, plat nomor, atau foto wajah di file ini.
- [ ] Bagian jalur yang tidak dipakai (5.3A atau 5.3B) sudah dihapus.

## 5. Isianmu

Semua yang ada di bawah judul ini adalah isianmu, dan hanya bagian ini yang diperiksa dosen. Jangan menghapus judul ini dan jangan menambah bagian baru sesudahnya.

### 5.1 Jalur yang dipilih

`A (narasumber)`

### 5.2 Sumber dan izin

`Wawancara 3 narasumber pada minggu PTS-4. N1 (pemilik) diwawancarai tatap muka (±20 menit), sedangkan N2 dan N3 (pelanggan) via WhatsApp (±10–15 menit). Semua memberikan izin lisan (Izin: ya (lisan)). Nama lengkap dan nomor HP tidak disalin; narasumber disamarkan menjadi N1, N2, dan N3.`

### 5.3A Narasumber (hapus bagian ini kalau memakai Jalur B)

#### N1

| | |
|---|---|
| Peran | `pemilik` |
| Hubungan dengan kasus | `Pemilik sekaligus pengelola utama yang memahami langsung operasional harian, kendala pencatatan manual, dan sering menerima keluhan pelanggan terkait status cucian.` |
| Cara dan lama | `tatap muka, 15 menit` |
| Izin | `ya (lisan)` |

| No | Pertanyaan | Jawaban ringkas |
|---|---|---|
| 1 | `Kapan terakhir pelanggan komplain cucian belum selesai padahal nota sudah jatuh tempo, dan bagaimana Anda melacaknya?` | `1 Nov 2026, pelanggan datang pukul 09.00. Nota tertulis "ambil Sabtu", namun cucian tertunda sehari karena mesin antre dan lupa dikabari (pelanggan sudah chat 3x). Saya minta maaf, mencari nota di tumpukan berkas (±20 menit), lalu meminta karyawan segera menyetrika. Sebagai kompensasi, pelanggan diberi potongan Rp5.000.` |
| 2 | `Kapan terakhir terjadi salah hitung, dan bagaimana perhitungan tarif reguler/express dilakukan?` | `13 Okt 2026, salah tulis berat 2,6 kg (aslinya 6,2 kg), ketahuan saat pelanggan membayar dan langsung ditimbang ulang. Contoh hitungan: 11 Nov 2026 order 5,4 kg reguler x Rp6.000 = Rp32.400. 12 Nov 2026 order express 3,3 kg x Rp16.000 (reguler+express) = Rp52.800. 20 Nov 2026, pelanggan express minta info via WA dan menanyakan status hingga 4 kali.` |
| 3 | `Bagaimana pencatatan order terakhir, dan kapan pelanggan datang tanpa nota?` | `23 Nov 2026, order dicatat di nota kertas rangkap dua dan buku besar (nama, tanggal, berat, jenis, harga, catatan). 23 Okt 2026, ada pelanggan datang tanpa nota; saya mencari di buku besar (±8 menit) dan butuh total ±10 menit untuk verifikasi karena ada nama yang mirip.` |
| 4 | `Bagaimana tingginya pertanyaan status cucian, dan kapan terakhir Anda kesulitan membalasnya?` | `22 Nov 2026, ada 7 pelanggan bertanya status (4 WA, 2 telepon, 1 datang), memuncak pukul 07.35–09.30 dan 13.30–15.00. 18 Nov 2026, saat saya sedang menyetrika, chat pelanggan baru bisa dibalas 40 menit kemudian (pelanggan sudah chat 2 kali lagi). Saya minta maaf karena hal ini mengganggu pekerjaan inti.` |
| 5 | `Kapan terakhir ada cucian tertukar/hilang, dan bagaimana penyelesaiannya?` | `17 Nov 2026, 2 potong pakaian pelanggan tertukar dengan pelanggan lain yang namanya sama. Butuh waktu sehari untuk menemukannya. Pelanggan kecewa dan berkata, "Kalau dicatat jelas, harusnya tidak begini, Bu. Saya jadi ragu menitipkan cucian saya lagi di sini." Saya minta maaf dan memberi gratis cuci + potongan Rp5.000.` |

Kutipan langsung: `"Maaf banget Bu, ini kemarin mesin antre, sebentar saya cek dulu."`

#### N2

| | |
|---|---|
| Peran | `pelanggan tetap` |
| Hubungan dengan kasus | `Pelanggan tetap laundry kiloan. Relevan karena sebagai pengguna langsung yang sering menanyakan status cucian via WA, pernah menggunakan layanan express, dan menerima nota manual tanpa kode order.` |
| Cara dan lama | `Chat WhatsApp, 15 menit` |
| Izin | `ya (tertulis dichat)` |

| No | Pertanyaan | Jawaban ringkas |
|---|---|---|
| 1 | `Kapan terakhir kali nge-chat via WA/telepon pemilik laundry buat nanya status cucian? Lewat apa dan jam berapa?` | `20 Nov 2026 pukul 10:23 via WhatsApp menanyakan jam ambil. Sebelumnya pada Sabtu, 14 Nov 2026 pukul 07:17 sudah chat menanyakan status karena mendesak, lalu chat lagi pukul 12:25 ("berapa lama lagi ya kak") karena cucian belum selesai, dan baru dinyatakan siap pada pukul 13:38.` |
| 2 | `Kapan terakhir menitipkan cucian di laundry? Ceritakan dari awal sampai mengambil cuciannya?` | `Selasa, 17 November 2026. Karena sibuk dan baju menumpuk, saya titipkan agar stok pakaian aman. Cucian diambil hari Jumat, 20 November karena posisinya sudah selesai dicuci.` |
| 3 | `Saat menitipkan, Anda diberi bukti apa? Bagaimana cara mengecek status tanpa tanya pemilik?` | `Hanya diberi nota kertas (nama, tanggal, berat, harga). Tidak bisa cek status sendiri, jadi harus tanya via WA dan menunggu balasan.` |
| 4 | `Kapan terakhir pakai express? Bagaimana tahu hitungan tarifnya benar?` | `20 Nov 2026, express 3,8 kg. Tarif Rp6.000 + Rp10.000 = Rp16.000/kg (Total Rp60.800). Tetap harus pastikan berkali-kali via chat apakah selesai sebelum jam 12.00.` |
| 5 | `Saat menunggu Selasa-Jumat, apakah tahu cucian sedang diproses atau antre? Pernah menunggu lebih lama?` | `Tidak tahu status prosesnya (antre/cuci/setrika). Jika mesin antre, selesai lebih lama dari perkiraan dan saya harus chat lagi untuk memastikan.` |

Kutipan langsung: `"Saya tidak tahu apakah cucian saya sedang diantre dicuci, disetrika, atau belum diproses. Kalau mesin antre, saya harus menanyakan lagi di chat untuk memastikannya."`

#### N3

| | |
|---|---|
| Peran | `pelanggan langganan` |
| Hubungan dengan kasus | `Pelanggan langganan laundry kiloan yang rutin memakai layanan reguler dan express. Relevan karena ia tidak memiliki nomor WA pemilik, sehingga terpaksa harus datang langsung ke lokasi untuk memastikan status cucian. Hal ini menegaskan perlunya sistem pelacakan mandiri (cek kode order) agar pelanggan tidak bergantung pada chat atau nota fisik.` |
| Cara dan lama | `Chat WhatsApp, 15 menit` |
| Izin | `ya (tertulis dichat)` |

| No | Pertanyaan | Jawaban ringkas |
|---|---|---|
| 1 | `Kapan terakhir kamu menitipkan cucian di laundry? Ceritakan dari awal?` | `Rabu pagi, 18 November 2026, di laundry langganan dekat rumah. Cucian ditimbang dulu sebelum diterima. Harganya Rp5.000/kg.` |
| 2 | ` Setelah ditimbang, apakah kamu diberi nota atau kode, dan kapan selesainya?` | `Pemilik mengonfirmasi berat, lalu langsung memberi nota yang ditulisi nama. Layanan reguler selesai 2–3 hari, dan tanggal pengambilan tertulis di nota.` |
| 3 | `Bagaimana kamu tahu cucianmu sudah bisa diambil? Apa yang dilakukan kalau tanggal di nota sudah lewat atau cucian belum jadi?` | `Langsung datang berdasarkan tanggal di nota. Tidak punya nomor pemilik, jadi tidak pernah menanyakan status lewat chat. Belum pernah mendapati cucian belum jadi saat datang. Kalau itu terjadi, ia memilih menunggu di tempat.` |
| 4 | `Pernah nota hilang atau tertinggal saat mau mengambil? Bagaimana caranya mengambil cucian?` | `Pernah hilang, tapi cucian tetap bisa diambil karena sudah langganan dan cucian sudah diberi nama.` |
| 5 | `Kapan terakhir memakai layanan express, dan apakah selesai sesuai janji?` | `Sekitar Desember 2025 atau Januari 2026, untuk kebutuhan mendesak keluarga. Selesai sesuai janji: diserahkan hari ini, besok sudah bisa diambil.` |

Kutipan langsung: `"Karena ga punya nomor owner nya jadi saya langsung dateng"`

### 5.4 Temuan awal

| Kode | Temuan | Bukti |
|---|---|---|
| TA1 | `<isi>` | `<isi: kode N atau T>` |
| TA2 | `<isi>` | `<isi>` |
| TA3 | `<isi>` | `<isi>` |
