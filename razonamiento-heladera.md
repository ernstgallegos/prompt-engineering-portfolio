# Prompt: Estimación del consumo de una heladera con razonamiento paso a paso

## 🎯 Objetivo
Diseñar un prompt para obtener un cálculo razonado del consumo energético mensual de una heladera doméstica. El modelo debe razonar paso a paso utilizando la técnica de Chain of Thought (CoT), con un tono claro y amigable.

## 🧠 Prompt utilizado
```
Actúa como un ingeniero eléctrico con 15 años de experiencia.
Utiliza un tono claro y un registro coloquial de divulgación para el público general.
Responde a la consigna: “¿Cuánta energía consume una heladera promedio en un mes?”
Explicá tu razonamiento paso a paso antes de dar una respuesta.
```

## ✅ Outputs generados (simulación de autoconsistencia con temperatura > 0)

### Resultado 1 – Estilo directo y pedagógico
```
1. Una heladera promedio tiene una potencia de unos 120 W.
2. Funciona en ciclos, promedio de 8 h al día.
3. 120 W × 8 h = 960 Wh/día = 0.96 kWh/día
4. Mensual: 0.96 × 30 = 28.8 kWh/mes
Conclusión: entre 25 y 35 kWh al mes.
```

### Resultado 2 – Estilo informal con analogías
```
1. Potencia estimada: 150 W
2. Funciona aprox. 7.5 h por día
3. 150 × 7.5 = 1125 Wh/día = 1.125 kWh
4. Mensual: 1.125 × 30 = 33.75 kWh
Comentario: como cargar el celular 300 veces.
```

### Resultado 3 – Estilo técnico-divulgativo
```
1. Potencia eficiente: 100 W
2. Ciclo estimado: 8 h/día
3. 100 × 8 = 800 Wh = 0.8 kWh
4. Mensual: 0.8 × 30 = 24 kWh
Comentario: depende del uso, modelo y eficiencia.
```

## 📌 Observaciones
- Se utilizó **rol técnico** con especificación de experiencia (15 años).
- Se aplicó **Chain of Thought** para forzar razonamiento paso a paso.
- La variabilidad en las respuestas refleja **simulación con temperatura > 0**.
- Excelente caso para mostrar capacidades de prompting técnico + divulgativo.
