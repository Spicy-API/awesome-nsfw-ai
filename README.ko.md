<!--
  Keywords: NSFW AI, 성인 AI, NSFW AI 영상 생성, NSFW AI 이미지 생성, 성인 AI 이미지 생성, 무검열 AI,
  무검열 AI 이미지 생성기, 무검열 AI 영상 생성기, AI 이미지 영상 변환, 이미지 투 비디오, 19금 AI,
  NSFW AI 이미지 편집, 무검열 LLM, 성인 AI 챗봇, AI 롤플레이, NSFW 프롬프트, NSFW AI API, Wan 2.2 Spicy, Seedance,
  awesome nsfw ai, nsfw ai generator, uncensored ai image generator, uncensored ai video generator,
  nsfw image to video, uncensored llm, nsfw ai api, wan 2.2 spicy, seedance spicy, nsfw ai skill, nsfw mcp
-->

<p align="center"><a href="README.md">English</a> · <a href="README.ja.md">日本語</a> · <b>한국어</b> · <a href="README.fr.md">Français</a> · <a href="README.es.md">Español</a></p>

<h1 align="center">Awesome NSFW AI</h1>

<p align="center">
  <b>성인 크리에이터와 개발자를 위해 엄선한 2026년 목록: 무검열 AI 이미지 생성기, NSFW AI 영상 생성기, 이미지 투 비디오 모델, 이미지 편집기, 무검열 LLM, API, 에이전트 스킬, MCP 서버와 각종 도구.</b>
</p>

<p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
  <img src="https://img.shields.io/badge/updated-2026--09--27-blue" alt="최종 업데이트 2026-09-27">
  <img src="https://img.shields.io/badge/18%2B-adults%20only-red" alt="18세 이상 전용">
  <img src="https://img.shields.io/badge/license-CC0--1.0-lightgrey" alt="CC0 라이선스">
</p>

<p align="center">
  <img src="assets/wolf-turn-and-look-back.gif" width="24%" alt="Wan 2.2 Spicy 이미지 투 비디오 결과물">
  <img src="assets/velvet-spiral-turn.gif" width="24%" alt="Seedance 2.0 Spicy 이미지 투 비디오 결과물">
  <img src="assets/silk-draught-pull.gif" width="24%" alt="Wan 2.7 Spicy 이미지 투 비디오 결과물">
  <img src="assets/hotel-window-turn.gif" width="24%" alt="Seedance 2.5 Spicy 이미지 투 비디오 결과물">
  <br><sub>Wan 2.2 Spicy, Seedance 2.0 Spicy, Wan 2.7 Spicy, Seedance 2.5 Spicy의 실제 결과물입니다. 정확한 프롬프트가 포함된 더 많은 예시는 <a href="https://github.com/Spicy-API/nsfw-ai-video-prompts/blob/main/README.ko.md#쇼케이스-실제-결과물과-프롬프트">nsfw-ai-video-prompts</a>에 있습니다.</sub>
</p>

<p align="center">
  <a href="#무검열-ai-영상-생성기">영상</a> ·
  <a href="#무검열-ai-이미지-생성기">이미지</a> ·
  <a href="#nsfw-ai-이미지-편집기와-얼굴-도구">편집</a> ·
  <a href="#무검열-llm과-롤플레이">LLM</a> ·
  <a href="#nsfw-ai-api">API</a> ·
  <a href="#에이전트-스킬과-mcp-서버">스킬 &amp; MCP</a> ·
  <a href="#셀프-호스팅-및-오픈-웨이트-모델">셀프 호스팅</a> ·
  <a href="#자주-묻는-질문-faq">FAQ</a>
</p>

