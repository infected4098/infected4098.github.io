---
title : ""
layout: posts
author_profile: false
permalink: /waveumambademo/
---
#### [Wave-U-Mamba: An End-To-End Framework For High-Quality And Efficient Speech Super Resolution](https://arxiv.org/abs/2409.09337)
<B>Yongjoon Lee</B>, Chanwoo Kim* 

_<span style="color: rgb(255, 0, 0);">arxiv preprint</span>_

#### Abstract

Speech Super-Resolution (SSR) is a task of enhancing low-resolution speech signals by restoring missing high-frequency components. Conventional approaches typically reconstruct log-mel features, followed by a vocoder that generates high-resolution speech in the waveform domain. However, as log-mel features lack phase information, this can result in performance degradation during the reconstruction phase. Motivated by recent advances with Selective State Spaces Models (SSMs), we propose a method, referred to as Wave-U-Mamba that directly performs SSR in time domain. In our comparative study, including models such as WSRGlow, NU-Wave 2, and AudioSR, Wave-U-Mamba demonstrates superior performance, achieving the lowest Log-Spectral Distance (LSD) across various low-resolution sampling rates, ranging from 8 kHz to 24 kHz. Additionally, subjective human evaluations, scored using Mean Opinion Score (MOS) reveal that our method produces SSR with natural and human-like quality. Furthermore, Wave-U-Mamba achieves these results while generating high-resolution speech over nine times faster than baseline models on a single A100 GPU, with parameter sizes less than 2% of those in the baseline models.


#### Comparisons of the super-resolved speech waveforms with State-of-the-Art (SOTA) models on some data files from VCTK-Test. 

* Ground Truth LR refers to the low-resolution (LR) signal that has sampling rates of either 12 kHz or 8 kHz.
* Ground Truth HR refers to the high-resolution (HR) signal that has sampling rates of 48 kHz. This is our target speech.
* All waveforms were volume-normalized to ensure the equivalence of other conditions.
* All spectrograms are time-frequency representations with mel-frequency as the y-axis. 

##### p360_008 (12 kHz -> 48 kHz)

| Ground Truth LR | WSRGLOW | AudioSR | **Wave-U-Mamba** | Ground Truth HR |
|-------------|-------------|-------------|-------------|--------------|
| <audio controls src="/assets/GTLOW_norm/2_p360_008.wav"></audio> | <audio controls src="/assets/WSRGLOW_norm/3_p360_008_4.wav"></audio> | <audio controls src="/assets/AUDIOSR_norm/5_p360_008.wav"></audio> | <audio controls src="/assets/OURS_norm/4_p360_008_4_.wav"></audio> | <audio controls src="/assets/GTHIGH_norm/1_p360_008.wav"></audio> |
| ![Subtitle 6 Image](/assets/GTLOW_pngs/p360_008.png) | ![Subtitle 7 Image](/assets/WSRGLOW_pngs/p360_008.png) | ![Subtitle 8 Image](/assets/AUDIOSR_sliced_pngs/p360_008_g_audiosr_sliced.png) | ![Subtitle 9 Image](/assets/OURS_pngs/p360_008.png) | ![Subtitle 10 Image](/assets/GTHIGH_pngs/p360_008.png) |

##### p361_003 (12 kHz -> 48 kHz)


| Ground Truth LR | WSRGLOW | AudioSR | **Wave-U-Mamba** | Ground Truth HR |
|--------------|--------------|--------------|--------------|--------------|
| <audio controls src="/assets/GTLOW_norm/2_p361_003.wav"></audio> | <audio controls src="/assets/WSRGLOW_norm/3_p361_003_4.wav"></audio> | <audio controls src="/assets/AUDIOSR_sliced/p361_003_g_audiosr_sliced.wav"></audio> | <audio controls src="/assets/OURS_norm/4_p361_003_4.wav"></audio> | <audio controls src="/assets/GTHIGH_norm/1_p361_003.wav"></audio> |
| ![Subtitle 6 Image](/assets/GTLOW_pngs/p361_003.png) | ![Subtitle 7 Image](/assets/WSRGLOW_pngs/p361_003.png) | ![Subtitle 8 Image](/assets/AUDIOSR_sliced_pngs/p361_003_g_audiosr_sliced.png) | ![Subtitle 9 Image](/assets/OURS_pngs/p361_003.png) | ![Subtitle 10 Image](/assets/GTHIGH_pngs/p361_003.png) |


##### p361_004 (12 kHz -> 48 kHz)


