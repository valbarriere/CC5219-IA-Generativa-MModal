# Inteligencia Artificial Generativa y Multimodal

## Departamento de Ciencias de la Computación - Universidad de Chile

**Docente:** [Valentín Barriere](https://valbarriere.github.io/)

Este repositorio va a contener el material (laboratorios, tutoriales y diapositivas) del curso **Inteligencia Artificial Generativa y Multimodal**, dictado en el semestre de **Primavera 2026**.

* **U-cursos**: https://www.u-cursos.cl/ingenieria/2026/2/CC5219/1/historial/
* [**Calendario oficial**](calendario.md) (puede cambiar) 
* [**Slides de Introduccion**](https://users.dcc.uchile.cl/~vbarrier/CC5219/slides_es/Intro.pdf)

### Resumen

Este curso ofrece una introducción práctica y conceptual a los fundamentos y aplicaciones de la inteligencia artificial generativa y multimodal. A través de una combinación equilibrada entre teoría y práctica, se explorará cómo los modelos generativos modernos —modelos de visión (GANs, autoencoders variacionales, modelos de difusión), modelos de audio, y modelos de lenguaje de gran escala (textuales y multimodales)— pueden crear, transformar y comprender distintos tipos de contenido (texto, imágenes, audio y datos multimodales).

Los laboratorios permiten experimentar directamente con herramientas y bibliotecas actuales del ecosistema de IA (`transformers`, `diffusers`, `peft`, …) de Hugging Face para construir, adaptar y combinar modelos generativos en escenarios reales.

### Prerrequisitos

Bases de Machine Learning y Deep Learning. Se recomienda (no es obligatorio) tener bases de NLP y de procesamiento de señales (STFT, escala Mel, etc.).

## Contenido del curso

El curso está organizado en 5 bloques (+1 de recordatorios) sobre **15 semanas**. Cada semana combina maximum dos **clases cátedra** (teoría, 1h30) con un **laboratorio** (práctica, 1h30). El calendario es disponible [aca](calendario.md) y puede cambiar durante la clase.

* **Recordatorios de Deep Learning**: repaso de conceptos base — diferencia entre ML y DL, perceptrón y MLP, extracción de características y transfer learning.
* **Modelos Generativos de Visión**: modelos generativos autoregresivos, VAEs y difusión; GANs y StyleGAN; self-supervised learning para visión.
* **Modelos de Audio**: representación de datos de audio y modelos SSL basados en Transformers; SpeechLLMs y generación de música.
* **Modelos de Texto**: modelado de lenguaje puro y modelos de lenguaje de gran escala (LLMs).
* **Multimodalidad**: principios de fusión multimodal (clásica y basada en Transformers); fusión basada en LLMs y tokens multimodales.
* **Técnicas Avanzadas**: agentes, razonamiento y uso de herramientas; adaptación e interpretabilidad de LLMs; modelos multimodales para series temporales de imágenes satelitales.

⚠️ El contenido tal que las slides o los papers a leer se van a subir poco a poco antes de las clases: 


## Notacion 

Cada bloque tiene:
* Un laboratorio a hacer en clase y terminar en la casa.  
* Un mini ccontrol de 15mn 

Ademas vamos a tener: 
* Una presentacion de un paper de investigacion 
* Una tarea a definir 

## Material complementario

#### Notebooks de tutoriales 

Como material de apoyo adicional, se incluyen dos tutoriales introductorios en [`Tutoriales/`](Tutoriales):

* [1\_Hugging\_Face\_Transformers\_Tutorial](https://colab.research.google.com/github/valbarriere/CC5219-IA-Generativa-MModal/blob/main/Tutoriales/1_Hugging_Face_Transformers_Tutorial.ipynb) — Introducción a la librería `transformers` de Hugging Face (pipelines, tokenizers, modelos preentrenados).
* [2\_Multimodalidad](https://colab.research.google.com/github/valbarriere/CC5219-IA-Generativa-MModal/blob/main/Tutoriales/2_Multimodalidad.ipynb) — Introducción a modelos y representaciones multimodales.

#### CheatSheets 

[Cheatseets](https://github.com/valbarriere/CC5205-Mineria-Datos-Content/tree/main/CheatSheets) sobre Python, Machine Learning and Deep Learning.

#### Videos

* Una explicacion mas en detalles de los AE variacionales: [https://www.youtube.com/watch?v=qJeaCHQ1k2w](https://www.youtube.com/watch?v=qJeaCHQ1k2w)
* Una explicacion mas en detalles de los modelos de difusion: [https://www.youtube.com/watch?v=EhndHhIvWWw](https://www.youtube.com/watch?v=EhndHhIvWWw)
* Una explicacion mas en detalles de la loss contrastiva y de SimCLR: [https://www.youtube.com/watch?v=UqJauYELn6c](https://www.youtube.com/watch?v=UqJauYELn6c)



