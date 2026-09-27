<!--
  Palabras clave: ia nsfw, generador de imágenes ia sin censura, generador de videos ia nsfw, generador de video ia sin censura,
  ia sin censura, imagen a video ia nsfw, editor de imágenes ia nsfw, modelos de ia sin censura, llm sin censura,
  api de ia nsfw, mejor generador de imágenes ia nsfw 2026, ia para adultos, ia +18, wan 2.2 spicy, seedance spicy,
  skill nsfw, mcp nsfw, awesome nsfw ai, nsfw ai generator, uncensored ai image generator, uncensored ai video generator,
  nsfw image to video, nsfw ai api
-->

<p align="center"><a href="README.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.fr.md">Français</a> · <b>Español</b></p>

<h1 align="center">Awesome NSFW AI</h1>

<p align="center">
  <b>Lista seleccionada 2026 de generadores de imágenes con IA sin censura, generadores de videos con IA NSFW, modelos de imagen a video, editores de imágenes, LLM sin censura, APIs, skills para agentes, servidores MCP y herramientas, para creadores y desarrolladores de contenido para adultos.</b>
</p>

<p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
  <img src="https://img.shields.io/badge/updated-2026--09--27-blue" alt="Última actualización: 2026-09-27">
  <img src="https://img.shields.io/badge/18%2B-adults%20only-red" alt="Solo mayores de 18">
  <img src="https://img.shields.io/badge/license-CC0--1.0-lightgrey" alt="Licencia CC0">
</p>

<p align="center">
  <img src="assets/wolf-turn-and-look-back.gif" width="24%" alt="Resultado de imagen a video con Wan 2.2 Spicy">
  <img src="assets/velvet-spiral-turn.gif" width="24%" alt="Resultado de imagen a video con Seedance 2.0 Spicy">
  <img src="assets/silk-draught-pull.gif" width="24%" alt="Resultado de imagen a video con Wan 2.7 Spicy">
  <img src="assets/hotel-window-turn.gif" width="24%" alt="Resultado de imagen a video con Seedance 2.5 Spicy">
  <br><sub>Resultados reales de Wan 2.2 Spicy, Seedance 2.0 Spicy, Wan 2.7 Spicy y Seedance 2.5 Spicy. Hay más, con sus prompts exactos, en <a href="https://github.com/Spicy-API/nsfw-ai-video-prompts/blob/main/README.es.md#ejemplos-reales-resultados-y-sus-prompts">nsfw-ai-video-prompts</a>.</sub>
</p>

<p align="center">
  <a href="#generadores-de-video-con-ia-sin-censura">Video</a> ·
  <a href="#generadores-de-imágenes-con-ia-sin-censura">Imagen</a> ·
  <a href="#editores-de-imágenes-con-ia-nsfw-y-herramientas-faciales">Edición</a> ·
  <a href="#llm-sin-censura-y-roleplay">LLM</a> ·
  <a href="#apis-de-ia-nsfw">APIs</a> ·
  <a href="#skills-para-agentes-y-servidores-mcp">Skills y MCP</a> ·
  <a href="#modelos-autoalojados-y-de-pesos-abiertos">Autoalojado</a> ·
  <a href="#preguntas-frecuentes">Preguntas frecuentes</a>
</p>

