# 05 · Clip Studio Paint: herramientas para revisar y corregir

Las funciones de CSP más útiles para **autorrevisarte** y acelerar las correcciones.
(Los nombres de menú pueden variar un poco según versión e idioma.)

## 1. Antes de empezar (configuración)
- [ ] Lienzo con tamaño y resolución adecuados (ilustración web: ≥ 3000 px lado largo; impresión: 300–350 ppp).
- [ ] Animación: define FPS y tamaño en *Archivo → Nuevo → Animación* (ej. 1920×1080, 24 fps).
- [ ] Referencias en la **Sub-vista** (*Ventana → Sub-vista*) con cuentagotas directo.
- [ ] Carpetas de capas con nombres: `boceto`, `linea`, `color_base`, `sombras`, `luces`, `fx`, `correccion_v2`.

## 2. Herramientas de autorrevisión

| Qué revisar | Cómo en CSP |
|---|---|
| Proporciones y simetría | **Voltear lienzo horizontal** (*Vista → Rotar/Invertir → Voltear horizontalmente*). Asígnale un atajo. |
| Lectura general | Paleta **Navegador** en pequeño, o abre una **nueva ventana** (*Ventana → Lienzo → Nueva ventana*) alejada. |
| Valores | **Capa de corrección** *Mapa de degradado* en blanco y negro arriba del todo, o capa rellena de gris en modo **Color**/**Saturación**. Ocúltala para seguir pintando. |
| Perspectiva | **Regla de perspectiva** (*Capa → Regla/Marco → Crear regla de perspectiva*). |
| Poses y anatomía | **Modelos 3D** de la paleta *Material* y **pose a partir de foto** (versiones recientes). |
| Simetría de diseño | **Regla simétrica**. |
| Comparar versiones | Duplica la carpeta, ocúltala y compara alternando visibilidad; o exporta ambas y ponlas lado a lado. |
| Consistencia de color | Guarda la paleta en **Juego de colores** por personaje/proyecto. |
| Colores fuera de lugar | **Rellenar → Referenciar otras capas** para ver huecos; capa de fondo de color chillón temporal para detectar huecos en el color plano. |

## 3. Herramientas para corregir rápido
- **Transformación libre / Deformar malla** (*Edición → Transformar → Transformación de malla*): corregir proporciones sin redibujar.
- **Licuar**: ajustes pequeños de formas.
- **Capas vectoriales** para línea: edita trazos, grosor y borra hasta la intersección.
- **Corrección de línea** (*Filtro / Herramienta Corrección de línea*) para ajustar grosor de vector.
- **Bloquear píxeles transparentes** y **Recortar a la capa inferior** (clipping) para recolorear sin salirte.
- **Capas de corrección tonal** (Tono/Saturación, Curvas, Balance de color) para ajustar color sin destruir.
- **Acciones automáticas** para tareas repetitivas (preparar capas, exportar).

## 4. Animación en CSP
- [ ] **Línea de tiempo** visible (*Ventana → Línea de tiempo*).
- [ ] **Papel cebolla** activo para revisar espaciado.
- [ ] Carpetas de animación separadas: `keys`, `breakdowns`, `inbetweens`, `clean`, `color`.
- [ ] Capa de **arcos** encima (no se exporta).
- [ ] **Mesa de luz de animación** para intermedios.
- [ ] Revisa en bucle a velocidad real **antes** del clean-up.
- [ ] Exporta: *Archivo → Exportar animación → GIF animado / Película / Secuencia de imágenes*.

## 5. Antes de exportar / entregar
- [ ] Ocultar capas de control (valores, arcos, guías).
- [ ] Zoom al 100% en toda la imagen: sin huecos, sin restos de boceto.
- [ ] Perfil de color correcto (RGB para pantalla, CMYK solo si imprenta lo pide).
- [ ] Guardar el `.clip` con versión: `nombre_v01.clip`, `nombre_v02.clip`.
- [ ] Exportar para crítica: PNG/JPG a 1500–2500 px; animación en GIF/MP4 en bucle.
- [ ] **Timelapse** (*Archivo → Timelapse*): muy útil para que quien critique vea tu proceso.

## 6. Atajos recomendados para configurar
| Acción | Sugerencia |
|---|---|
| Voltear horizontal | `H` |
| Mostrar/ocultar capa de valores | Atajo propio (vía Acción automática) |
| Papel cebolla | `O` |
| Siguiente / anterior fotograma | `.` / `,` |
| Reproducir animación | `Espacio` + atajo o botón de la línea de tiempo |
