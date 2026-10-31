# Visor de chats de WhatsApp

Página web (un solo `index.html`, sin servidor) para leer cómodamente un chat exportado de WhatsApp.

## Uso
1. En WhatsApp: chat → ⋮ → *Más* → *Exportar chat* (con o sin multimedia).
2. Abre `index.html` en el navegador y arrastra el `.txt` o el `.zip`.

Todo se procesa localmente en el navegador; el archivo no se sube a ningún sitio.
El `.gitignore` evita que se suban chats o fotos al repositorio por error.

## Funciones
- Nombres ocultos por defecto (Persona 1, Persona 2…), con alias editables en *Filtros*.
  También se reemplazan los nombres y apodos que aparecen dentro de los mensajes.
- Recuerda el último chat en el navegador: al volver a abrir la página aparece cargado.
- Burbujas tipo chat, separadores por día, colores por participante, modo oscuro.
- Fotos, vídeos, audios y documentos si se carga el `.zip` con multimedia.
- Búsqueda (ignora acentos y mayúsculas) con resaltado y salto al mensaje.
- Filtros por participante y rango de fechas; ir a una fecha concreta.
- Al tocar un resultado o momento se abre una ventana con el contexto (mensajes de antes y después).
- Fechas clave: eventos de afuera del chat marcados en gráficos y en el chat, con comparación antes/después.
- Comparar hasta 4 palabras a la vez, por persona y mes a mes.
- Marcar mensajes con ☆ y exportar los marcados a `.txt`.
- Estadísticas: mensajes por persona, por hora, por día de la semana y por mes.
- Vista **Análisis**: veredicto con humor, premios automáticos, cara a cara, evolución semanal,
  mapa de calor día/hora, mejores momentos (con salto al chat), palabras y emojis por persona
  y detector de palabras. Todo calculado en el navegador a partir del archivo cargado.
- Formatos de exportación de Android e iOS, 12 h / 24 h, día/mes o mes/día.
