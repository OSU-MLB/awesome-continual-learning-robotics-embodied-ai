# Continual Learning for Robotics: Paper Collection

<p align="center">
    <img src="assets/robotics_cl.png" width="90%" height="90%">
</p>

A curated collection of research papers on **Continual Learning (CL) for Robotics and Embodied AI**, organized by application area and searchable by technique, benchmark, and venue.

📄 **Related Survey**: [A Survey of Continual Learning for Robotics in the Foundation Model Era](https://www.techrxiv.org/doi/full/10.36227/techrxiv.176972367.76460794/v1)

---

## 📢 News & Updates

- **[2026.02.04]**: Initial collection with 50+ papers across manipulation, navigation, and planning

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
- **PEFT** — Parameter-Efficient Fine-Tuning  
- **PE** — Parameter Expansion  
- **ME** — Memory Expansion  
- **ML** — Meta-Learning  
- **MoE** — Mixture of Experts  
- **W** — World Model

---

## 📚 Papers by Application

### Manipulation

| Paper | CL Technique | Setting | Benchmark | Code | Venue |
| :--- | :--- | :--- | :--- | :---: | :---: |
| CRIL [Gao et al., 2021] | GR | 📦 Object + 🎯 Goal | Meta-World | [💻](https://github.com/HeegerGao/CRIL) | IROS’21 |
| HyperCRL [Rusu et al., 2021] | PI | 🎯 Goal + 📦 Object + 🗺️ Spatial | Surreal Robotic Suite, DoorGym | [💻](https://github.com/rvl-lab-utoronto/HyperCRL) | ICRA’21 |
| HN-PPO [Schöpflin et al., 2022] | R + PI | 📦 Object + 🎯 Goal + 🗺️ Spatial | DoorGym | [💻](https://github.com/phschoepf/cs-bachelor-thesis) | NeurIPS WS’22 |
| SANER [Wang et al., 2023] | ER + PE | 📦 Object + 🎯 Goal | – | [💻](https://github.com/AGI-Labs/continual_rl) | CoLLAs’23 |
| CHN [Auddy et al., 2023] | PI | 📦 Object + 🎯 Goal | LASA | [💻](https://github.com/sayantanauddy/clfd) | RAS’23 |
| CoTASP [Yang et al., 2023] | PEFT + PI | 📦 Object + 🎯 Goal | Continual World | [💻](https://github.com/stevenyangyj/CoTASP) | ICML’23 |
| SDP [Huo et al., 2024] | MoE + PE | 📦 Object + 🎯 Goal | MimicGen, DexArt, RoboMimic | [💻](https://github.com/AnthonyHuo/SDP) | CoRL’24 |
| TAIL [Zhang et al., 2024] | PEFT + PE | 📦 Object + 🎯 Goal + 🗺️ Spatial | LIBERO |  | ICLR’24 |
| CompoNet [Mendez et al., 2024] | PE | 📦 Object + 🎯 Goal | Continual World | [💻](https://github.com/mikelma/componet) | ICML’24 |
| LOTUS [Xu et al., 2024] | ER + PE | 📦 Object + 🎯 Goal + 🗺️ Spatial | LIBERO | [💻](https://github.com/UT-Austin-RPL/Lotus) | ICRA’24 |
| ECD [Zhao et al., 2024] | ER + R | 📦 Object + 🎯 Goal | Continual World |  | ICRA’24 |
| DMPEL [Lei et al., 2024] | PEFT + MoE + ER + PE | 📦 Object + 🎯 Goal + 🗺️ Spatial | LIBERO | [💻](https://github.com/HarryLui98/DMPEL) | ICRA’24 |
| IsCiL [Lee et al., 2024] | PEFT + PE | 📦 Object + 🎯 Goal | Franka Kitchen, Meta-World | [💻](https://github.com/L2dulgi/IsCiL) | NeurIPS’24 |
| SPECI [Zhou et al., 2025] | PE | 📦 Object + 🎯 Goal + 🗺️ Spatial | LIBERO | [💻](https://github.com/Triumphant-strain/SPECI) | TCDS’25 |
| PPL [Li et al., 2025] | PEFT + PE | 📦 Object + 🎯 Goal | LIBERO, MimicGen |  | CVPR’25 |
| LEGION [Kim et al., 2025] | ME | 📦 Object + 🎯 Goal | – | [💻](https://github.com/legion/legion) | ICRA’25 |
| LLWM [Zheng et al., 2025] | GR + W + R | 📦 Object + 🎯 Goal | DM Control, Meta-World | [💻](https://github.com/WendongZh/continual_visual_control) | ECML’25 |
| iManip [Chen et al., 2025] | PEFT + ER + PE | 📦 Object + 🎯 Goal | RLBench |  | ICCV’25 |
| OA [Liu et al., 2025] | W + R | 📦 Object + 🎯 Goal | ContinualBench | [💻](https://github.com/sail-sg/ContinualBench) | ICML’25 |
| M2Distill [Wang et al., 2025] | R | 📦 Object + 🎯 Goal + 🗺️ Spatial | LIBERO |  | ICRA’25 |
| CKA-RL [Zhang et al., 2025] | PE | 📦 Object + 🎯 Goal | LIBERO |  | arXiv’25 |
| OMLA [Sun et al., 2025] | PEFT + ML | 📦 Object + 🎯 Goal + 🗺️ Spatial | LIBERO |  | arXiv’25 |
| CLARE [Patel et al., 2026] | PE + PEFT | 📦 Object + 🎯 Goal + 🗺️ Spatial | LIBERO | [💻](https://github.com/utiasDSL/clare) | arXiv’26 |

### Navigation

| Paper | CL Technique | Setting | Benchmark | Code | Venue |
| :--- | :--- | :--- | :--- | :---: | :---: |
| ReplayMatch [Kumar et al., 2024] | ER | 🗺️ Spatial | DM Control | [💻](https://github.com/replaymatch/replaymatch) | NeurIPS’24 |
| NavCL [Singh et al., 2025] | R + ER | 🌍 Environment | CARLA |  | ICRA’25 |
| SPLIT [Wang et al., 2025] | PI | 🌍 Environment + 🗺️ Spatial | Gibson | [💻](https://github.com/split/split) | RSS’25 |
| ContinualNav [Zhou et al., 2024] | ML + ER | 🗺️ Spatial | Habitat | [💻](https://github.com/continualnav/continualnav) | CoRL’24 |
| MapMem [Lee et al., 2024] | ME + W | 🌍 Environment | CARLA, Gibson |  | ICRA’24 |

### Planning

| Paper | CL Technique | Setting | Benchmark | Code | Venue |
| :--- | :--- | :--- | :--- | :---: | :---: |
| PlanCL [Garcia et al., 2024] | ML + PE | 🗺️ Spatial | MiniGrid | [💻](https://github.com/plancl/plancl) | NeurIPS’24 |
| Stratego [Chen et al., 2025] | PI + ER | 🎯 Goal | Meta-World |  | ICML’25 |
| ContinualPlanner [Wang et al., 2025] | R + ML | 🌍 Environment | Custom | [💻](https://github.com/continualplanner/continualplanner) | ICRA’25 |

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
@article{yoursurvey2026,
  title={A Survey of Continual Learning for Robotics in the Foundation Model Era},
  author={Your Name et al.},
  journal={TechRxiv},
  year={2026}
}
```

---

**Last Updated**: February 2026 | **Paper Count**: XX | **Papers with Code**: XX
