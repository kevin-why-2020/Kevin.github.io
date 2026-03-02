---
title: "Decouple, Reorganize, and Fuse: A Multimodal Framework for Cancer Survival Prediction"
category: manuscripts
permalink: /publication/2025-05-29-paper-DeReF
excerpt: '
2025-08-27 ⭐: Initial release of DeReF model on arxiv preprint
2026-02-23 ⭐: Congratulations! 🎉🎊🎉 DeReF has been accepted by TMI 2026 (IF=9.8) 🎯 <br>
This paper proposed a Random Feature Reorganization and a Regional Cross-Attention Algorithms in Multimodal Cancer Survival Analysis. 
![Model Framework Figure](../images/DeReF.png)'
date: 2026-02-23
paperurl: '../files/TMI_DeReF.pdf'
citation: '@ARTICLE{DeReF,
  author={Wang, Huayi and Ying, Haochao and Xu, Yuyang and Qiu, Qibo and Zhang, Cheng and Chen, Danny Z. and Sun, Ying and Wu, Jian},
  journal={IEEE Transactions on Medical Imaging}, 
  title={Decouple, Reorganize, and Fuse: A Multimodal Framework for Cancer Survival Prediction}, 
  year={2026},
  keywords={Cancer survival prediction;Modal decoupling;Multimodal fusion;Mixture-of-Experts},
  doi={10.1109/TMI.2026.3668773},
  ISSN={1558-254X}}'
---

ABSTRACT
Cancer survival analysis commonly integrates information across diverse medical modalities to make survival-time predictions. Existing methods primarily focus on extracting different decoupled features of modalities and performing fusion operations such as concatenation, attention, and Mixture-of-Experts (MoE)-based fusion. However, these methods still face two key challenges: i) fixed fusion schemes (concatenation and attention) can lead to model over-reliance on predefined feature combinations, limiting the dynamic fusion of decoupled features; ii) in MoE-based fusion methods, each expert network handles separate decoupled features, which limits information interaction among the decoupled features. To address these challenges, we propose a novel Decoupling-Reorganization-Fusion framework (DeReF), which devises a random feature reorganization strategy between modalities decoupling and dynamic MoE fusion modules. Its advantages are: i) it increases the diversity of feature combinations and granularity, enhancing the generalization ability of the subsequent expert networks; ii) it overcomes the problem of information closure and helps expert networks better capture information among decoupled features. Additionally, we incorporate a regional cross-attention network within the modality decoupling module to improve the representation quality of decoupled features. Extensive experimental results on our in-house Liver Cancer (LC) and three widely used public datasets from The Cancer Genome Atlas (TCGA) confirm the effectiveness of our proposed method. Codes are available at https://github.com/ZJUMAI/DeReF.
