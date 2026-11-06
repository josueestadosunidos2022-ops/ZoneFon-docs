# ZoneFon — Configuration / Configuración (2026-11-06)

| Side / Lado | Version / Versión |
|---|---|
| Server / Servidor | 0.1.0-beta16 |
| Client / Cliente | 0.1.0-beta16 |

## Files and limits / Archivos y límites

`config/zonefon-client.toml` stores phone preferences, return points and personal music position. Server rules are in `<mundo>/serverconfig/zonefon-server.toml`. Photos/messages belong to the world. / Preferencias, destinos y posición musical son locales; reglas en serverconfig del mundo, fotos/mensajes en el mundo.

- Local music: `<instancia>/zonefon/music`; up to 100 `.mp3`/`.wav` tracks, no subdirectories, at most 2048 folder entries scanned. / Música local con esos límites.
- Direct radio: public HTTPS MP3/WAV URLs, default10-block radius. `allowed_music_hosts` can restrict hosts. / Radio directa HTTPS y radio inicial10 bloques; dominios restringibles.
- `max_local_broadcasts`: default8 simultaneous personal-music broadcasts through Simple Voice Chat. / Ocho emisiones locales simultáneas inicialmente.
- Up to 8 shared playlists with24 tracks each. / Ocho listas con 24 canciones cada una.
- Up to 64 friends/pending requests; messages have a 6-second send interval and retain48 recent messages per player. / Hasta 64 contactos/solicitudes y48 mensajes recientes por jugador, intervalo6s.
- Photos up to 1920×1080 and512 KiB; up to 96 posts. Complex photos may reduce quality/resolution to fit. / Fotos limitadas, con reducción si hace falta.
- Up to 64 private world/server compass destinations stored locally. / Hasta 64 destinos privados locales por mundos/servidores.

## Music outputs / Salidas de música

Use Ajustes → Salida de música to choose the Java Sound device, then check Minecraft master volume and ZoneFon volume. Mis MP3 plays personally until Emitir is enabled with connected Simple Voice Chat. Cortar señal stops sharing while personal playback continues; Detener stops both. / Elige dispositivo y revisa volúmenes. Mis MP3 es personal hasta Emitir con voz conectada; Cortar señal conserva escucha, Detener para ambas.

Only encoded Opus audio is sent for local music broadcasts; file names/paths/files are not uploaded. Re-entering can resume personal listening, but shared emission must be enabled again. / Solo se envía Opus, no nombres/rutas/archivos. Tras reconectar puede volver escucha personal, pero hay que volver a activar emisión.

## YouTube and voice / YouTube y voz

MCEF runs only on clients. It may download native Chromium libraries at first launch. Each viewer opens a visible player and presses Play; the server shares validated links, not extracted YouTube audio. F9 opens player controls, F10 changes window size. Video stops on leaving the world, minimizing Minecraft or hiding its interface. / MCEF es cliente; puede descargar bibliotecas. Cada usuario abre reproductor visible y pulsa Play. F9 controles y F10 tamaño; se detiene al salir/minimizar/ocultar interfaz.

Calls need the phone and active Simple Voice Chat on both participants. Incoming calls expire after30 seconds; players already in another voice group are not moved. Configure the voice plugin's UDP connectivity separately. / Llamadas requieren teléfono y voz; caducan a 30s y no mueven jugadores de otro grupo. Configura conectividad UDP por separado.

Messages are private in the game interface but are not encrypted. Photos/messages are stored in the world, not a separate hosted service. / Mensajes privados en interfaz pero sin cifrar; fotos/mensajes se guardan en el mundo.

[Current release / Entrega actual](RELEASE-2026-11-06.md) · [README](README.md).
