# Cara terhubung

[Kembali ke halaman utama](README.md)

[简体中文](../zh-SG/HOW_TO_LINK.md) | [繁體中文](../zh-TW/HOW_TO_LINK.md) | [English](../en-US/HOW_TO_LINK.md) | [日本語](../ja-JP/HOW_TO_LINK.md) | [한국어](../ko-KR/HOW_TO_LINK.md) | [Bahasa Melayu](../ms-MY/HOW_TO_LINK.md) | **Bahasa Indonesia** | [ภาษาไทย](../th-TH/HOW_TO_LINK.md) | [Español](../es-MX/HOW_TO_LINK.md)

Jika Anda tidak dapat terhubung ke VikACG, coba ubah pengaturan koneksi jaringan atau perbarui aplikasi yang sudah lama.

## Koneksi jaringan

### DoH (DNS over HTTPS)

Beberapa perangkat atau browser mungkin tidak mendukung fitur ini. Nama fitur dan lokasi menu juga dapat berbeda menurut versi. Ikuti pilihan yang tersedia di perangkat Anda.

**Chrome**

- Android: Setelan > Privasi dan keamanan > Gunakan DNS aman > Pilih Cloudflare.
- Komputer: Setelan > Privasi dan keamanan > Keamanan > Gunakan DNS aman > Pilih Cloudflare. Anda juga dapat memasukkan `chrome://settings/security` di kolom URL.

**Edge**

Komputer: Pengaturan > Privasi, pencarian, dan layanan > Keamanan > Gunakan DNS aman > Pilih Cloudflare. Anda juga dapat memasukkan `edge://settings/privacy` di kolom URL.

### DNS Pribadi Android (untuk akses aplikasi)

Android 9 dan versi yang lebih baru mendukung DNS Pribadi (DoT, yaitu DNS over TLS). Sistem yang lebih baru juga dapat menggunakan DoH.

Setelan sistem > Jaringan & internet > DNS Pribadi > Nama host penyedia DNS Pribadi > Masukkan `dns.google` dan simpan.

Menu dapat berbeda menurut produsen. Cari “DNS Pribadi” atau “DNS Terenkripsi” di setelan sistem Anda.

### VPN

Bagian ini sedang ditulis.

## Perbarui VikACG

Situs alternatif aplikasi: [https://www.vicacg.com](https://www.vicacg.com)

Situs aplikasi (mungkin tidak dapat diakses di beberapa wilayah): [https://www.vikacg.com/app](https://www.vikacg.com/app)

Unduhan alternatif melalui GitHub: [https://github.com/Sailoud/VikACG_Rescue/releases](https://github.com/Sailoud/VikACG_Rescue/releases)

## Referensi

- [Setelan DoH browser (Cloudflare)](https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/encrypted-dns-browsers/)
- [Setelan DNS aman Chrome di Android (Google)](https://support.google.com/chrome/answer/10468685?hl=id&co=GENIE.Platform%3DAndroid)
- [Penyiapan DNS Pribadi Android (Google)](https://developers.google.com/speed/public-dns/docs/using#android)
- [Protokol DNS terenkripsi di Android (Google)](https://security.googleblog.com/2022/07/dns-over-http3-in-android.html)
