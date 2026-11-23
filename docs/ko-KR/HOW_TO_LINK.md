# 접속 방법

[홈으로 돌아가기](README.md)

[简体中文](../zh-SG/HOW_TO_LINK.md) | [繁體中文](../zh-TW/HOW_TO_LINK.md) | [English](../en-US/HOW_TO_LINK.md) | [日本語](../ja-JP/HOW_TO_LINK.md) | **한국어** | [Bahasa Melayu](../ms-MY/HOW_TO_LINK.md) | [Bahasa Indonesia](../id-ID/HOW_TO_LINK.md) | [ภาษาไทย](../th-TH/HOW_TO_LINK.md) | [Español](../es-MX/HOW_TO_LINK.md)

VikACG에 접속할 수 없다면 네트워크 연결 설정을 변경하거나 오래된 앱을 업데이트해 보세요.

## 네트워크 연결

### DoH (DNS over HTTPS)

일부 기기나 브라우저는 이 기능을 지원하지 않을 수 있습니다. 기능 이름과 메뉴 위치도 버전에 따라 달라질 수 있으므로 사용 중인 기기의 화면을 참고하세요.

**Chrome**

- Android 버전: 설정 > 개인 정보 보호 및 보안 > 보안 DNS 사용 > Cloudflare 선택.
- 데스크톱 버전: 설정 > 개인 정보 보호 및 보안 > 보안 > 보안 DNS 사용 > Cloudflare 선택. 주소창에 `chrome://settings/security`를 입력해도 됩니다.

**Edge**

데스크톱 버전: 설정 > 개인 정보, 검색 및 서비스 > 보안 > 보안 DNS 사용 > Cloudflare 선택. 주소창에 `edge://settings/privacy`를 입력해도 됩니다.

### Android 비공개 DNS (앱 접속용)

Android 9 이상은 비공개 DNS(DoT, DNS over TLS)를 지원합니다. 최신 시스템에서는 DoH를 사용할 수도 있습니다.

시스템 설정 > 네트워크 및 인터넷 > 비공개 DNS > 비공개 DNS 공급자 호스트 이름 > `dns.google` 입력 후 저장.

제조사에 따라 메뉴가 다를 수 있습니다. 시스템 설정에서 “비공개 DNS” 또는 “암호화 DNS”를 검색해 보세요.

### VPN

이 항목은 현재 작성 중입니다.

## VikACG 업데이트

앱 공식 웹사이트 대체 주소: [https://www.vicacg.com](https://www.vicacg.com)

앱 공식 웹사이트(일부 지역에서는 접속이 불가능할 수 있음): [https://www.vikacg.com/app](https://www.vikacg.com/app)

GitHub 대체 다운로드: [https://github.com/Sailoud/VikACG_Rescue/releases](https://github.com/Sailoud/VikACG_Rescue/releases)

## 참고 자료

- [브라우저 DoH 설정 (Cloudflare)](https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/encrypted-dns-browsers/)
- [Android용 Chrome 보안 DNS 설정 (Google)](https://support.google.com/chrome/answer/10468685?hl=ko&co=GENIE.Platform%3DAndroid)
- [Android 비공개 DNS 설정 (Google)](https://developers.google.com/speed/public-dns/docs/using#android)
- [Android 암호화 DNS 프로토콜 안내 (Google)](https://security.googleblog.com/2022/07/dns-over-http3-in-android.html)
