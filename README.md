# REEL CLIP — Estudio Pro de Clips e IA Sin Límites

Aplicación web autónoma en español para crear, recortar (30s a 3 min), encuadrar personajes (`9:16`, `16:9`, `1:1`), generar subtítulos automáticos en 1 clic al estilo CapCut (sin necesidad de reproducir el video ni capturar audio en vivo) y exportar en **1080p** y **2K** directo desde el navegador (`MediaRecorder` + `Canvas Stream`).

## Correcciones y Mejoras de esta Versión
1. **Generador de Subtítulos en 1 Clic Estilo CapCut (Sin Reproducir ni Micrófono)**: dentro del **Estudio de Edición Pro**, al hacer clic en **Transcribir Audio del Video (IA)** (o automáticamente al abrir un Reel), la app analiza la pista de audio en segundo plano (`OfflineAudioContext` a 16 kHz + Whisper WebAssembly / detector de actividad de voz) y genera todos los bloques de subtítulos sincronizados al instante con el video en pausa.
2. **Botón para Generar en Todos los Reels e Importar .SRT/.TXT**: incluye opción para subtitular el lote completo en un clic o cargar un archivo `.SRT` externo.
