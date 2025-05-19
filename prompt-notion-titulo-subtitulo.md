# Prompt para automatización: generación de título y subtítulo desde notas en Notion

## Objetivo

El objetivo fue diseñar un prompt para ser usado en un flujo automatizado con Notion y Zapier, orientado a la generación de encabezados (título y subtítulo) para un newsletter de pensamiento crítico y tecnológico.

El flujo automatizado consiste en:
- Crear una nueva nota en Notion.
- Capturar su contenido mediante Zapier.
- Enviarlo a OpenAI mediante API.
- Obtener título + subtítulo para insertar en Substack o Mailchimp.

---

## Prompt diseñado

```
Actuá como un editor de contenidos digitales con experiencia en newsletters de pensamiento crítico y tecnología.

Tu tarea es generar:
- Un título atractivo y conciso (máximo 12 palabras).
- Un subtítulo descriptivo y sugerente (máximo 20 palabras).

Entrada: el siguiente texto es el contenido completo de una nota en Notion que será publicada como parte del newsletter “Quiero Creer”.

Tono: crítico pero esperanzador, con sensibilidad política, claridad conceptual y estética literaria.

Formato de salida:
Título: [texto]
Subtítulo: [texto]

Este prompt será utilizado en un flujo automatizado con Notion y Zapier para generar encabezados de newsletter.
```

---

## Output simulado

**Entrada:** Resumen de la nota “Sobre el tiempo”  
> La nota reflexiona sobre cómo distintas culturas y emociones afectan nuestra percepción del tiempo. Se mencionan relojes epigenéticos, rutinas, fluir, miedo, esperanza y la idea de que el tiempo puede dejar de ser una cuenta regresiva si se lo habita con plenitud. Termina con una referencia a Carl Sagan y su calendario cósmico como marco para valorar el presente.

**Salida generada:**

Título:  
El tiempo no existe, pero lo vivimos igual

Subtítulo:  
Una exploración íntima y cultural sobre la urgencia, la memoria, el cuerpo y la posibilidad de habitar el ahora

---

## Observaciones

- El prompt está optimizado para funcionar con herramientas nocode (Notion + Zapier + OpenAI).
- La estructura clara y el control de longitud permiten su integración directa a plataformas de newsletter.
- El tono narrativo y filosófico se mantiene alineado con la identidad del proyecto “Quiero Creer”.
