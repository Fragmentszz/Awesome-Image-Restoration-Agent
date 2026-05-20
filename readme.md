# Awesome Agent for Low-level Vision
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![Stars](https://img.shields.io/github/stars/njulj/Awesome-Image-Restoration-Agent?style=social)
![Forks](https://img.shields.io/github/forks/njulj/Awesome-Image-Restoration-Agent?style=social)
![Update](https://img.shields.io/github/last-commit/njulj/Awesome-Image-Restoration-Agent)

A curated list of awesome papers, codes, and resources exploring the intersection of **Autonomous Agents / (M)LLM Agents** for **Low-level Vision** and some related works.

*This repository is maintained by [Lixin Wang]( 2059559391@qq.com) and [Jie Liu]( https://njulj.github.io/), feel free to contact us if you have any questions.*

## 📑 Table of Contents
- [Awesome Agent for Low-level Vision](#awesome-agent-for-low-level-vision)
  - [📑 Table of Contents](#-table-of-contents)
  - [💡 Introduction](#-introduction)
  - [📝 Paper List](#-paper-list)
    - [Image Restoration](#image-restoration)
    - [Image Editing](#image-editing)
    - [Image Super-Resolution](#image-super-resolution)
    - [Video Restoration](#video-restoration)
    - [Computational Photography](#computational-photography)
    - [Image Retouching](#image-retouching)
    - [Image Quality Assessment (IQA)](#image-quality-assessment)
  - [🤝 Contributing](#-contributing)
  - [📄 License](#-license)

## 💡 Introduction
Image restoration and super-resolution have witnessed significant advancements with the introduction of generative models. Recently, the integration of **Autonomous Agents** and **Multi-Agent Systems (MAS)** has opened new paradigms for solving complex, real-world image degradation problems by leveraging planning, tool use, and interactive collaboration. This repository tracks the latest progress in this emerging field.

## 📝 Paper List
### Image Restoration
|Year<div style="width:20px">|Pub<div style="width:60px">|Title<div style="width:550px">|Links<div style="width:100px">|Main Institution<div style="width:100px">|
|:---:|:----:|:----:|:----:|:----:|
|2026|IJCV|**Multi-Agent Image Restoration**|\[[paper](https://arxiv.org/pdf/2503.09403)\]\[[project page](https://villa.jianzhang.tech/publication/200604/)\]|PKU|
|2026|CVPR|**Hybrid Agents for Image Restoration**|\[[paper](https://arxiv.org/pdf/2503.10120)\]|USTC|
|2026|ArXiv|**Derain-Agent**: A Plug-and-Play Agent Framework for Rainy Image Restoration|\[[paper](https://arxiv.org/pdf/2603.11866)\]|HIT|
|2026|CVPR|**FAPE-IR**: Frequency-Aware Planning and Execution Framework for All-in-One Image Restoration|\[[paper](https://arxiv.org/abs/2511.14099)\]\[[code](https://github.com/Programmergg/FAPE-IR/tree/main)\]|TJU|
|2026|CVPR|**EpiAgent**: An Agent-Centric System for Ancient Inscription Restoration|\[[paper](https://arxiv.org/pdf/2604.09367)\]\[[code](https://github.com/blackprotoss/EpiAgent)\]|SEU|
|2026|ArXiv|**TIR-AGENT:** Training an Explorative and Efficient Agent for Image Restoration|\[[paper](https://arxiv.org/pdf/2603.27742)\]|THU|
|2026|TIP|**IAMAgent:** Toward an Interactive and Adaptive Multi-Agent System for Image Restoration|\[[paper](https://ieeexplore.ieee.org/document/11433514)\]|HFUT|
|2026|Journal of Integration Technology|From specialized models to agentic systems: progress and challenges of agents in image restoration|\[[paper](https://jcjs.siat.ac.cn/article/doi/10.12146/j.issn.2095-3135.20251115001)\]|suat|
|2025|ICLR|**AgenticIR:** An Intelligent Agentic System for Complex Image Restoration Problems|\[[paper](https://arxiv.org/abs/2410.17809)\]\[[project page](https://kaiwen-zhu.github.io/research/agenticir)\]\[[code](https://github.com/Kaiwen-Zhu/AgenticIR)\]|SJTU|
|2025|ArXiV|**Q-Agent**: Quality-Driven Chain-of-Thought Image Restoration Agent through Robust Multimodal Large Language Model|\[[paper](https://arxiv.org/abs/2504.07148))\]|SJTU|
|2025|ArXiV|**SimpleCall**: A Lightweight Image Restoration Agent in Label-Free Environments with MLLM Perceptual Feedback|\[[paper](https://arxiv.org/html/2512.18599v1))\]|Amazon|
|2025|CVPR|**JarvisIR**: Elevating Autonomous Driving Perception with Intelligent Image Restoration|\[[paper](https://arxiv.org/abs/2504.04158))\]\[[code](https://github.com/LYL1015/JarvisIR)\]|XMU|
|2024|NIPS|**RestoreAgent:** Autonomous Image Restoration Agent via Multimodal Large Language Models|\[[paper](https://neurips.cc/virtual/2024/poster/93068#:~:text=RestoreAgent)\]\[[project page](https://haoyuchen.com/RestoreAgent)\]|HKUST(GZ)|
> **Note:** Institutions are abbreviated for table formatting (e.g., SJTU for Shanghai Jiao Tong University, PKU for Peking University).
### Image Editing
|Year<div style="width:20px">|Pub<div style="width:60px">|Title<div style="width:550px">|Links<div style="width:100px">|Main Institution<div style="width:100px">|
|:---:|:----:|:----:|:----:|:----:|
|2025|NeurIPS|**CREA**:A Collaborative Multi-Agent Framework for Creative Image Editing and Generation|\[[paper](https://arxiv.org/pdf/2504.05306)\]\[[project page](https://crea-diffusion.github.io/)\]|Virginia Tech|
|2026|ArXiv|**Agent Banana**: High-Fidelity Image Editing with Agentic Thinking and Tooling|\[[paper](https://arxiv.org/pdf/2602.09084)\]\[[project page](https://agent-banana.github.io/)\]\[[code](https://github.com/taco-group/agent-banana)\]|TAMU|
|2026|ArXiv|**PhotoAgent**: Agentic Photo Editing with Exploratory Visual Aesthetic Planning|\[[paper](https://arxiv.org/abs/2602.22809)\]\[[project page](https://mdyao.github.io/PhotoAgent/)\]\[[code](https://github.com/mdyao/PhotoAgent)\]|MMLab, CUHK|
|2026|ArXiv|**ImageEdit-R1**: Boosting Multi-Agent Image Editing via Reinforcement Learning|\[[paper](https://arxiv.org/abs/2603.08059v1)\]\[[code](https://github.com/zhaoyiran924/ImageEdit-R1)\]|NTU, Adobe|
|2026|ArXiv|**EditRefiner**: A Human-Aligned Agentic Framework for Image Editing Refinement|\[[paper](https://arxiv.org/abs/2605.07457v1)\]\[[code](https://github.com/IntMeGroup/EditRefiner)\]|SJU, Vivo|


### Image Super-Resolution
|Year<div style="width:20px">|Pub<div style="width:60px">|Title<div style="width:550px">|Links<div style="width:100px">|Main Institution<div style="width:100px">|
|:---:|:----:|:----:|:----:|:----:|
|2025|NIPS|**4KAgent**: Agentic Any Image to 4K Super-Resolution|\[[paper](https://arxiv.org/pdf/2507.07105)\]\[[project page](https://4kagent.github.io/)\]\[[code](https://github.com/taco-group/4KAgent)\]|TAMU|


### Video Restoration
|Year<div style="width:20px">|Pub<div style="width:60px">|Title<div style="width:550px">|Links<div style="width:100px">|Main Institution<div style="width:100px">|
|:---:|:----:|:----:|:----:|:----:|
|2026|ArXiv|**VQ-Jarvis**: Retrieval-Augmented Video Restoration Agent with Sharp Vision and Fast Thought|\[[paper](https://arxiv.org/pdf/2603.22998)\]|PKU|

### Computational Photography
|Year<div style="width:20px">|Pub<div style="width:60px">|Title<div style="width:550px">|Links<div style="width:100px">|Main Institution<div style="width:100px">|
|:---:|:----:|:----:|:----:|:----:|
|2026|ArXiv|**PhotoAgent**: A Robotic Photographer with Spatial and Aesthetic Understanding|\[[paper](https://arxiv.org/abs/2603.22796)\]|THU|

### Image Retouching
|Year<div style="width:20px">|Pub<div style="width:60px">|Title<div style="width:550px">|Links<div style="width:100px">|Main Institution<div style="width:100px">|
|:---:|:----:|:----:|:----:|:----:|
|2026|AAAI|**PerTouch**: VLM-Driven Agent for Personalized and Semantic Image Retouching|\[[paper](https://arxiv.org/pdf/2511.12998)\]\[[project page](https://auroral703.github.io/PerTouch/)\]\[[code](https://github.com/Auroral703/PerTouch)\]|NKU|
|2025|Arxiv|**Position**: Agentic Systems Constitute a Key Component of Next-Generation Intelligent Image Processing|\[[paper](https://arxiv.org/pdf/2505.16007v1)\]|INSAIT|


### Image Quality Assessment
|Year<div style="width:20px">|Pub<div style="width:60px">|Title<div style="width:550px">|Links<div style="width:100px">|Main Institution<div style="width:100px">|
|:---:|:----:|:----:|:----:|:----:|
|2026|ArXiv|**ME-IQA**: Memory-Enhanced Image Quality Assessment via Re-Ranking|\[[paper](https://arxiv.org/abs/2603.20785)\]|CityU|
|2026|ArXiv|**Q-Probe**: Scaling Image Quality Assessment to High Resolution via Context-Aware Agentic Probing|\[[paper](https://arxiv.org/abs/2601.15356)\]|USTC|
|2025|ArXiv|**AgenticIQA**: An Agentic Framework for Adaptive and Interpretable Image Quality Assessment|\[[paper](https://arxiv.org/abs/2509.26006)\]|NTU|
|2025|ACL|**CIGEval**: A Unified Agentic Framework for Evaluating Conditional Image Generation|\[[paper](https://arxiv.org/abs/2504.07046)\]\[[code](https://github.com/HITsz-TMG/Agentic-CIGEval)\]|HITsz|
|2025|ACL|**Evaluation Agent**: Efficient and Promptable Evaluation Framework for Visual Generative Models|\[[paper](https://arxiv.org/abs/2412.09645)\]\[[code](https://github.com/Vchitect/Evaluation-Agent)\]|Shanghai AI Lab|

## 🤝 Contributing
Welcome to contribute! If you find any awesome papers or projects that are not on the list, please feel free to open a Pull Request or Issue. 
1. Follow the exact format of the existing table entries.
2. Ensure the link to the paper is working.
3. If there is open-source code, please include the `[code]` link.

## 📄 License
This project is licensed under the [MIT License](LICENSE).
