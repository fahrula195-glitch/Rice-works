JARVIS AI OFFICE 0.2 — Reminder Edition

ISI:
- index.html: aplikasi kantor virtual
- manifest.json: identitas PWA
- sw.js: service worker/cache
- icon.svg: ikon aplikasi

CARA UJI:
1. Upload isi folder ini ke hosting statis HTTPS (misalnya GitHub Pages atau layanan static hosting gratis).
2. Buka alamat HTTPS tersebut melalui Chrome Android.
3. Tekan "Aktifkan notifikasi" dan izinkan.
4. Tambahkan pengingat dan tekan "Tes notifikasi".
5. Dari menu Chrome pilih "Tambahkan ke layar utama" / "Install app" jika tersedia.

BATASAN PENTING:
- Pengingat terjadwal dicek oleh halaman ketika aplikasi sedang berjalan.
- Browser/Android dapat menangguhkan timer saat layar terkunci, tab ditutup, atau aplikasi dihentikan.
- Service worker pada paket ini menyediakan cache dan menangani klik notifikasi; ia TIDAK menjadwalkan alarm mandiri saat browser tertutup.
- Notifikasi tes memerlukan izin notifikasi dan konteks HTTPS/localhost.
- Pengingat yang benar-benar andal saat aplikasi tertutup memerlukan push server atau aplikasi Android native dengan alarm terjadwal.
- Data jadwal disimpan lokal di browser perangkat melalui localStorage.

Paket ini prototipe gratis, bukan aplikasi yang sudah dipublikasikan di Play Store.