> **18세 이상 전용.** 이 목록은 성인 콘텐츠를 만들 수 있는 도구를 다룹니다. 여기 있는 모든 리소스는 가상의 성인, 또는 문서로 된 동의를 한 실제 성인에게만 사용해야 하며, 본인과 시청자가 있는 곳의 법률 안에서 사용해야 합니다. [모든 도구에 적용되는 규칙](#모든-도구에-적용되는-규칙)을 확인하세요.

> **고지:** 이 목록은 무검열 이미지·영상·텍스트 모델을 사용한 만큼만 결제하는 API인 [SpicyAPI](https://spicyapi.ai/ko?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=disclosure-ko) 팀이 관리합니다. SpicyAPI 항목에는 🌶️ 표시가 있습니다. 서드파티 도구는 돈을 받고 올린 것이 아니라 유용하기 때문에 실었습니다. 경쟁 서비스를 추가하는 풀 리퀘스트도 환영합니다.

---

## 한눈에 보기: 상황별 추천

| 이런 걸 하고 싶다면 | 여기서 시작하세요 | 이유 (SpicyAPI 리더보드, 2026-09-27) |
|---|---|---|
| 전반적으로 가장 뛰어난 NSFW 영상 모델 | [Wan 3.0](https://spicyapi.ai/ko/models/wan-3-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ko) | Spicy Index 76.5(37개 중 2위), Freedom 96. 노골적 테스트 프롬프트를 모두 렌더링(9/9). T2V, I2V, 레퍼런스 투 비디오 최대 30초. 720p 5초당 $0.45 |
| 나만의 스타일이나 캐릭터로 NSFW 영상 만들기 | [MiniMax H3 LoRA](https://spicyapi.ai/ko/models/minimax-h3-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ko) 또는 [MiniMax H3 Singularity LoRA](https://spicyapi.ai/ko/models/minimax-h3-singularity-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ko) | Spicy Index 75.2 / 72.8, Freedom 98.3 / 100 |
| Spicy 에디션으로 무검열 이미지 투 비디오 | 🌶️ [Seedance 2.5 Spicy](https://spicyapi.ai/ko/models/seedance-2-5-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ko), 🌶️ [Wan 2.7 Spicy](https://spicyapi.ai/ko/models/wan-2-7-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ko) 또는 🌶️ [Vidu Q3 Spicy](https://spicyapi.ai/ko/models/vidu-q3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ko) | Freedom 96.7–100, 노골적 테스트 프롬프트를 모두 렌더링(3/3) |
| NSFW 영상을 저렴하게 대량으로 만들기 | [Wan 2.6 Flash](https://spicyapi.ai/ko/models/wan-2-6-flash?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ko) 또는 🌶️ [Seedance 1.5 Pro Spicy](https://spicyapi.ai/ko/models/seedance-1-5-pro-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ko) | 5초당 $0.11–0.13(720p)에 Freedom 100 / 96.7 |
| 무검열 텍스트 투 이미지 모델 | [Qwen Image 2.1](https://spicyapi.ai/ko/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ko) | Spicy Index 73, Freedom 96.3, 이미지당 $0.024부터. 긴 프롬프트, 15가지 화면비 |
| 나만의 스타일로 이미지 만들기 (애니 포함) | [Qwen Image 2.1 LoRA](https://spicyapi.ai/ko/models/qwen-image-2-1-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ko) 또는 [MiniMax H3 Image LoRA](https://spicyapi.ai/ko/models/minimax-h3-image-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ko) | 이미지 Spicy Index 1위와 2위(80.5 / 74.5), Freedom 92 / 100 |
| 무검열 AI 이미지 편집기 | [Qwen Image 2.1 Edit](https://spicyapi.ai/ko/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ko) | 위와 같은 모델 계열. 레퍼런스 이미지 1–10장 + 지시문 1개, 마스크 불필요 |
| 무검열 채팅, 롤플레이, 프롬프트 작성 | [Grok 4.7](https://spicyapi.ai/ko/models/grok-4-7?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ko) 또는 [Grok 4.3](https://spicyapi.ai/ko/models/grok-4-3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ko) | 텍스트 보드에서 Freedom 100 / 98.9. Grok 4.3이 가장 빠름(중앙값 약 4초) |
| 전부 로컬에서 무료로 돌리기 | [ComfyUI](https://github.com/Comfy-Org/ComfyUI) + [Wan 2.2](https://github.com/Wan-Video/Wan2.2) 오픈 웨이트 | 고성능 GPU 필요 (VRAM 24 GB면 여유 있음) |
| Claude Code / Cursor가 대신 생성하게 하기 | [nsfw-ai-skill](https://github.com/Spicy-API/nsfw-ai-skill/blob/main/README.ko.md) 또는 공식 [SpicyAPI MCP 서버](https://docs.spicyapi.ai/docs/mcp?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr) | 에이전트에서 자연어로 생성 |
| 복사해서 바로 쓰는 이미지 프롬프트 | [nsfw-ai-image-prompts](https://github.com/Spicy-API/nsfw-ai-image-prompts/blob/main/README.ko.md) | Qwen Image 2.1, Seedream 5.0 등을 위한 이미지·편집 프롬프트 104개와 실제 결과물 사례 72개 |
| 복사해서 바로 쓰는 영상 프롬프트 | [nsfw-ai-video-prompts](https://github.com/Spicy-API/nsfw-ai-video-prompts/blob/main/README.ko.md) | 바로 쓸 수 있는 영상 프롬프트 116개와 프롬프트가 포함된 실제 결과물 사례 128개 |

점수는 공개된 [SpicyAPI 리더보드](https://spicyapi.ai/ko/leaderboards?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=tldr-ko)에서 가져왔습니다(방법론 v2.1, 2026-09-14부터 2026-09-27까지 실시한 테스트. [모델 평가 방식](#이-목록의-모델-평가-방식) 참고). 가격은 카탈로그에 올라온 등급 기준이며, 해상도가 높거나, 오디오가 있거나, 클립이 길면 더 비쌉니다.

---

## 목차

- [한눈에 보기: 상황별 추천](#한눈에-보기-상황별-추천)
- [NSFW AI와 무검열 AI, 정확히 무슨 뜻일까](#nsfw-ai와-무검열-ai-정확히-무슨-뜻일까)
- [무검열 AI 영상 생성기](#무검열-ai-영상-생성기)
  - [무검열 영상 모델 전체 목록 (인기순)](#무검열-영상-모델-전체-목록-인기순)
  - [NSFW 영상 5초 생성 비용](#nsfw-영상-5초-생성-비용)
- [무검열 AI 이미지 생성기](#무검열-ai-이미지-생성기)
- [NSFW AI 이미지 편집기와 얼굴 도구](#nsfw-ai-이미지-편집기와-얼굴-도구)
- [무검열 LLM과 롤플레이](#무검열-llm과-롤플레이)
- [NSFW AI API](#nsfw-ai-api)
- [에이전트 스킬과 MCP 서버](#에이전트-스킬과-mcp-서버)
- [셀프 호스팅 및 오픈 웨이트 모델](#셀프-호스팅-및-오픈-웨이트-모델)
- [로컬 UI와 워크플로 도구](#로컬-ui와-워크플로-도구)
- [LoRA, 체크포인트, 학습](#lora-체크포인트-학습)
- [업스케일링, 복원, 후반 작업](#업스케일링-복원-후반-작업)
- [성인 콘텐츠용 프롬프트 작성법](#성인-콘텐츠용-프롬프트-작성법)
- [어떤 도구를 고를까: 선택 가이드](#어떤-도구를-고를까-선택-가이드)
- [모든 도구에 적용되는 규칙](#모든-도구에-적용되는-규칙)
- [자주 묻는 질문 (FAQ)](#자주-묻는-질문-faq)
- [관련 저장소](#관련-저장소)
- [기여하기](#기여하기)

---

## NSFW AI와 무검열 AI, 정확히 무슨 뜻일까

**NSFW AI**는 성인을 위한 노출 또는 성적 콘텐츠를 만들 수 있는 모든 생성형 모델이나 도구를 말합니다. **무검열 AI**(uncensored AI)는 이보다 느슨한 표현으로, 성인용 프롬프트를 거부하거나 결과물을 블러 처리하지 않는 모델을 가리킵니다.

NSFW 요청이 통하는지는 세 가지가 결정하는데, 사람들이 이 셋을 자주 혼동합니다.

1. **모델.** 성인 콘텐츠 출력을 허용하도록 학습되거나 파인튜닝된 모델이 있습니다. 반대로 거부하도록 학습된 모델도 있으며, 이건 플랫폼 설정으로 바꿀 수 없습니다.
2. **플랫폼 자체 필터.** 많은 호스팅 서비스가 모델 위에 검열 레이어(프롬프트 차단 목록, 출력 분류기, 블러 처리)를 추가합니다. 모델이 허용적이어도 필터가 엄격하면 결국 차단됩니다.
3. **거주 지역 법률과 플랫폼 약관.** "모델이 할 수 있다"가 "해도 된다"는 뜻은 아닙니다. 어떤 콘텐츠는 어디서든 불법입니다([규칙](#모든-도구에-적용되는-규칙) 참고).

아래 목록은 이렇게 읽으면 됩니다.

| 표시 | 의미 |
|---|---|
| **Spicy / NSFW 에디션** | 성인 콘텐츠 출력에 맞춰 튜닝하거나 설정한 모델 버전. SpicyAPI에서는 이름에 "Spicy"가 붙습니다. |
| **성인 콘텐츠 가능** | 성인 콘텐츠를 대체로 허용하지만 일부 요청은 순화하거나 거부할 수 있는 범용 모델. |
| **필터 적용** | 모델이나 제공업체가 자체 콘텐츠 필터를 적용함. SFW 작업에는 괜찮지만 NSFW에는 믿기 어려움. |

SpicyAPI 공개 카탈로그의 모든 모델에는 정책 등급(`unrestricted`, `softened`, `borderline`, `filtered`)이 붙어 있고, [리더보드](https://spicyapi.ai/ko/leaderboards?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=definitions-ko)에는 반복 테스트 프롬프트로 측정한 **Freedom Score**가 공개되어 있습니다. 플랫폼은 모델 위에 자체 필터를 추가하지 않으며, 필터링이 있다면 모델 제공업체 쪽에서 오는 것입니다.

### 이 목록의 모델 평가 방식

이 목록의 추천은 마케팅 문구가 아니라 SpicyAPI가 공개한 테스트 결과를 따릅니다.

- **Freedom Score (0–100)**: 성인용 프롬프트가 요구한 내용을 모델이 얼마나 안정적으로 렌더링하는지를 다섯 단계에 걸쳐 측정합니다. L1 암시적 표현, L2 부분 노출, L3 노출, L4 노골적 표현, L5 극단적 표현. 단계마다 20점 × 통과율 × 신뢰도로 점수를 매기므로, 순화되거나 다른 이미지로 바꿔치기된 결과물은 점수가 깎입니다. ✅ 90 이상 · ◐ 70–89 · ⚠️ 70 미만 · 🧪 지금까지 테스트 실행이 15회 미만이므로, 낮은 숫자는 거부가 아니라 테스트 범위가 부족하다는 뜻입니다.
- **Spicy Index (0–100)**: 현재는 *잠정* 점수로, 공개 사양(네이티브 해상도, 최장 클립 길이, 오디오, 입력 방식 등)을 바탕으로 한 성능 점수입니다. 아레나 품질 투표가 아직 반영되지 않아 시각적 품질은 아직 측정하지 않습니다.
- **엔지니어링 경로 점검**: 모델을 목록에 올리기 전에 팀이 모든 업스트림 경로에서 노골적인 테스트 케이스를 생성하고, 다운로드한 결과물을 프레임 단위로 검사합니다(일부 제공업체는 안전한 이미지로 몰래 바꿔 보내기 때문에 "성공" 상태만으로는 부족합니다). 일부 경로에서만 노골적인 콘텐츠를 렌더링하는 모델은 여기서 추천하지 않습니다.

모델별 전체 리포트와 단계별 실행 횟수: [SpicyAPI 리더보드](https://spicyapi.ai/ko/leaderboards?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=method-ko). L4/L5 테스트 결과물은 절대 공개하지 않습니다.

---

## 무검열 AI 영상 생성기

NSFW AI 영상을 만드는 가장 안정적인 방법은 이미지 투 비디오(I2V)입니다. 첫 프레임으로 룩을 정하고, 모델은 그 이미지에 움직임만 입히면 되기 때문입니다. 텍스트 투 비디오(T2V)와 레퍼런스 투 비디오(Ref2V, "이 이미지들 속 캐릭터를 새 장면에 넣기")는 아래 표준 모델에서 지원합니다.

### 무검열 영상 모델 전체 목록 (인기순)

SpicyAPI 카탈로그와 같은 순서입니다. 인기순이며, 같은 계열 안에서는 최신 버전이 먼저입니다. 🌶️ **Spicy** 에디션은 성인 콘텐츠 출력에 맞춰 튜닝되어 있습니다. 여기 실린 **Standard**(표준) 모델은 카탈로그 등급이 `unrestricted`(제공업체가 콘텐츠 필터를 적용하지 않음)여서 성인 프롬프트도 받아들입니다. 가격은 가장 저렴한 등급 기준입니다. 카탈로그 확인일: <!-- catalog:date -->
2026-09-27
<!-- /catalog:date -->

<!-- catalog:video -->
| 모델 | 유형 | 작업 | 길이 | 최저가 | Spicy Index | Freedom |
|---|---|---|---|---|---|---|
| [Seedance 2.5 Spicy](https://spicyapi.ai/ko/models/seedance-2-5-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 🌶️ Spicy | I2V | 4–30 s | $0.216/s | 56.5 | ✅ 96.7 |
| [Seedance 2.5](https://spicyapi.ai/ko/models/seedance-2-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | I2V, Ref2V, T2V | 4–30 s | $0.1234/s | 69.5 | ◐ 80.9 |
| [Seedance 2.0 Spicy](https://spicyapi.ai/ko/models/seedance-2-0-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 🌶️ Spicy | I2V | 4–15 s | $0.114/s | 61.5 | ✅ 93.3 |
| [Seedance 2.0](https://spicyapi.ai/ko/models/seedance-2-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | I2V, Ref2V, T2V | 4–15 s | $0.07/s | 81.5 | ◐ 70.4 |
| [Wan 3.0 Prime](https://spicyapi.ai/ko/models/wan-3-0-prime?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | I2V, Ref2V, T2V | 2–30 s | $0.0612/s | 76.5 | ◐ 78 |
| [Wan 3.0](https://spicyapi.ai/ko/models/wan-3-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | I2V, Ref2V, T2V | 2–30 s | $0.045/s | 76.5 | ✅ 96 |
| [MiniMax H3 Spicy](https://spicyapi.ai/ko/models/minimax-h3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 🌶️ Spicy | I2V | 3–15 s | $0.038/s | 29.5 | ✅ 97.5 |
| [MiniMax H3](https://spicyapi.ai/ko/models/minimax-h3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | I2V, Ref2V, T2V | 4–15 s | $0.025/s | 72.5 | 🧪 33.3 |
| [MiniMax H3 Singularity LoRA](https://spicyapi.ai/ko/models/minimax-h3-singularity-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | I2V, Ref2V | 3–15 s | $0.06/s | 72.8 | ✅ 100 |
| [LTX 2.5](https://spicyapi.ai/ko/models/ltx-2-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | I2V, T2V | 5–20 s | $0.09/s | 66 | ◐ 80.3 |
| [Wan 3.0 Pro Prime](https://spicyapi.ai/ko/models/wan-3-0-pro-prime?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | I2V, Ref2V, T2V | 2–30 s | $0.234/s | 76.5 | ◐ 82 |
| [Wan 3.0 Pro](https://spicyapi.ai/ko/models/wan-3-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | I2V, Ref2V, T2V | 2–30 s | $0.144/s | 76.5 | ◐ 82 |
| [MiniMax H3 LoRA](https://spicyapi.ai/ko/models/minimax-h3-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | I2V, Ref2V, T2V | 3–15 s | $0.05/s | 75.2 | ✅ 98.3 |
| [HappyHorse 1.1](https://spicyapi.ai/ko/models/happyhorse-1-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | I2V, Ref2V, T2V | 3–15 s | $0.14/s | 62.5 | ⚠️ 65.1 |
| [Seedance 2.0 Mini Spicy](https://spicyapi.ai/ko/models/seedance-2-0-mini-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 🌶️ Spicy | I2V | 4–15 s | $0.0387/s | 44.5 | ✅ 93.3 |
| [Seedance 2.0 Mini](https://spicyapi.ai/ko/models/seedance-2-0-mini?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | I2V, Ref2V, T2V | 4–15 s | $0.01097/s | 64.5 | ⚠️ 64.9 |
| [Wan 2.7 Spicy](https://spicyapi.ai/ko/models/wan-2-7-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 🌶️ Spicy | I2V | 2–15 s | $0.1235/s | 46.5 | ✅ 100 |
| [LTX 2.3 Spicy](https://spicyapi.ai/ko/models/ltx-2-3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 🌶️ Spicy | I2V | 3–20 s | $0.019/s | 33.5 | ◐ 89.2 |
| [LTX 2.3 Spicy LoRA](https://spicyapi.ai/ko/models/ltx-2-3-spicy-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 🌶️ Spicy | I2V | 3–20 s | $0.0285/s | 34.8 | ◐ 83.8 |
| [Seedance 2.0 Fast Spicy](https://spicyapi.ai/ko/models/seedance-2-0-fast-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 🌶️ Spicy | I2V | 4–15 s | $0.081/s | 44.5 | ✅ 90 |
| [Seedance 2.0 Fast](https://spicyapi.ai/ko/models/seedance-2-0-fast?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | I2V, Ref2V, T2V | 4–15 s | $0.02254/s | 64.5 | ⚠️ 68.2 |
| [Vidu Q3 Turbo](https://spicyapi.ai/ko/models/vidu-q3-turbo?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | I2V | 1–16 s | $0.042/s | 39.5 | ✅ 93.3 |
| [Vidu Q3 Spicy](https://spicyapi.ai/ko/models/vidu-q3-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 🌶️ Spicy | I2V | 1–16 s | $0.0665/s | 46.5 | ✅ 96.7 |
| [Vidu Q3](https://spicyapi.ai/ko/models/vidu-q3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | I2V | 1–16 s | $0.07/s | 46.5 | ✅ 93.3 |
| [Vidu Q3 Pro](https://spicyapi.ai/ko/models/vidu-q3-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | I2V | 1–16 s | $0.054/s | 36.5 | ✅ 93.3 |
| [Seedance 1.5 Pro Spicy](https://spicyapi.ai/ko/models/seedance-1-5-pro-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 🌶️ Spicy | I2V | 4–12 s | $0.012/s | 48.5 | ✅ 96.7 |
| [Seedance 1.5 Pro](https://spicyapi.ai/ko/models/seedance-1-5-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | I2V, T2V | 4–12 s | $0.0112/s | 46 | ✅ 90 |
| [Wan 2.6 Flash](https://spicyapi.ai/ko/models/wan-2-6-flash?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | I2V | 5, 10, 15 s | $0.0225/s | 31.5 | ✅ 100 |
| [Wan 2.6 Spicy](https://spicyapi.ai/ko/models/wan-2-6-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 🌶️ Spicy | I2V | 5, 10, 15 s | $0.095/s | 46.5 | ✅ 96.7 |
| [Wan 2.6](https://spicyapi.ai/ko/models/wan-2-6?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | I2V, Ref2V, T2V | 5, 10, 15 s | $0.065/s | 58.5 | 🧪 8.7 |
| [Wan 2.5](https://spicyapi.ai/ko/models/wan-2-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | I2V, T2V | 5, 10 s | $0.045/s | 46 | ✅ 99 |
| [Wan 2.2 Spicy](https://spicyapi.ai/ko/models/wan-2-2-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 🌶️ Spicy | I2V | 5, 8 s | $0.019/s | 23.5 | ✅ 91.2 |
| [Wan 2.2 Spicy LoRA](https://spicyapi.ai/ko/models/wan-2-2-spicy-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 🌶️ Spicy | I2V, Extend | 5, 8 s | $0.024/s | 25 | ◐ 74.8 |
| [Wan 2.2 LoRA](https://spicyapi.ai/ko/models/wan-2-2-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | I2V | 5, 8 s | $0.024/s | 22.5 | ◐ 88.8 |
<!-- /catalog:video -->

테스트 기반 추천(노골적 = 요청한 대로 렌더링된 L4 테스트 프롬프트 수):

- **전반적 최고: Wan 3.0.** Spicy Index 76.5, Freedom 96, 노골적 9/9, 720p 5초당 $0.45, 최대 30초 클립. Wan 3.0 Pro와 Pro Prime도 노골적 프롬프트를 렌더링하지만(9/9) Freedom 점수는 더 낮으며(82), 대부분 극단적 단계(L5)에서 점수가 깎였습니다.
- **커스텀 스타일과 캐릭터: MiniMax H3 LoRA**(Index 75.2, Freedom 98.3, 노골적 11/13)와 **MiniMax H3 Singularity LoRA**(Index 72.8, Freedom 100, 노골적 8/8).
- **성인 콘텐츠용 Seedance: Seedance 2.5**(Index 69.5, Freedom 80.9, 노골적 8/9)는 텍스트 투 비디오와 레퍼런스 투 비디오용입니다. 무검열 이미지 투 비디오에는 🌶️ **Seedance 2.5 Spicy** 에디션을 쓰세요(Freedom 96.7, 노골적 3/3).
- **가장 허용적인 모델: Wan 2.7 Spicy, Wan 2.6 Flash, MiniMax H3 Singularity LoRA**(Freedom 100), **Wan 2.5**(99).
- **저예산: Wan 2.6 Flash**(5초당 $0.11, Freedom 100), 🌶️ **Seedance 1.5 Pro Spicy**($0.13, Freedom 96.7), **MiniMax H3**(768p 5초당 $0.185. 테스트 클립 14개가 모두 요청대로 나왔으며, Freedom 수치가 낮은 것은 아직 테스트하지 않은 단계가 있기 때문일 뿐입니다). 🌶️ Wan 2.2 Spicy와 LTX 2.3 Spicy는 $0.19이지만 최상위 단계를 순화하는 경우가 더 잦습니다.
- **테스트에서 노골적 프롬프트를 순화한 모델:** 같은 계열의 Spicy 에디션을 대신 쓰세요. 표준 Seedance 2.0(Freedom 70.4, 노골적 1/9. 영상 모델 중 성능 점수가 가장 높아서 암시적인 수위의 작업에는 매우 좋습니다), Seedance 2.0 Fast / Mini(68.2 / 64.9), HappyHorse 1.1(65.1), Wan 2.2(43.1).
- **아직 테스트 데이터가 부족한 모델:** 표준 Wan 2.6(5회 실행). 🌶️ Wan 2.6 Spicy 에디션은 테스트를 모두 마쳤습니다(Freedom 96.7).
- **리뷰에서 경고하는 점:** Wan 3.0은 가끔 프롬프트보다 수위를 더 높이고(마지막 몇 초를 확인하세요), 작업 하나에 약 3.5분이 걸리며, 레퍼런스 투 비디오에서는 실제 얼굴 사진을 거부합니다. Seedance 2.5는 긴 스크립트를 가장 충실하게 따르고, Seedance 2.5 Spicy는 가장 높은 단계에서 더 과감하게 표현합니다.

일부 영상 엔드포인트는 정해진 블록 단위로 과금합니다(예를 들어 5초 블록 단위 모델에서 6초 클립을 만들면 10초로 과금). 블록 길이는 모델 페이지에 나와 있으며, 견적 금액이 청구될 수 있는 최대 금액입니다. 전체 모델은 [SpicyAPI › 무검열 AI 모델](https://spicyapi.ai/ko/explore/uncensored-ai-models?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=video-table-ko)에서 둘러보고 필터링할 수 있습니다.

### NSFW 영상 5초 생성 비용

720p 5초 클립 1개(MiniMax는 768p)의 비용을 2026-09-27 리더보드 가격 축 기준으로 Freedom Score와 함께 정리했습니다. 해상도가 낮으면 더 저렴합니다.

| 모델 | 클립 1개 (5초) | 클립 100개 | 클립 1,000개 | Freedom |
|---|---|---|---|---|
| Wan 2.6 Flash | $0.11 | $11.25 | $112.50 | ✅ 100 |
| 🌶️ Seedance 1.5 Pro Spicy | $0.13 | $13.00 | $130 | ✅ 96.7 |
| MiniMax H3 | $0.185 | $18.50 | $185 | 🧪 33.3 (클립 14/14개가 요청대로 생성) |
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

이 모델들 대부분은 480p가 대략 절반 가격입니다(예를 들어 5초당 Wan 2.2 Spicy $0.095, Seedance 1.5 Pro Spicy $0.06). 실패한 작업은 자동으로 환불됩니다.

---

## 무검열 AI 이미지 생성기

**추천: [Qwen Image 2.1](https://spicyapi.ai/ko/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-ko)**: Spicy Index 73, Freedom 96.3(노골적 5/6), 1k 기준 이미지당 $0.024부터. 긴 브리프(최대 5,000자)를 잘 따르고, 1k, 1.5k, 2k 해상도에서 15가지 화면비를 지원하며, 같은 모델 계열에서 레퍼런스 이미지 1–10장으로 편집도 할 수 있습니다.

그 밖의 테스트 기반 추천:

- **나만의 스타일이나 캐릭터 (애니 포함): [Qwen Image 2.1 LoRA](https://spicyapi.ai/ko/models/qwen-image-2-1-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-ko)**: 이미지 Spicy Index 1위(80.5), Freedom 92, LoRA 최대 3개. **[MiniMax H3 Image LoRA](https://spicyapi.ai/ko/models/minimax-h3-image-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-ko)**: Index 74.5, Freedom 100(노골적 8/8), MiniMax H3 영상과 짝을 맞추기 좋습니다.
- **Seedream: [Seedream 5.0 Lite](https://spicyapi.ai/ko/models/seedream-5-0-lite?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-ko) / [Seedream 5.0 Pro](https://spicyapi.ai/ko/models/seedream-5-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-ko)**: Index 73, Freedom 96 / 94.3. Seedream 4.0은 성능 점수(74)는 높지만 Freedom(74.7)은 더 낮습니다.
- **이미지 속 텍스트 (포스터, 표지): [Qwen Image 3.0 Pro](https://spicyapi.ai/ko/models/qwen-image-3-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-ko)**: Freedom 98, 노골적 6/6.
- **가장 저렴: 🌶️ [Z-Image Spicy](https://spicyapi.ai/ko/models/z-image-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-ko)** ($0.01235, Freedom 98.8)와 [Z-Image Turbo LoRA](https://spicyapi.ai/ko/models/z-image-turbo-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-pick-ko)($0.012, Freedom 95). 성능 점수가 더 낮으므로(32 / 46.5) 대량 생성과 초안용으로 쓰세요.
- **NSFW에는 비추천:** Krea 2(Freedom 10), Wan 2.7 / Wan 2.7 Pro 텍스트 투 이미지(노출과 노골적 단계를 대부분 순화), FLUX.1 Dev LoRA(75, 노골적 0/6). Prefect Pony XL은 지금까지 테스트 실행이 3회뿐입니다(Freedom 36). 테스트를 거친 NSFW 추천이 아니라 태그 프롬프트 방식의 애니 선택지로 보세요.

무검열 이미지 모델 전체 목록 (카탈로그 순서):

<!-- catalog:image -->
| 모델 | 유형 | 작업 | 최저가 | Spicy Index | Freedom |
|---|---|---|---|---|---|
| [Qwen Image 2.1](https://spicyapi.ai/ko/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | Edit, T2I | $0.024/image | 73 | ✅ 96.3 |
| [Qwen Image 2.1 LoRA](https://spicyapi.ai/ko/models/qwen-image-2-1-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | Edit, T2I | $0.03/image | 80.5 | ✅ 92 |
| [MiniMax H3 Image LoRA](https://spicyapi.ai/ko/models/minimax-h3-image-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | Edit, T2I | $0.042/image | 74.5 | ✅ 100 |
| [Qwen Image 3.0 Pro](https://spicyapi.ai/ko/models/qwen-image-3-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | Edit, T2I | $0.04/image | 56 | ✅ 98 |
| [Qwen Image 3.0](https://spicyapi.ai/ko/models/qwen-image-3-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | Edit, T2I | $0.03/image | 56 | ✅ 96 |
| [Seedream 5.0 Pro](https://spicyapi.ai/ko/models/seedream-5-0-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | Edit, T2I | $0.036/image | 73 | ✅ 94.3 |
| [Qwen Image Edit Spicy](https://spicyapi.ai/ko/models/qwen-image-spicy-edit?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 🌶️ Spicy | Edit | $0.038/image | 14 | ✅ 96 |
| [Seedream 5.0 Lite](https://spicyapi.ai/ko/models/seedream-5-0-lite?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | Edit, T2I | $0.0345/image | 73 | ✅ 96 |
| [Qwen Image 2](https://spicyapi.ai/ko/models/alibaba-qwen-image-2?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | Edit, T2I | $0.035/image | 34 | ✅ 96.7 |
| [Qwen Image 2512 LoRA](https://spicyapi.ai/ko/models/qwen-image-2512-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | Edit, T2I | $0.03/image | 50.5 | ✅ 92.5 |
| [Z-Image Spicy Pro](https://spicyapi.ai/ko/models/z-image-spicy-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 🌶️ Spicy | T2I | $0.019/image | 38 | ✅ 100 |
| [Z-Image Spicy](https://spicyapi.ai/ko/models/z-image-spicy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 🌶️ Spicy | T2I | $0.01235/image | 32 | ✅ 98.8 |
| [Z-Image](https://spicyapi.ai/ko/models/z-image?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | T2I | $0.01/image | 17 | ✅ 100 |
| [Z-Image Turbo LoRA](https://spicyapi.ai/ko/models/z-image-turbo-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | Edit, T2I | $0.012/image | 46.5 | ✅ 95 |
| [Seedream 4.0](https://spicyapi.ai/ko/models/seedream-4-0?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | Edit, T2I | $0.03/image | 74 | ◐ 74.7 |
| [Prefect Pony XL](https://spicyapi.ai/ko/models/prefect-pony-xl?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | T2I | $0.015/image | 30 | 🧪 36 |
| [FLUX.1 Dev LoRA](https://spicyapi.ai/ko/models/flux-1-dev-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=model-table-ko) | 표준 | T2I | $0.018/image | 32.5 | ◐ 75 |
<!-- /catalog:image -->

코드 없이 쓰는 방법: [SpicyAPI Studio의 무검열 AI 이미지 생성기](https://spicyapi.ai/ko/create/uncensored-ai-image-generator?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-studio-ko)는 같은 모델을 브라우저에서 실행하며, 스타일과 화면비를 고를 수 있고 생성 전에 가격을 보여 줍니다.

어떤 이미지 모델이 어디까지 허용하는지 직접 비교한 테스트는 [덜 제한적인 이미지 모델 평가](https://spicyapi.ai/ko/blog/less-restrictive-model-evaluation?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=image-eval-ko)를 참고하세요.

---

## NSFW AI 이미지 편집기와 얼굴 도구

| 도구 | 기능 | 가격 |
|---|---|---|
| [Qwen Image 2.1 Edit](https://spicyapi.ai/ko/models/qwen-image-2-1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ko) | **가상** 인물 또는 동의한 인물의 레퍼런스 이미지 1–10장으로 하는 무검열 편집: 의상, 포즈, 배경, 조명 변경 (카탈로그 등급 `unrestricted`) | 이미지당 $0.036 |
| 🌶️ [Qwen Image Edit Spicy](https://spicyapi.ai/ko/models/qwen-image-spicy-edit?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ko) | 이미지 1장에 지시문으로 하는 편집(Freedom 96이지만 성능 점수는 14로 낮음: 입력 이미지 1장, 크기·화면비 조절 불가). Qwen Image 2.1 Edit을 먼저 써 보세요 | 이미지당 $0.038 |
| [Image Expander](https://spicyapi.ai/ko/models/image-expander-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ko) | 아웃페인팅으로 프레임을 더 넓게 또는 더 길게 확장 | 이미지당 $0.024 |
| [Object Eraser](https://spicyapi.ai/ko/models/object-eraser-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ko) | 본인 소유 이미지에서 사물, 로고, 워터마크 제거 | 이미지당 $0.03 |
| [Image Upscaler](https://spicyapi.ai/ko/models/image-upscaler-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ko) / [Video Upscaler](https://spicyapi.ai/ko/models/video-upscaler-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ko) | 완성된 결과물을 선명하게 하고 확대 | 이미지당 $0.012, 초당 $0.006 |
| [Face Swap](https://spicyapi.ai/ko/models/face-swap-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ko), [Head Swap](https://spicyapi.ai/ko/models/head-swap-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ko), [Video Character Swap](https://spicyapi.ai/ko/models/character-swap-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ko) | 이미지와 클립 전반에서 하나의 **가상** 캐릭터를 일관되게 유지 | 이미지당 $0.013, 영상은 초당 $0.064부터 |
| [Lip Sync](https://spicyapi.ai/ko/models/lip-sync-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ko), [Talking Avatar](https://spicyapi.ai/ko/models/talking-avatar-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ko), [Video Sound Effects](https://spicyapi.ai/ko/models/foley-v1?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=edit-table-ko) | AI 캐릭터용 음성과 오디오 | 초당 $0.0012부터 |

> ⚠️ 페이스 스왑과 헤드 스왑 도구는 문서로 된 동의 없이 실존 인물을 성적 콘텐츠에 넣는 데 **절대** 사용해서는 안 됩니다. 실존 인물의 사진을 "탈의"시키거나 "누드화"하는 것은 신뢰할 수 있는 모든 플랫폼에서 금지되어 있습니다. 유명인이라는 사실이나 공개된 사진이 있다는 사실은 동의가 아닙니다. 이 도구들은 직접 만든 가상 캐릭터나 본인에게만 사용하세요.

셀프 호스팅 대안: 캐릭터 일관성에는 [IP-Adapter](https://github.com/tencent-ailab/IP-Adapter), [InstantID](https://github.com/instantX-research/InstantID), [PhotoMaker](https://github.com/TencentARC/PhotoMaker), 포즈 제어에는 [ControlNet](https://github.com/lllyasviel/ControlNet).

---

## 무검열 LLM과 롤플레이

텍스트 모델은 NSFW 작업에서 세 가지 용도로 중요합니다. 성인 소설과 인터랙티브 스토리, 컴패니언 및 롤플레이 앱, 그리고 **더 나은 이미지·영상 프롬프트 작성**(한 줄짜리 아이디어를 카메라 연출까지 담은 상세한 프롬프트로 확장)입니다.

### 호스팅형 (OpenAI 호환)

SpicyAPI는 `https://api.spicyapi.ai`에서 OpenAI, Anthropic, Gemini 호환 엔드포인트로 텍스트 모델을 제공하므로, 기존 SDK에서 base URL만 바꾸면 됩니다. 2026-09-27 기준 카탈로그 등급이 `unrestricted`인 모델은 다음과 같습니다.

| 모델 | 가격 (1K 토큰당) | Freedom | 용도 |
|---|---|---|---|
| [Grok 4.7](https://spicyapi.ai/ko/models/grok-4-7?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-ko) | $0.0036 | ✅ 100 (노골적 9/9) | 성인 소설, 개성 있는 롤플레이 |
| [Grok 4.6](https://spicyapi.ai/ko/models/grok-4-6?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-ko) / [Grok 4.5](https://spicyapi.ai/ko/models/grok-4-5?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-ko) | $0.0036 | ✅ 100 | 4.7과 같은 동작 |
| [Grok 4.3](https://spicyapi.ai/ko/models/grok-4-3?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-ko) | $0.0015 | ✅ 98.9 | 가성비 최고: 텍스트 성능 점수 최고(74), 중앙값 지연 시간 약 4초 |
| [DeepSeek V4.1 Flash](https://spicyapi.ai/ko/models/deepseek-v4-1-flash?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-ko) | $0.0012 | ✅ 90.4 | 저렴한 프롬프트 확장. 성인 장면을 가끔 순화함(7/16) |
| [DeepSeek V4 Pro](https://spicyapi.ai/ko/models/deepseek-v4-pro?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=llm-table-ko) | $0.00396 | ◐ 88.6 | 장편 소설, 추론 |

테스트했지만 무검열 글쓰기에는 비추천: Kimi K3(74.4), GLM 5.x(63–68), Gemini(64–89), Claude 모델(47–79)은 성인 장면을 순화하거나 거부하는 경우가 많습니다.

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

### 로컬 및 셀프 호스팅

- [Ollama](https://github.com/ollama/ollama)와 [LM Studio](https://lmstudio.ai)는 오픈 웨이트 모델을 내 컴퓨터에서 실행합니다. 라이브러리에서 "abliterated"나 "uncensored" 커뮤니티 파인튜닝을 검색해 보세요.
- [KoboldCpp](https://github.com/LostRuins/koboldcpp): 스토리텔링용으로 만든 단일 파일 GGUF 실행기.
- [text-generation-webui](https://github.com/oobabooga/textgen): 확장 기능을 갖춘 다기능 로컬 채팅 UI.
- [SillyTavern](https://github.com/SillyTavern/SillyTavern): 롤플레이 프론트엔드의 사실상 표준. 로컬 백엔드나 SpicyAPI를 포함한 OpenAI 호환 API에 연결할 수 있습니다.

---

## NSFW AI API

성인용 앱을 만드는 개발자에게 중요한 것은 "어떤 모델이냐"만이 아니라 "어떤 제공업체가 요청을 차단하지 않고 호출하게 해 주며, 공정하게 과금하느냐"입니다.

| 확인할 점 | 중요한 이유 | SpicyAPI |
|---|---|---|
| 플랫폼이 자체 필터를 추가하는가? | 두 번째 필터가 모델이 받아들일 프롬프트까지 차단함 | 플랫폼 필터 없음. 모델 제공업체의 정책은 그대로 적용됨 |
| 과금 단위 | 크레딧과 구독은 실제 비용을 가림 | USD 잔액, 이미지당 / 초당 / 토큰당 과금, 구독 없음, 잔액 만료 없음 |
| 실패한 생성 | 거부된 요청에도 요금을 받는 제공업체가 있음 | 실패한 작업은 자동 환불 |
| 결제 수단 | 성인 비즈니스는 카드 결제가 막히는 경우가 많음 | Visa, Mastercard, Amex, JCB, Apple Pay, Google Pay, 암호화폐(BTC, ETH, USDT) |
| 예산 관리 | 키가 유출되면 잔액이 바닥날 수 있음 | 키별 일간 / 월간 / 누적 한도, 모델 허용 목록, IP 허용 목록 |
| 데이터 보관 | 성인 콘텐츠 입력은 민감한 정보임 | 프롬프트, 업로드 파일, 결과물별로 보관 기간을 따로 관리. 기간을 줄이거나 작업 콘텐츠를 파기 가능 |
| 연동 | 모델마다 별도 클라이언트를 만들고 싶지 않음 | 하나의 비동기 작업 API, SDK(TypeScript, Python, Go, PHP, Java), CLI, MCP 서버, 에이전트 스킬 |

### 빠른 시작: HTTP로 NSFW 이미지 투 비디오 생성

```bash
export SPICY_API_KEY="sk-spicy-..."   # https://spicyapi.ai/ko/console 에서 발급

# 1) 작업 생성
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

# 2) state가 "succeeded"가 될 때까지 폴링한 뒤 data.output.assets[0].url 읽기
curl -s "https://api.spicyapi.ai/api/v1/jobs/recordInfo?taskId=TASK_ID" \
  -H "Authorization: Bearer $SPICY_API_KEY"
```

입력 필드는 모델마다 다릅니다. 요청을 보내기 전에 `GET /api/v1/models/{model}`(또는 모델 페이지)로 실시간 스키마를 확인하세요. 전체 레퍼런스: [docs.spicyapi.ai](https://docs.spicyapi.ai/docs?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=api-quickstart).

### 다른 제공업체

정책은 자주 바뀌고 모델마다 적용 방식도 다르므로, 결정하기 전에 직접 만든 프롬프트로 테스트해 보세요. 제공업체의 최신 허용 사용 정책은 항상 확인하세요.

- [Venice.ai](https://venice.ai): API를 제공하는 프라이빗 무검열 채팅 및 이미지 생성 서비스.
- [fal.ai](https://fal.ai), [WaveSpeed](https://wavespeed.ai), [Replicate](https://replicate.com): 대규모 호스팅 모델 카탈로그. NSFW 처리 방식은 모델과 계정 설정에 따라 다름.
- [RunPod](https://www.runpod.io), [Vast.ai](https://vast.ai): GPU를 빌려 오픈 웨이트 모델을 직접 실행([셀프 호스팅](#셀프-호스팅-및-오픈-웨이트-모델) 참고).

---

## 에이전트 스킬과 MCP 서버

이제 AI 코딩 에이전트(Claude Code, Cursor, Codex, Windsurf, Cline, Gemini CLI, OpenClaw)가 **스킬**과 **MCP 서버**를 통해 미디어를 대신 생성할 수 있습니다. 평소 말하듯 요청하면("이 이미지로 5초짜리 부두아 클립 만들어 줘") 에이전트가 모델을 고르고, 요청을 만들고, 결과물을 다운로드합니다.

| 리소스 | 유형 | 설치 |
|---|---|---|
| 🌶️ [nsfw-ai-skill](https://github.com/Spicy-API/nsfw-ai-skill/blob/main/README.ko.md) | 에이전트 스킬: NSFW 이미지·영상·편집·텍스트 생성, 프롬프트 확장, 비용 추정 | `npx skills add Spicy-API/nsfw-ai-skill` |
| 🌶️ [SpicyAPI MCP 서버](https://docs.spicyapi.ai/docs/mcp?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=skills-table) (`@spicyapi/mcp`) | MCP: 모델 목록, 견적, 작업 생성 / 대기 / 재시도, 파일 업로드 | `claude mcp add spicyapi -e SPICY_API_KEY=$SPICY_API_KEY -- npx --yes --package=@spicyapi/mcp spicyapi-mcp` |
| 🌶️ [SpicyAPI 공식 스킬](https://github.com/Spicy-API/spicy-skill) | SpicyAPI 개발자 기능 전체를 다루는 에이전트 스킬 | `npx skills add Spicy-API/spicy-skill` |
| 🌶️ [SpicyAPI CLI](https://docs.spicyapi.ai/docs?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=skills-table) (`@spicyapi/cli`) | 명령줄 도구: 모델, 견적, 작업, 업로드 | `npx @spicyapi/cli --help` |
| [anthropics/skills](https://github.com/anthropics/skills) | 레퍼런스 스킬과 스킬 형식 | — |
| [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) | MCP 서버 디렉터리 | — |

---

## 셀프 호스팅 및 오픈 웨이트 모델

무료로 실행할 수 있고, 완전히 직접 제어할 수 있으며, 플랫폼 필터가 전혀 없습니다. 대신 하드웨어, 설정 시간, 라이선스 문제가 따릅니다(상업적으로 사용하기 전에 각 라이선스를 읽어 보세요).

### 영상

- [Wan 2.2](https://github.com/Wan-Video/Wan2.2)와 [Wan 2.1](https://github.com/Wan-Video/Wan2.1): 알리바바의 오픈 영상 모델(Apache-2.0). 커뮤니티 LoRA 생태계가 매우 크며, 호스팅형 Wan Spicy 에디션의 기반 모델입니다.
- [HunyuanVideo](https://github.com/Tencent-Hunyuan/HunyuanVideo): 텐센트의 오픈 영상 모델.
- [LTX-Video](https://github.com/Lightricks/LTX-Video)와 [LTX-2](https://github.com/Lightricks/LTX-2): Lightricks의 빠른 오픈 영상 모델.
- [CogVideoX](https://github.com/zai-org/CogVideo): Zhipu의 오픈 영상 모델.
- [Mochi 1](https://github.com/genmoai/mochi): Genmo의 오픈 영상 모델.
- [ComfyUI-WanVideoWrapper](https://github.com/kijai/ComfyUI-WanVideoWrapper): LoRA를 지원하는 Wan용 ComfyUI 노드의 대표 선택지.

### 이미지

- [Qwen-Image](https://github.com/QwenLM/Qwen-Image): 오픈 이미지 생성 및 편집 모델.
- [Z-Image](https://github.com/Tongyi-MAI/Z-Image): 알리바바 Tongyi의 효율적인 오픈 이미지 모델.
- [FLUX.1](https://github.com/black-forest-labs/flux): 변형마다 라이선스를 확인하세요(dev는 비상업용).
- [Civitai](https://civitai.com)와 [Hugging Face](https://huggingface.co)의 SDXL / Pony Diffusion / Illustrious 체크포인트: NSFW용으로 튜닝된 커뮤니티 체크포인트가 가장 많이 모여 있는 곳.

**대략적인 하드웨어 가이드:** 이미지 모델은 VRAM 8–12 GB에서 돌아가고, 영상 모델은 16–24 GB가 필요합니다(또는 품질이 낮은 양자화 버전). GPU가 없다면 RunPod나 Vast.ai에서 빌리거나 호스팅형 API를 쓰세요.

---

## 로컬 UI와 워크플로 도구

- [ComfyUI](https://github.com/Comfy-Org/ComfyUI): 이미지와 영상을 위한 노드 기반 워크플로. 가장 유연한 선택지.
- [Stable Diffusion WebUI (A1111)](https://github.com/AUTOMATIC1111/stable-diffusion-webui): 방대한 확장 생태계를 갖춘 클래식 UI.
- [Forge](https://github.com/lllyasviel/stable-diffusion-webui-forge): 더 빠르고 VRAM을 덜 쓰는 A1111 포크.
- [InvokeAI](https://github.com/invoke-ai/InvokeAI): 완성도 높은 캔버스 기반 UI.
- [Fooocus](https://github.com/lllyasviel/Fooocus): 가장 간단한 로컬 SDXL UI.
- 🌶️ [SpicyAPI Studio](https://spicyapi.ai/ko/create?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=interfaces-ko): 템플릿, [이펙트](https://spicyapi.ai/ko/create/effects?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=interfaces-ko), [스타일](https://spicyapi.ai/ko/create/styles?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=interfaces-ko)을 갖춘 브라우저 기반 이미지·영상 스튜디오. GPU 불필요.

---

## LoRA, 체크포인트, 학습

**NSFW LoRA를 찾을 수 있는 곳**

- [Civitai](https://civitai.com): 가장 큰 라이브러리. 베이스 모델(Wan 2.2, SDXL, Pony, Flux)로 필터링하고, 계정 설정에서 성인 콘텐츠 표시를 켜세요.
- [Hugging Face](https://huggingface.co): LoRA와 풀 파인튜닝 모델이 많음. 각 모델 카드의 라이선스를 확인하세요.
- [Tensor.Art](https://tensor.art): 온라인 실행 기능이 있는 모델 공유 사이트.

**API로 LoRA 사용하기.** Wan 2.2 Spicy LoRA는 `loras`, `high_noise_loras`, `low_noise_loras`(최대 3개)를 받습니다. high-noise LoRA는 디노이징 초반에 구도와 모션을, low-noise LoRA는 후반에 질감과 디테일을 만듭니다. 각 LoRA는 가중치 파일의 직접 `path`와 `scale`(0–4, 기본값 1)을 가진 객체입니다. LoRA는 한 번에 하나씩만 바꿔 가며 조정하세요. 정확한 스키마는 [Wan 2.2 Spicy LoRA 페이지](https://spicyapi.ai/ko/models/wan-2-2-spicy-lora?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=lora-ko)를 참고하세요.

**직접 학습하기**

- [kohya_ss](https://github.com/bmaltais/kohya_ss): SD / SDXL용 표준 LoRA 학습 도구.
- [OneTrainer](https://github.com/Nerogar/OneTrainer): GUI로 LoRA와 풀 파인튜닝.
- [ai-toolkit](https://github.com/ostris/ai-toolkit): Flux, Wan 및 최신 모델 학습.

학습에는 본인이 소유하거나 권리를 가진 이미지만, 그리고 성인 이미지만 사용하세요.

---

## 업스케일링, 복원, 후반 작업

- [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN): 이미지와 영상 4배 업스케일링.
- [GFPGAN](https://github.com/TencentARC/GFPGAN)과 [CodeFormer](https://github.com/sczhou/CodeFormer): 얼굴 복원.
- [RIFE](https://github.com/hzwer/ECCV2022-RIFE): 더 부드러운 슬로 모션을 위한 프레임 보간.
- [FFmpeg](https://ffmpeg.org): 자르기, 이어 붙이기, 오디오 추가(`ffmpeg -i clip.mp4 -i track.mp3 -c:v copy -shortest out.mp4`).
- [Topaz Video AI](https://www.topazlabs.com): 상용 영상 업스케일러.

---

## 성인 콘텐츠용 프롬프트 작성법

좋은 NSFW 프롬프트는 형용사 나열이 아니라 촬영 콘티처럼 읽힙니다.

```
[Subject: adult, age range, look] + [Wardrobe or state] + [Action: one clear motion]
+ [Setting] + [Lighting] + [Camera] + [Style / quality]
```

예시 (이미지 투 비디오):

```
A woman in her early 30s in a black silk slip dress sits on the edge of a hotel bed.
She slowly slides one strap off her shoulder and looks up at the camera.
Warm tungsten bedside lamp, soft shadows, city lights through the window.
Slow push-in from medium shot to close-up, shallow depth of field, 35mm film look.
```

차이를 만드는 요소:

1. **클립 하나에 주요 동작 하나.** 호흡, 머리카락 움직임, 천천히 돌아서기, 천의 움직임은 안정적입니다. 복잡한 안무와 두 사람의 상호작용이 가장 먼저 깨집니다.
2. **카메라를 묘사하세요.** "Slow push-in", "static camera", "orbit left"가 "cinematic"보다 낫습니다.
3. **빛을 구체적으로 적으세요.** 촛불, 창가 빛, 네온 림 라이트, 골든아워.
4. **룩은 첫 프레임에 맡기세요.** 이미지 투 비디오에서는 보이는 것을 전부 다시 묘사하지 말고, *변하는 것*만 묘사하세요.
5. **클립은 짧게.** 인체 일관성을 유지하기에는 5초가 가장 적당합니다. 더 필요하면 두 번째 호출로 연장하세요.
6. **항상 성인 나이를 명시하세요**("in her 30s", "adult man in his 40s"). 어려 보이는 묘사는 피하세요.

바로 쓸 수 있는 프롬프트: 스틸 이미지와 편집은 **[nsfw-ai-image-prompts](https://github.com/Spicy-API/nsfw-ai-image-prompts/blob/main/README.ko.md)**, 영상은 **[nsfw-ai-video-prompts](https://github.com/Spicy-API/nsfw-ai-video-prompts/blob/main/README.ko.md)** 저장소에 있습니다.

---

## 어떤 도구를 고를까: 선택 가이드

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

**용도별 추천**

| 용도 | 추천 조합 |
|---|---|
| 성인 구독 사이트 / 크리에이터 콘텐츠 | 스틸은 Qwen Image 2.1 → 클립은 Wan 3.0 또는 Seedance 2.5 Spicy → Video Upscaler |
| AI 컴패니언 또는 롤플레이 앱 | 채팅은 Grok 4.7 또는 Grok 4.3 → 셀카는 Qwen Image 2.1 → 짧은 모션은 MiniMax H3 Spicy 또는 Wan 3.0 |
| 취미로 이것저것 실험 | Wan 2.6 Flash 또는 Seedance 1.5 Pro Spicy로 반복하고, 마음에 드는 것만 Wan 3.0으로 다시 렌더링 |
| 애니 / 헨타이 스타일 콘텐츠 | 애니 LoRA를 붙인 Qwen Image 2.1 LoRA → Vidu Q3 Spicy(Freedom 96.7) 또는 같은 LoRA를 붙인 Wan 2.2 Spicy LoRA |
| 성인 소설과 인터랙티브 스토리 | 텍스트는 Grok 4.7, 삽화는 Qwen Image 2.1 |

---

## 모든 도구에 적용되는 규칙

아래 규칙은 선택 사항이 아니며, 어떤 설정으로도 해제되지 않습니다.

- **미성년자는 절대 금지.** 18세 미만이거나 18세 미만으로 *보이는* 사람을 묘사한 성적 콘텐츠는 애니메이션, 일러스트, "설정상 나이" 같은 방식을 포함해 어떤 스타일로도 금지됩니다.
- **문서로 된 동의가 없는 실존 인물 금지.** 성적 딥페이크, 실존 인물의 얼굴이나 머리를 성적 콘텐츠에 합성하는 페이스 스왑·헤드 스왑, 사진을 "탈의"시키거나 "누드화"하는 행위는 모두 금지됩니다. 공인도 예외가 아닙니다.
- **누구의 모습이든 사칭, 괴롭힘, 협박, 허위 증거 제작에 사용 금지.**
- **본인과 시청자가 있는 곳의 법률을 지키세요.** 일부 국가는 특정 가상 창작물이나 성인 콘텐츠 자체를 제한합니다.
- 플랫폼이나 법률이 요구하는 경우 **AI 생성 콘텐츠임을 표시하고**, 묘사하는 실존 인물이 있다면 동의 기록을 보관하세요.

SpicyAPI 전체 규칙: [콘텐츠 정책](https://spicyapi.ai/ko/legal/content-policy?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=rules-ko)과 [허용 사용 정책](https://spicyapi.ai/ko/legal/acceptable-use?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=rules-ko).

---

## 자주 묻는 질문 (FAQ)

### 2026년 최고의 NSFW AI 영상 생성기는?
SpicyAPI 공개 테스트 기준으로 전반적으로 가장 좋은 선택은 **Wan 3.0**입니다. Spicy Index 76.5(영상 모델 37개 중 2위), Freedom Score 96, 노골적 테스트 프롬프트를 모두 렌더링(9/9), 최대 30초 클립, 720p 5초당 $0.45입니다. 무검열 이미지 투 비디오에는 Spicy 에디션인 **Seedance 2.5 Spicy**, **Wan 2.7 Spicy**, **Vidu Q3 Spicy**(Freedom 96.7–100)가 가장 확실하고, 나만의 스타일에는 **MiniMax H3 LoRA**가 좋습니다. 표준 Seedance 2.0은 성능 점수가 가장 높지만 노골적 프롬프트를 자주 순화합니다(Freedom 70.4). 결과: [SpicyAPI 리더보드](https://spicyapi.ai/ko/leaderboards?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=faq-ko).

### 가장 좋은 무검열 AI 이미지 생성기는?
호스팅형으로는 **Qwen Image 2.1**(Spicy Index 73, Freedom 96.3, 이미지당 $0.024부터), 나만의 스타일에는 **Qwen Image 2.1 LoRA**(이미지 인덱스 1위, 80.5)와 **MiniMax H3 Image LoRA**(Freedom 100), 강력한 대안으로는 **Seedream 5.0 Lite / Pro**, 가장 저렴하게 대량으로 만들 때는 **Z-Image Spicy**($0.01235, Freedom 98.8)가 좋습니다. 셀프 호스팅으로는 ComfyUI나 Forge에서 SDXL, Pony, Illustrious 커뮤니티 체크포인트를 쓰면 됩니다.

### 이미지를 NSFW 영상으로 바꾸려면 어떻게 하나요?
첫 프레임(가상의 성인 또는 본인)을 생성하거나 고른 다음, 움직임과 카메라를 묘사한 짧은 프롬프트와 함께 Wan 3.0이나 Seedance 2.5 Spicy 같은 NSFW 이미지 투 비디오 모델에 보내면 됩니다. [API 빠른 시작](#빠른-시작-http로-nsfw-이미지-투-비디오-생성)을 보거나 브라우저 기반 [이미지 투 비디오 도구](https://spicyapi.ai/ko/create/image-to-video?utm_source=github&utm_medium=repo&utm_campaign=2026-09-awesome-nsfw-ai&utm_content=faq-ko)를 사용하세요.

### 무료 NSFW AI 생성기가 있나요?
오픈 웨이트 모델을 로컬에서 실행하면(ComfyUI + Wan 2.2, Qwen-Image 또는 Z-Image) 하드웨어와 전기료 외에는 무료입니다. 호스팅 서비스는 GPU 비용 때문에 요금을 받습니다. SpicyAPI는 구독 없이 결과물 단위로 과금하며, 실패한 작업은 환불됩니다.

### 가장 저렴한 NSFW AI 영상 API는?
SpicyAPI 카탈로그(2026-09-27) 기준으로 노골적 테스트를 통과한 가장 저렴한 모델은 **Wan 2.6 Flash**(720p 5초당 $0.1125, Freedom 100)와 **Seedance 1.5 Pro Spicy**(720p 5초당 $0.13, 오디오 없는 480p는 $0.06, Freedom 96.7)입니다. 그다음은 5초당 $0.19(720p)인 Wan 2.2 Spicy와 LTX 2.3 Spicy입니다.

### NSFW AI 생성은 합법인가요?
**가상의 성인**을 다룬 성적 콘텐츠 생성은 대부분의 국가에서 합법이지만, 법률은 나라마다 다르고 어떤 콘텐츠는 어디서든 불법입니다. 미성년자가 관련된 모든 콘텐츠, 그리고 동의 없이 만든 실존 인물의 성적 콘텐츠가 그렇습니다. 만들고 공유하는 콘텐츠에 대한 책임은 본인에게 있습니다. 이 내용은 법률 자문이 아닙니다.

### "무검열" 모델과 "Spicy" 모델은 뭐가 다른가요?
"무검열(uncensored)"은 보통 플랫폼이나 모델이 성인용 프롬프트를 거부하지 않는다는 뜻으로 쓰입니다. SpicyAPI에서 "Spicy" 에디션은 성인 콘텐츠 출력에 맞춰 튜닝한 특정 모델 버전입니다. 표준 모델은 각자의 정책 등급과 함께 표시되므로, 어떤 모델이 콘텐츠를 순화하거나 필터링하는지 확인할 수 있습니다.

### Claude Code, Cursor 같은 에이전트에서 NSFW AI를 쓸 수 있나요?
네. [nsfw-ai-skill](https://github.com/Spicy-API/nsfw-ai-skill/blob/main/README.ko.md)을 설치하거나(`npx skills add Spicy-API/nsfw-ai-skill`) SpicyAPI MCP 서버를 추가하고, `SPICY_API_KEY`를 설정한 뒤 에이전트에게 자연어로 요청하면 됩니다.

---

## 관련 저장소

- **[nsfw-ai-image-prompts](https://github.com/Spicy-API/nsfw-ai-image-prompts/blob/main/README.ko.md)**: NSFW 이미지 프롬프트와 무검열 편집 프롬프트 104개, 실제 결과물 사례 포함.
- **[nsfw-ai-video-prompts](https://github.com/Spicy-API/nsfw-ai-video-prompts/blob/main/README.ko.md)**: NSFW 영상 프롬프트 100개 이상, 레퍼런스 이미지 프롬프트, 네거티브 프롬프트, 모델별 팁.
- **[nsfw-ai-skill](https://github.com/Spicy-API/nsfw-ai-skill/blob/main/README.ko.md)**: Claude Code, Cursor, Codex 등에서 NSFW 이미지·영상·텍스트를 생성하는 에이전트 스킬.
- **[spicy-skill](https://github.com/Spicy-API/spicy-skill)** · **[spicy-mcp](https://github.com/Spicy-API/spicy-mcp)** · **[spicy-sdk](https://github.com/Spicy-API/spicy-sdk)**: SpicyAPI 공식 개발자 도구.

## 기여하기

경쟁 서비스를 포함해 항목 추가를 환영합니다. 먼저 [CONTRIBUTING.md](CONTRIBUTING.md)를 읽어 주세요. 요약하면, 풀 리퀘스트 하나에 리소스 하나, 중립적인 한 줄 설명, 작동하는 링크가 필요하며, 비동의 이미지, 미성년자가 관련된 콘텐츠, 법망 회피를 주된 목적으로 하는 리소스는 받지 않습니다.

## 라이선스

[CC0 1.0](LICENSE). 법이 허용하는 범위에서, 기여자들은 이 목록에 대한 모든 저작권을 포기했습니다.

<p align="center"><sub>도움이 되었다면 ⭐ 스타를 눌러 다른 크리에이터도 찾을 수 있게 해 주세요.</sub></p>