| Ground Truth LR | WSRGLOW | AudioSR | **Wave-U-Mamba** | Ground Truth HR |
|--------------|--------------|--------------|--------------|--------------|
| <audio controls src="/assets/GTLOW_norm/2_p361_004.wav"></audio> | <audio controls src="/assets/WSRGLOW_norm/3_p361_004_4.wav"></audio> | <audio controls src="/assets/AUDIOSR_sliced/p361_004_g_audiosr_sliced.wav"></audio> | <audio controls src="/assets/OURS_norm/4_p361_004_4.wav"></audio> | <audio controls src="/assets/GTHIGH_norm/1_p361_004.wav"></audio> |
| ![Subtitle 6 Image](/assets/GTLOW_pngs/p361_004.png) | ![Subtitle 7 Image](/assets/WSRGLOW_pngs/p361_004.png) | ![Subtitle 8 Image](/assets/AUDIOSR_sliced_pngs/p361_004_g_audiosr_sliced.png) | ![Subtitle 9 Image](/assets/OURS_pngs/p361_004.png) | ![Subtitle 10 Image](/assets/GTHIGH_pngs/p361_004.png) |

##### p363_010 (12 kHz -> 48 kHz)


| Ground Truth LR | WSRGLOW | AudioSR | **Wave-U-Mamba** | Ground Truth HR |
|--------------|--------------|--------------|--------------|--------------|
| <audio controls src="/assets/GTLOW_norm/2_p363_010.wav"></audio> | <audio controls src="/assets/WSRGLOW_norm/3_p363_010_4.wav"></audio> | <audio controls src="/assets/AUDIOSR_sliced/p363_010_g_audiosr_sliced"></audio> | <audio controls src="/assets/GTHIGH_norm/1_p363_010.wav"></audio> | <audio controls src="/assets/GTHIGH_norm/1_p363_010.wav"></audio> |
| ![Subtitle 6 Image](/assets/GTLOW_pngs/p363_010.png) | ![Subtitle 7 Image](/assets/WSRGLOW_pngs/p363_010.png) | ![Subtitle 8 Image](/assets/AUDIOSR_sliced_pngs/p363_010_g_audiosr_sliced.png) | ![Subtitle 9 Image](/assets/OURS_pngs/p363_010.png) | ![Subtitle 10 Image](/assets/GTHIGH_pngs/p363_010.png) |


##### p364_010 (8 kHz -> 48 kHz)


| Ground Truth LR | WSRGLOW | AudioSR | **Wave-U-Mamba** | Ground Truth HR |
|--------------|--------------|--------------|--------------|--------------|
| <audio controls src="/assets/GTLOW_norm/2_p364_010.wav"></audio> | <audio controls src="/assets/WSRGLOW_norm/3_p364_010_6.wav"></audio> | <audio controls src="/assets/AUDIOSR_sliced/p364_010_g_audiosr_sliced.wav"></audio> | <audio controls src="/assets/OURS_norm/4_p364_010_6.wav"></audio> | <audio controls src="/assets/GTHIGH_norm/1_p364_010.wav"></audio> |
| ![Subtitle 6 Image](/assets/GTLOW_pngs/p364_010.png) | ![Subtitle 7 Image](/assets/WSRGLOW_pngs/p364_010.png) | ![Subtitle 8 Image](/assets/AUDIOSR_sliced_pngs/p364_010_g_audiosr_sliced.png) | ![Subtitle 9 Image](/assets/OURS_pngs/p364_010.png) | ![Subtitle 10 Image](/assets/GTHIGH_pngs/p364_010.png) |


##### p374_002 (8 kHz -> 48 kHz)


| Ground Truth LR | WSRGLOW | AudioSR | **Wave-U-Mamba** | Ground Truth HR |
|--------------|--------------|--------------|--------------|--------------|
| <audio controls src="/assets/GTLOW_norm/2_p374_002.wav"></audio> | <audio controls src="/assets/WSRGLOW_norm/3_p374_002_6.wav"></audio> | <audio controls src="/assets/AUDIOSR_sliced/p374_002_g_audiosr_sliced.wav"></audio> | <audio controls src="/assets/OURS_norm/4_p374_002_6.wav"></audio> | <audio controls src="/assets/GTHIGH_norm/1_p374_002.wav"></audio> |
| ![Subtitle 6 Image](/assets/GTLOW_pngs/p374_002.png) | ![Subtitle 7 Image](/assets/WSRGLOW_pngs/p374_002.png) | ![Subtitle 8 Image](/assets/AUDIOSR_sliced_pngs/p374_002_g_audiosr_sliced.png) | ![Subtitle 9 Image](/assets/OURS_pngs/p374_002.png) | ![Subtitle 10 Image](/assets/GTHIGH_pngs/p374_002.png) |


