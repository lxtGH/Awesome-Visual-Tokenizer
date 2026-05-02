# Awesome-Visual-Tokenizer

This repository organizes papers on visual tokenizers following the survey taxonomy in our draft.

- `Task-Specific Tokenizers`: tokenizers mainly designed for perception, reconstruction, or compression.
- `Unified Tokenizers`: tokenizers designed to support both visual understanding and generation.

Notes:

- `-` means we did not find a public code or project link in the current notes.

## Task-Specific Tokenizers

### Variational / Continuous Foundations

| Alias | Paper | Link | Code / Project |
| --- | --- | --- | --- |
| VAE | Auto-Encoding Variational Bayes | [Paper](https://arxiv.org/abs/1312.6114) | - |
| - | Variational Inference with Normalizing Flows | [Paper](https://arxiv.org/abs/1505.05770) | - |
| - | Adversarial Autoencoders | [Paper](https://arxiv.org/abs/1511.05644) | - |
| - | Generating Sentences from a Continuous Space | [Paper](https://arxiv.org/abs/1511.06349) | - |
| - | Ladder Variational Autoencoders | [Paper](https://arxiv.org/abs/1602.02282) | - |
| Beta-VAE | Beta-VAE: Learning Basic Visual Concepts with a Constrained Variational Framework | [Paper](https://openreview.net/pdf?id=Sy2fzU9gl) | - |
| - | Variational Autoencoder for Deep Learning of Images, Labels, and Captions | [Paper](https://arxiv.org/abs/1609.08976) | - |
| - | Deep Unsupervised Clustering with Gaussian Mixture Variational Autoencoders | [Paper](https://arxiv.org/abs/1611.02648) | - |
| VampPrior | VAE with a VampPrior | [Paper](https://arxiv.org/abs/1705.07120) | - |
| - | Adversarially Regularized Autoencoders | [Paper](https://arxiv.org/abs/1706.04223) | - |
| WAE | Wasserstein Auto-Encoders | [Paper](https://arxiv.org/abs/1711.01558) | - |
| FactorVAE | Disentangling by Factorising | [Paper](https://arxiv.org/abs/1802.05983) | - |
| beta-TCVAE | Isolating Sources of Disentanglement in Variational Autoencoders | [Paper](https://arxiv.org/abs/1802.04942) | - |
| - | Understanding disentangling in beta-VAE | [Paper](https://arxiv.org/abs/1804.03599) | - |
| - | Sliced Wasserstein Auto-Encoders | [Paper](https://arxiv.org/abs/1804.01947) | - |
| IntroVAE | IntroVAE: Introspective Variational Autoencoders for Photographic Image Synthesis | [Paper](https://arxiv.org/abs/1807.06358) | - |
| - | Variational Autoencoder with Implicit Optimal Priors | [Paper](https://arxiv.org/abs/1809.05284) | - |
| - | Cyclical Annealing Schedule: A Simple Approach to Mitigating KL Vanishing | [Paper](https://arxiv.org/abs/1903.10145) | - |
| BIVA | BIVA: A Very Deep Hierarchy of Latent Variables for Generative Modeling | [Paper](https://arxiv.org/abs/1902.02102) | - |
| ControlVAE | ControlVAE: Controllable Variational Autoencoder | [Paper](https://arxiv.org/pdf/2004.05988) | [HuajieShao/ControlVAE-ICML2020](https://github.com/HuajieShao/ControlVAE-ICML2020) |
| DynamicVAE | DynamicVAE: Decoupling Reconstruction Error and Disentangled Representation Learning | [Paper](https://arxiv.org/abs/2009.06795) | - |
| NVAE | NVAE: A Deep Hierarchical Variational Autoencoder | [Paper](https://arxiv.org/abs/2007.03898) | - |
| - | A Contrastive Learning Approach for Training Variational Autoencoder Priors | [Paper](https://arxiv.org/abs/2010.02917) | - |
| - | Very Deep VAEs Generalize Autoregressive Models and Can Outperform Them on Images | [Paper](https://arxiv.org/abs/2011.10650) | - |
| Soft-IntroVAE | Soft-IntroVAE: Analyzing and Improving the Introspective Variational Autoencoder | [Paper](https://arxiv.org/abs/2012.13253) | - |
| - | Automatic Variational Inference with Cascading Flows | [Paper](https://arxiv.org/abs/2102.04801) | - |
| CR-VAE | Consistency Regularization for Variational Auto-Encoders | [Paper](https://arxiv.org/abs/2105.14859) | - |
| LDM | High-Resolution Image Synthesis with Latent Diffusion Models | [Paper](https://arxiv.org/abs/2112.10752) | - |
| ViTok | Learnings from Scaling Visual Tokenizers for Reconstruction and Generation | [Paper](https://arxiv.org/abs/2501.09755) | [Project Page](https://vitok.github.io/) |
| EQ-VAE | EQ-VAE: Equivariance Regularized Latent Space for Improved Generative Image Modeling | [Paper](https://arxiv.org/abs/2502.09509) | [zelaki/eqvae](https://github.com/zelaki/eqvae) |
| DeTok | Latent Denoising Makes Good Visual Tokenizers | [Paper](https://arxiv.org/abs/2507.15856) | [Jiawei-Yang/DeTok](https://github.com/Jiawei-Yang/DeTok) |
| Meissonic | Meissonic: Revitalizing Masked Generative Transformers for Efficient High-Resolution Text-to-Image Synthesis | [Paper](https://arxiv.org/abs/2410.08261) | [viiika/Meissonic](https://github.com/viiika/Meissonic) |
| REPA | Representation Alignment for Generation: Training Diffusion Transformers Is Easier Than You Think | [Paper](https://arxiv.org/abs/2410.06940) | [sihyun-yu/REPA](https://github.com/sihyun-yu/REPA) |

### Quantization / Discrete Foundations

| Alias | Paper | Link | Code / Project |
| --- | --- | --- | --- |
| AQ | Additive Quantization for Extreme Vector Compression | [Paper](https://www.cv-foundation.org/openaccess/content_cvpr_2014/html/Babenko_Additive_Quantization_for_2014_CVPR_paper.html) | - |
| PQ | Product Quantization for Nearest Neighbor Search | - | - |
| RVQ | Approximate Nearest Neighbor Search by Residual Vector Quantization | - | - |
| VQ-VAE | Neural Discrete Representation Learning | - | - |
| VQ-VAE-2 | Generating Diverse High-Fidelity Images with VQ-VAE-2 | [Paper](https://arxiv.org/abs/1906.00446) | - |
| - | Vector Quantization-Based Regularization for Autoencoders | - | - |
| HQ-AE | Hierarchical Quantized Autoencoders | [Paper](https://arxiv.org/abs/2002.08111) | - |
| VQGAN | Taming Transformers for High-Resolution Image Synthesis | [Paper](https://arxiv.org/abs/2012.09841) | [CompVis/taming-transformers](https://github.com/CompVis/taming-transformers) |
| - | Vector-quantized Image Modeling with Improved VQGAN | [Paper](https://arxiv.org/abs/2110.04627) | - |
| VQ-Diffusion | Vector Quantized Diffusion Model for Text-to-Image Synthesis | [Paper](https://arxiv.org/abs/2111.14822) | - |
| MaskGIT | MaskGIT: Masked Generative Image Transformer | [Paper](https://arxiv.org/abs/2202.04200) | - |
| RQ-VAE | Autoregressive Image Generation using Residual Quantization | [Paper](https://arxiv.org/abs/2203.01941) | - |
| SQ-VAE | SQ-VAE: Variational Bayes on Discrete Representation with Self-annealed Stochastic Quantization | [Paper](https://arxiv.org/abs/2205.07547) | - |
| MoVQ | MoVQ: Modulating Quantized Vectors for High-Fidelity Image Generation | [Paper](https://arxiv.org/abs/2209.09002) | - |
| MAGVIT | MAGVIT: Masked Generative Video Transformer | [Paper](https://arxiv.org/abs/2212.05199) | [Project Page](https://magvit.cs.cmu.edu/) |
| - | All in Tokens: Unifying Output Space of Visual Tasks via Soft Token | [Paper](https://arxiv.org/abs/2301.02229) | - |
| - | Designing a Better Asymmetric VQGAN for StableDiffusion | [Paper](https://arxiv.org/abs/2306.04632) | - |
| - | Online Clustered Codebook | [Paper](https://arxiv.org/abs/2307.15139) | - |
| FSQ | Finite Scalar Quantization: VQ-VAE Made Simple | [Paper](https://arxiv.org/abs/2309.15505) | - |
| - | Soft Convex Quantization: Revisiting Vector Quantization with Convex Optimization | [Paper](https://arxiv.org/abs/2310.03004) | - |
| Efficient-VQGAN | Efficient-VQGAN: Towards High-Resolution Image Generation with Efficient Vision Transformers | [Paper](https://arxiv.org/abs/2310.05400) | - |
| SEED-Voken | Language Model Beats Diffusion -- Tokenizer is Key to Visual Generation | [Paper](https://arxiv.org/abs/2310.05737) | [TencentARC/SEED-Voken](https://github.com/TencentARC/SEED-Voken) |
| HQ-VAE | HQ-VAE: Hierarchical Discrete Representation Learning with Variational Bayes | [Paper](https://arxiv.org/abs/2401.00365) | - |
| VAR | Visual Autoregressive Modeling: Scalable Image Generation via Next-Scale Prediction | [Paper](https://arxiv.org/abs/2404.02905) | - |
| LG-VQ | LG-VQ: Language-Guided Codebook Learning | [Paper](https://arxiv.org/abs/2405.14206) | - |
| LlamaGen | Autoregressive Model Beats Diffusion: Llama for Scalable Image Generation | [Paper](https://arxiv.org/abs/2406.06525) | - |
| BSQ | Image and Video Tokenization with Binary Spherical Quantization | [Paper](https://arxiv.org/abs/2406.07548) | - |
| - | Scaling the Codebook Size of VQGAN to 100,000 with a Utilization Rate of 99% | [Paper](https://arxiv.org/abs/2406.11837) | - |
| Open-MAGVIT2 | Open-MAGVIT2: An Open-Source Project Toward Democratizing Auto-regressive Visual Generation | [Paper](https://arxiv.org/abs/2409.04410) | [TencentARC/SEED-Voken](https://github.com/TencentARC/SEED-Voken) |
| IBQ | Scalable Image Tokenization with Index Backpropagation Quantization | [Paper](https://arxiv.org/abs/2412.02692) | [TencentARC/SEED-Voken](https://github.com/TencentARC/SEED-Voken) |
| WeTok | WeTok: Powerful Discrete Tokenization for High-Fidelity Visual Reconstruction | [Paper](https://arxiv.org/abs/2508.05599) | [zhuangshaobin/WeTok](https://github.com/zhuangshaobin/WeTok) |
| - | Scalable Training for Vector-Quantized Networks with 100% Codebook Utilization | [Paper](https://arxiv.org/abs/2509.10140) | - |
| UniWeTok | UniWeTok: An Unified Binary Tokenizer with Codebook Size 2128 for Unified Multimodal Large Language Model | [Paper](https://arxiv.org/abs/2602.14178) | [shallowdream204/BitDance](https://github.com/shallowdream204/BitDance) |

### Compression / Generation-Oriented Tokenizers

| Alias | Paper | Link | Code / Project |
| --- | --- | --- | --- |
| TiTok | An Image is Worth 32 Tokens for Reconstruction and Generation | [Paper](https://arxiv.org/abs/2406.07550) | [bytedance/1d-tokenizer](https://github.com/bytedance/1d-tokenizer) |
| DCAE | Deep Compression Autoencoder for Efficient High-Resolution Diffusion Models | [Paper](https://arxiv.org/abs/2410.10733) | [mit-han-lab/efficientvit](https://github.com/mit-han-lab/efficientvit) |
| SoftVQ-VAE | SoftVQ-VAE: Efficient 1-Dimensional Continuous Tokenizer | [Paper](https://arxiv.org/abs/2412.10958) | [Hhhhhhao/continuous_tokenizer](https://github.com/Hhhhhhao/continuous_tokenizer) |
| DC-AE 1.5 | DC-AE 1.5: Accelerating Diffusion Model Convergence with Structured Latent Space | [Paper](https://arxiv.org/abs/2508.00413) | - |
| - | Bit Prioritization in Variational Autoencoders via Progressive Coding | - | - |
| - | Emu: Enhancing Image Generation Models Using Photogenic Needles in a Haystack | - | - |
| ILLUME | Illumine: Illuminating Your LLMs to See, Draw, and Self-Enhance | - | - |
| AliTok | Alitok: Towards Sequence Modeling Alignment between Tokenizer and Autoregressive Model | - | - |
| - | Subobject-level Image Tokenization | [Paper](https://arxiv.org/abs/2402.14327) | - |
| - | Autoregressive Image Generation without Vector Quantization | - | - |
| ImageFolder | ImageFolder: Autoregressive Image Generation with Folded Tokens | [Paper](https://arxiv.org/abs/2410.01756) | [Project Page](https://lxa9867.github.io/works/imagefolder/index.html) |
| Fluid | Fluid: Scaling Autoregressive Text-to-Image Generative Models with Continuous Tokens | [Paper](https://arxiv.org/abs/2410.13863) | - |
| OmniTokenizer | Omnitokenizer: A Joint Image-Video Tokenizer for Visual Generation | [Paper](https://arxiv.org/abs/2406.09399) | - |
| Flextok | Flextok: Resampling Images into 1D Token Sequences of Flexible Length | [Paper](https://arxiv.org/abs/2502.13967) | - |
| DiTo | Diffusion Autoencoders are Scalable Image Tokenizers | [Paper](https://arxiv.org/abs/2501.18593) | [yinboc/dito](https://github.com/yinboc/dito) |
| Diffusability | Improving the Diffusability of Autoencoders | [Paper](https://arxiv.org/abs/2502.14831) | [snap-research/diffusability](https://github.com/snap-research/diffusability) |
| VFMTok | Vision Foundation Models as Effective Visual Tokenizers for Autoregressive Image Generation | [Paper](https://arxiv.org/abs/2507.08441) | [CVMI-Lab/VFMTok](https://github.com/CVMI-Lab/VFMTok) |
| REPA-E | REPA-E: Unlocking VAE for End-to-End Tuning with Latent Diffusion Transformers | [Paper](https://arxiv.org/abs/2504.10483) | [Project Page](https://end2end-diffusion.github.io/) |
| token-opt | Highly Compressed Tokenizer Can Generate Without Training | [Paper](https://arxiv.org/abs/2506.08257) | [lukaslaobeyer/token-opt](https://github.com/lukaslaobeyer/token-opt) |
| - | Enhancing Vector Quantization with Distributional Matching: A Theoretical and Empirical Study | [Paper](https://arxiv.org/abs/2506.15078) | - |

## Unified Tokenizers

### Single Encoder: Enhancing Semantics

| Alias | Paper | Link | Code / Project |
| --- | --- | --- | --- |
| VA-VAE | Reconstruction vs. Generation: Taming Optimization Dilemma in Latent Diffusion Models | [Paper](https://arxiv.org/abs/2501.01423) | [hustvl/LightningDiT](https://github.com/hustvl/LightningDiT) |
| MAETok | Masked Autoencoders Are Effective Tokenizers for Diffusion Models | [Paper](https://arxiv.org/abs/2502.03444) | [Hhhhhhao/continuous_tokenizer](https://github.com/Hhhhhhao/continuous_tokenizer) |
| GigaTok | GigaTok: Scaling Visual Tokenizers to 3 Billion Parameters for Autoregressive Image Generation | [Paper](https://arxiv.org/abs/2504.08736) | [Project Page](https://silentview.github.io/GigaTok/) |
| Ming-Tok | Ming-UniVision: Joint Image Understanding and Generation with a Unified Continuous Tokenizer | [Paper](https://arxiv.org/abs/2510.06590) | [inclusionAI/Ming-UniVision](https://github.com/inclusionAI/Ming-UniVision) |
| RecTok | RecTok: Reconstruction Distillation along Rectified Flow | [Paper](https://arxiv.org/abs/2512.13421) | [Project Page](https://shi-qingyu.github.io/rectok.github.io/) |
| ImageFolder | ImageFolder: Autoregressive Image Generation with Folded Tokens | [Paper](https://arxiv.org/abs/2410.01756) | [Project Page](https://lxa9867.github.io/works/imagefolder/index.html) |
| UniTok | UniTok: A Unified Tokenizer for Visual Generation and Understanding | [Paper](https://arxiv.org/abs/2502.20321) | [FoundationVision/UniTok](https://github.com/FoundationVision/UniTok) |
| AToken | AToken: A Unified Tokenizer for Vision | [Paper](https://arxiv.org/abs/2509.14476) | [apple/ml-atoken](https://github.com/apple/ml-atoken) |
| VTP | Towards Scalable Pre-training of Visual Tokenizers for Generation | [Paper](https://arxiv.org/abs/2512.13687) | [MiniMax-AI/VTP](https://github.com/MiniMax-AI/VTP) |

### Single Encoder: Preserving Semantics

| Alias | Paper | Link | Code / Project |
| --- | --- | --- | --- |
| EMU2 | Generative Multimodal Models are In-Context Learners | [Paper](https://arxiv.org/abs/2312.13286) | [Project Page](https://baaivision.github.io/emu2/) |
| VILA-U | VILA-U: A Unified Foundation Model Integrating Visual Understanding and Generation | [Paper](https://arxiv.org/abs/2409.04429) | [mit-han-lab/vila-u](https://github.com/mit-han-lab/vila-u) |
| QLIP | QLIP: Text-Aligned Visual Tokenization Unifies Auto-Regressive Multimodal Understanding and Generation | [Paper](https://arxiv.org/abs/2502.05178) | [NVlabs/QLIP](https://github.com/NVlabs/QLIP) |
| DualToken | DualToken: Towards Unifying Visual Understanding and Generation with Dual Visual Vocabularies | [Paper](https://arxiv.org/abs/2503.14324) | - |
| TA-Tok | Vision as a Dialect: Unifying Visual Understanding and Generation via Text-Aligned Representations | [Paper](https://arxiv.org/abs/2506.18898) | [Project Page](https://tar.csuhan.com/) |
| VFMTok | Vision Foundation Models as Effective Visual Tokenizers for Autoregressive Image Generation | [Paper](https://arxiv.org/abs/2507.08441) | [CVMI-Lab/VFMTok](https://github.com/CVMI-Lab/VFMTok) |
| UniLiP | UniLiP: Adapting CLIP for Unified Multimodal Understanding, Generation and Editing | [Paper](https://arxiv.org/abs/2507.23278) | - |
| AVFM | Aligning Visual Foundation Encoders to Tokenizers for Diffusion Models | [Paper](https://arxiv.org/abs/2509.25162) | [Project Page](https://aligntok.github.io/) |
| UniFlow | UniFlow: A Unified Pixel Flow Tokenizer for Visual Understanding and Generation | [Paper](https://arxiv.org/abs/2510.10575) | - |
| RAE | Diffusion Transformers with Representation Autoencoders | [Paper](https://arxiv.org/abs/2510.11690) | [Project Page](https://rae-dit.github.io/) |
| VFM-VAE | Vision Foundation Models Can Be Good Tokenizers for Latent Diffusion Models | [Paper](https://arxiv.org/abs/2510.18457) | - |
| DINO-Tok | DINO-Tok: Adapting DINO for Visual Tokenizers | [Paper](https://arxiv.org/abs/2511.20565) | [MKJia/DINO-Tok](https://github.com/MKJia/DINO-Tok) |
| VQRAE | VQRAE: Representation Quantization Autoencoders for Multimodal Understanding, Generation and Reconstruction | [Paper](https://arxiv.org/abs/2511.23386) | - |
| FAE | One Layer Is Enough: Adapting Pretrained Visual Encoders for Image Generation | [Paper](https://arxiv.org/abs/2512.07829) | - |
| UAE | The Prism Hypothesis: Harmonizing Semantic and Pixel Representations via Unified Autoencoding | [Paper](https://arxiv.org/abs/2512.19693) | [WeichenFan/UAE](https://github.com/WeichenFan/UAE) |

### Dual Encoder: Parallel

| Alias | Paper | Link | Code / Project |
| --- | --- | --- | --- |
| MUSE-VL | Muse-VL: Modeling Unified VLM through Semantic Discrete Encoding | [Paper](https://arxiv.org/abs/2411.17762) | - |
| TokenFlow | TokenFlow: Unified Image Tokenizer for Multimodal Understanding and Generation | [Paper](https://arxiv.org/abs/2412.03069) | [ByteVisionLab/TokenFlow](https://github.com/ByteVisionLab/TokenFlow) |
| TA-TiTok | Democratizing Text-to-Image Masked Generative Models with Compact Text-Aware One-Dimensional Tokens | [Paper](https://arxiv.org/abs/2501.07730) | [bytedance/1d-tokenizer](https://github.com/bytedance/1d-tokenizer) |
| ILLUME+ | ILLUME+: Illuminating Unified MLLM with Dual Visual Tokenization and Diffusion Refinement | [Paper](https://arxiv.org/abs/2504.01934) | [illume-unified-mllm/ILLUME_plus](https://github.com/illume-unified-mllm/ILLUME_plus) |
| UniToken | UniToken: Harmonizing Multimodal Understanding and Generation through Unified Visual Encoding | [Paper](https://arxiv.org/abs/2504.04423) | - |
| SemHiTok | SemHiTok: A Unified Image Tokenizer via Semantic-Guided Hierarchical Codebook for Multimodal Understanding and Generation | [Paper](https://arxiv.org/abs/2503.06764) | - |
| MANZANO | MANZANO: A Simple and Scalable Unified Multimodal Model with a Hybrid Vision Tokenizer | [Paper](https://arxiv.org/abs/2509.16197) | - |
| SVGTok | Latent Diffusion Model without Variational Autoencoder | [Paper](https://arxiv.org/abs/2510.15301) | [shiml20/SVG](https://github.com/shiml20/SVG) |

### Dual Encoder: Cascade

| Alias | Paper | Link | Code / Project |
| --- | --- | --- | --- |
| USP | USP: Unified Self-Supervised Pretraining for Image Generation and Understanding | [Paper](https://arxiv.org/abs/2503.06132) | - |
| TokLIP | TokLIP: Marry Visual Tokens to CLIP for Multimodal Comprehension and Generation | [Paper](https://arxiv.org/abs/2505.05422) | [TencentARC/TokLIP](https://github.com/TencentARC/TokLIP) |
| TUNA | TUNA: Taming Unified Visual Representations for Native Unified Multimodal Models | [Paper](https://arxiv.org/abs/2512.02014) | - |
| PS-VAE | Both Semantics and Reconstruction Matter: Making Representation Encoders Ready for Text-to-Image Generation and Editing | [Paper](https://arxiv.org/abs/2512.17909) | [Project Page](https://jshilong.github.io/PS-VAE-PAGE/) |

### Unified Multimodal Systems Using Shared Visual Tokenizers

| Alias | Paper | Link | Code / Project |
| --- | --- | --- | --- |
| Unified-IO 2 | Unified-IO 2: Scaling Autoregressive Multimodal Models with Vision, Language, Audio, and Action | [Paper](https://arxiv.org/abs/2312.17172) | [allenai/unified-io-2](https://github.com/allenai/unified-io-2) |
| Janus | Janus: Decoupling Visual Encoding for Unified Multimodal Understanding and Generation | [Paper](https://arxiv.org/abs/2410.13848) | [deepseek-ai/Janus](https://github.com/deepseek-ai/Janus) |
| Janus-Pro | Janus-Pro: Unified Multimodal Understanding and Generation with Data and Model Scaling | [Paper](https://arxiv.org/abs/2501.17811) | [deepseek-ai/Janus](https://github.com/deepseek-ai/Janus) |
| JanusFlow | JanusFlow: Harmonizing Autoregression and Rectified Flow for Unified Multimodal Understanding and Generation | [Paper](https://arxiv.org/abs/2411.07975) | [deepseek-ai/Janus](https://github.com/deepseek-ai/Janus) |
| - | Unified Autoregressive Visual Generation and Understanding with Continuous Tokens | [Paper](https://arxiv.org/abs/2503.13436) | - |
| BAGEL | Emerging Properties in Unified Multimodal Pretraining | [Paper](https://arxiv.org/abs/2505.14683) | [bytedance-seed/BAGEL](https://github.com/bytedance-seed/BAGEL) |
| EMMA | EMMA: Efficient Multimodal Understanding, Generation, and Editing with a Unified Architecture | [Paper](https://arxiv.org/abs/2512.04810) | [umm-emma/emma](https://github.com/umm-emma/emma) |
| OpenVision 3 | OpenVision 3: A Family of Unified Visual Encoder for Both Understanding and Generation | [Paper](https://arxiv.org/abs/2601.15369) | - |
| VTok | VTok: A Unified Video Tokenizer with Decoupled Spatial-Temporal Latents | [Paper](https://arxiv.org/abs/2602.04202) | [wangf3014/VTok](https://github.com/wangf3014/VTok) |
| OneVision-Encoder | OneVision-Encoder: Codec-Aligned Sparsity as a Foundational Principle for Multimodal Intelligence | [Paper](https://arxiv.org/abs/2602.08683) | [EvolvingLMMs-Lab/OneVision-Encoder](https://github.com/EvolvingLMMs-Lab/OneVision-Encoder) |
| HUVR | Implicit Neural Representation Facilitates Unified Universal Vision Encoding | [Paper](https://arxiv.org/abs/2601.14256) | [tiktok/huvr](https://github.com/tiktok/huvr) |
