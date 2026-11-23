# Cara menyambung

[Kembali ke halaman utama](README.md)

[简体中文](../zh-SG/HOW_TO_LINK.md) | [繁體中文](../zh-TW/HOW_TO_LINK.md) | [English](../en-US/HOW_TO_LINK.md) | [日本語](../ja-JP/HOW_TO_LINK.md) | [한국어](../ko-KR/HOW_TO_LINK.md) | **Bahasa Melayu** | [Bahasa Indonesia](../id-ID/HOW_TO_LINK.md) | [ภาษาไทย](../th-TH/HOW_TO_LINK.md) | [Español](../es-MX/HOW_TO_LINK.md)

Jika anda tidak dapat menyambung ke VikACG, cuba ubah tetapan sambungan rangkaian atau kemas kini aplikasi yang sudah lama.

## Sambungan rangkaian

### DoH (DNS over HTTPS)

Sesetengah peranti atau pelayar mungkin tidak menyokong ciri ini. Nama ciri dan lokasi menu juga mungkin berbeza mengikut versi. Sila ikut pilihan yang tersedia pada peranti anda.

**Chrome**

- Android: Tetapan > Privasi dan keselamatan > Gunakan DNS selamat > Pilih Cloudflare.
- Komputer: Tetapan > Privasi dan keselamatan > Keselamatan > Gunakan DNS selamat > Pilih Cloudflare. Anda juga boleh memasukkan `chrome://settings/security` dalam bar alamat.

**Edge**

Komputer: Tetapan > Privasi, carian dan perkhidmatan > Keselamatan > Gunakan DNS selamat > Pilih Cloudflare. Anda juga boleh memasukkan `edge://settings/privacy` dalam bar alamat.

### DNS Peribadi Android (untuk akses aplikasi)

Android 9 dan versi lebih baharu menyokong DNS Peribadi (DoT, iaitu DNS over TLS). Sistem yang lebih baharu juga mungkin menggunakan DoH.

Tetapan sistem > Rangkaian dan Internet > DNS Peribadi > Nama hos penyedia DNS Peribadi > Masukkan `dns.google` dan simpan.

Menu mungkin berbeza mengikut pengeluar. Cari “DNS Peribadi” atau “DNS Disulitkan” dalam tetapan sistem anda.

### VPN

Bahagian ini sedang ditulis.

## Kemas kini VikACG

Laman web alternatif aplikasi: [https://www.vicacg.com](https://www.vicacg.com)

Laman web aplikasi (mungkin tidak dapat diakses di sesetengah rantau): [https://www.vikacg.com/app](https://www.vikacg.com/app)

Muat turun alternatif melalui GitHub: [https://github.com/Sailoud/VikACG_Rescue/releases](https://github.com/Sailoud/VikACG_Rescue/releases)

## Rujukan

- [Tetapan DoH pelayar (Cloudflare)](https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/encrypted-dns-browsers/)
- [Tetapan DNS selamat Chrome pada Android (Google)](https://support.google.com/chrome/answer/10468685?hl=ms&co=GENIE.Platform%3DAndroid)
- [Persediaan DNS Peribadi Android (Google)](https://developers.google.com/speed/public-dns/docs/using#android)
- [Protokol DNS disulitkan pada Android (Google)](https://security.googleblog.com/2022/07/dns-over-http3-in-android.html)
