<div align="center">

# Neural Coding Is Not Always Semantic  
### *Toward the Standardized Coding Workflow in Semantic Communications*

[![arXiv](https://img.shields.io/badge/arXiv-2505.18637-b31b1b.svg)](https://arxiv.org/pdf/2505.18637) 
[![IEEE](https://img.shields.io/badge/IEEE-COMSTD%202025-blue.svg)](https://ieeexplore.ieee.org/document/11145020) 
[![Project Page](https://img.shields.io/badge/Project-Page-green.svg)](https://qin-jingyun.github.io/SemCod) 
[![Email](https://img.shields.io/badge/Contact-Email-red.svg)](mailto:hailong.qin@bupt.edu.cn)

[Hai-Long Qin](https://scholar.google.com/citations?user=N33wbdEAAAAJ)¹, [Jincheng Dai](https://scholar.google.com/citations?user=0I_YtFsAAAAJ)¹†, [Sixian Wang](https://scholar.google.com/citations?user=f9s8H6UAAAAJ)¹, [Xiaoqi Qin](https://scholar.google.com/citations?user=mrEeosAAAAAJ)¹,  
[Shuo Shao](https://ieeexplore.ieee.org/author/37086424888)², [Kai Niu](https://scholar.google.com/citations?user=Dm9tNxoAAAAJ)¹, [Wenjun Xu](https://scholar.google.com/citations?user=NC-ZeKAAAAAJ)¹, [Ping Zhang](https://ieeexplore.ieee.org/author/37274503400)¹†

¹ Beijing University of Posts and Telecommunications (BUPT)  
² University of Shanghai for Science and Technology (USST)  
† Corresponding Authors

***Accepted by IEEE Communications Standards Magazine (COMSTD), 2025***

</div>

##
<p align="center">
  <img src="./images/semcod.svg" alt="Teaser" style="max-width: 100%; height: auto;">
</p>

## 🚀 TL;DR

<p align="justify" style="text-align: justify;">
We establish a <b>standardized coding workflow</b> for semantic communication that moves beyond transmitting deep features and instead conveys compact, context-aware general semantic representations through:
</p>

- **📝 Tokenization**: Breaking data into embedded tokens  
- **🔄 Reorganization**: Merging semantically similar tokens based on contextual similarity  
- **⚡ Quantization**: Optional mapping to discrete codes approaching "one code, one concept"

<p align="justify" style="text-align: justify;">
Our method uses just <b>10–30 semantic tokens</b> to achieve better reconstruction quality (lower FID) and higher fidelity (higher PSNR) than traditional neural coding, especially at low data rates.
</p>

## 📖 Citation

If you find this work useful, please cite:

```bibtex
@article{qin2025semcod,
  author  = {H. L. Qin and J. Dai and S. Wang and X. Qin and S. Shao and K. Niu and W. Xu and P. Zhang},
  title   = {Neural Coding Is Not Always Semantic: Toward the Standardized Coding Workflow in Semantic Communications},
  journal = {IEEE Commun. Stand. Mag.},
  volume  = {9},
  number  = {4},
  pages   = {24--33},
  year    = {2025}
}
