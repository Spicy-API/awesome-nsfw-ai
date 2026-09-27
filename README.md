<!--
  Keywords: awesome nsfw ai, nsfw ai generator, uncensored ai image generator, uncensored ai video generator,
  nsfw ai video generator, nsfw image to video, nsfw ai image editor, uncensored ai models, uncensored llm,
  nsfw ai api, best nsfw ai image generator 2026, wan 2.2 spicy, seedance spicy, nsfw ai skill, nsfw mcp
-->

<p align="center"><b>English</b> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.fr.md">Français</a> · <a href="README.es.md">Español</a></p>

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

| I want to… | Start here | Why |
|---|---|---|
| Text-to-video or put my character in a new scene | [Seedance 2.5](https://spicyapi.ai/models/seedance-2-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) or [Wan 3.0](https://spicyapi.ai/models/wan-3-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) | Standard models with catalog tier `unrestricted`; T2V, I2V and reference-to-video |
| Make an NSFW video from a still image, cheaply | 🌶️ [Wan 2.2 Spicy](https://spicyapi.ai/models/wan-2-2-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) or [LTX 2.3 Spicy](https://spicyapi.ai/models/ltx-2-3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) | From $0.019 per output second at 480p |
| The best-looking uncensored image-to-video | 🌶️ [Seedance 2.5 Spicy](https://spicyapi.ai/models/seedance-2-5-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) | 4–30 s clips, native up to 1080p, optional audio |
| Uncensored video with my own LoRAs | 🌶️ [Wan 2.2 Spicy LoRA](https://spicyapi.ai/models/wan-2-2-spicy-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) | Up to three LoRAs per call, plus video-extend |
| An uncensored text-to-image model | [Qwen Image 2.1](https://spicyapi.ai/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) | From $0.024 per image, long prompts, 15 aspect ratios, edits from reference images |
| Anime / hentai-style stills | [Prefect Pony XL](https://spicyapi.ai/models/prefect-pony-xl?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) or self-hosted Pony / SDXL checkpoints | Tag-style prompts, anime lineage |
| An uncensored AI image editor | [Qwen Image 2.1 Edit](https://spicyapi.ai/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) or 🌶️ [Qwen Image Edit Spicy](https://spicyapi.ai/models/qwen-image-spicy-edit?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) | 1–10 reference images or one image + one instruction, no mask needed |
| Run everything locally, free | [ComfyUI](https://github.com/Comfy-Org/ComfyUI) + [Wan 2.2](https://github.com/Wan-Video/Wan2.2) open weights | Needs a strong GPU (24 GB VRAM is comfortable) |
| Let Claude Code / Cursor generate for me | [nsfw-ai-skill](https://github.com/Spicy-API/nsfw-ai-skill) or the official [SpicyAPI MCP server](https://docs.spicyapi.ai/docs/mcp?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) | Natural-language generation from your agent |
| Copy-paste prompts that work | [nsfw-ai-video-prompts](https://github.com/Spicy-API/nsfw-ai-video-prompts) | 116 ready-to-use video prompts plus 130 real output cases, each with its prompt |

Prices are the lowest listed tier in the SpicyAPI public catalog on 2026-09-27. Higher resolutions, audio and longer clips cost more; check the model page before you run a job.

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

---

## Uncensored AI video generators

Image-to-video (I2V) is the most reliable way to make an NSFW AI video: you control the look with the first frame and the model only has to animate it. Text-to-video (T2V) and reference-to-video (Ref2V, "put the character from these images into a new scene") come from the standard models below.

### All uncensored video models, most popular first

Ordered like the SpicyAPI catalog: most popular first, and within a family the newest version first. 🌶️ **Spicy** editions are tuned for adult output. **Standard** models listed here carry the catalog tier `unrestricted` (the provider applies no content filter), so they also take mature prompts. Prices are the cheapest tier. Catalog read on <!-- catalog:date -->
2026-09-27
<!-- /catalog:date -->

<!-- catalog:video -->
| Model | Type | Tasks | Duration | From |
|---|---|---|---|---|
| [Seedance 2.5 Spicy](https://spicyapi.ai/models/seedance-2-5-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | I2V | 4–30 s | $0.216/s |
| [Seedance 2.5](https://spicyapi.ai/models/seedance-2-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, Ref2V, T2V | 4–30 s | $0.1234/s |
| [Seedance 2.0 Spicy](https://spicyapi.ai/models/seedance-2-0-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | I2V | 4–15 s | $0.114/s |
| [Seedance 2.0](https://spicyapi.ai/models/seedance-2-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, Ref2V, T2V | 4–15 s | $0.07/s |
| [Wan 3.0 Prime](https://spicyapi.ai/models/wan-3-0-prime?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, Ref2V, T2V | 2–30 s | $0.0612/s |
| [Wan 3.0](https://spicyapi.ai/models/wan-3-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, Ref2V, T2V | 2–30 s | $0.045/s |
| [MiniMax H3 Spicy](https://spicyapi.ai/models/minimax-h3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | I2V | 3–15 s | $0.038/s |
| [MiniMax H3](https://spicyapi.ai/models/minimax-h3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, Ref2V, T2V | 4–15 s | $0.025/s |
| [MiniMax H3 Singularity LoRA](https://spicyapi.ai/models/minimax-h3-singularity-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, Ref2V | 3–15 s | $0.06/s |
| [LTX 2.5](https://spicyapi.ai/models/ltx-2-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, T2V | 5–20 s | $0.09/s |
| [Wan 3.0 Pro Prime](https://spicyapi.ai/models/wan-3-0-pro-prime?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, Ref2V, T2V | 2–30 s | $0.234/s |
| [Wan 3.0 Pro](https://spicyapi.ai/models/wan-3-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, Ref2V, T2V | 2–30 s | $0.144/s |
| [MiniMax H3 LoRA](https://spicyapi.ai/models/minimax-h3-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, Ref2V, T2V | 3–15 s | $0.05/s |
| [HappyHorse 1.1](https://spicyapi.ai/models/happyhorse-1-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, Ref2V, T2V | 3–15 s | $0.14/s |
| [Seedance 2.0 Mini Spicy](https://spicyapi.ai/models/seedance-2-0-mini-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | I2V | 4–15 s | $0.0387/s |
| [Seedance 2.0 Mini](https://spicyapi.ai/models/seedance-2-0-mini?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, Ref2V, T2V | 4–15 s | $0.01097/s |
| [Wan 2.7 Spicy](https://spicyapi.ai/models/wan-2-7-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | I2V | 2–15 s | $0.1235/s |
| [LTX 2.3 Spicy](https://spicyapi.ai/models/ltx-2-3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | I2V | 3–20 s | $0.019/s |
| [LTX 2.3 Spicy LoRA](https://spicyapi.ai/models/ltx-2-3-spicy-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | I2V | 3–20 s | $0.0285/s |
| [Seedance 2.0 Fast Spicy](https://spicyapi.ai/models/seedance-2-0-fast-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | I2V | 4–15 s | $0.081/s |
| [Seedance 2.0 Fast](https://spicyapi.ai/models/seedance-2-0-fast?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, Ref2V, T2V | 4–15 s | $0.02254/s |
| [Vidu Q3 Turbo](https://spicyapi.ai/models/vidu-q3-turbo?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V | 1–16 s | $0.042/s |
| [Vidu Q3 Spicy](https://spicyapi.ai/models/vidu-q3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | I2V | 1–16 s | $0.0665/s |
| [Vidu Q3](https://spicyapi.ai/models/vidu-q3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V | 1–16 s | $0.07/s |
| [Vidu Q3 Pro](https://spicyapi.ai/models/vidu-q3-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V | 1–16 s | $0.054/s |
| [Seedance 1.5 Pro Spicy](https://spicyapi.ai/models/seedance-1-5-pro-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | I2V | 4–12 s | $0.012/s |
| [Seedance 1.5 Pro](https://spicyapi.ai/models/seedance-1-5-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, T2V | 4–12 s | $0.0112/s |
| [Wan 2.6 Flash](https://spicyapi.ai/models/wan-2-6-flash?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V | 5, 10, 15 s | $0.0225/s |
| [Wan 2.6 Spicy](https://spicyapi.ai/models/wan-2-6-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | I2V | 5, 10, 15 s | $0.095/s |
| [Wan 2.6](https://spicyapi.ai/models/wan-2-6?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, Ref2V, T2V | 5, 10, 15 s | $0.065/s |
| [Wan 2.5](https://spicyapi.ai/models/wan-2-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V, T2V | 5, 10 s | $0.045/s |
| [Wan 2.2 Spicy](https://spicyapi.ai/models/wan-2-2-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | I2V | 5, 8 s | $0.019/s |
| [Wan 2.2 Spicy LoRA](https://spicyapi.ai/models/wan-2-2-spicy-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | I2V, Extend | 5, 8 s | $0.024/s |
| [Wan 2.2 LoRA](https://spicyapi.ai/models/wan-2-2-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | I2V | 5, 8 s | $0.024/s |
<!-- /catalog:video -->

Quick guidance:

- **Best quality:** Seedance 2.5 Spicy (up to 30 s), then Seedance 2.0 Spicy. For text-to-video or reference-to-video at that quality, use standard Seedance 2.5 / Seedance 2.0.
- **Newest Wan:** Wan 3.0 (and Prime / Pro tiers) for T2V, I2V and Ref2V up to 30 s; Wan 2.7 Spicy and Wan 2.6 Spicy for tuned adult image-to-video.
- **Cheapest drafts:** Seedance 1.5 Pro Spicy from $0.012/s, Wan 2.2 Spicy and LTX 2.3 Spicy from $0.019/s.
- **Your own LoRAs:** Wan 2.2 Spicy LoRA (plus `video-extend`), LTX 2.3 Spicy LoRA, MiniMax H3 LoRA.

Some video endpoints bill in whole blocks (for example a 6-second clip on a 5-second block is billed as 10 s); the model page states the block length, and the quoted amount is the most you can be charged. Browse and filter everything on [SpicyAPI › Uncensored AI models](https://spicyapi.ai/explore/uncensored-ai-models?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=video-table).

### What a 5-second NSFW clip costs

Lowest listed tier × 5 seconds, SpicyAPI catalog on 2026-09-27. Treat this as a floor, not a quote.

| Model | 1 clip (5 s) | 100 clips | 1,000 clips |
|---|---|---|---|
| Seedance 1.5 Pro Spicy (480p, no audio) | $0.06 | $6.00 | $60 |
| Wan 2.2 Spicy (480p) | $0.095 | $9.50 | $95 |
| LTX 2.3 Spicy (480p) | $0.095 | $9.50 | $95 |
| MiniMax H3 Spicy (480p) | $0.19 | $19.00 | $190 |
| Seedance 2.0 Mini Spicy (480p) | $0.19 | $19.35 | $193.50 |
| Wan 2.6 Spicy (720p) | $0.475 | $47.50 | $475 |
| Seedance 2.0 Spicy (480p) | $0.57 | $57.00 | $570 |
| Seedance 2.5 Spicy (480p) | $1.08 | $108.00 | $1,080 |

Wan 2.2 Spicy at 720p is $0.038/s, so a 5-second 720p clip is $0.19. Failed tasks are refunded automatically.

---

## Uncensored AI image generators

**Recommended: [Qwen Image 2.1](https://spicyapi.ai/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick)** (catalog tier `unrestricted`, from $0.024 per image at 1k). It follows long briefs (up to 5,000 characters), renders 15 aspect ratios at 1k, 1.5k or 2k, and edits from 1–10 reference images in the same family. [Qwen Image 2.1 LoRA](https://spicyapi.ai/models/qwen-image-2-1-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick) adds up to three of your own LoRAs for a consistent style or character.

All uncensored image models, in catalog order:

<!-- catalog:image -->
| Model | Type | Tasks | From |
|---|---|---|---|
| [Qwen Image 2.1](https://spicyapi.ai/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | Edit, T2I | $0.024/image |
| [Qwen Image 2.1 LoRA](https://spicyapi.ai/models/qwen-image-2-1-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | Edit, T2I | $0.03/image |
| [MiniMax H3 Image LoRA](https://spicyapi.ai/models/minimax-h3-image-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | Edit, T2I | $0.042/image |
| [Qwen Image 3.0 Pro](https://spicyapi.ai/models/qwen-image-3-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | Edit, T2I | $0.04/image |
| [Qwen Image 3.0](https://spicyapi.ai/models/qwen-image-3-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | Edit, T2I | $0.03/image |
| [Seedream 5.0 Pro](https://spicyapi.ai/models/seedream-5-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | Edit, T2I | $0.036/image |
| [Qwen Image Edit Spicy](https://spicyapi.ai/models/qwen-image-spicy-edit?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | Edit | $0.038/image |
| [Seedream 5.0 Lite](https://spicyapi.ai/models/seedream-5-0-lite?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | Edit, T2I | $0.0345/image |
| [Qwen Image 2](https://spicyapi.ai/models/alibaba-qwen-image-2?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | Edit, T2I | $0.035/image |
| [Qwen Image 2512 LoRA](https://spicyapi.ai/models/qwen-image-2512-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | Edit, T2I | $0.03/image |
| [Z-Image Spicy Pro](https://spicyapi.ai/models/z-image-spicy-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | T2I | $0.019/image |
| [Z-Image Spicy](https://spicyapi.ai/models/z-image-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | 🌶️ Spicy | T2I | $0.01235/image |
| [Z-Image](https://spicyapi.ai/models/z-image?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | T2I | $0.01/image |
| [Z-Image Turbo LoRA](https://spicyapi.ai/models/z-image-turbo-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | Edit, T2I | $0.012/image |
| [Seedream 4.0](https://spicyapi.ai/models/seedream-4-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | Edit, T2I | $0.03/image |
| [Prefect Pony XL](https://spicyapi.ai/models/prefect-pony-xl?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | T2I | $0.015/image |
| [FLUX.1 Dev LoRA](https://spicyapi.ai/models/flux-1-dev-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table) | Standard | T2I | $0.018/image |
<!-- /catalog:image -->

No-code option: the [uncensored AI image generator in SpicyAPI Studio](https://spicyapi.ai/create/uncensored-ai-image-generator?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-studio) runs the same models in the browser with styles, aspect ratios and a price shown before you generate.

For a head-to-head test of which image models allow what, read [Less-restrictive image model evaluation](https://spicyapi.ai/blog/less-restrictive-model-evaluation?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-eval).

---

## NSFW AI image editors and face tools

| Tool | What it does | From |
|---|---|---|
| [Qwen Image 2.1 Edit](https://spicyapi.ai/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table) | Uncensored editing from 1–10 reference images of a **fictional** or consenting subject: outfit, pose, setting, relighting (catalog tier `unrestricted`) | $0.036 / image |
| 🌶️ [Qwen Image Edit Spicy](https://spicyapi.ai/models/qwen-image-spicy-edit?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table) | Uncensored instruction editing: change outfit, pose, setting or lighting of a **fictional** or consenting subject | $0.038 / image |
| [Image Expander](https://spicyapi.ai/models/image-expander-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table) | Outpaint to a wider or taller frame | $0.024 / image |
| [Object Eraser](https://spicyapi.ai/models/object-eraser-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table) | Remove objects, logos, watermarks you own | $0.03 / image |
| [Image Upscaler](https://spicyapi.ai/models/image-upscaler-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table) / [Video Upscaler](https://spicyapi.ai/models/video-upscaler-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table) | Sharpen and enlarge finished output | $0.012 / image, $0.006 / s |
| [Face Swap](https://spicyapi.ai/models/face-swap-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table), [Head Swap](https://spicyapi.ai/models/head-swap-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table), [Video Character Swap](https://spicyapi.ai/models/character-swap-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table) | Keep one consistent **fictional** character across images and clips | $0.013 / image, video from $0.064 / s |
| [Lip Sync](https://spicyapi.ai/models/lip-sync-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table), [Talking Avatar](https://spicyapi.ai/models/talking-avatar-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table), [Video Sound Effects](https://spicyapi.ai/models/foley-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table) | Voice and audio for AI characters | from $0.0012 / s |

> ⚠️ Face and head swap tools must **never** be used to put a real person into sexual content without their documented consent, and "undressing" or "nudifying" a photo of a real person is prohibited on every reputable platform. Being a celebrity or having public photos is not consent. Use these tools for fictional characters you created, or for yourself.

Self-hosted equivalents: [IP-Adapter](https://github.com/tencent-ailab/IP-Adapter), [InstantID](https://github.com/instantX-research/InstantID) and [PhotoMaker](https://github.com/TencentARC/PhotoMaker) for character consistency; [ControlNet](https://github.com/lllyasviel/ControlNet) for pose control.

---

## Uncensored LLMs and roleplay

Text models matter for NSFW work in three places: erotic fiction and interactive stories, companion and roleplay apps, and **writing better image and video prompts** (an LLM expands a one-line idea into a detailed, camera-aware prompt).

### Hosted (OpenAI-compatible)

SpicyAPI serves text models through OpenAI, Anthropic and Gemini-compatible endpoints at `https://api.spicyapi.ai`, so existing SDKs work by changing the base URL. Models whose catalog tier is `unrestricted` on 2026-09-27 include:

| Model | From (per 1K tokens) | Good for |
|---|---|---|
| [Grok 4.7](https://spicyapi.ai/models/grok-4-7?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table) | $0.0036 | Creative writing, roleplay with personality |
| [DeepSeek V4 Pro](https://spicyapi.ai/models/deepseek-v4-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table) | $0.00396 | Long-form fiction, reasoning |
| [DeepSeek V4.1 Flash](https://spicyapi.ai/models/deepseek-v4-1-flash?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table) | $0.0012 | High-volume chat, prompt expansion |
| [GLM 5.3 Flash](https://spicyapi.ai/models/glm-5-3-flash?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table) | $0.000425 | Cheapest chat in the catalog |
| [Kimi K3](https://spicyapi.ai/models/kimi-k3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table) | $0.0135 | Long context stories |

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

100+ tested prompts, negative prompts and a camera/lighting cheat sheet live in **[nsfw-ai-video-prompts](https://github.com/Spicy-API/nsfw-ai-video-prompts)**.

---

## How to choose: a decision guide

```
Do you have a GPU with 16 GB+ VRAM and time to tinker?
├── Yes → ComfyUI + Wan 2.2 / Qwen-Image / Z-Image open weights + Civitai LoRAs (free, most control)
└── No
    ├── No-code, in the browser → SpicyAPI Studio (uncensored image & video generator)
    └── Code or an AI agent
        ├── Volume on a budget  → Wan 2.2 Spicy / LTX 2.3 Spicy ($0.019/s at 480p)
        ├── Best quality        → Seedance 2.5 Spicy or Seedance 2.0 Spicy
        ├── Text-to-video       → Seedance 2.5 or Wan 3.0 (standard, unrestricted)
        ├── Stills              → Qwen Image 2.1 (Qwen Image 2.1 LoRA for your own style)
        ├── Custom styles       → Wan 2.2 Spicy LoRA / LTX 2.3 Spicy LoRA
        ├── Anime               → Prefect Pony XL (stills) → Vidu Q3 Spicy (motion)
        └── From Claude Code / Cursor → nsfw-ai-skill or the SpicyAPI MCP server
```

**By use case**

| Use case | Recommended stack |
|---|---|
| Adult subscription site / creator content | Qwen Image 2.1 for stills → Seedance 2.0 Spicy or Wan 2.6 Spicy for clips → Video Upscaler |
| AI companion or roleplay app | Grok 4.7 or DeepSeek V4 for chat → Qwen Image 2.1 for selfies → MiniMax H3 Spicy for short motion |
| Hobbyist, lots of experiments | Wan 2.2 Spicy at 480p, iterate, re-render the keepers at 720p |
| Anime / hentai-style content | Prefect Pony XL → Vidu Q3 Spicy or Wan 2.2 Spicy LoRA with an anime LoRA |
| Erotic fiction and interactive stories | Grok 4.7 / Kimi K3 for text, Qwen Image 2.1 for illustrations |

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
For quality, **Seedance 2.5 Spicy** (4–30 s, up to 1080p native) and **Seedance 2.0 Spicy** lead the image-to-video Spicy editions; for text-to-video use the standard **Seedance 2.5** or **Wan 3.0**, both `unrestricted` in the catalog. For price, **Wan 2.2 Spicy** and **LTX 2.3 Spicy** start at $0.019 per second. If you want custom styles, use **Wan 2.2 Spicy LoRA**. All are available through one API on [SpicyAPI](https://spicyapi.ai/?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=faq).

### What is the best uncensored AI image generator?
Hosted: **Qwen Image 2.1** (from $0.024/image, catalog tier `unrestricted`) for photoreal and editorial work, with **Qwen Image 2.1 LoRA** for your own styles; **Z-Image Spicy** (from $0.01235/image) for the cheapest volume; **Prefect Pony XL** for anime. Self-hosted: SDXL, Pony and Illustrious community checkpoints in ComfyUI or Forge.

### How do I turn an image into an NSFW video?
Generate or pick a first frame (a fictional adult, or yourself), then send it to an NSFW image-to-video model such as Wan 2.2 Spicy with a short prompt that describes the motion and the camera. See the [API quick start](#quick-start-nsfw-image-to-video-over-http) or use the browser-based [image-to-video tool](https://spicyapi.ai/create/image-to-video?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=faq).

### Is there a free NSFW AI generator?
Running open-weight models locally (ComfyUI + Wan 2.2, Qwen-Image or Z-Image) is free apart from hardware and electricity. Hosted services charge because GPUs cost money; SpicyAPI has no subscription and bills per output, with failed jobs refunded.

### What is the cheapest NSFW AI video API?
On the SpicyAPI catalog (2026-09-27) the lowest per-second price for a Spicy video model is **Seedance 1.5 Pro Spicy at $0.012/s** (480p, no audio), followed by **Wan 2.2 Spicy** and **LTX 2.3 Spicy at $0.019/s** (480p).

### Is NSFW AI generation legal?
Generating sexual content of **fictional adults** is legal in most countries, but laws vary and some content is illegal everywhere: anything involving minors, and sexual content of real people made without their consent. You are responsible for what you create and share. This is not legal advice.

### What's the difference between "uncensored" and "Spicy" models?
"Uncensored" usually describes the platform or model not refusing mature prompts. On SpicyAPI, "Spicy" editions are specific model versions tuned for adult output; standard models are listed with their own policy tier so you can see which ones soften or filter content.

### Can I use NSFW AI inside Claude Code, Cursor or other agents?
Yes. Install [nsfw-ai-skill](https://github.com/Spicy-API/nsfw-ai-skill) (`npx skills add Spicy-API/nsfw-ai-skill`) or add the SpicyAPI MCP server, set `SPICY_API_KEY`, and ask the agent in natural language.

---

## Related repositories

- **[nsfw-ai-video-prompts](https://github.com/Spicy-API/nsfw-ai-video-prompts)**: 100+ NSFW video prompts, reference-image prompts, negative prompts and model-specific tips.
- **[nsfw-ai-skill](https://github.com/Spicy-API/nsfw-ai-skill)**: agent skill for NSFW image, video and text generation from Claude Code, Cursor, Codex and more.
- **[spicy-skill](https://github.com/Spicy-API/spicy-skill)** · **[spicy-mcp](https://github.com/Spicy-API/spicy-mcp)** · **[spicy-sdk](https://github.com/Spicy-API/spicy-sdk)**: official SpicyAPI developer tools.

## Contributing

Additions are welcome, including competitors. Read [CONTRIBUTING.md](CONTRIBUTING.md) first. In short: one resource per pull request, a one-line neutral description, a working link, and no resources whose main purpose is non-consensual imagery, content involving minors, or evading laws.

## License

[CC0 1.0](LICENSE). To the extent possible under law, the contributors have waived all copyright to this list.

<p align="center"><sub>Found this useful? ⭐ Star the repo so other creators can find it.</sub></p>
