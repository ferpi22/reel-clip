# REEL CLIP — Estudio Pro de Clips e IA Sin Límites

Aplicación web autónoma en español para crear, recortar (30s a 3 min), encuadrar personajes (`9:16`, `16:9`, `1:1`), subtitular automáticamente desde el audio real del video y exportar reels en **1080p** y **2K** directo desde el navegador (`MediaRecorder` + `Canvas Stream`).

## Novedades de esta versión
- **Reconocimiento Automático de Voz a Texto (IA en el navegador)**: al cargar un video desde tu PC, la app extrae y decodifica automáticamente la pista de audio (16 kHz) y ejecuta el motor neuronal Whisper WebAssembly (`Xenova/whisper-tiny`) en español para transcribir lo que se dice en el video y escribir los subtítulos sincronizados en todos los Reels y en el Editor Pro.
- **Modo Captura de Audio en Vivo (`SpeechRecognition` ES-AR)**: permite transcribir en tiempo real el audio mientras se reproduce un video o enlace externo.
- **Edición en vivo**: todos los subtítulos reconocidos aparecen listos en el panel izquierdo del Estudio de Edición Pro para corregir palabras, cambiar fuentes, colores o quemarlos al exportar en 1080p y 2K.
