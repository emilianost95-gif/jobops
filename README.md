# ⚡ JobOps — Suite de Búsqueda de Empleo

> Herramientas para postular a empleos sin morir en el intento. 100% vanilla JS, sin dependencias, sin backend: tus datos nunca salen de tu navegador.

**[🔴 Demo en vivo →](https://emilianost95-gif.github.io/jobops/)**

Construí esta suite para mi propia búsqueda de trabajo como desarrollador front-end junior, y la libero por si le sirve a alguien más en la misma.

## 🛠 Las herramientas

| # | Herramienta | Qué hace |
|---|------------|----------|
| 01 | **Cartas** | Genera tu carta de presentación personalizada por empresa con vista previa en vivo, fecha automática y párrafo adaptable según el tipo de cargo. Exporta a PDF con un clic (impresión del navegador). |
| 02 | **LinkedIn** | 5 escenarios de mensajes listos para copiar: nota de conexión (con tope de 300 caracteres y semáforo), contacto en frío, follow-up, agradecimiento post-entrevista y respuesta a reclutadores. |
| 03 | **Tracker** | Pipeline de postulaciones con estados, alertas automáticas de follow-up a los 5 días y estadísticas (tasa de respuesta, entrevistas activas). Persistencia por exportación/importación de JSON. |
| 04 | **Match CV** | Pega el texto de un aviso y obtén tu porcentaje de match: qué skills destacar arriba del CV, cuáles te faltan y cómo cubrirlas en la carta. Pensado para pasar filtros ATS. |
| 05 | **Entrevista** | Banco de preguntas reales para entrevistas junior front-end (técnicas y conductuales, incluidas las incómodas) con el ángulo sugerido para responder cada una. |

## 🚀 Uso

1. Abre la [demo en vivo](https://emilianost95-gif.github.io/jobops/) o descarga `index.html` y ábrelo en tu navegador — funciona offline (salvo las fuentes de Google).
2. Personaliza tus datos en el objeto `CONFIG` al inicio del `<script>` (nombre, contacto, portafolio, hook profesional).
3. En el **Tracker**: guarda tus datos con `GUARDAR ARCHIVO` antes de cerrar la pestaña, y recupéralos con `CARGAR ARCHIVO`.

## 🧱 Stack

- HTML5 + CSS3 + JavaScript ES6+ **vanilla** — cero frameworks, cero build, cero dependencias de runtime.
- Un solo archivo: toda la suite vive en `index.html`.
- Diseño propio (sistema visual "EST": Orbitron + Share Tech Mono, paleta cyberpunk).
- Datos 100% locales: nada se envía a ningún servidor.

## 🗺 Roadmap

- [ ] Persistencia del tracker con `localStorage`
- [ ] Exportación del tracker a CSV
- [ ] Plantillas de mensajes en inglés
- [ ] Modo claro (para los valientes)

## 📄 Licencia

MIT — usalo, modificalo, compartilo.

---

Hecho por **Emiliano Santo Tomás** · [Portafolio](https://emilianost95-gif.github.io/Portafolio-Emiliano-Santo-Tom-s) · [GitHub](https://github.com/emilianost95-gif) · [LinkedIn](https://www.linkedin.com/in/emiliano-santo-tomás-718489291)
