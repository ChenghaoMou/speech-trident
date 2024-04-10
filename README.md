# :trident: Speech Trident - Awesome Speech LM

<p align="center">
  <img src="assets/Speech-Trident-v2.png" alt="Speech Trident" style="width:70%;">
</p>

In this repository, we survey three crucial areas: (1) representation learning, (2) neural codec, and (3) language models that contribute to speech/audio large language models.

1.⚡ **Speech Representation Models:** These models focus on learning structural speech representations, which can then be quantized into discrete speech tokens, often refer to **semantic tokens**.

2.⚡ **Speech Neural Codec Models:** These models are designed to learn speech and audio discrete tokens, often referred to as **acoustic tokens**, while maintaining reconstruction ability and low bitrate.

3.⚡ **Speech Large Language Models:** These models are trained on top of speech and acoustic tokens in a language modeling approach. They demonstrate proficiency in tasks on speech understanding and speech generation.

## :trident: Contributors

<table>
  <tr>
    <td align="center">
      <a href="https://kwchang.org/">
        <img src="https://avatars.githubusercontent.com/u/20485030?v=4" width="100px;" style="border-radius: 50%;" alt=""/>
        <br />
        <sub><b>Kai-Wei Chang</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://hbwu-ntu.github.io/">
        <img src="https://scholar.googleusercontent.com/citations?view_op=medium_photo&user=-bB-WHEAAAAJ&citpid=1" width="100px;" style="border-radius: 50%;" alt=""/>
        <br />
        <sub><b>Haibin Wu</b></sub>
      </a>
    </td>
      <td align="center">
      <a href="https://scholar.google.com.tw/citations?user=-d6aNP0AAAAJ&hl=zh-TW">
        <img src="https://scholar.googleusercontent.com/citations?view_op=medium_photo&user=-d6aNP0AAAAJ&citpid=2" width="100px;" style="border-radius: 50%;" alt=""/>
        <br />
        <sub><b>Wei-Cheng Tseng</b></sub>
      </a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://kehanlu.com/">
        <img src="https://avatars.githubusercontent.com/u/22369406?v=4" width="100px;" style="border-radius: 50%;" alt=""/>
        <br />
        <sub><b>Kehan Lu</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/kuan2jiu99">
        <img src="https://avatars.githubusercontent.com/u/95064418?v=4" width="100px;" style="border-radius: 50%;" alt=""/>
        <br />
        <sub><b>Chun-Yi Kuan</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://speech.ee.ntu.edu.tw/~hylee/index.php">
        <img src="https://yt3.googleusercontent.com/ytc/AIdro_mlTtuvk8IoEtfAKvw7WDc0XuxqGBCjMn-klO63nQbfVjE=s176-c-k-c0x00ffffff-no-rj" width="100px;" style="border-radius: 50%;" alt=""/>
        <br />
        <sub><b>Hung-yi Lee</b></sub>
      </a>
    </td>
  </tr>
</table>

## :trident: Speech/Audio Language Models

