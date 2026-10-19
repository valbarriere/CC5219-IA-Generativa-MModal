# CC5219: Aplicar un modelo a un dataset o tarea nuevos

## Objetivo

En dupla, apliquen un modelo visto en el curso a un dataset o una tarea que no se haya usado en clase, para responder una pregunta concreta. Pueden usar el mismo modelo del paper que presentaron.

Lo que se evalúa es el diseño del experimento y el análisis de los resultados, no su complejidad. Un resultado negativo bien analizado puede obtener la nota máxima.

## Tipos de experimento e ideas

Elijan al menos un tipo de experimento:

1. **Evaluar:** correr un modelo preentrenado en inferencia (zero-shot, o un clasificador simple sobre sus features) y medir su desempeño.
2. **Adaptar:** ajustar el modelo (por ejemplo con LoRA) y compararlo con el modelo sin ajustar.
3. **Poner a prueba:** construir un conjunto pequeño y difícil para encontrar dónde falla el modelo.

Algunas ideas generales, para que busquen la suya:

- Un modelo de visión o audio sobre datos de un dominio distinto al de su entrenamiento, por ejemplo otro tipo de imágenes o voz con acento local.
- Un LLM o un modelo multimodal evaluado en español, o en conocimiento local.
- Dos modelos, dos tamaños o dos formas de adaptación comparados en una misma tarea.
- La robustez de un modelo ante cambios de ruido, idioma o formato del prompt.

## Requisitos

- El dataset o la tarea debe ser nuevo: no puede ser el de los laboratorios ni el benchmark principal del paper.
- Puede ser público o creado por ustedes. Indiquen fuente, tamaño y licencia, y cómo lo construyeron si es propio.
- Definan el split antes de experimentar: el conjunto de test no se usa para ajustar nada.
- Debe correr en Colab gratuito (GPU T4) en menos de una hora, pero si tienen mas computo esta bien tambien.
- Pueden usar asistentes de IA para programar, pero deben declararlo. **Ambos integrantes deben poder explicar el código**.

## Entregables

Un notebook ejecutable de principio a fin y un informe  (notebook) de 1–2 páginas con:

- Pregunta o hipótesis, dataset o tarea, modelo y métrica.
- Al menos un baseline para comparar.
- Resultados en una tabla o figura.
- Análisis de 5–10 errores concretos.
- Limitaciones y cómputo usado.

Ademas de eso, los estudiantes deberan hacer una presentacion de 15mn para mostrar lo que han hecho. 

## Rúbrica (7 puntos)

| Criterio | Pts | Qué se evalúa |
| --- | --- | --- |
| Dataset o tarea nuevos | 1 | Es nuevo, está justificado y tiene fuente, tamaño y licencia |
| Diseño experimental | 1,5 | Pregunta clara, baseline, métrica adecuada antes de experimentar |
| Análisis de resultados y errores | 3 | Resultados legibles y errores concretos explicados con una hipótesis |
| Reproducibilidad | 0,5 | El notebook corre completo, con semillas, versiones y cómputo indicados |
| Limitaciones y conclusiones | 1 | Conclusiones respaldadas por los datos y limitaciones honestas |
