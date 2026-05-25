# 📚 Adquisición de Fuentes Digitales: Guías de Trabajo Interactivas

Estimadas y estimados investigadores,

¡Bienvenidos a esta sección dedicada a la **adquisición asistida de textos y fuentes orales**! 

En el ámbito de las **Humanidades Digitales**, antes de poder interrogar a nuestros datos mediante consultas SQL, realizar minería de textos o construir visualizaciones complejas, nos enfrentamos a un reto metodológico inicial y crucial: **¿cómo transformamos nuestras fuentes primarias analógicas o semiestructuradas en datos limpios, explotables y legibles por una computadora?**

Esta carpeta contiene dos guías metodológicas e interactivas en formato **Jupyter Notebook** (diseñadas para ejecutarse de forma rápida y sencilla en Google Colab) que abordan las dos vías principales de digitalización y estructuración de corpus:

1. **La vía visual/documental (OCR)**: Para digitalizar fuentes impresas, manuscritas o archivos PDF "imagen" complejos.
2. **La vía auditiva/oral (ASR)**: Para transcribir de forma automatizada entrevistas, grabaciones de archivo o ponencias.

---

## 🛠️ ¿Qué cuadernos de trabajo encontrarás aquí?

### 1. [Reconocimiento Óptico de Documentos con Mistral OCR](MistralOCR_Transcripcion.ipynb)
Este cuaderno os guiará en el uso del modelo de comprensión documental de **Mistral AI**. 
*   **¿Qué aprenderás?** A extraer no solo el texto puro de PDFs e imágenes degradadas o multilingües, sino también a conservar la estructura (encabezados, tablas en Markdown, ecuaciones en LaTeX y figuras).
*   **Enfoque metodológico**: Reflexionamos sobre los límites de los OCR tradicionales y cómo los modelos multimodales contemporáneos permiten una "editorialización" más rica y automatizada de los corpus documentales.

### 2. [Transcripción Automática de Audio con Whisper (OpenAI)](Whisper_audio_Transcripcion.ipynb)
Este cuaderno proporciona un flujo de trabajo optimizado para el uso del modelo de código abierto **Whisper** empleando la GPU gratuita de Google Colab.
*   **¿Qué aprenderás?** A transcribir archivos sonoros y de video de forma local, traducir contenidos al inglés y exportar en múltiples formatos estandarizados (`.txt`, `.srt`, `.vtt`, `.json`).
*   **Enfoque metodológico**: Discutiremos la relación entre precisión, tamaño de modelo y costo computacional, analizando cómo integrar estas transcripciones en vuestras bases de datos de investigación.

---

## 🏛️ Contexto y Genealogía del Proyecto (Huma-Num ARIANE)

Como parte de una formación rigurosa en Humanidades Digitales, es fundamental comprender la procedencia y el marco institucional de las metodologías que empleamos:

*   **Infraestructura de origen**: Estos materiales están inspirados y derivan directamente de las guías metodológicas de la infraestructura francesa para las humanidades digitales **[Huma-Num](https://www.huma-num.fr/)**.
*   **Consorcio Metodológico**: Se inscriben formalmente en las actividades del consorcio **[ARIANE](https://cst-ariane.huma-num.fr)** (cuyo objetivo es la federación, análisis, visualización y adquisición de datos de investigación digital).
*   **Grupo de Trabajo**: En particular, estas guías son una adaptación del **[Grupo de Interés en Adquisición asistida de texto (GT2)](https://consortiumariane.gitpages.huma-num.fr/axe1/GT2/GT2.html)**, especializado en coordinar herramientas y metodologías libres para la digitalización científica.

Las guías metodológicas completas y el repositorio de desarrollo original pueden consultarse aquí:
👉 **[Methodologie de la recherche Numerique (GitHub de Andrés Echavarría)](https://github.com/andresecha/Methodologie-de-la-recherche-Numerique/tree/main)**.

---

## 🎓 Sobre el Docente

Este material es adaptado y coordinado por **[Andrés Echavarría](https://cv.hal.science/andres-echavarria)** (Université Sorbonne Nouvelle / Consorcio Huma-Num ARIANE), miembro activo del consorcio e investigador en la estructuración digital de textos aplicados a las ciencias sociales y las humanidades.

---

## 💡 Consejo Pedagógico antes de Empezar

> [!TIP]
> No ejecutéis las celdas de código a ciegas. Tomados un momento para leer las explicaciones metodológicas situadas antes de cada bloque. La programación interactiva no consiste solo en presionar "Play", sino en comprender cómo cada parámetro (la clave API de Mistral, el tamaño del modelo Whisper, etc.) afecta la representatividad, calidad y fidelidad del dato textual que constituirá el núcleo de vuestra tesis.

¡Disfrutad del aprendizaje y que tengáis una excelente sesión de investigación!