| Date    | Model Name     | Paper Title                                                                                                           | Link                                      |
| ------- | -------------- | --------------------------------------------------------------------------------------------------------------------- | ----------------------------------------- |
| 2024-04 | WavLLM         | WavLLM: Towards Robust and Adaptive Speech Large Language Model                                                       | [paper](https://arxiv.org/abs/2404.00656) |
| 2024-02 | SLAM-ASR       | An Embarrassingly Simple Approach for LLM with Strong ASR Capacity                                                    | [paper](https://arxiv.org/abs/2402.08846) |
| 2024-02 | AnyGPT         | AnyGPT: Unified Multimodal LLM with Discrete Sequence Modeling                                                        | [paper](https://arxiv.org/abs/2402.12226) |
| 2024-02 | SpiRit-LM      | SpiRit-LM: Interleaved Spoken and Written Language Model                                                              | [paper](https://arxiv.org/abs/2402.05755) |
| 2024-02 | BAT            | BAT: Learning to Reason about Spatial Sounds with Large Language Models                                               | [paper](https://arxiv.org/abs/2402.01591) |
| 2024-02 | Audio Flamingo | Audio Flamingo: A Novel Audio Language Model with Few-Shot Learning and Dialogue Abilities                            | [paper](https://arxiv.org/abs/2402.01831) |
| 2023-12 | Seamless       | Seamless: Multilingual Expressive and Streaming Speech Translation                                                    | [paper](https://arxiv.org/abs/2312.05187) |
| 2023-11 | Qwen-Audio     | Qwen-Audio: Advancing Universal Audio Understanding via Unified Large-Scale Audio-Language Models                     | [paper](https://arxiv.org/abs/2311.07919) |
| 2023-10 | LauraGPT       | LauraGPT: Listen, Attend, Understand, and Regenerate Audio with GPT                                                   | [paper](https://arxiv.org/abs/2310.04673) |
| 2023-10 | SALMONN        | SALMONN: Towards Generic Hearing Abilities for Large Language Models                                                  | [paper](https://arxiv.org/abs/2310.13289) |
| 2023-10 | UniAudio       | UniAudio: An Audio Foundation Model Toward Universal Audio Generation                                                 | [paper](https://arxiv.org/abs/2310.00704) |
| 2023-09 | VoxtLM         | Voxtlm: unified decoder-only models for consolidating speech recognition/synthesis and speech/text continuation tasks | [paper](https://arxiv.org/abs/2309.07937) |
| 2023-09 | LTU-AS         | Joint Audio and Speech Understanding                                                                                  | [paper](https://arxiv.org/abs/2309.14405) |
| 2023-09 | SLM            | SLM: Bridge the thin gap between speech and text foundation models                                                    | [paper](https://arxiv.org/abs/2310.00230) |
| 2023-08 | SpeechGen      | SpeechGen: Unlocking the Generative Power of Speech Language Models with Prompts                                      | [paper](https://arxiv.org/abs/2306.02207) |
| 2023-08 | SpeechX        | SpeechX: Neural Codec Language Model as a Versatile Speech Transformer                                                | [paper](https://arxiv.org/abs/2308.06873) |
| 2023-08 | LLaSM          | Large Language and Speech Model                                                                                       | [paper](https://arxiv.org/abs/2308.15930) |
| 2023-08 | SeamlessM4T    | Massively Multilingual & Multimodal Machine Translation                                                               | [paper](https://arxiv.org/abs/2308.11596) |
| 2023-07 | Speech-LLaMA   | On decoder-only architecture for speech-to-text and large language model integration                                  | [paper](https://arxiv.org/abs/2307.03917) |
| 2023-06 | AudioPaLM      | AudioPaLM: A Large Language Model That Can Speak and Listen                                                           | [paper](https://arxiv.org/abs/2306.12925) |
| 2023-05 | TWIST          | Textually Pretrained Speech Language Models                                                                           | [paper](https://arxiv.org/abs/2305.13009) |
| 2023-05 | Pengi          | Pengi: An Audio Language Model for Audio Tasks                                                                        | [paper](https://arxiv.org/abs/2305.11834) |
| 2023-05 | SoundStorm     | Efficient Parallel Audio Generation                                                                                   | [paper](https://arxiv.org/abs/2305.09636) |
| 2023-05 | LTU            | Joint Audio and Speech Understanding                                                                                  | [paper](https://arxiv.org/abs/2305.10790) |
| 2023-05 | SpeechGPT      | Empowering Large Language Models with Intrinsic Cross-Modal Conversational Abilities                                  | [paper](https://arxiv.org/abs/2305.11000) |
| 2023-05 | VioLA          | Unified Codec Language Models for Speech Recognition, Synthesis, and Translation                                      | [paper](https://arxiv.org/abs/2305.16107) |
| 2023-05 | X-LLM          | X-LLM: Bootstrapping Advanced Large Language Models by Treating Multi-Modalities as Foreign Languages                 | [paper](https://arxiv.org/abs/2305.04160) |
| 2023-03 | VALL-E X       | Speak Foreign Languages with Your Own Voice: Cross-Lingual Neural Codec Language Modeling                             | [paper](https://arxiv.org/abs/2303.03926) |
| 2023-02 | SPEAR-TTS      | Speak, Read and Prompt: High-Fidelity Text-to-Speech with Minimal Supervision                                         | [paper](https://arxiv.org/abs/2302.03540) |
| 2023-01 | VALL-E         | Neural Codec Language Models are Zero-Shot Text to Speech Synthesizers                                                | [paper](https://arxiv.org/abs/2301.02111) |
| 2022-10 | AudioGen       | AudioGen: Textually Guided Audio Generation                                                                           | [paper](https://arxiv.org/abs/2209.15352) |
| 2022-09 | AudioLM        | AudioLM: a Language Modeling Approach to Audio Generation                                                             | [paper](https://arxiv.org/abs/2209.03143) |
| 2022-05 | Wav2Seq        | Wav2Seq: Pre-training Speech-to-Text Encoder-Decoder Models Using Pseudo Languages                                    | [paper](https://arxiv.org/abs/2205.01086) |
| 2022-04 | Unit mBART     | Enhanced Direct Speech-to-Speech Translation Using Self-supervised Pre-training and Data Augmentation                 | [paper](https://arxiv.org/abs/2204.02967) |
| 2022-03 | d-GSLM         | Generative Spoken Dialogue Language Modeling                                                                          | [paper](https://arxiv.org/abs/2203.16502) |
| 2021-10 | SLAM           | SLAM: A Unified Encoder for Speech and Language Modeling via Speech-Text Joint Pre-Training                           | [paper](https://arxiv.org/abs/2110.10329) |
| 2021-09 | p-GSLM         | Text-Free Prosody-Aware Generative Spoken Language Modeling                                                           | [paper](https://arxiv.org/abs/2109.03264) |
| 2021-02 | GSLM           | Generative Spoken Language Modeling from Raw Audio                                                                    | [paper](https://arxiv.org/abs/2102.01192) |

## :trident: Speech/Audio Representation Models

| Date    | Model Name   | Paper Title                                                                                                   | Link                                      |
| ------- | ------------ | ------------------------------------------------------------------------------------------------------------- | ----------------------------------------- |
| 2024-01 | EAT          | Self-Supervised Pre-Training with Efficient Audio Transformer                                                 | [paper](https://arxiv.org/abs/2401.03497) |
| 2023-10 | MR-HuBERT    | Multi-resolution HuBERT: Multi-resolution Speech Self-Supervised Learning with Masked Unit Prediction         | [paper](https://arxiv.org/abs/2310.02720) |
| 2023-10 | SpeechFlow   | Generative Pre-training for Speech with Flow Matching                                                         | [paper](https://arxiv.org/abs/2310.16338) |
| 2023-09 | WavLabLM     | Joint Prediction and Denoising for Large-scale Multilingual Self-supervised Learning                          | [paper](https://arxiv.org/abs/2309.15317) |
| 2023-08 | W2v-BERT 2.0 | Massively Multilingual & Multimodal Machine Translation                                                       | [paper](https://arxiv.org/abs/2308.11596) |
| 2023-07 | Whisper-AT   | Noise-Robust Automatic Speech Recognizers are Also Strong General Audio Event Taggers                         | [paper](https://arxiv.org/abs/2307.03183) |
| 2023-06 | ATST         | Self-supervised Audio Teacher-Student Transformer for Both Clip-level and Frame-level Tasks                   | [paper](https://arxiv.org/abs/2306.04186) |
| 2023-05 | SPIN         | Self-supervised Fine-tuning for Improved Content Representations by Speaker-invariant Clustering              | [paper](https://arxiv.org/abs/2305.11072) |
| 2023-05 | DinoSR       | Self-Distillation and Online Clustering for Self-supervised Speech Representation Learning                    | [paper](https://arxiv.org/abs/2305.10005) |
| 2023-05 | NFA          | Self-supervised neural factor analysis for disentangling utterance-level speech representations               | [paper](https://arxiv.org/abs/2305.08099) |
| 2022-12 | Data2vec 2.0 | Efficient Self-supervised Learning with Contextualized Target Representations for Vision, Speech and Language | [paper](https://arxiv.org/abs/2212.07525) |
| 2022-12 | BEATs        | Audio Pre-Training with Acoustic Tokenizers                                                                   | [paper](https://arxiv.org/abs/2212.09058) |
| 2022-11 | MT4SSL       | MT4SSL: Boosting Self-Supervised Speech Representation Learning by Integrating Multiple Targets               | [paper](https://arxiv.org/abs/2211.07321) |
| 2022-08 | DINO         | Non-contrastive self-supervised learning of utterance-level speech representations                            | [paper](https://arxiv.org/abs/2208.05413) |
| 2022-07 | Audio-MAE    | Masked Autoencoders that Listen                                                                               | [paper](https://arxiv.org/abs/2207.06405) |
| 2022-03 | MAE-AST      | Masked Autoencoding Audio Spectrogram Transformer                                                             | [paper](https://arxiv.org/abs/2203.16691) |
| 2022-03 | LightHuBERT  | Lightweight and Configurable Speech Representation Learning with Once-for-All Hidden-Unit BERT                | [paper](https://arxiv.org/abs/2203.15610) |
| 2022-02 | Data2vec     | A General Framework for Self-supervised Learning in Speech, Vision and Language                               | [paper](https://arxiv.org/abs/2202.03555) |
| 2021-10 | WavLM        | WavLM: Large-Scale Self-Supervised Pre-Training for Full Stack Speech Processing                              | [paper](https://arxiv.org/abs/2110.13900) |
| 2021-08 | W2v-BERT     | Combining Contrastive Learning and Masked Language Modeling for Self-Supervised Speech Pre-Training           | [paper](https://arxiv.org/abs/2108.06209) |
| 2021-07 | mHuBERT      | Direct speech-to-speech translation with discrete units                                                       | [paper](https://arxiv.org/abs/2107.05604) |
| 2021-06 | HuBERT       | Self-Supervised Speech Representation Learning by Masked Prediction of Hidden Units                           | [paper](https://arxiv.org/abs/2106.07447) |
| 2021-03 | BYOL-A       | Self-Supervised Learning for General-Purpose Audio Representation                                             | [paper](https://arxiv.org/abs/2103.06695) |
| 2020-12 | DeCoAR2.0    | DeCoAR 2.0: Deep Contextualized Acoustic Representations with Vector Quantization                             | [paper](https://arxiv.org/abs/2012.06659) |
| 2020-07 | TERA         | TERA: Self-Supervised Learning of Transformer Encoder Representation for Speech                               | [paper](https://arxiv.org/abs/2007.06028) |
| 2020-06 | Wav2vec2.0   | wav2vec 2.0: A Framework for Self-Supervised Learning of Speech Representations                               | [paper](https://arxiv.org/abs/2006.11477) |
| 2019-10 | APC          | Generative Pre-Training for Speech with Autoregressive Predictive Coding                                      | [paper](https://arxiv.org/abs/1910.12607) |
| 2018-07 | CPC          | Representation Learning with Contrastive Predictive Coding                                                    | [paper](https://arxiv.org/abs/1807.03748) |

## :trident: Speech/Audio Codec Models

| Date    | Model Name           | Paper Title                                                                                                                                                | Link                                      |
| ------- | -------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------- |
| 2024-03 | FACodec              | NaturalSpeech 3: Zero-Shot Speech Synthesis with Factorized Codec and Diffusion Models                                                                     | [paper](https://arxiv.org/abs/2403.03100) |
| 2024-02 | Language-Codec       | Language-Codec: Reducing the Gaps Between Discrete Codec Representation and Speech Language Models                                                         | [paper](https://arxiv.org/abs/2402.12208) |
| 2024-01 | ScoreDec             | ScoreDec: A Phase-preserving High-Fidelity Audio Codec with A Generalized Score-based Diffusion Post-filter                                                | [paper](https://arxiv.org/abs/2401.12160) |
| 2023-11 | HierSpeech++         | HierSpeech++: Bridging the Gap between Semantic and Acoustic Representation of Speech by Hierarchical Variational Inference for Zero-shot Speech Synthesis | [paper](https://arxiv.org/abs/2311.12454) |
| 2023-09 | FunCodec             | FunCodec: A Fundamental, Reproducible and Integrable Open-source Toolkit for Neural Speech Codec                                                           | [paper](https://arxiv.org/abs/2309.07405) |
| 2023-08 | SpeechTokenizer      | Speechtokenizer: Unified speech tokenizer for speech large language models                                                                                 | [paper](https://arxiv.org/abs/2308.16692) |
| 2023-06 | Descript-audio-codec | High-Fidelity Audio Compression with Improved RVQGAN                                                                                                       | [paper](https://arxiv.org/abs/2306.06546) |
| 2023-05 | AudioDec             | Audiodec: An open-source streaming highfidelity neural audio codec                                                                                         | [paper](https://arxiv.org/abs/2305.16608) |
| 2023-05 | HiFi-Codec           | Hifi-codec: Group-residual vector quantization for high fidelity audio codec                                                                               | [paper](https://arxiv.org/abs/2305.02765) |
| 2023-03 | LMCodec              | LMCodec: A Low Bitrate Speech Codec With Causal Transformer Models                                                                                         | [paper](https://arxiv.org/abs/2303.12984) |
| 2022-10 | EnCodec              | High fidelity neural audio compression                                                                                                                     | [paper](https://arxiv.org/abs/2210.13438) |
| 2021-07 | SoundStream          | SoundStream: An End-to-End Neural Audio Codec                                                                                                              | [paper](https://arxiv.org/abs/2107.03312) |

## :trident: ICASSP 2024 Tutorial Information

I (Kai-Wei Chang) will be giving a talk as part of the [ICASSP 2024 tutorial](https://cmsworkshops.com/ICASSP2024/tutorials.php#tut32) titled **Parameter-Efficient and Prompt Learning for Speech and Language Foundation Models**. The topic will cover nowday's speech/audio large language models.

Tutorial speakers:

- Dr. Huck Yang (NVIDIA)
- Dr. Pin-Yu Chen (IBM Research)
- Prof. Hung-yi Lee (National Taiwan University)
- Kai-Wei Chang (National Taiwan University)
- Cheng-Han Chiang (National Taiwan University)

See you in Seoul!

## :trident: Related Repository

- https://github.com/liusongxiang/Large-Audio-Models
- https://github.com/kuan2jiu99/Awesome-Speech-Generation
- https://github.com/ga642381/Speech-Prompts-Adapters
- https://github.com/huckiyang/awesome-neural-reprogramming-prompting

## Citation

If you find this toolkit useful, please consider citing the following papers.

```
@article{wu2024codec,
  title={Codec-SUPERB: An In-Depth Analysis of Sound Codec Models},
  author={Wu, Haibin and Chung, Ho-Lam and Lin, Yi-Cheng and Wu, Yuan-Kuei and Chen, Xuanjun and Pai, Yu-Chi and Wang, Hsiu-Hsuan and Chang, Kai-Wei and Liu, Alexander H and Lee, Hung-yi},
  journal={arXiv preprint arXiv:2402.13071},
  year={2024}
}
```

```
@article{wu2024towards,
  title={Towards audio language modeling-an overview},
  author={Wu, Haibin and Chen, Xuanjun and Lin, Yi-Cheng and Chang, Kai-wei and Chung, Ho-Lam and Liu, Alexander H and Lee, Hung-yi},
  journal={arXiv preprint arXiv:2402.13236},
  year={2024}
}
```
