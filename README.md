# ClaroGasto — Blog de criptomonedas para principiantes

## Cómo publicar un nuevo artículo

1. Ve a la carpeta `_posts/` en tu repositorio de GitHub
2. Haz clic en **"Add file" → "Create new file"**
3. Ponle un nombre con este formato exacto:
   ```
   YYYY-MM-DD-titulo-del-articulo.md
   ```
   Ejemplo: `2026-05-18-que-es-bitcoin.md`

4. Al principio del archivo, escribe esto (cambiando los datos):

```
---
layout: post
title: "¿Qué es Bitcoin y cómo funciona?"
date: 2026-05-18
category: "Guía básica"
reading_time: 5
excerpt: "Una breve descripción del artículo que aparecerá en la portada."
---
```

5. Debajo de esas líneas, escribe tu artículo en texto normal.
6. Haz clic en **"Commit changes"** y en 1-2 minutos aparecerá publicado.

## Formato de texto básico (Markdown)

```
## Título de sección
### Subtítulo

Párrafo normal.

**texto en negrita**
*texto en cursiva*

- elemento de lista
- otro elemento

> Cita o nota destacada
```

## Estructura del proyecto

```
clarogasto-blog/
├── _config.yml          ← Configuración del blog
├── _layouts/            ← Plantillas de diseño
│   ├── default.html     ← Plantilla base
│   └── post.html        ← Plantilla de artículo
├── _posts/              ← TUS ARTÍCULOS VAN AQUÍ
├── assets/css/main.css  ← Estilos visuales
├── index.html           ← Página principal
├── sobre-mi.md          ← Página sobre ti
└── aviso-legal.md       ← Aviso legal (necesario para AdSense)
```
