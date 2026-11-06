# ZoneFon

An in-game phone with nine apps: music, messages, calls, camera, ZoneMail, friends, compass, YouTube and settings.

Teléfono con nueve apps: música, mensajes, llamadas, cámara, ZoneMail, amigos, brújula, YouTube y ajustes.

## Current release / Entrega actual — 2026-11-06

Minecraft **1.20.1**, Forge **47.x** (47.4.x for this release set), Java **17**. File availability follows CurseForge approval. / Disponibilidad de archivos según aprobación de CurseForge.

| Side / Lado | Version / Versión |
|---|---|
| Server / Servidor | 0.1.0-beta16 |
| Client / Cliente | 0.1.0-beta16 |

**Protocol / Protocolo:** zonefon-14.

[Downloads / Descargas](https://www.curseforge.com/projects/1762211/files) · [Release guide / Guía de novedades](RELEASE-2026-11-06.md) · [Configuration / Configuración](CONFIGURATION.md)

## English — Requirements and quick start

Simple Voice Chat API 2.6.0+ is required on both sides; configure its UDP service for voice. MCEF is optional on clients for visible YouTube playback. No Core dependency. Use beta16 on both network sides; singleplayer uses the client JAR only.

Obtain `zonefon:phone`, right-click it or press F8 with it in your inventory. Escape returns to the app home. Use Música for direct HTTPS MP3/WAV or Mis MP3 for local files; YouTube requires its visible MCEF player.

### What changed

- New midnight-blue/purple/cyan phone layout and model, F8 open/close, per-contact drafts, unread indicators and private return-point compass.
- Personal music library scanning moves off the graphics thread, supports circular play/repeat and preserves approximate position when switching output.
- Asynchronous photo gallery, zoom/pan up to 6× and a visible YouTube window that preserves its session alongside the phone when space allows.

## Español — Requisitos e inicio

API 2.6.0+ de Simple Voice Chat obligatoria en ambos lados; configura su UDP para voz. MCEF opcional solo cliente para YouTube visible. Sin dependencia de Core. Beta16 en ambos lados; individual usa solo el JAR cliente.

Obtén `zonefon:phone`, clic derecho o F8 llevándolo en inventario. Escape vuelve al inicio. Música acepta MP3/WAV HTTPS directos; Mis MP3 usa archivos locales; YouTube requiere reproductor visible MCEF.

### Novedades

- Nuevo diseño/modelo azul oscuro, morado y celeste, F8 para abrir/cerrar, borradores por contacto, avisos de no leído y brújula privada de regreso.
- Biblioteca musical fuera del hilo gráfico, reproducción circular/repetición y posición aproximada conservada al cambiar salida.
- Galería asíncrona con zoom/arrastre hasta 6× y ventana visible de YouTube que conserva sesión junto al teléfono cuando hay espacio.

## Updating / Actualizar

Stop the affected instance, back up world/configuration, replace only the previous same-mod/same-side JAR and retain player data. Never install the dedicated and client JARs of one mod together. / Detén la instancia correspondiente, respalda mundo/configuración y sustituye solo el JAR del mismo mod y lado conservando datos. Nunca instales juntos los JAR dedicado y cliente del mismo mod.

## Validation scope / Alcance de verificación

The finished delivery includes bounded automated validation and build checks. An expanded graphical session, two-player voice/music and the full production modpack are not certified by compilation or these checks.

La entrega terminada incluye comprobaciones automatizadas acotadas y compilación. No certifica sesión gráfica ampliada, voz/música con dos jugadores ni modpack completo de producción.

## Rights / Derechos

Original ZONE code and assets © Elgochogms; existing licenses and third-party notices remain applicable. This repository provides public documentation. / Código y recursos originales ZONE © Elgochogms; se conservan licencias y avisos de terceros. Este repositorio contiene documentación pública.
