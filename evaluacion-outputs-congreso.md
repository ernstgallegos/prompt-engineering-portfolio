# Prompt: Evaluación académica de resúmenes para congreso internacional

## 🌟 Objetivo
Diseñar un prompt que permita evaluar automáticamente resúmenes de ponencias para un congreso académico, utilizando criterios claros de pertinencia, calidad argumentativa, lenguaje, aporte y coherencia interna. El modelo debe actuar como par evaluador y devolver una tabla Markdown con puntuaciones y justificaciones.

## 👀 Prompt utilizado
```
Actuá como un revisor académico trabajando como par evaluador en el VI Congreso Latinoamericano y Caribeño de Ciencias Sociales de la FLACSO “Pensar el futuro. Transformaciones sociales en América Latina y el Caribe”.

Tu tarea es evaluar si los siguientes resúmenes de posibles ponencias cumplen con:

- Pertinencia del contenido de la propuesta según los ejes del Congreso.
- Aporte al campo de conocimiento.
- Cumplimiento del objetivo planteado.
- Uso de un lenguaje claro y adecuado.
- Coherencia argumentativa interna.

Para cada criterio:
- Asigná una puntuación de 1 a 5.
- Justificá brevemente tu decisión.

Formato: tabla Markdown con columnas: Criterio | Puntuación (1-5) | Justificación breve.

Contenido a evaluar:
--
📄 Resumen 1
Eje 3. Economía, desarrollo y sociedad
Subeje: Estado, política y desarrollo
Título: Modelos de Vinculación Tecnológica en Universidades del Siglo XXI: Lecciones desde UNAHUR en sus primeros diez años
Autor: Ernesto Gallegos – Universidad Nacional de Hurlingham / Comisión de Investigaciones Científicas de la Provincia de Buenos Aires
📩 ernestogallegos@unahur.edu.ar
Resumen:
Este trabajo aborda la construcción del modelo de vinculación tecnológica de la Universidad Nacional de Hurlingham (UNAHUR), creada en 2014. A lo largo de su primera década, la UNAHUR ha desarrollado un conjunto de dispositivos, normativas y enfoques de gestión que permiten pensar una arquitectura institucional de vinculación tecnológica orientada al desarrollo territorial.
El objetivo de esta ponencia es analizar esta experiencia para identificar elementos replicables en otras universidades públicas del siglo XXI. Se propone como hipótesis que la UNAHUR ofrece un modelo innovador, basado en la articulación entre docencia, investigación y vinculación, con fuerte anclaje en la demanda social y productiva.
La metodología combina análisis documental (reglamentos, convocatorias, resoluciones) y entrevistas a actores institucionales y territoriales. Se abordan casos como la convocatoria PIUNAHUR, el Banco de Proyectos PDTS, el Laboratorio de Investigación Aplicada (LIAPT) y la incubadora universitaria de emprendimientos.
Entre los principales resultados se destacan la consolidación de una estructura organizativa flexible, el impulso a la cultura institucional de transferencia y el desarrollo de una estrategia de innovación inclusiva. Asimismo, se identifican desafíos relacionados con la evaluación, la sostenibilidad y la articulación con políticas públicas nacionales y provinciales.
La experiencia de UNAHUR permite reflexionar sobre el papel de las universidades en la producción de conocimiento con impacto y sentido social, ofreciendo claves para el diseño de políticas de CTI orientadas al desarrollo.
Palabras clave: universidad pública, vinculación tecnológica, políticas de CTI, innovación inclusiva, desarrollo territorial.
--
📄 Resumen 2
Eje 3. Economía, desarrollo y sociedad
Subeje: Alternativas de desarrollo en un mundo pos-neoliberal
Título: De la Teoría a la Práctica: Implementación de los PDTS en la Universidad Nacional de Hurlingham
Autor: Ernesto Gallegos – Universidad Nacional de Hurlingham / Comisión de Investigaciones Científicas de la Provincia de Buenos Aires
📩 ernestogallegos@unahur.edu.ar
Resumen:
La implementación de los Proyectos de Desarrollo Tecnológico y Social (PDTS) en las universidades argentinas representa un cambio en el modo de concebir la investigación. Esta ponencia analiza cómo la Universidad Nacional de Hurlingham institucionalizó los PDTS a través de la convocatoria PIUNAHUR 6, evaluando su impacto en la cultura académica y las formas de producción de conocimiento.
El objetivo es identificar las transformaciones que implica esta modalidad para la universidad pública, su articulación con actores territoriales y su potencial como estrategia de desarrollo posneoliberal.
Metodológicamente, se utilizó un enfoque cualitativo basado en análisis de documentos institucionales, entrevistas a investigadores, y estudio de casos seleccionados dentro de PIUNAHUR 6.
Entre los resultados se observa una reconfiguración de los criterios de evaluación (incorporando pertinencia, impacto y articulación), una creciente apertura hacia la co-producción de conocimiento y una valorización del diálogo entre saberes. También se identifican tensiones con los modelos tradicionales de investigación, centrados en la publicación académica y la autonomía disciplinar.
Se concluye que los PDTS permiten pensar alternativas al modelo lineal de innovación, promoviendo una investigación situada, orientada a la resolución de problemas concretos. La experiencia de UNAHUR demuestra que es posible institucionalizar estos enfoques desde la universidad pública, en articulación con políticas estatales y demandas sociales.
Palabras clave: PDTS, investigación orientada, universidad pública, desarrollo inclusivo, co-producción de conocimiento.
--
📄 Resumen 3
Eje 3. Economía, desarrollo y sociedad
Subeje: Trabajo, empleo y desarrollo económico
Título: Ecosistemas de Innovación en Universidades del Conurbano: La experiencia de la incubadora de UNAHUR
Autor: Ernesto Gallegos – Universidad Nacional de Hurlingham / Comisión de Investigaciones Científicas de la Provincia de Buenos Aires
📩 ernestogallegos@unahur.edu.ar
Resumen:
La ponencia analiza la experiencia de la incubadora de emprendimientos y empresas de base tecnológica (EBT) de la Universidad Nacional de Hurlingham como caso de construcción de un ecosistema local de innovación en el conurbano bonaerense. Se examinan los vínculos entre formación, producción, vinculación tecnológica y generación de empleo en sectores intensivos en conocimiento.
El objetivo es describir los principales dispositivos de la incubadora, caracterizar los emprendimientos apoyados, y analizar su articulación con actores públicos y privados del territorio.
La metodología combina análisis documental, entrevistas a gestores institucionales y emprendedores, y revisión de políticas públicas de apoyo al emprendedorismo universitario. Se consideran también los vínculos con el Laboratorio de Investigación Aplicada (LIAPT) y la Dirección de Formación Profesional.
Entre los resultados se identifican fortalezas como la orientación a necesidades productivas locales, la capacidad de incubar ideas en etapas tempranas y la articulación con redes de innovación regional. También se destacan desafíos: financiamiento, sostenibilidad y escalabilidad de los emprendimientos.
Se concluye que la experiencia de UNAHUR aporta a la construcción de modelos de desarrollo económico con base territorial, donde la universidad cumple un rol estratégico en la generación de empleo calificado, en articulación con el Estado y el entramado productivo.
Palabras clave: incubación, ecosistema de innovación, universidad pública, desarrollo productivo, emprendimientos tecnológicos.
```

