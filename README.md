# Toward Socially Aware Vision-Language Models: Evaluating Cultural Competence Through Multimodal Story Generation

<div align="center">
<!-- Badges -->
<a href="https://arxiv.org/abs/2508.16762">
    <img src="https://img.shields.io/badge/arXiv-2508.16762-B31B1B?style=for-the-badge&logo=arxiv&logoColor=white" alt="arXiv">
</a>
<a href="https://huggingface.co/datasets/ArkaMukherjee/mmCultural">
    <img src="https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Dataset-yellow?style=for-the-badge" alt="Hugging Face Dataset">
</a>
<a href="#license">
    <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
</a>
<!-- Visual Abstract or Key Figure -->
  
<img src="assets/framework_overview.png" alt="Framework Overview" width="800px">
  <p><em>The first systematic evaluation of cultural competence in Vision-Language Models through multimodal story generation across 42 countries and 5 contemporary VLMs.</em></p>
</div>

## 🎯 Abstract

As Vision-Language Models (VLMs) achieve widespread deployment across diverse cultural contexts, ensuring their cultural competence becomes critical for responsible AI systems. We present the first comprehensive evaluation of VLM cultural competence through multimodal story generation, developing a novel framework that evaluates 5 contemporary VLMs across 42 countries.
Our analysis reveals significant cultural adaptation capabilities with rich culturally-specific vocabulary, but also concerning limitations: dramatic performance variance across architectures, inverse cultural alignment in some models, and architectural bias in automated metrics contradicting human assessments.

## 🗃️ Dataset
Our mmCultural dataset contains:

- 1,470 unique prompts spanning diverse cultural concepts
- 42 countries across 5 continents
- 35 cultural concepts (honesty, empathy, cooperation, etc.)
- Culturally-relevant images for each prompt
- 73,500 generated stories from 5 VLMs
- Human evaluation scores across 10 cultural competence dimensions

<div align="center">
<a href="https://huggingface.co/datasets/ArkaMukherjee/mmCultural">
    <img src="https://img.shields.io/badge/🤗%20Access%20Dataset-mmCultural-yellow?style=for-the-badge&logo=huggingface&logoColor=white" alt="Access Dataset">
</a>
</div>

## 🙏 Acknowledgments

- SPARC (Scheme for Promotion of Academic and Research Collaboration) Phase-III (Project ID: 3385)
- NVIDIA for providing Blackwell GPUs that made these experiments possible

<div align="center">
<p>Built with ❤️ for responsible AI and cultural inclusivity</p>
<a href="https://kiit.ac.in/">KIIT University</a> • <a href="https://www.iitbbs.ac.in/">IIT Bhubaneswar</a>
</div>
