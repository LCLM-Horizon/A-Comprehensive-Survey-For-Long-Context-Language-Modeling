# LCLM-Survey

<div align="center">
 <p align="center">
 
   <a href="#1-Survey-Papers">📝 Papers</a> | 
 
 </p>
</div>
<div align="center">

<!-- ![Build](https://img.shields.io/appveyor/build/gruntjs/grunt) -->
[![LICENSE](https://img.shields.io/github/license/LCLM-Space/LCLM-Survey)](https://github.com/LCLM-Space/LCLM-Survey/blob/main/LICENSE)
![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
[![commit](https://img.shields.io/github/last-commit/LCLM-Space/LCLM-Survey?color=blue)](https://github.com/LCLM-Space/LCLM-Survey/commits/main)
[![PR](https://img.shields.io/badge/PRs-Welcome-red)](https://github.com/LCLM-Space/LCLM-Survey/pulls)
[![GitHub Repo stars](https://img.shields.io/github/stars/LCLM-Space/LCLM-Survey)](https://github.com/LCLM-Space/LCLM-Survey)
<!-- ![license](https://img.shields.io/bower/l/bootstrap?style=plastic) -->

</div>

> A collection of papers and resources related to Long Context Language Modeling. 
>
> We appreciate any useful suggestions for improvement of this paper list or survey from peers. Please raise issues or send an email to dwzhu@pku.edu.cn or ljh411989@alibaba-inc.com or huanxuanliao@gmail.com. Thanks for your cooperation!
>
> If you find our survey useful for your research, please cite the following paper:

```bibtex

```

## Updates

- [2025.03.09] We release the first version of the survey on Long Context Language Modeling [[**arXiv**]()]


## Table of Contents

- [LCLM-Survey](#lclm-survey)
  - [Updates](#updates)
  - [Table of Contents](#table-of-contents)
  - [Paper List](#paper-list)
    - [Data](#data)
      - [Pretraining](#pretraining)
      - [Posttraining](#posttraining)
    - [Model](#model)
      - [Position Embeddings](#position-embeddings)
      - [Architecture](#architecture)
      - [Hybrid Architecture](#hybrid-architecture)
    - [Inference](#inference)
      - [Sparse Attention (inference)](#sparse-attention-inference)
      - [Prompt Compression](#prompt-compression)
      - [Memory-Based](#memory-based)
      - [RAG-Based](#rag-based)
      - [Agent-Based](#agent-based)
    - [Evaluation](#evaluation)
      - [Long-Context Comprehension](#long-context-comprehension)
      - [Long-Form Generation](#long-form-generation)
    - [AI Infrastructure](#ai-infrastructure)
      - [Training](#training)
        - [I/O Optimization](#io-optimization)
        - [Memory Optimization](#memory-optimization)
        - [Communication Optimization](#communication-optimization)
      - [Inference](#inference-1)
        - [Quantization](#quantization)
        - [Memory Management](#memory-management)
        - [Prefilling-Decoding Disaggregated Architecture](#prefilling-decoding-disaggregated-architecture)
        - [GPU-CPU Parallel Inference](#gpu-cpu-parallel-inference)
        - [Speculative Decoding](#speculative-decoding)
    - [Interpretability](#interpretability)
      - [Performance Analysis](#performance-analysis)
      - [Model Structure Analysis](#model-structure-analysis)
      - [Visualization and Interpretation of Positional Encoding](#visualization-and-interpretation-of-positional-encoding)
    - [Application](#application)
      - [Agent](#agent)
      - [RAG](#rag)
      - [Chatbot](#chatbot)
      - [Code](#code)
      - [NLP Tasks](#nlp-tasks)
      - [Multimodal Tasks](#multimodal-tasks)
      - [Specific Domains](#specific-domains)
    - [Future Directions](#future-directions)
      - [Long CoT](#long-cot)
  - [Other Awesome Lists](#other-awesome-lists)
  - [The Team](#the-team)
  - [Acknowledgments](#acknowledgments)
  - [Contributors](#contributors)
  - [Star History](#star-history)



## Paper List

### Data

#### Pretraining

#### Posttraining

### Model

#### Position Embeddings

#### Architecture

#### Hybrid Architecture

### Inference

#### Sparse Attention (inference)

#### Prompt Compression

<!-- ##### Hard Prompt Compression

##### Soft Prompt Compression -->


1. [**Adapting Language Models to Compress Contexts.**](https://arxiv.org/abs/2305.14788) *Alexis Chevalier, Alexander Wettig, Anirudh Ajith, Danqi Chen.* Arxiv 2023. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/AutoCompressors)](https://github.com/princeton-nlp/AutoCompressors)

#### Memory-Based

#### RAG-Based

#### Agent-Based

### Evaluation

#### Long-Context Comprehension

#### Long-Form Generation

1. [**Integrating Planning into Single-Turn Long-Form Text Generation.**](https://arxiv.org/abs/2410.06203) *Yi Liang, You Wu, Honglei Zhuang, Li Chen, Jiaming Shen, Yiling Jia, Zhen Qin, Sumit Sanghai, Xuanhui Wang, Carl Yang, Michael Bendersky.* Arxiv 2024.

2. [**Minimum Tuning to Unlock Long Output from LLMs with High Quality Data as the Key.**](https://arxiv.org/abs/2410.10210) *Yingda Chen, Xingjun Wang, Jintao Huang, Yunlin Mao, Daoze Zhang, Yuze Zhao.* Arxiv 2024.

3. [**LongGenBench: Long-context Generation Benchmark.**](https://arxiv.org/abs/2410.04199) *Xiang Liu, Peijie Dong, Xuming Hu, Xiaowen Chu.* EMNLP 2024.

4. [**LoGU: Long-form Generation with Uncertainty Expressions.**](https://arxiv.org/abs/2410.14309) *Ruihan Yang, Caiqi Zhang, Zhisong Zhang, Xinting Huang, Sen Yang, Nigel Collier, Dong Yu, Deqing Yang.* Arxiv 2024.

5. [**Large Language Models Still Exhibit Bias in Long Text.**](https://arxiv.org/abs/2410.17519) *Wonje Jeung, Dongjae Jeon, Ashkan Yousefpour, Jonghyun Choi.* Arxiv 2024.

6. [**Suri: Multi-constraint Instruction Following for Long-form Text Generation.**](https://arxiv.org/abs/2406.19371) *Chau Minh Pham, Simeng Sun, Mohit Iyyer.* Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/chtmp223/suri)](https://github.com/chtmp223/suri)

7. [**LongWriter: Unleashing 10,000+ Word Generation from Long Context LLMs.**](https://arxiv.org/abs/2408.07055) *Yushi Bai, Jiajie Zhang, Xin Lv, Linzhi Zheng, Siqi Zhu, Lei Hou, Yuxiao Dong, Jie Tang, Juanzi Li.* Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/THUDM/LongWriter)](https://github.com/THUDM/LongWriter)

8. [**Language Models can Self-Lengthen to Generate Long Texts.**](https://arxiv.org/abs/2410.23933) *Shanghaoran Quan, Tianyi Tang, Bowen Yu, An Yang, Dayiheng Liu, Bofei Gao, Jianhong Tu, Yichang Zhang, Jingren Zhou, Junyang Lin.* Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/QwenLM/Self-Lengthen)](https://github.com/QwenLM/Self-Lengthen)

9. [**Generating Long-form Story Using Dynamic Hierarchical Outlining with Memory-Enhancement.**](https://arxiv.org/abs/2412.13575) *Qianyue Wang, Jinwu Hu, Zhengping Li, Yufeng Wang, daiyuan li, Yu Hu, Mingkui Tan.* Arxiv 2024.

10. [**Beyond Factual Accuracy: Evaluating Coverage of Diverse Factual Information in Long-form Text Generation.**](https://arxiv.org/abs/2501.03545) *Chris Samarinas, Alexander Krubner, Alireza Salemi, Youngwoo Kim, Hamed Zamani.* Arxiv 2025. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/algoprog/ICAT)](https://github.com/algoprog/ICAT)

11. [**The FACTS Grounding Leaderboard: Benchmarking LLMs' Ability to Ground Responses to Long-Form Input.**](https://arxiv.org/abs/2501.03200) *Alon Jacovi, Andrew Wang, Chris Alberti, Connie Tao, Jon Lipovetz, Kate Olszewska, Lukas Haas, Michelle Liu, Nate Keating, Adam Bloniarz, Carl Saroufim, Corey Fry, Dror Marcus, Doron Kukliansky, Gaurav Singh Tomar, James Swirhun, Jinwei Xing, Lily Wang, Madhu Gurumurthy, Michael Aaron, Moran Ambar, Rachana Fellinger, Rui Wang, Zizhao Zhang, Sasha Goldshtein, Dipanjan Das.* Arxiv 2025. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://www.kaggle.com/facts-leaderboard)

12. [**LongProc: Benchmarking Long-Context Language Models on Long Procedural Generation.**](https://arxiv.org/abs/2501.05414) *Xi Ye, Fangcong Yin, Yinghui He, Joie Zhang, Howard Yen, Tianyu Gao, Greg Durrett, Danqi Chen.* Arxiv 2025. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/princeton-pli/LongProc)](https://github.com/princeton-pli/LongProc)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://princeton-pli.github.io/LongProc/)

13. [**ExPerT: Effective and Explainable Evaluation of Personalized Long-Form Text Generation.**](https://arxiv.org/abs/2501.14956) *Alireza Salemi, Julian Killingback, Hamed Zamani.* Arxiv 2025. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/alirezasalemi7/ExPerT)](https://github.com/alirezasalemi7/ExPerT)

14. [**LongDPO: Unlock Better Long-form Generation Abilities for LLMs via Critique-augmented Stepwise Information.**](https://arxiv.org/abs/2502.02095) *Bowen Ping, Jiali Zeng, Fandong Meng, Shuo Wang, Jie Zhou, Shanghang Zhang.* Arxiv 2025.

15. [**Context-Preserving Gradient Modulation for Large Language Models: A Novel Approach to Semantic Consistency in Long-Form Text Generation.**](https://arxiv.org/abs/2502.03643) *Nirola Kobanov, Edmund Weatherstone, Zachary Vanderpoel, Orlando Wetherby.* Arxiv 2025.

16. [**A Cognitive Writing Perspective for Constrained Long-Form Text Generation.**](https://arxiv.org/abs/2502.12568) *Kaiyang Wan, Honglin Mu, Rui Hao, Haoran Luo, Tianle Gu, Xiuying Chen.* Arxiv 2025. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/KaiyangWan/CogWriter)](https://github.com/KaiyangWan/CogWriter)

17. [**CLIPPER: Compression enables long-context synthetic data generation.**](https://arxiv.org/abs/2502.14854) *Chau Minh Pham, Yapei Chang, Mohit Iyyer.* Arxiv 2025. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/chtmp223/CLIPPER)](https://github.com/chtmp223/CLIPPER)

18. [**LongWriter-V: Enabling Ultra-Long and High-Fidelity Generation in Vision-Language Models.**](https://arxiv.org/abs/2502.14834) *Shangqing Tu, Yucheng Wang, Daniel Zhang-Li, Yushi Bai, Jifan Yu, Yuhao Wu, Lei Hou, Huiqin Liu, Zhiyuan Liu, Bin Xu, Juanzi Li.* Arxiv 2025. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/THU-KEG/LongWriter-V)](https://github.com/THU-KEG/LongWriter-V)

19. [**LongEval: A Comprehensive Analysis of Long-Text Generation Through a Plan-based Paradigm.**](https://arxiv.org/abs/2502.19103) *Siwei Wu, Yizhi Li, Xingwei Qu, Rishi Ravikumar, Yucheng Li, Tyler Loakman Shanghaoran Quan Xiaoyong Wei, Riza Batista-Navarro, Chenghua Lin.* Arxiv 2025. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Wusiwei0410/LongEval)](https://github.com/Wusiwei0410/LongEval)

20. [**From Hours to Minutes: Lossless Acceleration of Ultra Long Sequence Generation up to 100K Tokens.**](https://arxiv.org/abs/2502.18890) *Tong Wu, Junzhe Shen, Zixia Jia, Yuxuan Wang, Zilong Zheng.* Arxiv 2025. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/bigai-nlco/TokenSwift)](https://github.com/bigai-nlco/TokenSwift)

### AI Infrastructure

#### Training

##### I/O Optimization

##### Memory Optimization

##### Communication Optimization

#### Inference

##### Quantization

##### Memory Management

##### Prefilling-Decoding Disaggregated Architecture

##### GPU-CPU Parallel Inference

##### Speculative Decoding

1. [**LongSpec: Long-Context Speculative Decoding with Efficient Drafting and Verification.**](https://arxiv.org/abs/2502.17421) *Penghui Yang, Cunxiao Du, Fengzhuo Zhang, Haonan Wang, Tianyu Pang, Chao Du, Bo An.* Arxiv 2025. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/sail-sg/LongSpec)](https://github.com/sail-sg/LongSpec)

1. [**Long-Context Inference with Retrieval-Augmented Speculative Decoding.**](https://arxiv.org/abs/2502.20330) *Guanzheng Chen, Qilong Feng, Jinjie Ni, Xin Li, Michael Qizhe Shieh.* Arxiv 2025. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/John-AI-Lab/RAPID)](https://github.com/John-AI-Lab/RAPID)

### Interpretability

#### Performance Analysis

#### Model Structure Analysis

#### Visualization and Interpretation of Positional Encoding

### Application

#### Agent

#### RAG

#### Chatbot

#### Code

#### NLP Tasks

#### Multimodal Tasks

#### Specific Domains

### Future Directions

#### Long CoT

1. [**When More is Less: Understanding Chain-of-Thought Length in LLMs.**](https://arxiv.org/abs/2502.07266) *Yuyang Wu, Yifei Wang, Tianqi Du, Stefanie Jegelka, Yisen Wang.* Arxiv 2025.

2. [**LLMs Can Easily Learn to Reason from Demonstrations Structure, not content, is what matters!.**](https://arxiv.org/abs/2502.07374) *Dacheng Li, Shiyi Cao, Tyler Griggs, Shu Liu, Xiangxi Mo, Shishir G. Patil, Matei Zaharia, Joseph E. Gonzalez, Ion Stoica.* Arxiv 2025. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/NovaSky-AI/SkyThought)](https://github.com/NovaSky-AI/SkyThought)

3. [**Monte Carlo Tree Diffusion for System 2 Planning.**](https://arxiv.org/abs/2502.07202) *Jaesik Yoon, Hyeonseo Cho, Doojin Baek, Yoshua Bengio, Sungjin Ahn.* Arxiv 2025.

4. [**Enhancing Auto-regressive Chain-of-Thought through Loop-Aligned Reasoning.**](https://arxiv.org/abs/2502.08482) *Qifan Yu, Zhenyu He, Sijie Li, Xun Zhou, Jun Zhang, Jingjing Xu, Di He.* Arxiv 2025. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/qifanyu/RELAY)](https://github.com/qifanyu/RELAY)

5. [**CoT-Valve: Length-Compressible Chain-of-Thought Tuning.**](https://arxiv.org/abs/2502.09601) *Xinyin Ma, Guangnian Wan, Runpeng Yu, Gongfan Fang, Xinchao Wang.* Arxiv 2025. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/horseee/CoT-Valve)](https://github.com/horseee/CoT-Valve)

6. [**Efficient Long-Decoding Inference with Reasoning-Aware Attention Sparsity.**](https://arxiv.org/abs/2502.11147) *Junhao Hu, Wenrui Huang, Weidong Wang, Zhenwen Li, Tiancheng Hu, Zhixia Liu, Xusheng Chen, Tao Xie, Yizhou Shan.* Arxiv 2025.

7. [**DRT: Deep Reasoning Translation via Long Chain-of-Thought.**](https://arxiv.org/abs/2412.17498) *Jiaan Wang, Fandong Meng, Yunlong Liang, Jie Zhou.* Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/krystalan/DRT-o1)](https://github.com/krystalan/DRT-o1)

8. [**Do NOT Think That Much for 2+3=? On the Overthinking of o1-Like LLMs.**](https://arxiv.org/abs/2412.21187) *Xingyu Chen, Jiahao Xu, Tian Liang, Zhiwei He, Jianhui Pang, Dian Yu, Linfeng Song, Qiuzhi Liu, Mengfei Zhou, Zhuosheng Zhang, Rui Wang, Zhaopeng Tu, Haitao Mi, Dong Yu.* Arxiv 2024.

9. [**O1 Replication Journey -- Part 2: Surpassing O1-preview through Simple Distillation, Big Progress or Bitter Lesson?.**](https://arxiv.org/abs/2411.16489) *Zhen Huang, Haoyang Zou, Xuefeng Li, Yixiu Liu, Yuxiang Zheng, Ethan Chern, Shijie Xia, Yiwei Qin, Weizhe Yuan, Pengfei Liu.* Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/GAIR-NLP/O1-Journey)](https://github.com/GAIR-NLP/O1-Journey)

10. [**OpenRFT: Adapting Reasoning Foundation Model for Domain-specific Tasks with Reinforcement Fine-Tuning.**](https://arxiv.org/abs/2412.16849) *Yuxiang Zhang, Yuqi Yang, Jiangming Shu, Yuhang Wang, Jinlin Xiao, Jitao Sang.* Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/ADaM-BJTU/OpenRFT)](https://github.com/ADaM-BJTU/OpenRFT)

11. [**Dynamic Chain-of-Thought: Towards Adaptive Deep Reasoning.**](https://arxiv.org/abs/2502.10428) *Libo Wang.* Arxiv 2025. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/brucewang123456789/GeniusTrail)](https://github.com/brucewang123456789/GeniusTrail/tree/main/Dynamic%20CoT)

12. [**SafeChain: Safety of Language Models with Long Chain-of-Thought Reasoning Capabilities.**](https://arxiv.org/abs/2502.12025) *Fengqing Jiang, Zhangchen Xu, Yuetai Li, Luyao Niu, Zhen Xiang, Bo Li, Bill Yuchen Lin, Radha Poovendran.* Arxiv 2025. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://safe-chain.github.io/)

13. [**Leveraging Constrained Monte Carlo Tree Search to Generate Reliable Long Chain-of-Thought for Mathematical Reasoning.**](https://arxiv.org/abs/2502.11169) *Qingwen Lin, Boyan Xu, Zijian Li, Zhifeng Hao, Keli Zhang, Ruichu Cai.* Arxiv 2025.

14. [**Revisiting the Test-Time Scaling of o1-like Models: Do they Truly Possess Test-Time Scaling Capabilities?.**](https://arxiv.org/abs/2502.12215) *Zhiyuan Zeng, Qinyuan Cheng, Zhangyue Yin, Yunhua Zhou, Xipeng Qiu.* Arxiv 2025.

15. [**TokenSkip: Controllable Chain-of-Thought Compression in LLMs.**](https://arxiv.org/abs/2502.12067) *Heming Xia, Yongqi Li, Chak Tou Leong, Wenjie Wang, Wenjie Li.* Arxiv 2025. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/hemingkx/TokenSkip)](https://github.com/hemingkx/TokenSkip)

16. [**LightThinker: Thinking Step-by-Step Compression.**](https://arxiv.org/abs/2502.15589) *Jintian Zhang, Yuqi Zhu, Mengshu Sun, Yujie Luo, Shuofei Qiao, Lun Du, Da Zheng, Huajun Chen, Ningyu Zhang.* Arxiv 2025. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/zjunlp/LightThinker)](https://github.com/zjunlp/LightThinker)

17. [**Towards Thinking-Optimal Scaling of Test-Time Compute for LLM Reasoning.**](https://arxiv.org/abs/2502.18080) *Wenkai Yang, Shuming Ma, Yankai Lin, Furu Wei.* Arxiv 2025.

18. [**Can Large Language Models Detect Errors in Long Chain-of-Thought Reasoning?.**](https://arxiv.org/abs/2502.19361) *Yancheng He, Shilong Li, Jiaheng Liu, Weixun Wang, Xingyuan Bu, Ge Zhang, Zhongyuan Peng, Zhaoxiang Zhang, Zhicheng Zheng, Wenbo Su, Bo Zheng.* Arxiv 2025. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/OpenStellarTeam/DeltaBench)](https://github.com/OpenStellarTeam/DeltaBench)

## Other Awesome Lists

- **[Awesome-LLM-Long-Context-Modeling](https://github.com/Xnhyacinth/Awesome-LLM-Long-Context-Modeling)**  Collection of papers and resources on LLM-based Long Context Modeling.

## The Team

## Acknowledgments

Please contact us if We miss your names in the list, I will add you back ASAP!

## Contributors

<a href="https://github.com/LCLM-Space/LCLM-Survey/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=LCLM-Space/LCLM-Survey" />
</a>

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=LCLM-Space/LCLM-Survey&type=Timeline)](https://github.com/LCLM-Space/LCLM-Survey//stargazers)