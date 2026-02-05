# Portafolio DIW — Tema 4 (HTML + CSS)

**Autor:** Antonio Jesús Jiménez Polonio  
**Asignatura:** Diseño de Interfaces Web (DIW)  
**Trabajo:** Tema 4 — Portafolio con HTML y CSS (sin JavaScript)

## Finalidad del trabajo
Crear un portafolio personal usando únicamente **HTML y CSS**, cumpliendo los requisitos del Tema 4:
- Estructura semántica y código limpio (1 HTML + 1 CSS)
- Estilos coherentes y eficientes
- Modo claro/oscuro mediante variables CSS (`prefers-color-scheme`)
- Uso de recursos en carpeta `assets/` (imágenes, iconos, fuentes, capturas)
- Diseño responsive
- Transiciones y animaciones (incluye una animación 3D y una avanzada basada en vistas)
- Formulario de contacto centrado y estilizado

## Despliegue
**URL del sitio:** https://portfolio-html-css-sigma-amber.vercel.app/

## Estructura del proyecto
El proyecto contiene **un único HTML** y **un único CSS**, además de la carpeta de recursos.

├─ index.html
├─ styles.css
├─ README.md
└─ assets/
    ├─ capturasPantalla/
    ├─ fuentes/
    ├─ iconos/
    └─ imagenes/


### Contenido de carpetas
- `assets/imagenes/`: imágenes del portafolio (PNG / WEBP / AVIF). Incluye imagen con transparencia y una imagen responsive con `srcset`.
- `assets/iconos/`: iconos SVG usados en “Contacto”.
- `assets/fuentes/`: Actualmente se usa Google Fonts.
- `assets/capturasPantalla/`: capturas del portafolio (escritorio y móvil) para documentación.

## Apartados del portafolio (secciones)
El portafolio está organizado en estas secciones:

- **Inicio**: presentación breve y botones de navegación (“Ver títulos” y “Contactar”) + ilustración responsive (`srcset`/`sizes`).
- **Sobre mí**: descripción personal ampliada sobre enfoque y forma de trabajar.
- **Títulos y certificaciones**: 6 tarjetas (3 títulos + 3 certificaciones) con imágenes y contenido descriptivo.
- **Habilidades**: lista de habilidades en formato etiquetas.
- **Contacto**: accesos (Email / LinkedIn / GitHub) y formulario centrado y estilizado.

## Capturas de pantalla
Las capturas deben incluir **cada apartado** en **escritorio** y en **móvil**.  
Guárdalas en: `assets/capturasPantalla/`

### Escritorio (ancho aprox. 1366px o más)
- Inicio: `assets/capturasPantalla/desktop-inicio.png`
- Sobre mí: `assets/capturasPantalla/desktop-sobre-mi.png`
- Títulos y certificaciones: `assets/capturasPantalla/desktop-titulos.png`
- Habilidades: `assets/capturasPantalla/desktop-habilidades.png`
- Contacto: `assets/capturasPantalla/desktop-contacto.png`

### Móvil (ancho aprox. 390px o similar)
- Inicio: `assets/capturasPantalla/movil-inicio.png`
- Sobre mí: `assets/capturasPantalla/movil-sobre-mi.png`
- Títulos y certificaciones: `assets/capturasPantalla/movil-titulos.png`
- Habilidades: `assets/capturasPantalla/movil-habilidades.png`
- Contacto: `assets/capturasPantalla/movil-contacto.png`

> Nota: cuando estén creadas, estas imágenes deben existir en la ruta indicada para que la documentación sea comprobable.

## Requisitos técnicos (checklist)
- [x] Solo 1 archivo HTML (`index.html`) y 1 archivo CSS (`styles.css`).
- [x] Carpeta `assets/` con imágenes, iconos y capturas.
- [x] Variables CSS para modo claro/oscuro (`prefers-color-scheme`).
- [x] 2 tipografías libres (Google Fonts: Inter + Playfair Display).
- [x] Al menos 3 iconos SVG (Email, LinkedIn, GitHub).
- [x] Al menos 3 imágenes en formatos distintos: PNG, WEBP y AVIF (sin JPG/GIF).
- [x] Al menos una imagen con transparencia (PNG).
- [x] Imagen responsive con `srcset`/`sizes` (ilustración del hero).
- [x] Mínimo 3 transiciones CSS distintas (nav, botones, tarjetas).
- [x] Mínimo 3 animaciones CSS distintas (entrada hero, iconos, 3D).
- [x] 1 animación avanzada basada en vistas (`animation-timeline: view()` cuando está soportado).
- [x] Formulario centrado y estilizado.
- [x] Diseño responsive sin roturas en móvil/tablet/escritorio.
- [x] Control de versiones: mínimo 1 commit por día en 5 días distintos (comprobar en historial del repo).
