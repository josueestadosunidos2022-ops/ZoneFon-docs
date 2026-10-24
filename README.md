# ZoneFon / Teléfono Zone

[CurseForge](https://www.curseforge.com/minecraft/mc-mods/zonefon) · [Wiki](https://github.com/josueestadosunidos2022-ops/ZoneFon-docs/wiki) · [Issues](https://github.com/josueestadosunidos2022-ops/ZoneFon-docs/issues)

## English

A custom in-game phone for Minecraft Java 1.20.1 / Forge 47.4.x / Java 17. Right-click the `zonefon:phone` item to open Music, YouTube, Friends, Messages, Camera and ZoneMail. The server administrator supplies the phone according to server rules.

Use the matching **0.1.0-beta12** Server JAR on a dedicated server and Client JAR on each player. Singleplayer uses only the Client JAR, which includes integrated-server logic. Never install both in the same mods folder.

Music accepts direct public HTTPS MP3/WAV URLs; it does not extract YouTube audio. Playback is local and nearby listeners follow the server's configured radius. YouTube is optional and requires client-side MCEF Forge 2.1.6 for 1.20.1 with its Chromium runtime. Other phone functions work without MCEF. **Simple Voice Chat API 2.6.0+ is required on both sides** (companion 2.6.22). Calls can ring, answer, reject and hang up through isolated private groups. New: a personal MP3/WAV library, visible YouTube playback controls and validated larger photos. Protocol **zonefon-11**; both sides must use beta12. Actual two-player voice/UI testing remains pending. No direct ZoneCore dependency.

No private player accounts or production server configuration is included. Beta public builds are protected distributions; full graphical gameplay and multiplayer testing are separate from archive/startup checks.

## Español

Teléfono propio para Minecraft Java 1.20.1 / Forge 47.4.x / Java 17. Clic derecho con `zonefon:phone` para abrir Música, YouTube, Amigos, Mensajes, Cámara y ZoneMail. La administración entrega el teléfono según las reglas de su servidor.

Usa **0.1.0-beta12** en ambos lados: JAR Server en servidor dedicado y JAR Client en los jugadores. En mundo individual instala solo Client, que incluye servidor integrado. Nunca pongas ambos JAR en la misma carpeta.

La música usa URL HTTPS directas de MP3/WAV públicos; no extrae audio de YouTube. Cada cliente reproduce el audio y el servidor valida la proximidad. YouTube es opcional y requiere MCEF Forge 2.1.6 para 1.20.1 en el cliente y su runtime Chromium. Las demás apps funcionan sin MCEF. **Simple Voice Chat API 2.6.0+ es obligatorio en ambos lados** (acompañante 2.6.22). Permite llamadas con timbre, contestar, rechazar y colgar mediante grupos privados aislados. Añade biblioteca personal MP3/WAV, controles de YouTube visible y fotos mayores validadas. Protocolo **zonefon-11**; ambos lados deben usar beta12. Falta comprobar voz/interfaz con dos jugadores reales. No depende directamente de Core.

Distribución beta protegida, sin cuentas ni configuración privada de producción. La inspección del archivo y el arranque aislado no certifican todas las funciones gráficas ni el multijugador.

## Release files / Archivos de esta publicación

Minecraft **1.20.1** · Forge **47.4.x** · Java **17**. Check the approval status on CurseForge before downloading. / Comprueba la aprobación en CurseForge antes de descargar.

| Side / Lado | Version / Versión | CurseForge file / Archivo |
|---|---|---|
| server | 0.1.0-beta12 | [9312299](https://www.curseforge.com/minecraft/mc-mods/zonefon/files/9312299) |
| client | 0.1.0-beta12 | [9312320](https://www.curseforge.com/minecraft/mc-mods/zonefon/files/9312320) |

## Installation checklist / Lista de instalación

1. Back up your world and existing TOML files. / Respalda tu mundo y los TOML existentes.
2. Stop the game or server before replacing JAR files. / Cierra el juego o servidor antes de sustituir JAR.
3. Keep one matching version for each installation side. / Mantén una versión correspondiente a cada lado.
4. Preserve player progress and configuration; remove the previous JAR only from the active mods folder. / Conserva progreso y configuración; retira el JAR anterior de la carpeta mods activa.

## First steps / Primeros pasos

Open the phone with right-click. For Music, use a direct public HTTPS MP3/WAV link. For YouTube, install optional MCEF on the client first and use the visible player. The server does not run Chromium. / Abre el teléfono con clic derecho. Música necesita un enlace HTTPS directo a MP3/WAV público. YouTube requiere MCEF opcional en el cliente y el reproductor visible; el servidor no ejecuta Chromium.

Messages and photos are stored with the world; messages are not end-to-end encrypted. Use a trusted server and do not share passwords or private information. / Mensajes y fotos se guardan con el mundo; los mensajes no tienen cifrado de extremo a extremo. Usa un servidor de confianza y no compartas contraseñas ni información privada.

## Support / Soporte

Open an Issue with the exact mod version, Minecraft/Forge version, installation side, steps to reproduce, and a sanitized log excerpt. Remove credentials, private addresses and player data. / Abre un Issue con versión exacta del mod, Minecraft/Forge, lado de instalación, pasos y un fragmento de log sin datos privados. Elimina credenciales, direcciones privadas y datos de jugadores.

## Ownership / Titularidad

Documentation and original ZONE assets © Elgochogms. All rights reserved. This repository distributes public documentation only; it contains no mod source code, private mappings, secrets, player accounts or production configuration. / Documentación y recursos originales ZONE © Elgochogms. Todos los derechos reservados. Este repositorio contiene documentación pública; no distribuye fuentes del mod, mapas privados, secretos, cuentas ni configuración de producción.
