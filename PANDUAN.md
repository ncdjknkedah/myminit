# Laporan Wakil Mesyuarat: Panduan Ringkas

## A. Pasang (sekali sahaja, oleh pentadbir)
1. **GitHub Pages:** muat naik `index.html`, `manifest.json`, `sw.js`, `icon.svg`, `icon-192.png` dan `icon-512.png` ke repo (cth. `ncdjknkedah/LaporanMesyuarat`). Aktifkan Pages.
   Jika mahu logo jabatan di header, tambah fail `logo.png`.
2. **Google Sheet:** cipta Sheet baharu, buka Extensions > Apps Script, tampal `Code.gs` dan tukar `KUNCI`.
   Kemudian Deploy > New deployment > Web app (Execute as: **Me**, Access: **Anyone**). Salin URL `/exec`.
3. Kongsi pautan app, URL `/exec` dan kunci akses kepada staf.

## B. Tetapan pertama (setiap pengguna)
Buka **Tetapan**, kemudian:
- isi nama dan blok tandatangan;
- semak senarai penerima laporan;
- tampal URL dan kunci, tekan **Uji sambungan**.

Untuk pasang di telefon: menu pelayar > **Add to Home Screen**.

## C. Aliran kerja
| Bila | Tab | Apa dibuat |
|---|---|---|
| Sebelum mesyuarat | 1. Maklumat | Tajuk, tarikh, tempat, mewakili siapa, laporan kepada siapa |
| Semasa mesyuarat | 2. Nota | Tampal agenda, kemudian catat nota ikut agenda. Pilih jenis nota: Makluman / Keputusan / Tindakan JKN / Perhatian Boss. 🎤 = input suara |
| Selepas mesyuarat | 3. Ringkasan | Tekan ✨ untuk senaraikan Keputusan & Perhatian Boss, kemudian ringkaskan. Tulis ulasan & cadangan |
| Hantar | 4. Laporan | Muat turun **Word** / **Cetak-PDF** (format minit bebas), **Salin WhatsApp**, atau **Hantar ke Google Sheet** |

- **Tab Tindakan:** semua tindakan susulan daripada semua mesyuarat. Tandakan apabila selesai.
- **Tab Semakan (KPPK):** baca laporan staf dan tandakan **Disemak** berserta ulasan.
  Tekan **Salin ke Mesyuarat Saya** untuk melaporkan semula kepada TPKN/PKN atas nama sendiri.

## D. Mod Rakaman (tab Nota)
1. Tekan **● Mula rakam** di awal mesyuarat. Biarkan skrin hidup dan app terbuka.
2. Setiap kali mesyuarat beralih agenda, tekan **⏭ Agenda seterusnya** pada bar merah.
   Jika tersilap, tekan **⏱** pada kad agenda yang betul untuk tanda semula.
3. Nota masih boleh ditaip semasa merakam. Butang 🎤 diktasi mungkin tidak berfungsi kerana mikrofon sedang digunakan oleh rakaman.
4. Selepas **■ Henti**, setiap agenda ada butang **▶ Dengar**. Pemain audio di bawah skrin boleh dipercepat sehingga 2×.
5. **⬇️ Audio** memuat turun fail rakaman. **📋 Salin penanda masa** menyalin senarai masa mula setiap agenda.
   Kedua-duanya berguna jika audio ditranskrip dengan aplikasi lain.

Anggaran saiz: ~15 MB sejam. Audio tidak termasuk dalam sandaran JSON dan tidak dihantar ke Google Sheet.

## E. Perhatian
- Dapatkan izin pengerusi sebelum merakam mesyuarat.
- Rekod disimpan dalam pelayar peranti. Buat **Eksport sandaran** secara berkala (Tetapan > Sandaran).
- Input suara berfungsi paling baik di Chrome (Android/desktop). Di iPhone, guna mikrofon papan kekunci.
- Sheet boleh dicapai oleh sesiapa yang ada URL dan kunci. Jangan rekod maklumat terperingkat (Sulit/Rahsia) dalam app ini.
