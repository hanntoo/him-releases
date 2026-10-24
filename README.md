# Hanntoo Download Manager

Download manager Windows dengan antrean, jeda/lanjut, unduhan file paralel, dukungan video YouTube/TikTok melalui yt-dlp, dan pembaruan aplikasi.

**[Unduh rilis terbaru](https://github.com/hanntoo/him-releases/releases/latest)**

Pilih `Hanntoo-Download-Manager-<versi>-Setup-x64.exe` untuk pemasangan. Paket ZIP juga tersedia; ekstrak seluruh isinya dan jalankan `HanntooDownloadManager.exe`. Runtime .NET, WinUI, serta komponen video disertakan. Diuji pada Windows 11 x64; minimum API Windows 10 1809. Installer untuk akun Windows saat ini.

## Pembaruan

Mulai versi 0.5.0, Hanntoo memeriksa pembaruan maksimal sekali sehari. Gunakan **Cek update** untuk memeriksa secara manual. Ketika versi baru tersedia, pilih **Update sekarang** atau **Nanti**. Paket diverifikasi melalui manifest bertanda tangan ECDSA dan SHA-256 sebelum pemasangan.

Unduhan aktif dijeda dan progres disimpan sebelum aplikasi ditutup. Setelah pemasangan, Hanntoo dibuka kembali dan melanjutkan unduhan yang sebelumnya aktif. Riwayat, pengaturan, dan file unduhan dipertahankan. Pengguna versi 0.4.1 atau sebelumnya perlu memasang installer 0.5.0 sekali untuk memperoleh updater.

Installer belum memiliki tanda tangan Authenticode. Tanda tangan manifest pembaruan adalah mekanisme verifikasi terpisah.

## Isi repository

Repository ini digunakan untuk distribusi paket dan informasi rilis Hanntoo. Installer, ZIP, `update.json`, `SHA256SUMS.txt`, dan catatan perubahan tersedia di **Releases**. Source Hanntoo dan kunci penandatangan tidak disertakan.

## Komponen pihak ketiga

Lisensi dan pemberitahuan komponen disertakan dalam folder `licenses/` pada paket aplikasi. Komponen video dijalankan sebagai proses terpisah:

- [yt-dlp](https://github.com/yt-dlp/yt-dlp), [source rilis yang dibundel](https://github.com/yt-dlp/yt-dlp/tree/2026.10.21).
- [FFmpeg](https://ffmpeg.org/), [build Windows BtbN](https://github.com/BtbN/FFmpeg-Builds).
- [Deno](https://github.com/denoland/deno), [source rilis yang dibundel](https://github.com/denoland/deno/tree/v2.9.8).

Dukungan video mengikuti kemampuan yt-dlp dan kondisi masing-masing situs. Playlist, live stream, DRM, dan penerusan sesi login browser belum didukung.
