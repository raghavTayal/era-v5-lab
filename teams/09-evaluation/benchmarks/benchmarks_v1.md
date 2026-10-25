# Benchmarks v1 — Team 09 (Evaluation)

Licence and item count for each benchmark in the V5 evaluation suite.
Priority order: Coding & Agentic → Indic → everything else.

Status: ✅ checked against an official source · ⚠️ to be rechecked · ❓ information still to collect.

## 1. Coding & Agentic

| Benchmark | Source | Items | Licence | Status |
|---|---|---|---|---|
| SWE-bench Verified | `princeton-nlp/SWE-bench_Verified` | 500 | MIT | ✅ |
| SWE-bench Live | `microsoft/SWE-bench-Live` | 300 (Lite) | MIT | ✅ |
| SWE-bench Pro | `ScaleAI/SWE-bench_Pro` | 731 (public set) | MIT (repo); tasks come from copyleft (GPL) projects | ✅ |
| Terminal-Bench 2.0 | `laude-institute/terminal-bench-2` | 89 | Apache-2.0 | ✅ |
| tau2-bench | `sierra-research/tau2-bench` | 278 (airline 50, retail 114, telecom 114) | MIT | ✅ |
| BFCL v3 | `gorilla-llm/Berkeley-Function-Calling-Leaderboard` | 4,441 | Apache-2.0 | ✅ |
| WebArena | `web-arena-x/webarena` | 812 | Apache-2.0 | ✅ |
| WorkArena | `ServiceNow/WorkArena` | 33 (L1) | Apache-2.0 | ✅ |
| GAIA | `gaia-benchmark/GAIA` | 165 (validation; test 301 has private answers) | Gated terms | ✅ |
| BrowseComp | `openai/simple-evals` | 1,266 | MIT | ✅ |
| OSWorld | `xlang-ai/OSWorld` | 369 | Apache-2.0 | ✅ |
| LiveCodeBench | `livecodebench/code_generation_lite` | 1,055 (release_v6) | CONFLICT: code MIT, dataset card "cc" | ⚠️ |
| Aider Polyglot | `Aider-AI/polyglot-benchmark` | 225 (cpp 26, go 39, java 47, js 49, python 34, rust 30) | No LICENSE file in repo (exercises adapted from Exercism) | ⚠️ |
| Codeforces | `open-r1/codeforces` | 468 (test split) | CC-BY-4.0 in card metadata; README text says ODC-By 4.0 | ⚠️ |

## 2. Indic

| Benchmark | Source | Items | Licence | Status |
|---|---|---|---|---|
| MILU | `ai4bharat/MILU` | 79,608 (test) | CC-BY-4.0 (gated) | ✅ |
| IndicGenBench | `google-research-datasets/indic-gen-bench` | 29,589 (test, our 10 languages) | Flores-IN, XQuAD-IN: CC-BY-SA-4.0 · XorQA-IN: MIT · CrossSum-IN: CC-BY-NC-SA-4.0 | ✅ |

### Indic coverage — the 10 pack languages (test split)

| Benchmark | bn | gu | hi | kn | ml | mr | or | sa | ta | te |
|---|---|---|---|---|---|---|---|---|---|---|
| MILU | 6,637 | 4,826 | 14,831 | 6,234 | 4,321 | 6,924 | 4,525 | — | 6,372 | 7,304 |
| IndicGenBench CrossSum-IN | 155 | 104 | 481 | 500 | 500 | 118 | 500 | 499 | 315 | 212 |
| IndicGenBench Flores-IN (xx→en) | 1,012 | 1,012 | 1,012 | 1,012 | 1,012 | 1,012 | 1,012 | 1,012 | 1,012 | 1,012 |
| IndicGenBench XQuAD-IN | 1,190 | 1,190 | 1,190 | 1,190 | 1,190 | 1,190 | 1,190 | — | 1,190 | 1,190 |
| IndicGenBench XorQA-IN | 539 | 535 | 539 | 536 | 537 | 538 | 537 | 537 | 538 | 539 |
| ONERULER (long context) | — | — | generated | — | — | — | — | — | generated | — |

bn Bengali · gu Gujarati · hi Hindi · kn Kannada · ml Malayalam · mr Marathi · or Odia · sa Sanskrit · ta Tamil · te Telugu.
— = not covered · generated = synthetic, items are generated at run time.

## 3. Reasoning & Math

| Benchmark | Source | Items | Licence | Status |
|---|---|---|---|---|
| AIME 2024 / 2025 | `HuggingFaceH4/aime_2024` + `opencompass/AIME2025` | 30 + 30 | Not stated on the dataset cards; problems © MAA | ⚠️ |
| FrontierMath | `Epoch AI` | 338 (12 public) | Private | ✅ |
| GPQA Diamond | `Idavidrein/gpqa` | 198 | CC-BY-4.0 (gated) | ✅ |
| HLE | `cais/hle` | 2,500 | MIT (gated) | ✅ |

## 4. General Knowledge

| Benchmark | Source | Items | Licence | Status |
|---|---|---|---|---|
| MMLU | `cais/mmlu` | 14,042 | MIT | ✅ |

## 5. Long context

| Benchmark | Source | Items | Licence | Status |
|---|---|---|---|---|
| RULER | `NVIDIA/RULER` | 13 task configurations (generated per length) | Apache-2.0 | ✅ |
| HELMET | `princeton-nlp/HELMET` | 4,100 at 128K (7 categories, 21 datasets) | MIT (code); data keeps each source dataset's licence | ⚠️ |
| LongBench v2 | `THUDM/LongBench-v2` | 503 | Apache-2.0 (dataset card); code MIT | ✅ |
| ONERULER | `mungg/OneRuler` | 7 tasks × 26 languages | MIT | ✅ |