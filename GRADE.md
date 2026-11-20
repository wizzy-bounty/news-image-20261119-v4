# GRADE — news-image-20261119 v4 "THE WORLD ATLAS"

## Verifikasi lokal
- entry.png: 1024x1024, PNG (palette, 192 warna), **155.752 byte** (target ≤160 KB ✔)
- sha256: `7ce30ad523ab5606e13e6e34a27c9b4bfe013d226ae63da93d0dbfe4869a8d77`
- Determinisme: 5 run (3× dengan PIL, 2× jalur tanpa-PIL via PYTHONPATH
  pemblokir PIL) → sha256 IDENTIK semua ✔
- Jalur tanpa-PIL terverifikasi: fallback menyalin entry.png yang dibundel,
  byte-identik dengan hasil render PIL ✔
- Visual: gambar dibuka dan diperiksa penuh (1024px + crop masthead/strip/
  cluster pin + downscale 300px). Tanggal "THURSDAY 19 NOVEMBER 2026" benar,
  46 cerita + 2 bonus (Voyager, cruise outbreak) lengkap, tidak ada teks
  garbled/tumpang-tindih yang merusak, semua 12 pin bernomor terlihat dan
  nomornya cocok dengan indeks.

## Putaran review (2 varian)
- Varian A (samudra pucat/parchment): rapi tapi peta kurang menonjol.
- Varian B (samudra navy gelap): DIPILIH — peta jauh lebih tegas, pin merah
  kontras, komposisi terbaca sebagai satu gambar map-led bahkan di 300px.
- Perbaikan sesudah review: masthead (sub-headline sempat tertabrak rule),
  caption strip Day in Numbers (sempat meluber ke kolom sebelah), pin 33
  Shenzhen (sempat tertutup kotak Dhaka), warna caption/kompas di varian B
  (sempat gelap-di-atas-gelap).

## Penilaian jujur vs bar (5 kriteria juri)
1. Hari + tanggal: tanggal penuh besar di masthead + caption "PLATE I —
   19 NOVEMBER 2026" + footer. Kuat ✔
2. Seleksi + keluasan: 46 cerita / 7 region — cakupan TERBANYAK dari semua
   entri kita (v1 36, v2 36, v3 40) dan di atas #50 (43 cerita). Lead hari
   itu (Shenzhen, ICJ, Gulf, IPO, GTA VI) semua tampil sebagai pin. Kuat ✔
3. Terbaca: tiap cerita terbaca dari gambar + label; pin bernomor cocok
   dengan indeks. 12 pin dengan callout 2-baris — lebih informatif dari
   v2 (8 pin, label 2 kata). Kuat ✔
4. Setia fakta: semua headline dari spec v2/v3 yang terverifikasi
   19 Nov 2026; angka strip semuanya dari cerita yang sama. ✔
5. Craft: satu komposisi atlas yang jelas, terbaca di 300px. Kelemahan
   tersisa: pin 34/11 (Den Haag/Berlin) bersentuhan; bentuk benua
   disederhanakan (bukan peta presisi); kolom indeks tidak rata tingginya
   (NA/SA pendek, Asia penuh).

## Vonis
v4 jelas lebih kuat dari v3 (96.4993%, #7034) di keempat proksi: cakupan
46 vs 40 cerita, 12 pin ber-callout vs diptych tanpa peta, file 155.752 B
vs v3 yang lebih besar, konsep atlas yang beda total dari v1/v2/v3 dan
dari mayoritas front-page papan atas. Apakah tembus bar #50 (98.8869%)?
Tidak bisa dijamin — papan sangat padat (#1–#50 selisih ~0,35 poin) dan
v2 yang juga map-led hanya 98.0686%. Tapi v4 punya argumen terkuat dari
semua entri kita sejauh ini: cakupan terbanyak + peta sebagai pemimpin
halaman + angka hari itu. Layak jadi challenger resubmit (slot terakhir
hari ini) — keputusan submit di tangan parent.
