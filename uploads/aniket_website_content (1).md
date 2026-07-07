<!--
  Aniket Dey, website content.
  Order: (1) University Research  (2) Independent Research  (3) Personal Projects  (4) SWE Projects.
  Technology tags use inline color spans; the same skill keeps the same color across every project (see key below).
  Image slots are marked with comments; add images where noted.
-->

## Technology color key

<!-- Reuse these exact hex values so the same skill is the same color everywhere. -->

<span style="color:#3776AB"><b>Python</b></span> ·
<span style="color:#00599C"><b>C++</b></span> ·
<span style="color:#555555"><b>C</b></span> ·
<span style="color:#61DAFB"><b>React</b></span> ·
<span style="color:#3178C6"><b>TypeScript</b></span> ·
<span style="color:#EE4C2C"><b>PyTorch</b></span> ·
<span style="color:#F7931E"><b>scikit-learn</b></span> ·
<span style="color:#4DABCF"><b>NumPy</b></span> ·
<span style="color:#0054A6"><b>SciPy</b></span> ·
<span style="color:#FF4B4B"><b>Streamlit</b></span> ·
<span style="color:#1A7F64"><b>LangGraph</b></span> ·
<span style="color:#D97757"><b>Claude</b></span> ·
<span style="color:#8E44AD"><b>UDP / sockets</b></span> ·
<span style="color:#F37626"><b>Jupyter</b></span> ·
<span style="color:#6A5ACD"><b>Financial Engineering</b></span> ·
<span style="color:#009688"><b>FastAPI</b></span> ·
<span style="color:#9B59B6"><b>Diffusion / DiT</b></span> ·
<span style="color:#16A085"><b>VAE</b></span> ·
<span style="color:#C0392B"><b>Mamba / SSM</b></span>

---

# University Research

## Newton Group

**Affiliation:** Newton Group, Dartmouth College
**Co-researchers:** Casey Quinn, Dr. Elizabeth Newton

Research currently in progress. Further information will be published soon.

