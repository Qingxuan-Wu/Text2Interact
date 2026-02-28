# Text2Interact
Text2Interact: High-Fidelity and Diverse Text-to-Two-Person Interaction Generation (ICLR 2026)

## Introduction
Official GitHub repository of the paper [Text2Interact: High-Fidelity and Diverse Text-to-Two-Person Interaction Generation](https://arxiv.org/abs/2510.06504).

**Code Coming Soon!**

[[Project Page]](https://people.csail.mit.edu/frankzydou/projects/Text2Interact/index.html) [[Paper]](https://arxiv.org/pdf/2510.06504) [[Video]](https://www.youtube.com/watch?v=TNehUyASQlY)

<img width="3900" height="1800" alt="image" src="https://github.com/user-attachments/assets/4e00c924-95a4-4342-9382-de196a20a123" />

## Abstract
Generating realistic and diverse human-human interactions from text remains a fundamental but challenging problem in vision, graphics, and robotics. Current approaches face two main limitations: (i) interaction synthesis requires both high-quality individual motion and precise spatiotemporal coordination, yet existing datasets are too small to support such complexity, limiting generalization; and (ii) complex interactions often demand detailed textual descriptions, but sentence-level embeddings fail to capture fine-grained semantics. We address these issues with two contributions. First, we introduce InterCompose, a scalable data synthesis framework that combines the general knowledge of large language models with strong single-person motion priors to generate high-quality two-person interactions beyond existing distributions. Second, we propose Text2Interact, which employs word-level attention for fine-grained text-motion alignment and an adaptive supervision signal that dynamically weights body parts based on interaction context to enhance realism. Extensive experiments demonstrate that our approach substantially improves motion diversity, semantic alignment, and realism over state-of-the-art baselines. Our code and models will be released for reproducibility.

## Citation
```
@article{wu2026text2interact,
    title={Text2interact: High-fidelity and diverse text-to-two-person interaction generation},
    author={Wu, Qingxuan and Dou, Zhiyang and Guo, Chuan and Huang, Yiming and Feng, Qiao and Zhou, Bing and Wang, Jian and Liu, Lingjie},
    journal={ICLR 2026},
    year={2026}
}
```
