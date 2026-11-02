# Componentes de terceros incluidos en Velora

Velora (© 2026 OptiSuite · Enmanuel Gil) es gratuito para uso personal y su código es privado.
El paquete incluye, sin modificar, estos programas de terceros en la carpeta `vendor\`.
Se ejecutan como procesos independientes; Velora no los enlaza.

## yt-dlp 2026.08.19
- Uso: descarga de vídeo y audio desde páginas web.
- Licencia: **The Unlicense** (dominio público).
- Proyecto y código fuente: https://github.com/yt-dlp/yt-dlp

## FFmpeg 6.1.1 (compilación «essentials» de gyan.dev)
- Uso: unir vídeo y audio y convertir a MP3/M4A.
- Licencia: **GNU GPL versión 3** (compilado con `--enable-gpl --enable-version3`).
  Texto de la licencia: https://www.gnu.org/licenses/gpl-3.0.html
- Código fuente de FFmpeg: https://ffmpeg.org/download.html (versión 6.1.1:
  https://ffmpeg.org/releases/ffmpeg-6.1.1.tar.xz).
- Compilación usada y su configuración: https://www.gyan.dev/ffmpeg/builds/
- Puedes sustituir `vendor\ffmpeg.exe` por otra compilación de FFmpeg
  (Opciones → Vídeo → ruta de ffmpeg).
- Si necesitas el código fuente exacto correspondiente a este binario y no puedes
  obtenerlo en los enlaces anteriores, escribe a support@optisuite.app y te lo enviaremos.

## .NET 10 (Microsoft)
- Velora requiere el runtime de escritorio .NET 10, que se instala por separado.
- Licencia MIT: https://github.com/dotnet/runtime/blob/main/LICENSE.TXT
