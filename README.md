# Brief de Proyecto — SG Canvas & Publicidad

## 1. Resumen del proyecto

- **Tipo de proyecto:** Landing page (página única).
- **Base de trabajo:** Se parte de una **plantilla HTML ya existente**. No se debe rediseñar la estructura de secciones de la página; se debe **respetar y seguir la estructura de la plantilla base**.
- **Prompt inicial:** Ya se entregó por separado un prompt inicial para adaptar la plantilla al negocio. Este documento es un complemento: reúne la información real del negocio y los lineamientos de marca/estilo que deben aplicarse sobre esa plantilla.

---

## 2. Información del negocio

Datos extraídos directamente de los materiales de marketing del negocio (carpeta `imagenes/`).

- **Nombre del negocio:** SG Canvas & Publicidad
- **Slogan / tagline:** "De la idea al canvas. Tu marca, tu arte."
- **Giro:** Impresión y publicidad, artículos promocionales, y fabricación de cuadros decorativos en tela canvas.
- **Teléfono / WhatsApp (dato obligatorio):**
  - 442 115 2048
  - 442 356 2349
- **Redes sociales (Facebook):**
  - SG Publicidad Impresa & Promociones
  - Canvas Gallery

> No se encontró dirección física ni horario de atención en el material disponible, por lo que no se incluyen. Si el negocio los proporciona más adelante, deben agregarse siguiendo la estructura de la plantilla.

### Catálogo de servicios y productos

Esta es información de contenido del negocio (no una sugerencia de secciones ni de layout). Debe incorporarse como texto/datos dentro de la estructura ya definida por la plantilla base.

**Producto estrella — Cuadros en tela canvas**
- Más de 25,000 imágenes a elegir, o imagen propia del cliente.
- Fabricación a la medida que el cliente necesite.
- Envíos a todo México.
- Calidad premium, precios justos y garantía total.

**Impresión y publicidad exterior**
- Lonas y espectaculares
- Caballetes y stands
- Anuncios luminosos y anuncios en letras 3D
- Vinil de corte / microperforado
- Stickers y etiquetas adhesivas rotuladas
- Volantes, carteles y trípticos
- Banderines

**Papelería comercial y corporativa**
- Tarjetas de presentación
- Hojas membretadas y folders personalizados
- Menús y catálogos
- Calendarios personalizados
- Notas de remisión (foliadas, en papel autocopiante)
- Recetarios médicos y dentistas (con formato de registro de paciente)
- Imanes para refrigerador

**Textil y artículos promocionales**
- Playeras, sudaderas y uniformes
- Artículos promocionales personalizados

**Técnicas de impresión disponibles**
- DTF, Serigrafía, Láser, Offset digital

---

## 3. Identidad de marca (branding)

Paleta extraída directamente del logo del negocio.

| Uso sugerido | Color | HEX |
|---|---|---|
| Acento principal (cian/turquesa) | 🟦 | `#00F5E3` |
| Transición de degradado (azul-verdoso) | 🔵 | `#05AECF` |
| Acento secundario (magenta/violeta) | 🟣 | `#AC2797` |
| Transición de degradado (púrpura profundo) | 🟪 | `#7E1F85` |
| Texto / wordmark (gris carbón oscuro) | ⬛ | `#333B46` |
| Fondo claro | ⬜ | `#FAFAFA` |
| Fondo oscuro (para secciones premium) | ⬛ | `#14161C` |

El logo usa un degradado cian → magenta sobre un ícono geométrico tipo "S/G" entrelazado, con el nombre en un gris carbón oscuro. Este contraste (colores vibrantes + neutro oscuro serio) debe ser el hilo conductor de la identidad visual del sitio.

**Tipografía sugerida:**
- Encabezados / títulos: una tipografía sans-serif geométrica y de trazo grueso (por ejemplo, **Poppins** o **Montserrat**, en Bold/ExtraBold), en línea con el estilo del logotipo.
- Texto de cuerpo: una sans-serif limpia y legible (por ejemplo, **Inter** o **Work Sans**), en pesos Regular/Medium.

---

## 4. Estilo visual obligatorio

El sitio debe transmitir:
- Estilo **premium, enterprise y corporativo** de marca.
- Nivel **"big tech"**: elegante y a la vez minimalista.

---

## 5. Efectos y animaciones requeridos

- Efectos visuales y **animaciones al hacer scroll** a lo largo de toda la página.
- **Pantalla de carga (preloader)** al iniciar el sitio, con un spinner de carga acompañado del logo del negocio.
- **Animación en el título del hero**, usando efecto de máquina de escribir (typewriter), cambio de color en las letras, u otro efecto tipográfico animado equivalente.

---

## 6. Instrucciones sobre assets (carpeta `imagenes/`)

- El **logo** (`logo.jpeg`) viene **con fondo** (gris claro). Debe removerse el fondo antes de usarlo en cualquier parte del sitio (header, preloader, favicon, etc.), dejándolo en PNG con transparencia.
- La carpeta contiene **dos imágenes que no pertenecen a este negocio** (`Asesoria Fiscal Aguascalientes.png` y `asesoria contable y fiscal.png`, de una asesoría contable/fiscal). Deben descartarse; no corresponden a SG Canvas & Publicidad.
- Varios de los archivos de la carpeta son **flyers ya maquetados** (con texto y logo incrustados en la imagen). Estos sirven como **referencia de contenido y estilo**, pero no deben usarse tal cual como imágenes finales del sitio — de ahí debe extraerse el texto/información y, cuando aplique, recortarse solo la fotografía de producto limpia (sin texto de flyer superpuesto).

---

## 7. Nota para el desarrollador

Este brief es un punto de partida. El desarrollador puede **iterar sobre el proyecto dándole instrucciones a Claude las veces que sea necesario**, ajustando textos, estilos, animaciones o cualquier detalle hasta lograr el resultado deseado.

---

## 8. Checklist de trabajo

- [ ] Remover el fondo del logo y dejarlo en PNG transparente.
- [ ] Descartar del proyecto las imágenes que no pertenecen al negocio.
- [ ] Extraer el texto/producto útil de los flyers y descartar el flyer maquetado como imagen final.
- [ ] Aplicar la paleta de colores de marca (HEX) sobre la plantilla base.
- [ ] Aplicar la tipografía sugerida (encabezados y cuerpo de texto).
- [ ] Incorporar la información del negocio (teléfono, servicios/productos, redes sociales) dentro de la estructura ya existente de la plantilla.
- [ ] Implementar el preloader con spinner + logo.
- [ ] Implementar animaciones de scroll en toda la página.
- [ ] Implementar la animación del título del hero (máquina de escribir / cambio de color).
- [ ] Verificar que el estilo general se sienta premium, corporativo y minimalista ("big tech").
- [ ] Revisar responsividad en mobile y desktop.
- [ ] Iterar con Claude Code hasta cerrar el resultado final.
