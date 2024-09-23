---
title : ""
layout: posts
author_profile: false
permalink: /waveumambademo/
---
#### [Wave-U-Mamba: An End-To-End Framework For High-Quality And Efficient Speech Super Resolution](https://arxiv.org/abs/2409.09337)
<B>Yongjoon Lee</B>, Chanwoo Kim* 

_<span style="color: rgb(255, 0, 0);">arxiv preprint</span>_

##### Abstract

Speech Super-Resolution (SSR) is a task of enhancing low-resolution speech signals by restoring missing high-frequency components. Conventional approaches typically reconstruct log-mel features, followed by a vocoder that generates high-resolution speech in the waveform domain. However, as log-mel features lack phase information, this can result in performance degradation during the reconstruction phase. Motivated by recent advances with Selective State Spaces Models (SSMs), we propose a method, referred to as Wave-U-Mamba that directly performs SSR in time domain. In our comparative study, including models such as WSRGlow, NU-Wave 2, and AudioSR, Wave-U-Mamba demonstrates superior performance, achieving the lowest Log-Spectral Distance (LSD) across various low-resolution sampling rates, ranging from 8 kHz to 24 kHz. Additionally, subjective human evaluations, scored using Mean Opinion Score (MOS) reveal that our method produces SSR with natural and human-like quality. Furthermore, Wave-U-Mamba achieves these results while generating high-resolution speech over nine times faster than baseline models on a single A100 GPU, with parameter sizes less than 2% of those in the baseline models.


##### p360_002

| Ground Truth LR | WSRGLOW | AudioSR | **Wave-U-Mamba** | Ground Truth HR |
|-------------|-------------|-------------|-------------|-------------|
| <audio controls src="/assets/GTLOW_norm/2_p360_002.wav"></audio> | <audio controls src="/assets/WSRGLOW_norm/3_p360_002_6.wav"></audio> | <audio controls src="/assets/AUDIOSR_norm/5_p360_002.wav"></audio> | <audio controls src="/assets/OURS_norm/4_p360_002_6.wav"></audio> | <audio controls src="/assets/GTHIGH_norm/1_p360_002.wav"></audio> |
| ![Subtitle 6 Image](/assets/mypic.png) | ![Subtitle 7 Image](/assets/mypic.png) | ![Subtitle 8 Image](/assets/mypic.png) | ![Subtitle 9 Image](/assets/mypic.png) | ![Subtitle 10 Image](/assets/mypic.png) |

##### p360_008

| Ground Truth LR | WSRGLOW | AudioSR | **Wave-U-Mamba** | Ground Truth HR |
|-------------|-------------|-------------|-------------|--------------|
| <audio controls src="/assets/GTLOW_norm/2_p360_008.wav"></audio> | <audio controls src="/assets/WSRGLOW_norm/3_p360_008_4.wav"></audio> | <audio controls src="/assets/AUDIOSR_norm/5_p360_008.wav"></audio> | <audio controls src="/assets/OURS_norm/4_p360_008_4_.wav"></audio> | <audio controls src="/assets/GTHIGH_norm/1_p360_008.wav"></audio> |
| ![Subtitle 6 Image](/assets/mypic.png) | ![Subtitle 7 Image](/assets/mypic.png) | ![Subtitle 8 Image](/assets/mypic.png) | ![Subtitle 9 Image](/assets/mypic.png) | ![Subtitle 10 Image](/assets/mypic.png) |

##### p361_003


| Ground Truth LR | WSRGLOW | AudioSR | **Wave-U-Mamba** | Ground Truth HR |
|--------------|--------------|--------------|--------------|--------------|
| <audio controls src="/assets/GTLOW_norm/2_p361_003.wav"></audio> | <audio controls src="/assets/WSRGLOW_norm/3_p361_003_4.wav"></audio> | <audio controls src="/assets/AUDIOSR_norm/5_p361_003.wav"></audio> | <audio controls src="/assets/OURS_norm/4_p361_003_4.wav"></audio> | <audio controls src="/assets/GTHIGH_norm/1_p361_003.wav"></audio> |
| ![Subtitle 6 Image](/assets/mypic.png) | ![Subtitle 7 Image](/assets/mypic.png) | ![Subtitle 8 Image](/assets/mypic.png) | ![Subtitle 9 Image](/assets/mypic.png) | ![Subtitle 10 Image](/assets/mypic.png) |


##### p361_004


