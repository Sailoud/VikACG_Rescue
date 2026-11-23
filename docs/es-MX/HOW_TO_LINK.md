# Cómo conectarse

[Volver al inicio](README.md)

[简体中文](../zh-SG/HOW_TO_LINK.md) | [繁體中文](../zh-TW/HOW_TO_LINK.md) | [English](../en-US/HOW_TO_LINK.md) | [日本語](../ja-JP/HOW_TO_LINK.md) | [한국어](../ko-KR/HOW_TO_LINK.md) | [Bahasa Melayu](../ms-MY/HOW_TO_LINK.md) | [Bahasa Indonesia](../id-ID/HOW_TO_LINK.md) | [ภาษาไทย](../th-TH/HOW_TO_LINK.md) | **Español**

Si no puedes conectarte a VikACG, prueba ajustar la configuración de tu conexión de red o actualizar la aplicación si tienes una versión antigua.

## Conexión de red

### DoH (DNS over HTTPS)

Es posible que algunos dispositivos o navegadores no sean compatibles con esta función. Los nombres de las funciones y la ubicación de los menús también pueden variar según la versión. Sigue las opciones disponibles en tu dispositivo.

**Chrome**

- Android: Configuración > Privacidad y seguridad > Usar DNS seguro > Selecciona Cloudflare.
- Computadora: Configuración > Privacidad y seguridad > Seguridad > Usar DNS seguro > Selecciona Cloudflare. También puedes ingresar `chrome://settings/security` en la barra de direcciones.

**Edge**

Computadora: Configuración > Privacidad, búsqueda y servicios > Seguridad > Usar DNS seguro > Selecciona Cloudflare. También puedes ingresar `edge://settings/privacy` en la barra de direcciones.

### DNS privado de Android (para acceder desde la aplicación)

Android 9 y versiones posteriores admiten DNS privado (DoT, o DNS over TLS). Los sistemas más recientes también pueden usar DoH.

Configuración del sistema > Internet y redes > DNS privado > Nombre de host del proveedor de DNS privado > Ingresa `dns.google` y guarda los cambios.

Los menús pueden variar según el fabricante. Busca “DNS privado” o “DNS cifrado” en la configuración del sistema.

### VPN

Esta sección está en preparación.

## Actualizar VikACG

Sitio alternativo de la aplicación: [https://www.vicacg.com](https://www.vicacg.com)

Sitio de la aplicación (puede no estar disponible en algunas regiones): [https://www.vikacg.com/app](https://www.vikacg.com/app)

Descarga alternativa en GitHub: [https://github.com/Sailoud/VikACG_Rescue/releases](https://github.com/Sailoud/VikACG_Rescue/releases)

## Referencias

- [Configuración de DoH en navegadores (Cloudflare)](https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/encrypted-dns-browsers/)
- [Configuración de DNS seguro en Chrome para Android (Google)](https://support.google.com/chrome/answer/10468685?hl=es-419&co=GENIE.Platform%3DAndroid)
- [Configuración de DNS privado en Android (Google)](https://developers.google.com/speed/public-dns/docs/using#android)
- [Protocolos de DNS cifrado en Android (Google)](https://security.googleblog.com/2022/07/dns-over-http3-in-android.html)