## ✅ Output generado (ejemplo)

### Evaluación del Resumen 1 (Modelos de Vinculación Tecnológica en Universidades del Siglo XXI)

| Criterio | Puntuación (1-5) | Justificación breve |
|:---|:---:|:---|
| Pertinencia | 5 | Directamente relacionado con el eje de desarrollo y sociedad en universidades públicas. |
| Aporte | 4 | Propone un modelo replicable de vinculación tecnológica con fuerte anclaje territorial. |
| Cumplimiento del objetivo | 5 | Cumple con el objetivo de analizar experiencias innovadoras en universidades públicas. |
| Claridad del lenguaje | 5 | Lenguaje claro, accesible y riguroso. |
| Coherencia argumentativa | 5 | Estructura lógica, coherente entre hipótesis, metodología y resultados. |

### Evaluación del Resumen 2 (Implementación de los PDTS en UNAHUR)

| Criterio | Puntuación (1-5) | Justificación breve |
|:---|:---:|:---|
| Pertinencia | 5 | Totalmente alineado al análisis de alternativas de desarrollo pos-neoliberal. |
| Aporte | 5 | Aporta evidencia sobre nuevas formas de producción de conocimiento universitario. |
| Cumplimiento del objetivo | 5 | Identifica transformaciones institucionales de forma concreta. |
| Claridad del lenguaje | 4 | Lenguaje claro, aunque algunos conceptos técnicos requieren atención lectora. |
| Coherencia argumentativa | 5 | Fluidez lógica entre planteo, metodología y resultados. |

### Evaluación del Resumen 3 (Ecosistemas de Innovación en Universidades del Conurbano)

| Criterio | Puntuación (1-5) | Justificación breve |
|:---|:---:|:---|
| Pertinencia | 5 | Pertinente al análisis de trabajo, empleo y desarrollo económico. |
| Aporte | 4 | Buen aporte empírico sobre ecosistemas de innovación, aunque podría ampliarse en políticas de escalabilidad. |
| Cumplimiento del objetivo | 5 | Logra describir y analizar con claridad los dispositivos y sus vínculos. |
| Claridad del lenguaje | 5 | Redacción precisa y accesible. |
| Coherencia argumentativa | 5 | Coherencia total entre planteo, metodología, resultados y conclusión. |

## 👌 Observaciones
- Se define con precisión el **rol evaluador** y el **contexto académico real** (FLACSO 2025).
- Se establecen **criterios objetivos de evaluación** muy claros y adaptados al estándar de congresos científicos.
- El formato de salida permite **lectura rápida y comparación estructurada**.
- Ideal para integrar evaluaciones automatizadas en procesos de revisión académica preliminar o apoyo a comités científicos.

⚡️ Este tipo de prompting muestra capacidades de **evaluación crítica asistida** de nivel profesional académico.

