# Linguistic Differences between Chinese and English Prompts for LLMs: A Pragmatic Analysis (Xiaohongshu vs. Reddit)

**Bachelor's thesis** · BA Linguistics (Translation and Teaching Intercultural Communication)
Faculty of Foreign Languages, **Tomsk State University**, Russia · 2026
Author: **Yu Zhanbo** · Supervisor: Prof. Olga V. Nagel, Doctor of Philology

> This repository summarises the thesis: research questions, corpus, coding scheme and main findings. The full text is not published here.

**Keywords:** contrastive pragmatics · prompts · speech acts · politeness · human–AI interaction · corpus analysis · Chinese · English

---

## Overview

Prompts have become the main way ordinary users talk to large language models (LLMs). This thesis treats prompts as a new **directive register** and compares how Chinese and English users phrase them, using the tools of **contrastive pragmatics**. It asks whether users carry the politeness norms of their own language into human–AI interaction, or drop them because "it's only a machine".

## Research questions

1. **RQ1 – Speech acts and directness.** How do Chinese and English prompts differ in speech act type (command / request / suggestion / other) and in direct vs. indirect strategies?
2. **RQ2 – Metapragmatic control.** How do Chinese and English users differ in the use of **role setting** ("You are…", "Act as…"), **step requirements** ("first… then…") and **format constraints** (word limits, tables, structure)?

## Data: a 100-prompt contrastive corpus

| Language | Source | Keywords | Samples |
|---|---|---|---|
| Chinese | Xiaohongshu (小红书) | DeepSeek prompt, 豆包 prompt, AI指令, Prompt | 50 |
| English | Reddit r/ChatGPT | Prompt share, Act as, Best prompt | 25 |
| English | Reddit r/PromptEngineering | Prompt templates, AI prompt, System prompt | 25 |

- Collected manually, February–March 2026 (no scraping or API).
- Stratified by task type: creative writing and generation (35), academic learning and explanation (35), daily life (30), balanced across the two languages.
- Inclusion and exclusion criteria: complete, user-written, single-language prompts of 5–500 words or characters; no official templates, duplicates, heavy code-mixing or multi-turn fragments.

## Method

- **Coding scheme** with five dimensions, each with operational definitions and Chinese and English boundary cases:

  | Code | Dimension | Values |
  |---|---|---|
  | AP1 | Speech act type | command / request / suggestion / other |
  | AP2 | Directness strategy | direct (bare imperative) / indirect (请, 麻烦, 能不能, could you, please…) |
  | AP3 | Role assignment | yes / no |
  | AP4 | Format constraint | yes / no |
  | AP5 | Step requirement | yes / no |

- **Inter-coder reliability:** two coders double-coded 20 pilot prompts (10 Chinese, 10 English); Cohen's κ = 0.625–0.771 across dimensions (mean **κ = 0.682**, "good" agreement by Landis & Koch).
- **Analysis:** frequency comparison (quantitative), followed by qualitative interpretation of individual prompts.
- **Theoretical framework:** Speech Act Theory (Austin, Searle), politeness theory (Leech; Brown & Levinson; Gu Yueguo), Verschueren's adaptation theory and metapragmatic awareness, and Computers Are Social Actors (CASA; Nass & Moon).

## Key findings

| Dimension | Chinese (n = 50) | English (n = 50) |
|---|---|---|
| Command | 16% | **56%** |
| Request | **64%** | 18% |
| Suggestion | 4% | 0% |
| Other (e.g. "I need…", "I want you to…") | 16% | 26% |
| Direct strategy | 24% | **64%** |
| Indirect strategy | **76%** | 36% |
| Role setting | 28% | 28% |
| Format constraint | 28% | 20% |
| Step requirement | 16% | 18% |

1. **English prompts are mostly direct commands; Chinese prompts are mostly polite requests.** English users appear to strip politeness when the addressee is an AI ("Write about productivity."), while Chinese users keep everyday politeness routines ("请帮我写一篇……").
2. **Explanation: how far politeness is grammaticalised.** In English, *please / could / would* are detachable add-ons and easy to drop. In Chinese, 请帮我 has fused into a request construction, so removing it makes the sentence sound unnatural.
3. **Metapragmatic control is largely shared.** Role setting and step requirements occur at almost identical rates, which suggests they are *instrumental* strategies driven by task complexity rather than culture. A small difference shows up in phrasing: English "Act as…" (a temporary role) vs. Chinese "你是…" ("you are", an assigned identity).
4. **Chinese users add slightly more format constraints**, which the thesis interprets as a compensatory strategy: high-context communicators make their expectations explicit for a model that cannot "read between the lines".
5. **CASA, refined.** Users do transfer social norms to AI, but *how* they transfer them depends on language and culture: English users adapt to the addressee, while Chinese users keep the same norms.

## Contributions

- Extends contrastive pragmatics (CCSARP tradition) from human–human talk to **human–LLM prompts**.
- A reusable **five-dimension coding scheme** for prompt pragmatics that can be applied to other languages.
- Practical implications for **multilingual prompt design** and for the **localisation** of Chinese-facing AI products (e.g. better handling of indirect requests).

## Limitations and next steps

- Small corpus (100 prompts) and descriptive statistics only; the differences have not yet been tested for significance (e.g. chi-square).
- Inter-coder agreement was measured on a 20-prompt pilot; the full corpus was coded by one researcher.
- Next steps: a larger corpus, significance testing, and testing whether these pragmatic differences change **LLM output quality**.

## Citation

```
Yu, Z. (2026). Linguistic Differences between Chinese and English Prompts for LLMs:
A Pragmatic Analysis (Xiaohongshu vs. Reddit). Bachelor's thesis,
Tomsk State University, Faculty of Foreign Languages.
```
