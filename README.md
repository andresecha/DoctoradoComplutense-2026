# Construye tu propia base de datos: herramientas digitales para el análisis de textos (6ª edición)

Este repositorio contiene los materiales de la sesión introductoria a las bases de datos relacionales orientada a estudiantes de doctorado en humanidades y ciencias sociales de la **Escuela de Doctorado de la Universidad Complutense de Madrid**.

La sesión se centra en la fundamentación teórica de la estructuración de la información, el modelado conceptual y el diseño de diccionarios de datos relacionales aplicados al análisis de textos.

---

## 📁 Guía de materiales del repositorio

Dispones de los materiales de la primera sección en los siguientes formatos:

*   **[`presentacion.html`](presentacion.html) (Recomendado para visualización):** Diapositivas en formato web interactivo. Puedes abrirlas con cualquier navegador (Chrome, Firefox, Safari) en tu ordenador, tablet o móvil. 
    *   *Tip:* Ábrelo en tu navegador y pulsa la tecla **`F`** para entrar en modo de pantalla completa. Navega usando las flechas de dirección de tu teclado (`←` y `→`).
*   **[`presentacion.pdf`](presentacion.pdf):** Versión estática en PDF de las diapositivas, ideal para imprimir, tomar anotaciones a mano o conservar en tu gestor de referencias.
*   **[`presentacion_marp.md`](presentacion_marp.md):** Código fuente de las diapositivas en sintaxis Markdown (compatible con el motor de diapositivas Marp). Útil si deseas inspeccionar o recompilar la presentación tú mismo.

---

## 📈 Contenido y estructura de la sesión

La formación aborda los siguientes aspectos teóricos y metodológicos:

### Diseño conceptual de bases de datos (En la pizarra y papel)
*   **Epistemología del dato:** El dato como construcción interpretativa del investigador (*capta* de Johanna Drucker) frente a la complejidad del flujo continuo de la realidad.
*   **Modelización y editorialización:** Definición de entidades, atributos y la asignación de moldes formales mediante tipos de datos físicos en SQL.
*   **El problema del formato y la sintaxis:** Normalización de fechas (estándar ISO 8601), cálculo dinámico de variables temporales, precisión de coordenadas espaciales y protección de identificadores numéricos que no admiten cálculo (códigos postales, ISBNs).
*   **Tipos de relaciones y cardinalidades:** Explicación práctica y representación esquemática en tablas de relaciones uno a muchos (`1:N`), uno a uno (`1:1`) y muchos a muchos (`N:M` mediante tablas de unión).
*   **Ejercicio colectivo:** Elaboración colaborativa en la pizarra de un Diccionario de Datos a partir de los temas de investigación de tesis de los propios estudiantes.
*   **Tipología detallada de datos SQL:** Explicación técnica y metodológica de los diferentes tipos de datos físicos en bases de datos (cadenas `VARCHAR`/`CHAR`/`TEXT`, números exactos/aproximados, temporales/intervalos, y booleanos/binarios `BLOB`), con recomendaciones de diseño para proyectos literarios y aclaración de siglas técnicas.

---

## 📚 Bibliografía fundamental de la sesión

Si deseas profundizar en la teoría de modelado de datos y humanidades digitales, te recomendamos leer:

1.  **Drucker, J.** (2011). "Humanities Approaches to Graphical Display". *Digital Humanities Quarterly (DHQ)*, 5(1).
2.  **Codd, E. F.** (1970). "A Relational Model of Data for Large Shared Data Banks". *Communications of the ACM*, 13(6).
3.  **Dourish, P.** (2017). *The Stuff of Bits: An Essay on the Materialities of Information*. MIT Press.
4.  **Flanders, J., & Jannidis, F.** (Eds.). (2018). *The Shape of Data in Digital Humanities: Modeling Texts and Textual Phenomena*. Routledge.
5.  **Vitali-Rosati, M.** (2018). *On Editorialization: Structuring Space and Authority in the Digital Age*. Routledge.
6.  **Wilkinson, M. et al.** (2016). "The FAIR Guiding Principles for scientific data management and stewardship". *Scientific Data*, 3.

---
Docente: **Andrés Echavarría** 

**Université Sorbonne nouvelle**
___
**Escuela de Doctorado+**

Universidad Complutense de Madrid.
