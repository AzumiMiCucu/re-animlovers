# re-animlovers

Repack **AnimLovers 2.48** dengan bridge scraping **in-app** (Java, tanpa middleware luar)
ke Kuramanime. Pembaruan otomatis diambil dari release terbaru repo ini lewat menu Info dalam app.

## Download
Lihat [Releases](https://github.com/AzumiMiCucu/re-animlovers/releases/latest) — unduh `AnimLovers-bridge.apk`.

## Fitur bridge
- Scraping Kuramanime v20 langsung dari dalam app (HTTP `127.0.0.1:19127`)
- Streaming kualitas HD (720p) / SD (480p) via proxy kdrive
- Download video in-app (foreground service — tetap jalan walau app ditutup)
- Pencarian cocok juga dengan judul alternatif (live search situs)
- Daftar episode cepat untuk anime panjang (pola awal+akhir, tanpa crawl semua halaman)
- Auto-update: cek release terbaru repo ini, unduh & pasang dari dialog bawaan app

## Catatan
- Repo ini publik; APK tidak menyimpan token apa pun.
- Ganti versi: bump `versionName/versionCode` di `apktool.yml`, buat release baru dengan nama aset yang sama (`AnimLovers-bridge.apk`).