**Links:** [Newton Group](https://newton.host.dartmouth.edu/research.html)

---

## Implied Volatility Skew Detection

**Affiliation:** Dartmouth College, Department of Economics
**Co-researchers:** Prof. John Welborn (PI); advisory from Prof. Victor Van Erp

A pipeline that predicts next-day equity-ETF downturns from implied-volatility skew, using the IV gap between deep out-of-the-money and at-the-money puts as the signal. Trained on 1.77M QQQ option records across the 2020 crash and 2022 correction, the ensemble reaches 0.91 AUC at sub-50ms latency.

**Venue:** Working paper, Dartmouth Economics Department
**Links:** [Code](https://github.com/aniketxdey/iv-skew) · [Paper (PDF)](https://github.com/aniketxdey/iv-skew/blob/main/paper.pdf)

<!-- image slot: representative figure in the iv-skew README -->

---

## ASR Gradient-Inversion Attack

**Affiliation:** Learning, Intelligence + Signal Processing (LISP) Lab, Dartmouth College
**Co-researchers:** Prof. Peter Chin (Advisor), Minh Bui (PI), Paul Cherian, Mary Wood

An adversarial gradient-inversion attack that reconstructs private voice samples from speech-recognition models trained under federated learning. By matching gradients through the CTC loss, it recovers the original training audio the federated protocol is meant to protect, validated on DeepSpeech2, a production ASR framework.

**Venue:** "An Attack to Reveal Voice Samples in Distributed Speech Recognition Models"; presented at the 2024 Wetterhahn Science Symposium
**Links:** [Code](https://github.com/aniketxdey/asr-attack-algorithm) · [Symposium poster (PDF)](https://github.com/aniketxdey/lisp/files/15441960/Wetterhahn.Science.Symposium.1.pdf)

<!-- image slot: poster and screenshot in the asr-attack-algorithm README -->

---

## Tumor Microenvironment Genomics

**Affiliation:** Dietlein Lab, Computational Health Informatics Program (CHIP), Harvard Medical School
**Role:** Computational Genomics Researcher

Bioinformatics tools that interpret single-cell RNA-seq data to identify genomic drivers in the tumor microenvironment. Clustering and differential-expression analysis surface the gene-expression shifts behind malignant transition, and a random-forest pipeline predicts ligand-receptor interactions at those sites with 89.32% accuracy to guide therapeutic targeting.

**Links:** [Code](https://github.com/aniketxdey/hms) · [Dietlein Lab](https://www.dietleinlab.org/)

<!-- image slot: logo and figures in the hms README -->

---

# Independent Research

## Diffusion World Model for Billiards Physics

**Affiliation:** Independent

A diffusion-based world model that simulates 2D billiards physics with no physics engine at inference. An action-conditioned diffusion transformer predicts each frame in VAE latent space, using diffusion forcing for long-horizon stability, trained on a 200,000-episode dataset and playable in real time over WebSocket.

**Venue:** Independent research write-up (LaTeX essay and slides in repo)
**Links:** [Code and demo video](https://github.com/aniketxdey/dwm-billiards)

<!-- image slot: pipeline diagram and gameplay clip in the dwm-billiards README -->

---

## Mamba-ESI: Embedding Search for Selective SSMs

**Affiliation:** Advised by Prof. Yu-Wing Tai
**Co-researchers:** Abhinav Reddy

An extension to the Mamba state-space model that adds embedding search-and-injection to improve long-sequence recall while keeping linear-time inference. It embeds the query and input tokens, runs a similarity search for relevant context, and injects those hidden states into the current state rather than processing the full sequence memory.

**Venue:** Independent research; extends Mamba (Gu & Dao, [arXiv:2312.00752](https://arxiv.org/abs/2312.00752))
**Links:** [Code](https://github.com/aniketxdey/mamba-ESI)

<!-- image slot: selection figure and benchmark chart in the mamba-ESI README -->

---

## Non-Invasive Dementia Diagnosis (NLP + ML)

**Affiliation:** Independent (first author)
**Co-researchers:** Sanam Mittal

A non-invasive method for early dementia diagnosis that pairs NLP with machine learning. Instead of brain scans or blood tests, it derives a diagnostic signal from cognitive and language assessments, enabling accessible screening for the elderly populations where cognitive impairment is most common.

**Venue:** 2022 IEEE 2nd International Conference on Data Science and Computer Application (ICDSCA), pp. 75–79
**Links:** [Paper (IEEE Xplore)](https://ieeexplore.ieee.org/abstract/document/9987931)

<!-- image slot -->

---

## Automated Test-Case Analytics (Jira + Zephyr Scale)

**Affiliation:** Independent (first author)
**Co-researchers:** Amit Baranwal (DataCore Software), Sugandha Sahay (Carnegie Mellon University)

A system that measures test-case automation across corporate software infrastructure. Through the Atlassian Jira and SmartBear Zephyr Scale REST APIs, it authenticates against a company's cloud servers, pulls test-case records, and parses them into metrics on automation coverage and status for management.

**Venue:** "Data Analytics on Automation of Test Case Infrastructure with Jira and ZephyrScale," Global Technology and Business Management Conference (GTBMC) 2022, p. 33
**Links:** [Conference proceedings](https://gtbmc.org/gtbmc2022-conference-proceedings/)

<!-- image slot -->

---

## Visibility Correction for Autonomous Vehicles

**Affiliation:** Independent (first author)

A two-stage deep learning system that improves object detection for autonomous vehicles in adverse weather: a Visibility Correction Module masks and removes rain, snow, and fog, then an Object Detection Module labels the cleaned frames. It reached 89.72% average accuracy, beating industry alternatives on accuracy and detection time.

**Venue:** Journal of Emerging Investigators, October 31, 2022 · [doi:10.59720/22-101](https://doi.org/10.59720/22-101)
**Links:** [Article](https://emerginginvestigators.org/articles/22-101) · [Full PDF](https://emerginginvestigators.org/articles/22-101/pdf)

<!-- image slot: JEI cover figure on the article page -->

---

# Personal Projects

## Heston Calibration

**Headline:** Real-time Heston calibration on live vol surfaces

**Tech:** <span style="color:#3776AB"><b>Python</b></span> · <span style="color:#4DABCF"><b>NumPy</b></span> · <span style="color:#0054A6"><b>SciPy</b></span> · <span style="color:#6A5ACD"><b>Financial Engineering</b></span>

Real-time calibration of the Heston stochastic-volatility model to live SPY/SPX option surfaces, priced via the characteristic function with a Carr-Madan FFT and seeded by moment matching. A four-stage optimizer reaches an R² of 0.94, recalibrates in under 20ms, and cuts compute time 65% versus FFT-only implementations.

**Links:** [Code](https://github.com/aniketxdey/heston-calibration)

<!-- image slot -->

---

## Quantra: Options Pricing Platform

**Headline:** Real-time options pricing and analysis platform

**Tech:** <span style="color:#3776AB"><b>Python</b></span> · <span style="color:#FF4B4B"><b>Streamlit</b></span> · <span style="color:#F7931E"><b>scikit-learn</b></span> · <span style="color:#4DABCF"><b>NumPy</b></span>

An options pricing platform built for Dartmouth's Mathematical Finance I (MATH 86), pulling live market data to price each contract three ways side by side: Black-Scholes, a Cox-Ross-Rubinstein binomial tree, and a 10,000-path Monte Carlo. It also computes analytical and numerical Greeks, delta-neutral hedges, and full implied-volatility surfaces.

**Links:** [Code](https://github.com/aniketxdey/quantra) · [Live demo](https://advancedoptionspricing.streamlit.app/)

<!-- image slot: three UI screenshots in the quantra README -->

---

# SWE Projects

## Martian

**Headline:** AI agents that eliminate infrastructure waste

**Role:** Co-founder & CTO

**Tech:** <span style="color:#61DAFB"><b>React</b></span> · <span style="color:#3178C6"><b>TypeScript</b></span> · <span style="color:#3776AB"><b>Python</b></span> · <span style="color:#1A7F64"><b>LangGraph</b></span> · <span style="color:#D97757"><b>Claude</b></span>

Martian applies agentic AI to enterprise infrastructure cost optimization, with agents that connect to AWS, Azure, GCP, and on-premises systems through native APIs, map storage dependencies, and execute the changes that eliminate wasted spend. A LangGraph multi-agent backend reasoning through Claude drives the analysis, fronted by a React and TypeScript interface for finance and engineering teams.

**Links:** [Site](https://martian-ai.com/)

<!-- image slot -->

---

## Nuggets

**Headline:** Real-time multiplayer terminal mining game

**Tech:** <span style="color:#00599C"><b>C++</b></span> · <span style="color:#8E44AD"><b>UDP / sockets</b></span>

A real-time multiplayer terminal mining game where up to 26 players navigate a maze for gold while an authoritative server syncs every client over UDP, with ray-cast line-of-sight fog of war. Originally a CS50 final in C, the C++ rewrite swaps manual memory management for RAII and an unordered_map grid, rendering the full map in under 2ms per frame.

**Links:** [Code](https://github.com/aniketxdey/nuggets)

<!-- image slot: gameplay GIF in the nuggets README -->

---

## Amazon Review Analysis

**Headline:** Review rating and category classification

**Tech:** <span style="color:#3776AB"><b>Python</b></span> · <span style="color:#F7931E"><b>scikit-learn</b></span> · <span style="color:#F37626"><b>Jupyter</b></span>

A machine learning pipeline (Dartmouth CS74) that classifies Amazon reviews by rating and clusters them by category with scikit-learn. TF-IDF features feed logistic-regression and SGD classifiers tuned per rating cutoff, beating the course Kaggle baselines at every threshold, while clustering runs on 40 binary category-keyword features.

**Links:** [Code](https://github.com/aniketxdey/reviews-sentiment-analysis)

<!-- image slot -->

---

## TSE: Tiny Search Engine

**Headline:** A tiny search engine: crawl, index, rank

**Tech:** <span style="color:#555555"><b>C</b></span>

A search engine in C (CS50) built as three programs that communicate through the file system: a crawler that walks from a seed URL to a set depth and caches pages, an indexer that builds a word-to-page index, and a querier that evaluates AND/OR queries into ranked results.

**Links:** [Code](https://github.com/aniketxdey/tse)

<!-- image slot: architecture screenshot in the tse README -->
