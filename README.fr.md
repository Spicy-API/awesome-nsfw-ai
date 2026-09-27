<!--
  Mots-clés : IA NSFW, générateur IA NSFW, générateur d'images IA sans censure, générateur de vidéo IA sans censure,
  générateur de vidéo IA NSFW, image en vidéo IA NSFW, éditeur d'images IA NSFW, IA sans censure, modèles IA sans filtre,
  IA pour adultes, LLM sans censure, API IA NSFW, meilleur générateur d'images IA NSFW 2026, wan 2.2 spicy, seedance spicy,
  skill IA NSFW, MCP NSFW, awesome nsfw ai, nsfw ai generator, uncensored ai image generator, uncensored ai video generator,
  nsfw ai video generator, nsfw image to video, nsfw ai image editor, uncensored llm, nsfw ai api, nsfw mcp
-->

<p align="center"><a href="README.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <b>Français</b> · <a href="README.es.md">Español</a></p>

<h1 align="center">Awesome NSFW AI</h1>

<p align="center">
  <b>Une sélection 2026 de générateurs d'images IA sans censure, de générateurs de vidéo IA NSFW, de modèles image en vidéo, d'éditeurs d'images, de LLM sans censure, d'API, de skills pour agents, de serveurs MCP et d'outils, pour les créateurs et développeurs de contenu pour adultes.</b>
</p>

<p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
  <img src="https://img.shields.io/badge/updated-2026--09--27-blue" alt="Mis à jour le 2026-09-27">
  <img src="https://img.shields.io/badge/18%2B-adults%20only-red" alt="Réservé aux adultes (18+)">
  <img src="https://img.shields.io/badge/license-CC0--1.0-lightgrey" alt="Licence CC0">
</p>

<p align="center">
  <img src="assets/wolf-turn-and-look-back.gif" width="24%" alt="Vidéo générée par Wan 2.2 Spicy à partir d'une image">
  <img src="assets/velvet-spiral-turn.gif" width="24%" alt="Vidéo générée par Seedance 2.0 Spicy à partir d'une image">
  <img src="assets/silk-draught-pull.gif" width="24%" alt="Vidéo générée par Wan 2.7 Spicy à partir d'une image">
  <img src="assets/hotel-window-turn.gif" width="24%" alt="Vidéo générée par Seedance 2.5 Spicy à partir d'une image">
  <br><sub>Résultats réels de Wan 2.2 Spicy, Seedance 2.0 Spicy, Wan 2.7 Spicy et Seedance 2.5 Spicy. D'autres exemples, avec les prompts exacts, dans <a href="https://github.com/Spicy-API/nsfw-ai-video-prompts/blob/main/README.fr.md#galerie-de-résultats-réels-avec-leurs-prompts">nsfw-ai-video-prompts</a>.</sub>
</p>

<p align="center">
  <a href="#générateurs-de-vidéo-ia-sans-censure">Vidéo</a> ·
  <a href="#générateurs-dimages-ia-sans-censure">Image</a> ·
  <a href="#éditeurs-dimages-ia-nsfw-et-outils-de-visage">Retouche</a> ·
  <a href="#llm-sans-censure-et-jeu-de-rôle">LLM</a> ·
  <a href="#api-dia-nsfw">API</a> ·
  <a href="#skills-pour-agents-et-serveurs-mcp">Skills &amp; MCP</a> ·
  <a href="#modèles-auto-hébergés-et-à-poids-ouverts">Auto-hébergé</a> ·
  <a href="#faq">FAQ</a>
</p>

