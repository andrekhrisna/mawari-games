# Game Matematika Mawari

Teka-teki angka untuk segala usia, dalam bentuk HTML statis untuk GitHub Pages.

| Folder | Game | Isi |
|---|---|---|
| `candy/` | Candy Magic Square | Magic square 3×3, 5 tingkat angka, mode "cari yang salah", lembar A4 |
| `24/` | Jadikan 24 | Klasik, Kejar Waktu, Mungkin?, Tanding sampai 8 pemain, lembar A4 |
| `krypto/` | Krypto | 5 angka menuju kode target, 3 tingkat, Latihan dengan petunjuk bertahap, Kejar Waktu 1/3/5 menit |
| `sudoku-hitung/` | Sudoku Hitung | Teka-teki kandang (Mathdoku) 3×3–6×6, pilihan operasi + − / + − × / semua, jawaban selalu tunggal, catatan pensil, petunjuk, rekor waktu |
| `mesin-fungsi/` | Mesin Fungsi | Teka-teki fungsi SMP–SMA: Rakit Mesin (langkah minimal dihitung komputer), Tebak Mesin (cari rumus dari masukan–keluaran), Mesin Terbalik (masukan & f⁻¹), Komposisi (nilai, rumus f∘g/g∘f, cari g); Mudah/Sedang/Sulit; pembahasan; Harian 4 soal, Latihan, Kelas 2 tim |
| `teka-teki-simbol/` | Teka-Teki Simbol | Teka-teki gambar ala medsos untuk SMP–SMA (SPLDV/SPLTV): Mudah berantai, Sedang dengan eliminasi dan ×, Sulit 3–4 simbol dengan nilai negatif; selalu tepat satu jawaban; isi nilai tiap simbol + jawaban akhir; bintang; pembahasan langkah demi langkah; Harian (tanpa ulang 365 hari), Latihan, Kelas 2 tim |
| `tebak-persamaan/` | Tebak Persamaan | Teka-teki SMP–SMA mirip Wordle untuk persamaan: Mudah 7 kotak, Sedang 8 (urutan operasi), Sulit 10 (pangkat, kurung, negatif); tebakan harus persamaan benar; sifat tukar dihitung menang; soal harian tanpa ulang 365 hari + statistik & salin hasil; Latihan; Kelas 2 tim |
| `kuis-kelas/` | Kuis Kelas | Kuis buatan guru (pilihan ganda 2–4, benar/salah, angka, gambar) atau matematika otomatis; mode Satu Layar (2–6 tim, offline) atau HP Murid (kode/QR, real-time lewat PeerJS, bonus kecepatan opsional, unduh hasil CSV); ekspor/impor file kuis |
| `petualangan-perkalian/` | Petualangan Tabel Perkalian | Peta 15 pulau (×1–×15, urutan mudah dulu); tiap pulau: berurutan, acak, pembagian, Bos berwaktu; bintang 1–3 membuka tahap/pulau; maks. 6 profil anak + profil Kelas (semua terbuka, 2 Tim, layar besar) |
| `lanjutkan-pola/` | Lanjutkan Pola | Pola gambar, + −, × ÷ & campuran, bangun bertumbuh; pilihan ganda dengan penjelasan aturan; soal ambigu otomatis dibuang; 10 soal, 90 detik, 2 Tim; layar besar |
| `pecahan-pizza/` | Pecahan Pizza | Pecahan dengan pizza & cokelat batang: mengenal (warnai/potong/baca), senilai, membandingkan, jumlah & kurang; Mudah/Sulit; 2 Tim; layar besar |
| `warung-kembalian/` | Warung Kembalian | Jadi kasir: susun uang kembalian dari laci (pecahan rupiah bergaya, bukan tiruan uang asli), bonus lembar paling sedikit, 1 kali coba lagi; 4 tingkat; 2 Tim; layar besar |
| `jam-berapa/` | Jam Berapa? | Membaca jam: baca jam analog, atur jarum (jarum pendek ikut), kalimat waktu (lewat/kurang/setengah), lama waktu, format 24 jam & pagi–malam; 4 tingkat; 2 Tim; layar besar |
| `garis-bilangan/` | Garis Bilangan | Taruh pin & baca letak angka di garis: bulat 0–10/20/100/1000, pecahan 0–1/0–2, desimal 0–1/0–10, negatif −10–10; Mudah/Sulit; 10 soal; 2 Tim; layar besar proyektor |
| `ganjil-genap/` | Ganjil atau Genap? | Refleks: ketuk kiri (ganjil) / kanan (genap), 3 dtk makin cepat 5% sampai 0,6 dtk, jebakan bom 💣, angka makin besar, penjelasan lewat angka satuan |
| `kejar-urutan/` | Kejar Urutan | Tabel Schulte: ketuk 1–9/16/25 berurutan secepatnya, stopwatch milidetik, salah ketuk +1 dtk, petunjuk bisa dimatikan, peringkat 3 tercepat dengan nama |
| `pas-10/` | Pas 10 | Puzzle cepat 60 detik: sambungkan angka bersebelahan (8 arah) sampai jumlahnya 10, blok meledak & jatuh, combo sampai ×5, hukuman −3 detik |
| `benar-salah/` | Benar atau Salah? | Adu refleks: geser kartu benar/salah, soal menjebak, 3 kecepatan (Santai/Normal/Kilat), pilihan operasi, rekor streak |
| `silang-hitung/` | Silang Hitung | Teka-teki silang persamaan (ala Equate): papan 10×10, rak 9 kotak, seret sentuh atau ketuk, persamaan silang, petak bonus, tersimpan otomatis |
| `tebak-angka/` | Tebak Angka | Kuis 6 angka ala acara TV, target 2–3 digit, 3 tingkat, timer 30/60/90 dtk atau bebas, sesi 5 ronde, Tanding 2 pemain, Mode Kelas (proyektor) |

