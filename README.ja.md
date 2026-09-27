<!--
  Keywords: NSFW AI, NSFW AI 動画生成, NSFW AI 画像生成, エロ AI 画像生成, エロ AI 動画生成, 無修正 AI 画像生成,
  無修正 AI 動画, 無修正 AI 動画生成, AI 画像から動画, エロ 画像から動画 AI, NSFW AI 画像編集, 無検閲 LLM, NSFW AI API,
  成人向け AI, アダルト AI 生成, NSFW AI 2026 おすすめ, Wan 2.2 Spicy, Seedance Spicy, NSFW AI スキル, NSFW MCP,
  awesome nsfw ai, nsfw ai generator, uncensored ai image generator, uncensored ai video generator, nsfw image to video
-->

<p align="center"><a href="README.md">English</a> · <b>日本語</b> · <a href="README.ko.md">한국어</a> · <a href="README.fr.md">Français</a> · <a href="README.es.md">Español</a></p>

<h1 align="center">Awesome NSFW AI</h1>

<p align="center">
  <b>成人向けクリエイターと開発者のための、2026 年版 NSFW AI リソース集。無修正 AI 画像生成、NSFW AI 動画生成、画像から動画（I2V）モデル、画像編集、無検閲 LLM、API、エージェントスキル、MCP サーバー、ツールをまとめています。</b>
</p>

<p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
  <img src="https://img.shields.io/badge/updated-2026--09--27-blue" alt="最終更新 2026-09-27">
  <img src="https://img.shields.io/badge/18%2B-adults%20only-red" alt="18 歳以上限定">
  <img src="https://img.shields.io/badge/license-CC0--1.0-lightgrey" alt="CC0 ライセンス">
</p>

<p align="center">
  <img src="assets/wolf-turn-and-look-back.gif" width="24%" alt="Wan 2.2 Spicy の画像から動画の出力例">
  <img src="assets/velvet-spiral-turn.gif" width="24%" alt="Seedance 2.0 Spicy の画像から動画の出力例">
  <img src="assets/silk-draught-pull.gif" width="24%" alt="Wan 2.7 Spicy の画像から動画の出力例">
  <img src="assets/hotel-window-turn.gif" width="24%" alt="Seedance 2.5 Spicy の画像から動画の出力例">
  <br><sub>Wan 2.2 Spicy、Seedance 2.0 Spicy、Wan 2.7 Spicy、Seedance 2.5 Spicy の実際の出力です。使ったプロンプト付きの例は <a href="https://github.com/Spicy-API/nsfw-ai-video-prompts/blob/main/README.ja.md#ショーケース-実際の出力とプロンプト">nsfw-ai-video-prompts</a> にまとめています。</sub>
</p>

<p align="center">
  <a href="#無修正-ai-動画生成モデル">動画</a> ·
  <a href="#無修正-ai-画像生成モデル">画像</a> ·
  <a href="#nsfw-ai-画像編集顔ツール">編集</a> ·
  <a href="#無検閲-llm-とロールプレイ">LLM</a> ·
  <a href="#nsfw-ai-api">API</a> ·
  <a href="#エージェントスキルと-mcp-サーバー">スキル &amp; MCP</a> ·
  <a href="#セルフホストオープンウェイトモデル">セルフホスト</a> ·
  <a href="#よくある質問">よくある質問</a>
</p>

