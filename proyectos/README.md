# Proyectos

Cada proyecto tiene **su propia carpeta**. Las herramientas comunes (proceso, rúbricas, plantillas) siguen en [`../retroalimentacion/`](../retroalimentacion/).

## Mis proyectos

| Proyecto | Tipo | Estado | Inicio |
|---|---|---|---|
| [mascota-youtube](mascota-youtube/) | Diseño de personaje | 🔍 En revisión | 2026-11 |

> Estados sugeridos: 💡 Idea · 🎨 En proceso · 🔍 En revisión · ✅ Terminado · ⏸️ En pausa

---

## Cómo crear un proyecto nuevo

### Opción 1 · La más fácil: pídemelo
Escríbele a Claude: *“Crea el proyecto **nombre-del-proyecto**, es un/a ___ y quiero practicar ___”*. Se crea la carpeta completa y se añade a la tabla.

### Opción 2 · Desde la web de GitHub
GitHub crea las carpetas solo al crear un archivo dentro de ellas:
1. Entra a la carpeta `proyectos/` en GitHub.
2. Pulsa **Add file → Create new file**.
3. En el nombre escribe: `nombre-del-proyecto/README.md` (al escribir la `/` se crea la carpeta).
4. Copia dentro el contenido de [`_plantilla/README.md`](_plantilla/README.md) y rellénalo.
5. Pulsa **Commit changes**.
6. Repite para `nombre-del-proyecto/registro.md` (copiando [`_plantilla/registro.md`](_plantilla/registro.md)).

### Reglas para los nombres
- Minúsculas, sin acentos ni espacios, con guiones: `corto-gato-espacial`, `comic-dragones`, `fanart-2026`.

## Qué va en cada carpeta

```
nombre-del-proyecto/
├── README.md     ← ficha del proyecto: objetivo, fechas, estado
├── registro.md   ← progreso semanal y lo aprendido
├── fichas/       ← una ficha por pieza (copia de la ficha de entrega)
└── entregas/     ← exportaciones para revisar: PNG, JPG, GIF, MP4
```

### Nombres de archivos de entregas
`pieza_v01.png`, `pieza_v02.png`… Así se ve el antes/después de cada corrección.

### Los archivos `.clip` NO van aquí
Pesan mucho y GitHub no puede mostrarlos. Guárdalos en tu nube (Drive, Dropbox o Clip Studio Cloud) con la misma estructura de carpetas, y pon el enlace en el README del proyecto.
