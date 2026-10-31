# Visor de chats de WhatsApp

Página web (un solo `index.html`, sin servidor) para leer cómodamente un chat exportado de WhatsApp.

## Uso
1. En WhatsApp: chat → ⋮ → *Más* → *Exportar chat* (con o sin multimedia).
2. Abre `index.html` en el navegador y arrastra el `.txt` o el `.zip`.

Todo se procesa localmente en el navegador; el archivo no se sube a ningún sitio.
El `.gitignore` evita que se suban chats o fotos al repositorio por error.

## Funciones
- Burbujas tipo chat, separadores por día, colores por participante, modo oscuro.
- Fotos, vídeos, audios y documentos si se carga el `.zip` con multimedia.
- Búsqueda (ignora acentos y mayúsculas) con resaltado y salto al mensaje.
- Filtros por participante y rango de fechas; ir a una fecha concreta.
- Marcar mensajes con ☆ y exportar los marcados a `.txt`.
- Estadísticas: mensajes por persona, por hora, por día de la semana y por mes.
- Formatos de exportación de Android e iOS, 12 h / 24 h, día/mes o mes/día.
