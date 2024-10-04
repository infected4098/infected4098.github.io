---
title : ""
layout: single
author_profile: true
permalink: /publications/
---
#### [Wave-U-Mamba: An End-To-End Framework For High-Quality And Efficient Speech Super Resolution](https://arxiv.org/abs/2409.09337)
<B>Yongjoon Lee</B>, Chanwoo Kim

_<span style="color: rgb(255, 0, 0);">arxiv preprint</span>_

Speech Super-Resolution (SSR) is a task of enhancing low-resolution speech signals by restoring missing high-frequency components. Conventional approaches typically reconstruct log-mel features, followed by a vocoder that generates high-resolution speech in the waveform domain. However, as log-mel features lack phase information, this can result in performance degradation during the reconstruction phase. Motivated by recent advances with Selective State Spaces Models (SSMs), we propose a method, referred to as Wave-U-Mamba that directly performs SSR in time domain. In our comparative study, including models such as WSRGlow, NU-Wave 2, and AudioSR, Wave-U-Mamba demonstrates superior performance, achieving the lowest Log-Spectral Distance (LSD) across various low-resolution sampling rates, ranging from 8 kHz to 24 kHz. Additionally, subjective human evaluations, scored using Mean Opinion Score (MOS) reveal that our method produces SSR with natural and human-like quality. Furthermore, Wave-U-Mamba achieves these results while generating high-resolution speech over nine times faster than baseline models on a single A100 GPU, with parameter sizes less than 2% of those in the baseline models.