> **18 歳以上限定。** このリストには成人向けコンテンツを生成できるツールを載せています。どのリソースも、架空の成人、または記録に残る形で同意を得た実在の成人に対してのみ使い、あなたと視聴者が住む地域の法律を守ってください。詳しくは[すべてのツールに共通するルール](#すべてのツールに共通するルール)を参照してください。

> **開示：** このリストは、無修正の画像・動画・テキストモデルを従量課金で使える API、[SpicyAPI](https://spicyapi.ai/ja?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=disclosure-ja) のチームが管理しています。SpicyAPI の項目には 🌶️ を付けています。サードパーティのツールは役に立つから載せているのであって、掲載料をもらっているわけではありません。競合サービスを追加するプルリクエストも歓迎します。

---

## TL;DR: 目的別のおすすめ

| やりたいこと | まずはこれ | 理由（SpicyAPI リーダーボード、2026-09-27） |
|---|---|---|
| 総合力の高い NSFW 動画モデル | [Wan 3.0](https://spicyapi.ai/ja/models/wan-3-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ja) | Spicy Index 76.5（37 モデル中 2 位）、Freedom 96。露骨なテストプロンプトはすべて指示どおりに生成（9/9）。T2V、I2V、参照画像から動画に対応し最大 30 秒。720p で 5 秒 $0.45 |
| 自分のスタイルやキャラクターで NSFW 動画を作りたい | [MiniMax H3 LoRA](https://spicyapi.ai/ja/models/minimax-h3-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ja) または [MiniMax H3 Singularity LoRA](https://spicyapi.ai/ja/models/minimax-h3-singularity-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ja) | Spicy Index 75.2 / 72.8、Freedom 98.3 / 100 |
| Spicy 版で露骨な「画像から動画」を作りたい | 🌶️ [Seedance 2.5 Spicy](https://spicyapi.ai/ja/models/seedance-2-5-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ja)、🌶️ [Wan 2.7 Spicy](https://spicyapi.ai/ja/models/wan-2-7-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ja) または 🌶️ [Vidu Q3 Spicy](https://spicyapi.ai/ja/models/vidu-q3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ja) | Freedom 96.7〜100。露骨なテストプロンプトはすべて指示どおりに生成（3/3） |
| NSFW 動画を安く大量に作りたい | [Wan 2.6 Flash](https://spicyapi.ai/ja/models/wan-2-6-flash?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ja) または 🌶️ [Seedance 1.5 Pro Spicy](https://spicyapi.ai/ja/models/seedance-1-5-pro-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ja) | Freedom 100 / 96.7、720p で 5 秒 $0.11〜0.13 |
| 無修正のテキストから画像モデル | [Qwen Image 2.1](https://spicyapi.ai/ja/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ja) | Spicy Index 73、Freedom 96.3、1 枚 $0.024 から。長いプロンプト、15 種類のアスペクト比 |
| 自分のスタイルで画像を作りたい（アニメも含む） | [Qwen Image 2.1 LoRA](https://spicyapi.ai/ja/models/qwen-image-2-1-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ja) または [MiniMax H3 Image LoRA](https://spicyapi.ai/ja/models/minimax-h3-image-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ja) | 画像の Spicy Index で 1 位と 2 位（80.5 / 74.5）、Freedom 92 / 100 |
| 無修正の AI 画像編集 | [Qwen Image 2.1 Edit](https://spicyapi.ai/ja/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ja) | 上と同じシリーズ。参照画像 1〜10 枚と指示文 1 つ。マスク不要 |
| 無検閲のチャット、ロールプレイ、プロンプト作成 | [Grok 4.7](https://spicyapi.ai/ja/models/grok-4-7?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ja) または [Grok 4.3](https://spicyapi.ai/ja/models/grok-4-3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ja) | テキストのリーダーボードで Freedom 100 / 98.9。いちばん速いのは Grok 4.3（中央値 約 4 秒） |
| すべてローカルで無料で動かしたい | [ComfyUI](https://github.com/Comfy-Org/ComfyUI) + [Wan 2.2](https://github.com/Wan-Video/Wan2.2) のオープンウェイト | 高性能 GPU が必要（VRAM 24 GB あれば余裕） |
| Claude Code / Cursor に生成させたい | [nsfw-ai-skill](https://github.com/Spicy-API/nsfw-ai-skill/blob/main/README.ja.md) または公式 [SpicyAPI MCP サーバー](https://docs.spicyapi.ai/docs/mcp?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) | エージェントに自然な言葉で頼むだけで生成 |
| コピペで使える画像プロンプトが欲しい | [nsfw-ai-image-prompts](https://github.com/Spicy-API/nsfw-ai-image-prompts/blob/main/README.ja.md) | Qwen Image 2.1、Seedream 5.0 などに対応した画像・編集プロンプト 104 本と、実際の出力例 72 件 |
| コピペで使える動画プロンプトが欲しい | [nsfw-ai-video-prompts](https://github.com/Spicy-API/nsfw-ai-video-prompts/blob/main/README.ja.md) | すぐ使える動画プロンプト 116 本と、プロンプト付きの実際の出力例 130 件 |

スコアは公開されている [SpicyAPI リーダーボード](https://spicyapi.ai/ja/leaderboards?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ja)のものです（評価方法 v2.1、テスト期間 2026-09-14〜2026-09-27。[モデルの評価方法](#このリストでのモデルの評価方法)を参照）。価格はカタログに載っているティアの価格です。解像度を上げる、音声を付ける、尺を長くすると料金は上がります。

---

## 目次

- [TL;DR: 目的別のおすすめ](#tldr-目的別のおすすめ)
- [「NSFW AI」と「無修正 AI」の意味](#nsfw-aiと無修正-aiの意味)
- [無修正 AI 動画生成モデル](#無修正-ai-動画生成モデル)
  - [無修正動画モデル一覧（人気順）](#無修正動画モデル一覧人気順)
  - [5 秒の NSFW 動画 1 本あたりの料金](#5-秒の-nsfw-動画-1-本あたりの料金)
- [無修正 AI 画像生成モデル](#無修正-ai-画像生成モデル)
- [NSFW AI 画像編集・顔ツール](#nsfw-ai-画像編集顔ツール)
- [無検閲 LLM とロールプレイ](#無検閲-llm-とロールプレイ)
- [NSFW AI API](#nsfw-ai-api)
- [エージェントスキルと MCP サーバー](#エージェントスキルと-mcp-サーバー)
- [セルフホスト・オープンウェイトモデル](#セルフホストオープンウェイトモデル)
- [ローカル UI とワークフローツール](#ローカル-ui-とワークフローツール)
- [LoRA・チェックポイント・学習](#loraチェックポイント学習)
- [アップスケール・修復・ポストプロダクション](#アップスケール修復ポストプロダクション)
- [成人向けコンテンツのプロンプトの書き方](#成人向けコンテンツのプロンプトの書き方)
- [選び方: 用途別ガイド](#選び方-用途別ガイド)
- [すべてのツールに共通するルール](#すべてのツールに共通するルール)
- [よくある質問](#よくある質問)
- [関連リポジトリ](#関連リポジトリ)
- [コントリビュート](#コントリビュート)

---

## 「NSFW AI」と「無修正 AI」の意味

**NSFW AI** とは、成人向けのヌードや性的コンテンツを生成できる生成モデルやツールのことです。**無修正 AI（uncensored AI）** はもう少しゆるい言葉で、成人向けのプロンプトを拒否したり、出力にぼかしを入れたりしないモデルを指します。

NSFW のリクエストが通るかどうかは次の 3 つで決まりますが、よく混同されます。

1. **モデルそのもの。** 成人向けの出力を許すように学習・ファインチューニングされたモデルもあれば、拒否するように学習されたモデルもあります。後者はプラットフォーム側の設定では変えられません。
2. **プラットフォーム独自のフィルター。** 多くのホスティングサービスは、モデルの上にさらにモデレーション層（プロンプトのブロックリスト、出力の分類器、ぼかし）を重ねています。許容度の高いモデルでも、厳しいフィルターの裏にあればブロックされます。
3. **現地の法律とプラットフォームの規約。**「モデルが生成できる」ことと「あなたが生成してよい」ことは別です。どこの国でも違法なコンテンツがあります（[ルール](#すべてのツールに共通するルール)を参照）。

以下のリストは次のように読んでください。

| ラベル | 意味 |
|---|---|
| **Spicy / NSFW 版** | 成人向けの出力に合わせて調整・設定されたモデルのバージョン。SpicyAPI では名前に「Spicy」が付きます。 |
| **成人向け対応（Mature-capable）** | 成人向けコンテンツを許すことが多い汎用モデル。ただし一部のリクエストでは表現を弱めたり拒否したりすることがあります。 |
| **フィルターあり（Filtered）** | モデルまたはプロバイダーが独自のコンテンツフィルターをかけています。SFW 用途には問題ありませんが、NSFW には向きません。 |

SpicyAPI では、公開カタログのすべてのモデルにポリシーティア（`unrestricted`、`softened`、`borderline`、`filtered`）が付いていて、[リーダーボード](https://spicyapi.ai/ja/leaderboards?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=definitions-ja)では同じテストプロンプトを繰り返し使って測った **Freedom Score** を公開しています。プラットフォームとしてモデルの上に独自のフィルターを追加することはありません。フィルターがある場合、それはモデルプロバイダー側のものです。


### このリストでのモデルの評価方法

このリストのおすすめは、宣伝文句ではなく、SpicyAPI が公開しているテスト結果にもとづいています。

- **Freedom Score（0〜100）**：成人向けプロンプトが求める内容を、モデルがどれだけ確実に生成できるかを 5 つのレベルで測ります。L1 匂わせ、L2 部分的なヌード、L3 ヌード、L4 露骨な性描写、L5 過激（BDSM / ゴア）。各レベルは 20 点 × 合格率 × 信頼度で採点されるので、表現を弱めたり別の内容にすり替えたりした出力は減点されます。✅ 90 以上 · ◐ 70–89 · ⚠️ 70 未満 · 🧪 テスト実行がまだ 15 回未満（この場合、数字が低いのは拒否されたからではなく、テストで網羅できていないレベルがあるためです）。
- **Spicy Index（0〜100）**：現時点では*暫定値*です。公開スペック（ネイティブ解像度、最長の尺、音声、入力の種類など）から算出する性能スコアです。アリーナでの画質投票はまだ反映されていないので、今のところ見た目の品質は測っていません。
- **エンジニアリングによるルート検証**：モデルを掲載する前に、チームは上流のすべてのルートで露骨なテストケースを生成し、ダウンロードした出力を 1 フレームずつ確認します（プロバイダーによっては黙って安全な画像に差し替えることがあるため、「成功」ステータスだけでは不十分です）。一部のルートでしか露骨なコンテンツを生成できないモデルは、ここではおすすめしていません。

モデルごとの詳しいレポート（レベル別の実行回数付き）：[SpicyAPI リーダーボード](https://spicyapi.ai/ja/leaderboards?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=method-ja)。L4 / L5 のテスト出力は一切公開していません。

---

## 無修正 AI 動画生成モデル

NSFW AI 動画をいちばん安定して作れるのは「画像から動画（I2V）」です。見た目は開始フレームで決まり、モデルはそれを動かすだけで済むからです。テキストから動画（T2V）と、参照画像から動画（Ref2V、「この画像のキャラクターを新しいシーンに登場させる」）は、下の標準モデルで使えます。

### 無修正動画モデル一覧（人気順）

SpicyAPI のカタログと同じ順番です。人気の高い順に並べ、同じシリーズの中では新しいバージョンを先にしています。🌶️ **Spicy** 版は成人向けの出力に合わせて調整されています。ここに載せている**標準**モデルはカタログ上のティアが `unrestricted`（プロバイダーがコンテンツフィルターをかけていない）なので、成人向けのプロンプトも通ります。価格は最安ティアです。カタログ取得日: <!-- catalog:date -->
2026-09-27
<!-- /catalog:date -->

<!-- catalog:video -->
| モデル | 種類 | タスク | 長さ | 最低価格 | Spicy Index | Freedom |
|---|---|---|---|---|---|---|
| [Seedance 2.5 Spicy](https://spicyapi.ai/ja/models/seedance-2-5-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 🌶️ Spicy | I2V | 4–30 s | $0.216/s | 56.5 | ✅ 96.7 |
| [Seedance 2.5](https://spicyapi.ai/ja/models/seedance-2-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | I2V, Ref2V, T2V | 4–30 s | $0.1234/s | 69.5 | ◐ 80.9 |
| [Seedance 2.0 Spicy](https://spicyapi.ai/ja/models/seedance-2-0-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 🌶️ Spicy | I2V | 4–15 s | $0.114/s | 61.5 | ✅ 93.3 |
| [Seedance 2.0](https://spicyapi.ai/ja/models/seedance-2-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | I2V, Ref2V, T2V | 4–15 s | $0.07/s | 81.5 | ◐ 70.4 |
| [Wan 3.0 Prime](https://spicyapi.ai/ja/models/wan-3-0-prime?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | I2V, Ref2V, T2V | 2–30 s | $0.0612/s | 76.5 | ◐ 78 |
| [Wan 3.0](https://spicyapi.ai/ja/models/wan-3-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | I2V, Ref2V, T2V | 2–30 s | $0.045/s | 76.5 | ✅ 96 |
| [MiniMax H3 Spicy](https://spicyapi.ai/ja/models/minimax-h3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 🌶️ Spicy | I2V | 3–15 s | $0.038/s | 29.5 | ✅ 97.5 |
| [MiniMax H3](https://spicyapi.ai/ja/models/minimax-h3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | I2V, Ref2V, T2V | 4–15 s | $0.025/s | 72.5 | 🧪 33.3 |
| [MiniMax H3 Singularity LoRA](https://spicyapi.ai/ja/models/minimax-h3-singularity-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | I2V, Ref2V | 3–15 s | $0.06/s | 72.8 | ✅ 100 |
| [LTX 2.5](https://spicyapi.ai/ja/models/ltx-2-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | I2V, T2V | 5–20 s | $0.09/s | 66 | ◐ 80.3 |
| [Wan 3.0 Pro Prime](https://spicyapi.ai/ja/models/wan-3-0-pro-prime?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | I2V, Ref2V, T2V | 2–30 s | $0.234/s | 76.5 | ◐ 82 |
| [Wan 3.0 Pro](https://spicyapi.ai/ja/models/wan-3-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | I2V, Ref2V, T2V | 2–30 s | $0.144/s | 76.5 | ◐ 82 |
| [MiniMax H3 LoRA](https://spicyapi.ai/ja/models/minimax-h3-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | I2V, Ref2V, T2V | 3–15 s | $0.05/s | 75.2 | ✅ 98.3 |
| [HappyHorse 1.1](https://spicyapi.ai/ja/models/happyhorse-1-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | I2V, Ref2V, T2V | 3–15 s | $0.14/s | 62.5 | ⚠️ 65.1 |
| [Seedance 2.0 Mini Spicy](https://spicyapi.ai/ja/models/seedance-2-0-mini-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 🌶️ Spicy | I2V | 4–15 s | $0.0387/s | 44.5 | ✅ 93.3 |
| [Seedance 2.0 Mini](https://spicyapi.ai/ja/models/seedance-2-0-mini?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | I2V, Ref2V, T2V | 4–15 s | $0.01097/s | 64.5 | ⚠️ 64.9 |
| [Wan 2.7 Spicy](https://spicyapi.ai/ja/models/wan-2-7-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 🌶️ Spicy | I2V | 2–15 s | $0.1235/s | 46.5 | ✅ 100 |
| [LTX 2.3 Spicy](https://spicyapi.ai/ja/models/ltx-2-3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 🌶️ Spicy | I2V | 3–20 s | $0.019/s | 33.5 | ◐ 89.2 |
| [LTX 2.3 Spicy LoRA](https://spicyapi.ai/ja/models/ltx-2-3-spicy-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 🌶️ Spicy | I2V | 3–20 s | $0.0285/s | 34.8 | ◐ 83.8 |
| [Seedance 2.0 Fast Spicy](https://spicyapi.ai/ja/models/seedance-2-0-fast-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 🌶️ Spicy | I2V | 4–15 s | $0.081/s | 44.5 | ✅ 90 |
| [Seedance 2.0 Fast](https://spicyapi.ai/ja/models/seedance-2-0-fast?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | I2V, Ref2V, T2V | 4–15 s | $0.02254/s | 64.5 | ⚠️ 68.2 |
| [Vidu Q3 Turbo](https://spicyapi.ai/ja/models/vidu-q3-turbo?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | I2V | 1–16 s | $0.042/s | 39.5 | ✅ 93.3 |
| [Vidu Q3 Spicy](https://spicyapi.ai/ja/models/vidu-q3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 🌶️ Spicy | I2V | 1–16 s | $0.0665/s | 46.5 | ✅ 96.7 |
| [Vidu Q3](https://spicyapi.ai/ja/models/vidu-q3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | I2V | 1–16 s | $0.07/s | 46.5 | ✅ 93.3 |
| [Vidu Q3 Pro](https://spicyapi.ai/ja/models/vidu-q3-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | I2V | 1–16 s | $0.054/s | 36.5 | ✅ 93.3 |
| [Seedance 1.5 Pro Spicy](https://spicyapi.ai/ja/models/seedance-1-5-pro-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 🌶️ Spicy | I2V | 4–12 s | $0.012/s | 48.5 | ✅ 96.7 |
| [Seedance 1.5 Pro](https://spicyapi.ai/ja/models/seedance-1-5-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | I2V, T2V | 4–12 s | $0.0112/s | 46 | ✅ 90 |
| [Wan 2.6 Flash](https://spicyapi.ai/ja/models/wan-2-6-flash?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | I2V | 5, 10, 15 s | $0.0225/s | 31.5 | ✅ 100 |
| [Wan 2.6 Spicy](https://spicyapi.ai/ja/models/wan-2-6-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 🌶️ Spicy | I2V | 5, 10, 15 s | $0.095/s | 46.5 | ✅ 96.7 |
| [Wan 2.6](https://spicyapi.ai/ja/models/wan-2-6?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | I2V, Ref2V, T2V | 5, 10, 15 s | $0.065/s | 58.5 | 🧪 8.7 |
| [Wan 2.5](https://spicyapi.ai/ja/models/wan-2-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | I2V, T2V | 5, 10 s | $0.045/s | 46 | ✅ 99 |
| [Wan 2.2 Spicy](https://spicyapi.ai/ja/models/wan-2-2-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 🌶️ Spicy | I2V | 5, 8 s | $0.019/s | 23.5 | ✅ 91.2 |
| [Wan 2.2 Spicy LoRA](https://spicyapi.ai/ja/models/wan-2-2-spicy-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 🌶️ Spicy | I2V, Extend | 5, 8 s | $0.024/s | 25 | ◐ 74.8 |
| [Wan 2.2 LoRA](https://spicyapi.ai/ja/models/wan-2-2-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | I2V | 5, 8 s | $0.024/s | 22.5 | ◐ 88.8 |
<!-- /catalog:video -->

テスト済みのおすすめ（「露骨」＝ L4 のテストプロンプトが指示どおりに生成された数）：

- **総合力で選ぶなら Wan 3.0。** Spicy Index 76.5、Freedom 96、露骨 9/9、720p で 5 秒 $0.45、最大 30 秒。Wan 3.0 Pro と Pro Prime も露骨なプロンプトを生成できます（9/9）が、Freedom は低め（82）で、減点は主に過激レベル（L5）です。
- **独自のスタイルやキャラクター：MiniMax H3 LoRA**（Index 75.2、Freedom 98.3、露骨 11/13）と **MiniMax H3 Singularity LoRA**（Index 72.8、Freedom 100、露骨 8/8）。
- **成人向けに Seedance を使うなら：Seedance 2.5**（Index 69.5、Freedom 80.9、露骨 8/9）をテキストから動画と参照画像から動画に。露骨な画像から動画には 🌶️ **Seedance 2.5 Spicy** 版を使います（Freedom 96.7、露骨 3/3）。
- **いちばん許容度が高い：Wan 2.7 Spicy、Wan 2.6 Flash、MiniMax H3 Singularity LoRA**（Freedom 100）、**Wan 2.5**（99）。
- **低予算：Wan 2.6 Flash**（5 秒 $0.11、Freedom 100）、🌶️ **Seedance 1.5 Pro Spicy**（$0.13、Freedom 96.7）、**MiniMax H3**（768p で 5 秒 $0.185。テスト動画 14 本すべてが指示どおりに生成されました。Freedom の数字が低いのは、まだテストしていないレベルがあるためです）。🌶️ Wan 2.2 Spicy と LTX 2.3 Spicy は $0.19 ですが、最上位のレベルで表現を弱めることが多めです。
- **テストで露骨なプロンプトの表現を弱めるモデル**なので、同じシリーズの Spicy 版を使ってください：標準の Seedance 2.0（Freedom 70.4、露骨 1/9。性能スコアは動画モデルの中でいちばん高いので、匂わせ系の表現には最適です）、Seedance 2.0 Fast / Mini（68.2 / 64.9）、HappyHorse 1.1（65.1）、Wan 2.2（43.1）。
- **テストデータがまだ足りない：** 標準の Wan 2.6（実行 5 回）。🌶️ Wan 2.6 Spicy 版は十分にテスト済みです（Freedom 96.7）。
- **レビューで指摘されている注意点：** Wan 3.0 はプロンプトより踏み込みすぎることがあり（最後の数秒に注意）、1 ジョブに約 3.5 分かかり、参照画像から動画では実在の人物の顔写真を拒否します。長い台本にいちばん忠実なのは Seedance 2.5、最も過激なレベルでより踏み込むのは Seedance 2.5 Spicy です。

一部の動画エンドポイントはブロック単位で課金されます（たとえば 5 秒ブロックのモデルで 6 秒の動画を作ると 10 秒分の課金）。ブロックの長さはモデルページに書いてあり、見積もり額が請求される上限額です。すべてのモデルは [SpicyAPI › 無修正 AI モデル](https://spicyapi.ai/ja/explore/uncensored-ai-models?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=video-table-ja)で一覧・絞り込みできます。

### 5 秒の NSFW 動画 1 本あたりの料金

720p（MiniMax は 768p）の 5 秒動画 1 本の料金です。2026-09-27 時点のリーダーボードの価格軸から取り、Freedom Score と並べています。解像度を下げれば安くなります。

| モデル | 1 本（5 秒） | 100 本 | 1,000 本 | Freedom |
|---|---|---|---|---|
| Wan 2.6 Flash | $0.11 | $11.25 | $112.50 | ✅ 100 |
| 🌶️ Seedance 1.5 Pro Spicy | $0.13 | $13.00 | $130 | ✅ 96.7 |
| MiniMax H3 | $0.185 | $18.50 | $185 | 🧪 33.3（14/14 本が指示どおり） |
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

ほとんどのモデルは 480p にするとおよそ半額です（たとえば Wan 2.2 Spicy は 5 秒 $0.095、Seedance 1.5 Pro Spicy は $0.06）。失敗したタスクは自動で返金されます。

---

## 無修正 AI 画像生成モデル

**おすすめ：[Qwen Image 2.1](https://spicyapi.ai/ja/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-ja)**：Spicy Index 73、Freedom 96.3（露骨 5/6）、1k で 1 枚 $0.024 から。長い指示文（最大 5,000 文字）にも従い、15 種類のアスペクト比を 1k・1.5k・2k で出力でき、同じシリーズ内で参照画像 1〜10 枚からの編集もできます。

そのほかのテスト済みのおすすめ：

- **自分のスタイルやキャラクター（アニメも含む）：[Qwen Image 2.1 LoRA](https://spicyapi.ai/ja/models/qwen-image-2-1-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-ja)**：画像の Spicy Index で 1 位（80.5）、Freedom 92、LoRA を 3 つまで。**[MiniMax H3 Image LoRA](https://spicyapi.ai/ja/models/minimax-h3-image-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-ja)**：Index 74.5、Freedom 100（露骨 8/8）、MiniMax H3 の動画とそろえられます。
- **Seedream：[Seedream 5.0 Lite](https://spicyapi.ai/ja/models/seedream-5-0-lite?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-ja) / [Seedream 5.0 Pro](https://spicyapi.ai/ja/models/seedream-5-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-ja)**：Index 73、Freedom 96 / 94.3。Seedream 4.0 は性能スコアは高い（74）ものの、Freedom は低め（74.7）です。
- **画像内の文字（ポスター、表紙）：[Qwen Image 3.0 Pro](https://spicyapi.ai/ja/models/qwen-image-3-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-ja)**：Freedom 98、露骨 6/6。
- **最安：🌶️ [Z-Image Spicy](https://spicyapi.ai/ja/models/z-image-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-ja)**（$0.01235、Freedom 98.8）と [Z-Image Turbo LoRA](https://spicyapi.ai/ja/models/z-image-turbo-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-ja)（$0.012、Freedom 95）。性能スコアは低め（32 / 46.5）なので、大量生成や下書きに使ってください。
- **NSFW にはおすすめしない：** Krea 2（Freedom 10）、Wan 2.7 / Wan 2.7 Pro のテキストから画像（ヌードと露骨なレベルはほとんど表現が弱められる）、FLUX.1 Dev LoRA（75、露骨 0/6）。Prefect Pony XL はテスト実行がまだ 3 回しかありません（Freedom 36）。タグ形式のプロンプトで使うアニメ向けの選択肢として扱い、テスト済みの NSFW 向けおすすめとは考えないでください。

無修正の画像モデル一覧（カタログ順）：

<!-- catalog:image -->
| モデル | 種類 | タスク | 最低価格 | Spicy Index | Freedom |
|---|---|---|---|---|---|
| [Qwen Image 2.1](https://spicyapi.ai/ja/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | Edit, T2I | $0.024/image | 73 | ✅ 96.3 |
| [Qwen Image 2.1 LoRA](https://spicyapi.ai/ja/models/qwen-image-2-1-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | Edit, T2I | $0.03/image | 80.5 | ✅ 92 |
| [MiniMax H3 Image LoRA](https://spicyapi.ai/ja/models/minimax-h3-image-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | Edit, T2I | $0.042/image | 74.5 | ✅ 100 |
| [Qwen Image 3.0 Pro](https://spicyapi.ai/ja/models/qwen-image-3-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | Edit, T2I | $0.04/image | 56 | ✅ 98 |
| [Qwen Image 3.0](https://spicyapi.ai/ja/models/qwen-image-3-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | Edit, T2I | $0.03/image | 56 | ✅ 96 |
| [Seedream 5.0 Pro](https://spicyapi.ai/ja/models/seedream-5-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | Edit, T2I | $0.036/image | 73 | ✅ 94.3 |
| [Qwen Image Edit Spicy](https://spicyapi.ai/ja/models/qwen-image-spicy-edit?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 🌶️ Spicy | Edit | $0.038/image | 14 | ✅ 96 |
| [Seedream 5.0 Lite](https://spicyapi.ai/ja/models/seedream-5-0-lite?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | Edit, T2I | $0.0345/image | 73 | ✅ 96 |
| [Qwen Image 2](https://spicyapi.ai/ja/models/alibaba-qwen-image-2?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | Edit, T2I | $0.035/image | 34 | ✅ 96.7 |
| [Qwen Image 2512 LoRA](https://spicyapi.ai/ja/models/qwen-image-2512-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | Edit, T2I | $0.03/image | 50.5 | ✅ 92.5 |
| [Z-Image Spicy Pro](https://spicyapi.ai/ja/models/z-image-spicy-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 🌶️ Spicy | T2I | $0.019/image | 38 | ✅ 100 |
| [Z-Image Spicy](https://spicyapi.ai/ja/models/z-image-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 🌶️ Spicy | T2I | $0.01235/image | 32 | ✅ 98.8 |
| [Z-Image](https://spicyapi.ai/ja/models/z-image?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | T2I | $0.01/image | 17 | ✅ 100 |
| [Z-Image Turbo LoRA](https://spicyapi.ai/ja/models/z-image-turbo-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | Edit, T2I | $0.012/image | 46.5 | ✅ 95 |
| [Seedream 4.0](https://spicyapi.ai/ja/models/seedream-4-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | Edit, T2I | $0.03/image | 74 | ◐ 74.7 |
| [Prefect Pony XL](https://spicyapi.ai/ja/models/prefect-pony-xl?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | T2I | $0.015/image | 30 | 🧪 36 |
| [FLUX.1 Dev LoRA](https://spicyapi.ai/ja/models/flux-1-dev-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ja) | 標準 | T2I | $0.018/image | 32.5 | ◐ 75 |
<!-- /catalog:image -->

コードを書かずに使うなら、[SpicyAPI Studio の無修正 AI 画像生成](https://spicyapi.ai/ja/create/uncensored-ai-image-generator?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-studio-ja)で同じモデルをブラウザから使えます。スタイルやアスペクト比を選べ、生成前に価格が表示されます。

どの画像モデルがどこまで許容するかを比較したテストは、[制限の少ない画像モデルの評価（英語）](https://spicyapi.ai/ja/blog/less-restrictive-model-evaluation?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-eval-ja)を読んでください。

---

## NSFW AI 画像編集・顔ツール

| ツール | できること | 価格 |
|---|---|---|
| [Qwen Image 2.1 Edit](https://spicyapi.ai/ja/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ja) | **架空の**人物、または同意した人物の参照画像 1〜10 枚から無修正で編集：服装、ポーズ、背景、ライティングの変更（カタログ上のティアは `unrestricted`） | $0.036 / 枚 |
| 🌶️ [Qwen Image Edit Spicy](https://spicyapi.ai/ja/models/qwen-image-spicy-edit?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ja) | 画像 1 枚への指示文による編集（Freedom 96。ただし性能スコアは 14 と低く、入力画像は 1 枚のみで、サイズやアスペクト比も指定できません）。まずは Qwen Image 2.1 Edit を使ってください | $0.038 / 枚 |
| [Image Expander](https://spicyapi.ai/ja/models/image-expander-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ja) | 横長・縦長のフレームに広げるアウトペイント | $0.024 / 枚 |
| [Object Eraser](https://spicyapi.ai/ja/models/object-eraser-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ja) | 自分が権利を持つ画像から物体、ロゴ、透かしを消す | $0.03 / 枚 |
| [Image Upscaler](https://spicyapi.ai/ja/models/image-upscaler-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ja) / [Video Upscaler](https://spicyapi.ai/ja/models/video-upscaler-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ja) | 完成した出力をシャープにして拡大 | $0.012 / 枚、$0.006 / 秒 |
| [Face Swap](https://spicyapi.ai/ja/models/face-swap-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ja)、[Head Swap](https://spicyapi.ai/ja/models/head-swap-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ja)、[Video Character Swap](https://spicyapi.ai/ja/models/character-swap-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ja) | 1 人の**架空の**キャラクターを画像や動画をまたいで一貫させる | $0.013 / 枚、動画は $0.064 / 秒から |
| [Lip Sync](https://spicyapi.ai/ja/models/lip-sync-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ja)、[Talking Avatar](https://spicyapi.ai/ja/models/talking-avatar-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ja)、[Video Sound Effects](https://spicyapi.ai/ja/models/foley-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ja) | AI キャラクターの声と音声 | $0.0012 / 秒から |

> ⚠️ フェイススワップやヘッドスワップを、実在の人物を本人の記録に残る同意なしに性的コンテンツに合成するために使うことは**絶対に**禁止です。実在の人物の写真を「脱がせる」「ヌード化する」ことも、信頼できるすべてのプラットフォームで禁止されています。有名人であることや写真が公開されていることは、同意にはなりません。これらのツールは、自分で作った架空のキャラクターか、自分自身にだけ使ってください。

セルフホストで同じことをするなら：キャラクターの一貫性には [IP-Adapter](https://github.com/tencent-ailab/IP-Adapter)、[InstantID](https://github.com/instantX-research/InstantID)、[PhotoMaker](https://github.com/TencentARC/PhotoMaker)、ポーズ制御には [ControlNet](https://github.com/lllyasviel/ControlNet)。

---

## 無検閲 LLM とロールプレイ

NSFW の制作でテキストモデルが役立つ場面は 3 つあります。官能小説やインタラクティブストーリー、コンパニオン・ロールプレイアプリ、そして**画像・動画プロンプトの質を上げること**（1 行のアイデアを、カメラワークまで含めた詳しいプロンプトに LLM が膨らませる）です。

### ホスト型（OpenAI 互換）

SpicyAPI は `https://api.spicyapi.ai` で、OpenAI・Anthropic・Gemini 互換のエンドポイントからテキストモデルを提供しています。既存の SDK はベース URL を変えるだけで使えます。2026-09-27 時点でカタログ上のティアが `unrestricted` のモデルには次のものがあります。

| モデル | 価格（1K トークンあたり） | Freedom | 向いている用途 |
|---|---|---|---|
| [Grok 4.7](https://spicyapi.ai/ja/models/grok-4-7?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-ja) | $0.0036 | ✅ 100（露骨 9/9） | 露骨な小説、個性のあるロールプレイ |
| [Grok 4.6](https://spicyapi.ai/ja/models/grok-4-6?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-ja) / [Grok 4.5](https://spicyapi.ai/ja/models/grok-4-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-ja) | $0.0036 | ✅ 100 | 4.7 と同じ挙動 |
| [Grok 4.3](https://spicyapi.ai/ja/models/grok-4-3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-ja) | $0.0015 | ✅ 98.9 | コスパ最良：テキストの性能スコアが最も高く（74）、レイテンシの中央値は約 4 秒 |
| [DeepSeek V4.1 Flash](https://spicyapi.ai/ja/models/deepseek-v4-1-flash?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-ja) | $0.0012 | ✅ 90.4 | 安価なプロンプトの膨らませ。露骨な場面の表現を弱めることがある（7/16） |
| [DeepSeek V4 Pro](https://spicyapi.ai/ja/models/deepseek-v4-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-ja) | $0.00396 | ◐ 88.6 | 長編小説、推論 |

テストはしたものの、露骨な文章にはおすすめしないモデル：Kimi K3（74.4）、GLM 5.x（63〜68）、Gemini（64〜89）、Claude の各モデル（47〜79）は、露骨な場面の表現を弱めたり拒否したりすることがよくあります。

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

### ローカル・セルフホスト

- [Ollama](https://github.com/ollama/ollama) と [LM Studio](https://lmstudio.ai) は、オープンウェイトモデルを自分のマシンで動かせます。ライブラリで「abliterated」や「uncensored」と検索すると、コミュニティのファインチューンが見つかります。
- [KoboldCpp](https://github.com/LostRuins/koboldcpp)：物語づくり向けに作られた、単一ファイルの GGUF ランナー。
- [text-generation-webui](https://github.com/oobabooga/textgen)：拡張機能に対応した多機能なローカルチャット UI。
- [SillyTavern](https://github.com/SillyTavern/SillyTavern)：ロールプレイ用フロントエンドの定番。ローカルのバックエンドや、SpicyAPI を含む OpenAI 互換 API に接続できます。

---

## NSFW AI API

成人向けアプリを作る開発者にとっての問題は「どのモデルを使うか」だけではありません。「どのプロバイダーならリクエストをブロックされずに呼べて、料金も公正か」も重要です。

| 確認すること | なぜ重要か | SpicyAPI の場合 |
|---|---|---|
| プラットフォーム独自のフィルターがあるか | 2 段目のフィルターが、モデルなら通すプロンプトまでブロックしてしまう | プラットフォームのフィルターなし。モデルプロバイダーのポリシーは適用される |
| 課金単位 | クレジットやサブスクリプションでは実際のコストが見えにくい | USD 残高制、画像 1 枚 / 1 秒 / 1 トークン単位、サブスクなし、残高の有効期限なし |
| 生成失敗時の扱い | 拒否された分まで課金するプロバイダーもある | 失敗したタスクは自動で返金 |
| 支払い方法 | 成人向けビジネスはカード決済を止められやすい | Visa、Mastercard、Amex、JCB、Apple Pay、Google Pay、暗号資産（BTC、ETH、USDT） |
| 予算管理 | キーが漏れると残高を使い切られる | キーごとの日次 / 月次 / 累計の上限、モデルの許可リスト、IP 許可リスト |
| データ保持 | 成人向けの入力データはセンシティブ | プロンプト、アップロード、出力で別々の保持期間。短縮したり、タスクの内容を削除したりできる |
| 連携のしやすさ | モデルごとに専用クライアントを書きたくない | 非同期タスク API が 1 つ、SDK（TypeScript、Python、Go、PHP、Java）、CLI、MCP サーバー、エージェントスキル |

### クイックスタート: HTTP で NSFW 画像から動画を生成

```bash
export SPICY_API_KEY="sk-spicy-..."   # キーは https://spicyapi.ai/ja/console で作成

# 1) タスクを作成
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

# 2) state が "succeeded" になるまでポーリングし、data.output.assets[0].url を読む
curl -s "https://api.spicyapi.ai/api/v1/jobs/recordInfo?taskId=TASK_ID" \
  -H "Authorization: Bearer $SPICY_API_KEY"
```

入力フィールドはモデルごとに異なります。リクエストを送る前に `GET /api/v1/models/{model}`（またはモデルページ）で最新のスキーマを確認してください。詳しいリファレンス：[docs.spicyapi.ai](https://docs.spicyapi.ai/docs?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=api-quickstart)。

### その他のプロバイダー

ポリシーは頻繁に変わり、モデルごとに運用も違うので、本格的に使う前に自分のプロンプトで試してください。各プロバイダーの最新の利用規約（AUP）も必ず読んでください。

- [Venice.ai](https://venice.ai)：プライベートで無修正のチャットと画像生成。API あり。
- [fal.ai](https://fal.ai)、[WaveSpeed](https://wavespeed.ai)、[Replicate](https://replicate.com)：大規模なホスト型モデルカタログ。NSFW の扱いはモデルやアカウント設定によって異なります。
- [RunPod](https://www.runpod.io)、[Vast.ai](https://vast.ai)：GPU を借りてオープンウェイトモデルを自分で動かせます（[セルフホスト](#セルフホストオープンウェイトモデル)を参照）。

---

## エージェントスキルと MCP サーバー

AI コーディングエージェント（Claude Code、Cursor、Codex、Windsurf、Cline、Gemini CLI、OpenClaw）は、**スキル**や **MCP サーバー**を通じてメディアを生成できるようになりました。普通の言葉で頼めば（「この画像から 5 秒のブドワール動画を作って」）、エージェントがモデルを選び、リクエストを組み立て、結果をダウンロードします。

| リソース | 種類 | インストール |
|---|---|---|
| 🌶️ [nsfw-ai-skill](https://github.com/Spicy-API/nsfw-ai-skill/blob/main/README.ja.md) | エージェントスキル：NSFW の画像・動画・編集・テキスト生成、プロンプトの膨らませ、費用の見積もり | `npx skills add Spicy-API/nsfw-ai-skill` |
| 🌶️ [SpicyAPI MCP サーバー](https://docs.spicyapi.ai/docs/mcp?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=skills-table)（`@spicyapi/mcp`） | MCP：モデル一覧、見積もり、タスクの作成 / 待機 / 再試行、ファイルのアップロード | `claude mcp add spicyapi -e SPICY_API_KEY=$SPICY_API_KEY -- npx --yes --package=@spicyapi/mcp spicyapi-mcp` |
| 🌶️ [SpicyAPI 公式スキル](https://github.com/Spicy-API/spicy-skill) | SpicyAPI の開発者向け機能をすべて扱えるエージェントスキル | `npx skills add Spicy-API/spicy-skill` |
| 🌶️ [SpicyAPI CLI](https://docs.spicyapi.ai/docs?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=skills-table)（`@spicyapi/cli`） | コマンドライン：モデル、見積もり、タスク、アップロード | `npx @spicyapi/cli --help` |
| [anthropics/skills](https://github.com/anthropics/skills) | リファレンス用のスキルとスキルの形式 | — |
| [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) | MCP サーバーのディレクトリ | — |

---

## セルフホスト・オープンウェイトモデル

無料で動かせて、すべて自分で管理でき、プラットフォームのフィルターもまったくありません。その代わり、ハードウェア、セットアップの手間、ライセンスの確認が必要です（商用利用の前に各ライセンスを読んでください）。

### 動画

- [Wan 2.2](https://github.com/Wan-Video/Wan2.2) と [Wan 2.1](https://github.com/Wan-Video/Wan2.1)：Alibaba のオープン動画モデル（Apache-2.0）。コミュニティの LoRA が非常に豊富で、ホスト型の Wan Spicy 版のベースでもあります。
- [HunyuanVideo](https://github.com/Tencent-Hunyuan/HunyuanVideo)：Tencent のオープン動画モデル。
- [LTX-Video](https://github.com/Lightricks/LTX-Video) と [LTX-2](https://github.com/Lightricks/LTX-2)：Lightricks の高速なオープン動画モデル。
- [CogVideoX](https://github.com/zai-org/CogVideo)：Zhipu のオープン動画モデル。
- [Mochi 1](https://github.com/genmoai/mochi)：Genmo のオープン動画モデル。
- [ComfyUI-WanVideoWrapper](https://github.com/kijai/ComfyUI-WanVideoWrapper)：LoRA に対応した、Wan 用 ComfyUI ノードの定番。

### 画像

- [Qwen-Image](https://github.com/QwenLM/Qwen-Image)：オープンな画像生成・編集モデル。
- [Z-Image](https://github.com/Tongyi-MAI/Z-Image)：Alibaba Tongyi の軽量なオープン画像モデル。
- [FLUX.1](https://github.com/black-forest-labs/flux)：バリアントごとにライセンスを確認してください（dev は非商用）。
- [Civitai](https://civitai.com) や [Hugging Face](https://huggingface.co) の SDXL / Pony Diffusion / Illustrious チェックポイント：NSFW 向けに調整されたコミュニティのチェックポイントがいちばん多く集まっています。

**ハードウェアの目安：** 画像モデルは VRAM 8〜12 GB で動きます。動画モデルは 16〜24 GB 欲しいところです（量子化版なら少なくて済みますが画質は落ちます）。GPU がなければ RunPod や Vast.ai で借りるか、ホスト型 API を使ってください。

---

## ローカル UI とワークフローツール

- [ComfyUI](https://github.com/Comfy-Org/ComfyUI)：画像・動画向けのノードベースのワークフロー。いちばん柔軟な選択肢です。
- [Stable Diffusion WebUI (A1111)](https://github.com/AUTOMATIC1111/stable-diffusion-webui)：拡張機能のエコシステムが巨大な定番 UI。
- [Forge](https://github.com/lllyasviel/stable-diffusion-webui-forge)：より高速で VRAM 消費の少ない A1111 のフォーク。
- [InvokeAI](https://github.com/invoke-ai/InvokeAI)：完成度の高いキャンバス型 UI。
- [Fooocus](https://github.com/lllyasviel/Fooocus)：いちばんシンプルなローカル SDXL UI。
- 🌶️ [SpicyAPI Studio](https://spicyapi.ai/ja/create?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=interfaces-ja)：テンプレート、[エフェクト](https://spicyapi.ai/ja/create/effects?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=interfaces-ja)、[スタイル](https://spicyapi.ai/ja/create/styles?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=interfaces-ja)が使える、ブラウザ上の画像・動画スタジオ。GPU は不要です。

---

## LoRA・チェックポイント・学習

**NSFW LoRA の探し方**

- [Civitai](https://civitai.com)：最大のライブラリ。ベースモデル（Wan 2.2、SDXL、Pony、Flux）で絞り込み、アカウント設定で成人向けコンテンツの表示を有効にします。
- [Hugging Face](https://huggingface.co)：LoRA やフルファインチューンが多数。各モデルカードのライセンスを確認してください。
- [Tensor.Art](https://tensor.art)：オンラインで実行もできるモデル共有サイト。

**API から LoRA を使う。** Wan 2.2 Spicy LoRA は `loras`、`high_noise_loras`、`low_noise_loras` を受け付けます（最大 3 つ）。high-noise の LoRA はデノイズの前半で構図と動きを、low-noise の LoRA は後半で質感とディテールを決めます。各 LoRA は、重みファイルへの直接の `path` と `scale`（0〜4、デフォルト 1）を持つオブジェクトです。変更は 1 回に 1 つの LoRA だけにしてください。正確なスキーマは [Wan 2.2 Spicy LoRA のページ](https://spicyapi.ai/ja/models/wan-2-2-spicy-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=lora-ja)を参照してください。

**自分で学習する**

- [kohya_ss](https://github.com/bmaltais/kohya_ss)：SD / SDXL 用 LoRA トレーナーの定番。
- [OneTrainer](https://github.com/Nerogar/OneTrainer)：GUI 付きで LoRA とフルファインチューンに対応。
- [ai-toolkit](https://github.com/ostris/ai-toolkit)：Flux、Wan などの新しいモデルの学習に対応。

学習に使うのは、自分が所有している、または権利を持っている画像だけにし、被写体は成人に限ってください。

---

## アップスケール・修復・ポストプロダクション

- [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN)：画像と動画の 4 倍アップスケール。
- [GFPGAN](https://github.com/TencentARC/GFPGAN) と [CodeFormer](https://github.com/sczhou/CodeFormer)：顔の修復。
- [RIFE](https://github.com/hzwer/ECCV2022-RIFE)：フレーム補間で、なめらかなスローモーションに。
- [FFmpeg](https://ffmpeg.org)：カット、結合、音声の追加（`ffmpeg -i clip.mp4 -i track.mp3 -c:v copy -shortest out.mp4`）。
- [Topaz Video AI](https://www.topazlabs.com)：商用の動画アップスケーラー。

---

## 成人向けコンテンツのプロンプトの書き方

良い NSFW プロンプトは、形容詞を並べたものではなく、撮影指示書のように読めるものです。

```
[Subject: adult, age range, look] + [Wardrobe or state] + [Action: one clear motion]
+ [Setting] + [Lighting] + [Camera] + [Style / quality]
```

（被写体：成人・年齢層・外見 ＋ 服装や状態 ＋ 動き：はっきりした動作を 1 つ ＋ 場所 ＋ ライティング ＋ カメラ ＋ スタイル・画質）

例（画像から動画）：

```
A woman in her early 30s in a black silk slip dress sits on the edge of a hotel bed.
She slowly slides one strap off her shoulder and looks up at the camera.
Warm tungsten bedside lamp, soft shadows, city lights through the window.
Slow push-in from medium shot to close-up, shallow depth of field, 35mm film look.
```

差がつくポイント：

1. **1 本の動画につきメインの動作は 1 つ。** 呼吸、髪の動き、ゆっくり振り向く動き、布の揺れは安定します。複雑な振り付けや 2 人の絡みは真っ先に崩れます。
2. **カメラを指定する。**「slow push-in」「static camera」「orbit left」のほうが「cinematic」よりずっと効きます。
3. **光源を書く。** キャンドルの光、窓からの光、ネオンのリムライト、ゴールデンアワー。
4. **見た目は開始フレームに任せる。** 画像から動画では、映っているものを全部書き直さず、*変化する*部分だけを書きます。
5. **動画は短く。** 体の形が崩れにくいのは 5 秒前後です。もっと長くしたいときは 2 回目の呼び出しで延長します。
6. **必ず成人の年齢を書く**（「in her 30s」「adult man in his 40s」など）。幼さを連想させる表現は使わないでください。

すぐ使えるプロンプト：静止画と編集は **[nsfw-ai-image-prompts](https://github.com/Spicy-API/nsfw-ai-image-prompts/blob/main/README.ja.md)**、動画は **[nsfw-ai-video-prompts](https://github.com/Spicy-API/nsfw-ai-video-prompts/blob/main/README.ja.md)** にあります。

---

## 選び方: 用途別ガイド

```
Do you have a GPU with 16 GB+ VRAM and time to tinker?
├── Yes → ComfyUI + Wan 2.2 / Qwen-Image / Z-Image open weights + Civitai LoRAs (free, most control)
└── No
    ├── No-code, in the browser → SpicyAPI Studio (uncensored image & video generator)
    └── Code or an AI agent
        ├── Best all-round video → Wan 3.0 (T2V / I2V / Ref2V, Freedom 96, $0.45 per 5 s)
        ├── Explicit from a still → Seedance 2.5 Spicy, Wan 2.7 Spicy or Vidu Q3 Spicy
        ├── Custom style / character → MiniMax H3 LoRA / Singularity LoRA (video), Qwen Image 2.1 LoRA (stills)
        ├── Volume on a budget  → Wan 2.6 Flash or Seedance 1.5 Pro Spicy ($0.11–0.13 per 5 s)
        ├── Stills              → Qwen Image 2.1 (Qwen Image 2.1 LoRA for your own style)
        ├── Text / roleplay     → Grok 4.7 or Grok 4.3
        └── From Claude Code / Cursor → nsfw-ai-skill or the SpicyAPI MCP server
```

上の図の要点：VRAM 16 GB 以上の GPU があっていじる時間もあるなら、ComfyUI とオープンウェイト（無料で自由度が最も高い）。なければ、コード不要なら SpicyAPI Studio。コードやエージェントを使うなら、総合力の高い動画は Wan 3.0（T2V / I2V / Ref2V、Freedom 96、5 秒 $0.45）、静止画から露骨な動画を作るなら Seedance 2.5 Spicy、Wan 2.7 Spicy、Vidu Q3 Spicy、独自のスタイルやキャラクターは MiniMax H3 LoRA / Singularity LoRA（動画）と Qwen Image 2.1 LoRA（静止画）、低予算で大量に作るなら Wan 2.6 Flash か Seedance 1.5 Pro Spicy（5 秒 $0.11〜0.13）、静止画は Qwen Image 2.1（自分のスタイルなら Qwen Image 2.1 LoRA）、テキストやロールプレイは Grok 4.7 か Grok 4.3、Claude Code / Cursor からは nsfw-ai-skill か SpicyAPI MCP サーバーです。

**用途別**

| 用途 | おすすめの構成 |
|---|---|
| 成人向けサブスクサイト・クリエイターのコンテンツ | 静止画は Qwen Image 2.1 → 動画は Wan 3.0 か Seedance 2.5 Spicy → Video Upscaler |
| AI コンパニオン・ロールプレイアプリ | チャットは Grok 4.7 か Grok 4.3 → 自撮り風画像は Qwen Image 2.1 → 短い動きは MiniMax H3 Spicy か Wan 3.0 |
| 趣味でたくさん試したい | Wan 2.6 Flash か Seedance 1.5 Pro Spicy で何度も試し、気に入ったものだけ Wan 3.0 で作り直す |
| アニメ・エロアニメ風コンテンツ | アニメ LoRA を付けた Qwen Image 2.1 LoRA → Vidu Q3 Spicy（Freedom 96.7）、または同じ LoRA を付けた Wan 2.2 Spicy LoRA |
| 官能小説・インタラクティブストーリー | テキストは Grok 4.7、挿絵は Qwen Image 2.1 |

---

## すべてのツールに共通するルール

以下は任意ではなく、どんな設定でも解除できません。

- **未成年は絶対に禁止。** 18 歳未満の人物、または 18 歳未満に*見える*人物を描いた性的コンテンツは、アニメ、イラスト、「設定上の年齢」という言い訳を含め、どんな画風でも一切禁止です。
- **記録に残る同意のない実在の人物は禁止。** 性的なディープフェイク、実在の人物の顔や頭部を性的コンテンツに合成すること、写真を「脱がせる」「ヌード化する」ことは禁止です。公人も例外ではありません。
- **なりすまし、嫌がらせ、恐喝、偽の証拠づくりは禁止。** 誰の容姿であっても同様です。
- **自分と視聴者の地域の法律に従う。** 国によっては、特定の架空の表現物や成人向けコンテンツそのものを規制しています。
- **AI 生成コンテンツであることを表示する。** プラットフォームや法律で求められる場合は必ず表示し、実在の人物を描く場合は同意の記録を保管してください。

SpicyAPI のルール全文：[コンテンツポリシー](https://spicyapi.ai/ja/legal/content-policy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=rules-ja)、[利用上のルール](https://spicyapi.ai/ja/legal/acceptable-use?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=rules-ja)。

---

## よくある質問

### 2026 年のおすすめ NSFW AI 動画生成ツールは？
SpicyAPI の公開テストでは、総合力で選ぶなら **Wan 3.0** です。Spicy Index 76.5（動画モデル 37 本中 2 位）、Freedom Score 96、露骨なテストプロンプトはすべて指示どおりに生成（9/9）、最大 30 秒、720p で 5 秒 $0.45。露骨な画像から動画なら、Spicy 版の **Seedance 2.5 Spicy**、**Wan 2.7 Spicy**、**Vidu Q3 Spicy**（Freedom 96.7〜100）がいちばん確実です。自分のスタイルを使うなら **MiniMax H3 LoRA**。標準の Seedance 2.0 は性能スコアがいちばん高いものの、露骨なプロンプトの表現を弱めることがよくあります（Freedom 70.4）。結果：[SpicyAPI リーダーボード](https://spicyapi.ai/ja/leaderboards?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=faq-ja)。

### 無修正の AI 画像生成でおすすめは？
ホスト型なら **Qwen Image 2.1**（Spicy Index 73、Freedom 96.3、1 枚 $0.024 から）。自分のスタイルを使うなら **Qwen Image 2.1 LoRA**（画像の Index で 1 位、80.5）と **MiniMax H3 Image LoRA**（Freedom 100）。有力な代替は **Seedream 5.0 Lite / Pro**、とにかく安く大量に作るなら **Z-Image Spicy**（$0.01235、Freedom 98.8）です。セルフホストなら、ComfyUI や Forge で SDXL、Pony、Illustrious のコミュニティチェックポイントを使います。

### 画像から NSFW 動画を作るには？
開始フレーム（架空の成人、または自分自身）を生成するか用意し、それを Wan 3.0 や Seedance 2.5 Spicy などの NSFW 対応の画像から動画モデルに送ります。プロンプトには動きとカメラを短く書きます。[API のクイックスタート](#クイックスタート-http-で-nsfw-画像から動画を生成)を見るか、ブラウザで使える[画像から動画ツール](https://spicyapi.ai/ja/create/image-to-video?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=faq-ja)を使ってください。

### 無料で使える NSFW AI 生成ツールはある？
オープンウェイトモデルをローカルで動かせば（ComfyUI + Wan 2.2、Qwen-Image、Z-Image）、ハードウェアと電気代以外はかかりません。ホスト型サービスは GPU にお金がかかるので有料です。SpicyAPI はサブスクリプションなしの出力単位の課金で、失敗したジョブは返金されます。

### いちばん安い NSFW AI 動画 API は？
SpicyAPI のカタログ（2026-09-27）で、露骨なテストに合格したモデルの中でいちばん安いのは **Wan 2.6 Flash**（720p で 5 秒 $0.1125、Freedom 100）と **Seedance 1.5 Pro Spicy**（720p で 5 秒 $0.13、480p・音声なしなら $0.06。Freedom 96.7）です。次いで Wan 2.2 Spicy と LTX 2.3 Spicy が 5 秒 $0.19（720p）です。

### NSFW AI で画像や動画を生成するのは合法？
**架空の成人**の性的コンテンツを生成することは多くの国で合法ですが、法律は国によって違い、どこでも違法なコンテンツもあります。未成年が関わるものすべてと、本人の同意なしに作った実在の人物の性的コンテンツです。作ったものや共有したものの責任はあなたにあります。これは法的助言ではありません。

### 「無修正（uncensored）」モデルと「Spicy」モデルの違いは？
「無修正」は、プラットフォームやモデルが成人向けのプロンプトを拒否しないことを指すのが一般的です。SpicyAPI の「Spicy」版は、成人向けの出力に合わせて調整された特定のモデルバージョンです。標準モデルにもそれぞれポリシーティアが付いているので、どのモデルが表現を弱めたりフィルターをかけたりするのかがわかります。

### Claude Code や Cursor などのエージェントで NSFW AI は使える？
使えます。[nsfw-ai-skill](https://github.com/Spicy-API/nsfw-ai-skill/blob/main/README.ja.md) をインストールする（`npx skills add Spicy-API/nsfw-ai-skill`）か、SpicyAPI MCP サーバーを追加し、`SPICY_API_KEY` を設定して、エージェントに普通の言葉で頼んでください。

---

## 関連リポジトリ

- **[nsfw-ai-image-prompts](https://github.com/Spicy-API/nsfw-ai-image-prompts/blob/main/README.ja.md)**：NSFW 画像プロンプトと無修正の画像編集プロンプト 104 本、実際の出力例付き。
- **[nsfw-ai-video-prompts](https://github.com/Spicy-API/nsfw-ai-video-prompts/blob/main/README.ja.md)**：NSFW 動画プロンプト 100 本以上、参照画像用プロンプト、ネガティブプロンプト、モデル別のコツ。
- **[nsfw-ai-skill](https://github.com/Spicy-API/nsfw-ai-skill/blob/main/README.ja.md)**：Claude Code、Cursor、Codex などから NSFW の画像・動画・テキストを生成できるエージェントスキル。
- **[spicy-skill](https://github.com/Spicy-API/spicy-skill)** · **[spicy-mcp](https://github.com/Spicy-API/spicy-mcp)** · **[spicy-sdk](https://github.com/Spicy-API/spicy-sdk)**：SpicyAPI 公式の開発者ツール。

## コントリビュート

競合サービスも含め、追加は歓迎します。まず [CONTRIBUTING.md](CONTRIBUTING.md) を読んでください。要点は、プルリクエスト 1 つにつきリソース 1 つ、中立的な 1 行の説明、有効なリンク。そして、同意のない画像、未成年が関わるコンテンツ、法律の回避を主な目的とするリソースは受け付けません。

## ライセンス

[CC0 1.0](LICENSE)。法律で認められる範囲で、コントリビューターはこのリストに関するすべての著作権を放棄しています。

<p align="center"><sub>役に立ったら ⭐ Star を付けてください。ほかのクリエイターが見つけやすくなります。</sub></p>