> **Solo para mayores de 18 años.** Esta lista incluye herramientas capaces de generar contenido para adultos. Todos los recursos deben usarse con adultos ficticios o con adultos reales que hayan dado su consentimiento documentado, y respetando la ley del lugar donde vives tú y donde vive tu público. Consulta [Reglas que se aplican a todas las herramientas](#reglas-que-se-aplican-a-todas-las-herramientas).

> **Aviso:** esta lista la mantiene el equipo de [SpicyAPI](https://spicyapi.ai/es?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=disclosure-es), una API de pago por uso para modelos de imagen, video y texto sin censura. Las entradas de SpicyAPI están marcadas con 🌶️. Las herramientas de terceros aparecen porque son útiles, no porque paguen por estar aquí. Se aceptan pull requests que añadan competidores.

---

## En resumen: qué elegir

| Quiero… | Empieza por | Por qué |
|---|---|---|
| Texto a video, o poner a mi personaje en una escena nueva | [Seedance 2.5](https://spicyapi.ai/es/models/seedance-2-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-es) o [Wan 3.0](https://spicyapi.ai/es/models/wan-3-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-es) | Modelos estándar con nivel `unrestricted` en el catálogo; T2V, I2V y referencia a video |
| Hacer un video NSFW a partir de una imagen fija, barato | 🌶️ [Wan 2.2 Spicy](https://spicyapi.ai/es/models/wan-2-2-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-es) o [LTX 2.3 Spicy](https://spicyapi.ai/es/models/ltx-2-3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-es) | Desde $0.019 por segundo generado a 480p |
| La mejor calidad en imagen a video sin censura | 🌶️ [Seedance 2.5 Spicy](https://spicyapi.ai/es/models/seedance-2-5-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-es) | Clips de 4–30 s, hasta 1080p nativo, audio opcional |
| Video sin censura con mis propios LoRAs | 🌶️ [Wan 2.2 Spicy LoRA](https://spicyapi.ai/es/models/wan-2-2-spicy-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-es) | Hasta tres LoRAs por llamada, además de extender videos |
| Un modelo de texto a imagen sin censura | [Qwen Image 2.1](https://spicyapi.ai/es/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-es) | Desde $0.024 por imagen, prompts largos, 15 relaciones de aspecto, edición a partir de imágenes de referencia |
| Imágenes estilo anime / hentai | [Prefect Pony XL](https://spicyapi.ai/es/models/prefect-pony-xl?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-es) o checkpoints Pony / SDXL autoalojados | Prompts por etiquetas, linaje anime |
| Un editor de imágenes con IA sin censura | [Qwen Image 2.1 Edit](https://spicyapi.ai/es/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-es) o 🌶️ [Qwen Image Edit Spicy](https://spicyapi.ai/es/models/qwen-image-spicy-edit?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-es) | De 1 a 10 imágenes de referencia, o una imagen + una instrucción, sin máscara |
| Ejecutarlo todo en local, gratis | [ComfyUI](https://github.com/Comfy-Org/ComfyUI) + pesos abiertos de [Wan 2.2](https://github.com/Wan-Video/Wan2.2) | Necesita una GPU potente (con 24 GB de VRAM es suficiente) |
| Que Claude Code / Cursor generen por mí | [nsfw-ai-skill](https://github.com/Spicy-API/nsfw-ai-skill/blob/main/README.es.md) o el [servidor MCP oficial de SpicyAPI](https://docs.spicyapi.ai/docs/mcp?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) | Generación en lenguaje natural desde tu agente |
| Prompts para copiar y pegar que funcionan | [nsfw-ai-video-prompts](https://github.com/Spicy-API/nsfw-ai-video-prompts/blob/main/README.es.md) | 116 prompts de video listos para usar y 130 casos reales, cada uno con su prompt |

Los precios son el nivel más bajo publicado en el catálogo público de SpicyAPI el 2026-09-27. Las resoluciones más altas, el audio y los clips más largos cuestan más; revisa la página del modelo antes de lanzar una tarea.

---

## Contenido

- [En resumen: qué elegir](#en-resumen-qué-elegir)
- [Qué significan realmente "IA NSFW" e "IA sin censura"](#qué-significan-realmente-ia-nsfw-e-ia-sin-censura)
- [Generadores de video con IA sin censura](#generadores-de-video-con-ia-sin-censura)
  - [Todos los modelos de video sin censura, de más a menos popular](#todos-los-modelos-de-video-sin-censura-de-más-a-menos-popular)
  - [Cuánto cuesta un clip NSFW de 5 segundos](#cuánto-cuesta-un-clip-nsfw-de-5-segundos)
- [Generadores de imágenes con IA sin censura](#generadores-de-imágenes-con-ia-sin-censura)
- [Editores de imágenes con IA NSFW y herramientas faciales](#editores-de-imágenes-con-ia-nsfw-y-herramientas-faciales)
- [LLM sin censura y roleplay](#llm-sin-censura-y-roleplay)
- [APIs de IA NSFW](#apis-de-ia-nsfw)
- [Skills para agentes y servidores MCP](#skills-para-agentes-y-servidores-mcp)
- [Modelos autoalojados y de pesos abiertos](#modelos-autoalojados-y-de-pesos-abiertos)
- [Interfaces locales y herramientas de flujo de trabajo](#interfaces-locales-y-herramientas-de-flujo-de-trabajo)
- [LoRAs, checkpoints y entrenamiento](#loras-checkpoints-y-entrenamiento)
- [Escalado, restauración y posproducción](#escalado-restauración-y-posproducción)
- [Cómo escribir prompts para contenido adulto](#cómo-escribir-prompts-para-contenido-adulto)
- [Cómo elegir: guía de decisión](#cómo-elegir-guía-de-decisión)
- [Reglas que se aplican a todas las herramientas](#reglas-que-se-aplican-a-todas-las-herramientas)
- [Preguntas frecuentes](#preguntas-frecuentes)
- [Repositorios relacionados](#repositorios-relacionados)
- [Cómo contribuir](#cómo-contribuir)

---

## Qué significan realmente "IA NSFW" e "IA sin censura"

**IA NSFW** es cualquier modelo o herramienta generativa capaz de producir desnudos o contenido sexual para adultos. **IA sin censura** es un término más amplio para los modelos que no rechazan prompts para adultos ni difuminan sus resultados.

Hay tres factores que deciden si una petición NSFW funciona, y la gente los confunde constantemente:

1. **El modelo.** Algunos modelos se entrenaron o ajustaron para permitir contenido adulto. Otros se entrenaron para rechazarlo, y ninguna configuración de la plataforma cambia eso.
2. **El filtro propio de la plataforma.** Muchos servicios alojados añaden una capa de moderación encima del modelo (listas de palabras bloqueadas, clasificadores de resultados, difuminado). Un modelo permisivo detrás de un filtro estricto sigue bloqueado.
3. **Las leyes de tu país y los términos de la plataforma.** Que "el modelo pueda hacerlo" no significa que "tú puedas hacerlo". Hay contenido que es ilegal en todas partes (consulta [las reglas](#reglas-que-se-aplican-a-todas-las-herramientas)).

Una forma práctica de leer las listas de abajo:

| Etiqueta | Qué significa |
|---|---|
| **Edición Spicy / NSFW** | Una versión de un modelo ajustada o configurada para contenido adulto. En SpicyAPI llevan "Spicy" en el nombre. |
| **Apto para contenido adulto** | Un modelo general que a menudo permite contenido adulto, pero puede suavizar o rechazar algunas peticiones. |
| **Filtrado** | El modelo o el proveedor aplica su propio filtro de contenido. Sirve para trabajo SFW, pero no es fiable para NSFW. |

En SpicyAPI, cada modelo del catálogo público tiene un nivel de política (`unrestricted`, `softened`, `borderline`, `filtered`), y las [clasificaciones](https://spicyapi.ai/es/leaderboards?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=definitions-es) publican un **Freedom Score** calculado con prompts de prueba repetidos. La plataforma no añade su propio filtro encima del modelo; si hay filtrado, lo aplica el proveedor del modelo.

---

## Generadores de video con IA sin censura

Imagen a video (I2V) es la forma más fiable de crear un video NSFW con IA: tú controlas el aspecto con el primer fotograma y el modelo solo tiene que animarlo. Texto a video (T2V) y referencia a video (Ref2V, "pon al personaje de estas imágenes en una escena nueva") los ofrecen los modelos estándar de la tabla.

### Todos los modelos de video sin censura, de más a menos popular

Mismo orden que el catálogo de SpicyAPI: primero los más populares y, dentro de cada familia, primero la versión más reciente. Las ediciones 🌶️ **Spicy** están ajustadas para contenido adulto. Los modelos **estándar** de esta lista tienen el nivel `unrestricted` en el catálogo (el proveedor no aplica ningún filtro de contenido), así que también aceptan prompts para adultos. Los precios corresponden al nivel más barato. Catálogo consultado el <!-- catalog:date -->
2026-09-27
<!-- /catalog:date -->

<!-- catalog:video -->
| Modelo | Tipo | Tareas | Duración | Desde |
|---|---|---|---|---|
| [Seedance 2.5 Spicy](https://spicyapi.ai/es/models/seedance-2-5-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | 🌶️ Spicy | I2V | 4–30 s | $0.216/s |
| [Seedance 2.5](https://spicyapi.ai/es/models/seedance-2-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | I2V, Ref2V, T2V | 4–30 s | $0.1234/s |
| [Seedance 2.0 Spicy](https://spicyapi.ai/es/models/seedance-2-0-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | 🌶️ Spicy | I2V | 4–15 s | $0.114/s |
| [Seedance 2.0](https://spicyapi.ai/es/models/seedance-2-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | I2V, Ref2V, T2V | 4–15 s | $0.07/s |
| [Wan 3.0 Prime](https://spicyapi.ai/es/models/wan-3-0-prime?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | I2V, Ref2V, T2V | 2–30 s | $0.0612/s |
| [Wan 3.0](https://spicyapi.ai/es/models/wan-3-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | I2V, Ref2V, T2V | 2–30 s | $0.045/s |
| [MiniMax H3 Spicy](https://spicyapi.ai/es/models/minimax-h3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | 🌶️ Spicy | I2V | 3–15 s | $0.038/s |
| [MiniMax H3](https://spicyapi.ai/es/models/minimax-h3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | I2V, Ref2V, T2V | 4–15 s | $0.025/s |
| [MiniMax H3 Singularity LoRA](https://spicyapi.ai/es/models/minimax-h3-singularity-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | I2V, Ref2V | 3–15 s | $0.06/s |
| [LTX 2.5](https://spicyapi.ai/es/models/ltx-2-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | I2V, T2V | 5–20 s | $0.09/s |
| [Wan 3.0 Pro Prime](https://spicyapi.ai/es/models/wan-3-0-pro-prime?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | I2V, Ref2V, T2V | 2–30 s | $0.234/s |
| [Wan 3.0 Pro](https://spicyapi.ai/es/models/wan-3-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | I2V, Ref2V, T2V | 2–30 s | $0.144/s |
| [MiniMax H3 LoRA](https://spicyapi.ai/es/models/minimax-h3-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | I2V, Ref2V, T2V | 3–15 s | $0.05/s |
| [HappyHorse 1.1](https://spicyapi.ai/es/models/happyhorse-1-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | I2V, Ref2V, T2V | 3–15 s | $0.14/s |
| [Seedance 2.0 Mini Spicy](https://spicyapi.ai/es/models/seedance-2-0-mini-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | 🌶️ Spicy | I2V | 4–15 s | $0.0387/s |
| [Seedance 2.0 Mini](https://spicyapi.ai/es/models/seedance-2-0-mini?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | I2V, Ref2V, T2V | 4–15 s | $0.01097/s |
| [Wan 2.7 Spicy](https://spicyapi.ai/es/models/wan-2-7-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | 🌶️ Spicy | I2V | 2–15 s | $0.1235/s |
| [LTX 2.3 Spicy](https://spicyapi.ai/es/models/ltx-2-3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | 🌶️ Spicy | I2V | 3–20 s | $0.019/s |
| [LTX 2.3 Spicy LoRA](https://spicyapi.ai/es/models/ltx-2-3-spicy-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | 🌶️ Spicy | I2V | 3–20 s | $0.0285/s |
| [Seedance 2.0 Fast Spicy](https://spicyapi.ai/es/models/seedance-2-0-fast-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | 🌶️ Spicy | I2V | 4–15 s | $0.081/s |
| [Seedance 2.0 Fast](https://spicyapi.ai/es/models/seedance-2-0-fast?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | I2V, Ref2V, T2V | 4–15 s | $0.02254/s |
| [Vidu Q3 Turbo](https://spicyapi.ai/es/models/vidu-q3-turbo?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | I2V | 1–16 s | $0.042/s |
| [Vidu Q3 Spicy](https://spicyapi.ai/es/models/vidu-q3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | 🌶️ Spicy | I2V | 1–16 s | $0.0665/s |
| [Vidu Q3](https://spicyapi.ai/es/models/vidu-q3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | I2V | 1–16 s | $0.07/s |
| [Vidu Q3 Pro](https://spicyapi.ai/es/models/vidu-q3-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | I2V | 1–16 s | $0.054/s |
| [Seedance 1.5 Pro Spicy](https://spicyapi.ai/es/models/seedance-1-5-pro-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | 🌶️ Spicy | I2V | 4–12 s | $0.012/s |
| [Seedance 1.5 Pro](https://spicyapi.ai/es/models/seedance-1-5-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | I2V, T2V | 4–12 s | $0.0112/s |
| [Wan 2.6 Flash](https://spicyapi.ai/es/models/wan-2-6-flash?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | I2V | 5, 10, 15 s | $0.0225/s |
| [Wan 2.6 Spicy](https://spicyapi.ai/es/models/wan-2-6-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | 🌶️ Spicy | I2V | 5, 10, 15 s | $0.095/s |
| [Wan 2.6](https://spicyapi.ai/es/models/wan-2-6?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | I2V, Ref2V, T2V | 5, 10, 15 s | $0.065/s |
| [Wan 2.5](https://spicyapi.ai/es/models/wan-2-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | I2V, T2V | 5, 10 s | $0.045/s |
| [Wan 2.2 Spicy](https://spicyapi.ai/es/models/wan-2-2-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | 🌶️ Spicy | I2V | 5, 8 s | $0.019/s |
| [Wan 2.2 Spicy LoRA](https://spicyapi.ai/es/models/wan-2-2-spicy-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | 🌶️ Spicy | I2V, Extend | 5, 8 s | $0.024/s |
| [Wan 2.2 LoRA](https://spicyapi.ai/es/models/wan-2-2-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | I2V | 5, 8 s | $0.024/s |
<!-- /catalog:video -->

Recomendaciones rápidas:

- **Mejor calidad:** Seedance 2.5 Spicy (hasta 30 s) y después Seedance 2.0 Spicy. Para texto a video o referencia a video con esa calidad, usa los estándar Seedance 2.5 / Seedance 2.0.
- **Wan más reciente:** Wan 3.0 (y sus niveles Prime / Pro) para T2V, I2V y Ref2V de hasta 30 s; Wan 2.7 Spicy y Wan 2.6 Spicy para imagen a video ajustado para adultos.
- **Borradores más baratos:** Seedance 1.5 Pro Spicy desde $0.012/s; Wan 2.2 Spicy y LTX 2.3 Spicy desde $0.019/s.
- **Tus propios LoRAs:** Wan 2.2 Spicy LoRA (con `video-extend`), LTX 2.3 Spicy LoRA, MiniMax H3 LoRA.

Algunos endpoints de video facturan por bloques completos (por ejemplo, un clip de 6 segundos en un modelo con bloques de 5 segundos se factura como 10 s); la página del modelo indica la duración del bloque, y el importe cotizado es lo máximo que se te puede cobrar. Explora y filtra todo en [SpicyAPI › Modelos de IA sin censura](https://spicyapi.ai/es/explore/uncensored-ai-models?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=video-table-es).

### Cuánto cuesta un clip NSFW de 5 segundos

Nivel más bajo publicado × 5 segundos, catálogo de SpicyAPI del 2026-09-27. Tómalo como un precio mínimo, no como una cotización.

| Modelo | 1 clip (5 s) | 100 clips | 1000 clips |
|---|---|---|---|
| Seedance 1.5 Pro Spicy (480p, sin audio) | $0.06 | $6.00 | $60 |
| Wan 2.2 Spicy (480p) | $0.095 | $9.50 | $95 |
| LTX 2.3 Spicy (480p) | $0.095 | $9.50 | $95 |
| MiniMax H3 Spicy (480p) | $0.19 | $19.00 | $190 |
| Seedance 2.0 Mini Spicy (480p) | $0.19 | $19.35 | $193.50 |
| Wan 2.6 Spicy (720p) | $0.475 | $47.50 | $475 |
| Seedance 2.0 Spicy (480p) | $0.57 | $57.00 | $570 |
| Seedance 2.5 Spicy (480p) | $1.08 | $108.00 | $1,080 |

Wan 2.2 Spicy a 720p cuesta $0.038/s, así que un clip de 5 segundos a 720p sale por $0.19. Las tareas fallidas se reembolsan automáticamente.

---

## Generadores de imágenes con IA sin censura

**Recomendado: [Qwen Image 2.1](https://spicyapi.ai/es/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-es)** (nivel `unrestricted` en el catálogo, desde $0.024 por imagen a 1k). Sigue instrucciones largas (hasta 5000 caracteres), genera en 15 relaciones de aspecto a 1k, 1.5k o 2k, y edita a partir de 1 a 10 imágenes de referencia dentro de la misma familia. [Qwen Image 2.1 LoRA](https://spicyapi.ai/es/models/qwen-image-2-1-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-es) permite añadir hasta tres LoRAs propios para mantener un estilo o un personaje coherente.

Todos los modelos de imagen sin censura, en el orden del catálogo:

<!-- catalog:image -->
| Modelo | Tipo | Tareas | Desde |
|---|---|---|---|
| [Qwen Image 2.1](https://spicyapi.ai/es/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | Edit, T2I | $0.024/image |
| [Qwen Image 2.1 LoRA](https://spicyapi.ai/es/models/qwen-image-2-1-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | Edit, T2I | $0.03/image |
| [MiniMax H3 Image LoRA](https://spicyapi.ai/es/models/minimax-h3-image-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | Edit, T2I | $0.042/image |
| [Qwen Image 3.0 Pro](https://spicyapi.ai/es/models/qwen-image-3-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | Edit, T2I | $0.04/image |
| [Qwen Image 3.0](https://spicyapi.ai/es/models/qwen-image-3-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | Edit, T2I | $0.03/image |
| [Seedream 5.0 Pro](https://spicyapi.ai/es/models/seedream-5-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | Edit, T2I | $0.036/image |
| [Qwen Image Edit Spicy](https://spicyapi.ai/es/models/qwen-image-spicy-edit?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | 🌶️ Spicy | Edit | $0.038/image |
| [Seedream 5.0 Lite](https://spicyapi.ai/es/models/seedream-5-0-lite?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | Edit, T2I | $0.0345/image |
| [Qwen Image 2](https://spicyapi.ai/es/models/alibaba-qwen-image-2?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | Edit, T2I | $0.035/image |
| [Qwen Image 2512 LoRA](https://spicyapi.ai/es/models/qwen-image-2512-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | Edit, T2I | $0.03/image |
| [Z-Image Spicy Pro](https://spicyapi.ai/es/models/z-image-spicy-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | 🌶️ Spicy | T2I | $0.019/image |
| [Z-Image Spicy](https://spicyapi.ai/es/models/z-image-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | 🌶️ Spicy | T2I | $0.01235/image |
| [Z-Image](https://spicyapi.ai/es/models/z-image?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | T2I | $0.01/image |
| [Z-Image Turbo LoRA](https://spicyapi.ai/es/models/z-image-turbo-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | Edit, T2I | $0.012/image |
| [Seedream 4.0](https://spicyapi.ai/es/models/seedream-4-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | Edit, T2I | $0.03/image |
| [Prefect Pony XL](https://spicyapi.ai/es/models/prefect-pony-xl?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | T2I | $0.015/image |
| [FLUX.1 Dev LoRA](https://spicyapi.ai/es/models/flux-1-dev-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-es) | Estándar | T2I | $0.018/image |
<!-- /catalog:image -->

Opción sin código: el [generador de imágenes con IA sin censura de SpicyAPI Studio](https://spicyapi.ai/es/create/uncensored-ai-image-generator?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-studio-es) ejecuta los mismos modelos en el navegador, con estilos, relaciones de aspecto y el precio visible antes de generar.

Para una prueba comparativa de qué permite cada modelo de imagen, lee [Less-restrictive image model evaluation](https://spicyapi.ai/es/blog/less-restrictive-model-evaluation?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-eval-es) (evaluación de modelos de imagen menos restrictivos).

---

## Editores de imágenes con IA NSFW y herramientas faciales

| Herramienta | Qué hace | Desde |
|---|---|---|
| [Qwen Image 2.1 Edit](https://spicyapi.ai/es/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-es) | Edición sin censura a partir de 1 a 10 imágenes de referencia de un sujeto **ficticio** o que ha dado su consentimiento: ropa, pose, escenario, iluminación (nivel `unrestricted` en el catálogo) | $0.036 / imagen |
| 🌶️ [Qwen Image Edit Spicy](https://spicyapi.ai/es/models/qwen-image-spicy-edit?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-es) | Edición sin censura por instrucciones: cambia la ropa, la pose, el escenario o la iluminación de un sujeto **ficticio** o que ha dado su consentimiento | $0.038 / imagen |
| [Image Expander](https://spicyapi.ai/es/models/image-expander-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-es) | Amplía la imagen (outpainting) a un encuadre más ancho o más alto | $0.024 / imagen |
| [Object Eraser](https://spicyapi.ai/es/models/object-eraser-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-es) | Elimina objetos, logotipos y marcas de agua de imágenes que te pertenecen | $0.03 / imagen |
| [Image Upscaler](https://spicyapi.ai/es/models/image-upscaler-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-es) / [Video Upscaler](https://spicyapi.ai/es/models/video-upscaler-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-es) | Da nitidez y aumenta la resolución del resultado final | $0.012 / imagen, $0.006 / s |
| [Face Swap](https://spicyapi.ai/es/models/face-swap-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-es), [Head Swap](https://spicyapi.ai/es/models/head-swap-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-es), [Video Character Swap](https://spicyapi.ai/es/models/character-swap-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-es) | Mantienen un mismo personaje **ficticio** coherente entre imágenes y clips | $0.013 / imagen, video desde $0.064 / s |
| [Lip Sync](https://spicyapi.ai/es/models/lip-sync-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-es), [Talking Avatar](https://spicyapi.ai/es/models/talking-avatar-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-es), [Video Sound Effects](https://spicyapi.ai/es/models/foley-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-es) | Voz y audio para personajes de IA | desde $0.0012 / s |

> ⚠️ Las herramientas de cambio de cara y de cabeza **nunca** deben usarse para poner a una persona real en contenido sexual sin su consentimiento documentado, y "desvestir" o "desnudar" la foto de una persona real está prohibido en todas las plataformas serias. Ser famoso o tener fotos públicas no equivale a dar consentimiento. Usa estas herramientas con personajes ficticios que hayas creado tú o contigo mismo.

Equivalentes autoalojados: [IP-Adapter](https://github.com/tencent-ailab/IP-Adapter), [InstantID](https://github.com/instantX-research/InstantID) y [PhotoMaker](https://github.com/TencentARC/PhotoMaker) para mantener la coherencia del personaje; [ControlNet](https://github.com/lllyasviel/ControlNet) para controlar la pose.

---

## LLM sin censura y roleplay

Los modelos de texto importan en el trabajo NSFW en tres frentes: ficción erótica e historias interactivas, apps de compañía y roleplay, y **escribir mejores prompts de imagen y video** (un LLM convierte una idea de una línea en un prompt detallado que tiene en cuenta la cámara).

### Alojados (compatibles con OpenAI)

SpicyAPI ofrece modelos de texto mediante endpoints compatibles con OpenAI, Anthropic y Gemini en `https://api.spicyapi.ai`, así que los SDK que ya usas funcionan cambiando solo la URL base. Entre los modelos con nivel `unrestricted` en el catálogo el 2026-09-27 están:

| Modelo | Desde (por 1K tokens) | Ideal para |
|---|---|---|
| [Grok 4.7](https://spicyapi.ai/es/models/grok-4-7?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-es) | $0.0036 | Escritura creativa, roleplay con personalidad |
| [DeepSeek V4 Pro](https://spicyapi.ai/es/models/deepseek-v4-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-es) | $0.00396 | Ficción larga, razonamiento |
| [DeepSeek V4.1 Flash](https://spicyapi.ai/es/models/deepseek-v4-1-flash?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-es) | $0.0012 | Chat de alto volumen, ampliación de prompts |
| [GLM 5.3 Flash](https://spicyapi.ai/es/models/glm-5-3-flash?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-es) | $0.000425 | El chat más barato del catálogo |
| [Kimi K3](https://spicyapi.ai/es/models/kimi-k3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-es) | $0.0135 | Historias con contexto largo |

```python
from openai import OpenAI

client = OpenAI(base_url="https://api.spicyapi.ai/v1", api_key="YOUR_SPICY_API_KEY")
reply = client.chat.completions.create(
    model="xai/grok-4.7/chat",
    messages=[
        {"role": "system", "content": "You write cinematic prompts for adult image-to-video models. All characters are adults."},
        {"role": "user", "content": "Boudoir scene, woman in her 30s, red silk robe, candlelight, slow push-in."},
    ],
)
print(reply.choices[0].message.content)
```

### Locales y autoalojados

- [Ollama](https://github.com/ollama/ollama) y [LM Studio](https://lmstudio.ai) ejecutan modelos de pesos abiertos en tu propia máquina; busca en sus bibliotecas ajustes de la comunidad "abliterated" o "uncensored".
- [KoboldCpp](https://github.com/LostRuins/koboldcpp): ejecutor GGUF de un solo archivo pensado para narrativa.
- [text-generation-webui](https://github.com/oobabooga/textgen): interfaz de chat local completa, con extensiones.
- [SillyTavern](https://github.com/SillyTavern/SillyTavern): el front end de referencia para roleplay. Conéctalo a un backend local o a cualquier API compatible con OpenAI, incluida SpicyAPI.

---

## APIs de IA NSFW

Si desarrollas apps para adultos, la pregunta no es solo "qué modelo", sino "qué proveedor me deja llamarlo sin bloquear mis peticiones y me cobra de forma justa".

| Qué revisar | Por qué importa | SpicyAPI |
|---|---|---|
| ¿La plataforma añade su propio filtro? | Un segundo filtro bloquea prompts que el modelo aceptaría | Sin filtro de plataforma; se sigue aplicando la política del proveedor del modelo |
| Unidad de facturación | Los créditos y las suscripciones ocultan el costo real | Saldo en USD, por imagen / por segundo / por token, sin suscripción, el saldo no caduca |
| Generaciones fallidas | Algunos proveedores cobran los rechazos | Las tareas fallidas se reembolsan automáticamente |
| Métodos de pago | Los negocios para adultos pierden a menudo el procesamiento con tarjeta | Visa, Mastercard, Amex, JCB, Apple Pay, Google Pay y cripto (BTC, ETH, USDT) |
| Control del gasto | Una clave filtrada puede vaciar el saldo | Límites diarios / mensuales / totales por clave, listas de modelos permitidos, listas de IP permitidas |
| Retención de datos | Los datos de entrada para adultos son sensibles | Plazos de retención independientes para prompts, archivos subidos y resultados; puedes acortarlos o destruir el contenido de una tarea |
| Integración | No quieres un cliente distinto para cada modelo | Una única API de tareas asíncronas, SDK (TypeScript, Python, Go, PHP, Java), CLI, servidor MCP, skill para agentes |

### Inicio rápido: imagen a video NSFW por HTTP

```bash
export SPICY_API_KEY="sk-spicy-..."   # crea una en https://spicyapi.ai/es/console

# 1) crear la tarea
curl -s https://api.spicyapi.ai/api/v1/jobs/createTask \
  -H "Authorization: Bearer $SPICY_API_KEY" \
  -H "Content-Type: application/json" \
  -H "Idempotency-Key: $(uuidgen)" \
  -d '{
    "model": "alibaba/wan-2.2-spicy/image-to-video",
    "input": {
      "image_url": "https://example.com/first-frame.jpg",
      "prompt": "She turns slowly toward the camera, silk robe slipping off one shoulder, warm candlelight, slow push-in",
      "duration_seconds": 5,
      "resolution": "480p"
    }
  }'
# → {"code":200,"data":{"taskId":"...","state":"queued",...}}

# 2) consulta hasta que state sea "succeeded" y luego lee data.output.assets[0].url
curl -s "https://api.spicyapi.ai/api/v1/jobs/recordInfo?taskId=TASK_ID" \
  -H "Authorization: Bearer $SPICY_API_KEY"
```

Los campos de entrada cambian según el modelo. Consulta el esquema en vivo con `GET /api/v1/models/{model}` (o en la página del modelo) antes de enviar una petición. Referencia completa: [docs.spicyapi.ai](https://docs.spicyapi.ai/docs?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=api-quickstart).

### Otros proveedores

Las políticas cambian a menudo y se aplican de forma distinta en cada modelo, así que prueba con tus propios prompts antes de comprometerte. Lee siempre la política de uso aceptable vigente del proveedor.

- [Venice.ai](https://venice.ai): chat y generación de imágenes privados y sin censura, con API.
- [fal.ai](https://fal.ai), [WaveSpeed](https://wavespeed.ai), [Replicate](https://replicate.com): grandes catálogos de modelos alojados; el tratamiento del contenido NSFW varía según el modelo y la configuración de la cuenta.
- [RunPod](https://www.runpod.io), [Vast.ai](https://vast.ai): alquila GPU y ejecuta tú mismo modelos de pesos abiertos (consulta [autoalojados](#modelos-autoalojados-y-de-pesos-abiertos)).

---

## Skills para agentes y servidores MCP

Los agentes de programación con IA (Claude Code, Cursor, Codex, Windsurf, Cline, Gemini CLI, OpenClaw) ya pueden generar contenido multimedia por ti mediante **skills** y **servidores MCP**. Pídelo en lenguaje natural ("haz un clip boudoir de 5 segundos a partir de esta imagen") y el agente elige el modelo, arma la petición y descarga el resultado.

| Recurso | Tipo | Instalación |
|---|---|---|
| 🌶️ [nsfw-ai-skill](https://github.com/Spicy-API/nsfw-ai-skill/blob/main/README.es.md) | Skill para agentes: generación de imágenes, video, edición y texto NSFW, ampliación de prompts, estimación de costos | `npx skills add Spicy-API/nsfw-ai-skill` |
| 🌶️ [Servidor MCP de SpicyAPI](https://docs.spicyapi.ai/docs/mcp?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=skills-table) (`@spicyapi/mcp`) | MCP: listar modelos, cotizar, crear / esperar / reintentar tareas, subir archivos | `claude mcp add spicyapi -e SPICY_API_KEY=$SPICY_API_KEY -- npx --yes --package=@spicyapi/mcp spicyapi-mcp` |
| 🌶️ [Skill oficial de SpicyAPI](https://github.com/Spicy-API/spicy-skill) | Skill para agentes que cubre toda la superficie para desarrolladores de SpicyAPI | `npx skills add Spicy-API/spicy-skill` |
| 🌶️ [CLI de SpicyAPI](https://docs.spicyapi.ai/docs?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=skills-table) (`@spicyapi/cli`) | Línea de comandos: modelos, cotizaciones, tareas, subidas | `npx @spicyapi/cli --help` |
| [anthropics/skills](https://github.com/anthropics/skills) | Skills de referencia y el formato de las skills | — |
| [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) | Directorio de servidores MCP | — |

---

## Modelos autoalojados y de pesos abiertos

Gratis de ejecutar, control total y ningún filtro de plataforma. A cambio, necesitas hardware, tiempo de configuración y revisar las licencias (lee cada licencia antes de un uso comercial).

### Video

- [Wan 2.2](https://github.com/Wan-Video/Wan2.2) y [Wan 2.1](https://github.com/Wan-Video/Wan2.1): los modelos de video abiertos de Alibaba (Apache-2.0). Enorme ecosistema de LoRAs de la comunidad; son la base de las ediciones alojadas Wan Spicy.
- [HunyuanVideo](https://github.com/Tencent-Hunyuan/HunyuanVideo): el modelo de video abierto de Tencent.
- [LTX-Video](https://github.com/Lightricks/LTX-Video) y [LTX-2](https://github.com/Lightricks/LTX-2): los modelos de video abiertos y rápidos de Lightricks.
- [CogVideoX](https://github.com/zai-org/CogVideo): el modelo de video abierto de Zhipu.
- [Mochi 1](https://github.com/genmoai/mochi): el modelo de video abierto de Genmo.
- [ComfyUI-WanVideoWrapper](https://github.com/kijai/ComfyUI-WanVideoWrapper): los nodos de ComfyUI de referencia para Wan, con soporte de LoRA.

### Imagen

- [Qwen-Image](https://github.com/QwenLM/Qwen-Image): generación y edición de imágenes abiertas.
- [Z-Image](https://github.com/Tongyi-MAI/Z-Image): el modelo de imagen abierto y eficiente de Alibaba Tongyi.
- [FLUX.1](https://github.com/black-forest-labs/flux): revisa la licencia de cada variante (dev no permite uso comercial).
- Checkpoints SDXL / Pony Diffusion / Illustrious en [Civitai](https://civitai.com) y [Hugging Face](https://huggingface.co): la mayor colección de checkpoints de la comunidad ajustados para NSFW.

**Guía aproximada de hardware:** los modelos de imagen funcionan con 8–12 GB de VRAM; los de video piden 16–24 GB (o versiones cuantizadas con menos calidad). Si no tienes GPU, alquila una en RunPod o Vast.ai, o usa una API alojada.

---

## Interfaces locales y herramientas de flujo de trabajo

- [ComfyUI](https://github.com/Comfy-Org/ComfyUI): flujos de trabajo por nodos para imagen y video; la opción más flexible.
- [Stable Diffusion WebUI (A1111)](https://github.com/AUTOMATIC1111/stable-diffusion-webui): la interfaz clásica, con un enorme ecosistema de extensiones.
- [Forge](https://github.com/lllyasviel/stable-diffusion-webui-forge): fork de A1111 más rápido y con menos consumo de VRAM.
- [InvokeAI](https://github.com/invoke-ai/InvokeAI): interfaz pulida basada en lienzo.
- [Fooocus](https://github.com/lllyasviel/Fooocus): la interfaz local de SDXL más sencilla.
- 🌶️ [SpicyAPI Studio](https://spicyapi.ai/es/create?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=interfaces-es): estudio de imagen y video en el navegador, con plantillas, [efectos](https://spicyapi.ai/es/create/effects?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=interfaces-es) y [estilos](https://spicyapi.ai/es/create/styles?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=interfaces-es); no necesitas GPU.

---

## LoRAs, checkpoints y entrenamiento

**Dónde encontrar LoRAs NSFW**

- [Civitai](https://civitai.com): la biblioteca más grande; filtra por modelo base (Wan 2.2, SDXL, Pony, Flux) y activa el contenido para adultos en la configuración de tu cuenta.
- [Hugging Face](https://huggingface.co): muchos LoRAs y ajustes completos; revisa la licencia en la ficha de cada modelo.
- [Tensor.Art](https://tensor.art): plataforma para compartir modelos con ejecución en línea.

**Usar LoRAs a través de una API.** Wan 2.2 Spicy LoRA acepta `loras`, `high_noise_loras` y `low_noise_loras` (hasta tres). Los LoRAs de ruido alto (high-noise) definen la composición y el movimiento al principio del proceso de eliminación de ruido; los de ruido bajo (low-noise) definen la textura y el detalle al final. Cada LoRA es un objeto con un `path` directo al archivo de pesos y un `scale` (0–4, por defecto 1); cambia un LoRA cada vez. Consulta la [página de Wan 2.2 Spicy LoRA](https://spicyapi.ai/es/models/wan-2-2-spicy-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=lora-es) para ver el esquema exacto.

**Entrenar los tuyos**

- [kohya_ss](https://github.com/bmaltais/kohya_ss): el entrenador de LoRAs de referencia para SD / SDXL.
- [OneTrainer](https://github.com/Nerogar/OneTrainer): LoRA y ajuste completo con interfaz gráfica.
- [ai-toolkit](https://github.com/ostris/ai-toolkit): entrenamiento para Flux, Wan y modelos más recientes.

Entrena solo con imágenes que te pertenezcan o sobre las que tengas derechos, y solo con adultos.

---

## Escalado, restauración y posproducción

- [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN): escalado 4× de imagen y video.
- [GFPGAN](https://github.com/TencentARC/GFPGAN) y [CodeFormer](https://github.com/sczhou/CodeFormer): restauración de rostros.
- [RIFE](https://github.com/hzwer/ECCV2022-RIFE): interpolación de fotogramas para cámara lenta más fluida.
- [FFmpeg](https://ffmpeg.org): cortar, unir y añadir audio (`ffmpeg -i clip.mp4 -i track.mp3 -c:v copy -shortest out.mp4`).
- [Topaz Video AI](https://www.topazlabs.com): escalador de video comercial.

---

## Cómo escribir prompts para contenido adulto

Un buen prompt NSFW se lee como un guion de planos, no como una lista de adjetivos. Los prompts de ejemplo se dejan en inglés.

```
[Subject: adult, age range, look] + [Wardrobe or state] + [Action: one clear motion]
+ [Setting] + [Lighting] + [Camera] + [Style / quality]
```

Es decir: sujeto (adulto, rango de edad, aspecto) + vestuario o estado + acción (un único movimiento claro) + escenario + iluminación + cámara + estilo / calidad.

Ejemplo (imagen a video):

```
A woman in her early 30s in a black silk slip dress sits on the edge of a hotel bed.
She slowly slides one strap off her shoulder and looks up at the camera.
Warm tungsten bedside lamp, soft shadows, city lights through the window.
Slow push-in from medium shot to close-up, shallow depth of field, 35mm film look.
```

Lo que marca la diferencia:

1. **Una acción principal por clip.** La respiración, el movimiento del pelo, un giro lento y el movimiento de la tela son fiables; las coreografías complejas y la interacción entre dos personas son lo primero que falla.
2. **Describe la cámara.** "Slow push-in", "static camera" u "orbit left" funcionan mejor que "cinematic".
3. **Nombra la luz.** Luz de velas, luz de ventana, contraluz de neón, hora dorada.
4. **Deja que el primer fotograma defina el aspecto.** En imagen a video, no vuelvas a describir todo lo que ya se ve; describe lo que *cambia*.
5. **Haz clips cortos.** 5 segundos es el punto ideal para que la anatomía se mantenga coherente; si necesitas más, extiende el clip en una segunda llamada.
6. **Indica siempre una edad adulta** ("in her 30s", "adult man in his 40s") y evita descripciones que sugieran juventud.

Más de 100 prompts probados, prompts negativos y una guía rápida de cámara e iluminación en **[nsfw-ai-video-prompts](https://github.com/Spicy-API/nsfw-ai-video-prompts/blob/main/README.es.md)**.

---

## Cómo elegir: guía de decisión

```
¿Tienes una GPU con 16 GB+ de VRAM y tiempo para experimentar?
├── Sí → ComfyUI + pesos abiertos de Wan 2.2 / Qwen-Image / Z-Image + LoRAs de Civitai (gratis, máximo control)
└── No
    ├── Sin código, en el navegador → SpicyAPI Studio (generador de imágenes y video sin censura)
    └── Con código o un agente de IA
        ├── Mucho volumen, poco presupuesto → Wan 2.2 Spicy / LTX 2.3 Spicy ($0.019/s a 480p)
        ├── Mejor calidad                   → Seedance 2.5 Spicy o Seedance 2.0 Spicy
        ├── Texto a video                   → Seedance 2.5 o Wan 3.0 (estándar, unrestricted)
        ├── Imágenes fijas                  → Qwen Image 2.1 (Qwen Image 2.1 LoRA para tu propio estilo)
        ├── Estilos personalizados          → Wan 2.2 Spicy LoRA / LTX 2.3 Spicy LoRA
        ├── Anime                           → Prefect Pony XL (imagen) → Vidu Q3 Spicy (movimiento)
        └── Desde Claude Code / Cursor      → nsfw-ai-skill o el servidor MCP de SpicyAPI
```

**Por caso de uso**

| Caso de uso | Combinación recomendada |
|---|---|
| Sitio de suscripción para adultos / contenido de creadores | Qwen Image 2.1 para imágenes → Seedance 2.0 Spicy o Wan 2.6 Spicy para clips → Video Upscaler |
| App de compañía con IA o de roleplay | Grok 4.7 o DeepSeek V4 para el chat → Qwen Image 2.1 para selfies → MiniMax H3 Spicy para movimientos cortos |
| Aficionado que experimenta mucho | Wan 2.2 Spicy a 480p, iterar y volver a renderizar los mejores a 720p |
| Contenido estilo anime / hentai | Prefect Pony XL → Vidu Q3 Spicy o Wan 2.2 Spicy LoRA con un LoRA de anime |
| Ficción erótica e historias interactivas | Grok 4.7 / Kimi K3 para el texto, Qwen Image 2.1 para las ilustraciones |

---

## Reglas que se aplican a todas las herramientas

No son opcionales y ninguna configuración las desactiva:

- **Nunca menores.** Nada de contenido sexual que represente a menores de 18 años o a cualquier persona que *parezca* menor de 18, en ningún estilo, incluidos el anime, la ilustración y el recurso de la "edad ficticia".
- **Nada de personas reales sin consentimiento documentado.** Nada de deepfakes sexuales, nada de cambiar la cara o la cabeza de personas reales para meterlas en contenido sexual, nada de fotos "desvestidas" o "desnudadas". Las figuras públicas no son una excepción.
- **Nada de suplantación de identidad, acoso, extorsión ni pruebas falsas** usando la imagen de nadie.
- **Cumple la ley de tu país y la de tu público.** Algunos países restringen cierto material ficticio o el contenido para adultos en general.
- **Etiqueta el contenido generado con IA** cuando las plataformas o las leyes lo exijan, y guarda constancia del consentimiento de cualquier persona real que aparezca.

Normas completas de SpicyAPI: [Política de contenidos](https://spicyapi.ai/es/legal/content-policy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=rules-es) y [Política de uso aceptable](https://spicyapi.ai/es/legal/acceptable-use?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=rules-es).

---

## Preguntas frecuentes

### ¿Cuál es el mejor generador de videos con IA NSFW en 2026?
En calidad, **Seedance 2.5 Spicy** (4–30 s, hasta 1080p nativo) y **Seedance 2.0 Spicy** encabezan las ediciones Spicy de imagen a video; para texto a video usa los estándar **Seedance 2.5** o **Wan 3.0**, ambos `unrestricted` en el catálogo. En precio, **Wan 2.2 Spicy** y **LTX 2.3 Spicy** empiezan en $0.019 por segundo. Si quieres estilos personalizados, usa **Wan 2.2 Spicy LoRA**. Todos están disponibles con una sola API en [SpicyAPI](https://spicyapi.ai/es?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=faq-es).

### ¿Cuál es el mejor generador de imágenes con IA sin censura?
Alojados: **Qwen Image 2.1** (desde $0.024/imagen, nivel `unrestricted` en el catálogo) para trabajo fotorrealista y editorial, con **Qwen Image 2.1 LoRA** para tus propios estilos; **Z-Image Spicy** (desde $0.01235/imagen) para grandes volúmenes al menor precio; **Prefect Pony XL** para anime. Autoalojados: checkpoints de la comunidad SDXL, Pony e Illustrious en ComfyUI o Forge.

### ¿Cómo convierto una imagen en un video NSFW?
Genera o elige un primer fotograma (un adulto ficticio, o tú mismo) y envíalo a un modelo NSFW de imagen a video como Wan 2.2 Spicy, con un prompt corto que describa el movimiento y la cámara. Consulta el [inicio rápido de la API](#inicio-rápido-imagen-a-video-nsfw-por-http) o usa la [herramienta de imagen a video](https://spicyapi.ai/es/create/image-to-video?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=faq-es) en el navegador.

### ¿Hay algún generador de IA NSFW gratis?
Ejecutar modelos de pesos abiertos en local (ComfyUI + Wan 2.2, Qwen-Image o Z-Image) es gratis, sin contar el hardware y la electricidad. Los servicios alojados cobran porque las GPU cuestan dinero; SpicyAPI no tiene suscripción y cobra por resultado, con reembolso de las tareas fallidas.

### ¿Cuál es la API de video con IA NSFW más barata?
En el catálogo de SpicyAPI (2026-09-27), el precio por segundo más bajo de un modelo de video Spicy es el de **Seedance 1.5 Pro Spicy, a $0.012/s** (480p, sin audio), seguido de **Wan 2.2 Spicy** y **LTX 2.3 Spicy, a $0.019/s** (480p).

### ¿Es legal generar contenido NSFW con IA?
Generar contenido sexual de **adultos ficticios** es legal en la mayoría de los países, pero las leyes varían y hay contenido que es ilegal en todas partes: cualquier cosa que involucre a menores y el contenido sexual de personas reales creado sin su consentimiento. Tú eres responsable de lo que creas y compartes. Esto no es asesoramiento legal.

### ¿Qué diferencia hay entre los modelos "sin censura" y los "Spicy"?
"Sin censura" suele describir una plataforma o un modelo que no rechaza prompts para adultos. En SpicyAPI, las ediciones "Spicy" son versiones concretas de modelos ajustadas para contenido adulto; los modelos estándar aparecen con su propio nivel de política para que veas cuáles suavizan o filtran el contenido.

### ¿Puedo usar IA NSFW dentro de Claude Code, Cursor u otros agentes?
Sí. Instala [nsfw-ai-skill](https://github.com/Spicy-API/nsfw-ai-skill/blob/main/README.es.md) (`npx skills add Spicy-API/nsfw-ai-skill`) o añade el servidor MCP de SpicyAPI, define `SPICY_API_KEY` y pídeselo al agente en lenguaje natural.

---

## Repositorios relacionados

- **[nsfw-ai-video-prompts](https://github.com/Spicy-API/nsfw-ai-video-prompts/blob/main/README.es.md)**: más de 100 prompts de video NSFW, prompts para imágenes de referencia, prompts negativos y consejos específicos para cada modelo.
- **[nsfw-ai-skill](https://github.com/Spicy-API/nsfw-ai-skill/blob/main/README.es.md)**: skill para agentes que genera imágenes, video y texto NSFW desde Claude Code, Cursor, Codex y más.
- **[spicy-skill](https://github.com/Spicy-API/spicy-skill)** · **[spicy-mcp](https://github.com/Spicy-API/spicy-mcp)** · **[spicy-sdk](https://github.com/Spicy-API/spicy-sdk)**: herramientas oficiales de SpicyAPI para desarrolladores.

## Cómo contribuir

Se aceptan aportaciones, incluidos los competidores. Lee primero [CONTRIBUTING.md](CONTRIBUTING.md). En resumen: un recurso por pull request, una descripción neutral de una línea, un enlace que funcione y ningún recurso cuyo propósito principal sea crear imágenes sin consentimiento, contenido con menores o eludir la ley.

## Licencia

[CC0 1.0](LICENSE). En la medida en que la ley lo permita, los colaboradores han renunciado a todos los derechos de autor sobre esta lista.

<p align="center"><sub>¿Te ha resultado útil? ⭐ Dale una estrella al repositorio para que otros creadores lo encuentren.</sub></p>
