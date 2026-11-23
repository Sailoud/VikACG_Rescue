# How to connect

[Back to home](README.md)

[简体中文](../zh-SG/HOW_TO_LINK.md) | [繁體中文](../zh-TW/HOW_TO_LINK.md) | **English** | [日本語](../ja-JP/HOW_TO_LINK.md) | [한국어](../ko-KR/HOW_TO_LINK.md) | [Bahasa Melayu](../ms-MY/HOW_TO_LINK.md) | [Bahasa Indonesia](../id-ID/HOW_TO_LINK.md) | [ภาษาไทย](../th-TH/HOW_TO_LINK.md) | [Español](../es-MX/HOW_TO_LINK.md)

If you cannot connect to VikACG, try adjusting your network connection settings or updating an outdated app.

## Network access

### DoH (DNS over HTTPS)

Some devices or browsers may not support this feature. Feature names and menu locations may also vary by version, so follow the options available on your device.

**Chrome**

- Android: Settings > Privacy and security > Use secure DNS > Select Cloudflare.
- Desktop: Settings > Privacy and security > Security > Use secure DNS > Select Cloudflare. You can also enter `chrome://settings/security` in the address bar.

**Edge**

Desktop: Settings > Privacy, search, and services > Security > Use secure DNS > Select Cloudflare. You can also enter `edge://settings/privacy` in the address bar.

### Android Private DNS (for app access)

Android 9 and later support Private DNS (DoT, or DNS over TLS; newer systems may also use DoH).

System Settings > Network & internet > Private DNS > Private DNS provider hostname > Enter `dns.google` and save.

Menus may differ by manufacturer. Search for “Private DNS” or “Encrypted DNS” in your system settings.

### VPN

This section is being written.

## Update VikACG

Alternative app website: [https://www.vicacg.com](https://www.vicacg.com)

App website (may be unavailable in some regions): [https://www.vikacg.com/app](https://www.vikacg.com/app)

Alternative download on GitHub: [https://github.com/Sailoud/VikACG_Rescue/releases](https://github.com/Sailoud/VikACG_Rescue/releases)

## References

- [Browser DoH settings (Cloudflare)](https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/encrypted-dns-browsers/)
- [Chrome secure DNS settings on Android (Google)](https://support.google.com/chrome/answer/10468685?hl=en&co=GENIE.Platform%3DAndroid)
- [Android Private DNS setup (Google)](https://developers.google.com/speed/public-dns/docs/using#android)
- [Encrypted DNS protocols on Android (Google)](https://security.googleblog.com/2022/07/dns-over-http3-in-android.html)