`index.html` di akar repo adalah halaman menu.

## Cara memasang di GitHub Pages

1. Buat repo baru di GitHub, misalnya `mawari-games` (Public).
2. Unggah **isi** folder ini (bukan foldernya) lewat *Add file → Upload files*: `index.html`, `README.md`, dan semua folder game (`candy`, `24`, `krypto`, `tebak-angka`, `sudoku-hitung`, `silang-hitung`, `benar-salah`, `pas-10`, `kejar-urutan`, `ganjil-genap`, `garis-bilangan`, `jam-berapa`, `warung-kembalian`, `pecahan-pizza`, `lanjutkan-pola`, `petualangan-perkalian`, `kuis-kelas`, `tebak-persamaan`, `teka-teki-simbol`, `mesin-fungsi`).
3. Buka *Settings → Pages*. Pada *Build and deployment*, pilih *Deploy from a branch*, cabang `main`, folder `/ (root)`, lalu *Save*.
4. Tunggu 1–2 menit. Alamatnya menjadi `https://<nama-akun>.github.io/mawari-games/`.

## Memperbarui game

Ganti `index.html` di folder game yang bersangkutan (misalnya `krypto/index.html`) dengan versi baru, lalu commit. Perubahan tampil setelah GitHub Pages selesai memperbarui situs, biasanya dalam beberapa menit.

## Catatan

- Rekor dan pengaturan disimpan di browser masing-masing HP (localStorage). Tidak ada data yang dikirim ke server mana pun.
- Mode Tanding Online di Jadikan 24 memakai server penghubung publik PeerJS untuk mempertemukan HP. Kalau server itu sedang tidak bisa dihubungi, pakai mode Tanding **Tanpa internet** (wasit).
- Setiap game juga tetap jalan kalau file HTML-nya dibuka langsung dari folder; tautan "← Menu" hanya muncul saat dibuka dari situs.
