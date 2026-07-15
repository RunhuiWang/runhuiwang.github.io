---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I'm an Applied Scientist and technical lead at **AWS**, working on reinforcement learning for LLM post-training: GSPO, GRPO, DAPO, and RLAIF at frontier scale, rubric-based reward design with LLM judges, and reward-hacking mitigation. I build the training and inference systems underneath on NVIDIA Blackwell and Hopper clusters (verl, vLLM, FSDP, custom kernels), with a focus on training-inference consistency and quantization numerics. I also work on mechanistic interpretability, training per-layer transcoders for activation-level model steering. Previously, I built and shipped billion-scale ML products for entity resolution and retrieval.

Before AWS I completed my Ph.D. at **Rutgers University** under [Prof. Yongfeng Zhang](http://yongfeng.me/) and [Prof. Dong Deng](https://people.cs.rutgers.edu/~dd903/), focused on LLMs for data integration, retrieval, and similarity search. M.Phil. at the **University of Queensland** with [Prof. Xiaofang Zhou](http://staff.itee.uq.edu.au/zxf/) (IEEE Fellow) and [Prof. Sibo Wang](http://www1.se.cuhk.edu.hk/~swang/). B.S. from **Peking University**.

I'm interested in the hardware-software seam of LLM training and inference — RL post-training systems, kernels, and serving infrastructure. I previously interned at AWS (Applied Scientist, 2022) and at [Megagon Labs](https://megagon.ai/) (Research Scientist, 2021), mentored by [Dr. Yuliang Li](https://oi02lyl.github.io/) and [Dr. Jin Wang](http://yellowstone.cs.ucla.edu/~jinwang/).


# Research interests

- Reinforcement learning for LLM post-training (GSPO, GRPO, DAPO, RLAIF) <br>
- Reward design and evaluation: LLM judges, rubric rewards, reward-hacking mitigation <br>
- Training and inference systems for large-scale RL <br>
- Mechanistic interpretability and activation-level model steering <br>
- Agentic RL and on-policy distillation <br>
- Data-centric ML: entity resolution, retrieval, similarity search <br>

# Open Source

- **[CSR Bench](https://github.com/amazon-science/CSR-Bench)** - Multi-Agent system for automatic computer science research repo exploration (NAACL 2025 Oral)
- **[SkillsBench](https://github.com/benchflow-ai/skillsbench)** - Benchmark for evaluating how well AI agents leverage skills to perform specialized workflows. Independent Contributor. [[arXiv](https://arxiv.org/abs/2602.12670)]
- **[Sudowoodo](https://github.com/megagonlabs/sudowoodo)** - Contrastive self-supervised learning framework for multi-purpose data integration (entity matching, data cleaning, column type detection). ICDE 2023.
- **[DeltaPQ](https://github.com/RunhuiWang/DeltaPQ)** - Lossless product quantization compression for similarity search (VLDB 2021)
- **[PAFO](https://github.com/RunhuiWang/PAFO-release)** - Parallel approximate personalized PageRank (VLDB Journal 2019)
- **[Declarative Data Pipeline](https://github.com/amazon-science/DeclarativeDataPipeline)** - A framework for efficient and scalable ML service development


# Publications

1. [SkillsBench: Benchmarking How Well Agent Skills Work Across Diverse Tasks](https://arxiv.org/abs/2602.12670) ***arXiv 2026***  
<!-- TODO: add author line reflecting your position among the co-authors -->

2. [CSR-Bench: Benchmarking LLM Agents in Deployment of Computer Science Research Repositories](https://arxiv.org/abs/2502.06111) ***NAACL 2025 Oral***  
Yijia Xiao, **Runhui Wang**, Luyang Kong, Davor Golac, Wei Wang.

3. [Language is All a Graph Needs](https://arxiv.org/abs/2308.07134) ***EACL 2024 Findings***  
Ruosong Ye, Caiqi Zhang, **Runhui Wang**, Shuyuan Xu, Yongfeng Zhang.

4. [BPID: A Benchmark for Personal Identity Deduplication](https://aclanthology.org/2024.emnlp-industry.40/) ***EMNLP 2024***  
 **Runhui Wang**\*, Yefan Tao\*, Adit Krishnan\*, Luyang Kong\*, Xuanqing Liu, Yuqian Deng, Yunzhao Yang, Henrik Johnson, Andrew Borthwick, Shobhit Gupta, Aditi Sinha Gundlapalli, Davor Golac.

5. [Large Language Models for Entity Blocking: A Reproducibility Study](https://aclanthology.org/2024.naacl-long.483/) ***NAACL 2024***  
 **Runhui Wang**, Yongfeng Zhang.

6. [GRAM: Generative Retrieval Augmented Matching of Data Schemas in the Context of Data Security](https://dl.acm.org/doi/abs/10.1145/3637528.3671602) ***KDD 2024***  
Xuanqing Liu, **Runhui Wang**, Yang Song, Luyang Kong.

7. [Learning from Natural Language Explanations for Generalizable Entity Matching](https://aclanthology.org/2024.emnlp-main.352/) ***EMNLP 2024***  
Somin Wadhwa, Adit Krishnan, **Runhui Wang**, Byron C Wallace, Luyang Kong.

8. [Neural Locality Sensitive Hashing for Entity Blocking](https://epubs.siam.org/doi/10.1137/1.9781611978032.101) ***SDM 2024***  
 **Runhui Wang**, Luyang Kong, Yefan Tao, Andrew Borthwick, Davor Golac, Henrik Johnson, Shadie Hijazi, Dong Deng, Yongfeng Zhang.

9. [Sudowoodo: Contrastive Self-supervised Learning for Multi-purpose Data Integration and Preparation](https://arxiv.org/pdf/2207.04122.pdf) ***ICDE 2023*** · [Code](https://github.com/megagonlabs/sudowoodo)  
 **Runhui Wang**, Yuliang Li, Jin Wang.

### Earlier work

10. [DeltaPQ: Lossless Product Quantization Code Compression for High Dimensional Similarity Search](http://www.vldb.org/pvldb/vol13/p3603-wang.pdf) ***VLDB 2021*** · [Code](https://github.com/RunhuiWang/DeltaPQ)  
 **Runhui Wang**, Dong Deng.

11. [Parallelizing Approximate Single-Source Personalized PageRank Queries on Shared-Memory](https://link.springer.com/article/10.1007/s00778-019-00576-7) ***VLDB Journal 2019*** · [Code](https://github.com/RunhuiWang/PAFO-release)  
 **Runhui Wang**, Sibo Wang, Xiaofang Zhou.

12. [Efficient Algorithms for Approximate Single-Source Personalized PageRank Queries](https://dl.acm.org/doi/10.1145/3360902) ***TODS 2019***  
Sibo Wang, Renchi Yang, **Runhui Wang**, Xiaokui Xiao, Zhewei Wei, Wenqing Lin, Yin Yang, Nan Tang.


Miscellaneous
====
I love sports and enjoy professional trainings. 

Since highschool, I've won championships for multiple provincial badminton competitions, and received the Chinese National Second-level Athelete Certification.

Since college, I've trained myself massively in running and powerlifting:<br>
- powerlifting: 455lbs deadlift, 415 lbs squat, 275lbs bench press<br>
- finished Beijing International Marathon in 4 hours 33 minutes (despite a sprained ankle);<br>
- participated in Nike University Elite Challenge-Wei Ming Relay (May 2015), and won the 3rd Place;<br>
- joined the First World Renowned Universities’ Dragon Boat Competition (Oct 2015), and won the 6th Place in 4000m Race
