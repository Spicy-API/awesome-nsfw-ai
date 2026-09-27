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

| Je veux… | Commencer par | Pourquoi (classement SpicyAPI, 2026-09-27) |
|---|---|---|
| Le meilleur modèle vidéo NSFW polyvalent | [Wan 3.0](https://spicyapi.ai/fr/models/wan-3-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-fr) | Spicy Index 76.5 (n° 2 sur 37), Freedom 96 ; tous les prompts de test explicites rendus (9/9) ; T2V, I2V et vidéo à partir de références jusqu'à 30 s ; $0.45 les 5 s en 720p |
| De la vidéo NSFW avec mon propre style ou personnage | [MiniMax H3 LoRA](https://spicyapi.ai/fr/models/minimax-h3-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-fr) ou [MiniMax H3 Singularity LoRA](https://spicyapi.ai/fr/models/minimax-h3-singularity-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-fr) | Spicy Index 75.2 / 72.8, Freedom 98.3 / 100 |
| De l'image en vidéo explicite avec une édition Spicy | 🌶️ [Seedance 2.5 Spicy](https://spicyapi.ai/fr/models/seedance-2-5-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-fr), 🌶️ [Wan 2.7 Spicy](https://spicyapi.ai/fr/models/wan-2-7-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-fr) ou 🌶️ [Vidu Q3 Spicy](https://spicyapi.ai/fr/models/vidu-q3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-fr) | Freedom 96.7–100, tous les prompts de test explicites rendus (3/3) |
| De la vidéo NSFW pas chère, en volume | [Wan 2.6 Flash](https://spicyapi.ai/fr/models/wan-2-6-flash?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-fr) ou 🌶️ [Seedance 1.5 Pro Spicy](https://spicyapi.ai/fr/models/seedance-1-5-pro-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-fr) | Freedom 100 / 96.7 pour $0.11–0.13 les 5 s (720p) |
| Un modèle texte en image sans censure | [Qwen Image 2.1](https://spicyapi.ai/fr/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-fr) | Spicy Index 73, Freedom 96.3, à partir de $0.024 par image ; prompts longs, 15 formats |
| Des images dans mon propre style (anime compris) | [Qwen Image 2.1 LoRA](https://spicyapi.ai/fr/models/qwen-image-2-1-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-fr) ou [MiniMax H3 Image LoRA](https://spicyapi.ai/fr/models/minimax-h3-image-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-fr) | N° 1 et n° 2 du Spicy Index image (80.5 / 74.5), Freedom 92 / 100 |
| Un éditeur d'images IA sans censure | [Qwen Image 2.1 Edit](https://spicyapi.ai/fr/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-fr) | Même famille que ci-dessus ; 1 à 10 images de référence + une instruction, sans masque |
| Du chat, du jeu de rôle ou de l'écriture de prompts sans censure | [Grok 4.7](https://spicyapi.ai/fr/models/grok-4-7?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-fr) ou [Grok 4.3](https://spicyapi.ai/fr/models/grok-4-3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-fr) | Freedom 100 / 98.9 au classement texte ; Grok 4.3 est le plus rapide (≈4 s en médiane) |
| Tout faire tourner en local, gratuitement | [ComfyUI](https://github.com/Comfy-Org/ComfyUI) + poids ouverts [Wan 2.2](https://github.com/Wan-Video/Wan2.2) | Demande un GPU puissant (24 Go de VRAM, c'est confortable) |
| Laisser Claude Code / Cursor générer à ma place | [nsfw-ai-skill](https://github.com/Spicy-API/nsfw-ai-skill/blob/main/README.fr.md) ou le [serveur MCP officiel de SpicyAPI](https://docs.spicyapi.ai/docs/mcp?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) | Génération en langage naturel depuis votre agent |
| Des prompts qui marchent, prêts à copier-coller | [nsfw-ai-video-prompts](https://github.com/Spicy-API/nsfw-ai-video-prompts/blob/main/README.fr.md) | 116 prompts vidéo prêts à l'emploi et 130 résultats réels, chacun avec son prompt |

Les scores proviennent des [classements publics de SpicyAPI](https://spicyapi.ai/fr/leaderboards?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-fr) (méthodologie v2.1, tests du 2026-09-14 au 2026-09-27 ; voir [comment les modèles sont classés](#comment-les-modèles-sont-classés-ici)). Les prix correspondent au palier indiqué dans le catalogue ; les résolutions plus élevées, l'audio et les clips plus longs coûtent plus cher.

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

### Comment les modèles sont classés ici

Les recommandations de cette liste s'appuient sur les résultats de tests publiés par SpicyAPI, pas sur des arguments marketing :

- **Freedom Score (0–100)** : la fiabilité avec laquelle un modèle rend ce que demande un prompt pour adultes, sur cinq niveaux : L1 suggestif, L2 nudité partielle, L3 nudité, L4 explicite, L5 extrême (BDSM / gore). Chaque niveau vaut 20 points × taux de réussite × confiance, si bien que les résultats adoucis ou remplacés font perdre des points. ✅ 90+ · ◐ 70–89 · ⚠️ moins de 70 · 🧪 moins de 15 tests à ce jour : un score bas traduit alors un manque de couverture plutôt que des refus.
- **Spicy Index (0–100)** : pour l'instant *préliminaire* ; c'est un score de capacités calculé à partir des spécifications publiques (résolution native, durée maximale des clips, audio, entrées, etc.). Les votes de qualité de l'arène ne sont pas encore pris en compte : il ne mesure donc pas encore la qualité visuelle.
- **Vérifications techniques par route** : avant qu'un modèle soit listé, l'équipe génère des cas de test explicites sur chaque route amont et inspecte le résultat téléchargé image par image (un statut « succès » ne suffit pas, car certains fournisseurs remplacent discrètement le résultat par une image sans risque). Les modèles qui ne rendent du contenu explicite que sur certaines routes ne sont pas recommandés ici.

Rapports complets par modèle, avec le nombre de tests par niveau : [classements SpicyAPI](https://spicyapi.ai/fr/leaderboards?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=method-fr). Les résultats de test des niveaux L4/L5 ne sont jamais publiés.

---

## Générateurs de vidéo IA sans censure

L'image en vidéo (I2V) est la façon la plus fiable de faire une vidéo IA NSFW : vous contrôlez le rendu avec la première image et le modèle n'a plus qu'à l'animer. Le texte en vidéo (T2V) et la vidéo à partir de références (Ref2V, « placer le personnage de ces images dans une nouvelle scène ») passent par les modèles standard ci-dessous.

### Tous les modèles vidéo sans censure, par popularité

Même ordre que le catalogue SpicyAPI : les plus populaires d'abord, et au sein d'une famille, la version la plus récente d'abord. Les éditions 🌶️ **Spicy** sont réglées pour le contenu adulte. Les modèles **Standard** listés ici sont classés `unrestricted` dans le catalogue (le fournisseur n'applique aucun filtre), ils acceptent donc aussi les prompts pour adultes. Les prix indiqués sont ceux du palier le moins cher. Catalogue consulté le <!-- catalog:date -->
2026-09-27
<!-- /catalog:date -->

<!-- catalog:video -->
| Modèle | Type | Tâches | Durée | À partir de | Spicy Index | Freedom |
|---|---|---|---|---|---|---|
| [Seedance 2.5 Spicy](https://spicyapi.ai/fr/models/seedance-2-5-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | I2V | 4–30 s | $0.216/s | 56.5 | ✅ 96.7 |
| [Seedance 2.5](https://spicyapi.ai/fr/models/seedance-2-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, Ref2V, T2V | 4–30 s | $0.1234/s | 69.5 | ◐ 80.9 |
| [Seedance 2.0 Spicy](https://spicyapi.ai/fr/models/seedance-2-0-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | I2V | 4–15 s | $0.114/s | 61.5 | ✅ 93.3 |
| [Seedance 2.0](https://spicyapi.ai/fr/models/seedance-2-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, Ref2V, T2V | 4–15 s | $0.07/s | 81.5 | ◐ 70.4 |
| [Wan 3.0 Prime](https://spicyapi.ai/fr/models/wan-3-0-prime?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, Ref2V, T2V | 2–30 s | $0.0612/s | 76.5 | ◐ 78 |
| [Wan 3.0](https://spicyapi.ai/fr/models/wan-3-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, Ref2V, T2V | 2–30 s | $0.045/s | 76.5 | ✅ 96 |
| [MiniMax H3 Spicy](https://spicyapi.ai/fr/models/minimax-h3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | I2V | 3–15 s | $0.038/s | 29.5 | ✅ 97.5 |
| [MiniMax H3](https://spicyapi.ai/fr/models/minimax-h3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, Ref2V, T2V | 4–15 s | $0.025/s | 72.5 | 🧪 33.3 |
| [MiniMax H3 Singularity LoRA](https://spicyapi.ai/fr/models/minimax-h3-singularity-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, Ref2V | 3–15 s | $0.06/s | 72.8 | ✅ 100 |
| [LTX 2.5](https://spicyapi.ai/fr/models/ltx-2-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, T2V | 5–20 s | $0.09/s | 66 | ◐ 80.3 |
| [Wan 3.0 Pro Prime](https://spicyapi.ai/fr/models/wan-3-0-pro-prime?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, Ref2V, T2V | 2–30 s | $0.234/s | 76.5 | ◐ 82 |
| [Wan 3.0 Pro](https://spicyapi.ai/fr/models/wan-3-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, Ref2V, T2V | 2–30 s | $0.144/s | 76.5 | ◐ 82 |
| [MiniMax H3 LoRA](https://spicyapi.ai/fr/models/minimax-h3-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, Ref2V, T2V | 3–15 s | $0.05/s | 75.2 | ✅ 98.3 |
| [HappyHorse 1.1](https://spicyapi.ai/fr/models/happyhorse-1-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, Ref2V, T2V | 3–15 s | $0.14/s | 62.5 | ⚠️ 65.1 |
| [Seedance 2.0 Mini Spicy](https://spicyapi.ai/fr/models/seedance-2-0-mini-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | I2V | 4–15 s | $0.0387/s | 44.5 | ✅ 93.3 |
| [Seedance 2.0 Mini](https://spicyapi.ai/fr/models/seedance-2-0-mini?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, Ref2V, T2V | 4–15 s | $0.01097/s | 64.5 | ⚠️ 64.9 |
| [Wan 2.7 Spicy](https://spicyapi.ai/fr/models/wan-2-7-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | I2V | 2–15 s | $0.1235/s | 46.5 | ✅ 100 |
| [LTX 2.3 Spicy](https://spicyapi.ai/fr/models/ltx-2-3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | I2V | 3–20 s | $0.019/s | 33.5 | ◐ 89.2 |
| [LTX 2.3 Spicy LoRA](https://spicyapi.ai/fr/models/ltx-2-3-spicy-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | I2V | 3–20 s | $0.0285/s | 34.8 | ◐ 83.8 |
| [Seedance 2.0 Fast Spicy](https://spicyapi.ai/fr/models/seedance-2-0-fast-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | I2V | 4–15 s | $0.081/s | 44.5 | ✅ 90 |
| [Seedance 2.0 Fast](https://spicyapi.ai/fr/models/seedance-2-0-fast?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, Ref2V, T2V | 4–15 s | $0.02254/s | 64.5 | ⚠️ 68.2 |
| [Vidu Q3 Turbo](https://spicyapi.ai/fr/models/vidu-q3-turbo?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V | 1–16 s | $0.042/s | 39.5 | ✅ 93.3 |
| [Vidu Q3 Spicy](https://spicyapi.ai/fr/models/vidu-q3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | I2V | 1–16 s | $0.0665/s | 46.5 | ✅ 96.7 |
| [Vidu Q3](https://spicyapi.ai/fr/models/vidu-q3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V | 1–16 s | $0.07/s | 46.5 | ✅ 93.3 |
| [Vidu Q3 Pro](https://spicyapi.ai/fr/models/vidu-q3-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V | 1–16 s | $0.054/s | 36.5 | ✅ 93.3 |
| [Seedance 1.5 Pro Spicy](https://spicyapi.ai/fr/models/seedance-1-5-pro-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | I2V | 4–12 s | $0.012/s | 48.5 | ✅ 96.7 |
| [Seedance 1.5 Pro](https://spicyapi.ai/fr/models/seedance-1-5-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, T2V | 4–12 s | $0.0112/s | 46 | ✅ 90 |
| [Wan 2.6 Flash](https://spicyapi.ai/fr/models/wan-2-6-flash?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V | 5, 10, 15 s | $0.0225/s | 31.5 | ✅ 100 |
| [Wan 2.6 Spicy](https://spicyapi.ai/fr/models/wan-2-6-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | I2V | 5, 10, 15 s | $0.095/s | 46.5 | ✅ 96.7 |
| [Wan 2.6](https://spicyapi.ai/fr/models/wan-2-6?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, Ref2V, T2V | 5, 10, 15 s | $0.065/s | 58.5 | 🧪 8.7 |
| [Wan 2.5](https://spicyapi.ai/fr/models/wan-2-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V, T2V | 5, 10 s | $0.045/s | 46 | ✅ 99 |
| [Wan 2.2 Spicy](https://spicyapi.ai/fr/models/wan-2-2-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | I2V | 5, 8 s | $0.019/s | 23.5 | ✅ 91.2 |
| [Wan 2.2 Spicy LoRA](https://spicyapi.ai/fr/models/wan-2-2-spicy-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | I2V, Extend | 5, 8 s | $0.024/s | 25 | ◐ 74.8 |
| [Wan 2.2 LoRA](https://spicyapi.ai/fr/models/wan-2-2-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | I2V | 5, 8 s | $0.024/s | 22.5 | ◐ 88.8 |
<!-- /catalog:video -->

Choix testés (explicite = prompts de test L4 rendus comme demandé) :

- **Meilleur polyvalent : Wan 3.0.** Spicy Index 76.5, Freedom 96, explicite 9/9, $0.45 les 5 s en 720p, clips jusqu'à 30 s. Wan 3.0 Pro et Pro Prime rendent eux aussi les prompts explicites (9/9) mais obtiennent un Freedom plus bas (82), surtout au niveau extrême (L5).
- **Styles et personnages personnalisés : MiniMax H3 LoRA** (Index 75.2, Freedom 98.3, explicite 11/13) et **MiniMax H3 Singularity LoRA** (Index 72.8, Freedom 100, explicite 8/8).
- **Seedance pour le contenu adulte : Seedance 2.5** (Index 69.5, Freedom 80.9, explicite 8/9) pour le texte en vidéo et la vidéo à partir de références ; pour de l'image en vidéo explicite, utilisez l'édition 🌶️ **Seedance 2.5 Spicy** (Freedom 96.7, explicite 3/3).
- **Les plus permissifs : Wan 2.7 Spicy, Wan 2.6 Flash et MiniMax H3 Singularity LoRA** (Freedom 100), **Wan 2.5** (99).
- **Petit budget : Wan 2.6 Flash** ($0.11 les 5 s, Freedom 100), 🌶️ **Seedance 1.5 Pro Spicy** ($0.13, Freedom 96.7) et **MiniMax H3** ($0.185 les 5 s en 768p ; ses 14 clips de test sont tous sortis comme demandé ; son Freedom n'est bas que parce que certains niveaux ne sont pas encore couverts). 🌶️ Wan 2.2 Spicy et LTX 2.3 Spicy coûtent $0.19 mais adoucissent plus souvent le niveau le plus élevé.
- **Adoucissent les prompts explicites en test**, préférez donc l'édition Spicy de la famille : Seedance 2.0 standard (Freedom 70.4, explicite 1/9 ; c'est le modèle vidéo qui a le score de capacités le plus élevé, il est donc excellent pour du contenu suggestif), Seedance 2.0 Fast / Mini (68.2 / 64.9), HappyHorse 1.1 (65.1) et Wan 2.2 (43.1).
- **Pas encore assez de données de test :** Wan 2.6 standard (5 tests) ; l'édition 🌶️ Wan 2.6 Spicy est entièrement testée (Freedom 96.7).
- **Points de vigilance relevés dans les avis :** Wan 3.0 va parfois plus loin que le prompt (surveillez les dernières secondes), met environ 3,5 minutes par tâche, et sa vidéo à partir de références refuse les photos de vrais visages. Seedance 2.5 reste le plus fidèle à un long script ; Seedance 2.5 Spicy va plus loin sur les niveaux les plus durs.

Certains endpoints vidéo facturent par blocs entiers (par exemple, un clip de 6 secondes sur des blocs de 5 secondes est facturé 10 s) ; la page du modèle indique la durée du bloc, et le montant du devis est le maximum qui peut vous être facturé. Parcourez et filtrez tous les modèles sur [SpicyAPI › Modèles IA sans censure](https://spicyapi.ai/fr/explore/uncensored-ai-models?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=video-table-fr).

### Combien coûte un clip NSFW de 5 secondes

Coût d'un clip de 5 secondes en 720p (768p pour MiniMax), d'après l'axe prix du classement au 2026-09-27, avec le Freedom Score en regard. Les résolutions plus basses coûtent moins cher.

| Modèle | 1 clip (5 s) | 100 clips | 1 000 clips | Freedom |
|---|---|---|---|---|
| Wan 2.6 Flash | $0.11 | $11.25 | $112.50 | ✅ 100 |
| 🌶️ Seedance 1.5 Pro Spicy | $0.13 | $13.00 | $130 | ✅ 96.7 |
| MiniMax H3 | $0.185 | $18.50 | $185 | 🧪 33.3 (14/14 clips comme demandé) |
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

En 480p, la plupart de ces modèles coûtent à peu près moitié prix (par exemple Wan 2.2 Spicy $0.095 et Seedance 1.5 Pro Spicy $0.06 les 5 s). Les tâches échouées sont remboursées automatiquement.

---

## Générateurs d'images IA sans censure

**Notre recommandation : [Qwen Image 2.1](https://spicyapi.ai/fr/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-fr)** : Spicy Index 73, Freedom 96.3 (explicite 5/6), à partir de $0.024 l'image en 1k. Il suit des consignes longues (jusqu'à 5 000 caractères), génère 15 formats en 1k, 1,5k ou 2k, et retouche à partir de 1 à 10 images de référence dans la même famille.

Autres choix testés :

- **Votre propre style ou personnage (anime compris) : [Qwen Image 2.1 LoRA](https://spicyapi.ai/fr/models/qwen-image-2-1-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-fr)** : n° 1 du Spicy Index image (80.5), Freedom 92, jusqu'à trois LoRA. **[MiniMax H3 Image LoRA](https://spicyapi.ai/fr/models/minimax-h3-image-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-fr)** : Index 74.5, Freedom 100 (explicite 8/8), assorti à la vidéo MiniMax H3.
- **Seedream : [Seedream 5.0 Lite](https://spicyapi.ai/fr/models/seedream-5-0-lite?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-fr) / [Seedream 5.0 Pro](https://spicyapi.ai/fr/models/seedream-5-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-fr)** : Index 73, Freedom 96 / 94.3. Seedream 4.0 obtient un bon score de capacités (74) mais un Freedom plus bas (74.7).
- **Texte dans l'image (affiches, couvertures) : [Qwen Image 3.0 Pro](https://spicyapi.ai/fr/models/qwen-image-3-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-fr)** : Freedom 98, explicite 6/6.
- **Le moins cher : 🌶️ [Z-Image Spicy](https://spicyapi.ai/fr/models/z-image-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-fr)** ($0.01235, Freedom 98.8) et [Z-Image Turbo LoRA](https://spicyapi.ai/fr/models/z-image-turbo-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-fr) ($0.012, Freedom 95). Leurs scores de capacités sont plus bas (32 / 46.5) : réservez-les au volume et aux brouillons.
- **Déconseillés pour le NSFW :** Krea 2 (Freedom 10), Wan 2.7 / Wan 2.7 Pro en texte en image (niveaux nudité et explicite le plus souvent adoucis), FLUX.1 Dev LoRA (75, explicite 0/6). Prefect Pony XL n'a que 3 tests à ce jour (Freedom 36) ; considérez-le comme une option anime à prompts par tags, pas comme un choix NSFW testé.

Tous les modèles d'image sans censure, dans l'ordre du catalogue :

<!-- catalog:image -->
| Modèle | Type | Tâches | À partir de | Spicy Index | Freedom |
|---|---|---|---|---|---|
| [Qwen Image 2.1](https://spicyapi.ai/fr/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | Edit, T2I | $0.024/image | 73 | ✅ 96.3 |
| [Qwen Image 2.1 LoRA](https://spicyapi.ai/fr/models/qwen-image-2-1-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | Edit, T2I | $0.03/image | 80.5 | ✅ 92 |
| [MiniMax H3 Image LoRA](https://spicyapi.ai/fr/models/minimax-h3-image-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | Edit, T2I | $0.042/image | 74.5 | ✅ 100 |
| [Qwen Image 3.0 Pro](https://spicyapi.ai/fr/models/qwen-image-3-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | Edit, T2I | $0.04/image | 56 | ✅ 98 |
| [Qwen Image 3.0](https://spicyapi.ai/fr/models/qwen-image-3-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | Edit, T2I | $0.03/image | 56 | ✅ 96 |
| [Seedream 5.0 Pro](https://spicyapi.ai/fr/models/seedream-5-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | Edit, T2I | $0.036/image | 73 | ✅ 94.3 |
| [Qwen Image Edit Spicy](https://spicyapi.ai/fr/models/qwen-image-spicy-edit?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | Edit | $0.038/image | 14 | ✅ 96 |
| [Seedream 5.0 Lite](https://spicyapi.ai/fr/models/seedream-5-0-lite?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | Edit, T2I | $0.0345/image | 73 | ✅ 96 |
| [Qwen Image 2](https://spicyapi.ai/fr/models/alibaba-qwen-image-2?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | Edit, T2I | $0.035/image | 34 | ✅ 96.7 |
| [Qwen Image 2512 LoRA](https://spicyapi.ai/fr/models/qwen-image-2512-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | Edit, T2I | $0.03/image | 50.5 | ✅ 92.5 |
| [Z-Image Spicy Pro](https://spicyapi.ai/fr/models/z-image-spicy-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | T2I | $0.019/image | 38 | ✅ 100 |
| [Z-Image Spicy](https://spicyapi.ai/fr/models/z-image-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | 🌶️ Spicy | T2I | $0.01235/image | 32 | ✅ 98.8 |
| [Z-Image](https://spicyapi.ai/fr/models/z-image?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | T2I | $0.01/image | 17 | ✅ 100 |
| [Z-Image Turbo LoRA](https://spicyapi.ai/fr/models/z-image-turbo-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | Edit, T2I | $0.012/image | 46.5 | ✅ 95 |
| [Seedream 4.0](https://spicyapi.ai/fr/models/seedream-4-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | Edit, T2I | $0.03/image | 74 | ◐ 74.7 |
| [Prefect Pony XL](https://spicyapi.ai/fr/models/prefect-pony-xl?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | T2I | $0.015/image | 30 | 🧪 36 |
| [FLUX.1 Dev LoRA](https://spicyapi.ai/fr/models/flux-1-dev-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-fr) | Standard | T2I | $0.018/image | 32.5 | ◐ 75 |
<!-- /catalog:image -->

Option sans code : le [générateur d'images IA sans censure de SpicyAPI Studio](https://spicyapi.ai/fr/create/uncensored-ai-image-generator?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-studio-fr) fait tourner les mêmes modèles dans le navigateur, avec des styles, des formats et le prix affiché avant chaque génération.

Pour un comparatif direct de ce que chaque modèle d'image autorise, lisez [Less-restrictive image model evaluation](https://spicyapi.ai/fr/blog/less-restrictive-model-evaluation?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-eval-fr).

---

## Éditeurs d'images IA NSFW et outils de visage

| Outil | Ce qu'il fait | À partir de |
|---|---|---|
| [Qwen Image 2.1 Edit](https://spicyapi.ai/fr/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-fr) | Retouche sans censure à partir de 1 à 10 images de référence d'un sujet **fictif** ou consentant : tenue, pose, décor, éclairage (classé `unrestricted` dans le catalogue) | $0.036 / image |
| 🌶️ [Qwen Image Edit Spicy](https://spicyapi.ai/fr/models/qwen-image-spicy-edit?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-fr) | Retouche par instruction sur une seule image (Freedom 96, mais un score de capacités bas, 14 : une seule image en entrée, aucun contrôle de la taille ni du format) ; essayez d'abord Qwen Image 2.1 Edit | $0.038 / image |
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

| Modèle | À partir de (pour 1K tokens) | Freedom | Idéal pour |
|---|---|---|---|
| [Grok 4.7](https://spicyapi.ai/fr/models/grok-4-7?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-fr) | $0.0036 | ✅ 100 (explicite 9/9) | Fiction explicite, jeu de rôle avec de la personnalité |
| [Grok 4.6](https://spicyapi.ai/fr/models/grok-4-6?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-fr) / [Grok 4.5](https://spicyapi.ai/fr/models/grok-4-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-fr) | $0.0036 | ✅ 100 | Même comportement que 4.7 |
| [Grok 4.3](https://spicyapi.ai/fr/models/grok-4-3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-fr) | $0.0015 | ✅ 98.9 | Meilleur rapport qualité-prix : score de capacités texte le plus élevé (74) et latence médiane ≈4 s |
| [DeepSeek V4.1 Flash](https://spicyapi.ai/fr/models/deepseek-v4-1-flash?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-fr) | $0.0012 | ✅ 90.4 | Enrichissement de prompts pas cher ; adoucit parfois les scènes explicites (7/16) |
| [DeepSeek V4 Pro](https://spicyapi.ai/fr/models/deepseek-v4-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-fr) | $0.00396 | ◐ 88.6 | Fiction longue et raisonnement |

Testés mais déconseillés pour l'écriture explicite : Kimi K3 (74.4), GLM 5.x (63–68), Gemini (64–89) et les modèles Claude (47–79) adoucissent ou refusent souvent les scènes explicites.

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
        ├── Meilleure vidéo polyvalente → Wan 3.0 (T2V / I2V / Ref2V, Freedom 96, $0.45 les 5 s)
        ├── Explicite à partir d'une image fixe → Seedance 2.5 Spicy, Wan 2.7 Spicy ou Vidu Q3 Spicy
        ├── Style / personnage personnalisé → MiniMax H3 LoRA / Singularity LoRA (vidéo), Qwen Image 2.1 LoRA (images fixes)
        ├── Volume à petit budget → Wan 2.6 Flash ou Seedance 1.5 Pro Spicy ($0.11–0.13 les 5 s)
        ├── Images fixes          → Qwen Image 2.1 (Qwen Image 2.1 LoRA pour votre propre style)
        ├── Texte / jeu de rôle   → Grok 4.7 ou Grok 4.3
        └── Depuis Claude Code / Cursor → nsfw-ai-skill ou le serveur MCP SpicyAPI
```

**Par cas d'usage**

| Cas d'usage | Combinaison recommandée |
|---|---|
| Site d'abonnement pour adultes / contenu de créateur | Qwen Image 2.1 pour les images → Wan 3.0 ou Seedance 2.5 Spicy pour les clips → Video Upscaler |
| Appli de compagnon IA ou de jeu de rôle | Grok 4.7 ou Grok 4.3 pour le chat → Qwen Image 2.1 pour les selfies → MiniMax H3 Spicy ou Wan 3.0 pour de courtes animations |
| Amateur, beaucoup d'essais | Wan 2.6 Flash ou Seedance 1.5 Pro Spicy, itérer, puis refaire les meilleurs sur Wan 3.0 |
| Contenu style anime / hentai | Qwen Image 2.1 LoRA avec un LoRA anime → Vidu Q3 Spicy (Freedom 96.7) ou Wan 2.2 Spicy LoRA avec le même LoRA |
| Fiction érotique et histoires interactives | Grok 4.7 pour le texte, Qwen Image 2.1 pour les illustrations |

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
D'après les tests publics de SpicyAPI, **Wan 3.0** est le meilleur choix polyvalent : Spicy Index 76.5 (n° 2 sur 37 modèles vidéo), Freedom Score 96, tous les prompts de test explicites rendus (9/9), clips jusqu'à 30 s, et $0.45 les 5 s en 720p. Pour de l'image en vidéo explicite, les éditions Spicy **Seedance 2.5 Spicy**, **Wan 2.7 Spicy** et **Vidu Q3 Spicy** (Freedom 96.7–100) sont les valeurs les plus sûres ; pour votre propre style, **MiniMax H3 LoRA**. Seedance 2.0 standard a le score de capacités le plus élevé mais adoucit souvent les prompts explicites (Freedom 70.4). Résultats : [classements SpicyAPI](https://spicyapi.ai/fr/leaderboards?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=faq-fr).

### Quel est le meilleur générateur d'images IA sans censure ?
En hébergé : **Qwen Image 2.1** (Spicy Index 73, Freedom 96.3, à partir de $0.024/image) ; **Qwen Image 2.1 LoRA** (n° 1 de l'index image, 80.5) et **MiniMax H3 Image LoRA** (Freedom 100) pour vos propres styles ; **Seedream 5.0 Lite / Pro** comme solides alternatives ; **Z-Image Spicy** ($0.01235, Freedom 98.8) pour le volume au meilleur prix. En auto-hébergé : les checkpoints communautaires SDXL, Pony et Illustrious dans ComfyUI ou Forge.

### Comment transformer une image en vidéo NSFW ?
Générez ou choisissez une première image (un adulte fictif, ou vous-même), puis envoyez-la à un modèle image en vidéo NSFW comme Wan 3.0 ou Seedance 2.5 Spicy avec un prompt court qui décrit le mouvement et la caméra. Voir le [démarrage rapide de l'API](#démarrage-rapide--image-en-vidéo-nsfw-via-http) ou utilisez l'[outil image en vidéo](https://spicyapi.ai/fr/create/image-to-video?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=faq-fr) dans le navigateur.

### Existe-t-il un générateur IA NSFW gratuit ?
Faire tourner des modèles à poids ouverts en local (ComfyUI + Wan 2.2, Qwen-Image ou Z-Image) est gratuit, hors matériel et électricité. Les services hébergés sont payants parce que les GPU coûtent cher ; SpicyAPI n'a pas d'abonnement et facture au résultat, avec remboursement des tâches échouées.

### Quelle est l'API vidéo IA NSFW la moins chère ?
Dans le catalogue SpicyAPI (2026-09-27), **Wan 2.6 Flash** ($0.1125 les 5 s en 720p, Freedom 100) et **Seedance 1.5 Pro Spicy** ($0.13 les 5 s en 720p, ou $0.06 en 480p sans audio ; Freedom 96.7) sont les modèles les moins chers qui réussissent les tests explicites. Wan 2.2 Spicy et LTX 2.3 Spicy suivent à $0.19 les 5 s (720p).

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
