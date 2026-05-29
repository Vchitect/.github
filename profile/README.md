<div align="center">

<p align="center">
    <picture>
<img src="imgs/logo.png?raw=true" width="350">
    </picture>
</p>

![Stars](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/Vchitect/.github/main/badges/stars.json)

</div>

Welcome to the Vchitect homepage. Vchitect is mainly developed by Shanghai AI Laboratory. We keep working in the field of video generation, open-sourcing the models, benchmark suites, and efficient training tools.

## 🔥 Updates

**Vchitect 2.0**

- [09/2024] We release Vchitect 2.0, including the model and the training system
  - **Model**: 
    - [Vchitect-2.0](https://github.com/Vchitect/Vchitect-2.0) is a high-quality video generative model with **2 billion parameters,** supporting resolutions up to 720x480 and video durations of 10-20 seconds.
    - [VEnhancer](https://github.com/Vchitect/VEnhancer) is a generative space-time enhancement framework. It integrates super-resolution, frame interpolation, and video refinement to elevate the video quality to **2K resolution at 24 FPS**.
  - **System**: 
    - [LiteGen](https://github.com/Vchitect/LiteGen) is a lightweight and highly efficient training framework for diffusion tasks. It supports sequence lengths of up to **1.63 million tokens** using 8x NVIDIA A100 GPU cards during the training of the [Vchitect-2.0](https://github.com/Vchitect/Vchitect-2.0) model.
    - [FasterCache](https://github.com/Vchitect/FasterCache) is a training-free method for accelerating video sampling in diffusion transformers.
  - **Evaluation**: 
    - [VBench](https://github.com/Vchitect/VBench) is a comprehensive benchmark suite for video generative models, covering **56 text-to-video generation models**.
    - [VBench++](https://github.com/Vchitect/VBench) further supports image-to-video evaluation, with an Image Suite of high-resolution images and adaptive aspect ratios. It also focuses on trustworthiness of video generative models like fairness, bias, and safety.
    - [Evaluation Agent](https://vchitect.github.io/Evaluation-Agent-project/) is an efficient evaluation paradigm for visual generative models. It uses dynamic multi-round evaluations, reducing evaluation time to 10% of traditional methods while ensuring efficiency, customization, and explainability.


## 🎁 Model

- 🎉 **[new]** [Vchitect-2.0](https://github.com/Vchitect/Vchitect-2.0): A high-quality video generation video with resolutions up to 720x480 and video durations of 10-20 seconds.
- 🎉 **[new]** [VEnhancer](https://github.com/Vchitect/VEnhancer): A generative space-time enhancement framework that can improve the existing T2V results.



## 🚀 System
- 🎉 **[new]** [FasterCache](https://github.com/Vchitect/FasterCache): A training-free method for accelerating video sampling in diffusion transformers.
- 🎉 **[new]** [LiteGen](https://github.com/Vchitect/LiteGen): A light-weight and high-efficient training framework for accelerating diffusion tasks.



## 🏔️ Evaluation

- 🎉 **[new]** [Evaluation Agent](https://vchitect.github.io/Evaluation-Agent-project/): An efficient and promptable evaluation paradigm for visual generative models.
- 🎉 **[new]** [VBench++](https://github.com/Vchitect/VBench): A comprehensive benchmark suite for video generative models with image-to-video and trustworthiness evaluation support.
- 🎉 **[new]** [VBench](https://github.com/Vchitect/VBench): A comprehensive benchmark suite for video generative models

## Latte
- [Latte](https://github.com/Vchitect/Latte): Latent Diffusion Transformer for Video Generation

## Vchitect 1.0
- [LaVie](https://github.com/Vchitect/LaVie): High-Quality Video Generation with Cascaded Latent Diffusion Models
- [SEINE](https://github.com/Vchitect/SEINE): Short-to-Long Video Diffusion Model for Generative Transition and Prediction
- [VideoBooth](https://github.com/Vchitect/VideoBooth): Diffusion-based Video Generation with Image Prompts
- [Vlogger](https://github.com/Vchitect/Vlogger): A generic AI system for generating a minute-level video blog (i.e., vlog) of user descriptions.
- [Optix](https://github.com/Vchitect/Optix): Memory Efficient Training Framework for Large Video Generation Model
