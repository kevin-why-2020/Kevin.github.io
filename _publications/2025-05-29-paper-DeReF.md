---
title: "Decouple, Reorganize, and Fuse: A Multimodal Framework for Cancer Survival Prediction"
category: manuscripts
permalink: /publication/2025-05-29-paper-DeReF
excerpt: 'This paper proposed a Random Feature Reorganization and a Regional Cross-Attention Algorithms in Multimodal Cancer Survival Analysis. 
![Editing a markdown file for a talk](/images/why.png)'
date: 2024-11-15
paperurl: 'https://kevin-why-2020/Kevin.github.io/files/TMI_DeReF.pdf'
citation: 'Huayi Wang, et al. (2025). &quot;Decouple, Reorganize, and Fuse: A Multimodal Framework for Cancer Survival Prediction.&quot; <i>Under Review IEEE TRANSACTIONS ON MEDICAL IMAGING（TMI）, IF=8.9</i>.'
---

ABSTRACT
Cancer survival analysis commonly integrates information across diverse medical modalities to make survival-time predictions. Existing methods primarily focus on extracting different decoupled features of modalities and performing fusion operations such as concatenation, attention, and MoE-based (Mixture-of-Experts) fusion. However, these methods still face two key challenges: i) Fixed fusion schemes (concatenation and attention) can lead to model over-reliance on predefined feature combinations, limiting the dynamic fusion of decoupled features; ii) in MoE-based fusion methods, each expert network handles separate decoupled features, which limits information interaction among the decoupled features. To address these challenges, we propose a novel Decoupling-Reorganization-Fusion framework (DeReF), which devises a random feature reorganization strategy between modalities decoupling and dynamic MoE fusion modules. Its advantages are: i) it increases the diversity of feature combinations and granularity, enhancing the generalization ability of the subsequent expert networks; ii) it overcomes the problem of information closure and helps expert networks better capture information among decoupled features. Additionally, we incorporate a regional cross-attention network within the modality decoupling module to improve the representation quality of decoupled features. Extensive experimental results on our in-house Liver Cancer (LC) and three widely used TCGA public datasets confirm the effectiveness of our proposed method. 
The code will be made publicly available.
