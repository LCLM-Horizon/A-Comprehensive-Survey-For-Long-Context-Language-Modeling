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
1. [**An Efficient Recipe for Long Context Extension via Middle-Focused Positional Encoding.**](https://arxiv.org/abs/2406.07138) *Tong Wu, Yanpeng Zhao, Zilong Zheng.* NeurIPS 2024. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/bigai-nlco/cream)](https://github.com/bigai-nlco/cream)

2. [**PoSE: Efficient Context Window Extension of LLMs via Positional Skip-wise Training.**](https://arxiv.org/abs/2309.10400) *Dawei Zhu,Nan Yang,Liang Wang,Yifan Song,Wenhao Wu,Furu Wei,Sujian Li.* Arxiv 2023.   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/dwzhu-pku/PoSE)](https://github.com/dwzhu-pku/PoSE)

3. [**Contextual Position Encoding: Learning to Count What's Important.**](https://arxiv.org/abs/2405.18719) *Olga Golovneva, Tianlu Wang, Jason Weston, Sainbayar Sukhbaatar.* Arxiv 2024.

4. [**Why Does the Effective Context Length of LLMs Fall Short?.**](https://arxiv.org/abs/2410.18745) *Chenxin An, Jun Zhang, Ming Zhong, Lei Li, Shansan Gong, Yao Luo, Jingjing Xu, Lingpeng Kong.* Arxiv 2024.

5. [**HoPE: A Novel Positional Encoding Without Long-Term Decay for Enhanced Context Awareness and Extrapolation.**](https://arxiv.org/abs/2410.21216) *Yuhan Chen, Ang Lv, Jian Luan, Bin Wang, Wei Liu.* Arxiv 2024.

6. [**DAPE: Data-Adaptive Positional Encoding for Length Extrapolation.**](https://arxiv.org/abs/2405.14722) *Chuanyang Zheng, Yihang Gao, Han Shi, Minbin Huang, Jingyao Li, Jing Xiong, Xiaozhe Ren, Michael Ng, Xin Jiang, Zhenguo Li, Yu Li.* NeurIPS 2024. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/chuanyang-Zheng/DAPE)](https://github.com/chuanyang-Zheng/DAPE)

7. [**Convolutional sequence to sequence learning.**](https://arxiv.org/abs/1705.03122)  *Jonas Gehring and Michael Auli and David Grangier and Denis Yarats and Yann N. Dauphin*. Arxiv 2017

8. [**Self-attention with relative position representations.**](https://arxiv.org/abs/1803.02155)  *Peter Shaw and Jakob Uszkoreit and Ashish Vaswani*. Arxiv 2018

9. [**Encoding word order in complex embeddings.**](https://arxiv.org/abs/1912.12333)  *Benyou Wang and Donghao Zhao and Christina Lioma and Qiuchi Li and Peng Zhang and Jakob Grue Simonsen*. Arxiv 2020

10. [**Exploring the limits of transfer learning with a unified text-to-text transformer.**](https://arxiv.org/abs/1910.10683)  *Colin Raffel and Noam Shazeer and Adam Roberts and Katherine Lee and Sharan Narang and Michael Matena and Yanqi Zhou and Wei Li and Peter J. Liu*. 2023

11. [**Train short, test long: Attention with linear biases enables input length extrapolation.**](https://arxiv.org/abs/2108.12409)  *Ofir Press and Noah A. Smith and Mike Lewis*. Arxiv 2022

12. [**Kerple: Kernelized relative positional embedding for length extrapolation.**](https://arxiv.org/abs/2205.09921)  *Ta-Chung Chi and Ting-Han Fan and Peter J. Ramadge and Alexander I. Rudnicky*. Arxiv 2022

13. [**Dissecting transformer length extrapolation via the lens of receptive field analysis.**](https://arxiv.org/abs/2212.10356)  *Ta-Chung Chi and Ting-Han Fan and Alexander I. Rudnicky and Peter J. Ramadge*. Arxiv 2023

14. [**A length-extrapolatable transformer.**](https://arxiv.org/abs/2212.10554)  *Yutao Sun and Li Dong and Barun Patra and Shuming Ma and Shaohan Huang and Alon Benhaim and Vishrav Chaudhary and Xia Song and Furu Wei*. Arxiv 2022

15. [**Functional interpolation for relative positions improves long context transformers.**](https://arxiv.org/abs/2310.04418)  *Shanda Li and Chong You and Guru Guruganesh and Joshua Ainslie and Santiago Ontanon and Manzil Zaheer and Sumit Sanghai and Yiming Yang and Sanjiv Kumar and Srinadh Bhojanapalli*. Arxiv 2024

16. [**Latent positional information is in the self-attention variance of transformer language models without positional embeddings.**](https://arxiv.org/abs/2305.13571)  *Latent Positional Information is in the Self-Attention Variance of Transformer Language Models Without Positional Embeddings*. Arxiv 2023

17. [**Extending context window of large language models via positional interpolation.**](https://arxiv.org/abs/2306.15595)  *Shouyuan Chen and Sherman Wong and Liangjian Chen and Yuandong Tian*. Arxiv 2023

18. [**Randomized positional encodings boost length generalization of transformers.**](https://arxiv.org/abs/2305.16843)  *Anian Ruoss and Grégoire Delétang and Tim Genewein and Jordi Grau-Moya and Róbert Csordás and Mehdi Bennani and Shane Legg and Joel Veness*. Arxiv 2023

19. [**Yarn: Efficient context window extension of large language models.**](https://arxiv.org/abs/2309.00071)  *Bowen Peng and Jeffrey Quesnelle and Honglu Fan and Enrico Shippole*. Arxiv 2023

20. [**Clex: Continuous length extrapolation for large language models.**](https://arxiv.org/abs/2310.16450)  *Guanzheng Chen and Xin Li and Zaiqiao Meng and Shangsong Liang and Lidong Bing*. Arxiv 2024

21. [**Effective long-context scaling of foundation models.**](https://arxiv.org/abs/2309.16039)  *Wenhan Xiong and Jingyu Liu and Igor Molybog and Hejia Zhang and Prajjwal Bhargava and Rui Hou and Louis Martin and Rashi Rungta and Karthik Abinav Sankararaman and Barlas Oguz and Madian Khabsa and Han Fang and Yashar Mehdad and Sharan Narang and Kshitiz Malik and Angela Fan and Shruti Bhosale and Sergey Edunov and Mike Lewis and Sinong Wang and Hao Ma*. Arxiv 2023

22. [**Giraffe: Adventures in expanding context lengths in llms.**](https://arxiv.org/abs/2308.10882)  *Arka Pal and Deep Karkhanis and Manley Roberts and Samuel Dooley and Arvind Sundararajan and Siddartha Naidu*. Arxiv 2023

23. [**Resonance rope: Improving context length generalization of large language models.**](https://arxiv.org/abs/2403.00071)  *Suyuchen Wang and Ivan Kobyzev and Peng Lu and Mehdi Rezagholizadeh and Bang Liu*. Arxiv 2024

24. [**Long context alignment with short instructions and synthesized positions.**](https://arxiv.org/abs/2405.03939)  *Wenhao Wu and Yizhong Wang and Yao Fu and Xiang Yue and Dawei Zhu and Sujian Li*. Arxiv 2024

25. [**Two stones hit one bird: Bilevel positional encoding for better length extrapolation.**](https://arxiv.org/abs/2401.16421)  *Zhenyu He and Guhao Feng and Shengjie Luo and Kai Yang and Liwei Wang and Jingjing Xu and Zhi Zhang and Hongxia Yang and Di He*. Arxiv 2024

26. [**Found in the middle: How language models use long contexts better via plug-and-play positional encoding.**](https://arxiv.org/abs/2403.04797)  *Zhenyu Zhang and Runjin Chen and Shiwei Liu and Zhewei Yao and Olatunji Ruwase and Beidi Chen and Xiaoxia Wu and Zhangyang Wang*. Arxiv 2024

27. [**Llm maybe longlm: Self-extend llm context window without tuning.**](https://arxiv.org/abs/2401.01325)  *Hongye Jin and Xiaotian Han and Jingfeng Yang and Zhimeng Jiang and Zirui Liu and Chia-Yuan Chang and Huiyuan Chen and Xia Hu*. Arxiv 2024

28. [**Longrope: Extending llm context window beyond 2 million tokens.**](https://arxiv.org/abs/2402.13753)  *Yiran Ding and Li Lyna Zhang and Chengruidong Zhang and Yuanyuan Xu and Ning Shang and Jiahang Xu and Fan Yang and Mao Yang*. Arxiv 2024

29. [**The impact of positional encoding on length generalization in transformers.**](https://arxiv.org/abs/2305.19466)  *Amirhossein Kazemnejad and Inkit Padhi and Karthikeyan Natesan Ramamurthy and Payel Das and Siva Reddy*. Arxiv 2024

30. [**Roformer: Enhanced transformer with rotary position embedding.**](https://arxiv.org/abs/2104.09864)  *Jianlin Su and Yu Lu and Shengfeng Pan and Ahmed Murtadha and Bo Wen and Yunfeng Liu*. Arxiv 2023

31. [**Training-free long-context scaling of large language models.**](https://arxiv.org/abs/2402.1746)  *Chenxin An and Fei Huang and Jun Zhang and Shansan Gong and Xipeng Qiu and Chang Zhou and Lingpeng Kong*. Arxiv 2024


#### Architecture

1. [**Compressive Transformers for Long-Range Sequence Modelling.**](https://arxiv.org/abs/1911.05507) *Jack W. Rae, Anna Potapenko, Siddhant M. Jayakumar, Timothy P. Lillicrap.* Arxiv 2019.   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/compressive-transformer-pytorch)](https://github.com/lucidrains/compressive-transformer-pytorch)

2. [**Transformers are RNNs: Fast Autoregressive Transformers with Linear Attention.**](https://arxiv.org/abs/2006.16236) *Angelos Katharopoulos, Apoorv Vyas, Nikolaos Pappas, François Fleuret.* ICML 2020.   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/idiap/fast-transformers)](https://github.com/idiap/fast-transformers)

3. [**Block-Recurrent Transformers.**](https://arxiv.org/abs/2203.07852) *DeLesley Hutchins, Imanol Schlag, Yuhuai Wu, Ethan Dyer, Behnam Neyshabur.* Arxiv 2023.   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/block-recurrent-transformer-pytorch)](https://github.com/lucidrains/block-recurrent-transformer-pytorch)

4. [**Memorizing Transformers.**](https://arxiv.org/abs/2203.08913) *Yuhuai Wu, Markus N. Rabe, DeLesley Hutchins, Christian Szegedy.* Arxiv 2022.   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/memorizing-transformers-pytorch)](https://github.com/lucidrains/memorizing-transformers-pytorch)

5. [**GQA: Training Generalized Multi-Query Transformer Models from Multi-Head Checkpoints.**](https://arxiv.org/abs/2305.13245) *Joshua Ainslie, James Lee-Thorp, Michiel de Jong, Yury Zemlyanskiy, Federico Lebrón, Sumit Sanghai.* Arxiv 2023.

6. [**Zebra: Extending Context Window with Layerwise Grouped Local-Global Attention.**](https://arxiv.org/abs/2312.08618) *Kaiqiang Song, Xiaoyang Wang, Sangwoo Cho, Xiaoman Pan, Dong Yu.* Arxiv 2023.

7. [**Leave No Context Behind: Efficient Infinite Context Transformers with Infini-attention.**](https://arxiv.org/abs/2404.07143) *Tsendsuren Munkhdalai, Manaal Faruqui, Siddharth Gopal.* Arxiv 2024.

8. [**Weighted Grouped Query Attention in Transformers.**](https://arxiv.org/abs/2407.10855) *Sai Sena Chinnakonduru, Astarag Mohapatra.* Arxiv 2024.

9. [**Associative Recurrent Memory Transformer.**](https://arxiv.org/abs/2407.04841) *Ivan Rodkin, Yuri Kuratov, Aydar Bulatov, Mikhail Burtsev.* ICML 2024 Workshop. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/RodkinIvan/associative-recurrent-memory-transformer)](https://github.com/RodkinIvan/associative-recurrent-memory-transformer)

10. [**Simple linear attention language models balance the recall-throughput tradeoff.**](https://arxiv.org/abs/2402.18668) *Simran Arora, Sabri Eyuboglu, Michael Zhang, Aman Timalsina, Silas Alberti, Dylan Zinsley, James Zou, Atri Rudra, Christopher Ré.* Arxiv 2024. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/HazyResearch/based)](https://github.com/HazyResearch/based)

11. [**DuoAttention: Efficient Long-Context LLM Inference with Retrieval and Streaming Heads.**](https://arxiv.org/abs/2410.10819) *Guangxuan Xiao, Jiaming Tang, Jingwei Zuo, Junxian Guo, Shang Yang, Haotian Tang, Yao Fu, Song Han.* Arxiv 2024. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/mit-han-lab/duo-attention)](https://github.com/mit-han-lab/duo-attention)

12. [**TidalDecode: Fast and Accurate LLM Decoding with Position Persistent Sparse Attention.**](https://arxiv.org/abs/2410.05076) *Lijie Yang, Zhihao Zhang, Zhuofu Chen, Zikun Li, Zhihao Jia.* Arxiv 2024. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/DerrickYLJ/TidalDecode)](https://github.com/DerrickYLJ/TidalDecode)

13. [**Selective Attention Improves Transformer.**](https://arxiv.org/abs/2410.02703) *Yaniv Leviathan, Matan Kalman, Yossi Matias.* Arxiv 2024.

16. [**SnapKV: LLM Knows What You are Looking for Before Generation.**](https://arxiv.org/abs/2404.14469) *Yuhong Li, Yingbing Huang, Bowen Yang, Bharat Venkitesh, Acyr Locatelli, Hanchen Ye, Tianle Cai, Patrick Lewis, Deming Chen.* Arxiv 2024. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/FasterDecoding/SnapKV)](https://github.com/FasterDecoding/SnapKV)

17. [**Extra Global Attention Designation Using Keyword Detection in Sparse Transformer Architectures.**](https://arxiv.org/abs/2410.08971) *Evan Lucas, Dylan Kangas, Timothy C Havens.* Arxiv 2024.

18. [**An Empirical Study of Mamba-based Language Models.**](https://arxiv.org/abs/2406.07887) *Roger Waleffe, Wonmin Byeon, Duncan Riach, Brandon Norick, Vijay Korthikanti, Tri Dao, Albert Gu, Ali Hatamizadeh, Sudhakar Singh, Deepak Narayanan, Garvit Kulshreshtha, Vartika Singh, Jared Casper, Jan Kautz, Mohammad Shoeybi, Bryan Catanzaro.* Arxiv 2024. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/NVIDIA/Megatron-LM)](https://github.com/NVIDIA/Megatron-LM/tree/ssm/examples/mamba)

19. [**Lightning Attention-2: A Free Lunch for Handling Unlimited Sequence Lengths in Large Language Models.**](https://arxiv.org/abs/2401.04695) *Zhen Qin, Weigao Sun, Dong Li, Xuyang Shen, Weixuan Sun, Yiran Zhong.* Arxiv 2024. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/OpenNLPLab/lightning-attention)](https://github.com/OpenNLPLab/lightning-attention)

20. [**Various Lengths, Constant Speed: Efficient Language Modeling with Lightning Attention.**](https://arxiv.org/abs/2405.17381) *Zhen Qin, Weigao Sun, Dong Li, Xuyang Shen, Weixuan Sun, Yiran Zhong.* Arxiv 2024.

21. [**SeerAttention: Learning Intrinsic Sparse Attention in Your LLMs.**](https://arxiv.org/abs/2410.13276) *Yizhao Gao, Zhichen Zeng, Dayou Du, Shijie Cao, Hayden Kwok-Hay So, Ting Cao, Fan Yang, Mao Yang.* Arxiv 2024. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/SeerAttention)](https://github.com/microsoft/SeerAttention)

22. [**Stuffed Mamba: State Collapse and State Capacity of RNN-Based Long-Context Modeling.**](https://arxiv.org/abs/2410.07145) *Yingfa Chen, Xinrong Zhang, Shengding Hu, Xu Han, Zhiyuan Liu, Maosong Sun.* Arxiv 2024. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/thunlp/stuffed-mamba)](https://github.com/thunlp/stuffed-mamba)

23. [**Taipan: Efficient and Expressive State Space Language Models with Selective Attention.**](https://arxiv.org/abs/2410.18572) *Chien Van Nguyen, Huy Huu Nguyen, Thang M. Pham, Ruiyi Zhang, Hanieh Deilamsalehy, Puneet Mathur, Ryan A. Rossi, Trung Bui, Viet Dac Lai, Franck Dernoncourt, Thien Huu Nguyen.* Arxiv 2024.

24. [**Jamba: A Hybrid Transformer-Mamba Language Model.**](https://arxiv.org/abs/2403.19887) *Opher Lieber, Barak Lenz, Hofit Bata, Gal Cohen, Jhonathan Osin, Itay Dalmedigos, Erez Safahi, Shaked Meirom, Yonatan Belinkov, Shai Shalev-Shwartz, Omri Abend, Raz Alon, Tomer Asida, Amir Bergman, Roman Glozman, Michael Gokhman, Avashalom Manevich, Nir Ratner, Noam Rozen, Erez Shwartz, Mor Zusman, Yoav Shoham.* Arxiv 2024.

25. [**Megalodon: Efficient LLM Pretraining and Inference with Unlimited Context Length.**](https://arxiv.org/abs/2404.08801) *Xuezhe Ma, Xiaomeng Yang, Wenhan Xiong, Beidi Chen, Lili Yu, Hao Zhang, Jonathan May, Luke Zettlemoyer, Omer Levy, Chunting Zhou.* Arxiv 2024. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/XuezheMax/megalodon](https://github.com/XuezheMax/megalodon)

26. [**An Empirical Study of Mamba-based Language Models.**](https://arxiv.org/abs/2406.07887) *Roger Waleffe, Wonmin Byeon, Duncan Riach, Brandon Norick, Vijay Korthikanti, Tri Dao, Albert Gu, Ali Hatamizadeh, Sudhakar Singh, Deepak Narayanan, Garvit Kulshreshtha, Vartika Singh, Jared Casper, Jan Kautz, Mohammad Shoeybi, Bryan Catanzaro.* Arxiv 2024. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/NVIDIA/Megatron-LM)](https://github.com/NVIDIA/Megatron-LM/tree/ssm/examples/mamba)

27. [**Samba: Simple Hybrid State Space Models for Efficient Unlimited Context Language Modeling.**](https://arxiv.org/abs/2406.07522) *Liliang Ren, Yang Liu, Yadong Lu, Yelong Shen, Chen Liang, Weizhu Chen.* Arxiv 2024. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/Samba)](https://github.com/microsoft/Samba)

28. [**ReMamba: Equip Mamba with Effective Long-Sequence Modeling.**](https://arxiv.org/abs/2408.15496) *Danlong Yuan, Jiahao Liu, Bei Li, Huishuai Zhang, Jingang Wang, Xunliang Cai, Dongyan Zhao.* Arxiv 2024.

29. [**Native Sparse Attention: Hardware-Aligned and Natively Trainable Sparse Attention.**](https://arxiv.org/abs/2502.11089) *Jingyang Yuan, Huazuo Gao, Damai Dai, Junyu Luo, Liang Zhao, Zhengyan Zhang, Zhenda Xie, Y. X. Wei, Lean Wang, Zhiping Xiao, Yuqing Wang, Chong Ruan, Ming Zhang, Wenfeng Liang, Wangding Zeng.* Arxiv 2025.

30. [**MoBA: Mixture of Block Attention for Long-Context LLMs.**](https://arxiv.org/abs/2502.13189) *Enzhe Lu, Zhejun Jiang, Jingyuan Liu, Yulun Du, Tao Jiang, Chao Hong, Shaowei Liu, Weiran He, Enming Yuan, Yuzhi Wang, Zhiqi Huang, Huan Yuan, Suting Xu, Xinran Xu, Guokun Lai, Yanru Chen, Huabin Zheng, Junjie Yan, Jianlin Su, Yuxin Wu, Neo Y. Zhang, Zhilin Yang, Xinyu Zhou, Mingxing Zhang, Jiezhong Qiu.* Arxiv 2025. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/MoonshotAI/MoBA)](https://github.com/MoonshotAI/MoBA)

31. [**MiniMax-01: Scaling Foundation Models with Lightning Attention.**](https://arxiv.org/abs/2501.08313) *MiniMax, Aonian Li, Bangwei Gong, Bo Yang, Boji Shan, Chang Liu, Cheng Zhu, Chunhao Zhang, Congchao Guo, Da Chen, Dong Li, Enwei Jiao, Gengxin Li, Guojun Zhang, Haohai Sun, Houze Dong, Jiadai Zhu, Jiaqi Zhuang, Jiayuan Song, Jin Zhu, Jingtao Han, Jingyang Li, Junbin Xie, Junhao Xu, Junjie Yan, Kaishun Zhang, Kecheng Xiao, Kexi Kang, Le Han, Leyang Wang, Lianfei Yu, Liheng Feng, Lin Zheng, Linbo Chai, Long Xing, Meizhi Ju, Mingyuan Chi, Mozhi Zhang, Peikai Huang, Pengcheng Niu, Pengfei Li, Pengyu Zhao, Qi Yang, Qidi Xu, Qiexiang Wang, Qin Wang, Qiuhui Li, Ruitao Leng, Shengmin Shi, Shuqi Yu, Sichen Li, Songquan Zhu, Tao Huang, Tianrun Liang, Weigao Sun, Weixuan Sun, Weiyu Cheng, Wenkai Li, Xiangjun Song, Xiao Su, Xiaodong Han, Xinjie Zhang, Xinzhu Hou, Xu Min, Xun Zou, Xuyang Shen, Yan Gong, Yingjie Zhu, Yipeng Zhou, Yiran Zhong, Yongyi Hu, Yuanxiang Fan, Yue Yu, Yufeng Yang, Yuhao Li, Yunan Huang, Yunji Li, Yunpeng Huang, Yunzhi Xu, Yuxin Mao, Zehan Li, Zekang Li, Zewei Tao, Zewen Ying, Zhaoyang Cong, Zhen Qin, Zhenhua Fan, Zhihang Yu, Zhuo Jiang, Zijia Wu.* Arxiv 2025. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/MiniMax-AI/MiniMax-01)](https://github.com/MiniMax-AI/MiniMax-01)

32. [**Can Mamba Learn How To Learn? A Comparative Study on In-Context Learning Tasks.**](https://arxiv.org/abs/2402.04248) *Jongho Park and Jaeseung Park and Zheyang Xiong and Nayoung Lee and Jaewoong Cho and Samet Oymak and Kangwook Lee and Dimitris Papailiopoulos*. Arxiv 2024

33. [**A new approach to linear filtering and prediction problems.**]( http://ieeexplore.ieee.org/document/5311910)  *Basar, Tamer*. IEEE 2001

34. [**Fast and Accurate Deep Network Learning by Exponential Linear Units (ELUs).**](https://arxiv.org/abs/1511.07289) *Djork-Arné Clevert, Thomas Unterthiner, Sepp Hochreiter*. Arxiv 2016

35. [**Neural Discrete Representation Learning.**](https://arxiv.org/abs/1711.00937) *Aaron van den Oord, Oriol Vinyals, Koray Kavukcuoglu*. Arxiv 2018

36. [**Improving spiking dynamical networks: Accurate delays, higher-order synapses, and time cells.**](https://ieeexplore.ieee.org/abstract/document/8294070)  *Voelker, Aaron R and Eliasmith, Chris*. IEEE 2018

37. [**Improving language understanding by generative pre-training.**](https://www.mikecaptain.com/resources/pdf/GPT-1.pdf)  *Radford, Alec and Narasimhan, Karthik and Salimans, Tim and Sutskever, Ilya and others*. mikecaptain 2018

38. [**Transformer-XL: Attentive Language Models Beyond a Fixed-Length Context.**](https://arxiv.org/abs/1901.02860) *Zihang Dai, Zhilin Yang, Yiming Yang, Jaime Carbonell, Quoc V. Le, Ruslan Salakhutdinov*. Arxiv 2019

39. [**Memformer: The Memory-Augmented Transformer.**](https://arxiv.org/abs/2010.06891) *Qingyang Wu, Zhenzhong Lan, Jing Gu, Zhou Yu*. Arxiv 2020

40. [**Linformer: Self-Attention with Linear Complexity.**](https://arxiv.org/abs/2006.04768) *Sinong Wang, Belinda Z. Li, Madian Khabsa, Han Fang, Hao Ma*. Arxiv 2020

41. [**Combining recurrent, convolutional, and continuous-time models with linear state space layers.**](https://arxiv.org/abs/2110.13985)  *Albert Gu and Isys Johnson and Karan Goel and Khaled Saab and Tri Dao and Atri Rudra and Christopher Ré*. Arxiv 2021

42. [**Nystr\"omformer: A Nystr\"om-Based Algorithm for Approximating Self-Attention.**](https://arxiv.org/abs/2102.03902) *Yunyang Xiong, Zhanpeng Zeng, Rudrasis Chakraborty, Mingxing Tan, Glenn Fung, Yin Li, Vikas Singh*. Arxiv 2021

43. [**Efficient attention: Attention with linear complexities.**](https://arxiv.org/abs/1812.01243)  *Zhuoran Shen and Mingyuan Zhang and Haiyu Zhao and Shuai Yi and Hongsheng Li*. Arxiv 2024

44. [**{ERNIE-SPARSE:} Learning Hierarchical Efficient Transformer Through Regularized Self-Attention.**](https://arxiv.org/abs/2203.12276)  *Yang Liu and Jiaxiang Liu and Li Chen and Yuxiang Lu and Shikun Feng and Zhida Feng and Yu Sun and Hao Tian and Hua Wu and Haifeng Wang*. Arxiv 2022

45. [**cosFormer: Rethinking Softmax in Attention.**](https://arxiv.org/abs/2202.08791) *Zhen Qin, Weixuan Sun, Hui Deng, Dongxu Li, Yunshen Wei, Baohong Lv, Junjie Yan, Lingpeng Kong, Yiran Zhong*. Arxiv 2022

46. [**Rethinking Attention with Performers.**](https://arxiv.org/abs/2009.14794) *Krzysztof Choromanski, Valerii Likhosherstov, David Dohan, Xingyou Song, Andreea Gane, Tamas Sarlos, Peter Hawkins, Jared Davis, Afroz Mohiuddin, Lukasz Kaiser, David Belanger, Lucy Colwell, Adrian Weller*. Arxiv 2022

47. [**Multi-head state space model for speech recognition.**](https://arxiv.org/abs/2305.12498)  *Yassir Fathullah and Chunyang Wu and Yuan Shangguan and Junteng Jia and Wenhan Xiong and Jay Mahadeokar and Chunxi Liu and Yangyang Shi and Ozlem Kalinli and Mike Seltzer and Mark J. F. Gales*. Arxiv 2023

48. [**Attention Is All You Need.**](https://arxiv.org/abs/1706.03762) *Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Lukasz Kaiser, Illia Polosukhin*. Arxiv 2023

49. [**Retentive Network: A Successor to Transformer for Large Language Models.**](https://arxiv.org/abs/2307.08621) *Yutao Sun, Li Dong, Shaohan Huang, Shuming Ma, Yuqing Xia, Jilong Xue, Jianyong Wang, Furu Wei*. Arxiv 2023

50. [**Mamba: Linear-time sequence modeling with selective state spaces.**](https://arxiv.org/abs/2312.00752)  *Albert Gu and Tri Dao*. Arxiv 2024

51. [**Scaling Transformer to 1M tokens and beyond with {RMT}.**](https://arxiv.org/abs/2304.11062)  *Aydar Bulatov and Yuri Kuratov and Yermek Kapushev and Mikhail S. Burtsev*. Arxiv 2024

52. [**FLatten Transformer: Vision Transformer using Focused Linear Attention.**](https://arxiv.org/abs/2308.00442) *Dongchen Han, Xuran Pan, Yizeng Han, Shiji Song, Gao Huang*. Arxiv 2023

53. [**{TRAMS:} Training-free Memory Selection for Long-range Language Modeling.**](https://arxiv.org/abs/2310.15494)  *Haofei Yu and Cunxiang Wang and Yue Zhang and Wei Bi*. Arxiv 2023

54. [**Segmented Recurrent Transformer: An Efficient Sequence-to-Sequence Model.**](https://arxiv.org/abs/2305.16340)  *Yinghan Long and Sayeed Shafayet Chowdhury and Kaushik Roy*. Arxiv 2023

55. [**Leave No Context Behind: Efficient Infinite Context Transformers with Infini-attention.**](https://arxiv.org/abs/2404.07143) *Tsendsuren Munkhdalai, Manaal Faruqui, Siddharth Gopal.* Arxiv 2024.

56. [**Transformer-VQ: Linear-Time Transformers via Vector Quantization.**](https://arxiv.org/abs/2309.16354) *Lucas D. Lingle*. Arxiv 2024

57. [**Stuffed mamba: State collapse and state capacity of rnn-based long-context modeling.**](https://arxiv.org/abs/2410.07145)  *Yingfa Chen and Xinrong Zhang and Shengding Hu and Xu Han and Zhiyuan Liu and Maosong Sun*. Arxiv 2024

58. [**Transformers are SSMs: Generalized models and efficient algorithms through structured state space duality.**](https://arxiv.org/abs/2405.21060)  *Tri Dao and Albert Gu*. Arxiv 2024

59. [**Block-state transformers.**](https://arxiv.org/abs/2306.09539)  *Mahan Fathi and Jonathan Pilault and Orhan Firat and Christopher Pal and Pierre-Luc Bacon and Ross Goroshin*. Arxiv 2023

60. [**Jamba: A hybrid transformer-mamba language model.**](https://arxiv.org/abs/2403.19887)  *Opher Lieber and Barak Lenz and Hofit Bata and Gal Cohen and Jhonathan Osin and Itay Dalmedigos and Erez Safahi and Shaked Meirom and Yonatan Belinkov and Shai Shalev-Shwartz and Omri Abend and Raz Alon and Tomer Asida and Amir Bergman and Roman Glozman and Michael Gokhman and Avashalom Manevich and Nir Ratner and Noam Rozen and Erez Shwartz and Mor Zusman and Yoav Shoham*. Arxiv 2024

61. [**Extensible Embedding: {A} Flexible Multipler For LLM's Context Length.**](https://arxiv.org/abs/2402.11577)  *Ninglu Shao and Shitao Xiao and Zheng Liu and Peitian Zhang*. Arxiv 2024

62. [**DeciMamba: Exploring the Length Extrapolation Potential of Mamba.**](https://arxiv.org/abs/2406.14528) *Assaf Ben-Kish, Itamar Zimerman, Shady Abu-Hussein, Nadav Cohen, Amir Globerson, Lior Wolf, Raja Giryes*. Arxiv 2024

63. [**CORM: Cache Optimization with Recent Message for Large Language Model Inference.**](https://arxiv.org/abs/2404.15949) *Jincheng Dai, Zhuowei Huang, Haiyun Jiang, Chen Chen, Deng Cai, Wei Bi, Shuming Shi*. Arxiv 2024

#### Hybrid Architecture

1. [**C4AI Command R7B: A 7 Billion Parameter Multilingual Model.**](https://huggingface.co/CohereForAI/c4ai-command-r7b-12-2024) *Cohere, Cohere For AI*. Arxiv 2024

2. [**Jamba: A hybrid transformer-mamba language model.**](https://arxiv.org/abs/2403.19887)  *Opher Lieber and Barak Lenz and Hofit Bata and Gal Cohen and Jhonathan Osin and Itay Dalmedigos and Erez Safahi and Shaked Meirom and Yonatan Belinkov and Shai Shalev-Shwartz and Omri Abend and Raz Alon and Tomer Asida and Amir Bergman and Roman Glozman and Michael Gokhman and Avashalom Manevich and Nir Ratner and Noam Rozen and Erez Shwartz and Mor Zusman and Yoav Shoham*. Arxiv 2024

3. [**Hymba: A hybrid-head architecture for small language models.**](https://arxiv.org/abs/2411.13676)  *Xin Dong and Yonggan Fu and Shizhe Diao and Wonmin Byeon and Zijia Chen and Ameya Sunil Mahabaleshwarkar and Shih-Yang Liu and Matthijs Van Keirsbilck and Min-Hung Chen and Yoshi Suhara and Yingyan Lin and Jan Kautz and Pavlo Molchanov*. Arxiv 2024

4. [**Zamba: A compact 7b ssm hybrid model.**](https://arxiv.org/abs/2405.16712)  *Paolo Glorioso and Quentin Anthony and Yury Tokpanov and James Whittington and Jonathan Pilault and Adam Ibrahim and Beren Millidge*. Arxiv 2024

5. [**Goldfinch: High performance rwkv/transformer hybrid with linear pre-fill and extreme kv-cache compression.**](https://arxiv.org/abs/2407.12077) *Daniel Goldstein and Fares Obeid and Eric Alcaide and Guangyu Song and Eugene Cheah*. Arxiv 2024

6. [**Gemma 2: Improving open language models at a practical size.**](https://arxiv.org/abs/2408.00118)  *Gemma Team and Morgane Riviere and Shreya Pathak and Pier Giuseppe Sessa and Cassidy Hardin and Surya Bhupatiraju and Léonard Hussenot and Thomas Mesnard and Bobak Shahriari and Alexandre Ramé and Johan Ferret and Peter Liu and Pouya Tafti and Abe Friesen and Michelle Casbon and Sabela Ramos and Ravin Kumar and Charline Le Lan and Sammy Jerome and Anton Tsitsulin and Nino Vieillard and Piotr Stanczyk and Sertan Girgin and Nikola Momchev and Matt Hoffman and Shantanu Thakoor and Jean-Bastien Grill and Behnam Neyshabur and Olivier Bachem and Alanna Walton and Aliaksei Severyn and Alicia Parrish and Aliya Ahmad and Allen Hutchison and Alvin Abdagic and Amanda Carl and Amy Shen and Andy Brock and Andy Coenen and Anthony Laforge and Antonia Paterson and Ben Bastian and Bilal Piot and Bo Wu and Brandon Royal and Charlie Chen and Chintu Kumar and Chris Perry and Chris Welty and Christopher A. Choquette-Choo and Danila Sinopalnikov and David Weinberger and Dimple Vijaykumar and Dominika Rogozińska and Dustin Herbison and Elisa Bandy and Emma Wang and Eric Noland and Erica Moreira and Evan Senter and Evgenii Eltyshev and Francesco Visin and Gabriel Rasskin and Gary Wei and Glenn Cameron and Gus Martins and Hadi Hashemi and Hanna Klimczak-Plucińska and Harleen Batra and Harsh Dhand and Ivan Nardini and Jacinda Mein and Jack Zhou and James Svensson and Jeff Stanway and Jetha Chan and Jin Peng Zhou and Joana Carrasqueira and Joana Iljazi and Jocelyn Becker and Joe Fernandez and Joost van Amersfoort and Josh Gordon and Josh Lipschultz and Josh Newlan and Ju-yeong Ji and Kareem Mohamed and Kartikeya Badola and Kat Black and Katie Millican and Keelin McDonell and Kelvin Nguyen and Kiranbir Sodhia and Kish Greene and Lars Lowe Sjoesund and Lauren Usui and Laurent Sifre and Lena Heuermann and Leticia Lago and Lilly McNealus and Livio Baldini Soares and Logan Kilpatrick and Lucas Dixon and Luciano Martins and Machel Reid and Manvinder Singh and Mark Iverson and Martin Görner and Mat Velloso and Mateo Wirth and Matt Davidow and Matt Miller and Matthew Rahtz and Matthew Watson and Meg Risdal and Mehran Kazemi and Michael Moynihan and Ming Zhang and Minsuk Kahng and Minwoo Park and Mofi Rahman and Mohit Khatwani and Natalie Dao and Nenshad Bardoliwalla and Nesh Devanathan and Neta Dumai and Nilay Chauhan and Oscar Wahltinez and Pankil Botarda and Parker Barnes and Paul Barham and Paul Michel and Pengchong Jin and Petko Georgiev and Phil Culliton and Pradeep Kuppala and Ramona Comanescu and Ramona Merhej and Reena Jana and Reza Ardeshir Rokni and Rishabh Agarwal and Ryan Mullins and Samaneh Saadat and Sara Mc Carthy and Sarah Cogan and Sarah Perrin and Sébastien M. R. Arnold and Sebastian Krause and Shengyang Dai and Shruti Garg and Shruti Sheth and Sue Ronstrom and Susan Chan and Timothy Jordan and Ting Yu and Tom Eccles and Tom Hennigan and Tomas Kocisky and Tulsee Doshi and Vihan Jain and Vikas Yadav and Vilobh Meshram and Vishal Dharmadhikari and Warren Barkley and Wei Wei and Wenming Ye and Woohyun Han and Woosuk Kwon and Xiang Xu and Zhe Shen and Zhitao Gong and Zichuan Wei and Victor Cotruta and Phoebe Kirk and Anand Rao and Minh Giang and Ludovic Peran and Tris Warkentin and Eli Collins and Joelle Barral and Zoubin Ghahramani and Raia Hadsell and D. Sculley and Jeanine Banks and Anca Dragan and Slav Petrov and Oriol Vinyals and Jeff Dean and Demis Hassabis and Koray Kavukcuoglu and Clement Farabet and Elena Buchatskaya and Sebastian Borgeaud and Noah Fiedel and Armand Joulin and Kathleen Kenealy and Robert Dadashi and Alek Andreev*. Arxiv 2024

7. [**Jamba-1.5: Hybrid transformer-mamba models at scale.**](https://arxiv.org/abs/2408.12570)  *Jamba Team and Barak Lenz and Alan Arazi and Amir Bergman and Avshalom Manevich and Barak Peleg and Ben Aviram and Chen Almagor and Clara Fridman and Dan Padnos and Daniel Gissin and Daniel Jannai and Dor Muhlgay and Dor Zimberg and Edden M Gerber and Elad Dolev and Eran Krakovsky and Erez Safahi and Erez Schwartz and Gal Cohen and Gal Shachaf and Haim Rozenblum and Hofit Bata and Ido Blass and Inbal Magar and Itay Dalmedigos and Jhonathan Osin and Julie Fadlon and Maria Rozman and Matan Danos and Michael Gokhman and Mor Zusman and Naama Gidron and Nir Ratner and Noam Gat and Noam Rozen and Oded Fried and Ohad Leshno and Omer Antverg and Omri Abend and Opher Lieber and Or Dagan and Orit Cohavi and Raz Alon and Ro'i Belson and Roi Cohen and Rom Gilad and Roman Glozman and Shahar Lev and Shaked Meirom and Tal Delbari and Tal Ness and Tomer Asida and Tom Ben Gal and Tom Braude and Uriya Pumerantz and Yehoshua Cohen and Yonatan Belinkov and Yuval Globerson and Yuval Peleg Levy and Yoav Shoham*. Arxiv 2024

8. [**RecurrentGemma: Moving Past Transformers for Efficient Open Language Models.**](https://arxiv.org/abs/2404.07839)  *Aleksandar Botev and Soham De and Samuel L Smith and Anushan Fernando and George-Cristian Muraru and Ruba Haroun and Leonard Berrada and Razvan Pascanu and Pier Giuseppe Sessa and Robert Dadashi and Léonard Hussenot and Johan Ferret and Sertan Girgin and Olivier Bachem and Alek Andreev and Kathleen Kenealy and Thomas Mesnard and Cassidy Hardin and Surya Bhupatiraju and Shreya Pathak and Laurent Sifre and Morgane Rivière and Mihir Sanjay Kale and Juliette Love and Pouya Tafti and Armand Joulin and Noah Fiedel and Evan Senter and Yutian Chen and Srivatsan Srinivasan and Guillaume Desjardins and David Budden and Arnaud Doucet and Sharad Vikram and Adam Paszke and Trevor Gale and Sebastian Borgeaud and Charlie Chen and Andy Brock and Antonia Paterson and Jenny Brennan and Meg Risdal and Raj Gundluru and Nesh Devanathan and Paul Mooney and Nilay Chauhan and Phil Culliton and Luiz Gustavo Martins and Elisa Bandy and David Huntsperger and Glenn Cameron and Arthur Zucker and Tris Warkentin and Ludovic Peran and Minh Giang and Zoubin Ghahramani and Clément Farabet and Koray Kavukcuoglu and Demis Hassabis and Raia Hadsell and Yee Whye Teh and Nando de Frietas*. Arxiv 2024

9. [**The Zamba2 Suite: Technical Report.**](https://arxiv.org/abs/2411.15242)  *Paolo Glorioso and Quentin Anthony and Yury Tokpanov and Anna Golubeva and Vasudev Shyam and James Whittington and Jonathan Pilault and Beren Millidge*. Arxiv 2024

10. [**You only cache once: Decoder-decoder architectures for language models.**](https://arxiv.org/abs/2405.05254)  *Yutao Sun and Li Dong and Yi Zhu and Shaohan Huang and Wenhui Wang and Shuming Ma and Quanlu Zhang and Jianyong Wang and Furu Wei*. Arxiv 2024

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

1. [**ELI5: Long form question answering.**](https://arxiv.org/abs/1907.09190) *Fan, Angela and Jernite, Yacine and Perez, Ethan and Grangier, David and Weston, Jason and Auli, Michael.* Arxiv 2019.

2. [**Ms marco: A human-generated machine reading comprehension dataset.**](https://arxiv.org/abs/1611.09268) *Nguyen, Tri and Rosenberg, Mir and Song, Xia and Gao, Jianfeng and Tiwary, Saurabh and Majumder, Rangan and Deng, Li.* Arxiv 2016.

3. [**Expertqa: Expert-curated questions and attributed answers.**](https://arxiv.org/abs/2309.07852) *Malaviya, Chaitanya and Lee, Subin and Chen, Sihao and Sieber, Elizabeth and Yatskar, Mark and Roth, Dan.* NAACL 2024.

4. [**Proxyqa: An alternative framework for evaluating long-form text generation with large language models.**](https://arxiv.org/abs/2401.15042) *Tan, Haochen and Guo, Zhijiang and Shi, Zhan and Xu, Lu and Liu, Zhili and Feng, Yunlong and Li, Xiaoguang and Wang, Yasheng and Shang, Lifeng and Liu, Qun and others.* ACL 2024

5. [**LongGenBench: Long-context Generation Benchmark.**](https://arxiv.org/abs/2410.04199) *Xiang Liu, Peijie Dong, Xuming Hu, Xiaowen Chu.* EMNLP 2024.

6. [**ASQA: Factoid questions meet long-form answers.**](https://arxiv.org/abs/2204.06092) *Stelmakh, Ivan and Luan, Yi and Dhingra, Bhuwan and Chang, Ming-Wei.* EMNLP 2022.

7. [**Qasa: advanced question answering on scientific articles.**](https://proceedings.mlr.press/v202/lee23n.html) *Lee, Yoonjoo and Lee, Kyungjae and Park, Sunghyun and Hwang, Dasol and Kim, Jaehyeon and Lee, Hong-in and Lee, Moontae.* PMLR 2023.

8. [**CLAPNQ: Cohesive Long-form Answers from Passages in Natural Questions for RAG systems.**](https://arxiv.org/abs/2404.02103) *Sara Rosenthal, Avirup Sil, Radu Florian, Salim Roukos.* Arxiv 2024. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/primeqa/clapnq)](https://github.com/primeqa/clapnq)

9. [**LONG2RAG: Evaluating Long-Context \& Long-Form Retrieval-Augmented Generation with Key Point Recall.**](https://arxiv.org/abs/2410.23000) *Qi, Zehan and Xu, Rongwu and Guo, Zhijiang and Wang, Cunxiang and Zhang, Hao and Xu, Wei.* ACL 2024.

10. [**A Benchmark for Long-Form Medical Question Answering.**](https://arxiv.org/abs/2411.09834) *Pedram Hosseini, Jessica M. Sin, Bing Ren, Bryceton G. Thomas, Elnaz Nouri, Ali Farahanchi, Saeed Hassanpour.* NeurIPS 2024. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/lavita-ai/medical-eval-sphere)](https://github.com/lavita-ai/medical-eval-sphere)

11. [**OLAPH: Improving Factuality in Biomedical Long-form Question Answering.**](https://arxiv.org/abs/2405.12701) *Minbyul Jeong, Hyeon Hwang, Chanwoong Yoon, Taewhoo Lee, Jaewoo Kang.* Arxiv 2024. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/dmis-lab/OLAPH)](https://github.com/dmis-lab/OLAPH)

12. [**Factscore: Fine-grained atomic evaluation of factual precision in long form text generation.**](https://arxiv.org/abs/2305.14251) *Min, Sewon and Krishna, Kalpesh and Lyu, Xinxi and Lewis, Mike and Yih, Wen-tau and Koh, Pang Wei and Iyyer, Mohit and Zettlemoyer, Luke and Hajishirzi, Hannaneh.* EMNLP 2023.

13. [**Long-form factuality in large language models.**](https://arxiv.org/abs/2403.18802) *Jerry Wei, Chengrun Yang, Xinying Song, Yifeng Lu, Nathan Hu, Dustin Tran, Daiyi Peng, Ruibo Liu, Da Huang, Cosmo Du, Quoc V. Le.* Arxiv 2024. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/google-deepmind/long-form-factuality)](https://github.com/google-deepmind/long-form-factuality)

14. [**Large Language Models Still Exhibit Bias in Long Text.**](https://arxiv.org/abs/2410.17519) *Wonje Jeung, Dongjae Jeon, Ashkan Yousefpour, Jonghyun Choi.* Arxiv 2024.

15. [**Aquamuse: Automatically generating datasets for query-based multi-document summarization.**](https://arxiv.org/abs/2010.12694) *Kulkarni, Sayali and Chammas, Sheide and Zhu, Wan and Sha, Fei and Ie, Eugene.* Arxiv 2020.

16. [**Multi-News: A Large-Scale Multi-Document Summarization Dataset and Abstractive Hierarchical Model.**](https://arxiv.org/abs/1906.01749) *Fabbri, Alexander Richard and Li, Irene and She, Tianwei and Li, Suyi and Radev, Dragomir.* ACL 2019.

17. [**LCFO: Long Context and Long Form Output Dataset and Benchmarking.**](https://arxiv.org/abs/2412.08268) *Marta R. Costa-jussà, Pierre Andrews, Mariano Coria Meglioli, Joy Chen, Joe Chuang, David Dale, Christophe Ropers, Alexandre Mourachko, Eduardo Sánchez, Holger Schwenk, Tuan Tran, Arina Turkatenko, Carleigh Wood.* Arxiv 2024.

18. [**LongForm: Effective Instruction Tuning with Reverse Instructions.**](https://arxiv.org/abs/2304.08460) *Koksal, Abdullatif and Schick, Timo and Korhonen, Anna and Schutze, Hinrich.* EMNLP 2024.

19. [**Suri: Multi-constraint Instruction Following for Long-form Text Generation.**](https://arxiv.org/abs/2406.19371) *Chau Minh Pham, Simeng Sun, Mohit Iyyer.* EMNLP 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/chtmp223/suri)](https://github.com/chtmp223/suri)

20. [**LongWriter: Unleashing 10,000+ Word Generation from Long Context LLMs.**](https://arxiv.org/abs/2408.07055) *Yushi Bai, Jiajie Zhang, Xin Lv, Linzhi Zheng, Siqi Zhu, Lei Hou, Yuxiao Dong, Jie Tang, Juanzi Li.* Arxiv 2024. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/THUDM/LongWriter)](https://github.com/THUDM/LongWriter)

21. [**Language Models can Self-Lengthen to Generate Long Texts.**](https://arxiv.org/abs/2410.23933) *Shanghaoran Quan, Tianyi Tang, Bowen Yu, An Yang, Dayiheng Liu, Bofei Gao, Jianhong Tu, Yichang Zhang, Jingren Zhou, Junyang Lin.* Arxiv 2024. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/QwenLM/Self-Lengthen)](https://github.com/QwenLM/Self-Lengthen)

22. [**LOT: A story-centric benchmark for evaluating Chinese long text understanding and generation.**](https://arxiv.org/abs/2108.12960) *Guan, Jian and Feng, Zhuoer and Chen, Yamei and He, Ruilin and Mao, Xiaoxi and Fan, Changjie and Huang, Minlie.* TACL 2022.

23. [**Longlamp: A benchmark for personalized long-form text generation.**](https://arxiv.org/abs/2407.11016) *Kumar, Ishita and Viswanathan, Snigdha and Yerra, Sushrita and Salemi, Alireza and Rossi, Ryan A and Dernoncourt, Franck and Deilamsalehy, Hanieh and Chen, Xiang and Zhang, Ruiyi and Agarwal, Shubham and others.* Arxiv 2o24.

24. [**DOLOMITES: Domain-Specific Long-Form Methodical Tasks.**](https://arxiv.org/abs/2405.05938) *Chaitanya Malaviya, Priyanka Agrawal, Kuzman Ganchev, Pranesh Srinivasan, Fantine Huot, Jonathan Berant, Mark Yatskar, Dipanjan Das, Mirella Lapata, Chris Alberti.* Arxiv 2024.

25. [**LongGenBench: Benchmarking Long-Form Generation in Long Context LLMs.**](https://arxiv.org/abs/2409.02076) *Yuhao Wu, Ming Shan Hee, Zhiqing Hu, Roy Ka-Wei Lee.* Arxiv 2024. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/mozhu621/LongGenBench)](https://github.com/mozhu621/LongGenBench/)

26. [**LongProc: Benchmarking Long-Context Language Models on Long Procedural Generation.**](https://arxiv.org/abs/2501.05414) *Xi Ye, Fangcong Yin, Yinghui He, Joie Zhang, Howard Yen, Tianyu Gao, Greg Durrett, Danqi Chen.* Arxiv 2025. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/princeton-pli/LongProc)](https://github.com/princeton-pli/LongProc) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://princeton-pli.github.io/LongProc/)

27. [**Hellobench: Evaluating long text generation capabilities of large language models.**](https://arxiv.org/abs/2409.16191) *Que, Haoran and Duan, Feiyu and He, Liqun and Mou, Yutao and Zhou, Wangchunshu and Liu, Jiaheng and Rong, Wenge and Wang, Zekun Moore and Yang, Jian and Zhang, Ge and others.* Arxiv 2024.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://github.com/Quehry/HelloBench/)](https://github.com/Quehry/HelloBench/)

28. [**The FACTS Grounding Leaderboard: Benchmarking LLMs' Ability to Ground Responses to Long-Form Input.**](https://arxiv.org/abs/2501.03200) *Alon Jacovi, Andrew Wang, Chris Alberti, Connie Tao, Jon Lipovetz, Kate Olszewska, Lukas Haas, Michelle Liu, Nate Keating, Adam Bloniarz, Carl Saroufim, Corey Fry, Dror Marcus, Doron Kukliansky, Gaurav Singh Tomar, James Swirhun, Jinwei Xing, Lily Wang, Madhu Gurumurthy, Michael Aaron, Moran Ambar, Rachana Fellinger, Rui Wang, Zizhao Zhang, Sasha Goldshtein, Dipanjan Das.* Arxiv 2025. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://www.kaggle.com/facts-leaderboard)

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