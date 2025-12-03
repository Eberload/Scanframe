# Scanframe - Extract text from videos using OCR

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/J3J31N82KX)

![alt text](https://github.com/Eberload/Scanframe/blob/main/Screenshots/1.1.1.png)

Scanframe is a desktop application designed to extract text from videos using OCR (Optical Character Recognition). It allows you to play videos, pause at specific frames, extract subtitles or any text in the video, edit them, and export them in .TXT or .SRT (standard subtitles) formats. The application supports videos in MP4, MKV, AVI, and MOV formats. It works with light/dark themes and a Spanish/English interface.

![alt text](https://github.com/Eberload/Scanframe/blob/main/Screenshots/2.1.1.png)

# Execution
- Download the executable file “Scanframe.exe” from the link provided by the developer.
- No installation required: simply run the “.exe” file by double-clicking.
- If you use antivirus software, make sure it allows the file to run (false positives are common with .exe files).
- The executable includes all necessary dependencies.

![alt text](https://github.com/Eberload/Scanframe/blob/main/Screenshots/3.png)

# User Interface 

The interface is divided into two main panels:

Left panel: Video player.
- Video area.
- Bottom controls: Progress bar, forward buttons, volume, and full screen.
    
Right panel: OCR and editing module.
- OCR recognition and cancel buttons.
- Progress bar for OCR/export.
- List of extracted text blocks.
- Export buttons. 

![alt text](https://github.com/Eberload/Scanframe/blob/main/Screenshots/4.png)

# Video Player Controls
- 📁 Open: Select a video file (MP4, MKV, AVI, MOV).
- Play/Pause: Start or stop playback.
- ⏪ Rewind: Skip back 2 seconds (one click).
- ⏩ Fast Forward: Accelerates to 5x speed while holding pressed.
- 🔊 Volume: Toggles mute (M). Slider adjusts level (0-100%).
- ⛶ Full Screen: Toggles fullscreen mode.
    
![alt text](https://github.com/Eberload/Scanframe/blob/main/Screenshots/5.1.1.png)

# OCR Module: Text Extraction
- Play and pause (Space) at the selected frame.
- Click on “🔍 Extract Text.”
- The software captures the current frame and processes it with OCR.
- If text is detected, a “Text Block” is created in the right-hand list.
- If there is no text: Error message (“No text detected in the image”).
- Cancel: “❌ Cancel Extraction” (confirmed with dialog).

![alt text](https://github.com/Eberload/Scanframe/blob/main/Screenshots/6.1.png)

Scanframe project file:
- File → Save Project (Ctrl+S)
- File → Open Project (Ctrl+O)
- Format: .sfpf file

IMPORTANT
- Pause on frames with clear text to improve OCR accuracy and edit manually if there are errors.
- The start point is set automatically, but the end point is set manually. Let the video advance and click “Set End.”

# Keyboard Shortcuts
- Space ⏯️ Play/Pause video.
- Left Arrow ⏪ Rewind 2 seconds.
- Right Arrow (hold) ⏩ Fast forward 5.0x.
- Ctrl + O 🔍 Extract text from current frame.
- Ctrl + S 💾 Save current project.
- Ctrl + D 💰 Open donation link.
- Up/Down Arrow 🔊 Increase/decrease volume.
- F ⛶ Enable/disable full screen.
- M 🔇 Mute/unmute sound.

Thank you for using Scanframe! If you find it useful, consider donating.💰
https://ko-fi.com/eberload

![alt text](https://github.com/Eberload/Scanframe/blob/main/Screenshots/7.1.1.png)

# Scanframe - Extrae texto de videos mediante OCR.

![alt text](https://github.com/Eberload/Scanframe/blob/main/Screenshots/1.1.1.png)

Scanframe es una aplicación de escritorio diseñada para extraer texto de videos
utilizando OCR (Reconocimiento Óptico de Caracteres).
Permite reproducir videos, pausar en frames específicos, extraer subtítulos o cualquier texto en el video,
editarlos y exportarlos en formatos .TXT o .SRT (subtítulos estándar).

La aplicación soporta videos en formatos MP4, MKV, AVI y MOV.
Funciona en temas claro/oscuro, interfaz en español/inglés.

![alt text](https://github.com/Eberload/Scanframe/blob/main/Screenshots/2.1.1.png)

# Ejecución

  - Descarga el archivo ejecutable "Scanframe.exe" desde el enlace proporcionado por el desarrollador.
  - No requiere instalación: simplemente ejecuta el archivo ".exe" haciendo doble clic.
  - La ventana se abrirá centrada en pantalla (mínimo 1200x700 píxeles).
  - Si usas antivirus, asegúrate de que permita la ejecución (falsos positivos comunes en .exe).
  - El ejecutable es standalone, incluye todas las dependencias necesarias.

![alt text](https://github.com/Eberload/Scanframe/blob/main/Screenshots/3.png)

# Interfaz de usuario

La interfaz se divide en dos paneles principales:

  - Panel Izquierdo: Reproductor de video.
  - Área de video (fondo negro con bordes redondeados).
  - Controles inferiores: Barra de progreso, botones de navegación, volumen y pantalla completa.
  - Panel Derecho: Módulo OCR y edición.
  - Selectores de tema e idioma. Temas: Oscuro o Claro. Idiomas: Español o Inglés. 
  - Botón de reconocimiento y cancelación.
  - Barra de progreso para OCR/exportación.
  - Lista de bloques de texto extraídos (editable).
  - Botones de exportación.

![alt text](https://github.com/Eberload/Scanframe/blob/main/Screenshots/4.png)

    # Controles del Reproductor de Video

   - 📁 Abrir Video: Selecciona un archivo de video (MP4, MKV, AVI, MOV).
   - ▶️ / ⏸️ Reproducir/Pausar: Inicia o detiene la reproducción.
   - ⏪ Retroceder: Salta 2 segundos hacia atrás (una vez por clic).
   - ⏩ Avance Rápido: Acelera a 5x mientras se mantiene presionado.
   - 🔊 Volumen: Alterna silencio (M). Deslizador ajusta nivel (0-100%).
   - ⛶ Pantalla Completa: Alterna modo fullscreen.

![alt text](https://github.com/Eberload/Scanframe/blob/main/Screenshots/5.1.1.png)

# Módulo OCR: Extracción de texto
   - Abre un video.
   - Reproduce y pausa (Espacio) en el frame deseado. 
   - Haz clic en "🔍 Extraer Texto".
   - La app captura el frame actual lo procesa con OCR.
   - Resultado: Si se detecta texto, se crea un "Bloque de Texto" en la lista derecha. Muestra mensaje de éxito.
   - Si no hay texto: Mensaje de error ("No se detectó texto en la imagen").
   - Cancelar: "❌ Cancelar Extracción" (confirma con diálogo).

![alt text](https://github.com/Eberload/Scanframe/blob/main/Screenshots/6.1.png)

  # Consejos

1. Pausa en frames con textos claros para mejorar la precisión OCR y edita manualmente si hay errores.
2. El punto de inicio se configura automáticamente,
pero el final se establece manualmente, deja avanzar el video y haz clic en "establecer fin".

   # Atajos de teclado

   - Espacio: Reproducir/Pausar.
   - Flecha Izquierda: Retroceder 2s.
   - Flecha Derecha: Avance rápido 5x (mantén presionada).
   - Flecha Arriba/Abajo: +10% / -10% volumen.
   - M: Silenciar/Activar sonido.
   - F: Pantalla completa.
   - F: Salir de fullscreen.

¡Gracias por usar Scanframe! Si te es útil, considera donar.💰
 https://ko-fi.com/eberload
