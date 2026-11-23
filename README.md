# Wave Zombie

Game web berburu zombie bergaya Brave Frontier: susun squad 5 hero, lawan gerombolan
zombie wave demi wave di Mall Terbengkalai, Rumah Sakit Mati, dan Kota Mati, isi Burst
sampai penuh lalu lepaskan Ultimate. Ada gacha rekrut Survivor, dungeon/quest berurutan,
item, dan sistem Guard.

## Mainkan

- **GitHub Pages (disarankan):** buka repo ini di Settings → Pages → pilih branch
  `main` dan folder `/ (root)`, lalu buka URL `https://danryu655-ship-it.github.io/wave-zombie/`.
- **Lokal:** buka `index.html` di browser (butuh `assets.js` di folder yang sama —
  semua gambar pixel-art ada di file itu).

## Struktur

- `index.html` — game lengkap (HTML + CSS + JS). Satu-satunya gambar yang masih
  inline di file ini adalah background Mall awal; sisanya dimuat dari `assets.js`.
- `assets.js` — 19 aset gambar pixel-art (webp, base64) sebagai `window.WZIMG`:
  5 hero (potret + sprite sheet), 3 zombie + 3 sprite sheet zombie, dan 3 background
  wilayah (Mall, Rumah Sakit, Kota Mati).
- `README.md` — file ini.

## Kontrol

- Ketuk zombie untuk memilih target, ketuk tombol pedang untuk Serang, tombol perisai
  untuk Tahan (Guard: damage berikutnya separuh, Burst +10), dan ULTIMATE saat Burst
  penuh. Ada juga tombol AUTO dan mode cepat.
- Atur Squad di layar persiapan: ketuk kartu untuk memilih, ketuk kartu lain untuk
  bertukar posisi (BELAKANG posisi 1–3, DEPAN posisi 4–5). Leader dipilih lewat tombol
  khusus dari kartu terpilih.

## Catatan

Game orisinal buatan Danryu. Mekaniknya terinspirasi Brave Frontier, tapi semua
karakter, cerita, dan aset gambarnya orisinal — tidak memakai aset, nama, atau musik
dari Brave Frontier (gumi / Alim). Tidak ada afiliasi dengan Brave Frontier.
