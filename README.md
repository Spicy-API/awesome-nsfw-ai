<!--
  Keywords: awesome nsfw ai, nsfw ai generator, uncensored ai image generator, uncensored ai video generator,
  nsfw ai video generator, nsfw image to video, nsfw ai image editor, uncensored ai models, uncensored llm,
  nsfw ai api, best nsfw ai image generator 2026, wan 2.2 spicy, seedance spicy, nsfw ai skill, nsfw mcp
-->

<p align="center"><b>English</b> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.fr.md">Français</a> · <a href="README.es.md">Español</a> · <a href="README.ru.md">Русский</a></p>

<h1 align="center">Awesome NSFW AI</h1>

<p align="center">
  <b>A curated 2026 list of uncensored AI image generators, NSFW AI video generators, image-to-video models, image editors, uncensored LLMs, APIs, agent skills, MCP servers and tools, for adult creators and developers.</b>
</p>

<p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
  <img src="https://img.shields.io/badge/updated-2026--09--27-blue" alt="Last updated 2026-09-27">
  <img src="https://img.shields.io/badge/18%2B-adults%20only-red" alt="18+ adults only">
  <img src="https://img.shields.io/badge/license-CC0--1.0-lightgrey" alt="CC0 license">
</p>

<p align="center">
  <img src="assets/wolf-turn-and-look-back.gif" width="24%" alt="Wan 2.2 Spicy image-to-video output">
  <img src="assets/velvet-spiral-turn.gif" width="24%" alt="Seedance 2.0 Spicy image-to-video output">
  <img src="assets/silk-draught-pull.gif" width="24%" alt="Wan 2.7 Spicy image-to-video output">
  <img src="assets/hotel-window-turn.gif" width="24%" alt="Seedance 2.5 Spicy image-to-video output">
  <br><sub>Real outputs from Wan 2.2 Spicy, Seedance 2.0 Spicy, Wan 2.7 Spicy and Seedance 2.5 Spicy. More, with exact prompts, in <a href="https://github.com/Spicy-API/nsfw-ai-video-prompts#showcase-real-outputs-and-their-prompts">nsfw-ai-video-prompts</a>.</sub>
</p>

<p align="center">
  <a href="#uncensored-ai-video-generators">Video</a> ·
  <a href="#uncensored-ai-image-generators">Image</a> ·
  <a href="#nsfw-ai-image-editors-and-face-tools">Editing</a> ·
  <a href="#uncensored-llms-and-roleplay">LLMs</a> ·
  <a href="#nsfw-ai-apis">APIs</a> ·
  <a href="#agent-skills-and-mcp-servers">Skills &amp; MCP</a> ·
  <a href="#self-hosted-and-open-weight-models">Self-hosted</a> ·
  <a href="#faq">FAQ</a>
</p>

