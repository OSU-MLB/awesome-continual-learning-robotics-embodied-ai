# Continual Learning for Robotics: Paper Collection

<p align="center">
    <img src="assets/robotics_cl.png" width="90%" height="90%">
</p>

A curated collection of research papers on **Continual Learning (CL) for Robotics**, organized by application area and searchable by technique, benchmark, and venue.

📄 **Related Survey**: [A Survey of Continual Learning for Robotics in the Foundation Model Era](https://www.techrxiv.org/doi/full/10.36227/techrxiv.176972367.76460794/v1)

---

## 📢 News & Updates

- **[2026.02.11]**: Initial collection added!

---

## 📋 Table of Contents

- [News & Updates](#-news--updates)
- [How to Use This Repo](#-how-to-use-this-repo)
- [Papers by Application](#-papers-by-application)
  - [Manipulation](#manipulation)
  - [Navigation](#navigation)
  - [Planning](#planning)

---

## 🔍 How to Use This Repo

**Browse by application area**: Start with [Manipulation](#manipulation), [Navigation](#navigation), or [Planning](#planning)

---

## 🧭 Legend

### Setting

- 📦 **Object**
- 🎯 **Goal**
- 🗺️ **Spatial**
- 🌍 **Environment**

### CL Technique (Abbreviations)

- **GR** — Generative Replay  
- **ER** — Experience Replay  
- **R** — Regularization  
- **PI** — Parameter Isolation  
- **PEFT** — PEFT
- **PE** — Parameter Expansion  
- **ME** — Memory Expansion  
- **ML** — Meta-Learning  
- **MoE** — MoE  
- **W** — World Model

---

## 📚 Papers by Application

### Manipulation

| Paper | CL Technique | Setting | Benchmark | Code | Venue |
| :--- | :--- | :--- | :--- | :---: | :---: |
| CRIL [Gao et al., 2021] | GR | 📦🎯 | Meta-World | [💻](https://github.com/HeegerGao/CRIL) | IROS’21 |
| HyperCRL [Huang et al., 2021] | PI | 🎯 / 📦🎯🗺️ | Surreal Robotic Suite, DoorGym | [💻](https://github.com/rvl-lab-utoronto/HyperCRL) | ICRA’21 |
| HN-PPO [Schöpf et al., 2022] | R + PI | 📦🎯🗺️ | DoorGym | [💻](https://github.com/phschoepf/cs-bachelor-thesis) | NeurIPS-W’22 |
| SANER [Powers et al., 2023] | ER + PE | 📦🎯 |  | [💻](https://github.com/AGI-Labs/continual_rl) | CoLLAs’23 |
| CHN [Auddy et al., 2023] | PI | 📦🎯 | LASA | [💻](https://github.com/sayantanauddy/clfd) | RAS’23 |
| CoTASP [Yang et al., 2023] | PEFT + PI | 📦🎯 | Continual World | [💻](https://github.com/stevenyangyj/CoTASP) | ICML’23 |
| SDP [Wang et al., 2025b] | MoE + PE | 📦🎯 | Mimicgen, DexArt, Robomimic | [💻](https://github.com/AnthonyHuo/SDP) | CoRL’24 |
| TAIL [Liu et al., 2024] | PEFT + PE | 📦 / 🎯 / 🗺️ / 📦🎯🗺️ | LIBERO |  | ICLR’24 |
| CompoNet [Malagon et al., 2024] | PE | 📦🎯 | Continual World | [💻](https://github.com/mikelma/componet) | ICML’24 |
| LOTUS [Wan et al., 2024] | ER + PE | 📦 / 🎯 / 📦🎯🗺️ | LIBERO | [💻](https://github.com/UT-Austin-RPL/Lotus) | ICRA’24 |
| ECD [Zhao et al., 2024] | ER + R | 📦🎯 | Continual World |  | ICRA’24 |
| DMPEL [Lei et al., 2025] | PEFT + MoE + ER + PE | 📦 / 🎯 / 🗺️ / 📦🎯🗺️ | LIBERO | [💻](https://github.com/HarryLui98/DMPEL) | ICRA’24 |
| IsCiL [Lee et al., 2024] | PEFT + PE | 📦🎯 | Franka Kitchen, Meta-World | [💻](https://github.com/L2dulgi/IsCiL) | NeurIPS’24 |
| SPECI [Xu and Nie, 2025] | PE | 📦 / 🎯 / 🗺️ / 📦🎯🗺️ | LIBERO | [💻](https://github.com/Triumphant-strain/SPECI) | TCDS’25 |
| PPL [Yao et al., 2025] | PEFT + PE | 🎯 / 📦🎯 | LIBERO, Mimicgen |  | CVPR’25 |
| LEGION [Meng et al., 2025] | ME | 📦🎯 |  | [💻](https://github.com/Ghiara/LEGION) | NMI’25 |
| LLWM [Pan et al., 2025] | GR + W + R | 🎯 / 📦🎯 | Deepmind Control Suite, Meta-World | [💻](https://github.com/WendongZh/continual_visual_control) | ECML’25 |
| iManip [Zheng et al., 2025] | PEFT + ER + PE | 📦🎯 | RLBench |  | ICCV’25 |
| OA [Liu et al., 2025] | W + R | 🎯 / 📦🎯 | Continual Bench | [💻](https://github.com/sail-sg/ContinualBench) | ICML’25 |
| M2Distill [Roy et al., 2025] | R | 📦 / 🎯 / 🗺️ | LIBERO |  | ICRA’25 |
| CKA-RL [Hu et al., 2025] | PE | 🎯 / 📦🎯 | Continual World | [💻](https://github.com/Fhujinwu/CKA-RL) | NeurIPS’25 |
| SIL-C [Lee et al., 2025] | PEFT + ME | 🎯 / 📦🗺️ | Franka Kitchen, Meta-World | [💻](https://github.com/L2dulgi/SIL-C) | NeurIPS’25 |
| Stellar VLA [Wu et al., 2025] | MoE + ER + ME | 🎯 / 📦🎯🗺️ | LIBERO |  | arXiv’25 |
| TOPIC [Song et al., 2025] | PEFT + PE | 📦🎯 | RLBench |  | arXiv’25 |
| ExpReS-VLA [Syed et al., 2025] | ER | 📦 / 🎯 / 🗺️ / 📦🎯🗺️ | LIBERO |  | arXiv’25 |
| OMLA [Zhu et al., 2025] | PEFT + ML | 📦 / 🎯 / 🗺️ | LIBERO |  | arXiv’25 |
| CLARE [Römer et al., 2026] | PE + PEFT | 📦🎯🗺️ | LIBERO | [💻](https://github.com/utiasDSL/clare) | arXiv’26 |

### Navigation

| Paper | CL Technique | Setting | Benchmark | Code | Venue |
| :--- | :--- | :--- | :--- | :---: | :---: |
| CVLN [Jeong et al., 2024] | ER + R | 🌍 | R2R, RxR |  | arXiv’24 |
| VLNCL [Li et al., 2025] | ML + ER | 🌍 | R2R |  | IROS’25 |
| UFA [Yu et al., 2025] | ER + ME | 🌍 | GSA-R2R |  | arXiv’25 |
| TuKA [Anonymous, 2026a] | PEFT + R + PE | 🌍 | Habitat |  | ICLR’26 sub. |
| Uni-Walker [Anonymous, 2026b] | PEFT + R | 🎯 / 🌍 / 🎯🌍 | LENL |  | ICLR’26 sub. |

### Planning

| Paper | CL Technique | Setting | Benchmark | Code | Venue |
| :--- | :--- | :--- | :--- | :---: | :---: |
| TAMP [Mendez-Mendez et al., 2023] | MoE + ER | 📦🎯🌍 | BEHAVIOR |  | CoRL’23 |
| CAMA [Kim et al., 2024] | ER + R | 📦🎯 / 🌍 | CL-ALFRED | [💻](https://github.com/snumprlab/cl-alfred) | ICLR’24 |
| ViReSkill [Kagaya et al., 2025] | ER + ME | 📦 / 🎯 / 🗺️ / 📦🎯🗺️ | LIBERO |  | arXiv’25 |

---

## 🤝 Contributing

We welcome contributions! To add a paper:

1. Fork this repository
2. Add the paper to the appropriate application section(s)
3. Fill in all columns: Paper (with link), CL Technique, Setting, Benchmark, Code (💻 emoji if available), Venue
4. If a paper uses multiple CL techniques, list them with "+" (e.g., "PEFT + MoE + ER")
5. Submit a pull request with a brief description

**Format Example**: 
```
| [Paper Title](paper-link) [Author et al., Year] | Technique(s) | Setting | Benchmark | [💻](code-link) | Venue |
```

---

## 📖 Citation

If you find this collection useful, please consider citing our survey:
```bibtex
@article{Mai_2026,
    title={A Survey of Continual Learning for Robotics in the Foundation Model Era},
    url={http://dx.doi.org/10.36227/techrxiv.176972367.76460794/v2},
    DOI={10.36227/techrxiv.176972367.76460794/v2},
    publisher={Institute of Electrical and Electronics Engineers (IEEE)},
    author={Mai, Zheda and Jeon, Sooyoung and Huang, Zanming and Yoo, Jinsu and Lee, Colin and Zhang, Gengyu and Wang, Haoxuan and Li, Yifan and Kong, Yu and Yan, Yan and Chao, Wei-Lun},
    year={2026},
    month=feb
}
```

---

**Last Updated**: February 2026 | **Paper Count**: 35