| Ground Truth LR | WSRGLOW | AudioSR | **Wave-U-Mamba** | Ground Truth HR |
|--------------|--------------|--------------|--------------|--------------|
| <audio controls src="/assets/GTLOW_norm/2_p361_004.wav"></audio> | <audio controls src="/assets/WSRGLOW_norm/3_p361_004_4.wav"></audio> | <audio controls src="/assets/AUDIOSR_norm/5_p361_004.wav"></audio> | <audio controls src="/assets/OURS_norm/4_p361_004_4.wav"></audio> | <audio controls src="/assets/GTHIGH_norm/1_p361_004.wav"></audio> |
| ![Subtitle 6 Image](/assets/mypic.png) | ![Subtitle 7 Image](/assets/mypic.png) | ![Subtitle 8 Image](/assets/mypic.png) | ![Subtitle 9 Image](/assets/mypic.png) | ![Subtitle 10 Image](/assets/mypic.png) |

##### p363_010


| Ground Truth LR | WSRGLOW | AudioSR | **Wave-U-Mamba** | Ground Truth HR |
|--------------|--------------|--------------|--------------|--------------|
| <audio controls src="/assets/GTLOW_norm/2_p363_010.wav"></audio> | <audio controls src="/assets/WSRGLOW_norm/3_p363_010_4.wav"></audio> | <audio controls src="/assets/AUDIOSR_norm/5_p363_010.wav"></audio> | <audio controls src="/assets/GTHIGH_norm/1_p363_010.wav"></audio> | <audio controls src="audio20.wav"></audio> |
| ![Subtitle 6 Image](/assets/mypic.png) | ![Subtitle 7 Image](/assets/mypic.png) | ![Subtitle 8 Image](/assets/mypic.png) | ![Subtitle 9 Image](/assets/mypic.png) | ![Subtitle 10 Image](/assets/mypic.png) |


##### p364_010


| Ground Truth LR | WSRGLOW | AudioSR | **Wave-U-Mamba** | Ground Truth HR |
|--------------|--------------|--------------|--------------|--------------|
| <audio controls src="/assets/GTLOW_norm/2_p364_010.wav"></audio> | <audio controls src="/assets/WSRGLOW_norm/3_p364_010_6.wav"></audio> | <audio controls src="/assets/AUDIOSR_norm/5_p364_010.wav"></audio> | <audio controls src="/assets/OURS_norm/4_p364_010_6.wav"></audio> | <audio controls src="/assets/GTHIGH_norm/1_p364_010.wav"></audio> |
| ![Subtitle 6 Image](/assets/mypic.png) | ![Subtitle 7 Image](/assets/mypic.png) | ![Subtitle 8 Image](/assets/mypic.png) | ![Subtitle 9 Image](/assets/mypic.png) | ![Subtitle 10 Image](/assets/mypic.png) |


##### p374_002


| Ground Truth LR | WSRGLOW | AudioSR | **Wave-U-Mamba** | Ground Truth HR |
|--------------|--------------|--------------|--------------|--------------|
| <audio controls src="/assets/GTLOW_norm/2_p374_002.wav"></audio> | <audio controls src="/assets/WSRGLOW_norm/3_p374_002_6.wav"></audio> | <audio controls src="/assets/AUDIOSR_norm/5_p374_002.wav"></audio> | <audio controls src="/assets/OURS_norm/4_p374_002_6.wav"></audio> | <audio controls src="/assets/GTHIGH_norm/1_p374_002.wav"></audio> |
| ![Subtitle 6 Image](/assets/mypic.png) | ![Subtitle 7 Image](/assets/mypic.png) | ![Subtitle 8 Image](/assets/mypic.png) | ![Subtitle 9 Image](/assets/mypic.png) | ![Subtitle 10 Image](/assets/mypic.png) |


##### p374_005


| Ground Truth LR | WSRGLOW | AudioSR | **Wave-U-Mamba** | Ground Truth HR |
|--------------|--------------|--------------|--------------|--------------|
| <audio controls src="/assets/GTLOW_norm/2_p360_005.wav"></audio> | <audio controls src="/assets/WSRGLOW_norm/3_p374_005_6.wav"></audio> | <audio controls src="/assets/AUDIOSR_norm/5_p374_005.wav"></audio> | <audio controls src="/assets/OURS_norm/4_p374_005_6.wav"></audio> | <audio controls src="/assets/GTHIGH_norm/1_p374_005.wav"></audio> |
| ![Subtitle 6 Image](/assets/mypic.png) | ![Subtitle 7 Image](/assets/mypic.png) | ![Subtitle 8 Image](/assets/mypic.png) | ![Subtitle 9 Image](/assets/mypic.png) | ![Subtitle 10 Image](/assets/mypic.png) |