> **18+ only.** This list covers tools that can produce adult content. Every resource here must be used with fictional adults or real adults who gave documented consent, and within the law where you and your audience live. See [Rules that apply to every tool](#rules-that-apply-to-every-tool).

> **Disclosure:** this list is maintained by the team behind [SpicyAPI](https://spicyapi.ai/?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=disclosure), a pay-per-use API for uncensored image, video and text models. SpicyAPI entries are marked 🌶️. Third-party tools are listed because they are useful, not because they pay to be here. Pull requests adding competitors are welcome.

---

## TL;DR: quick picks

| I want to… | Start here | Why (SpicyAPI leaderboard, 2026-09-27) |
|---|---|---|
| The best all-round NSFW video model | [Wan 3.0](https://spicyapi.ai/models/wan-3-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) | Spicy Index 76.5 (#2 of 37), Freedom 96; every explicit test prompt rendered (9/9); T2V, I2V and reference-to-video up to 30 s; $0.45 per 5 s at 720p |
| NSFW video with my own style or character | [MiniMax H3 LoRA](https://spicyapi.ai/models/minimax-h3-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) or [MiniMax H3 Singularity LoRA](https://spicyapi.ai/models/minimax-h3-singularity-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) | Spicy Index 75.2 / 72.8, Freedom 98.3 / 100 |
| Uncensored image-to-video with a Spicy edition | 🌶️ [Seedance 2.5 Spicy](https://spicyapi.ai/models/seedance-2-5-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr), 🌶️ [Wan 2.7 Spicy](https://spicyapi.ai/models/wan-2-7-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) or 🌶️ [Vidu Q3 Spicy](https://spicyapi.ai/models/vidu-q3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) | Freedom 96.7–100, every explicit test prompt rendered (3/3) |
| Cheap NSFW video in volume | [Wan 2.6 Flash](https://spicyapi.ai/models/wan-2-6-flash?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) or 🌶️ [Seedance 1.5 Pro Spicy](https://spicyapi.ai/models/seedance-1-5-pro-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) | Freedom 100 / 96.7 at $0.11–0.13 per 5 s (720p) |
| An uncensored text-to-image model | [Qwen Image 2.1](https://spicyapi.ai/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) | Spicy Index 73, Freedom 96.3, from $0.024 per image; long prompts, 15 aspect ratios |
| Images in my own style (incl. anime) | [Qwen Image 2.1 LoRA](https://spicyapi.ai/models/qwen-image-2-1-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) or [MiniMax H3 Image LoRA](https://spicyapi.ai/models/minimax-h3-image-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) | #1 and #2 on the image Spicy Index (80.5 / 74.5), Freedom 92 / 100 |
| An uncensored AI image editor | [Qwen Image 2.1 Edit](https://spicyapi.ai/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) | Same family as above; 1–10 reference images + one instruction, no mask |
| Uncensored chat, roleplay or prompt writing | [Grok 4.7](https://spicyapi.ai/models/grok-4-7?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) or [Grok 4.3](https://spicyapi.ai/models/grok-4-3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) | Freedom 100 / 98.9 on the text board; Grok 4.3 is the fastest (≈4 s median) |
| Run everything locally, free | [ComfyUI](https://github.com/Comfy-Org/ComfyUI) + [Wan 2.2](https://github.com/Wan-Video/Wan2.2) open weights | Needs a strong GPU (24 GB VRAM is comfortable) |
| Let Claude Code / Cursor generate for me | [nsfw-ai-skill](https://github.com/Spicy-API/nsfw-ai-skill) or the official [SpicyAPI MCP server](https://docs.spicyapi.ai/docs/mcp?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) | Natural-language generation from your agent |
| Copy-paste image prompts | [nsfw-ai-image-prompts](https://github.com/Spicy-API/nsfw-ai-image-prompts) | 104 image and editing prompts for Qwen Image 2.1, Seedream 5.0 and more, plus 72 real output cases |
| Copy-paste video prompts | [nsfw-ai-video-prompts](https://github.com/Spicy-API/nsfw-ai-video-prompts) | 116 ready-to-use video prompts plus 128 real output cases, each with its prompt |

Scores come from the public [SpicyAPI leaderboards](https://spicyapi.ai/leaderboards?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) (methodology v2.1, tests run 2026-09-14 to 2026-09-27; see [how models are ranked](#how-models-are-ranked-here)). Prices are the listed catalog tier; higher resolutions, audio and longer clips cost more.

---

## Contents

- [TL;DR: quick picks](#tldr-quick-picks)
- [What "NSFW AI" and "uncensored AI" actually mean](#what-nsfw-ai-and-uncensored-ai-actually-mean)
- [Uncensored AI video generators](#uncensored-ai-video-generators)
  - [All uncensored video models, most popular first](#all-uncensored-video-models-most-popular-first)
  - [What a 5-second NSFW clip costs](#what-a-5-second-nsfw-clip-costs)
- [Uncensored AI image generators](#uncensored-ai-image-generators)
- [NSFW AI image editors and face tools](#nsfw-ai-image-editors-and-face-tools)
- [Uncensored LLMs and roleplay](#uncensored-llms-and-roleplay)
- [NSFW AI APIs](#nsfw-ai-apis)
- [Agent skills and MCP servers](#agent-skills-and-mcp-servers)
- [Self-hosted and open-weight models](#self-hosted-and-open-weight-models)
- [Local interfaces and workflow tools](#local-interfaces-and-workflow-tools)
- [LoRAs, checkpoints and training](#loras-checkpoints-and-training)
- [Upscaling, restoration and post-production](#upscaling-restoration-and-post-production)
- [Prompt engineering for mature content](#prompt-engineering-for-mature-content)
- [How to choose: a decision guide](#how-to-choose-a-decision-guide)
- [Rules that apply to every tool](#rules-that-apply-to-every-tool)
- [FAQ](#faq)
- [Related repositories](#related-repositories)
- [Contributing](#contributing)

---

## What "NSFW AI" and "uncensored AI" actually mean

**NSFW AI** is any generative model or tool that can produce nudity or sexual content for adults. **Uncensored AI** is a looser term for models that do not refuse mature prompts or blur their output.

Three things decide whether an NSFW request works, and people mix them up constantly:

1. **The model.** Some models were trained or fine-tuned to allow adult output. Others were trained to refuse it, and no platform setting changes that.
2. **The platform's own filter.** Many hosted services add a moderation layer on top of the model (prompt blocklists, output classifiers, blurring). A permissive model behind a strict filter still gets blocked.
3. **Your local laws and the platform's terms.** "The model can do it" is not "you may do it". Some content is illegal everywhere (see [the rules](#rules-that-apply-to-every-tool)).

A practical way to read the lists below:

| Label | What it means |
|---|---|
| **Spicy / NSFW edition** | A version of a model tuned or configured for adult output. On SpicyAPI these carry "Spicy" in the name. |
| **Mature-capable** | A general model that often allows adult content but may soften or refuse some requests. |
| **Filtered** | The model or provider applies its own content filter. Fine for SFW work, unreliable for NSFW. |

On SpicyAPI, every model in the public catalog carries a policy tier (`unrestricted`, `softened`, `borderline`, `filtered`), and the [leaderboards](https://spicyapi.ai/leaderboards?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=definitions) publish a **Freedom Score** from repeated test prompts. The platform does not add its own filter on top of the model; filtering, where it exists, comes from the model provider.


### How models are ranked here

Recommendations in this list follow SpicyAPI's published test results, not marketing copy:

- **Freedom Score (0–100)**: how reliably a model renders what an adult prompt asks for across five levels: L1 suggestive, L2 partial nudity, L3 nudity, L4 explicit, L5 extreme. Each level scores 20 points × pass rate × confidence, so softened or swapped outputs lose points. ✅ 90+ · ◐ 70–89 · ⚠️ under 70 · 🧪 fewer than 15 test runs so far, so a low number reflects coverage gaps rather than refusals.
- **Spicy Index (0–100)**: currently *preliminary*: a capability score from the public spec (native resolution, longest clip, audio, inputs and so on). Arena quality votes are still pending, so it does not measure visual quality yet.
- **Engineering route checks**: before a model is listed, the team generates explicit test cases on every upstream route and inspects the downloaded output frame by frame (a "success" status is not enough, because some providers silently swap in a safe image). Models that only render explicit content on some routes are not recommended here.

Full per-model reports, with run counts per level: [SpicyAPI leaderboards](https://spicyapi.ai/leaderboards?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=method). Test outputs at L4/L5 are never published.

---

## Uncensored AI video generators

Image-to-video (I2V) is the most reliable way to make an NSFW AI video: you control the look with the first frame and the model only has to animate it. Text-to-video (T2V) and reference-to-video (Ref2V, "put the character from these images into a new scene") come from the standard models below.

### All uncensored video models, most popular first

Ordered like the SpicyAPI catalog: most popular first, and within a family the newest version first. 🌶️ **Spicy** editions are tuned for adult output. **Standard** models listed here carry the catalog tier `unrestricted` (the provider applies no content filter), so they also take mature prompts. Prices are the cheapest tier. Catalog read on <!-- catalog:date -->
2026-09-27
<!-- /catalog:date -->

<!-- catalog:video -->
| Model | Type | Tasks | Duration | From | Spicy Index | Freedom |
|---|---|---|---|---|---|---|
| [Seedance 2.5 Spicy](https://spicyapi.ai/models/seedance-2-5-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | I2V | 4–30 s | $0.216/s | 56.5 | ✅ 96.7 |
| [Seedance 2.5](https://spicyapi.ai/models/seedance-2-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, Ref2V, T2V | 4–30 s | $0.1234/s | 69.5 | ◐ 80.9 |
| [Seedance 2.0 Spicy](https://spicyapi.ai/models/seedance-2-0-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | I2V | 4–15 s | $0.114/s | 61.5 | ✅ 93.3 |
| [Seedance 2.0](https://spicyapi.ai/models/seedance-2-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, Ref2V, T2V | 4–15 s | $0.07/s | 81.5 | ◐ 70.4 |
| [Wan 3.0 Prime](https://spicyapi.ai/models/wan-3-0-prime?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, Ref2V, T2V | 2–30 s | $0.0612/s | 76.5 | ◐ 78 |
| [Wan 3.0](https://spicyapi.ai/models/wan-3-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, Ref2V, T2V | 2–30 s | $0.045/s | 76.5 | ✅ 96 |
| [MiniMax H3 Spicy](https://spicyapi.ai/models/minimax-h3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | I2V | 3–15 s | $0.038/s | 29.5 | ✅ 97.5 |
| [MiniMax H3](https://spicyapi.ai/models/minimax-h3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, Ref2V, T2V | 4–15 s | $0.025/s | 72.5 | 🧪 33.3 |
| [MiniMax H3 Singularity LoRA](https://spicyapi.ai/models/minimax-h3-singularity-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, Ref2V | 3–15 s | $0.06/s | 72.8 | ✅ 100 |
| [LTX 2.5](https://spicyapi.ai/models/ltx-2-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, T2V | 5–20 s | $0.09/s | 66 | ◐ 80.3 |
| [Wan 3.0 Pro Prime](https://spicyapi.ai/models/wan-3-0-pro-prime?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, Ref2V, T2V | 2–30 s | $0.234/s | 76.5 | ◐ 82 |
| [Wan 3.0 Pro](https://spicyapi.ai/models/wan-3-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, Ref2V, T2V | 2–30 s | $0.144/s | 76.5 | ◐ 82 |
| [MiniMax H3 LoRA](https://spicyapi.ai/models/minimax-h3-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, Ref2V, T2V | 3–15 s | $0.05/s | 75.2 | ✅ 98.3 |
| [HappyHorse 1.1](https://spicyapi.ai/models/happyhorse-1-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, Ref2V, T2V | 3–15 s | $0.14/s | 62.5 | ⚠️ 65.1 |
| [Seedance 2.0 Mini Spicy](https://spicyapi.ai/models/seedance-2-0-mini-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | I2V | 4–15 s | $0.0387/s | 44.5 | ✅ 93.3 |
| [Seedance 2.0 Mini](https://spicyapi.ai/models/seedance-2-0-mini?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, Ref2V, T2V | 4–15 s | $0.01097/s | 64.5 | ⚠️ 64.9 |
| [Wan 2.7 Spicy](https://spicyapi.ai/models/wan-2-7-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | I2V | 2–15 s | $0.1235/s | 46.5 | ✅ 100 |
| [LTX 2.3 Spicy](https://spicyapi.ai/models/ltx-2-3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | I2V | 3–20 s | $0.019/s | 33.5 | ◐ 89.2 |
| [LTX 2.3 Spicy LoRA](https://spicyapi.ai/models/ltx-2-3-spicy-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | I2V | 3–20 s | $0.0285/s | 34.8 | ◐ 83.8 |
| [Seedance 2.0 Fast Spicy](https://spicyapi.ai/models/seedance-2-0-fast-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | I2V | 4–15 s | $0.081/s | 44.5 | ✅ 90 |
| [Seedance 2.0 Fast](https://spicyapi.ai/models/seedance-2-0-fast?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, Ref2V, T2V | 4–15 s | $0.02254/s | 64.5 | ⚠️ 68.2 |
| [Vidu Q3 Turbo](https://spicyapi.ai/models/vidu-q3-turbo?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V | 1–16 s | $0.042/s | 39.5 | ✅ 93.3 |
| [Vidu Q3 Spicy](https://spicyapi.ai/models/vidu-q3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | I2V | 1–16 s | $0.0665/s | 46.5 | ✅ 96.7 |
| [Vidu Q3](https://spicyapi.ai/models/vidu-q3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V | 1–16 s | $0.07/s | 46.5 | ✅ 93.3 |
| [Vidu Q3 Pro](https://spicyapi.ai/models/vidu-q3-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V | 1–16 s | $0.054/s | 36.5 | ✅ 93.3 |
| [Seedance 1.5 Pro Spicy](https://spicyapi.ai/models/seedance-1-5-pro-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | I2V | 4–12 s | $0.012/s | 48.5 | ✅ 96.7 |
| [Seedance 1.5 Pro](https://spicyapi.ai/models/seedance-1-5-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, T2V | 4–12 s | $0.0112/s | 46 | ✅ 90 |
| [Wan 2.6 Flash](https://spicyapi.ai/models/wan-2-6-flash?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V | 5, 10, 15 s | $0.0225/s | 31.5 | ✅ 100 |
| [Wan 2.6 Spicy](https://spicyapi.ai/models/wan-2-6-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | I2V | 5, 10, 15 s | $0.095/s | 46.5 | ✅ 96.7 |
| [Wan 2.6](https://spicyapi.ai/models/wan-2-6?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, Ref2V, T2V | 5, 10, 15 s | $0.065/s | 58.5 | 🧪 8.7 |
| [Wan 2.5](https://spicyapi.ai/models/wan-2-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, T2V | 5, 10 s | $0.045/s | 46 | ✅ 99 |
| [Wan 2.2 Spicy](https://spicyapi.ai/models/wan-2-2-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | I2V | 5, 8 s | $0.019/s | 23.5 | ✅ 91.2 |
| [Wan 2.2 Spicy LoRA](https://spicyapi.ai/models/wan-2-2-spicy-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | I2V, Extend | 5, 8 s | $0.024/s | 25 | ◐ 74.8 |
| [Wan 2.2 LoRA](https://spicyapi.ai/models/wan-2-2-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V | 5, 8 s | $0.024/s | 22.5 | ◐ 88.8 |
<!-- /catalog:video -->

Tested picks (explicit = L4 test prompts that rendered as asked):

- **Best all-round: Wan 3.0.** Spicy Index 76.5, Freedom 96, explicit 9/9, $0.45 per 5 s at 720p, clips up to 30 s. Wan 3.0 Pro and Pro Prime render explicit prompts too (9/9) but score lower on Freedom (82), mostly on the extreme level (L5).
- **Custom styles and characters: MiniMax H3 LoRA** (Index 75.2, Freedom 98.3, explicit 11/13) and **MiniMax H3 Singularity LoRA** (Index 72.8, Freedom 100, explicit 8/8).
- **Seedance for adult work: Seedance 2.5** (Index 69.5, Freedom 80.9, explicit 8/9) for text-to-video and reference-to-video; for uncensored image-to-video use the 🌶️ **Seedance 2.5 Spicy** edition (Freedom 96.7, explicit 3/3).
- **Most permissive: Wan 2.7 Spicy, Wan 2.6 Flash and MiniMax H3 Singularity LoRA** (Freedom 100), **Wan 2.5** (99).
- **Budget: Wan 2.6 Flash** ($0.11 per 5 s, Freedom 100), 🌶️ **Seedance 1.5 Pro Spicy** ($0.13, Freedom 96.7) and **MiniMax H3** ($0.185 per 5 s at 768p; all 14 of its test clips came back as asked; its Freedom number is low only because some levels are not covered yet). 🌶️ Wan 2.2 Spicy and LTX 2.3 Spicy cost $0.19 but soften the top level more often.
- **Soften explicit prompts in testing**, so use the Spicy edition of the family instead: standard Seedance 2.0 (Freedom 70.4, explicit 1/9; it has the highest capability score of any video model, so it is excellent for suggestive work), Seedance 2.0 Fast / Mini (68.2 / 64.9), HappyHorse 1.1 (65.1) and Wan 2.2 (43.1).
- **Not enough test data yet:** Wan 2.6 standard (5 runs); the 🌶️ Wan 2.6 Spicy edition is fully tested (Freedom 96.7).
- **Things the reviews warn about:** Wan 3.0 sometimes goes further than the prompt (watch the last seconds), takes about 3.5 minutes per job, and its reference-to-video refuses photos of real faces. Seedance 2.5 stays closest to a long script; Seedance 2.5 Spicy goes further on the hardest levels.

Some video endpoints bill in whole blocks (for example a 6-second clip on a 5-second block is billed as 10 s); the model page states the block length, and the quoted amount is the most you can be charged. Browse and filter everything on [SpicyAPI › Uncensored AI models](https://spicyapi.ai/explore/uncensored-ai-models?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=video-table).

### What a 5-second NSFW clip costs

Cost of one 5-second 720p clip (768p for MiniMax), from the leaderboard price axis on 2026-09-27, next to the Freedom Score. Lower resolutions are cheaper.

| Model | 1 clip (5 s) | 100 clips | 1,000 clips | Freedom |
|---|---|---|---|---|
| Wan 2.6 Flash | $0.11 | $11.25 | $112.50 | ✅ 100 |
| 🌶️ Seedance 1.5 Pro Spicy | $0.13 | $13.00 | $130 | ✅ 96.7 |
| MiniMax H3 | $0.185 | $18.50 | $185 | 🧪 33.3 (14/14 clips as asked) |
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

480p is roughly half price on most of these (for example Wan 2.2 Spicy $0.095 and Seedance 1.5 Pro Spicy $0.06 per 5 s). Failed tasks are refunded automatically.

---

## Uncensored AI image generators

**Recommended: [Qwen Image 2.1](https://spicyapi.ai/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick)**: Spicy Index 73, Freedom 96.3 (explicit 5/6), from $0.024 per image at 1k. It follows long briefs (up to 5,000 characters), renders 15 aspect ratios at 1k, 1.5k or 2k, and edits from 1–10 reference images in the same family.

Other tested picks:

- **Your own style or character (including anime): [Qwen Image 2.1 LoRA](https://spicyapi.ai/models/qwen-image-2-1-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick)**: #1 on the image Spicy Index (80.5), Freedom 92, up to three LoRAs. **[MiniMax H3 Image LoRA](https://spicyapi.ai/models/minimax-h3-image-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick)**: Index 74.5, Freedom 100 (explicit 8/8), matches MiniMax H3 video.
- **Seedream: [Seedream 5.0 Lite](https://spicyapi.ai/models/seedream-5-0-lite?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick) / [Seedream 5.0 Pro](https://spicyapi.ai/models/seedream-5-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick)**: Index 73, Freedom 96 / 94.3. Seedream 4.0 scores well on capability (74) but lower on Freedom (74.7).
- **Text in the image (posters, covers): [Qwen Image 3.0 Pro](https://spicyapi.ai/models/qwen-image-3-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick)**: Freedom 98, explicit 6/6.
- **Cheapest: 🌶️ [Z-Image Spicy](https://spicyapi.ai/models/z-image-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick)** ($0.01235, Freedom 98.8) and [Z-Image Turbo LoRA](https://spicyapi.ai/models/z-image-turbo-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick) ($0.012, Freedom 95). Lower capability scores (32 / 46.5), so use them for volume and drafts.
- **Not recommended for NSFW:** Krea 2 (Freedom 10), Wan 2.7 / Wan 2.7 Pro text-to-image (nudity and explicit levels mostly softened), FLUX.1 Dev LoRA (75, explicit 0/6). Prefect Pony XL has only 3 test runs so far (Freedom 36); treat it as a tag-prompt anime option, not a tested NSFW pick.

All uncensored image models, in catalog order:

<!-- catalog:image -->
| Model | Type | Tasks | From | Spicy Index | Freedom |
|---|---|---|---|---|---|
| [Qwen Image 2.1](https://spicyapi.ai/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | Edit, T2I | $0.024/image | 73 | ✅ 96.3 |
| [Qwen Image 2.1 LoRA](https://spicyapi.ai/models/qwen-image-2-1-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | Edit, T2I | $0.03/image | 80.5 | ✅ 92 |
| [MiniMax H3 Image LoRA](https://spicyapi.ai/models/minimax-h3-image-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | Edit, T2I | $0.042/image | 74.5 | ✅ 100 |
| [Qwen Image 3.0 Pro](https://spicyapi.ai/models/qwen-image-3-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | Edit, T2I | $0.04/image | 56 | ✅ 98 |
| [Qwen Image 3.0](https://spicyapi.ai/models/qwen-image-3-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | Edit, T2I | $0.03/image | 56 | ✅ 96 |
| [Seedream 5.0 Pro](https://spicyapi.ai/models/seedream-5-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | Edit, T2I | $0.036/image | 73 | ✅ 94.3 |
| [Qwen Image Edit Spicy](https://spicyapi.ai/models/qwen-image-spicy-edit?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | Edit | $0.038/image | 14 | ✅ 96 |
| [Seedream 5.0 Lite](https://spicyapi.ai/models/seedream-5-0-lite?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | Edit, T2I | $0.0345/image | 73 | ✅ 96 |
| [Qwen Image 2](https://spicyapi.ai/models/alibaba-qwen-image-2?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | Edit, T2I | $0.035/image | 34 | ✅ 96.7 |
| [Qwen Image 2512 LoRA](https://spicyapi.ai/models/qwen-image-2512-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | Edit, T2I | $0.03/image | 50.5 | ✅ 92.5 |
| [Z-Image Spicy Pro](https://spicyapi.ai/models/z-image-spicy-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | T2I | $0.019/image | 38 | ✅ 100 |
| [Z-Image Spicy](https://spicyapi.ai/models/z-image-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | T2I | $0.01235/image | 32 | ✅ 98.8 |
| [Z-Image](https://spicyapi.ai/models/z-image?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | T2I | $0.01/image | 17 | ✅ 100 |
| [Z-Image Turbo LoRA](https://spicyapi.ai/models/z-image-turbo-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | Edit, T2I | $0.012/image | 46.5 | ✅ 95 |
| [Seedream 4.0](https://spicyapi.ai/models/seedream-4-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | Edit, T2I | $0.03/image | 74 | ◐ 74.7 |
| [Prefect Pony XL](https://spicyapi.ai/models/prefect-pony-xl?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | T2I | $0.015/image | 30 | 🧪 36 |
| [FLUX.1 Dev LoRA](https://spicyapi.ai/models/flux-1-dev-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | T2I | $0.018/image | 32.5 | ◐ 75 |
<!-- /catalog:image -->

No-code option: the [uncensored AI image generator in SpicyAPI Studio](https://spicyapi.ai/create/uncensored-ai-image-generator?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-studio) runs the same models in the browser with styles, aspect ratios and a price shown before you generate.

For a head-to-head test of which image models allow what, read [Less-restrictive image model evaluation](https://spicyapi.ai/blog/less-restrictive-model-evaluation?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-eval).

---

## NSFW AI image editors and face tools

| Tool | What it does | From |
|---|---|---|
| [Qwen Image 2.1 Edit](https://spicyapi.ai/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table) | Uncensored editing from 1–10 reference images of a **fictional** or consenting subject: outfit, pose, setting, relighting (catalog tier `unrestricted`) | $0.036 / image |
| 🌶️ [Qwen Image Edit Spicy](https://spicyapi.ai/models/qwen-image-spicy-edit?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table) | Single-image instruction edit (Freedom 96, but a low capability score of 14: one input image, no size or aspect control); use Qwen Image 2.1 Edit first | $0.038 / image |
| [Image Expander](https://spicyapi.ai/models/image-expander-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table) | Outpaint to a wider or taller frame | $0.024 / image |
| [Object Eraser](https://spicyapi.ai/models/object-eraser-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table) | Remove objects, logos, watermarks you own | $0.03 / image |
| [Image Upscaler](https://spicyapi.ai/models/image-upscaler-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table) / [Video Upscaler](https://spicyapi.ai/models/video-upscaler-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table) | Sharpen and enlarge finished output | $0.012 / image, $0.006 / s |
| [Face Swap](https://spicyapi.ai/models/face-swap-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table), [Head Swap](https://spicyapi.ai/models/head-swap-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table), [Video Character Swap](https://spicyapi.ai/models/character-swap-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table) | Keep one consistent **fictional** character across images and clips | $0.013 / image, video from $0.064 / s |
| [Lip Sync](https://spicyapi.ai/models/lip-sync-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table), [Talking Avatar](https://spicyapi.ai/models/talking-avatar-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table), [Video Sound Effects](https://spicyapi.ai/models/foley-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table) | Voice and audio for AI characters | from $0.0012 / s |

> ⚠️ Face and head swap tools must **never** be used to put a real person into sexual content without their documented consent, and "undressing" or "nudifying" a photo of a real person is prohibited on every reputable platform. Being a celebrity or having public photos is not consent. Use these tools for fictional characters you created, or for yourself.

Self-hosted equivalents: [IP-Adapter](https://github.com/tencent-ailab/IP-Adapter), [InstantID](https://github.com/instantX-research/InstantID) and [PhotoMaker](https://github.com/TencentARC/PhotoMaker) for character consistency; [ControlNet](https://github.com/lllyasviel/ControlNet) for pose control.

---

## Uncensored LLMs and roleplay

Text models matter for NSFW work in three places: adult fiction and interactive stories, companion and roleplay apps, and **writing better image and video prompts** (an LLM expands a one-line idea into a detailed, camera-aware prompt).

### Hosted (OpenAI-compatible)

SpicyAPI serves text models through OpenAI, Anthropic and Gemini-compatible endpoints at `https://api.spicyapi.ai`, so existing SDKs work by changing the base URL. Models whose catalog tier is `unrestricted` on 2026-09-27 include:

| Model | From (per 1K tokens) | Freedom | Good for |
|---|---|---|---|
| [Grok 4.7](https://spicyapi.ai/models/grok-4-7?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table) | $0.0036 | ✅ 100 (explicit 9/9) | Adult fiction, roleplay with personality |
| [Grok 4.6](https://spicyapi.ai/models/grok-4-6?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table) / [Grok 4.5](https://spicyapi.ai/models/grok-4-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table) | $0.0036 | ✅ 100 | Same behaviour as 4.7 |
| [Grok 4.3](https://spicyapi.ai/models/grok-4-3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table) | $0.0015 | ✅ 98.9 | Best value: highest text capability score (74) and ≈4 s median latency |
| [DeepSeek V4.1 Flash](https://spicyapi.ai/models/deepseek-v4-1-flash?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table) | $0.0012 | ✅ 90.4 | Cheap prompt expansion; sometimes tones down adult scenes (7/16) |
| [DeepSeek V4 Pro](https://spicyapi.ai/models/deepseek-v4-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table) | $0.00396 | ◐ 88.6 | Long-form fiction and reasoning |

Tested but not recommended for uncensored writing: Kimi K3 (74.4), GLM 5.x (63–68), Gemini (64–89) and Claude models (47–79) often soften or refuse adult scenes.

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

### Local and self-hosted

- [Ollama](https://github.com/ollama/ollama) and [LM Studio](https://lmstudio.ai) run open-weight models on your own machine; search their libraries for "abliterated" or "uncensored" community fine-tunes.
- [KoboldCpp](https://github.com/LostRuins/koboldcpp): single-file GGUF runner built for storytelling.
- [text-generation-webui](https://github.com/oobabooga/textgen): full-featured local chat UI with extensions.
- [SillyTavern](https://github.com/SillyTavern/SillyTavern): the standard roleplay front end. Connect it to a local backend or any OpenAI-compatible API, including SpicyAPI.

---

## NSFW AI APIs

For developers building adult apps, the question is not only "which model", but "which provider lets me call it without my requests being blocked, and bills me fairly".

| What to check | Why it matters | SpicyAPI |
|---|---|---|
| Does the platform add its own filter? | A second filter blocks prompts the model would accept | No platform filter; the model provider's policy still applies |
| Billing unit | Credits and subscriptions hide the real cost | USD balance, per image / per second / per token, no subscription, balance never expires |
| Failed generations | Some providers charge for refusals | Failed tasks are refunded automatically |
| Payment methods | Adult businesses often lose card processing | Visa, Mastercard, Amex, JCB, Apple Pay, Google Pay, and crypto (BTC, ETH, USDT) |
| Budget control | A leaked key can drain a balance | Per-key daily / monthly / lifetime caps, model allowlists, IP allowlists |
| Data retention | Adult inputs are sensitive | Separate retention clocks for prompts, uploads and outputs; shorten them or destroy a task's content |
| Integration | You don't want a custom client per model | One async task API, SDKs (TypeScript, Python, Go, PHP, Java), CLI, MCP server, agent skill |

### Quick start: NSFW image-to-video over HTTP

```bash
export SPICY_API_KEY="sk-spicy-..."   # create one at https://spicyapi.ai/console

# 1) create the task
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

# 2) poll until state is "succeeded", then read data.output.assets[0].url
curl -s "https://api.spicyapi.ai/api/v1/jobs/recordInfo?taskId=TASK_ID" \
  -H "Authorization: Bearer $SPICY_API_KEY"
```

Input fields differ per model. Read the live schema with `GET /api/v1/models/{model}` (or the model page) before sending a request. Full reference: [docs.spicyapi.ai](https://docs.spicyapi.ai/docs?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=api-quickstart).

### Other providers

Policies change often and are enforced differently per model, so test with your own prompts before committing. Always read the provider's current acceptable-use policy.

- [Venice.ai](https://venice.ai): private, uncensored chat and image generation with an API.
- [fal.ai](https://fal.ai), [WaveSpeed](https://wavespeed.ai), [Replicate](https://replicate.com): large hosted model catalogs; NSFW handling varies by model and by account settings.
- [RunPod](https://www.runpod.io), [Vast.ai](https://vast.ai): rent GPUs and run open-weight models yourself (see [self-hosted](#self-hosted-and-open-weight-models)).

---

## Agent skills and MCP servers

AI coding agents (Claude Code, Cursor, Codex, Windsurf, Cline, Gemini CLI, OpenClaw) can now generate media for you through **skills** and **MCP servers**. Ask in plain English ("make a 5-second boudoir clip from this image") and the agent picks the model, builds the request and downloads the result.

| Resource | Type | Install |
|---|---|---|
| 🌶️ [nsfw-ai-skill](https://github.com/Spicy-API/nsfw-ai-skill) | Agent skill: NSFW image, video, edit and text generation, prompt expansion, cost estimates | `npx skills add Spicy-API/nsfw-ai-skill` |
| 🌶️ [SpicyAPI MCP server](https://docs.spicyapi.ai/docs/mcp?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=skills-table) (`@spicyapi/mcp`) | MCP: list models, quote, create / wait / retry tasks, upload files | `claude mcp add spicyapi -e SPICY_API_KEY=$SPICY_API_KEY -- npx --yes --package=@spicyapi/mcp spicyapi-mcp` |
| 🌶️ [SpicyAPI official skill](https://github.com/Spicy-API/spicy-skill) | Agent skill for the full SpicyAPI developer surface | `npx skills add Spicy-API/spicy-skill` |
| 🌶️ [SpicyAPI CLI](https://docs.spicyapi.ai/docs?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=skills-table) (`@spicyapi/cli`) | Command line: models, quotes, tasks, uploads | `npx @spicyapi/cli --help` |
| [anthropics/skills](https://github.com/anthropics/skills) | Reference skills and the skill format | — |
| [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) | Directory of MCP servers | — |

---

## Self-hosted and open-weight models

Free to run, full control, no platform filter at all. The trade-off is hardware, setup time, and licensing (read each license before commercial use).

### Video

- [Wan 2.2](https://github.com/Wan-Video/Wan2.2) and [Wan 2.1](https://github.com/Wan-Video/Wan2.1): Alibaba's open video models (Apache-2.0). Huge community LoRA ecosystem; the base of the hosted Wan Spicy editions.
- [HunyuanVideo](https://github.com/Tencent-Hunyuan/HunyuanVideo): Tencent's open video model.
- [LTX-Video](https://github.com/Lightricks/LTX-Video) and [LTX-2](https://github.com/Lightricks/LTX-2): Lightricks' fast open video models.
- [CogVideoX](https://github.com/zai-org/CogVideo): Zhipu's open video model.
- [Mochi 1](https://github.com/genmoai/mochi): Genmo's open video model.
- [ComfyUI-WanVideoWrapper](https://github.com/kijai/ComfyUI-WanVideoWrapper): the go-to ComfyUI nodes for Wan with LoRA support.

### Image

- [Qwen-Image](https://github.com/QwenLM/Qwen-Image): open image generation and editing.
- [Z-Image](https://github.com/Tongyi-MAI/Z-Image): Alibaba Tongyi's efficient open image model.
- [FLUX.1](https://github.com/black-forest-labs/flux): check the license of each variant (dev is non-commercial).
- SDXL / Pony Diffusion / Illustrious checkpoints on [Civitai](https://civitai.com) and [Hugging Face](https://huggingface.co): the largest pool of NSFW-tuned community checkpoints.

**Rough hardware guide:** image models run on 8–12 GB VRAM; video models want 16–24 GB (or quantized versions with lower quality). If you don't have a GPU, rent one on RunPod or Vast.ai, or use a hosted API.

---

## Local interfaces and workflow tools

- [ComfyUI](https://github.com/Comfy-Org/ComfyUI): node-based workflows for image and video; the most flexible option.
- [Stable Diffusion WebUI (A1111)](https://github.com/AUTOMATIC1111/stable-diffusion-webui): classic UI with a huge extension ecosystem.
- [Forge](https://github.com/lllyasviel/stable-diffusion-webui-forge): faster, lower-VRAM A1111 fork.
- [InvokeAI](https://github.com/invoke-ai/InvokeAI): polished canvas-based UI.
- [Fooocus](https://github.com/lllyasviel/Fooocus): the simplest local SDXL UI.
- 🌶️ [SpicyAPI Studio](https://spicyapi.ai/create?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=interfaces): browser-based image and video studio with templates, [effects](https://spicyapi.ai/create/effects?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=interfaces) and [styles](https://spicyapi.ai/create/styles?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=interfaces); no GPU needed.

---

## LoRAs, checkpoints and training

**Where to find NSFW LoRAs**

- [Civitai](https://civitai.com): the largest library; filter by base model (Wan 2.2, SDXL, Pony, Flux) and enable mature content in your account settings.
- [Hugging Face](https://huggingface.co): many LoRAs and full fine-tunes; check each model card's license.
- [Tensor.Art](https://tensor.art): model sharing with an online runner.

**Using LoRAs through an API.** Wan 2.2 Spicy LoRA takes `loras`, `high_noise_loras` and `low_noise_loras` (up to three). High-noise LoRAs shape composition and motion early in denoising; low-noise LoRAs shape texture and detail late. Each LoRA is an object with a direct `path` to the weights file and a `scale` (0–4, default 1); change one LoRA at a time. See the [Wan 2.2 Spicy LoRA page](https://spicyapi.ai/models/wan-2-2-spicy-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=lora) for the exact schema.

**Training your own**

- [kohya_ss](https://github.com/bmaltais/kohya_ss): the standard LoRA trainer for SD / SDXL.
- [OneTrainer](https://github.com/Nerogar/OneTrainer): LoRA and full fine-tuning with a GUI.
- [ai-toolkit](https://github.com/ostris/ai-toolkit): training for Flux, Wan and newer models.

Only train on images you own or have rights to, and only on adults.

---

## Upscaling, restoration and post-production

- [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN): 4× image and video upscaling.
- [GFPGAN](https://github.com/TencentARC/GFPGAN) and [CodeFormer](https://github.com/sczhou/CodeFormer): face restoration.
- [RIFE](https://github.com/hzwer/ECCV2022-RIFE): frame interpolation for smoother slow motion.
- [FFmpeg](https://ffmpeg.org): cut, join, add audio (`ffmpeg -i clip.mp4 -i track.mp3 -c:v copy -shortest out.mp4`).
- [Topaz Video AI](https://www.topazlabs.com): commercial video upscaler.

---

## Prompt engineering for mature content

A good NSFW prompt reads like a shot list, not a list of adjectives.

```
[Subject: adult, age range, look] + [Wardrobe or state] + [Action: one clear motion]
+ [Setting] + [Lighting] + [Camera] + [Style / quality]
```

Example (image-to-video):

```
A woman in her early 30s in a black silk slip dress sits on the edge of a hotel bed.
She slowly slides one strap off her shoulder and looks up at the camera.
Warm tungsten bedside lamp, soft shadows, city lights through the window.
Slow push-in from medium shot to close-up, shallow depth of field, 35mm film look.
```

What makes the difference:

1. **One main action per clip.** Breathing, hair movement, a slow turn and fabric motion are reliable; complex choreography and two-person interaction break first.
2. **Describe the camera.** "Slow push-in", "static camera", "orbit left" beat "cinematic".
3. **Name the light.** Candlelight, window light, neon rim light, golden hour.
4. **Let the first frame carry the look.** In image-to-video, don't re-describe everything visible; describe what *changes*.
5. **Keep clips short.** 5 seconds is the sweet spot for anatomy consistency; extend in a second call if you need more.
6. **Always state adult age** ("in her 30s", "adult man in his 40s") and avoid descriptors that suggest youth.

Ready prompts: **[nsfw-ai-image-prompts](https://github.com/Spicy-API/nsfw-ai-image-prompts)** for stills and edits, **[nsfw-ai-video-prompts](https://github.com/Spicy-API/nsfw-ai-video-prompts)** for video.

---

## How to choose: a decision guide

```
Do you have a GPU with 16 GB+ VRAM and time to tinker?
├── Yes → ComfyUI + Wan 2.2 / Qwen-Image / Z-Image open weights + Civitai LoRAs (free, most control)
└── No
    ├── No-code, in the browser → SpicyAPI Studio (uncensored image & video generator)
    └── Code or an AI agent
        ├── Best all-round video → Wan 3.0 (T2V / I2V / Ref2V, Freedom 96, $0.45 per 5 s)
        ├── Uncensored from a still → Seedance 2.5 Spicy, Wan 2.7 Spicy or Vidu Q3 Spicy
        ├── Custom style / character → MiniMax H3 LoRA / Singularity LoRA (video), Qwen Image 2.1 LoRA (stills)
        ├── Volume on a budget  → Wan 2.6 Flash or Seedance 1.5 Pro Spicy ($0.11–0.13 per 5 s)
        ├── Stills              → Qwen Image 2.1 (Qwen Image 2.1 LoRA for your own style)
        ├── Text / roleplay     → Grok 4.7 or Grok 4.3
        └── From Claude Code / Cursor → nsfw-ai-skill or the SpicyAPI MCP server
```

**By use case**

| Use case | Recommended stack |
|---|---|
| Adult subscription site / creator content | Qwen Image 2.1 for stills → Wan 3.0 or Seedance 2.5 Spicy for clips → Video Upscaler |
| AI companion or roleplay app | Grok 4.7 or Grok 4.3 for chat → Qwen Image 2.1 for selfies → MiniMax H3 Spicy or Wan 3.0 for short motion |
| Hobbyist, lots of experiments | Wan 2.6 Flash or Seedance 1.5 Pro Spicy, iterate, re-render the keepers on Wan 3.0 |
| Anime / hentai-style content | Qwen Image 2.1 LoRA with an anime LoRA → Vidu Q3 Spicy (Freedom 96.7) or Wan 2.2 Spicy LoRA with the same LoRA |
| Adult fiction and interactive stories | Grok 4.7 for text, Qwen Image 2.1 for illustrations |

---

## Rules that apply to every tool

These are not optional and no setting unlocks them:

- **No minors, ever.** No sexual content depicting anyone under 18 or anyone who *appears* to be under 18, in any style, including anime, illustration and "fictional age" framing.
- **No real people without documented consent.** No sexual deepfakes, no face or head swaps of real people into sexual content, no "undressing" or "nudifying" photos. Public figures are not an exception.
- **No impersonation, harassment, extortion or fake evidence** using anyone's likeness.
- **Follow your local law and your audience's.** Some countries restrict certain fictional material or adult content altogether.
- **Label AI-generated content** where platforms or laws require it, and keep records of consent for any real person you depict.

SpicyAPI's full rules: [Content Policy](https://spicyapi.ai/legal/content-policy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=rules) and [Acceptable Use Policy](https://spicyapi.ai/legal/acceptable-use?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=rules).

---

## FAQ

### What is the best NSFW AI video generator in 2026?
On SpicyAPI's public tests, **Wan 3.0** is the best all-round pick: Spicy Index 76.5 (#2 of 37 video models), Freedom Score 96, every explicit test prompt rendered (9/9), clips up to 30 s, and $0.45 per 5 s at 720p. For uncensored image-to-video, the Spicy editions **Seedance 2.5 Spicy**, **Wan 2.7 Spicy** and **Vidu Q3 Spicy** (Freedom 96.7–100) are the safest bets; for your own style, **MiniMax H3 LoRA**. Standard Seedance 2.0 has the highest capability score but often softens explicit prompts (Freedom 70.4). Results: [SpicyAPI leaderboards](https://spicyapi.ai/leaderboards?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=faq).

### What is the best uncensored AI image generator?
Hosted: **Qwen Image 2.1** (Spicy Index 73, Freedom 96.3, from $0.024/image); **Qwen Image 2.1 LoRA** (#1 on the image index, 80.5) and **MiniMax H3 Image LoRA** (Freedom 100) for your own styles; **Seedream 5.0 Lite / Pro** as strong alternatives; **Z-Image Spicy** ($0.01235, Freedom 98.8) for the cheapest volume. Self-hosted: SDXL, Pony and Illustrious community checkpoints in ComfyUI or Forge.

### How do I turn an image into an NSFW video?
Generate or pick a first frame (a fictional adult, or yourself), then send it to an NSFW image-to-video model such as Wan 3.0 or Seedance 2.5 Spicy with a short prompt that describes the motion and the camera. See the [API quick start](#quick-start-nsfw-image-to-video-over-http) or use the browser-based [image-to-video tool](https://spicyapi.ai/create/image-to-video?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=faq).

### Is there a free NSFW AI generator?
Running open-weight models locally (ComfyUI + Wan 2.2, Qwen-Image or Z-Image) is free apart from hardware and electricity. Hosted services charge because GPUs cost money; SpicyAPI has no subscription and bills per output, with failed jobs refunded.

### What is the cheapest NSFW AI video API?
On the SpicyAPI catalog (2026-09-27), **Wan 2.6 Flash** ($0.1125 per 5 s at 720p, Freedom 100) and **Seedance 1.5 Pro Spicy** ($0.13 per 5 s at 720p, or $0.06 at 480p without audio; Freedom 96.7) are the cheapest models that pass the explicit tests. Wan 2.2 Spicy and LTX 2.3 Spicy follow at $0.19 per 5 s (720p).

### Is NSFW AI generation legal?
Generating sexual content of **fictional adults** is legal in most countries, but laws vary and some content is illegal everywhere: anything involving minors, and sexual content of real people made without their consent. You are responsible for what you create and share. This is not legal advice.

### What's the difference between "uncensored" and "Spicy" models?
"Uncensored" usually describes the platform or model not refusing mature prompts. On SpicyAPI, "Spicy" editions are specific model versions tuned for adult output; standard models are listed with their own policy tier so you can see which ones soften or filter content.

### Can I use NSFW AI inside Claude Code, Cursor or other agents?
Yes. Install [nsfw-ai-skill](https://github.com/Spicy-API/nsfw-ai-skill) (`npx skills add Spicy-API/nsfw-ai-skill`) or add the SpicyAPI MCP server, set `SPICY_API_KEY`, and ask the agent in natural language.

---

## Related repositories

- **[nsfw-ai-image-prompts](https://github.com/Spicy-API/nsfw-ai-image-prompts)**: 104 NSFW image and uncensored editing prompts with real output cases.
- **[nsfw-ai-video-prompts](https://github.com/Spicy-API/nsfw-ai-video-prompts)**: 100+ NSFW video prompts, reference-image prompts, negative prompts and model-specific tips.
- **[nsfw-ai-skill](https://github.com/Spicy-API/nsfw-ai-skill)**: agent skill for NSFW image, video and text generation from Claude Code, Cursor, Codex and more.
- **[spicy-skill](https://github.com/Spicy-API/spicy-skill)** · **[spicy-mcp](https://github.com/Spicy-API/spicy-mcp)** · **[spicy-sdk](https://github.com/Spicy-API/spicy-sdk)**: official SpicyAPI developer tools.

## Contributing

Additions are welcome, including competitors. Read [CONTRIBUTING.md](CONTRIBUTING.md) first. In short: one resource per pull request, a one-line neutral description, a working link, and no resources whose main purpose is non-consensual imagery, content involving minors, or evading laws.

## License

[CC0 1.0](LICENSE). To the extent possible under law, the contributors have waived all copyright to this list.

<p align="center"><sub>Found this useful? ⭐ Star the repo so other creators can find it.</sub></p>
