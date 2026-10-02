<!--
  Keywords: NSFW нейросеть, нейросеть 18+, нейросеть без цензуры, ИИ без цензуры, генерация видео без цензуры,
  нейросеть для видео без цензуры, генерация изображений без цензуры, NSFW генерация видео, видео из фото нейросеть 18+,
  NSFW редактор изображений, LLM без цензуры, NSFW AI API, нейросети для взрослых, лучшие NSFW нейросети 2026,
  Wan 2.2 Spicy, Seedance Spicy, NSFW AI skill, NSFW MCP,
  awesome nsfw ai, nsfw ai generator, uncensored ai image generator, uncensored ai video generator, nsfw image to video
-->

<p align="center"><a href="README.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.fr.md">Français</a> · <a href="README.es.md">Español</a> · <b>Русский</b></p>

<h1 align="center">Awesome NSFW AI</h1>

<p align="center">
  <b>Подборка NSFW-нейросетей 2026 года для взрослых авторов и разработчиков: генерация изображений и видео без цензуры, модели «изображение в видео», редакторы изображений, LLM без цензуры, API, навыки для агентов, MCP-серверы и инструменты.</b>
</p>

<p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
  <img src="https://img.shields.io/badge/updated-2026--09--27-blue" alt="Последнее обновление 2026-09-27">
  <img src="https://img.shields.io/badge/18%2B-adults%20only-red" alt="Только 18+">
  <img src="https://img.shields.io/badge/license-CC0--1.0-lightgrey" alt="Лицензия CC0">
</p>

<p align="center">
  <img src="assets/wolf-turn-and-look-back.gif" width="24%" alt="Пример результата Wan 2.2 Spicy (изображение в видео)">
  <img src="assets/velvet-spiral-turn.gif" width="24%" alt="Пример результата Seedance 2.0 Spicy (изображение в видео)">
  <img src="assets/silk-draught-pull.gif" width="24%" alt="Пример результата Wan 2.7 Spicy (изображение в видео)">
  <img src="assets/hotel-window-turn.gif" width="24%" alt="Пример результата Seedance 2.5 Spicy (изображение в видео)">
  <br><sub>Реальные результаты Wan 2.2 Spicy, Seedance 2.0 Spicy, Wan 2.7 Spicy и Seedance 2.5 Spicy. Больше примеров с точными промптами — в <a href="https://github.com/Spicy-API/nsfw-ai-video-prompts/blob/main/README.ru.md#примеры-реальные-результаты-и-их-промпты">nsfw-ai-video-prompts</a>.</sub>
</p>

<p align="center">
  <a href="#нейросети-для-генерации-видео-без-цензуры">Видео</a> ·
  <a href="#нейросети-для-генерации-изображений-без-цензуры">Изображения</a> ·
  <a href="#nsfw-редакторы-изображений-и-инструменты-для-лиц">Редактирование</a> ·
  <a href="#llm-без-цензуры-и-ролевые-игры">LLM</a> ·
  <a href="#nsfw-ai-api">API</a> ·
  <a href="#навыки-для-агентов-и-mcp-серверы">Навыки &amp; MCP</a> ·
  <a href="#модели-для-самостоятельного-запуска-и-открытые-веса">Свой сервер</a> ·
  <a href="#частые-вопросы-faq">FAQ</a>
</p>

