# MASoMENOS · Álgebra 1º ESO

[![Licencia: CC BY-NC-SA 4.0](https://img.shields.io/badge/Licencia-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.es)
[![Analíticas: GoatCounter](https://img.shields.io/badge/Anal%C3%ADticas-GoatCounter-brightgreen)](https://www.goatcounter.com/)
[![Sin cookies](https://img.shields.io/badge/Cookies-ninguna-blue)](https://gabrielrogo.goatcounter.com/)
[![Hecho con: HTML CSS JS](https://img.shields.io/badge/Stack-HTML%20%2B%20CSS%20%2B%20JS-orange)](.)

> **App web interactiva de Álgebra para 1º ESO** — diseñada para uso en el aula con smartphone, sin instalación, sin registro y sin publicidad.

---

## ¿Qué es MASoMENOS?

MASoMENOS es una aplicación educativa de matemáticas construida con HTML, CSS y JavaScript puro. Cubre el bloque de **Álgebra de 1º ESO** del currículo español, con un enfoque en la comprensión progresiva: del número a la letra, de la expresión a la ecuación, de la ecuación al problema real.

Está pensada para usarse **junto al cuaderno y el bolígrafo**, no en su lugar.

---

## Estructura de contenidos

| Bloque | Título | Módulos | Estado |
|--------|--------|---------|--------|
| **CD** | Actividades preliminares | M0 — Privacidad · M1 — Predecesores | ✅ Disponible |
| **1.1** | Del número a la letra | 1.1a · 1.1b · 1.1c | ✅ Disponible |
| **1.2** | Expresiones algebraicas | 1.2a · 1.2b · 1.2c · 1.2d | ⏳ En construcción |
| **1.3** | Ecuaciones de primer grado | 1.3a · 1.3b · 1.3c · 1.3d | ⏳ En construcción |
| **1.4** | Ecuaciones en contextos reales | 1.4a · 1.4b | ⏳ En construcción |

---

## Características

- 📱 **Diseño mobile-first** — columna única, zonas táctiles ≥ 52 px, sin zoom automático en iOS
- 🌙 **Tema oscuro** — familiar para el alumnado, reduce fatiga visual
- 🔒 **Módulo 0 de Privacidad obligatorio** — trabaja la Competencia Digital CD4 antes de acceder al contenido
- 🍪 **Sin cookies** — las analíticas usan GoatCounter, sin rastreo entre sesiones
- 📄 **Exportación de certificados PDF** — generados en el navegador con jsPDF, sin servidores
- 💬 **Foro de aula virtual** — enlace directo al Moodle del IES Beade
- ♿ **Accesible** — fuente mínima 16 px, contraste alto, sin animaciones bloqueantes
- 🧩 **Modular** — cada epígrafe es un fichero HTML independiente

---

## Tecnología

| Herramienta | Uso |
|-------------|-----|
| HTML + CSS + JS puro | Sin frameworks ni dependencias de build |
| [jsPDF 2.5.1](https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js) | Exportación de certificados y formularios en PDF |
| [GoatCounter](https://www.goatcounter.com/) | Analíticas sin cookies, código abierto, RGPD compliant |
| [Google Fonts](https://fonts.google.com/) | Space Grotesk · Syne · Syne Mono |
| `localStorage` | Estado del alumno (módulos completados, gate de privacidad) |

No hay pasos de compilación. Todo funciona abriendo los `.html` directamente en el navegador o sirviéndolos con cualquier servidor estático.

---

## Estructura de ficheros

```
MASoMENOS/
├── index.html                          ← Home · Gate de privacidad · Índice de bloques
├── mod0-privacidad.html                ← CD4 · Quiz obligatorio · Certificado PDF
├── cd1-predecesores.html               ← CD1 · Formulario de investigación · Export PDF
├── 1.1a-por-que-letras.html            ← Generalización y patrones
├── 1.1b-traduccion-algebraica.html     ← Lenguaje cotidiano ↔ algebraico
├── 1.1c-propiedades-aritmeticas.html   ← Propiedades y pensamiento computacional
├── LICENSE.md
└── README.md
```

---

## Competencia Digital trabajada

| Descriptor | Actividad |
|-----------|-----------|
| **CD1** — Buscar y filtrar información | Módulo M1: busca recursos de álgebra, evalúa y documenta |
| **CD3** — Comunicación y colaboración | Foro "Consejos de aula" en el aula virtual Moodle |
| **CD4** — Privacidad y seguridad | Módulo M0: cookies, datos, RGPD, salud digital |

---

## Cómo usar en clase

1. El alumno abre la URL en el móvil (sin instalación)
2. El **gate de privacidad** obliga a completar el Módulo 0 antes de acceder
3. Cada módulo tiene teoría + elemento interactivo + quiz de 4 preguntas
4. Las respuestas correctas desbloquean el **desarrollo paso a paso**
5. El progreso se guarda en `localStorage` del dispositivo (sin cuentas de usuario)

---

## Analíticas

Las estadísticas de uso son **públicas y anónimas**: [gabrielrogo.goatcounter.com](https://gabrielrogo.goatcounter.com)

GoatCounter no usa cookies, no construye perfiles de usuario y cumple el RGPD. Los datos se almacenan en servidores de la Unión Europea.

---

## Capturas de pantalla

> *(Próximamente — se añadirán capturas del índice, módulo 0 y módulos 1.1x)*

---

## Proyecto relacionado

Este proyecto es la versión de **1º ESO** de una familia de apps educativas. La app hermana para **2º Bachillerato CCSS** es [MatEBAUticas](https://gabrielrogo.github.io/MatEBAUticas).

---

## Licencia

**MASoMENOS** © 2026 Gabriel Rogo

[![CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.es)

Esta obra está licenciada bajo [Creative Commons Atribución-NoComercial-CompartirIgual 4.0 Internacional](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.es).

Puedes compartir y adaptar el material siempre que des crédito al autor, no lo uses con fines comerciales y distribuyas las obras derivadas bajo la misma licencia.