> **Réservé aux plus de 18 ans.** Cette liste recense des outils capables de produire du contenu pour adultes. Chaque ressource doit être utilisée avec des adultes fictifs ou des adultes réels ayant donné un consentement documenté, et dans le respect de la loi du pays où vous vivez et de celui de votre public. Voir [Règles valables pour tous les outils](#règles-valables-pour-tous-les-outils).

> **Transparence :** cette liste est tenue par l'équipe de [SpicyAPI](https://spicyapi.ai/fr?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=disclosure-fr), une API facturée à l'usage pour des modèles d'image, de vidéo et de texte sans censure. Les entrées SpicyAPI sont marquées 🌶️. Les outils tiers figurent ici parce qu'ils sont utiles, pas parce qu'ils paient pour y être. Les pull requests qui ajoutent des concurrents sont les bienvenues.

---

## En bref : nos choix rapides

| Je veux… | Commencer par | Pourquoi |
|---|---|---|
| Faire du texte en vidéo ou placer mon personnage dans une nouvelle scène | [Seedance 2.5](https://spicyapi.ai/fr/models/seedance-2-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-fr) ou [Wan 3.0](https://spicyapi.ai/fr/models/wan-3-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-fr) | Modèles standard classés `unrestricted` dans le catalogue ; T2V, I2V et vidéo à partir de références |
| Faire une vidéo NSFW à partir d'une image fixe, pour pas cher | 🌶️ [Wan 2.2 Spicy](https://spicyapi.ai/fr/models/wan-2-2-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-fr) ou [LTX 2.3 Spicy](https://spicyapi.ai/fr/models/ltx-2-3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-fr) | À partir de $0.019 par seconde de vidéo en 480p |
| La meilleure qualité en image en vidéo sans censure | 🌶️ [Seedance 2.5 Spicy](https://spicyapi.ai/fr/models/seedance-2-5-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-fr) | Clips de 4 à 30 s, jusqu'à 1080p natif, audio en option |
| De la vidéo sans censure avec mes propres LoRA | 🌶️ [Wan 2.2 Spicy LoRA](https://spicyapi.ai/fr/models/wan-2-2-spicy-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-fr) | Jusqu'à trois LoRA par appel, plus l'extension de vidéo |
| Un modèle texte en image sans censure | [Qwen Image 2.1](https://spicyapi.ai/fr/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-fr) | À partir de $0.024 par image, prompts longs, 15 formats, retouche à partir d'images de référence |
| Des images fixes style anime / hentai | [Prefect Pony XL](https://spicyapi.ai/fr/models/prefect-pony-xl?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-fr) ou des checkpoints Pony / SDXL auto-hébergés | Prompts par tags, lignée anime |
| Un éditeur d'images IA sans censure | [Qwen Image 2.1 Edit](https://spicyapi.ai/fr/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-fr) ou 🌶️ [Qwen Image Edit Spicy](https://spicyapi.ai/fr/models/qwen-image-spicy-edit?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-fr) | 1 à 10 images de référence, ou une image + une instruction, sans masque |
| Tout faire tourner en local, gratuitement | [ComfyUI](https://github.com/Comfy-Org/ComfyUI) + poids ouverts [Wan 2.2](https://github.com/Wan-Video/Wan2.2) | Demande un GPU puissant (24 Go de VRAM, c'est confortable) |
| Laisser Claude Code / Cursor générer à ma place | [nsfw-ai-skill](https://github.com/Spicy-API/nsfw-ai-skill/blob/main/README.fr.md) ou le [serveur MCP officiel de SpicyAPI](https://docs.spicyapi.ai/docs/mcp?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) | Génération en langage naturel depuis votre agent |
| Des prompts qui marchent, prêts à copier-coller | [nsfw-ai-video-prompts](https://github.com/Spicy-API/nsfw-ai-video-prompts/blob/main/README.fr.md) | 116 prompts vidéo prêts à l'emploi et 130 résultats réels, chacun avec son prompt |

Les prix correspondent au palier le plus bas du catalogue public de SpicyAPI au 2026-09-27. Les résolutions plus élevées, l'audio et les clips plus longs coûtent plus cher ; vérifiez la page du modèle avant de lancer une génération.

---

## Sommaire

- [En bref : nos choix rapides](#en-bref--nos-choix-rapides)
- [IA NSFW et IA sans censure : ce que ces termes veulent dire](#ia-nsfw-et-ia-sans-censure--ce-que-ces-termes-veulent-dire)
- [Générateurs de vidéo IA sans censure](#générateurs-de-vidéo-ia-sans-censure)
  - [Tous les modèles vidéo sans censure, par popularité](#tous-les-modèles-vidéo-sans-censure-par-popularité)
  - [Combien coûte un clip NSFW de 5 secondes](#combien-coûte-un-clip-nsfw-de-5-secondes)
- [Générateurs d'images IA sans censure](#générateurs-dimages-ia-sans-censure)
- [Éditeurs d'images IA NSFW et outils de visage](#éditeurs-dimages-ia-nsfw-et-outils-de-visage)
- [LLM sans censure et jeu de rôle](#llm-sans-censure-et-jeu-de-rôle)
- [API d'IA NSFW](#api-dia-nsfw)
- [Skills pour agents et serveurs MCP](#skills-pour-agents-et-serveurs-mcp)
- [Modèles auto-hébergés et à poids ouverts](#modèles-auto-hébergés-et-à-poids-ouverts)
- [Interfaces locales et outils de workflow](#interfaces-locales-et-outils-de-workflow)
- [LoRA, checkpoints et entraînement](#lora-checkpoints-et-entraînement)
- [Upscaling, restauration et post-production](#upscaling-restauration-et-post-production)
- [Écrire des prompts pour du contenu adulte](#écrire-des-prompts-pour-du-contenu-adulte)
- [Comment choisir : guide de décision](#comment-choisir--guide-de-décision)
- [Règles valables pour tous les outils](#règles-valables-pour-tous-les-outils)
- [FAQ](#faq)
- [Dépôts associés](#dépôts-associés)
- [Contribuer](#contribuer)

---

## IA NSFW et IA sans censure : ce que ces termes veulent dire

On appelle **IA NSFW** tout modèle ou outil génératif capable de produire de la nudité ou du contenu sexuel pour adultes. **IA sans censure** est un terme plus large qui désigne les modèles qui ne refusent pas les prompts pour adultes et ne floutent pas leurs résultats.

Trois éléments déterminent si une requête NSFW passe, et on les confond sans arrêt :

1. **Le modèle.** Certains modèles ont été entraînés ou affinés pour autoriser le contenu adulte. D'autres ont été entraînés à le refuser, et aucun réglage de plateforme n'y change rien.
2. **Le filtre propre à la plateforme.** Beaucoup de services hébergés ajoutent une couche de modération par-dessus le modèle (listes de mots bloqués, classifieurs sur les résultats, floutage). Un modèle permissif derrière un filtre strict reste bloqué.
3. **Vos lois locales et les conditions de la plateforme.** « Le modèle sait le faire » ne veut pas dire « vous avez le droit de le faire ». Certains contenus sont illégaux partout (voir [les règles](#règles-valables-pour-tous-les-outils)).

Pour lire les listes ci-dessous :

| Étiquette | Signification |
|---|---|
| **Édition Spicy / NSFW** | Une version d'un modèle réglée ou configurée pour le contenu adulte. Sur SpicyAPI, ces modèles ont « Spicy » dans leur nom. |
| **Compatible contenu adulte** | Un modèle généraliste qui accepte souvent le contenu adulte mais peut adoucir ou refuser certaines demandes. |
| **Filtré** | Le modèle ou le fournisseur applique son propre filtre. Très bien pour du contenu SFW, peu fiable pour du NSFW. |

Sur SpicyAPI, chaque modèle du catalogue public porte un niveau de politique (`unrestricted`, `softened`, `borderline`, `filtered`), et les [classements](https://spicyapi.ai/fr/leaderboards?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=definitions-fr) publient un **Freedom Score** calculé à partir de prompts de test répétés. La plateforme n'ajoute pas son propre filtre par-dessus le modèle ; quand un filtrage existe, il vient du fournisseur du modèle.

---

## Générateurs de vidéo IA sans censure

L'image en vidéo (I2V) est la façon la plus fiable de faire une vidéo IA NSFW : vous contrôlez le rendu avec la première image et le modèle n'a plus qu'à l'animer. Le texte en vidéo (T2V) et la vidéo à partir de références (Ref2V, « placer le personnage de ces images dans une nouvelle scène ») passent par les modèles standard ci-dessous.

### Tous les modèles vidéo sans censure, par popularité

Même ordre que le catalogue SpicyAPI : les plus populaires d'abord, et au sein d'une famille, la version la plus récente d'abord. Les éditions 🌶️ **Spicy** sont réglées pour le contenu adulte. Les modèles **Standard** listés ici sont classés `unrestricted` dans le catalogue (le fournisseur n'applique aucun filtre), ils acceptent donc aussi les prompts pour adultes. Les prix indiqués sont ceux du palier le moins cher. Catalogue consulté le <!-- catalog:date -->
2026-09-27
<!-- /catalog:date -->

<!-- catalog:video -->
| Modèle | Type | Tâches | Durée | À partir de |
|---|---|---|---|---|
| [Seedance 2.5 Spicy](https://spicyapi.ai/fr/models/seedance-2-5-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | I2V | 4–30 s | $0.216/s |
| [Seedance 2.5](https://spicyapi.ai/fr/models/seedance-2-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, Ref2V, T2V | 4–30 s | $0.1234/s |
| [Seedance 2.0 Spicy](https://spicyapi.ai/fr/models/seedance-2-0-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | I2V | 4–15 s | $0.114/s |
| [Seedance 2.0](https://spicyapi.ai/fr/models/seedance-2-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, Ref2V, T2V | 4–15 s | $0.07/s |
| [Wan 3.0 Prime](https://spicyapi.ai/fr/models/wan-3-0-prime?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, Ref2V, T2V | 2–30 s | $0.0612/s |
| [Wan 3.0](https://spicyapi.ai/fr/models/wan-3-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, Ref2V, T2V | 2–30 s | $0.045/s |
| [MiniMax H3 Spicy](https://spicyapi.ai/fr/models/minimax-h3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | I2V | 3–15 s | $0.038/s |
| [MiniMax H3](https://spicyapi.ai/fr/models/minimax-h3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, Ref2V, T2V | 4–15 s | $0.025/s |
| [MiniMax H3 Singularity LoRA](https://spicyapi.ai/fr/models/minimax-h3-singularity-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, Ref2V | 3–15 s | $0.06/s |
| [LTX 2.5](https://spicyapi.ai/fr/models/ltx-2-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, T2V | 5–20 s | $0.09/s |
| [Wan 3.0 Pro Prime](https://spicyapi.ai/fr/models/wan-3-0-pro-prime?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, Ref2V, T2V | 2–30 s | $0.234/s |
| [Wan 3.0 Pro](https://spicyapi.ai/fr/models/wan-3-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, Ref2V, T2V | 2–30 s | $0.144/s |
| [MiniMax H3 LoRA](https://spicyapi.ai/fr/models/minimax-h3-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, Ref2V, T2V | 3–15 s | $0.05/s |
| [HappyHorse 1.1](https://spicyapi.ai/fr/models/happyhorse-1-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, Ref2V, T2V | 3–15 s | $0.14/s |
| [Seedance 2.0 Mini Spicy](https://spicyapi.ai/fr/models/seedance-2-0-mini-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | I2V | 4–15 s | $0.0387/s |
| [Seedance 2.0 Mini](https://spicyapi.ai/fr/models/seedance-2-0-mini?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, Ref2V, T2V | 4–15 s | $0.01097/s |
| [Wan 2.7 Spicy](https://spicyapi.ai/fr/models/wan-2-7-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | I2V | 2–15 s | $0.1235/s |
| [LTX 2.3 Spicy](https://spicyapi.ai/fr/models/ltx-2-3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | I2V | 3–20 s | $0.019/s |
| [LTX 2.3 Spicy LoRA](https://spicyapi.ai/fr/models/ltx-2-3-spicy-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | I2V | 3–20 s | $0.0285/s |
| [Seedance 2.0 Fast Spicy](https://spicyapi.ai/fr/models/seedance-2-0-fast-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | I2V | 4–15 s | $0.081/s |
| [Seedance 2.0 Fast](https://spicyapi.ai/fr/models/seedance-2-0-fast?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, Ref2V, T2V | 4–15 s | $0.02254/s |
| [Vidu Q3 Turbo](https://spicyapi.ai/fr/models/vidu-q3-turbo?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V | 1–16 s | $0.042/s |
| [Vidu Q3 Spicy](https://spicyapi.ai/fr/models/vidu-q3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | I2V | 1–16 s | $0.0665/s |
| [Vidu Q3](https://spicyapi.ai/fr/models/vidu-q3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V | 1–16 s | $0.07/s |
| [Vidu Q3 Pro](https://spicyapi.ai/fr/models/vidu-q3-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V | 1–16 s | $0.054/s |
| [Seedance 1.5 Pro Spicy](https://spicyapi.ai/fr/models/seedance-1-5-pro-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | I2V | 4–12 s | $0.012/s |
| [Seedance 1.5 Pro](https://spicyapi.ai/fr/models/seedance-1-5-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, T2V | 4–12 s | $0.0112/s |
| [Wan 2.6 Flash](https://spicyapi.ai/fr/models/wan-2-6-flash?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V | 5, 10, 15 s | $0.0225/s |
| [Wan 2.6 Spicy](https://spicyapi.ai/fr/models/wan-2-6-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | I2V | 5, 10, 15 s | $0.095/s |
| [Wan 2.6](https://spicyapi.ai/fr/models/wan-2-6?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, Ref2V, T2V | 5, 10, 15 s | $0.065/s |
| [Wan 2.5](https://spicyapi.ai/fr/models/wan-2-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, T2V | 5, 10 s | $0.045/s |
| [Wan 2.2 Spicy](https://spicyapi.ai/fr/models/wan-2-2-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | I2V | 5, 8 s | $0.019/s |
| [Wan 2.2 Spicy LoRA](https://spicyapi.ai/fr/models/wan-2-2-spicy-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | I2V, Extend | 5, 8 s | $0.024/s |
| [Wan 2.2 LoRA](https://spicyapi.ai/fr/models/wan-2-2-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V | 5, 8 s | $0.024/s |
<!-- /catalog:video -->

En résumé :

- **Meilleure qualité :** Seedance 2.5 Spicy (jusqu'à 30 s), puis Seedance 2.0 Spicy. Pour du texte en vidéo ou de la vidéo à partir de références à ce niveau de qualité, utilisez les versions standard Seedance 2.5 / Seedance 2.0.
- **Wan le plus récent :** Wan 3.0 (et ses paliers Prime / Pro) pour le T2V, l'I2V et le Ref2V jusqu'à 30 s ; Wan 2.7 Spicy et Wan 2.6 Spicy pour de l'image en vidéo réglée pour le contenu adulte.
- **Brouillons les moins chers :** Seedance 1.5 Pro Spicy à partir de $0.012/s, Wan 2.2 Spicy et LTX 2.3 Spicy à partir de $0.019/s.
- **Vos propres LoRA :** Wan 2.2 Spicy LoRA (avec `video-extend`), LTX 2.3 Spicy LoRA, MiniMax H3 LoRA.

Certains endpoints vidéo facturent par blocs entiers (par exemple, un clip de 6 secondes sur des blocs de 5 secondes est facturé 10 s) ; la page du modèle indique la durée du bloc, et le montant du devis est le maximum qui peut vous être facturé. Parcourez et filtrez tous les modèles sur [SpicyAPI › Modèles IA sans censure](https://spicyapi.ai/fr/explore/uncensored-ai-models?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=video-table-fr).

### Combien coûte un clip NSFW de 5 secondes

Palier le plus bas × 5 secondes, catalogue SpicyAPI au 2026-09-27. C'est un minimum, pas un devis.

| Modèle | 1 clip (5 s) | 100 clips | 1 000 clips |
|---|---|---|---|
| Seedance 1.5 Pro Spicy (480p, sans audio) | $0.06 | $6.00 | $60 |
| Wan 2.2 Spicy (480p) | $0.095 | $9.50 | $95 |
| LTX 2.3 Spicy (480p) | $0.095 | $9.50 | $95 |
| MiniMax H3 Spicy (480p) | $0.19 | $19.00 | $190 |
| Seedance 2.0 Mini Spicy (480p) | $0.19 | $19.35 | $193.50 |
| Wan 2.6 Spicy (720p) | $0.475 | $47.50 | $475 |
| Seedance 2.0 Spicy (480p) | $0.57 | $57.00 | $570 |
| Seedance 2.5 Spicy (480p) | $1.08 | $108.00 | $1,080 |

Wan 2.2 Spicy en 720p coûte $0.038/s, soit $0.19 pour un clip de 5 secondes en 720p. Les tâches échouées sont remboursées automatiquement.

---

## Générateurs d'images IA sans censure

**Notre recommandation : [Qwen Image 2.1](https://spicyapi.ai/fr/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-fr)** (classé `unrestricted` dans le catalogue, à partir de $0.024 l'image en 1k). Il suit des consignes longues (jusqu'à 5 000 caractères), génère 15 formats en 1k, 1,5k ou 2k, et retouche à partir de 1 à 10 images de référence dans la même famille. [Qwen Image 2.1 LoRA](https://spicyapi.ai/fr/models/qwen-image-2-1-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-fr) permet d'ajouter jusqu'à trois de vos propres LoRA pour garder un style ou un personnage constant.

Tous les modèles d'image sans censure, dans l'ordre du catalogue :

<!-- catalog:image -->
| Modèle | Type | Tâches | À partir de |
|---|---|---|---|
| [Qwen Image 2.1](https://spicyapi.ai/fr/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | Edit, T2I | $0.024/image |
| [Qwen Image 2.1 LoRA](https://spicyapi.ai/fr/models/qwen-image-2-1-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | Edit, T2I | $0.03/image |
| [MiniMax H3 Image LoRA](https://spicyapi.ai/fr/models/minimax-h3-image-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | Edit, T2I | $0.042/image |
| [Qwen Image 3.0 Pro](https://spicyapi.ai/fr/models/qwen-image-3-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | Edit, T2I | $0.04/image |
| [Qwen Image 3.0](https://spicyapi.ai/fr/models/qwen-image-3-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | Edit, T2I | $0.03/image |
| [Seedream 5.0 Pro](https://spicyapi.ai/fr/models/seedream-5-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | Edit, T2I | $0.036/image |
| [Qwen Image Edit Spicy](https://spicyapi.ai/fr/models/qwen-image-spicy-edit?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | Edit | $0.038/image |
| [Seedream 5.0 Lite](https://spicyapi.ai/fr/models/seedream-5-0-lite?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | Edit, T2I | $0.0345/image |
| [Qwen Image 2](https://spicyapi.ai/fr/models/alibaba-qwen-image-2?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | Edit, T2I | $0.035/image |
| [Qwen Image 2512 LoRA](https://spicyapi.ai/fr/models/qwen-image-2512-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | Edit, T2I | $0.03/image |
| [Z-Image Spicy Pro](https://spicyapi.ai/fr/models/z-image-spicy-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | T2I | $0.019/image |
| [Z-Image Spicy](https://spicyapi.ai/fr/models/z-image-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | T2I | $0.01235/image |
| [Z-Image](https://spicyapi.ai/fr/models/z-image?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | T2I | $0.01/image |
| [Z-Image Turbo LoRA](https://spicyapi.ai/fr/models/z-image-turbo-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | Edit, T2I | $0.012/image |
| [Seedream 4.0](https://spicyapi.ai/fr/models/seedream-4-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | Edit, T2I | $0.03/image |
| [Prefect Pony XL](https://spicyapi.ai/fr/models/prefect-pony-xl?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | T2I | $0.015/image |
| [FLUX.1 Dev LoRA](https://spicyapi.ai/fr/models/flux-1-dev-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | T2I | $0.018/image |
<!-- /catalog:image -->

Option sans code : le [générateur d'images IA sans censure de SpicyAPI Studio](https://spicyapi.ai/fr/create/uncensored-ai-image-generator?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-studio-fr) fait tourner les mêmes modèles dans le navigateur, avec des styles, des formats et le prix affiché avant chaque génération.

Pour un comparatif direct de ce que chaque modèle d'image autorise, lisez [Less-restrictive image model evaluation](https://spicyapi.ai/fr/blog/less-restrictive-model-evaluation?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-eval-fr).

---

## Éditeurs d'images IA NSFW et outils de visage

| Outil | Ce qu'il fait | À partir de |
|---|---|---|
| [Qwen Image 2.1 Edit](https://spicyapi.ai/fr/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-fr) | Retouche sans censure à partir de 1 à 10 images de référence d'un sujet **fictif** ou consentant : tenue, pose, décor, éclairage (classé `unrestricted` dans le catalogue) | $0.036 / image |
| 🌶️ [Qwen Image Edit Spicy](https://spicyapi.ai/fr/models/qwen-image-spicy-edit?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-fr) | Retouche sans censure par instruction : changer la tenue, la pose, le décor ou l'éclairage d'un sujet **fictif** ou consentant | $0.038 / image |
| [Image Expander](https://spicyapi.ai/fr/models/image-expander-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-fr) | Étendre l'image (outpainting) vers un cadre plus large ou plus haut | $0.024 / image |
| [Object Eraser](https://spicyapi.ai/fr/models/object-eraser-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-fr) | Supprimer des objets, logos ou filigranes qui vous appartiennent | $0.03 / image |
| [Image Upscaler](https://spicyapi.ai/fr/models/image-upscaler-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-fr) / [Video Upscaler](https://spicyapi.ai/fr/models/video-upscaler-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-fr) | Rendre plus net et agrandir un résultat final | $0.012 / image, $0.006 / s |
| [Face Swap](https://spicyapi.ai/fr/models/face-swap-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-fr), [Head Swap](https://spicyapi.ai/fr/models/head-swap-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-fr), [Video Character Swap](https://spicyapi.ai/fr/models/character-swap-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-fr) | Garder un même personnage **fictif** cohérent d'une image et d'un clip à l'autre | $0.013 / image, vidéo à partir de $0.064 / s |
| [Lip Sync](https://spicyapi.ai/fr/models/lip-sync-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-fr), [Talking Avatar](https://spicyapi.ai/fr/models/talking-avatar-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-fr), [Video Sound Effects](https://spicyapi.ai/fr/models/foley-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-fr) | Voix et son pour personnages IA | à partir de $0.0012 / s |

> ⚠️ Les outils d'échange de visage ou de tête ne doivent **jamais** servir à placer une personne réelle dans un contenu sexuel sans son consentement documenté, et « déshabiller » ou « dénuder » la photo d'une personne réelle est interdit sur toutes les plateformes sérieuses. Être une célébrité ou avoir des photos publiques ne vaut pas consentement. Utilisez ces outils pour des personnages fictifs que vous avez créés, ou pour vous-même.

Équivalents auto-hébergés : [IP-Adapter](https://github.com/tencent-ailab/IP-Adapter), [InstantID](https://github.com/instantX-research/InstantID) et [PhotoMaker](https://github.com/TencentARC/PhotoMaker) pour la cohérence des personnages ; [ControlNet](https://github.com/lllyasviel/ControlNet) pour le contrôle de la pose.

---

## LLM sans censure et jeu de rôle

Les modèles de texte comptent à trois endroits pour le NSFW : la fiction érotique et les histoires interactives, les applis de compagnon virtuel et de jeu de rôle, et **l'écriture de meilleurs prompts image et vidéo** (un LLM transforme une idée d'une ligne en prompt détaillé qui décrit la caméra).

### Hébergés (compatibles OpenAI)

SpicyAPI sert des modèles de texte via des endpoints compatibles OpenAI, Anthropic et Gemini à l'adresse `https://api.spicyapi.ai` : les SDK existants fonctionnent en changeant simplement l'URL de base. Parmi les modèles classés `unrestricted` dans le catalogue au 2026-09-27 :

| Modèle | À partir de (pour 1K tokens) | Idéal pour |
|---|---|---|
| [Grok 4.7](https://spicyapi.ai/fr/models/grok-4-7?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-fr) | $0.0036 | Écriture créative, jeu de rôle avec de la personnalité |
| [DeepSeek V4 Pro](https://spicyapi.ai/fr/models/deepseek-v4-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-fr) | $0.00396 | Fiction longue, raisonnement |
| [DeepSeek V4.1 Flash](https://spicyapi.ai/fr/models/deepseek-v4-1-flash?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-fr) | $0.0012 | Chat à gros volume, enrichissement de prompts |
| [GLM 5.3 Flash](https://spicyapi.ai/fr/models/glm-5-3-flash?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-fr) | $0.000425 | Le chat le moins cher du catalogue |
| [Kimi K3](https://spicyapi.ai/fr/models/kimi-k3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-fr) | $0.0135 | Histoires à long contexte |

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

### En local et auto-hébergé

- [Ollama](https://github.com/ollama/ollama) et [LM Studio](https://lmstudio.ai) font tourner des modèles à poids ouverts sur votre propre machine ; cherchez dans leurs bibliothèques les fine-tunes communautaires « abliterated » ou « uncensored ».
- [KoboldCpp](https://github.com/LostRuins/koboldcpp) : lanceur GGUF en un seul fichier, pensé pour la narration.
- [text-generation-webui](https://github.com/oobabooga/textgen) : interface de chat locale complète, avec extensions.
- [SillyTavern](https://github.com/SillyTavern/SillyTavern) : l'interface de référence pour le jeu de rôle. Connectez-la à un backend local ou à n'importe quelle API compatible OpenAI, dont SpicyAPI.

---

## API d'IA NSFW

Pour les développeurs qui créent des applis pour adultes, la question n'est pas seulement « quel modèle », mais « quel fournisseur me laisse l'appeler sans bloquer mes requêtes, et me facture honnêtement ».

| Ce qu'il faut vérifier | Pourquoi c'est important | SpicyAPI |
|---|---|---|
| La plateforme ajoute-t-elle son propre filtre ? | Un second filtre bloque des prompts que le modèle accepterait | Pas de filtre de plateforme ; la politique du fournisseur du modèle s'applique toujours |
| Unité de facturation | Les crédits et abonnements masquent le coût réel | Solde en USD, à l'image / à la seconde / au token, sans abonnement, le solde n'expire jamais |
| Générations échouées | Certains fournisseurs facturent les refus | Les tâches échouées sont remboursées automatiquement |
| Moyens de paiement | Les entreprises pour adultes perdent souvent l'accès au paiement par carte | Visa, Mastercard, Amex, JCB, Apple Pay, Google Pay et crypto (BTC, ETH, USDT) |
| Maîtrise du budget | Une clé qui fuite peut vider un solde | Plafonds par clé (quotidien / mensuel / total), liste de modèles autorisés, liste d'IP autorisées |
| Conservation des données | Les contenus adultes envoyés sont sensibles | Durées de conservation distinctes pour les prompts, les fichiers envoyés et les résultats ; vous pouvez les raccourcir ou détruire le contenu d'une tâche |
| Intégration | Vous ne voulez pas un client sur mesure par modèle | Une API de tâches asynchrones, des SDK (TypeScript, Python, Go, PHP, Java), une CLI, un serveur MCP, une skill pour agents |

### Démarrage rapide : image en vidéo NSFW via HTTP

```bash
export SPICY_API_KEY="sk-spicy-..."   # à créer sur https://spicyapi.ai/fr/console

# 1) créer la tâche
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

# 2) interroger jusqu'à ce que state vaille "succeeded", puis lire data.output.assets[0].url
curl -s "https://api.spicyapi.ai/api/v1/jobs/recordInfo?taskId=TASK_ID" \
  -H "Authorization: Bearer $SPICY_API_KEY"
```

Les champs d'entrée varient selon le modèle. Lisez le schéma en direct avec `GET /api/v1/models/{model}` (ou sur la page du modèle) avant d'envoyer une requête. Référence complète : [docs.spicyapi.ai](https://docs.spicyapi.ai/docs?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=api-quickstart).

### Autres fournisseurs

Les politiques changent souvent et sont appliquées différemment selon les modèles : testez avec vos propres prompts avant de vous engager. Lisez toujours la politique d'utilisation en vigueur du fournisseur.

- [Venice.ai](https://venice.ai) : chat et génération d'images privés et sans censure, avec une API.
- [fal.ai](https://fal.ai), [WaveSpeed](https://wavespeed.ai), [Replicate](https://replicate.com) : grands catalogues de modèles hébergés ; le traitement du NSFW varie selon le modèle et les réglages du compte.
- [RunPod](https://www.runpod.io), [Vast.ai](https://vast.ai) : location de GPU pour faire tourner vous-même des modèles à poids ouverts (voir [auto-hébergé](#modèles-auto-hébergés-et-à-poids-ouverts)).

---

## Skills pour agents et serveurs MCP

Les agents de code IA (Claude Code, Cursor, Codex, Windsurf, Cline, Gemini CLI, OpenClaw) peuvent désormais générer des médias pour vous grâce aux **skills** et aux **serveurs MCP**. Demandez en langage courant (« fais un clip boudoir de 5 secondes à partir de cette image ») et l'agent choisit le modèle, construit la requête et télécharge le résultat.

| Ressource | Type | Installation |
|---|---|---|
| 🌶️ [nsfw-ai-skill](https://github.com/Spicy-API/nsfw-ai-skill/blob/main/README.fr.md) | Skill pour agents : génération d'images, de vidéos, de retouches et de texte NSFW, enrichissement de prompts, estimation des coûts | `npx skills add Spicy-API/nsfw-ai-skill` |
| 🌶️ [Serveur MCP SpicyAPI](https://docs.spicyapi.ai/docs/mcp?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=skills-table) (`@spicyapi/mcp`) | MCP : lister les modèles, obtenir un devis, créer / attendre / relancer des tâches, envoyer des fichiers | `claude mcp add spicyapi -e SPICY_API_KEY=$SPICY_API_KEY -- npx --yes --package=@spicyapi/mcp spicyapi-mcp` |
| 🌶️ [Skill officielle SpicyAPI](https://github.com/Spicy-API/spicy-skill) | Skill pour agents couvrant toutes les fonctions développeur de SpicyAPI | `npx skills add Spicy-API/spicy-skill` |
| 🌶️ [CLI SpicyAPI](https://docs.spicyapi.ai/docs?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=skills-table) (`@spicyapi/cli`) | Ligne de commande : modèles, devis, tâches, envois de fichiers | `npx @spicyapi/cli --help` |
| [anthropics/skills](https://github.com/anthropics/skills) | Skills de référence et format des skills | — |
| [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) | Annuaire de serveurs MCP | — |

---

## Modèles auto-hébergés et à poids ouverts

Gratuits à faire tourner, contrôle total, aucun filtre de plateforme. La contrepartie : le matériel, le temps d'installation et les licences (lisez chaque licence avant un usage commercial).

### Vidéo

- [Wan 2.2](https://github.com/Wan-Video/Wan2.2) et [Wan 2.1](https://github.com/Wan-Video/Wan2.1) : les modèles vidéo ouverts d'Alibaba (Apache-2.0). Énorme écosystème de LoRA communautaires ; la base des éditions Wan Spicy hébergées.
- [HunyuanVideo](https://github.com/Tencent-Hunyuan/HunyuanVideo) : le modèle vidéo ouvert de Tencent.
- [LTX-Video](https://github.com/Lightricks/LTX-Video) et [LTX-2](https://github.com/Lightricks/LTX-2) : les modèles vidéo ouverts et rapides de Lightricks.
- [CogVideoX](https://github.com/zai-org/CogVideo) : le modèle vidéo ouvert de Zhipu.
- [Mochi 1](https://github.com/genmoai/mochi) : le modèle vidéo ouvert de Genmo.
- [ComfyUI-WanVideoWrapper](https://github.com/kijai/ComfyUI-WanVideoWrapper) : les nœuds ComfyUI de référence pour Wan, avec prise en charge des LoRA.

### Image

- [Qwen-Image](https://github.com/QwenLM/Qwen-Image) : génération et retouche d'images en open source.
- [Z-Image](https://github.com/Tongyi-MAI/Z-Image) : le modèle d'image ouvert et efficace d'Alibaba Tongyi.
- [FLUX.1](https://github.com/black-forest-labs/flux) : vérifiez la licence de chaque variante (dev n'est pas utilisable commercialement).
- Checkpoints SDXL / Pony Diffusion / Illustrious sur [Civitai](https://civitai.com) et [Hugging Face](https://huggingface.co) : le plus grand choix de checkpoints communautaires affinés pour le NSFW.

**Matériel, en gros :** les modèles d'image tournent avec 8 à 12 Go de VRAM ; les modèles vidéo demandent 16 à 24 Go (ou des versions quantifiées, de moindre qualité). Sans GPU, louez-en un sur RunPod ou Vast.ai, ou utilisez une API hébergée.

---

## Interfaces locales et outils de workflow

- [ComfyUI](https://github.com/Comfy-Org/ComfyUI) : workflows à base de nœuds pour l'image et la vidéo ; l'option la plus flexible.
- [Stable Diffusion WebUI (A1111)](https://github.com/AUTOMATIC1111/stable-diffusion-webui) : l'interface classique, avec un énorme écosystème d'extensions.
- [Forge](https://github.com/lllyasviel/stable-diffusion-webui-forge) : fork d'A1111 plus rapide et moins gourmand en VRAM.
- [InvokeAI](https://github.com/invoke-ai/InvokeAI) : interface soignée, organisée autour d'un canevas.
- [Fooocus](https://github.com/lllyasviel/Fooocus) : l'interface SDXL locale la plus simple.
- 🌶️ [SpicyAPI Studio](https://spicyapi.ai/fr/create?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=interfaces-fr) : studio d'image et de vidéo dans le navigateur, avec modèles prêts à l'emploi, [effets](https://spicyapi.ai/fr/create/effects?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=interfaces-fr) et [styles](https://spicyapi.ai/fr/create/styles?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=interfaces-fr) ; aucun GPU nécessaire.

---

## LoRA, checkpoints et entraînement

**Où trouver des LoRA NSFW**

- [Civitai](https://civitai.com) : la plus grande bibliothèque ; filtrez par modèle de base (Wan 2.2, SDXL, Pony, Flux) et activez le contenu adulte dans les réglages de votre compte.
- [Hugging Face](https://huggingface.co) : beaucoup de LoRA et de fine-tunes complets ; vérifiez la licence sur la fiche de chaque modèle.
- [Tensor.Art](https://tensor.art) : partage de modèles avec exécution en ligne.

**Utiliser des LoRA via une API.** Wan 2.2 Spicy LoRA accepte `loras`, `high_noise_loras` et `low_noise_loras` (jusqu'à trois). Les LoRA « high-noise » façonnent la composition et le mouvement au début du débruitage ; les LoRA « low-noise » façonnent la texture et les détails à la fin. Chaque LoRA est un objet avec un `path` direct vers le fichier de poids et un `scale` (0–4, 1 par défaut) ; changez un seul LoRA à la fois. Consultez la [page Wan 2.2 Spicy LoRA](https://spicyapi.ai/fr/models/wan-2-2-spicy-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=lora-fr) pour le schéma exact.

**Entraîner vos propres LoRA**

- [kohya_ss](https://github.com/bmaltais/kohya_ss) : l'outil standard pour entraîner des LoRA SD / SDXL.
- [OneTrainer](https://github.com/Nerogar/OneTrainer) : LoRA et fine-tuning complet, avec interface graphique.
- [ai-toolkit](https://github.com/ostris/ai-toolkit) : entraînement pour Flux, Wan et les modèles récents.

N'entraînez que sur des images qui vous appartiennent ou dont vous détenez les droits, et uniquement sur des adultes.

---

## Upscaling, restauration et post-production

- [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN) : upscaling ×4 d'images et de vidéos.
- [GFPGAN](https://github.com/TencentARC/GFPGAN) et [CodeFormer](https://github.com/sczhou/CodeFormer) : restauration des visages.
- [RIFE](https://github.com/hzwer/ECCV2022-RIFE) : interpolation d'images pour un ralenti plus fluide.
- [FFmpeg](https://ffmpeg.org) : couper, assembler, ajouter du son (`ffmpeg -i clip.mp4 -i track.mp3 -c:v copy -shortest out.mp4`).
- [Topaz Video AI](https://www.topazlabs.com) : upscaler vidéo commercial.

---

## Écrire des prompts pour du contenu adulte

Un bon prompt NSFW se lit comme une liste de plans, pas comme une liste d'adjectifs. Les modèles comprennent mieux l'anglais : les exemples ci-dessous restent donc en anglais.

```
[Subject: adult, age range, look] + [Wardrobe or state] + [Action: one clear motion]
+ [Setting] + [Lighting] + [Camera] + [Style / quality]
```

Exemple (image en vidéo) :

```
A woman in her early 30s in a black silk slip dress sits on the edge of a hotel bed.
She slowly slides one strap off her shoulder and looks up at the camera.
Warm tungsten bedside lamp, soft shadows, city lights through the window.
Slow push-in from medium shot to close-up, shallow depth of field, 35mm film look.
```

Ce qui fait la différence :

1. **Une seule action principale par clip.** La respiration, les cheveux qui bougent, une rotation lente et le mouvement du tissu sont fiables ; les chorégraphies complexes et les interactions à deux cassent en premier.
2. **Décrivez la caméra.** « Slow push-in », « static camera », « orbit left » valent mieux que « cinematic ».
3. **Nommez la lumière.** Bougie, lumière de fenêtre, contre-jour néon, heure dorée.
4. **Laissez la première image porter le rendu.** En image en vidéo, ne redécrivez pas tout ce qui est visible ; décrivez ce qui *change*.
5. **Gardez des clips courts.** 5 secondes, c'est le bon compromis pour la cohérence anatomique ; prolongez avec un second appel si besoin.
6. **Indiquez toujours un âge adulte** (« in her 30s », « adult man in his 40s ») et évitez tout descripteur qui suggère la jeunesse.

Plus de 100 prompts testés, des prompts négatifs et un aide-mémoire caméra/lumière sont dans **[nsfw-ai-video-prompts](https://github.com/Spicy-API/nsfw-ai-video-prompts/blob/main/README.fr.md)**.

---

## Comment choisir : guide de décision

```
Vous avez un GPU avec 16 Go+ de VRAM et du temps pour bidouiller ?
├── Oui → ComfyUI + poids ouverts Wan 2.2 / Qwen-Image / Z-Image + LoRA Civitai (gratuit, contrôle maximal)
└── Non
    ├── Sans code, dans le navigateur → SpicyAPI Studio (générateur d'images et de vidéos sans censure)
    └── Avec du code ou un agent IA
        ├── Volume à petit budget → Wan 2.2 Spicy / LTX 2.3 Spicy ($0.019/s en 480p)
        ├── Meilleure qualité     → Seedance 2.5 Spicy ou Seedance 2.0 Spicy
        ├── Texte en vidéo        → Seedance 2.5 ou Wan 3.0 (standard, unrestricted)
        ├── Images fixes          → Qwen Image 2.1 (Qwen Image 2.1 LoRA pour votre propre style)
        ├── Styles personnalisés  → Wan 2.2 Spicy LoRA / LTX 2.3 Spicy LoRA
        ├── Anime                 → Prefect Pony XL (images) → Vidu Q3 Spicy (mouvement)
        └── Depuis Claude Code / Cursor → nsfw-ai-skill ou le serveur MCP SpicyAPI
```

**Par cas d'usage**

| Cas d'usage | Combinaison recommandée |
|---|---|
| Site d'abonnement pour adultes / contenu de créateur | Qwen Image 2.1 pour les images → Seedance 2.0 Spicy ou Wan 2.6 Spicy pour les clips → Video Upscaler |
| Appli de compagnon IA ou de jeu de rôle | Grok 4.7 ou DeepSeek V4 pour le chat → Qwen Image 2.1 pour les selfies → MiniMax H3 Spicy pour de courtes animations |
| Amateur, beaucoup d'essais | Wan 2.2 Spicy en 480p, itérer, puis refaire les meilleurs en 720p |
| Contenu style anime / hentai | Prefect Pony XL → Vidu Q3 Spicy ou Wan 2.2 Spicy LoRA avec un LoRA anime |
| Fiction érotique et histoires interactives | Grok 4.7 / Kimi K3 pour le texte, Qwen Image 2.1 pour les illustrations |

---

## Règles valables pour tous les outils

Ces règles ne sont pas facultatives et aucun réglage ne les lève :

- **Jamais de mineurs.** Aucun contenu sexuel représentant une personne de moins de 18 ans ou qui *paraît* avoir moins de 18 ans, quel que soit le style, y compris l'anime, l'illustration et les prétextes d'« âge fictif ».
- **Pas de personnes réelles sans consentement documenté.** Pas de deepfakes sexuels, pas d'échange de visage ou de tête d'une personne réelle dans un contenu sexuel, pas de photos « déshabillées » ou « dénudées ». Les personnalités publiques ne font pas exception.
- **Pas d'usurpation d'identité, de harcèlement, d'extorsion ni de fausses preuves** à partir de l'image de qui que ce soit.
- **Respectez la loi de votre pays et celle de votre public.** Certains pays restreignent certains contenus fictifs, voire tout contenu pour adultes.
- **Signalez le contenu généré par IA** lorsque les plateformes ou la loi l'exigent, et conservez les preuves de consentement de toute personne réelle que vous représentez.

Règles complètes de SpicyAPI : [Politique de contenu](https://spicyapi.ai/fr/legal/content-policy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=rules-fr) et [Politique d’utilisation acceptable](https://spicyapi.ai/fr/legal/acceptable-use?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=rules-fr).

---

## FAQ

### Quel est le meilleur générateur de vidéo IA NSFW en 2026 ?
Pour la qualité, **Seedance 2.5 Spicy** (4 à 30 s, jusqu'à 1080p natif) et **Seedance 2.0 Spicy** sont en tête des éditions Spicy en image en vidéo ; pour le texte en vidéo, prenez les versions standard **Seedance 2.5** ou **Wan 3.0**, toutes deux `unrestricted` dans le catalogue. Pour le prix, **Wan 2.2 Spicy** et **LTX 2.3 Spicy** démarrent à $0.019 la seconde. Pour des styles personnalisés, utilisez **Wan 2.2 Spicy LoRA**. Tous sont disponibles via une seule API sur [SpicyAPI](https://spicyapi.ai/fr?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=faq-fr).

### Quel est le meilleur générateur d'images IA sans censure ?
En hébergé : **Qwen Image 2.1** (à partir de $0.024/image, classé `unrestricted` dans le catalogue) pour le photoréalisme et l'éditorial, avec **Qwen Image 2.1 LoRA** pour vos propres styles ; **Z-Image Spicy** (à partir de $0.01235/image) pour le volume au meilleur prix ; **Prefect Pony XL** pour l'anime. En auto-hébergé : les checkpoints communautaires SDXL, Pony et Illustrious dans ComfyUI ou Forge.

### Comment transformer une image en vidéo NSFW ?
Générez ou choisissez une première image (un adulte fictif, ou vous-même), puis envoyez-la à un modèle image en vidéo NSFW comme Wan 2.2 Spicy avec un prompt court qui décrit le mouvement et la caméra. Voir le [démarrage rapide de l'API](#démarrage-rapide--image-en-vidéo-nsfw-via-http) ou utilisez l'[outil image en vidéo](https://spicyapi.ai/fr/create/image-to-video?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=faq-fr) dans le navigateur.

### Existe-t-il un générateur IA NSFW gratuit ?
Faire tourner des modèles à poids ouverts en local (ComfyUI + Wan 2.2, Qwen-Image ou Z-Image) est gratuit, hors matériel et électricité. Les services hébergés sont payants parce que les GPU coûtent cher ; SpicyAPI n'a pas d'abonnement et facture au résultat, avec remboursement des tâches échouées.

### Quelle est l'API vidéo IA NSFW la moins chère ?
Dans le catalogue SpicyAPI (2026-09-27), le prix à la seconde le plus bas pour un modèle vidéo Spicy est celui de **Seedance 1.5 Pro Spicy à $0.012/s** (480p, sans audio), suivi de **Wan 2.2 Spicy** et **LTX 2.3 Spicy à $0.019/s** (480p).

### La génération de contenu NSFW par IA est-elle légale ?
Générer du contenu sexuel mettant en scène des **adultes fictifs** est légal dans la plupart des pays, mais les lois varient et certains contenus sont illégaux partout : tout ce qui implique des mineurs, et le contenu sexuel de personnes réelles réalisé sans leur consentement. Vous êtes responsable de ce que vous créez et partagez. Ceci n'est pas un conseil juridique.

### Quelle différence entre les modèles « sans censure » et « Spicy » ?
« Sans censure » désigne en général une plateforme ou un modèle qui ne refuse pas les prompts pour adultes. Sur SpicyAPI, les éditions « Spicy » sont des versions précises de modèles réglées pour le contenu adulte ; les modèles standard sont listés avec leur propre niveau de politique, pour que vous voyiez lesquels adoucissent ou filtrent le contenu.

### Peut-on utiliser l'IA NSFW dans Claude Code, Cursor ou d'autres agents ?
Oui. Installez [nsfw-ai-skill](https://github.com/Spicy-API/nsfw-ai-skill/blob/main/README.fr.md) (`npx skills add Spicy-API/nsfw-ai-skill`) ou ajoutez le serveur MCP SpicyAPI, définissez `SPICY_API_KEY`, puis demandez à l'agent en langage naturel.

---

## Dépôts associés

- **[nsfw-ai-video-prompts](https://github.com/Spicy-API/nsfw-ai-video-prompts/blob/main/README.fr.md)** : plus de 100 prompts vidéo NSFW, des prompts pour images de référence, des prompts négatifs et des conseils par modèle.
- **[nsfw-ai-skill](https://github.com/Spicy-API/nsfw-ai-skill/blob/main/README.fr.md)** : skill pour agents qui génère images, vidéos et textes NSFW depuis Claude Code, Cursor, Codex et d'autres.
- **[spicy-skill](https://github.com/Spicy-API/spicy-skill)** · **[spicy-mcp](https://github.com/Spicy-API/spicy-mcp)** · **[spicy-sdk](https://github.com/Spicy-API/spicy-sdk)** : outils développeur officiels de SpicyAPI.

## Contribuer

Les ajouts sont les bienvenus, concurrents compris. Lisez d'abord [CONTRIBUTING.md](CONTRIBUTING.md). En bref : une ressource par pull request, une description neutre d'une ligne, un lien qui fonctionne, et aucune ressource dont l'objet principal est l'imagerie non consentie, le contenu impliquant des mineurs ou le contournement de la loi.

## Licence

[CC0 1.0](LICENSE). Dans la mesure permise par la loi, les contributeurs ont renoncé à tout droit d'auteur sur cette liste.

<p align="center"><sub>Cette liste vous a été utile ? ⭐ Mettez une étoile au dépôt pour que d'autres créateurs la trouvent.</sub></p>
