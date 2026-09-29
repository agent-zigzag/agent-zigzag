# Hi, I'm Nate,

**Generative AI & Agentic AI Engineer | PhD in Electrical and Computer Engineering**

I build generative and multimodal AI systems, from research prototypes to production deployments. My work spans **video diffusion**, **controllable image generation**, **vision-language models**, **3D generation**, and **synthetic data**, with an emphasis on efficient training, fine-tuning, and real-world deployment.

I am currently a **Machine Learning Engineer at Turing**, where I develop **LangChain-based deep research agents** and evaluate long-horizon agentic systems. Previously, as a Computer Vision Engineer at [Path Robotics](https://www.path-robotics.com/), I built and deployed multimodal foundation models for robotic welding.

## What I Work On

- **Generative AI:** video diffusion models, Diffusion Transformers (DiT), Stable Diffusion, ControlNet, image/video/3D generation, synthetic data generation, and 3D morphable models such as FLAME
- **Agentic AI & LangChain:** deep research agents grounded in scientific literature, agent trajectory analysis, benchmark quality evaluation, and long-horizon software engineering agents
- **Efficient adaptation:** LoRA, QLoRA, PEFT, and Direct Preference Optimization (DPO) for generative and multimodal models
- **Multimodal & Physical AI:** vision-language models, masked multimodal modeling, 3D perception, point-cloud processing, and edge deployment for robotics
- **Scalable training:** PyTorch, Hugging Face, DDP, FSDP, DeepSpeed, NCCL, multi-node GPU training, SLURM, AWS, and Weights & Biases

## Agentic AI Experience

At Turing, I designed a **LangChain-based deep research agent** that grounds benchmark review in authoritative scientific literature. The agent helps identify ambiguous prompts, instruction-test misalignment, incomplete test coverage, and ungrounded auto-generated tasks.

I have also reviewed **200+ agentic benchmark tasks** across science, machine learning, and software engineering through task inspection, agent trajectory analysis, and loss pattern analysis. I am contributing to the design of a new benchmark for evaluating AI agents on extended, multi-step software engineering tasks.

## Selected Generative & Multimodal AI Work

| Project | Contribution | Links |
|---|---|---|
| **Loki** | Video diffusion for controllable portrait animation using FLAME representations. Enables cross-identity reenactment without cross-ID training data while using 43% fewer parameters and 1,496x less training video than the leading baseline. Trained on 8x H200 GPUs. *Submitted to NeurIPS 2026.* | - |
| **KnobGen** | Dual-pathway diffusion framework for sketch-to-image generation with adjustable control over output sophistication, supporting both novice and expert sketches. *CVPR Workshops 2025.* | [Paper](https://arxiv.org/abs/2410.01595) / [Code](https://github.com/aminK8/KnobGen) |
| **SeamCam** | Applied DPO fine-tuning to diffusion-based inpainting for camouflage generation and helped introduce a visual detectability metric with 78.82% agreement with human judgments. *Under review at ECCV 2026.* | - |
| **LLaVA-LE** | Fine-tuned LLaVA for lunar surface characterization through two-stage instruction tuning, achieving a 3.3x performance gain; helped curate 96k images and 81k question-answer pairs from NASA archives. *CVPR Workshops 2026.* | [Project](https://osupcvlab.github.io/LLaVA-LE/) / [Code](https://github.com/OSUPCVLab/LLaVA-LE) |
| **SegFormer3D** | Lightweight hierarchical transformer for 3D medical-image segmentation, delivering competitive accuracy with 33x fewer parameters and 13x lower compute. *CVPR Workshops 2024.* | [Paper](https://openaccess.thecvf.com/content/CVPR2024W/DEF-AI-MIA/html/Perera_SegFormer3D_An_Efficient_Transformer_for_3D_Medical_Image_Segmentation_CVPRW_2024_paper.html) / [Code](https://github.com/OSUPCVLab/SegFormer3D) |

## Production AI at Path Robotics

- Architected and trained an approximately **800M-parameter multimodal foundation model** on paired point-cloud and image data across multi-node GPU clusters, consolidating five customer-specific models into one model with **96% classification accuracy**
- Adapted the foundation model to new customers using **LoRA/QLoRA** and task-specific heads without full retraining
- Quantized the model to **INT8**, reducing its memory footprint by approximately **4x** and enabling real-time inference on NVIDIA Jetson devices

## Education

- **PhD, Electrical and Computer Engineering** - The Ohio State University, 2025
- **Research focus:** 3D perception, diffusion-based generative modeling, and multimodal learning
- **Dissertation:** *Distribution-Aware Learning for Sparsely Labeled and Imbalanced Spatiotemporal Data*

---

[![Website](https://img.shields.io/badge/Website-bnavard.github.io-blue)](https://bnavard.github.io/)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-Profile-4285F4)](https://scholar.google.com/citations?user=Zlac41oAAAAJ&hl=en)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2)](https://www.linkedin.com/in/pouyan-boreshnavard/)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-pnavard-FFD21E)](https://huggingface.co/pnavard)
