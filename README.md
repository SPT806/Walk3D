<div align="center">

# Walk3D: Walking Through 3D Spaces: Spatial Routing for Referring 3D Gaussian Splatting Segmentation

**NeurIPS 2026**

<!-- 徽标按钮区域 -->
<a href="https://arxiv.org"><img src="https://img.shields.io/badge/Paper-PDF-brightgreen?logo=arXiv" alt="Paper"></a>
<a href="https://github.com/SPT806/Walk3D"><img src="https://img.shields.io/badge/Code-Page-blue?logo=github" alt="Code"></a>

</div>

## Abstract

This paper introduces Walk3D, a novel 3D Gaussian Splatting (3DGS) framework
explicitly designed for 3D referring segmentation, particularly excelling at inter-
preting complex, long-sentence descriptions. Our primary motivation stems from
observing that existing 3DGS-based open-vocabulary methods mainly focus on
simple, category-level object segmentation. These methods struggle to precisely
segment targets described by highly detailed, multi-sentence queries due to weak
compositional language understanding and a lack of structural scene awareness. To
tackle these dense and complex linguistic constraints, we propose a spatial routing
network that decodes these queries into sequential chain-of-thought instructions
upon a scene graph. Specifically, we construct a static supernode graph based on
the geometric and semantic properties of the 3DGS space, where a spatial Graph
Neural Network (GNN) dynamically pathfinds using the decomposed linguistic
chain to accurately segment the referred target. Extensive experiments on complex
3D referring segmentation benchmarks demonstrate the superiority of our proposed
method in interpreting lengthy, multi-conditional queries.
<!-- Teaser 图居中展示 -->
<img src="https://github.com/user-attachments/assets/0367eeee-0e4b-4598-b482-08619e7a2cea" width="95%" alt="Walk3D Teaser">

## 📌 Status
Code and pretrained models are coming soon! Stay tuned.
