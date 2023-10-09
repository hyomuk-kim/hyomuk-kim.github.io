---
title: "Neural Speech Synthesis"
excerpt: " <b>For the deployment of AI voice services using deep generative models.</b> <br/><img src='/images/500x300.png'>"
collection: portfolio
---

_Information_
* _Apr. 2018 ~ Jan. 2020 @Language & Voice Team with 10 members_
  _(4 members in overseas research institute)._

### Goal
The aim of this project is to develop a commercially viable and efficient deep learning-based speech synthesis model.

### Need
During a period when entertaining demonstrations mimicking celebrities' voices using deep learning-based open-source tools were on the rise, we aimed to replace our already commercialized parametric TTS model with a high-quality yet lightweight neural synthesis solution, which is possible to serve as AI voice synthesizer for Bixby. This new solution needed to be capable of serving as an AI voice synthesis engine for Bixby.

### Approach
Before moving towards a complete end-to-end model, we conducted research by incrementally developing a neural speech synthesis model that combined an **Acoustic Model** based on [_Tacotron_](https://google.github.io/tacotron/)<sup>[1]</sup> or _DC-TTS_<sup>[2]</sup> with a **Vocoder Model** like [_WaveNet_](https://www.deepmind.com/blog/wavenet-a-generative-model-for-raw-audio)<sup>[3]</sup>, [_Parallel WaveNet_](https://www.deepmind.com/blog/high-fidelity-speech-synthesis-with-wavenet)<sup>[4]</sup>, _WaveRNN_<sup>[5]</sup>, or _LPCNet_<sup>[6]</sup>.

The acoustic model takes sequential texts as inputs and produces the inferred mel spectrogram using an attention-based seq2seq model. Subsequently, the vocoder model takes the mel spectrogram and converts it into speech data using residual blocks including dilated causal convolution layers.

![Residual Blocks](/images/residual_block.png "Residual Blocks")
<span style="color:gray">       Residual blocks</span>

![Dilated Causal Convolution layers](/images/dilated_causal_convolution.gif "Dilated Causal Convolution layers")
<span style="color:gray">       Dilated Causal Convolution layers</span>

### Insights & Further Considerations
* aa

* bb

### References

[1] Wang, Yuxuan, et al. "[Tacotron: Towards End-to-End Speech Synthesis.](https://arxiv.org/abs/1703.10135)" Interspeech 2017 (2017).

[2] Tachibana, Hideyuki, Katsuya Uenoyama, and Shunsuke Aihara. "[Efficiently trainable text-to-speech system based on deep convolutional networks with guided attention.](https://ieeexplore.ieee.org/abstract/document/8461829)" 2018 IEEE international conference on acoustics, speech and signal processing (ICASSP). IEEE, 2018.

[3] Oord, Aaron van den, et al. "[Wavenet: A generative model for raw audio.](https://arxiv.org/abs/1609.03499)" arXiv preprint arXiv:1609.03499 (2016).

[4] Oord, Aaron, et al. "[Parallel wavenet: Fast high-fidelity speech synthesis.](https://proceedings.mlr.press/v80/oord18a.html)" International conference on machine learning. PMLR, 2018.

[5] Kalchbrenner, Nal, et al. "[Efficient neural audio synthesis.](https://proceedings.mlr.press/v80/kalchbrenner18a.html)" International Conference on Machine Learning. PMLR, 2018.

[6] Valin, Jean-Marc, and Jan Skoglund. "[LPCNet: Improving neural speech synthesis through linear prediction.](https://ieeexplore.ieee.org/abstract/document/8682804)" ICASSP 2019-2019 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP). IEEE, 2019.

***

> I became interested in pursuing a career as a researcher while working on the speech synthesis project. Furthermore, through collaborating on AI voice support for robots, I have continued to nurture the same desire I had when working on TV system development – the exploration of dynamic systems. These thoughts have become intertwined with my passion for self-maintenance and track driving, combined with my love for cars, which has further fueled my strong desire for research in robotics and autonomous driving. So, in response to the request for resources to develop a multimodal interaction framework for "robots" and AR/VR, I decided to move to the AI Center with the hope of making a meaningful contribution to the robot system...
