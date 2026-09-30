# Game Matematika Mawari

Teka-teki angka untuk segala usia, dalam bentuk HTML statis untuk GitHub Pages.

| Folder | Game | Isi |
|---|---|---|
| `candy/` | Candy Magic Square | Magic square 3×3, 5 tingkat angka, mode "cari yang salah", lembar A4 |
| `24/` | Jadikan 24 | Klasik, Kejar Waktu, Mungkin?, Tanding sampai 8 pemain, lembar A4 |
| `krypto/` | Krypto | 5 angka menuju kode target, 3 tingkat, Latihan dengan petunjuk bertahap, Kejar Waktu 1/3/5 menit |
| `tebak-angka/` | Tebak Angka | Kuis 6 angka ala acara TV, target 2–3 digit, 3 tingkat, timer 30/60/90 dtk atau bebas, sesi 5 ronde, Tanding 2 pemain, Mode Kelas (proyektor) |

`index.html` di akar repo adalah halaman menu.

## Cara memasang di GitHub Pages

1. Buat repo baru di GitHub, misalnya `mawari-games` (Public).
2. Unggah **isi** folder ini (bukan foldernya) lewat *Add file → Upload files*: `index.html`, `README.md`, dan semua folder game (`candy`, `24`, `krypto`, `tebak-angka`).
3. Buka *Settings → Pages*. Pada *Build and deployment*, pilih *Deploy from a branch*, cabang `main`, folder `/ (root)`, lalu *Save*.
4. Tunggu 1–2 menit. Alamatnya menjadi `https://<nama-akun>.github.io/mawari-games/`.

## Memperbarui game

Ganti `index.html` di folder game yang bersangkutan (misalnya `krypto/index.html`) dengan versi baru, lalu commit. Perubahan tampil setelah GitHub Pages selesai memperbarui situs, biasanya dalam beberapa menit.

## Catatan

- Rekor dan pengaturan disimpan di browser masing-masing HP (localStorage). Tidak ada data yang dikirim ke server mana pun.
- Mode Tanding Online di Jadikan 24 memakai server penghubung publik PeerJS untuk mempertemukan HP. Kalau server itu sedang tidak bisa dihubungi, pakai mode Tanding **Tanpa internet** (wasit).
- Setiap game juga tetap jalan kalau file HTML-nya dibuka langsung dari folder; tautan "← Menu" hanya muncul saat dibuka dari situs.
