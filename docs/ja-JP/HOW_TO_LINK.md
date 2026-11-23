# 接続方法

[ホームに戻る](README.md)

[简体中文](../zh-SG/HOW_TO_LINK.md) | [繁體中文](../zh-TW/HOW_TO_LINK.md) | [English](../en-US/HOW_TO_LINK.md) | **日本語** | [한국어](../ko-KR/HOW_TO_LINK.md) | [Bahasa Melayu](../ms-MY/HOW_TO_LINK.md) | [Bahasa Indonesia](../id-ID/HOW_TO_LINK.md) | [ภาษาไทย](../th-TH/HOW_TO_LINK.md) | [Español](../es-MX/HOW_TO_LINK.md)

VikACG に接続できない場合は、ネットワークの接続設定を変更するか、古いバージョンのアプリを更新してみてください。

## ネットワーク接続

### DoH（DNS over HTTPS）

端末やブラウザによっては、この機能に対応していない場合があります。機能名やメニューの位置もバージョンによって異なるため、お使いの端末の表示に従ってください。

**Chrome**

- Android 版：設定 > プライバシーとセキュリティ > セキュア DNS を使用する > Cloudflare を選択。
- パソコン版：設定 > プライバシーとセキュリティ > セキュリティ > セキュア DNS を使用する > Cloudflare を選択。アドレスバーに `chrome://settings/security` と入力して開くこともできます。

**Edge**

パソコン版：設定 > プライバシー、検索、サービス > セキュリティ > セキュア DNS を使用する > Cloudflare を選択。アドレスバーに `edge://settings/privacy` と入力して開くこともできます。

### Android のプライベート DNS（アプリからのアクセス用）

Android 9 以降はプライベート DNS（DoT、DNS over TLS）に対応しています。新しいシステムでは DoH が使われる場合もあります。

端末の設定 > ネットワークとインターネット > プライベート DNS > プライベート DNS プロバイダのホスト名 > `dns.google` と入力して保存。

メーカーによってメニューが異なる場合は、端末の設定で「プライベート DNS」または「暗号化 DNS」を検索してください。

### VPN

このセクションは現在執筆中です。

## VikACG を更新する

アプリ公式サイトの代替アクセス先：[https://www.vicacg.com](https://www.vicacg.com)

アプリ公式サイト（一部の地域では接続できない場合があります）：[https://www.vikacg.com/app](https://www.vikacg.com/app)

GitHub の代替ダウンロード先：[https://github.com/Sailoud/VikACG_Rescue/releases](https://github.com/Sailoud/VikACG_Rescue/releases)

## 参考資料

- [ブラウザの DoH 設定（Cloudflare）](https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/encrypted-dns-browsers/)
- [Android 版 Chrome のセキュア DNS 設定（Google）](https://support.google.com/chrome/answer/10468685?hl=ja&co=GENIE.Platform%3DAndroid)
- [Android のプライベート DNS 設定（Google）](https://developers.google.com/speed/public-dns/docs/using#android)
- [Android の暗号化 DNS プロトコル（Google）](https://security.googleblog.com/2022/07/dns-over-http3-in-android.html)
