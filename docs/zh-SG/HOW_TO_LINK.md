# 如何连接

[返回首页](README.md)

**简体中文** | [繁體中文](../zh-TW/HOW_TO_LINK.md) | [English](../en-US/HOW_TO_LINK.md) | [日本語](../ja-JP/HOW_TO_LINK.md) | [한국어](../ko-KR/HOW_TO_LINK.md) | [Bahasa Melayu](../ms-MY/HOW_TO_LINK.md) | [Bahasa Indonesia](../id-ID/HOW_TO_LINK.md) | [ภาษาไทย](../th-TH/HOW_TO_LINK.md) | [Español](../es-MX/HOW_TO_LINK.md)

如果无法连接 VikACG，可以尝试调整网络连接方式，或更新过旧的客户端。

## 网络连接

### DoH（DNS over HTTPS）

部分设备或浏览器可能不支持此功能，功能名称和菜单位置也可能随版本变化，请以实际版本为准。

**Chrome 浏览器**

- Android 版：设置 > 隐私和安全 > 使用安全 DNS > 选择 Cloudflare。
- 电脑版：设置 > 隐私和安全 > 安全 > 使用安全 DNS > 选择 Cloudflare。也可以在地址栏输入 `chrome://settings/security`。

**Edge 浏览器**

电脑版：设置 > 隐私、搜索和服务 > 安全性 > 使用安全 DNS > 选择 Cloudflare。也可以在地址栏输入 `edge://settings/privacy`。

### Android 私人 DNS（用于 App 访问）

Android 9 及以上版本支持私人 DNS（DoT，即 DNS over TLS；较新系统还可能使用 DoH）。

系统设置 > 网络和互联网 > 私人 DNS > 私人 DNS 提供商主机名 > 输入 `dns.google` 并保存。

不同品牌的菜单可能不同，可以在系统设置中搜索“私人 DNS”或“加密 DNS”。

### VPN

这部分文档正在撰写中……

## 更新 VikACG

备用 App 官网：[https://www.vicacg.com](https://www.vicacg.com)

App 官网（部分地区可能无法连接）：[https://www.vikacg.com/app](https://www.vikacg.com/app)

GitHub 备用下载：[https://github.com/Sailoud/VikACG_Rescue/releases](https://github.com/Sailoud/VikACG_Rescue/releases)

## 参考资料

- [浏览器 DoH 设置（Cloudflare）](https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/encrypted-dns-browsers/)
- [Chrome Android 安全 DNS 设置（Google）](https://support.google.com/chrome/answer/10468685?hl=zh-Hans&co=GENIE.Platform%3DAndroid)
- [Android 私人 DNS 设置（Google）](https://developers.google.com/speed/public-dns/docs/using#android)
- [Android 加密 DNS 协议说明（Google）](https://security.googleblog.com/2022/07/dns-over-http3-in-android.html)
