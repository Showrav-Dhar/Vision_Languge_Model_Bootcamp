# Vision-Language Bootcamp

Repository contains resources, notebooks, and implementation patterns from the Vision Language Bootcamp. This project focuses on the operating principles, training dynamics, and practical application of modern vision-language systems.

## Core Modules

### 1. Contrastive Vision-Language Pretraining (CLIP)
Implementation of CLIP-style models focusing on text–image embedding alignment.
* **Mechanics:** Text and image encoders projecting to a shared latent space.
* **Retrieval:** Cosine-similarity based search between modalities.
* **Workflows:** Zero-shot image classification without explicit labels.

### 2. Instruction-Tuned Vision-Language Models
Prompting of Large Vision Multimodal Models, specifically **Qwen 2.5-VL (3B)**.
* **Architecture:** Understanding multimodal reasoning capabilities.
* **Prompt Engineering:** Implementing role-formatted prompting (System, User, Assistant) and chat templates.
* **Infrastructure:** Cloud GPU setup for inference and execution.

### 3. Multimodal Inference Pipelines
End to end pipelines for processing visual inputs.
* **Captioning:** Multi image context generation.
* **Detection:** Zero-shot object detection utilizing VLM semantic reasoning (bypassing task-specific training).
* **Analysis:** Interpreting spatial and semantic reasoning outputs.

## Tech Stack

* **Language:** Python
* **Models:** Qwen 2.5-VL, CLIP variants
* **Compute:** CUDA enabled GPU Inference, Kaggle