> **Только 18+.** В этом списке собраны инструменты, которые могут создавать контент для взрослых. Любой ресурс отсюда можно использовать только с вымышленными взрослыми или с реальными взрослыми, давшими документально подтверждённое согласие, и только в рамках законов страны, где живёте вы и ваша аудитория. См. [Правила для всех инструментов](#правила-для-всех-инструментов).

> **Раскрытие информации:** список ведёт команда [SpicyAPI](https://spicyapi.ai/ru?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=disclosure-ru) — API с оплатой по факту использования для моделей изображений, видео и текста без цензуры. Позиции SpicyAPI отмечены 🌶️. Сторонние инструменты попали сюда, потому что они полезны, а не потому что платят за размещение. Pull request'ы с конкурентами приветствуются.

---

## TL;DR: быстрый выбор

| Мне нужно… | С чего начать | Почему (рейтинги SpicyAPI, 2026-09-27) |
|---|---|---|
| Лучшая универсальная NSFW-модель для видео | [Wan 3.0](https://spicyapi.ai/ru/models/wan-3-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ru) | Spicy Index 76.5 (#2 из 37), Freedom 96; все откровенные тестовые промпты выполнены (9/9); T2V, I2V и видео по референсу до 30 с; $0.45 за 5 с в 720p |
| NSFW-видео в моём стиле или с моим персонажем | [MiniMax H3 LoRA](https://spicyapi.ai/ru/models/minimax-h3-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ru) или [MiniMax H3 Singularity LoRA](https://spicyapi.ai/ru/models/minimax-h3-singularity-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ru) | Spicy Index 75.2 / 72.8, Freedom 98.3 / 100 |
| Видео из изображения без цензуры в Spicy-версии | 🌶️ [Seedance 2.5 Spicy](https://spicyapi.ai/ru/models/seedance-2-5-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ru), 🌶️ [Wan 2.7 Spicy](https://spicyapi.ai/ru/models/wan-2-7-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ru) или 🌶️ [Vidu Q3 Spicy](https://spicyapi.ai/ru/models/vidu-q3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ru) | Freedom 96.7–100, все откровенные тестовые промпты выполнены (3/3) |
| Дешёвое NSFW-видео в больших объёмах | [Wan 2.6 Flash](https://spicyapi.ai/ru/models/wan-2-6-flash?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ru) или 🌶️ [Seedance 1.5 Pro Spicy](https://spicyapi.ai/ru/models/seedance-1-5-pro-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ru) | Freedom 100 / 96.7 при цене $0.11–0.13 за 5 с (720p) |
| Генерация изображений по тексту без цензуры | [Qwen Image 2.1](https://spicyapi.ai/ru/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ru) | Spicy Index 73, Freedom 96.3, от $0.024 за изображение; длинные промпты, 15 соотношений сторон |
| Изображения в моём стиле (включая аниме) | [Qwen Image 2.1 LoRA](https://spicyapi.ai/ru/models/qwen-image-2-1-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ru) или [MiniMax H3 Image LoRA](https://spicyapi.ai/ru/models/minimax-h3-image-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ru) | #1 и #2 в Spicy Index для изображений (80.5 / 74.5), Freedom 92 / 100 |
| Нейросеть-редактор изображений без цензуры | [Qwen Image 2.1 Edit](https://spicyapi.ai/ru/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ru) | То же семейство, что и выше; 1–10 референсных изображений + одна инструкция, без маски |
| Чат, ролевые игры или написание промптов без цензуры | [Grok 4.7](https://spicyapi.ai/ru/models/grok-4-7?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ru) или [Grok 4.3](https://spicyapi.ai/ru/models/grok-4-3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ru) | Freedom 100 / 98.9 в текстовом рейтинге; Grok 4.3 самый быстрый (медиана ≈4 с) |
| Всё локально и бесплатно | [ComfyUI](https://github.com/Comfy-Org/ComfyUI) + открытые веса [Wan 2.2](https://github.com/Wan-Video/Wan2.2) | Нужна мощная видеокарта (с 24 ГБ VRAM комфортно) |
| Чтобы Claude Code / Cursor генерировали за меня | [nsfw-ai-skill](https://github.com/Spicy-API/nsfw-ai-skill/blob/main/README.ru.md) или официальный [MCP-сервер SpicyAPI](https://docs.spicyapi.ai/docs/mcp?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) | Генерация из агента запросами на обычном языке |
| Готовые промпты для изображений | [nsfw-ai-image-prompts](https://github.com/Spicy-API/nsfw-ai-image-prompts/blob/main/README.ru.md) | 104 промпта для генерации и редактирования изображений для Qwen Image 2.1, Seedream 5.0 и других моделей, плюс 72 реальных примера |
| Готовые промпты для видео | [nsfw-ai-video-prompts](https://github.com/Spicy-API/nsfw-ai-video-prompts/blob/main/README.ru.md) | 116 готовых видеопромптов и 128 реальных примеров, у каждого указан промпт |

Оценки взяты из публичных [рейтингов SpicyAPI](https://spicyapi.ai/ru/leaderboards?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ru) (методология v2.1, тесты с 2026-09-14 по 2026-09-27; см. [как здесь ранжируются модели](#как-здесь-ранжируются-модели)). Цены указаны по тарифу из каталога; более высокое разрешение, звук и длинные ролики стоят дороже.

---

## Содержание

- [TL;DR: быстрый выбор](#tldr-быстрый-выбор)
- [Что на самом деле означают «NSFW AI» и «нейросеть без цензуры»](#что-на-самом-деле-означают-nsfw-ai-и-нейросеть-без-цензуры)
- [Нейросети для генерации видео без цензуры](#нейросети-для-генерации-видео-без-цензуры)
  - [Все видеомодели без цензуры по популярности](#все-видеомодели-без-цензуры-по-популярности)
  - [Сколько стоит 5-секундный NSFW-ролик](#сколько-стоит-5-секундный-nsfw-ролик)
- [Нейросети для генерации изображений без цензуры](#нейросети-для-генерации-изображений-без-цензуры)
- [NSFW-редакторы изображений и инструменты для лиц](#nsfw-редакторы-изображений-и-инструменты-для-лиц)
- [LLM без цензуры и ролевые игры](#llm-без-цензуры-и-ролевые-игры)
- [NSFW AI API](#nsfw-ai-api)
- [Навыки для агентов и MCP-серверы](#навыки-для-агентов-и-mcp-серверы)
- [Модели для самостоятельного запуска и открытые веса](#модели-для-самостоятельного-запуска-и-открытые-веса)
- [Локальные интерфейсы и инструменты для пайплайнов](#локальные-интерфейсы-и-инструменты-для-пайплайнов)
- [LoRA, чекпойнты и обучение](#lora-чекпойнты-и-обучение)
- [Апскейл, восстановление и постобработка](#апскейл-восстановление-и-постобработка)
- [Промпты для контента 18+](#промпты-для-контента-18)
- [Как выбрать: схема решения](#как-выбрать-схема-решения)
- [Правила для всех инструментов](#правила-для-всех-инструментов)
- [Частые вопросы (FAQ)](#частые-вопросы-faq)
- [Связанные репозитории](#связанные-репозитории)
- [Как внести вклад](#как-внести-вклад)

---

## Что на самом деле означают «NSFW AI» и «нейросеть без цензуры»

**NSFW AI** — это любая генеративная модель или инструмент, способные создавать обнажённую натуру или сексуальный контент для взрослых. **Нейросеть без цензуры** (uncensored AI) — более размытый термин для моделей, которые не отказываются выполнять промпты 18+ и не размывают результат.

Сработает ли NSFW-запрос, зависит от трёх вещей, которые постоянно путают:

1. **Модель.** Одни модели обучены или дообучены так, чтобы разрешать контент для взрослых. Другие обучены отказывать, и никакие настройки платформы это не изменят.
2. **Собственный фильтр платформы.** Многие облачные сервисы добавляют поверх модели слой модерации (стоп-листы промптов, классификаторы результата, размытие). Даже лояльная модель за строгим фильтром всё равно будет блокироваться.
3. **Местные законы и условия платформы.** «Модель это умеет» не означает «вам это разрешено». Некоторый контент незаконен везде (см. [правила](#правила-для-всех-инструментов)).

Как читать списки ниже:

| Метка | Что означает |
|---|---|
| **Spicy / NSFW-версия** | Версия модели, настроенная или сконфигурированная для контента 18+. В SpicyAPI в названии таких моделей есть «Spicy». |
| **Допускает 18+** | Модель общего назначения, которая часто допускает контент для взрослых, но может смягчать или отклонять часть запросов. |
| **С фильтром** | Модель или провайдер применяют собственный контент-фильтр. Подходит для SFW-задач, ненадёжна для NSFW. |

В SpicyAPI у каждой модели публичного каталога есть уровень политики (`unrestricted`, `softened`, `borderline`, `filtered`), а [рейтинги](https://spicyapi.ai/ru/leaderboards?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=definitions-ru) публикуют **Freedom Score** по результатам повторяющихся тестовых промптов. Платформа не добавляет поверх модели собственный фильтр; если фильтрация есть, она идёт от провайдера модели.


### Как здесь ранжируются модели

Рекомендации в этом списке опираются на опубликованные результаты тестов SpicyAPI, а не на рекламные тексты:

- **Freedom Score (0–100)**: насколько надёжно модель выполняет то, что просит промпт 18+, на пяти уровнях: L1 — намёки, L2 — частичная обнажённость, L3 — обнажённость, L4 — откровенный контент, L5 — экстремальный. Каждый уровень даёт 20 баллов × доля успешных прогонов × достоверность, поэтому смягчённые или подменённые результаты теряют баллы. ✅ 90+ · ◐ 70–89 · ⚠️ ниже 70 · 🧪 пока меньше 15 тестовых прогонов, поэтому низкое число отражает пробелы в покрытии, а не отказы.
- **Spicy Index (0–100)**: пока *предварительный* — оценка возможностей по публичной спецификации (нативное разрешение, максимальная длина ролика, звук, типы входных данных и т. д.). Голоса за качество на арене ещё не учтены, поэтому визуальное качество он пока не измеряет.
- **Инженерная проверка маршрутов**: прежде чем модель попадёт в список, команда генерирует откровенные тестовые примеры на каждом upstream-маршруте и покадрово проверяет скачанный результат (статуса «success» недостаточно: некоторые провайдеры молча подменяют результат безопасным изображением). Модели, которые выдают откровенный контент только на части маршрутов, здесь не рекомендуются.

Полные отчёты по каждой модели с количеством прогонов на каждом уровне: [рейтинги SpicyAPI](https://spicyapi.ai/ru/leaderboards?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=method-ru). Тестовые результаты уровней L4/L5 никогда не публикуются.

---

## Нейросети для генерации видео без цензуры

«Изображение в видео» (I2V) — самый надёжный способ сделать NSFW-видео нейросетью: внешний вид вы задаёте первым кадром, а модели остаётся только его оживить. «Текст в видео» (T2V) и «видео по референсу» (Ref2V, «помести персонажа с этих изображений в новую сцену») доступны в стандартных моделях ниже.

### Все видеомодели без цензуры по популярности

Порядок как в каталоге SpicyAPI: сначала самые популярные, а внутри семейства — сначала новейшая версия. 🌶️ **Spicy**-версии настроены на контент 18+. Перечисленные здесь **стандартные** модели имеют в каталоге уровень `unrestricted` (провайдер не применяет контент-фильтр), поэтому тоже принимают промпты 18+. Цены — по самому дешёвому тарифу. Каталог прочитан <!-- catalog:date -->
2026-09-27
<!-- /catalog:date -->

<!-- catalog:video -->
| Модель | Тип | Задачи | Длительность | От | Spicy Index | Freedom |
|---|---|---|---|---|---|---|
| [Seedance 2.5 Spicy](https://spicyapi.ai/ru/models/seedance-2-5-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | 🌶️ Spicy | I2V | 4–30 s | $0.216/s | 56.5 | ✅ 96.7 |
| [Seedance 2.5](https://spicyapi.ai/ru/models/seedance-2-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | I2V, Ref2V, T2V | 4–30 s | $0.1234/s | 69.5 | ◐ 80.9 |
| [Seedance 2.0 Spicy](https://spicyapi.ai/ru/models/seedance-2-0-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | 🌶️ Spicy | I2V | 4–15 s | $0.114/s | 61.5 | ✅ 93.3 |
| [Seedance 2.0](https://spicyapi.ai/ru/models/seedance-2-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | I2V, Ref2V, T2V | 4–15 s | $0.07/s | 81.5 | ◐ 70.4 |
| [Wan 3.0 Prime](https://spicyapi.ai/ru/models/wan-3-0-prime?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | I2V, Ref2V, T2V | 2–30 s | $0.0612/s | 76.5 | ◐ 78 |
| [Wan 3.0](https://spicyapi.ai/ru/models/wan-3-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | I2V, Ref2V, T2V | 2–30 s | $0.045/s | 76.5 | ✅ 96 |
| [MiniMax H3 Spicy](https://spicyapi.ai/ru/models/minimax-h3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | 🌶️ Spicy | I2V | 3–15 s | $0.038/s | 29.5 | ✅ 97.5 |
| [MiniMax H3](https://spicyapi.ai/ru/models/minimax-h3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | I2V, Ref2V, T2V | 4–15 s | $0.025/s | 72.5 | 🧪 33.3 |
| [MiniMax H3 Singularity LoRA](https://spicyapi.ai/ru/models/minimax-h3-singularity-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | I2V, Ref2V | 3–15 s | $0.06/s | 72.8 | ✅ 100 |
| [LTX 2.5](https://spicyapi.ai/ru/models/ltx-2-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | I2V, T2V | 5–20 s | $0.09/s | 66 | ◐ 80.3 |
| [Wan 3.0 Pro Prime](https://spicyapi.ai/ru/models/wan-3-0-pro-prime?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | I2V, Ref2V, T2V | 2–30 s | $0.234/s | 76.5 | ◐ 82 |
| [Wan 3.0 Pro](https://spicyapi.ai/ru/models/wan-3-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | I2V, Ref2V, T2V | 2–30 s | $0.144/s | 76.5 | ◐ 82 |
| [MiniMax H3 LoRA](https://spicyapi.ai/ru/models/minimax-h3-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | I2V, Ref2V, T2V | 3–15 s | $0.05/s | 75.2 | ✅ 98.3 |
| [HappyHorse 1.1](https://spicyapi.ai/ru/models/happyhorse-1-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | I2V, Ref2V, T2V | 3–15 s | $0.14/s | 62.5 | ⚠️ 65.1 |
| [Seedance 2.0 Mini Spicy](https://spicyapi.ai/ru/models/seedance-2-0-mini-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | 🌶️ Spicy | I2V | 4–15 s | $0.0387/s | 44.5 | ✅ 93.3 |
| [Seedance 2.0 Mini](https://spicyapi.ai/ru/models/seedance-2-0-mini?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | I2V, Ref2V, T2V | 4–15 s | $0.01097/s | 64.5 | ⚠️ 64.9 |
| [Wan 2.7 Spicy](https://spicyapi.ai/ru/models/wan-2-7-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | 🌶️ Spicy | I2V | 2–15 s | $0.1235/s | 46.5 | ✅ 100 |
| [LTX 2.3 Spicy](https://spicyapi.ai/ru/models/ltx-2-3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | 🌶️ Spicy | I2V | 3–20 s | $0.019/s | 33.5 | ◐ 89.2 |
| [LTX 2.3 Spicy LoRA](https://spicyapi.ai/ru/models/ltx-2-3-spicy-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | 🌶️ Spicy | I2V | 3–20 s | $0.0285/s | 34.8 | ◐ 83.8 |
| [Seedance 2.0 Fast Spicy](https://spicyapi.ai/ru/models/seedance-2-0-fast-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | 🌶️ Spicy | I2V | 4–15 s | $0.081/s | 44.5 | ✅ 90 |
| [Seedance 2.0 Fast](https://spicyapi.ai/ru/models/seedance-2-0-fast?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | I2V, Ref2V, T2V | 4–15 s | $0.02254/s | 64.5 | ⚠️ 68.2 |
| [Vidu Q3 Turbo](https://spicyapi.ai/ru/models/vidu-q3-turbo?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | I2V | 1–16 s | $0.042/s | 39.5 | ✅ 93.3 |
| [Vidu Q3 Spicy](https://spicyapi.ai/ru/models/vidu-q3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | 🌶️ Spicy | I2V | 1–16 s | $0.0665/s | 46.5 | ✅ 96.7 |
| [Vidu Q3](https://spicyapi.ai/ru/models/vidu-q3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | I2V | 1–16 s | $0.07/s | 46.5 | ✅ 93.3 |
| [Vidu Q3 Pro](https://spicyapi.ai/ru/models/vidu-q3-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | I2V | 1–16 s | $0.054/s | 36.5 | ✅ 93.3 |
| [Seedance 1.5 Pro Spicy](https://spicyapi.ai/ru/models/seedance-1-5-pro-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | 🌶️ Spicy | I2V | 4–12 s | $0.012/s | 48.5 | ✅ 96.7 |
| [Seedance 1.5 Pro](https://spicyapi.ai/ru/models/seedance-1-5-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | I2V, T2V | 4–12 s | $0.0112/s | 46 | ✅ 90 |
| [Wan 2.6 Flash](https://spicyapi.ai/ru/models/wan-2-6-flash?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | I2V | 5, 10, 15 s | $0.0225/s | 31.5 | ✅ 100 |
| [Wan 2.6 Spicy](https://spicyapi.ai/ru/models/wan-2-6-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | 🌶️ Spicy | I2V | 5, 10, 15 s | $0.095/s | 46.5 | ✅ 96.7 |
| [Wan 2.6](https://spicyapi.ai/ru/models/wan-2-6?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | I2V, Ref2V, T2V | 5, 10, 15 s | $0.065/s | 58.5 | 🧪 8.7 |
| [Wan 2.5](https://spicyapi.ai/ru/models/wan-2-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | I2V, T2V | 5, 10 s | $0.045/s | 46 | ✅ 99 |
| [Wan 2.2 Spicy](https://spicyapi.ai/ru/models/wan-2-2-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | 🌶️ Spicy | I2V | 5, 8 s | $0.019/s | 23.5 | ✅ 91.2 |
| [Wan 2.2 Spicy LoRA](https://spicyapi.ai/ru/models/wan-2-2-spicy-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | 🌶️ Spicy | I2V, Extend | 5, 8 s | $0.024/s | 25 | ◐ 74.8 |
| [Wan 2.2 LoRA](https://spicyapi.ai/ru/models/wan-2-2-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | I2V | 5, 8 s | $0.024/s | 22.5 | ◐ 88.8 |
<!-- /catalog:video -->

Проверенные варианты (откровенные = тестовые промпты уровня L4, выполненные как запрошено):

- **Лучшая универсальная: Wan 3.0.** Spicy Index 76.5, Freedom 96, откровенные 9/9, $0.45 за 5 с в 720p, ролики до 30 с. Wan 3.0 Pro и Pro Prime тоже выполняют откровенные промпты (9/9), но набирают меньше по Freedom (82), в основном на экстремальном уровне (L5).
- **Свои стили и персонажи: MiniMax H3 LoRA** (Index 75.2, Freedom 98.3, откровенные 11/13) и **MiniMax H3 Singularity LoRA** (Index 72.8, Freedom 100, откровенные 8/8).
- **Seedance для контента 18+: Seedance 2.5** (Index 69.5, Freedom 80.9, откровенные 8/9) для «текст в видео» и «видео по референсу»; для генерации видео из изображения без цензуры используйте 🌶️ **Seedance 2.5 Spicy** (Freedom 96.7, откровенные 3/3).
- **Самые свободные: Wan 2.7 Spicy, Wan 2.6 Flash и MiniMax H3 Singularity LoRA** (Freedom 100), **Wan 2.5** (99).
- **Бюджетные: Wan 2.6 Flash** ($0.11 за 5 с, Freedom 100), 🌶️ **Seedance 1.5 Pro Spicy** ($0.13, Freedom 96.7) и **MiniMax H3** ($0.185 за 5 с в 768p; все 14 тестовых роликов вышли как запрошено; низкий Freedom объясняется только тем, что часть уровней ещё не покрыта). 🌶️ Wan 2.2 Spicy и LTX 2.3 Spicy стоят $0.19, но чаще смягчают верхний уровень.
- **В тестах смягчают откровенные промпты**, поэтому лучше берите Spicy-версию того же семейства: стандартная Seedance 2.0 (Freedom 70.4, откровенные 1/9; у неё самая высокая оценка возможностей среди всех видеомоделей, так что для контента с намёками она отлична), Seedance 2.0 Fast / Mini (68.2 / 64.9), HappyHorse 1.1 (65.1) и Wan 2.2 (43.1).
- **Пока мало тестовых данных:** стандартная Wan 2.6 (5 прогонов); 🌶️ Wan 2.6 Spicy протестирована полностью (Freedom 96.7).
- **О чём предупреждают обзоры:** Wan 3.0 иногда заходит дальше промпта (следите за последними секундами), обрабатывает задачу около 3,5 минуты, а её режим «видео по референсу» отклоняет фотографии реальных лиц. Seedance 2.5 точнее всех следует длинному сценарию; Seedance 2.5 Spicy заходит дальше на самых сложных уровнях.

Некоторые видеоэндпоинты тарифицируют целыми блоками (например, 6-секундный ролик при блоке в 5 секунд оплачивается как 10 с); длина блока указана на странице модели, а сумма в предварительной оценке — это максимум, который с вас могут списать. Смотрите и фильтруйте все модели на странице [SpicyAPI › Нейросети без цензуры](https://spicyapi.ai/ru/explore/uncensored-ai-models?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=video-table-ru).

### Сколько стоит 5-секундный NSFW-ролик

Стоимость одного 5-секундного ролика в 720p (768p для MiniMax) по ценовой оси рейтинга на 2026-09-27, рядом с Freedom Score. Более низкие разрешения дешевле.

| Модель | 1 ролик (5 с) | 100 роликов | 1000 роликов | Freedom |
|---|---|---|---|---|
| Wan 2.6 Flash | $0.11 | $11.25 | $112.50 | ✅ 100 |
| 🌶️ Seedance 1.5 Pro Spicy | $0.13 | $13.00 | $130 | ✅ 96.7 |
| MiniMax H3 | $0.185 | $18.50 | $185 | 🧪 33.3 (14/14 роликов как запрошено) |
| 🌶️ Wan 2.2 Spicy | $0.19 | $19.00 | $190 | ✅ 91.2 |
| 🌶️ LTX 2.3 Spicy | $0.19 | $19.00 | $190 | ◐ 89.2 |
| 🌶️ MiniMax H3 Spicy | $0.42 | $42.00 | $420 | ✅ 97.5 |
| Wan 3.0 | $0.45 | $45.00 | $450 | ✅ 96 |
| Wan 2.5 | $0.45 | $45.00 | $450 | ✅ 99 |
| 🌶️ Wan 2.6 Spicy | $0.475 | $47.50 | $475 | ✅ 96.7 |
| MiniMax H3 LoRA | $0.50 | $50.00 | $500 | ✅ 98.3 |
| 🌶️ Wan 2.7 Spicy | $0.62 | $61.75 | $617.50 | ✅ 100 |
| MiniMax H3 Singularity LoRA | $0.63 | $62.50 | $625 | ✅ 100 |
| 🌶️ Vidu Q3 Spicy | $0.71 | $71.25 | $712.50 | ✅ 96.7 |
| 🌶️ Seedance 2.0 Spicy | $1.14 | $114.00 | $1,140 | ✅ 93.3 |
| Seedance 2.5 | $1.39 | $138.65 | $1,386.50 | ◐ 80.9 |
| 🌶️ Seedance 2.5 Spicy | $2.16 | $216.00 | $2,160 | ✅ 96.7 |

В 480p большинство этих моделей стоит примерно вдвое дешевле (например, Wan 2.2 Spicy — $0.095, а Seedance 1.5 Pro Spicy — $0.06 за 5 с). За неудачные задачи деньги возвращаются автоматически.

---

## Нейросети для генерации изображений без цензуры

**Рекомендуем: [Qwen Image 2.1](https://spicyapi.ai/ru/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-ru)**: Spicy Index 73, Freedom 96.3 (откровенные 5/6), от $0.024 за изображение в 1k. Следует длинным описаниям (до 5000 символов), выдаёт 15 соотношений сторон в 1k, 1.5k или 2k и в том же семействе редактирует по 1–10 референсным изображениям.

Другие проверенные варианты:

- **Свой стиль или персонаж (включая аниме): [Qwen Image 2.1 LoRA](https://spicyapi.ai/ru/models/qwen-image-2-1-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-ru)**: #1 в Spicy Index для изображений (80.5), Freedom 92, до трёх LoRA. **[MiniMax H3 Image LoRA](https://spicyapi.ai/ru/models/minimax-h3-image-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-ru)**: Index 74.5, Freedom 100 (откровенные 8/8), сочетается с видеомоделью MiniMax H3.
- **Seedream: [Seedream 5.0 Lite](https://spicyapi.ai/ru/models/seedream-5-0-lite?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-ru) / [Seedream 5.0 Pro](https://spicyapi.ai/ru/models/seedream-5-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-ru)**: Index 73, Freedom 96 / 94.3. Seedream 4.0 хорошо набирает по возможностям (74), но ниже по Freedom (74.7).
- **Текст на изображении (постеры, обложки): [Qwen Image 3.0 Pro](https://spicyapi.ai/ru/models/qwen-image-3-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-ru)**: Freedom 98, откровенные 6/6.
- **Самые дешёвые: 🌶️ [Z-Image Spicy](https://spicyapi.ai/ru/models/z-image-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-ru)** ($0.01235, Freedom 98.8) и [Z-Image Turbo LoRA](https://spicyapi.ai/ru/models/z-image-turbo-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-ru) ($0.012, Freedom 95). Оценки возможностей ниже (32 / 46.5), так что используйте их для объёма и черновиков.
- **Не рекомендуются для NSFW:** Krea 2 (Freedom 10), Wan 2.7 / Wan 2.7 Pro в режиме «текст в изображение» (уровни обнажённости и откровенного контента в основном смягчаются), FLUX.1 Dev LoRA (75, откровенные 0/6). У Prefect Pony XL пока всего 3 тестовых прогона (Freedom 36); считайте её вариантом для аниме с промптами из тегов, а не проверенным NSFW-выбором.

Все модели изображений без цензуры в порядке каталога:

<!-- catalog:image -->
| Модель | Тип | Задачи | От | Spicy Index | Freedom |
|---|---|---|---|---|---|
| [Qwen Image 2.1](https://spicyapi.ai/ru/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | Edit, T2I | $0.024/image | 73 | ✅ 96.3 |
| [Qwen Image 2.1 LoRA](https://spicyapi.ai/ru/models/qwen-image-2-1-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | Edit, T2I | $0.03/image | 80.5 | ✅ 92 |
| [MiniMax H3 Image LoRA](https://spicyapi.ai/ru/models/minimax-h3-image-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | Edit, T2I | $0.042/image | 74.5 | ✅ 100 |
| [Qwen Image 3.0 Pro](https://spicyapi.ai/ru/models/qwen-image-3-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | Edit, T2I | $0.04/image | 56 | ✅ 98 |
| [Qwen Image 3.0](https://spicyapi.ai/ru/models/qwen-image-3-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | Edit, T2I | $0.03/image | 56 | ✅ 96 |
| [Seedream 5.0 Pro](https://spicyapi.ai/ru/models/seedream-5-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | Edit, T2I | $0.036/image | 73 | ✅ 94.3 |
| [Qwen Image Edit Spicy](https://spicyapi.ai/ru/models/qwen-image-spicy-edit?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | 🌶️ Spicy | Edit | $0.038/image | 14 | ✅ 96 |
| [Seedream 5.0 Lite](https://spicyapi.ai/ru/models/seedream-5-0-lite?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | Edit, T2I | $0.0345/image | 73 | ✅ 96 |
| [Qwen Image 2](https://spicyapi.ai/ru/models/alibaba-qwen-image-2?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | Edit, T2I | $0.035/image | 34 | ✅ 96.7 |
| [Qwen Image 2512 LoRA](https://spicyapi.ai/ru/models/qwen-image-2512-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | Edit, T2I | $0.03/image | 50.5 | ✅ 92.5 |
| [Z-Image Spicy Pro](https://spicyapi.ai/ru/models/z-image-spicy-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | 🌶️ Spicy | T2I | $0.019/image | 38 | ✅ 100 |
| [Z-Image Spicy](https://spicyapi.ai/ru/models/z-image-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | 🌶️ Spicy | T2I | $0.01235/image | 32 | ✅ 98.8 |
| [Z-Image](https://spicyapi.ai/ru/models/z-image?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | T2I | $0.01/image | 17 | ✅ 100 |
| [Z-Image Turbo LoRA](https://spicyapi.ai/ru/models/z-image-turbo-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | Edit, T2I | $0.012/image | 46.5 | ✅ 95 |
| [Seedream 4.0](https://spicyapi.ai/ru/models/seedream-4-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | Edit, T2I | $0.03/image | 74 | ◐ 74.7 |
| [Prefect Pony XL](https://spicyapi.ai/ru/models/prefect-pony-xl?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | T2I | $0.015/image | 30 | 🧪 36 |
| [FLUX.1 Dev LoRA](https://spicyapi.ai/ru/models/flux-1-dev-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ru) | Стандарт | T2I | $0.018/image | 32.5 | ◐ 75 |
<!-- /catalog:image -->

Вариант без кода: [генератор изображений без цензуры в SpicyAPI Studio](https://spicyapi.ai/ru/create/uncensored-ai-image-generator?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-studio-ru) запускает те же модели прямо в браузере — со стилями, соотношениями сторон и ценой, которую видно до генерации.

Сравнительный тест того, что разрешают разные модели изображений: [Less-restrictive image model evaluation](https://spicyapi.ai/ru/blog/less-restrictive-model-evaluation?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-eval-ru).

---

## NSFW-редакторы изображений и инструменты для лиц

| Инструмент | Что делает | Цена от |
|---|---|---|
| [Qwen Image 2.1 Edit](https://spicyapi.ai/ru/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ru) | Редактирование без цензуры по 1–10 референсным изображениям **вымышленного** или давшего согласие человека: одежда, поза, обстановка, освещение (уровень в каталоге `unrestricted`) | $0.036 / изображение |
| 🌶️ [Qwen Image Edit Spicy](https://spicyapi.ai/ru/models/qwen-image-spicy-edit?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ru) | Редактирование одного изображения по инструкции (Freedom 96, но низкая оценка возможностей — 14: одно входное изображение, без управления размером и соотношением сторон); сначала попробуйте Qwen Image 2.1 Edit | $0.038 / изображение |
| [Image Expander](https://spicyapi.ai/ru/models/image-expander-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ru) | Аутпейнтинг: расширение кадра по ширине или высоте | $0.024 / изображение |
| [Object Eraser](https://spicyapi.ai/ru/models/object-eraser-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ru) | Удаление объектов, логотипов и водяных знаков с ваших собственных изображений | $0.03 / изображение |
| [Image Upscaler](https://spicyapi.ai/ru/models/image-upscaler-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ru) / [Video Upscaler](https://spicyapi.ai/ru/models/video-upscaler-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ru) | Повышение резкости и увеличение готового результата | $0.012 / изображение, $0.006 / с |
| [Face Swap](https://spicyapi.ai/ru/models/face-swap-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ru), [Head Swap](https://spicyapi.ai/ru/models/head-swap-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ru), [Video Character Swap](https://spicyapi.ai/ru/models/character-swap-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ru) | Единый **вымышленный** персонаж во всех изображениях и роликах | $0.013 / изображение, видео от $0.064 / с |
| [Lip Sync](https://spicyapi.ai/ru/models/lip-sync-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ru), [Talking Avatar](https://spicyapi.ai/ru/models/talking-avatar-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ru), [Video Sound Effects](https://spicyapi.ai/ru/models/foley-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ru) | Голос и звук для ИИ-персонажей | от $0.0012 / с |

> ⚠️ Инструменты замены лица и головы **никогда** нельзя использовать, чтобы поместить реального человека в сексуальный контент без его документально подтверждённого согласия, а «раздевание» фотографии реального человека запрещено на любой добросовестной платформе. Известность человека или публичные фото — это не согласие. Используйте эти инструменты для созданных вами вымышленных персонажей или для себя.

Аналоги для самостоятельного запуска: [IP-Adapter](https://github.com/tencent-ailab/IP-Adapter), [InstantID](https://github.com/instantX-research/InstantID) и [PhotoMaker](https://github.com/TencentARC/PhotoMaker) для единообразия персонажа; [ControlNet](https://github.com/lllyasviel/ControlNet) для управления позой.

---

## LLM без цензуры и ролевые игры

Текстовые модели важны для NSFW-работы в трёх местах: художественная проза 18+ и интерактивные истории, приложения-компаньоны и ролевые игры, а также **написание более качественных промптов для изображений и видео** (LLM разворачивает идею в одну строку в подробный промпт с учётом работы камеры).

### Облачные (совместимые с OpenAI)

SpicyAPI предоставляет текстовые модели через эндпоинты, совместимые с OpenAI, Anthropic и Gemini, по адресу `https://api.spicyapi.ai`, так что существующие SDK работают после замены base URL. Среди моделей с уровнем `unrestricted` в каталоге на 2026-09-27:

| Модель | От (за 1K токенов) | Freedom | Для чего подходит |
|---|---|---|---|
| [Grok 4.7](https://spicyapi.ai/ru/models/grok-4-7?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-ru) | $0.0036 | ✅ 100 (откровенные 9/9) | Проза 18+, ролевые игры с характером |
| [Grok 4.6](https://spicyapi.ai/ru/models/grok-4-6?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-ru) / [Grok 4.5](https://spicyapi.ai/ru/models/grok-4-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-ru) | $0.0036 | ✅ 100 | Ведут себя так же, как 4.7 |
| [Grok 4.3](https://spicyapi.ai/ru/models/grok-4-3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-ru) | $0.0015 | ✅ 98.9 | Лучшее соотношение цены и качества: самая высокая оценка возможностей среди текстовых моделей (74) и медианная задержка ≈4 с |
| [DeepSeek V4.1 Flash](https://spicyapi.ai/ru/models/deepseek-v4-1-flash?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-ru) | $0.0012 | ✅ 90.4 | Дешёвое расширение промптов; иногда смягчает сцены 18+ (7/16) |
| [DeepSeek V4 Pro](https://spicyapi.ai/ru/models/deepseek-v4-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-ru) | $0.00396 | ◐ 88.6 | Длинная проза и рассуждения |

Протестированы, но не рекомендуются для текстов без цензуры: Kimi K3 (74.4), GLM 5.x (63–68), Gemini (64–89) и модели Claude (47–79) часто смягчают или отклоняют сцены 18+.

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

### Локально и на своём сервере

- [Ollama](https://github.com/ollama/ollama) и [LM Studio](https://lmstudio.ai) запускают модели с открытыми весами на вашем компьютере; ищите в их библиотеках файнтюны сообщества с пометками «abliterated» или «uncensored».
- [KoboldCpp](https://github.com/LostRuins/koboldcpp): однофайловый запускатель GGUF, созданный для сторителлинга.
- [text-generation-webui](https://github.com/oobabooga/textgen): полнофункциональный локальный чат-интерфейс с расширениями.
- [SillyTavern](https://github.com/SillyTavern/SillyTavern): стандартный фронтенд для ролевых игр. Подключается к локальному бэкенду или любому OpenAI-совместимому API, включая SpicyAPI.

---

## NSFW AI API

Для разработчиков приложений 18+ вопрос не только в том, «какую модель взять», но и в том, «какой провайдер даст вызывать её без блокировки запросов и будет честно выставлять счета».

| Что проверить | Почему это важно | SpicyAPI |
|---|---|---|
| Добавляет ли платформа свой фильтр? | Второй фильтр блокирует промпты, которые модель приняла бы | Фильтра платформы нет; политика провайдера модели по-прежнему действует |
| Единица оплаты | Кредиты и подписки скрывают реальную стоимость | Баланс в USD, оплата за изображение / секунду / токен, без подписки, баланс не сгорает |
| Неудачные генерации | Некоторые провайдеры берут деньги за отказы | За неудачные задачи деньги возвращаются автоматически |
| Способы оплаты | Бизнес 18+ часто лишается приёма карт | Visa, Mastercard, Amex, JCB, Apple Pay, Google Pay и криптовалюта (BTC, ETH, USDT) |
| Контроль бюджета | Утёкший ключ может опустошить баланс | Дневные / месячные / пожизненные лимиты на ключ, белые списки моделей, белые списки IP |
| Хранение данных | Входные данные 18+ чувствительны | Отдельные сроки хранения для промптов, загрузок и результатов; их можно сократить или удалить содержимое задачи |
| Интеграция | Не хочется писать отдельный клиент под каждую модель | Единый асинхронный API задач, SDK (TypeScript, Python, Go, PHP, Java), CLI, MCP-сервер, навык для агентов |

### Быстрый старт: NSFW-видео из изображения по HTTP

```bash
export SPICY_API_KEY="sk-spicy-..."   # создайте ключ на https://spicyapi.ai/ru/console

# 1) создать задачу
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

# 2) опрашивать, пока state не станет "succeeded", затем прочитать data.output.assets[0].url
curl -s "https://api.spicyapi.ai/api/v1/jobs/recordInfo?taskId=TASK_ID" \
  -H "Authorization: Bearer $SPICY_API_KEY"
```

Входные поля различаются от модели к модели. Перед отправкой запроса прочитайте актуальную схему через `GET /api/v1/models/{model}` (или на странице модели). Полный справочник: [docs.spicyapi.ai](https://docs.spicyapi.ai/docs?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=api-quickstart).

### Другие провайдеры

Политики часто меняются и по-разному применяются к разным моделям, поэтому прежде чем на что-то переходить, проверьте своими промптами. Всегда читайте актуальную политику допустимого использования провайдера.

- [Venice.ai](https://venice.ai): приватный чат и генерация изображений без цензуры, есть API.
- [fal.ai](https://fal.ai), [WaveSpeed](https://wavespeed.ai), [Replicate](https://replicate.com): большие каталоги облачных моделей; отношение к NSFW зависит от модели и настроек аккаунта.
- [RunPod](https://www.runpod.io), [Vast.ai](https://vast.ai): аренда GPU для самостоятельного запуска моделей с открытыми весами (см. [свой сервер](#модели-для-самостоятельного-запуска-и-открытые-веса)).

---

## Навыки для агентов и MCP-серверы

ИИ-агенты для программирования (Claude Code, Cursor, Codex, Windsurf, Cline, Gemini CLI, OpenClaw) теперь умеют генерировать медиа за вас через **навыки (skills)** и **MCP-серверы**. Попросите обычными словами («сделай 5-секундный ролик в стиле будуар из этого изображения»), и агент сам выберет модель, соберёт запрос и скачает результат.

| Ресурс | Тип | Установка |
|---|---|---|
| 🌶️ [nsfw-ai-skill](https://github.com/Spicy-API/nsfw-ai-skill/blob/main/README.ru.md) | Навык для агентов: NSFW-генерация изображений, видео, редактирование и текст, расширение промптов, оценка стоимости | `npx skills add Spicy-API/nsfw-ai-skill` |
| 🌶️ [MCP-сервер SpicyAPI](https://docs.spicyapi.ai/docs/mcp?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=skills-table) (`@spicyapi/mcp`) | MCP: список моделей, расчёт стоимости, создание / ожидание / повтор задач, загрузка файлов | `claude mcp add spicyapi -e SPICY_API_KEY=$SPICY_API_KEY -- npx --yes --package=@spicyapi/mcp spicyapi-mcp` |
| 🌶️ [Официальный навык SpicyAPI](https://github.com/Spicy-API/spicy-skill) | Навык для агентов, покрывающий все возможности SpicyAPI для разработчиков | `npx skills add Spicy-API/spicy-skill` |
| 🌶️ [CLI SpicyAPI](https://docs.spicyapi.ai/docs?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=skills-table) (`@spicyapi/cli`) | Командная строка: модели, расчёт стоимости, задачи, загрузки | `npx @spicyapi/cli --help` |
| [anthropics/skills](https://github.com/anthropics/skills) | Эталонные навыки и формат навыков | — |
| [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) | Каталог MCP-серверов | — |

---

## Модели для самостоятельного запуска и открытые веса

Бесплатный запуск, полный контроль и никаких фильтров платформы. Плата за это — железо, время на настройку и лицензии (прочитайте лицензию каждой модели перед коммерческим использованием).

### Видео

- [Wan 2.2](https://github.com/Wan-Video/Wan2.2) и [Wan 2.1](https://github.com/Wan-Video/Wan2.1): открытые видеомодели Alibaba (Apache-2.0). Огромная экосистема LoRA от сообщества; основа облачных версий Wan Spicy.
- [HunyuanVideo](https://github.com/Tencent-Hunyuan/HunyuanVideo): открытая видеомодель Tencent.
- [LTX-Video](https://github.com/Lightricks/LTX-Video) и [LTX-2](https://github.com/Lightricks/LTX-2): быстрые открытые видеомодели Lightricks.
- [CogVideoX](https://github.com/zai-org/CogVideo): открытая видеомодель Zhipu.
- [Mochi 1](https://github.com/genmoai/mochi): открытая видеомодель Genmo.
- [ComfyUI-WanVideoWrapper](https://github.com/kijai/ComfyUI-WanVideoWrapper): основной набор нод ComfyUI для Wan с поддержкой LoRA.

### Изображения

- [Qwen-Image](https://github.com/QwenLM/Qwen-Image): открытая генерация и редактирование изображений.
- [Z-Image](https://github.com/Tongyi-MAI/Z-Image): эффективная открытая модель изображений от Alibaba Tongyi.
- [FLUX.1](https://github.com/black-forest-labs/flux): проверяйте лицензию каждого варианта (dev — только некоммерческая).
- Чекпойнты SDXL / Pony Diffusion / Illustrious на [Civitai](https://civitai.com) и [Hugging Face](https://huggingface.co): крупнейший пул чекпойнтов сообщества, дообученных под NSFW.

**Примерные требования к железу:** моделям изображений хватает 8–12 ГБ VRAM; видеомоделям нужно 16–24 ГБ (или квантованные версии с более низким качеством). Если видеокарты нет, арендуйте GPU на RunPod или Vast.ai либо используйте облачный API.

---

## Локальные интерфейсы и инструменты для пайплайнов

- [ComfyUI](https://github.com/Comfy-Org/ComfyUI): нодовые пайплайны для изображений и видео; самый гибкий вариант.
- [Stable Diffusion WebUI (A1111)](https://github.com/AUTOMATIC1111/stable-diffusion-webui): классический интерфейс с огромной экосистемой расширений.
- [Forge](https://github.com/lllyasviel/stable-diffusion-webui-forge): более быстрый форк A1111, требующий меньше VRAM.
- [InvokeAI](https://github.com/invoke-ai/InvokeAI): продуманный интерфейс на основе холста.
- [Fooocus](https://github.com/lllyasviel/Fooocus): самый простой локальный интерфейс для SDXL.
- 🌶️ [SpicyAPI Studio](https://spicyapi.ai/ru/create?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=interfaces-ru): браузерная студия изображений и видео с шаблонами, [эффектами](https://spicyapi.ai/ru/create/effects?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=interfaces-ru) и [стилями](https://spicyapi.ai/ru/create/styles?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=interfaces-ru); видеокарта не нужна.

---

## LoRA, чекпойнты и обучение

**Где искать NSFW LoRA**

- [Civitai](https://civitai.com): крупнейшая библиотека; фильтруйте по базовой модели (Wan 2.2, SDXL, Pony, Flux) и включите контент 18+ в настройках аккаунта.
- [Hugging Face](https://huggingface.co): множество LoRA и полных файнтюнов; проверяйте лицензию в карточке каждой модели.
- [Tensor.Art](https://tensor.art): обмен моделями с онлайн-запуском.

**LoRA через API.** Wan 2.2 Spicy LoRA принимает `loras`, `high_noise_loras` и `low_noise_loras` (до трёх). High-noise LoRA формируют композицию и движение на ранних шагах денойзинга; low-noise LoRA — текстуру и детали на поздних. Каждая LoRA — объект с прямым `path` к файлу весов и `scale` (0–4, по умолчанию 1); меняйте по одной LoRA за раз. Точная схема — на [странице Wan 2.2 Spicy LoRA](https://spicyapi.ai/ru/models/wan-2-2-spicy-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=lora-ru).

**Обучение своих моделей**

- [kohya_ss](https://github.com/bmaltais/kohya_ss): стандартный тренер LoRA для SD / SDXL.
- [OneTrainer](https://github.com/Nerogar/OneTrainer): LoRA и полный файнтюнинг с графическим интерфейсом.
- [ai-toolkit](https://github.com/ostris/ai-toolkit): обучение для Flux, Wan и более новых моделей.

Обучайте только на изображениях, которые принадлежат вам или на которые у вас есть права, и только на взрослых.

---

## Апскейл, восстановление и постобработка

- [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN): 4× апскейл изображений и видео.
- [GFPGAN](https://github.com/TencentARC/GFPGAN) и [CodeFormer](https://github.com/sczhou/CodeFormer): восстановление лиц.
- [RIFE](https://github.com/hzwer/ECCV2022-RIFE): интерполяция кадров для более плавного замедленного движения.
- [FFmpeg](https://ffmpeg.org): нарезка, склейка, добавление звука (`ffmpeg -i clip.mp4 -i track.mp3 -c:v copy -shortest out.mp4`).
- [Topaz Video AI](https://www.topazlabs.com): коммерческий апскейлер видео.

---

## Промпты для контента 18+

Хороший NSFW-промпт читается как режиссёрский список кадров, а не как набор прилагательных. Модели лучше понимают английский, поэтому примеры ниже оставлены на английском.

```
[Subject: adult, age range, look] + [Wardrobe or state] + [Action: one clear motion]
+ [Setting] + [Lighting] + [Camera] + [Style / quality]
```

(Объект: взрослый человек, возраст, внешность + одежда или состояние + действие: одно чёткое движение + место + свет + камера + стиль / качество)

Пример («изображение в видео»):

```
A woman in her early 30s in a black silk slip dress sits on the edge of a hotel bed.
She slowly slides one strap off her shoulder and looks up at the camera.
Warm tungsten bedside lamp, soft shadows, city lights through the window.
Slow push-in from medium shot to close-up, shallow depth of field, 35mm film look.
```

Что даёт разницу:

1. **Одно основное действие на ролик.** Дыхание, движение волос, медленный поворот и движение ткани получаются надёжно; сложная хореография и взаимодействие двух людей ломаются первыми.
2. **Опишите камеру.** «Slow push-in», «static camera», «orbit left» работают лучше, чем «cinematic».
3. **Назовите свет.** Свечи, свет из окна, неоновый контровой свет, золотой час.
4. **Пусть внешний вид задаёт первый кадр.** В режиме «изображение в видео» не описывайте заново всё, что видно; описывайте то, что *меняется*.
5. **Делайте ролики короткими.** 5 секунд — оптимум для стабильной анатомии; если нужно дольше, продлите вторым вызовом.
6. **Всегда указывайте взрослый возраст** («in her 30s», «adult man in his 40s») и избегайте описаний, намекающих на юный возраст.

Готовые промпты: **[nsfw-ai-image-prompts](https://github.com/Spicy-API/nsfw-ai-image-prompts/blob/main/README.ru.md)** для изображений и редактирования, **[nsfw-ai-video-prompts](https://github.com/Spicy-API/nsfw-ai-video-prompts/blob/main/README.ru.md)** для видео.

---

## Как выбрать: схема решения

```
Есть видеокарта с 16+ ГБ VRAM и время на эксперименты?
├── Да → ComfyUI + открытые веса Wan 2.2 / Qwen-Image / Z-Image + LoRA с Civitai (бесплатно, максимум контроля)
└── Нет
    ├── Без кода, в браузере → SpicyAPI Studio (генерация изображений и видео без цензуры)
    └── Код или ИИ-агент
        ├── Лучшее универсальное видео → Wan 3.0 (T2V / I2V / Ref2V, Freedom 96, $0.45 за 5 с)
        ├── Без цензуры из статичного изображения → Seedance 2.5 Spicy, Wan 2.7 Spicy или Vidu Q3 Spicy
        ├── Свой стиль / персонаж → MiniMax H3 LoRA / Singularity LoRA (видео), Qwen Image 2.1 LoRA (изображения)
        ├── Много и недорого    → Wan 2.6 Flash или Seedance 1.5 Pro Spicy ($0.11–0.13 за 5 с)
        ├── Изображения         → Qwen Image 2.1 (Qwen Image 2.1 LoRA для своего стиля)
        ├── Текст / ролевые игры → Grok 4.7 или Grok 4.3
        └── Из Claude Code / Cursor → nsfw-ai-skill или MCP-сервер SpicyAPI
```

**По сценариям**

| Сценарий | Рекомендуемый стек |
|---|---|
| Сайт по подписке 18+ / контент для авторов | Qwen Image 2.1 для изображений → Wan 3.0 или Seedance 2.5 Spicy для роликов → Video Upscaler |
| Приложение-компаньон или ролевые игры с ИИ | Grok 4.7 или Grok 4.3 для чата → Qwen Image 2.1 для селфи → MiniMax H3 Spicy или Wan 3.0 для коротких движений |
| Хобби, много экспериментов | Wan 2.6 Flash или Seedance 1.5 Pro Spicy, итерации, удачные варианты перерендерить на Wan 3.0 |
| Аниме и хентай-стилистика | Qwen Image 2.1 LoRA с аниме-LoRA → Vidu Q3 Spicy (Freedom 96.7) или Wan 2.2 Spicy LoRA с той же LoRA |
| Проза 18+ и интерактивные истории | Grok 4.7 для текста, Qwen Image 2.1 для иллюстраций |

---

## Правила для всех инструментов

Эти правила обязательны, и никакая настройка их не отменяет:

- **Никаких несовершеннолетних — никогда.** Никакого сексуального контента с участием лиц младше 18 лет или тех, кто *выглядит* младше 18, в любом стиле, включая аниме, иллюстрации и оговорки про «вымышленный возраст».
- **Никаких реальных людей без документально подтверждённого согласия.** Никаких сексуальных дипфейков, никакой замены лица или головы реальных людей в сексуальном контенте, никакого «раздевания» фотографий. Публичные персоны — не исключение.
- **Никакой имперсонации, травли, вымогательства или фальшивых доказательств** с использованием чьей-либо внешности.
- **Соблюдайте законы своей страны и страны вашей аудитории.** В некоторых странах ограничены отдельные виды вымышленных материалов или контент для взрослых в целом.
- **Маркируйте контент, созданный ИИ**, там, где этого требуют платформы или закон, и храните подтверждения согласия любого реального человека, которого изображаете.

Полные правила SpicyAPI: [Политика в отношении контента](https://spicyapi.ai/ru/legal/content-policy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=rules-ru) и [Правила допустимого использования](https://spicyapi.ai/ru/legal/acceptable-use?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=rules-ru).

---

## Частые вопросы (FAQ)

### Какая нейросеть для генерации NSFW-видео лучшая в 2026 году?
По публичным тестам SpicyAPI лучший универсальный выбор — **Wan 3.0**: Spicy Index 76.5 (#2 из 37 видеомоделей), Freedom Score 96, все откровенные тестовые промпты выполнены (9/9), ролики до 30 с и $0.45 за 5 с в 720p. Для генерации видео из изображения без цензуры надёжнее всего Spicy-версии **Seedance 2.5 Spicy**, **Wan 2.7 Spicy** и **Vidu Q3 Spicy** (Freedom 96.7–100); для своего стиля — **MiniMax H3 LoRA**. У стандартной Seedance 2.0 самая высокая оценка возможностей, но она часто смягчает откровенные промпты (Freedom 70.4). Результаты: [рейтинги SpicyAPI](https://spicyapi.ai/ru/leaderboards?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=faq-ru).

### Какая нейросеть для генерации изображений без цензуры лучшая?
В облаке: **Qwen Image 2.1** (Spicy Index 73, Freedom 96.3, от $0.024 за изображение); **Qwen Image 2.1 LoRA** (#1 в индексе изображений, 80.5) и **MiniMax H3 Image LoRA** (Freedom 100) для своих стилей; **Seedream 5.0 Lite / Pro** как сильные альтернативы; **Z-Image Spicy** ($0.01235, Freedom 98.8) для самых дешёвых больших объёмов. На своём железе: чекпойнты сообщества SDXL, Pony и Illustrious в ComfyUI или Forge.

### Как сделать NSFW-видео из изображения?
Сгенерируйте или выберите первый кадр (вымышленный взрослый или вы сами), затем отправьте его в NSFW-модель «изображение в видео», например Wan 3.0 или Seedance 2.5 Spicy, с коротким промптом, описывающим движение и камеру. См. [быстрый старт по API](#быстрый-старт-nsfw-видео-из-изображения-по-http) или воспользуйтесь браузерным [инструментом «изображение в видео»](https://spicyapi.ai/ru/create/image-to-video?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=faq-ru).

### Есть ли бесплатная NSFW-нейросеть?
Локальный запуск моделей с открытыми весами (ComfyUI + Wan 2.2, Qwen-Image или Z-Image) бесплатен, если не считать железа и электричества. Облачные сервисы берут деньги, потому что GPU стоят дорого; в SpicyAPI нет подписки, оплата идёт за результат, а неудачные задачи возвращаются.

### Какой NSFW AI API для видео самый дешёвый?
В каталоге SpicyAPI (2026-09-27) самые дешёвые модели, прошедшие откровенные тесты, — **Wan 2.6 Flash** ($0.1125 за 5 с в 720p, Freedom 100) и **Seedance 1.5 Pro Spicy** ($0.13 за 5 с в 720p или $0.06 в 480p без звука; Freedom 96.7). Следом идут Wan 2.2 Spicy и LTX 2.3 Spicy — $0.19 за 5 с (720p).

### Законна ли NSFW-генерация с помощью ИИ?
Создание сексуального контента с **вымышленными взрослыми** законно в большинстве стран, но законы различаются, а некоторый контент незаконен везде: всё, что связано с несовершеннолетними, и сексуальный контент с реальными людьми, созданный без их согласия. Вы отвечаете за то, что создаёте и распространяете. Это не юридическая консультация.

### Чем модели «без цензуры» отличаются от Spicy-моделей?
«Без цензуры» (uncensored) обычно означает, что платформа или модель не отказывается выполнять промпты 18+. В SpicyAPI Spicy-версии — это конкретные версии моделей, настроенные на контент для взрослых; стандартные модели перечислены со своим уровнем политики, чтобы было видно, какие из них смягчают или фильтруют контент.

### Можно ли использовать NSFW AI в Claude Code, Cursor или других агентах?
Да. Установите [nsfw-ai-skill](https://github.com/Spicy-API/nsfw-ai-skill/blob/main/README.ru.md) (`npx skills add Spicy-API/nsfw-ai-skill`) или добавьте MCP-сервер SpicyAPI, задайте `SPICY_API_KEY` и обращайтесь к агенту на обычном языке.

---

## Связанные репозитории

- **[nsfw-ai-image-prompts](https://github.com/Spicy-API/nsfw-ai-image-prompts/blob/main/README.ru.md)**: 104 NSFW-промпта для генерации изображений и редактирования без цензуры с реальными примерами результатов.
- **[nsfw-ai-video-prompts](https://github.com/Spicy-API/nsfw-ai-video-prompts/blob/main/README.ru.md)**: более 100 NSFW-промптов для видео, промпты для референсных изображений, негативные промпты и советы по конкретным моделям.
- **[nsfw-ai-skill](https://github.com/Spicy-API/nsfw-ai-skill/blob/main/README.ru.md)**: навык для NSFW-генерации изображений, видео и текста из Claude Code, Cursor, Codex и других агентов.
- **[spicy-skill](https://github.com/Spicy-API/spicy-skill)** · **[spicy-mcp](https://github.com/Spicy-API/spicy-mcp)** · **[spicy-sdk](https://github.com/Spicy-API/spicy-sdk)**: официальные инструменты SpicyAPI для разработчиков.

## Как внести вклад

Дополнения приветствуются, в том числе конкуренты. Сначала прочитайте [CONTRIBUTING.md](CONTRIBUTING.md). Коротко: один ресурс на pull request, нейтральное описание в одну строку, рабочая ссылка и никаких ресурсов, основная цель которых — изображения без согласия, контент с участием несовершеннолетних или обход законов.

## Лицензия

[CC0 1.0](LICENSE). В той мере, в какой это допускает закон, участники отказались от всех авторских прав на этот список.

<p align="center"><sub>Пригодился список? Поставьте ⭐ Star, чтобы другие авторы тоже могли его найти.</sub></p>
