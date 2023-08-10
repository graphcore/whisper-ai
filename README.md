<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/81682248/226963550-21eaaf59-ee3c-49a9-8e75-b76d740ddd09.png">
  <img width="300" alt="Graphcore logo" src="https://user-images.githubusercontent.com/81682248/226963440-9cae0ac4-ebf5-407a-9870-5679e434cada.png">
</picture>

# Whisper on IPUs
<img width="500" alt="Waveform" src="https://github.com/graphcore/whisper/assets/81682248/5f21338f-5358-4686-97cc-1f321405607f">

Whisper is a versatile speech recognition model that can transcribe speech as well as perform multi-lingual translation and recognition tasks. It was trained on diverse datasets to give human-level speech recognition performance without the need for fine-tuning.

Graphcore's IPU (Intelligence Processing Unit) is a completely new kind of massively parallel processor to accelerate machine intelligence. Developers can access advanced, cost-efficient IPU compute on-demand in the cloud for building, fine-tuning and deploying AI models such as Whisper.


## Whisper Notebooks powered by IPUs

| Notebook | Framework | Type | Try for Free
| ------------- | ------------- | ------------- | ------------- |
| Speech Transcription on IPUs using Whisper Tiny | Hugging Face | Inference | [![Gradient](https://assets.paperspace.io/img/gradient-badge.svg)](https://ipu.dev/RxNoMC)
| Multi-lingual ASR Transcription on IPUs using Whisper - Fine-tuning | Hugging Face | Fine-tuning | [![Gradient](https://assets.paperspace.io/img/gradient-badge.svg)](https://ipu.dev/1cP6n2)
| Speech Transcription on IPUs using Whisper - Quantized Inference | Hugging Face | Inference | [![Gradient](https://assets.paperspace.io/img/gradient-badge.svg)](https://ipu.dev/Djq2SC)

In the **Speech Transcription on IPUs using Whisper Tiny | Hugging Face** notebook, we demonstrate using Whisper Tiny for speech recognition and transcription on the IPU. We use Optimum Graphcore - a new open-source library and toolkit that enables developers to access IPU-optimized models certified by Hugging Face. Only a few lines of code are needed to get this state-of-the-art automated speech recognition model running on IPUs.

In the **Multi-lingual ASR Transcription on IPUs using Whisper - Fine-tuning** notebook, we demonstrate fine-tuning for multi-lingual speech transcription on the IPU using the Whisper implementation in the 🤗 Transformers library alongside Optimum Graphcore.

In the **Speech Transcription on IPUs using Whisper - Quantized Inference** notebook, we demonstrate speech transcription on the IPU using the Whisper implementation in the 🤗 Transformers library alongside Optimum Graphcore using INT4 group quantization.


## Whisper Resources

* [GitHub Code](https://github.com/graphcore/Gradient-HuggingFace/tree/main/early-access/whisper)
* [Hugging Face Model](https://huggingface.co/Graphcore/whisper-tiny-ipu)
* [How-to Walkthrough Blog](https://www.graphcore.ai/posts/how-to-use-openais-whisper-for-speech-recognition)
* [Original Paper](https://arxiv.org/abs/2212.04356)

To take your Whisper usage on IPUs further, or speak to an expert, please feel free to [contact us](https://www.graphcore.ai/speak-to-an-expert-whisper-ai).

## IPU Community

Join our growing community and interact with AI experts, IPU developers and researchers. Hear the latest IPU news and get access to our newest models.

[![Join our Slack Community](https://img.shields.io/badge/Slack-Join%20Graphcore's%20Community-blue?style=flat-square&logo=slack)](https://www.graphcore.ai/join-community)

## License

The contents of this repository are made available according to the terms of the Apache 2.0 license. See the included [LICENSE](LICENSE) file for details.
