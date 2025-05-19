# Prompt técnico: Generación de resumen ejecutivo para automatización vía API

## Objetivo

El objetivo fue diseñar un prompt robusto, claro y portable para ser utilizado dentro de un sistema automatizado vía API (como OpenAI), orientado a la generación de resúmenes ejecutivos para planificación pública.

Se aplican criterios técnicos de claridad, formato de salida estructurado, tono profesional y bajo nivel de temperatura para maximizar control y precisión.

---

## Prompt diseñado (contenido del role: user)

```
Redactá un resumen ejecutivo basado en un informe de tres páginas sobre productividad en empresas cooperativas.

Tu salida debe estar en formato:
- Lista con 5 bullets clave (una línea cada uno, con foco en hallazgos, tendencias o datos relevantes).
- Conclusión final de no más de 2 líneas que resuma las implicancias estratégicas del informe.

Tono: profesional, claro, orientado a la toma de decisiones en contextos de planificación pública.

No repitas los enunciados del input. No agregues explicaciones fuera del formato solicitado.

Este texto será utilizado dentro de un sistema automático de generación de reportes para una dirección de planificación del sector público.
```

---

## Estructura para uso vía API (estilo OpenAI)

```json
{
  "model": "gpt-4",
  "temperature": 0.4,
  "messages": [
    {
      "role": "system",
      "content": "Actuás como un analista de datos especializado en informes ejecutivos para organismos públicos."
    },
    {
      "role": "user",
      "content": "Redactá un resumen ejecutivo basado en un informe de tres páginas sobre productividad en empresas cooperativas.\n\nTu salida debe estar en formato:\n- Lista con 5 bullets clave (una línea cada uno, con foco en hallazgos, tendencias o datos relevantes).\n- Conclusión final de no más de 2 líneas que resuma las implicancias estratégicas del informe.\n\nTono: profesional, claro, orientado a la toma de decisiones en contextos de planificación pública.\n\nNo repitas los enunciados del...
    }
  ]
}
```

---

## Output simulado (respuesta del modelo)

**Resumen ejecutivo:**

- La productividad en cooperativas creció un 12% promedio en el último año, superando a pymes tradicionales en sectores como alimentos y servicios.
- Equipos con mayor participación democrática presentaron mejores indicadores de eficiencia y retención de talento.
- Las cooperativas con modelos de gestión híbridos (digital + territorial) mostraron un aprovechamiento superior de herramientas tecnológicas.
- Persisten brechas estructurales en acceso a financiamiento y escalabilidad de procesos productivos.
- La falta de políticas específicas para el sector limita la sistematización y evaluación comparativa entre regiones.

**Conclusión:**  
Las cooperativas demuestran un potencial creciente en términos de productividad y resiliencia, pero requieren un entorno institucional más robusto para consolidarse como alternativa estructural en la economía argentina.

---

## Observaciones

- El prompt es completamente portable a flujos automatizados.
- La salida es compatible con herramientas como Notion, Zapier, Airtable, dashboards institucionales o generación de PDF.
- El nivel de control sobre tono y formato lo hace apto para entornos productivos.

