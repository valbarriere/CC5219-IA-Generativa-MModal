# CC5219: Presentación de un paper

## Formato

Cada dupla presenta un paper de investigación a la clase: 15 minutos de charla + preguntas. La charla explica la idea central del paper, la conecta con el curso y la evalúa con ojo crítico.

- Un paper distinto por dupla, elegido de la lista de abajo.
- Pueden proponer otro, con aprobación del docente: de 2022 o posterior y con modelo o código abierto.
- Ambos integrantes hablan y ambos responden las preguntas, sin importar quién presentó esa parte.

## Estructura de la charla

| Minutos | Bloque | Qué debe quedar claro |
| --- | --- | --- |
| 2 | Problema | Qué resuelve el paper y por qué importa |
| 1.5 | Conexión con el curso | Qué concepto de las clases extiende |
| 4.5 | El método | Un diagrama propio y la idea clave: pérdida, arquitectura o pipeline |
| 2.5 | Resultados | Una tabla o figura leída con ojo crítico |
| 1.5 | Límites y conclusión | Qué no resuelve el paper y una pregunta para la clase |
| 3 | Preguntas | Del docente y de los compañeros |

Máximo 10 slides, en español. El diagrama del método debe ser hecho por ustedes, no copiado sin anotar.

## Ideas de papers propuestos (pueden usar otros)

Papers legibles en una semana. Verifiquen el título exacto y el PDF original antes de empezar.

| Paper | Ancla en el curso | Idea central | Dificultad |
| --- | --- | --- | --- |
| **DINOv2**, Oquab et al., 2023 | SSL para visión: self-distillation, DINO | Features visuales robustas, entrenadas sin etiquetas | Media |
| **DreamBooth**, Ruiz et al., 2022 | Difusión: Stable Diffusion | Personalizar un modelo texto-a-imagen con pocas fotos de un sujeto | Baja |
| **MusicGen**, Copet et al., 2023 | Generación de música: modelos autorregresivos de audio | Un solo Transformer genera música a partir de texto, sobre tokens de EnCodec | Media |
| **Whisper**, Radford et al., 2022 | Reconocimiento de voz | Entrenar con audio de etiquetas ruidosas a gran escala da robustez | Baja |
| **Lost in the Middle**, Liu et al., 2023 | LLMs: ventana de contexto y RAG | Los LLMs usan mal la información ubicada en medio de un contexto largo | Baja |
| **Judging LLM-as-a-Judge**, Zheng et al., 2023 | LLMs: evaluación con LLM como juez | Un LLM puede evaluar a otros, pero tiene sesgos medibles | Baja |
| **DeepSeek-R1**, DeepSeek-AI, 2025 | LLMs: razonamiento y Chain of Thought | El aprendizaje por refuerzo con recompensas verificables mejora el razonamiento | Media |
| **SigLIP**, Zhai et al., 2023 | Multimodalidad: CLIP, InfoNCE | Reemplazar el softmax de CLIP por una pérdida sigmoide | Baja |
| **Vision Language Models Are Blind**, Rahmanzadehgervi et al., 2024 | Multimodalidad: Laboratorio 5 | Los VLMs fallan en tareas visuales simples, como contar | Baja |
| **DoRA**, Liu et al., 2024 | Técnicas avanzadas: LoRA y QLoRA | Separar magnitud y dirección de los pesos mejora LoRA | Media |
| **ReAct**, Yao et al., 2022 | Técnicas avanzadas: agentes y herramientas | Intercalar razonamiento y acciones con herramientas | Baja |

## Rúbrica (7 puntos)

| Criterio | Pts | Qué se evalúa |
| --- | --- | --- |
| Comprensión del método | 2 | Explican la idea con sus propias palabras y un diagrama propio |
| Análisis crítico | 1.5 | Leen resultados con ojo crítico: baselines, datasets, supuestos y límites |
| Conexión con el curso | 0.5 | Nombran el concepto de las clases que el paper extiende |
| Claridad de las slides | 1 | Estructura lógica, un mensaje por slide, figuras legibles |
| Manejo del tiempo | 0.5 | Respetan los 12 minutos y ambos hablan de forma equilibrada |
| Respuesta a preguntas | 1.5 | Cada integrante responde con precisión y reconoce lo que no sabe |
