# Prompt: Clasificación de países según altitud máxima

## 🎯 Objetivo
Diseñar un prompt que permita clasificar una lista de países según la altura máxima de su territorio, en función de umbrales establecidos (5000m, 6000m, 7000m, 9000m). El modelo debe asumir el rol de experto en geografía y ciencia de datos, justificar cada asignación con el nombre del pico más alto, y devolver los resultados en formato CSV.

## 🧠 Prompt utilizado
```
Eres un experto en ciencia de datos y geografía.

Clasifica la siguiente lista de países en las siguientes categorías:

- Países con algún punto de su territorio por encima de los 5000 metros sobre el nivel del mar
- Países con algún punto de su territorio por encima de los 6000 metros sobre el nivel del mar
- Países con algún punto de su territorio por encima de los 7000 metros sobre el nivel del mar
- Países con algún punto de su territorio por encima de los 9000 metros sobre el nivel del mar

Además:
- Da una justificación (ejemplo de su pico más importante)
- Expresa resultados en formato tabla (CSV)

Lista de países:
[insertar lista completa de países]
```

## 📌 Observaciones
- El prompt incluye **rol claro** (experto en geografía y ciencia de datos).
- La tarea está **especificada en términos de clasificación numérica**.
- La salida debe estar **estructurada como tabla CSV**, lo que permite su uso en contextos de análisis de datos.
- Este tipo de prompt puede integrarse a flujos de trabajo de consultoría, educación, visualización territorial o planificación climática.

⚠️ Nota: Este prompt requiere conocimiento geográfico preciso, por lo que es útil en tareas de clasificación automatizada combinada con verificación humana o APIs externas.
