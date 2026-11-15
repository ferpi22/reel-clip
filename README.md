# REEL CLIP — Estudio Pro de Clips e IA Sin Límites

Aplicación web autónoma en español para crear, recortar (30s a 3 min), encuadrar personajes (`9:16`, `16:9`, `1:1`), generar subtítulos automáticos reales en 1 clic al estilo CapCut y exportar en **1080p** y **2K** directo desde el navegador (`MediaRecorder` + `Canvas Stream`).

## Correcciones de esta Versión
1. **Botón Directo Estilo CapCut en el Reproductor del Reel ("Generar Subtítulos Automáticos (CapCut IA)")**: ubicado directamente en la barra de controles debajo del Reel que estás editando (junto a Play y Stop) y también en el panel izquierdo.
2. **Eliminación Total de Etiquetas Genéricas (`[Voz 02:19...]`)**: se eliminó por completo el texto genérico. El motor normaliza el volumen de la voz a 16 kHz y ejecuta el modelo neuronal Whisper IA en español para extraer únicamente las palabras reales habladas en ese Reel.
3. **Subtítulos Visibles al Instante en el Reel**: al generarse o al hacer clic en cualquier línea de subtítulo en la lista izquierda, el subtítulo aparece inmediatamente renderizado sobre el Reel (incluso estando en pausa).
