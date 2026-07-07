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

A pipeline to predicts next-day equity-ETF downturns from implied-volatility skew between deep out-of-the-money and at-the-money puts as the signal. Trained on 1.77M QQQ option records across the 2020 crash and 2022 correction, the ensemble reaches 0.91 AUC at sub-50ms latency.

**Venue:** Working paper, Dartmouth Economics Department
**Links:** [Code](https://github.com/aniketxdey/iv-skew) · [Paper (PDF)](https://github.com/aniketxdey/iv-skew/blob/main/paper.pdf)

<!-- image slot: representative figure in the iv-skew README -->

---

## ASR Gradient-Inversion Attack

**Affiliation:** Learning, Intelligence + Signal Processing (LISP) Lab, Dartmouth College
**Co-researchers:** Prof. Peter Chin (Advisor), Minh Bui (PI), Paul Cherian, Mary Wood

An adversarial attack that reconstructs private voice samples with 99% fidelity from the gradients of speech-recognition models. Reverse engineers CTC loss in federated learning environments, recovering original training audio & validated on DeepSpeech2.

**Venue:** "An Attack to Reveal Voice Samples in Distributed Speech Recognition Models"; presented at the 2024 Wetterhahn Science Symposium
**Links:** [Code](https://github.com/aniketxdey/asr-attack-algorithm) · [Symposium poster (PDF)](https://github.com/aniketxdey/lisp/files/15441960/Wetterhahn.Science.Symposium.1.pdf)

<!-- image slot: poster and screenshot in the asr-attack-algorithm README -->

---

## Tumor Microenvironment Genomics

**Affiliation:** Dietlein Lab, Computational Health Informatics Program (CHIP), Harvard Medical School
**Role:** Computational Genomics Researcher

A suite of computational bioinformatics tools to analyze single-cell RNA-seq data & identify genomic drivers in the tumor microenvironment. Built during research at Harvard Medical School, deployed in 5+ UMass Memorial drug development cinics.

**Links:** [Code](https://github.com/aniketxdey/hms) · [Dietlein Lab](https://www.dietleinlab.org/)

<!-- image slot: logo and figures in the hms README -->

---

# Independent Research

## Diffusion World Model for Billiards Physics

**Affiliation:** Independent

A diffusion-based world model to simulate 2D billiards (pool) physics with no physics engine at inference. An action-conditioned DiT predicts each frame in VAE latent space, using diffusion forcing for long-horizon stability. Trained on a 200,000 episode dataset and playable in a  WebSocket neural simulatoe.

**Venue:** Independent Research
**Links:** [Code and demo](https://github.com/aniketxdey/dwm-billiards)

<!-- image slot: pipeline diagram and gameplay clip in the dwm-billiards README -->

---

## Mamba-ESI: Embedding Search for Selective SSMs

**Affiliation:** Advised by Prof. Yu-Wing Tai
**Co-researchers:** Abhinav Reddy

An extension to Mamba's state-space model that adds embedding search and injection to improve long-sequence recall, matching Transformer baselines in linear time. Embeds the query and input tokens, runs a similarity search for relevant context, and injects those hidden states into the current state rather than processing the full sequence memory.

**Venue:** Independent research; extends Mamba (Gu & Dao, [arXiv:2312.00752](https://arxiv.org/abs/2312.00752))
**Links:** [Code](https://github.com/aniketxdey/mamba-ESI)

<!-- image slot: selection figure and benchmark chart in the mamba-ESI README -->

---

## Non-Invasive Dementia Diagnosis (NLP + ML)

**Affiliation:** Independent (first author)
**Co-researchers:** Sanam Mittal

A non-invasive method for early dementia diagnosis that pairs NLP with machine learning. Instead of brain scans or blood tests, it derives diagnostic signals from cognitive and language assessments, enabling accessible screening for elderly populations. Built during research at Optum, published at ICDSCA 2022.

**Venue:** 2022 IEEE 2nd International Conference on Data Science and Computer Application (ICDSCA), pp. 75–79
**Links:** [Paper (IEEE Xplore)](https://ieeexplore.ieee.org/abstract/document/9987931)

<!-- image slot -->

---

## Automated Test-Case Analytics (Jira + Zephyr Scale)

**Affiliation:** Independent (first author)
**Co-researchers:** Amit Baranwal (DataCore Software), Sugandha Sahay (Carnegie Mellon University)

    Novel methodology to measure test-case automation across corporate software infrastructure. Authenticates against a company's cloud servers, pulls test-case records, and parses them into metrics on automation coverage and status for management. Published & presented at GTMBC 2022.

**Venue:** "Data Analytics on Automation of Test Case Infrastructure with Jira and ZephyrScale," Global Technology and Business Management Conference (GTBMC) 2022, p. 33
**Links:** [Conference proceedings](https://gtbmc.org/gtbmc2022-conference-proceedings/)

<!-- image slot -->

---

## Visibility Correction for Autonomous Vehicles

**Affiliation:** Independent (first author)

A two-stage deep learning system to improve object detection for autonomous vehicles in adverse weather. Consists of a Visibility Correction Module masks and removes rain, snow, and fog, & an Object Detection Module to label cleaned frames. Reached 89.72% average accuracy, beating YOLOv3 on accuracy and detection time. 

**Venue:** Journal of Emerging Investigators, October 31, 2022 · [doi:10.59720/22-101](https://doi.org/10.59720/22-101)
**Links:** [Article](https://emerginginvestigators.org/articles/22-101) · [Full PDF](https://emerginginvestigators.org/articles/22-101/pdf)

<!-- image slot: JEI cover figure on the article page -->

---

# Personal Projects

## Heston Calibration

**Headline:** Real-time Heston calibration on live vol surfaces

**Tech:** <span style="color:#3776AB"><b>Python</b></span> · <span style="color:#4DABCF"><b>NumPy</b></span> · <span style="color:#0054A6"><b>SciPy</b></span> · <span style="color:#6A5ACD"><b>Financial Engineering</b></span>

Real-time calibration algorithm for the Heston stochastic-volatility model to live SPY/SPX option surfaces. Priced via the characteristic function with a Carr-Madan FFT, it uses a four-stage optimizer that reaches an R² of 0.94 and recalibrates in under 20ms.

**Links:** [Code](https://github.com/aniketxdey/heston-calibration)

<!-- image slot -->

---

## Quantra: Options Pricing Platform

**Headline:** Real-time options pricing and analysis platform

**Tech:** <span style="color:#3776AB"><b>Python</b></span> · <span style="color:#FF4B4B"><b>Streamlit</b></span> · <span style="color:#F7931E"><b>scikit-learn</b></span> · <span style="color:#4DABCF"><b>NumPy</b></span>

A educational tool I built for Dartmouth's Mathematical Finance I as TA, Quantra pulls live market data and prices contracts with Black–Scholes, a Cox–Ross–Rubinstein tree, and a 10,000-path Monte Carlo. Also computes analytical and numerical Greeks, delta-neutral hedges, and full implied-vol surfaces.

**Links:** [Code](https://github.com/aniketxdey/quantra) · [Live demo](https://advancedoptionspricing.streamlit.app/)

<!-- image slot: three UI screenshots in the quantra README -->

---

# SWE Projects

## Martian

**Headline:** AI agents that eliminate infrastructure waste

**Role:** Co-founder & CTO

**Tech:** <span style="color:#61DAFB"><b>React</b></span> · <span style="color:#3178C6"><b>TypeScript</b></span> · <span style="color:#3776AB"><b>Python</b></span> · <span style="color:#1A7F64"><b>LangGraph</b></span> · <span style="color:#D97757"><b>Claude</b></span>

A startup I co-founded with other AWS interns in Summer 2025. Martian applies agentic AI to enterprise infrastructure cost optimization, with agents map storage dependencies and execute runbooks to eliminate wasted spend. A LangGraph multi-agent MCP server drives the analysis with integrations to Azure, AWS, & GCP cloud environemnts, fronted by a TypeScript interface for fintech teams.

**Links:** [Site](https://martian-ai.com/)

<!-- image slot -->

---

## Nuggets

**Headline:** Real-time multiplayer terminal mining game

**Tech:** <span style="color:#00599C"><b>C++</b></span> · <span style="color:#8E44AD"><b>UDP / sockets</b></span>

A real-time multiplayer terminal mining game where 26 players navigate a maze for gold while an authoritative server syncs clients over UDP, with ray-cast line-of-sight visibility. Originally built for CS50 Final in C, the C++ rewrite swaps manual memory management for RAII and an unordered_map grid, rendering the full map in under 2ms per frame.

**Links:** [Code](https://github.com/aniketxdey/nuggets)

<!-- image slot: gameplay GIF in the nuggets README -->

---

## Amazon Review Analysis

**Headline:** Review rating and category classification

**Tech:** <span style="color:#3776AB"><b>Python</b></span> · <span style="color:#F7931E"><b>scikit-learn</b></span> · <span style="color:#F37626"><b>Jupyter</b></span>

A machine learning pipeline that classifies Amazon reviews by rating and clusters them by category with scikit-learn. TF-IDF and SGD classifiers tuned per rating cutoff, beating Kaggle baselines at every threshold, while clustering runs on 40 binary category-keyword features. Built for Dartmouth CS74.

**Links:** [Code](https://github.com/aniketxdey/reviews-sentiment-analysis)

<!-- image slot -->

---

## TSE: Tiny Search Engine

**Headline:** A tiny search engine: crawl, index, rank

**Tech:** <span style="color:#555555"><b>C</b></span>

A search engine in C built as three programs that communicate through the file system: a crawler that walks from a seed URL to a set depth and caches pages, an indexer that builds a word-to-page index, and a querier that evaluates AND/OR queries into ranked results. Built for Dartmouth CS50.

**Links:** [Code](https://github.com/aniketxdey/tse)

<!-- image slot: architecture screenshot in the tse README -->
