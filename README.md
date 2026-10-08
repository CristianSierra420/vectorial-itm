[README.md](https://github.com/user-attachments/files/33227365/README.md)
# Vectorial ITM — Guía de estudio

Sitio de estudio interactivo para la asignatura **Geometría Vectorial y Analítica** (XRGV03-404, ITM — Institución Universitaria, Medellín), construido a partir del material de clase y de parciales reales del curso.

🔗 **Demo en vivo:** https://claude.ai/artifact/AzcthHcgmu6LjiXH5aFkoN

---

## ⚠️ Aviso: este proyecto está hecho 100% por IA

Todo el código (HTML, CSS y JavaScript), el diseño visual y el contenido de este sitio fueron generados por **Claude (Anthropic)**, a partir de:

- Las diapositivas de clase (PDFs) proporcionadas por el profesor.
- Ejercicios y parciales reales ya presentados en el curso (fotografiados y transcritos por el estudiante).
- Instrucciones y decisiones de diseño dadas por el estudiante en una conversación con Claude.

Ninguna línea de código fue escrita manualmente por una persona. El estudiante definió el alcance, revisó el contenido y lo publicó, pero la construcción (estructura, estilos, lógica de las vistas, generación de ejercicios y su verificación matemática) fue realizada íntegramente por el modelo. Esto se documenta explícitamente por transparencia, tanto para quien lo use como para quien revise este repositorio como parte de un portafolio.

---

## Qué es

Una guía de estudio de una sola página (sin backend, sin build) para repasar y practicar los dos primeros parciales del curso: coordenadas, vectores libres y coordenados, producto escalar, producto vectorial, producto mixto, y rectas en el espacio.

## Funcionalidades

| Sección | Qué hace |
|---|---|
| **Inicio** | Mapa de los 12 temas del curso, divididos por Parcial 1 y Parcial 2 |
| **Guía** | Cada tema con concepto, fórmulas, un ejemplo real resuelto paso a paso, errores comunes y un video recomendado |
| **Formulario** | Todas las fórmulas del curso en una vista compacta de repaso rápido |
| **Práctica** | 15 preguntas de opción múltiple con retroalimentación inmediata |
| **Simulacros** | Banco de ejercicios: reales (parciales y evaluaciones de seguimiento ya presentados) y propuestos (tomados de los PDFs del profesor), con respuesta revelable bajo demanda |
| **Examen ITM** | Un parcial completo de 5 secciones (20% cada una), con la misma estructura de un examen real del ITM, incluyendo una función para **subir una foto del procedimiento resuelto a mano** y que Claude la analice y dé retroalimentación |

## Trazabilidad del contenido

Cada ejemplo y ejercicio indica su origen: `[PDF del profesor]` para contenido directo de las diapositivas, y una etiqueta de fuente específica (ej. "Parcial 2 real", "Evaluación de seguimiento") para ejercicios de exámenes reales. Las soluciones elaboradas para esta guía, cuando el material original no las traía, están marcadas explícitamente como "no oficiales".

## Stack técnico

HTML + CSS + JavaScript vanilla, un solo archivo (`index.html`), sin frameworks ni paso de build. Tipografías vía Google Fonts (Space Grotesk, JetBrains Mono). La validación de fotos usa la capacidad de IA nativa del visor de artifacts de Claude.

## Cómo verlo localmente

Abre `index.html` directamente en el navegador — no requiere servidor ni instalación.

## Nota

Guía no oficial de apoyo para estudiantes del curso. Basada en material de clase real; no sustituye al profesor ni al material oficial de la asignatura.
