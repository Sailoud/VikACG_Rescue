# 如何連線

[返回首頁](README.md)

[简体中文](../zh-SG/HOW_TO_LINK.md) | **繁體中文** | [English](../en-US/HOW_TO_LINK.md) | [日本語](../ja-JP/HOW_TO_LINK.md) | [한국어](../ko-KR/HOW_TO_LINK.md) | [Bahasa Melayu](../ms-MY/HOW_TO_LINK.md) | [Bahasa Indonesia](../id-ID/HOW_TO_LINK.md) | [ภาษาไทย](../th-TH/HOW_TO_LINK.md) | [Español](../es-MX/HOW_TO_LINK.md)

如果無法連線至 VikACG，可以嘗試調整網路連線方式，或更新過舊的用戶端。

## 網路連線

### DoH（DNS over HTTPS）

部分裝置或瀏覽器可能不支援此功能，功能名稱和選單位置也可能隨版本變更，請以實際版本為準。

**Chrome 瀏覽器**

- Android 版：設定 > 隱私權和安全性 > 使用安全 DNS > 選擇 Cloudflare。
- 電腦版：設定 > 隱私權和安全性 > 安全性 > 使用安全 DNS > 選擇 Cloudflare。也可以在網址列輸入 `chrome://settings/security`。

**Edge 瀏覽器**

電腦版：設定 > 隱私權、搜尋與服務 > 安全性 > 使用安全 DNS > 選擇 Cloudflare。也可以在網址列輸入 `edge://settings/privacy`。

### Android 私人 DNS（用於 App 存取）

Android 9 及以上版本支援私人 DNS（DoT，即 DNS over TLS；較新的系統也可能使用 DoH）。

系統設定 > 網路和網際網路 > 私人 DNS > 私人 DNS 供應商主機名稱 > 輸入 `dns.google` 並儲存。

不同品牌的選單可能不同，可以在系統設定中搜尋「私人 DNS」或「加密 DNS」。

### VPN

這部分文件正在撰寫中……

## 更新 VikACG

備用 App 官網：[https://www.vicacg.com](https://www.vicacg.com)

App 官網（部分地區可能無法連線）：[https://www.vikacg.com/app](https://www.vikacg.com/app)

GitHub 備用下載：[https://github.com/Sailoud/VikACG_Rescue/releases](https://github.com/Sailoud/VikACG_Rescue/releases)

## 參考資料

- [瀏覽器 DoH 設定（Cloudflare）](https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/encrypted-dns-browsers/)
- [Chrome Android 安全 DNS 設定（Google）](https://support.google.com/chrome/answer/10468685?hl=zh-Hant&co=GENIE.Platform%3DAndroid)
- [Android 私人 DNS 設定（Google）](https://developers.google.com/speed/public-dns/docs/using#android)
- [Android 加密 DNS 通訊協定說明（Google）](https://security.googleblog.com/2022/07/dns-over-http3-in-android.html)
