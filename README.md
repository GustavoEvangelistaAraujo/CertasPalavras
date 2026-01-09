# Certas Palavras
**A 1980s–90s Brazilian Radio Corpus to Test TTS Models in Noisy Multi-Speaker Dialogues (PROPOR 2026)**

A Brazilian Portuguese radio corpus of spontaneous, multi-speaker broadcast dialogues (1980s–1990s) designed for **robustness-oriented speech synthesis and evaluation** under real acoustic conditions (music beds, jingles, channel noise, overlap, hesitations, and repair phenomena).

---

## Contents
- [Dataset overview](#dataset-overview)
- [What makes this corpus different](#what-makes-this-corpus-different)
- [Statistics](#statistics)
- [Data organization](#data-organization)
- [Annotations](#annotations)
- [Licensing and ethics](#licensing-and-ethics)
- [Citation](#citation)
- [Contact](#contact)

---

## Dataset overview
**Certas Palavras** is a corpus of spontaneous Brazilian Portuguese dialogues from a radio broadcast program. The dataset captures speech produced under broadcast constraints and interactional dynamics (hosts, co-host, guests, varying recording conditions).

**Speaker composition (high-level):**
- **2 main hosts**: Claudiney Ferreira, Jorge Vasconcelos  
- **1 co-host**: Ivan Lessa  
- **Guest speakers**: 133 male, 55 female  

---

## What makes this corpus different
Compared to interview-style or read-speech corpora, broadcast dialogues exhibit:
- **Higher turn-taking density** (rapid, interactive exchanges)
- **Frequent filled pauses and repairs** (e.g., hesitations, rephrasings)
- **Non-stationary acoustic conditions** (music, jingles, on-air artifacts)
- **Substantial speaker diversity** (hosts + large guest pool)

This design supports experiments on:
- robustness of TTS and ASR under noise and interference,
- model behavior under speaker imbalance,
- prosody and style transfer in spontaneous dialogue,
- evaluation protocols combining objective and subjective metrics.

---

## Statistics
**Table 2: Detailed statistics of Certas Palavras.**

| feature | total |
|---|---:|
| # speakers | 190 |
| # words | 689,574 |
| total duration (h) | 70.98 |
| # radio program clips | 42,486 |
| mean duration/segment (s) | 5.95 |
| mean words/episode | 4,257 |
| mean turns/episode | 55 |
| # sentences with unintelligible words (i) | 972 |
| # sentences with filled pauses (ii) | 8,968 |
| # sentences with emotional content (viii) | 594 |
| # sentences with segmental errors (x) | 609 |
| # sentences with music/SFX (xi) | 1,807 |
