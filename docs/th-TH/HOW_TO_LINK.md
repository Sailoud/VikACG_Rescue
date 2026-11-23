# วิธีเชื่อมต่อ

[กลับหน้าหลัก](README.md)

[简体中文](../zh-SG/HOW_TO_LINK.md) | [繁體中文](../zh-TW/HOW_TO_LINK.md) | [English](../en-US/HOW_TO_LINK.md) | [日本語](../ja-JP/HOW_TO_LINK.md) | [한국어](../ko-KR/HOW_TO_LINK.md) | [Bahasa Melayu](../ms-MY/HOW_TO_LINK.md) | [Bahasa Indonesia](../id-ID/HOW_TO_LINK.md) | **ภาษาไทย** | [Español](../es-MX/HOW_TO_LINK.md)

หากไม่สามารถเชื่อมต่อ VikACG ได้ ให้ลองปรับการตั้งค่าการเชื่อมต่อเครือข่าย หรืออัปเดตแอปที่เป็นเวอร์ชันเก่า

## การเชื่อมต่อเครือข่าย

### DoH (DNS over HTTPS)

อุปกรณ์หรือเบราว์เซอร์บางรุ่นอาจไม่รองรับฟีเจอร์นี้ ชื่อฟีเจอร์และตำแหน่งเมนูอาจแตกต่างกันตามเวอร์ชัน โปรดใช้ตัวเลือกที่มีอยู่ในอุปกรณ์ของคุณ

**Chrome**

- Android: การตั้งค่า > ความเป็นส่วนตัวและความปลอดภัย > ใช้ DNS ที่ปลอดภัย > เลือก Cloudflare
- คอมพิวเตอร์: การตั้งค่า > ความเป็นส่วนตัวและความปลอดภัย > ความปลอดภัย > ใช้ DNS ที่ปลอดภัย > เลือก Cloudflare หรือป้อน `chrome://settings/security` ในแถบที่อยู่

**Edge**

คอมพิวเตอร์: การตั้งค่า > ความเป็นส่วนตัว การค้นหา และบริการ > ความปลอดภัย > ใช้ DNS ที่ปลอดภัย > เลือก Cloudflare หรือป้อน `edge://settings/privacy` ในแถบที่อยู่

### DNS ส่วนตัวของ Android (สำหรับการเข้าถึงผ่านแอป)

Android 9 ขึ้นไปรองรับ DNS ส่วนตัว (DoT หรือ DNS over TLS) โดยระบบเวอร์ชันใหม่อาจใช้ DoH ได้ด้วย

การตั้งค่าระบบ > เครือข่ายและอินเทอร์เน็ต > DNS ส่วนตัว > ชื่อโฮสต์ของผู้ให้บริการ DNS ส่วนตัว > ป้อน `dns.google` แล้วบันทึก

เมนูอาจแตกต่างกันตามผู้ผลิต ให้ค้นหา “DNS ส่วนตัว” หรือ “DNS ที่เข้ารหัส” ในการตั้งค่าระบบ

### VPN

เนื้อหาส่วนนี้อยู่ระหว่างการจัดทำ

## อัปเดต VikACG

เว็บไซต์สำรองของแอป: [https://www.vicacg.com](https://www.vicacg.com)

เว็บไซต์ของแอป (อาจเข้าไม่ได้ในบางภูมิภาค): [https://www.vikacg.com/app](https://www.vikacg.com/app)

ดาวน์โหลดสำรองผ่าน GitHub: [https://github.com/Sailoud/VikACG_Rescue/releases](https://github.com/Sailoud/VikACG_Rescue/releases)

## เอกสารอ้างอิง

- [การตั้งค่า DoH ในเบราว์เซอร์ (Cloudflare)](https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/encrypted-dns-browsers/)
- [การตั้งค่า DNS ที่ปลอดภัยของ Chrome บน Android (Google)](https://support.google.com/chrome/answer/10468685?hl=th&co=GENIE.Platform%3DAndroid)
- [การตั้งค่า DNS ส่วนตัวของ Android (Google)](https://developers.google.com/speed/public-dns/docs/using#android)
- [โปรโตคอล DNS ที่เข้ารหัสบน Android (Google)](https://security.googleblog.com/2022/07/dns-over-http3-in-android.html)
