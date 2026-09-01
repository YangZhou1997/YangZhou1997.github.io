---
layout: default
--- 

## About

I am an Assistant Professor at UC Davis CS. My office is in Kemper 2127. 
I have equal interests in core systems and ML systems research, e.g., efficient LLMs, GPU communication, heterogeneous computing. 
I am currently working on [UCCL](https://github.com/uccl-project/uccl) [![GitHub Repo stars](https://img.shields.io/github/stars/uccl-project/uccl?style=social)](https://github.com/uccl-project/uccl/stargazers) for GPU communication, with close collaborations between Davis and Berkeley. 

<!-- <span style="color:red;">I will be joining UC Davis CS as an Assistant Professor, starting July 2025.</span> -->
<!-- I have multiple PhD openings at UC Davis (apply [here](https://apply.grad.ucdavis.edu/apply/) by Dec 15, 2024). Feel free to drop me an email if you are interested. 
* UC Davis is ranked 28th in Best National University and 36th in Best Computer Science Schools by US News. 
* UC Davis has a great location: 20min drive from Sacramento (capital of California) and 1.5h from Silicon Valley (Google, Meta, Amazon).
* Perhaps more importantly, it is a 50min drive from the famous Napa Valley (wine) and 2h from the great Lake Tahoe (skiing and more!). -->

I was a PostDoc at UC Berkeley during 2024-2025, advised by [Ion Stoica](https://people.eecs.berkeley.edu/~istoica/) on GPU communication. 
I finished my PhD in Computer Science at Harvard University in 2024, advised by [Minlan Yu](http://minlanyu.seas.harvard.edu/) and [James Mickens](https://mickens.seas.harvard.edu/) on network-application co-design.
I received my B.S. in Computer Science at Peking University in 2018, advised by [Tong Yang](https://yangtonghome.github.io/) on probabilistic data structures and streaming algorithms.
I was supported by a Google PhD Fellowship in Systems and Networking (see my [app materials](./materials/google_fellowship_cv_rs.pdf)). 

## Updates
* June 2026, check the llm-d [blogpost](https://llm-d.ai/blog/networking-for-distributed-inference-llm-d) on networking for distributed inference with the UCCL backend!
* May 2026, LEANN wins MLSys Best Paper Award!
* Mar 2026, both UCCL papers ([UCCL-Tran](https://arxiv.org/pdf/2504.17307) and [UCCL-EP](https://arxiv.org/pdf/2512.19849)) accepted to OSDI'26!
* Feb 2026, check the llm-d [blogpost](https://llm-d.ai/blog/llm-d-v0.5-sustaining-performance-at-scale) on how they use UCCL to achieve resilient networking for KV cache transfer! 
* Jan 2026, LEANN and FCP to appear at MLSys'26!
<!-- * Dec 2025, [UCCL-EP](https://arxiv.org/pdf/2512.19849) for portable expert-parallel communication (AMD, Broadcom, AWS EFA)! -->
<!-- * Dec 2025, UCCL talk at UIUC -->
<!-- * Nov 2025, BlendServe to appear at ASPLOS'26! -->
<!-- * Nov 2025, UCCL talk at Northeastern, UW-Madison -->
<!-- * Oct 2025, UCCL talk at Google network summit, Google NetInfra -->
<!-- * July 2025, UCCL talk at Meta, ByteDance (Seed), SJTU IPADS -->
<!-- * June 2025, UCCL talk at ByteDance (Networking), NVIDIA -->
<!-- * May 2025, UCCL talk at UC Berkeley SkyLab Summer Retreat, Broadcom -->
<!-- * Jan 2025, UCCL talk at UC Berkeley SkyLab Winter Retreat  -->

## Students

* Shuang Ma (2025-now, PhD), from USTC
* Yihan Zhang (2025-now, PhD), from UIUC
* Zhiyi Hu (2026-now, PhD), from HUST then ETH

I also work(ed) with:
* [Jinyao Liu](https://scholar.google.com/citations?user=k6p3fykAAAAJ) (2025-now), Shandong Univ PhD
* Danyang Chen (2025-now), CUHK-Shenzhen undergrad
* [Ziming Mao](https://maoziming.github.io/) (2024-now), UC Berkeley PhD
* [Zhongjie Chen](https://zhongjiechen.github.io/) (2024-now), Tsinghua Univ PhD → MSRA senior researcher
* Xuanlin Jiang (2024), Peking Univ undergrad → Harvard PhD
* Matt Kiley (2023), Harvard College undergrad → Clockwork Systems
* [Yunxi Shen](https://yxshen20.github.io/) (2023-2024), Tsinghua Univ undergrad → Cornell PhD
* [Xingyu Xiang](https://xyxiang7.github.io/) (2023-now), Peking Univ undergrad → Harvard PhD
* Zezhou Wang (2022), Peking Univ undergrad → Univ of Washington PhD

## Publications

2026

* CommBench: Can LLMs Write Correct and Efficient GPU Communication Code?
<br>Shuang Ma, Yuyi Li, Yihan Zhang, Hezhi Xie, Danyang Chen, Shuyang Ji, Ziming Mao, Cheng Ji, Ansha Prashanth, Wenting Yang, Yiran Wang, Chihan Cui, Pei Yu Lin, Ion Stoica, <u>Yang Zhou</u>
<br>[[Arxiv Aug 2026](https://arxiv.org/pdf/2608.04450)]

* ConServe: Harvesting GPUs for Low-Latency and High-Throughput Large Language Model Serving
<br> Yifan Qiao, Shu Anzai, Shan Yu, Haoran Ma, Shuo Yang, Yang Wang, Miryung Kim, Yongji Wu, <u>Yang Zhou</u>, Jiarong Xing, Joseph Gonzalez, Ion Stoica, Harry Xu
<br> [[Arxiv Oct 2024](https://arxiv.org/pdf/2410.01228)]
<br>**ICML 2026**. International Conference on Machine Learning

* UCCL-Zip: Lossless Compression Supercharged GPU Communication
<br>Shuang Ma, ChonLam Lao, Zhiying Xu, Zhuang Wang, Ziming Mao, Delong Meng, Zhen Jia, Jun Wu, Ion Stoica, Yida Wang, <u>Yang Zhou</u>
<br>[[Arxiv April 2026](https://arxiv.org/pdf/2604.17172)]
[[code](https://github.com/uccl-project/uccl)]

* UCCL-EP: Portable Expert-Parallel Communication
<br> Ziming Mao, Yihan Zhang, Chihan Cui, Zhen Huang, Kaichao You, Zhongjie Chen, Zhiying Xu, Zhenyu Gu, Scott Shenker, Costin Raiciu, <u>Yang Zhou</u>, Ion Stoica
<br>[[Arxiv Dec 2025](https://arxiv.org/pdf/2512.19849)]
[[code](https://github.com/uccl-project/uccl)]
<br>Used by [AMD Primus training framework](https://github.com/AMD-AGI/Primus/tree/main/examples/moe_package), [Nvidia NeMo framework](https://docs.nvidia.com/nemo/automodel/latest/apidocs/nemo_automodel/nemo_automodel.components.moe.uccl_ep.html), [Apertus / Swiss AI Initiative](https://github.com/uccl-project/uccl/issues/956), and various AWS teams and customers (Kimi achieves 2x e2e SGLang speedup compared to DeepEP IBRC)
<br>**OSDI 2026**. USENIX Symposium on Operating Systems Design and Implementation

* UCCL-Tran: An Extensible Software Transport Layer for GPU Networking
<br> <u>Yang Zhou</u>\*, Zhongjie Chen\*, Ziming Mao, ChonLam Lao, Shuo Yang, Pravein Govindan Kannan, Xizhi Zhang, Jiaqi Gao, Yilong Zhao, Yongji Wu, Kaichao You, Fengyuan Ren, Zhiying Xu, Costin Raiciu, Ion Stoica
<br>[[Arxiv April 2025](https://arxiv.org/pdf/2504.17307)]
[[homepage](https://uccl-project.github.io/)]
[[slides](https://docs.google.com/presentation/d/1LQxZzxghRmua4FkfQjWu69wXy9hrs9V_tXrXt_DT-F4/edit?usp=sharing)]
[[code](https://github.com/uccl-project/uccl)]
[![GitHub Repo stars](https://img.shields.io/github/stars/uccl-project/uccl?style=social)](https://github.com/uccl-project/uccl/stargazers)
<br> Used by IBM/Red Hat/Google llm-d ([blog1](https://llm-d.ai/blog/llm-d-v0.5-sustaining-performance-at-scale), [blog2](https://llm-d.ai/blog/networking-for-distributed-inference-llm-d)), [Nvidia NIXL](https://github.com/ai-dynamo/nixl/releases/tag/0.9.0), [AMD TheRock](https://github.com/ROCm/TheRock/tree/main/external-builds/uccl)
<br>**OSDI 2026**. USENIX Symposium on Operating Systems Design and Implementation

* Expert-Choice Routing Enables Adaptive Computation in Diffusion Language Models
<br>Shuibai Zhang\*, Caspian Zhuang\*, Chihan Cui\*, Zhihan Yang, Fred Zhangzhi Peng, Yanxin Zhang, Haoyue Bai, Zack Jia, <u>Yang Zhou</u>, Guanhua Chen, Ming Liu
<br>**COLM 2026**. Conference on Language Modeling
<br>[[Arxiv April 2026](https://arxiv.org/pdf/2604.01622)]
[[code](https://github.com/zhangshuibai/EC-DLM)]

* Unleashing Scalable Context Parallelism for Foundation Models Pre-Training via FCP
<br> Yilong Zhao, Xiaonan Nie, Kan Zhu, Shuang Ma, Zhichao Lai, Hongxiang Hao, <u>Yang Zhou</u>, Baris Kasikci, Ion Stoica
<br>**MLSys 2026**. The Conference on Machine Learning and Systems
<br>[[Arxiv May 2026](https://arxiv.org/pdf/2605.08524)]

* LEANN: a Low-Storage Vector Index
<br> Yichuan Wang, Shu Liu, Zhifei Li, Yongji Wu, Ziming Mao, Yilong Zhao, Xiao Yan, Zhiying Xu, <u>Yang Zhou</u>, Ion Stoica, Sewon Min, Matei Zaharia, Joseph E. Gonzalez
<br>**MLSys 2026**. The Conference on Machine Learning and Systems
<br>**ICML 2025 Workshop** on Vector Databases
<br>[[Arxiv June 2025](https://arxiv.org/pdf/2506.08276)]
[[code](https://github.com/yichuan-w/LEANN)]
[![GitHub Repo stars](https://img.shields.io/github/stars/yichuan-w/LEANN?style=social)](https://github.com/yichuan-w/LEANN/stargazers)
<br>**<span style="color:red">MLSys Best Paper Award</span>**

* BlendServe: Optimizing Offline Inference for Auto-regressive Large Models with Resource-aware Batching
<br>Yilong Zhao\*, Shuo Yang\*, Kan Zhu, Lianmin Zheng, Baris Kasikci, Yifan Qiao, <u>Yang Zhou</u>, Jiarong Xing, Ion Stoica
<br>**ASPLOS 2026**
<br>[[Arxiv Nov 2024](https://arxiv.org/pdf/2411.16102)]

* Unlocking Software-defined GPU Fabric Scheduling in the LLM Era
<br>Danyang Chen, Yufeng Gu, Yibo Huang, Chengxuan Pei, Peichun Hua, <u>Yang Zhou</u>, Yunming Xiao
<br>**APSys 2026**. ACM SIGOPS Asia-Pacific Workshop on Systems
<br>[[Paper](paper/gpu-fabric-apsys26.pdf)]

2025

* ShadowServe: Interference-Free KV Cache Fetching for Distributed Prefix Caching
<br> Xingyu Xiang, Raj Joshi, Yuhan Liu, Jiayi Yao, Chenxingyu Zhao, Junchen Jiang, <u>Yang Zhou</u>, Eddie Kohler, Minlan Yu
<br>[[Arxiv Sep 2025](https://arxiv.org/pdf/2509.16857)]

* Towards Efficient and Practical GPU Multitasking in the Era of LLM
<br> Jiarong Xing, Yifan Qiao, Simon Mo, Xingqi Cui, Gur-Eyal Sela, <u>Yang Zhou</u>, Joseph Gonzalez, Ion Stoica
<br>[[Arxiv Aug 2025](https://arxiv.org/pdf/2508.08448)]
[[code](https://github.com/ovg-project)]
[![GitHub Repo stars](https://img.shields.io/github/stars/ovg-project/kvcached?style=social)](https://github.com/ovg-project/kvcached/stargazers)

* Locality-Aware Fair Scheduling in LLM Serving
<br>Shiyi Cao\*, Yichuan Wang\*, Ziming Mao, Pin-Lun Hsu, Liangsheng Yin, Tian Xia, Dacheng Li, Shu Liu, Yineng Zhang, <u>Yang Zhou</u>, Ying Sheng, Joseph Gonzalez, Ion Stoica
<br>[[Arxiv Jan 2025](https://arxiv.org/pdf/2501.14312)]

* Toward Interference-Aware Scheduling for Serverless Functions via eBPF and Meta-Learning
<br>Yifan Zhang, Jianchang Su, Zixu Shen, <u>Yang Zhou</u>, Wei Zhang
<br>**PACMI 2025**. Workshop on Practical Adoption Challenges of ML for Systems
<br>[[paper](paper/emfs-pacmi25.pdf)] 

* Rethinking RPC Communication for Microservices-based Applications
<br>Xiangfeng Zhu, <u>Yang Zhou</u>, Yuyao Wang, Xiangyu Gao, Arvind Krishnamurthy, Sam Kumar, Ratul Mahajan, Danyang Zhuo
<br>**HotOS 2025**. The ACM SIGOPS 20th Workshop on Hot Topics in Operating Systems
<br>[[paper](paper/rethinking-hotos25.pdf)] 

* NEO: Saving GPU Memory Crisis with CPU Offloading for Online LLM Inference
<br>Xuanlin Jiang, <u>Yang Zhou</u>, Shiyi Cao, Ion Stoica, Minlan Yu
<br>**MLSys 2025**. The Conference on Machine Learning and Systems
<br>[[paper](paper/neo_mlsys25.pdf)]
[[slides](slides/neo-mlsys25-slides.pdf)]
[[code](https://github.com/NEO-MLSys25/NEO)]

* eTran: Extensible Kernel Transport with eBPF
<br>Zhongjie Chen, Qingkai Meng, ChonLam Lao, Yifan Liu, Fengyuan Ren, Minlan Yu, <u>Yang Zhou</u>
<br>**NSDI 2025**. USENIX Symposium on Networked Systems Design and Implementation
<br>[[paper](paper/etran-nsdi25.pdf)] 
[[code](https://github.com/eTran-NSDI25/eTran)]

2024

* Post-Training Sparse Attention with Double Sparsity
<br>Shuo Yang, Ying Sheng, Yilong Zhao, Joseph Gonzalez, <u>Yang Zhou</u>, Ion Stoica, Lianmin Zheng
<br>[[Arxiv Aug 2024](https://arxiv.org/pdf/2408.07092)]

PhD and prior work

* SmartNIC Security Isolation in the Cloud with S-NIC
<br><u>Yang Zhou</u>, Mark Wilkening, James Mickens, Minlan Yu
<br>**EuroSys 2024**. European Conference on Computer Systems
<br>[[paper](paper/snic-eurosys24.pdf)] 
[[slides](slides/snic-eurosys24-slides.pdf)]
[[code](https://github.com/SNIC-EuroSys24/SNIC)]

* DINT: Fast In-Kernel Distributed Transactions with eBPF
<br><u>Yang Zhou</u>\*, Xingyu Xiang\*, Matthew Kiley, Sowmya Dharanipragada, Minlan Yu
<br>**NSDI 2024**. USENIX Symposium on Networked Systems Design and Implementation
<br>[[paper](paper/dint-nsdi24.pdf)]
[[slides](slides/dint-nsdi24-slides.pdf)] 
[[talk](https://youtu.be/EgdXrjwBdBA)] 
[[code](https://github.com/DINT-NSDI24/DINT)]

* Electrode: Accelerating Distributed Protocols with eBPF
<br><u>Yang Zhou</u>\*, Zezhou Wang\*, Sowmya Dharanipragada, Minlan Yu
<br>**NSDI 2023**. USENIX Symposium on Networked Systems Design and Implementation
<br>[[paper](paper/electrode-nsdi23.pdf)] 
[[slides](slides/electrode-nsdi23-slides.pdf)] 
[[talk](https://youtu.be/E6qcR2Lb1xE)] 
[[code](https://github.com/Electrode-NSDI23/Electrode)]
<!-- <br> **<span style="color:red">Initial conversations with multiple companies</span>** -->

* Carbink: Fault-Tolerant Far Memory
<br><u>Yang Zhou</u>, Hassan Wassel, Sihang Liu, Jiaqi Gao, James Mickens, Minlan Yu, Chris Kennelly, Paul Turner, David Culler, Hank Levy, Amin Vahdat
<br>**OSDI 2022**. USENIX Symposium on Operating Systems Design and Implementation
<br>[[paper](paper/carbink-osdi22.pdf)] 
[[slides](slides/carbink-osdi22-slides.pdf)]
[[talk](https://youtu.be/PZhqlPyhImE)] 
<!-- <br> **<span style="color:red">Joint patent with Google</span>** -->

* Evolvable Network Telemetry at Facebook
<br><u>Yang Zhou</u>, Ying Zhang, Minlan Yu, Guangyu Wang, Dexter Cao, Eric Sung and Starsky Wong
<br>**NSDI 2022**. USENIX Symposium on Networked Systems Design and Implementation
<br>[[paper](paper/pcat-nsdi22.pdf)] 
[[slides](slides/pcat-nsdi22-slides.pdf)]
[[talk](https://youtu.be/azW4vssu9T0)] 
<!-- <br> **<span style="color:red">Describing production systems and challenges</span>** -->

* On the Evolutionary of Bloom Filter False Positives - An Information Theoretical Approach to Optimizing Bloom Filter Parameters
<br>Zhuochen Fan, Gang Wen, Zhipeng Huang, <u>Yang Zhou</u>, Qiaobin Fu, Tong Yang, Alex X. Liu, Bin Cui
<br>IEEE Transactions on Knowledge and Data Engineering (TKDE) 2022
<br>[[paper](paper/bf-tkde22.pdf)] [[Code](https://github.com/pkufzc/Bloom-Error-TKDE)]

* Pyramid Family: Generic Frameworks for Accurate and Fast Flow Size Measurement
<br>Yuanpeng Li, Xiang Yu, Yilong Yang, <u>Yang Zhou</u>, Tong Yang, Zhuo Ma, Shigang Chen
<br>IEEE/ACM Trasactions on Networking (TON) 2021
<br>[[paper](paper/pyramid_family_ton21.pdf)] 
[[Code](https://github.com/Pyramid-Family /Pyramid-Family)]

* Fast and Accurate Stream Processing by Filtering the Cold.
<br>Tong Yang, Jie Jiang, <u>Yang Zhou</u>, Long He, Jinyang Li, Bin Cui, Steve Uhlig, Xiaoming Li
<br>VLDB Journal 2019
<br>[[paper](paper/filtering_cold_vldbj19.pdf)] 
[[Code](https://github.com/zhouyangpkuer/ColdFilter)]

* Adaptive Measurements using One Elastic Sketch.
<br>Tong Yang, Jie Jiang, Peng Liu, Qun Huang, Junzhi Gong, <u>Yang Zhou</u>, Rui Miao, Xiaoming Li, Steve Uhlig
<br>IEEE/ACM Trasactions on Networking (TON) 2019
<br>[[paper](paper/elastic_ton2019.pdf)] 
[[Code](https://github.com/BlockLiu/ElasticSketchCode)]

* Cold Filter: A Meta-Framework for Faster and More Accurate Stream Processing. 
<br><u>Yang Zhou</u>, Tong Yang, Jie Jiang, Bin Cui, Minlan Yu, Xiaoming Li, Steve Uhlig
<br>**SIGMOD 2018**. ACM SIGMOD International Conference on Management of Data
<br>[[paper](paper/cf-sigmod18.pdf)] 
[[slides](slides/coldfilter-sigmod18-slides.pdf)]
[[Code](https://github.com/zhouyangpkuer/ColdFilter)]

* Elastic Sketch: Adaptive and Fast Network-wide Measurements.
<br>Tong Yang, Jie Jiang, Peng Liu, Qun Huang, Junzhi Gong, <u>Yang Zhou</u>, Rui Miao, Xiaoming Li, Steve Uhlig
<br>**SIGCOMM 2018**. ACM SIGCOMM International Conference on Data Communications
<br>[[paper](paper/elastic-sigcomm18.pdf)] 
[[slides](slides/elastic-sigcomm18-slides.pdf)]
[[talk](https://youtu.be/w8L0opwetms?t=3172)]
[[Code](https://github.com/BlockLiu/ElasticSketchCode)]
<!-- <br> **<span style="color:red">Widely followed (cited 430+)</span>** -->

* Accelerating Network Measurement in Software.
<br><u>Yang Zhou</u>, Omid Alipourfard, Minlan Yu, Tong Yang
<br>**SIGCOMM CCR 2018** July issue, ACM SIGCOMM Computer Communication Review
<br>[[paper](paper/agg-ccr18.pdf)] 
[[Code](https://github.com/harvard-cns/Agg-Evict)]

* A Comparison of Performance and Accuracy of Measurement Algorithms in Software.
<br>Omid Alipourfard, Masoud Moshref, <u>Yang Zhou</u>, Tong Yang, Minlan Yu
<br>**SOSR 2018**. ACM Symposium on SDN Research
<br>[[paper](paper/simple-sosr18.pdf)]

* Accurate Per-Flow Measurement with Bloom Sketch.
<br><u>Yang Zhou</u>, Hao Jin, Peng Liu, Haowei Zhang, Tong Yang, Xiaoming Li
<br>INFOCOM 2018 Workshops. IEEE International Conference on Computer Communications
<br>[[paper](paper/bs-infocom18.pdf)] 
[[Code](https://github.com/zhouyangpkuer/BloomSketch)]

* Single Hash: Use One Hash Function to Build Faster Hash Based Data Structures.
<br>Xiangyang Gou, Chenxingyu Zhao, Tong Yang, Lei Zou, <u>Yang Zhou</u>, Yibo Yan, Xiaoming Li, Bin Cui
<br>BigComp 2018. IEEE International Conference on Big Data and Smart Computing
<br>[[paper](paper/singlehash-bigcomp18.pdf)]

* Pyramid Sketch: a Sketch Framework for Frequency Estimation of Data Streams.
<br>Tong Yang, <u>Yang Zhou</u>, Hao Jin, Shigang Chen, Xiaoming Li
<br>**VLDB 2017**. International Conference on Very Large Data Bases
<br>[[paper](paper/pyramid-vldb17.pdf)] 
[[Code](https://github.com/zhouyangpkuer/Pyramid_Sketch_Framework)]

* One Memory Access Sketch: a More Accurate and Faster Sketch for Per-flow Measurement.
<br><u>Yang Zhou</u>, Peng Liu, Hao Jin, Tong Yang, Shoujiang Dang, Xiaoming Li
<br>Globecom 2017. IEEE Global Communications Conference
<br>[[paper](paper/om-globecom17.pdf)] 
[[Code](https://github.com/zhouyangpkuer/OMsketch)]

* ABC: a Practicable Sketch Framework for Non-uniform Multisets.
<br>Junzhi Gong, Tong Yang, <u>Yang Zhou</u>, Dongsheng Yang, Shigang Chen, Bin Cui, Xiaoming Li
<br>BigData 2017. IEEE International Conference on Big Data
<br>[[paper](paper/abc-bigdata17.pdf)]

*: co-primary authors

## Teaching

* ECS 150 Operating Systems: [Spring 2026](https://bob.cs.ucdavis.edu/classes/s26-ecs150/index.html) (with Sam King)
* ECS 289D Seminar in Operating Systems: Datacenter Systems for LLMs: [Fall 2025](./teaching/ecs289d_fall25.html)
  * [RDMA tutorial](https://kyli-leo.github.io/289D-RDMA-toturial/) made by the class

## Service

* Organizer:
  * Co-Chair for SIGCOMM Artifact Evaluation 2024  
* Program Committee: 
  * ICNP 2026
  * APSys 2026
  * SIGCOMM Workshop on Networks for AI Computing (NAIC) 2025, 2026
  * EuroSys 2026
  * ASPLOS 2026
  * NSDI 2026
  * OSDI 2025
  * SIGCOMM Poster/Demo 2023, 2024
  * SIGCOMM Workshop on eBPF and Kernel Extensions 2024, 2025

<!-- ## Highlighted Projects -->

<!-- * Adding the feature of direct message passing to opensource serverless platform -- OpenWhisk.
  * Code: [openwhisk-lambda-mpi](https://github.com/YangZhou1997/openwhisk-lambda-mpi)
  * Using docker overlay network for socket connection.
  * Implementing a zero-overhead DNS service among serverless instances. -->

## Miscellaneous

* I do skiing and traveling, see my [photos](./travelling.html) from:
  * Japan
  * China
  * White Mountains
  * Ecuador
  * Zion
  * Acadia
  * Salem
  * Puerto Rico
  * Mount Rainier
  * Olympic National Park
  * Great Smoky Mountains
  * Bryce Canyon
  * Capitol Reef
  * Utah 12
  * Death Valley
  * Crater Lake
  * Rocky Mountain
  * Mount Evans
  * Mount Baker
  * Lake Tahoe
  * Yosemite
  * Point Reyes
  * Grand Teton
  * Yellowstone
  * Everglades
  * Key West
  * Lassen Volcanic
  * Kenai Fjords
  * Denali
  * Monument Valley
  * Arches
  * Canyonlands
  * Alta
  * Snowbird
  * Aspen Snowmass
* I did long-distance biking
  * I cycled 700 miles around Taiwan in ten days, see my [photos](./cycling.html).
* I did long-distance running
  * I finished a half-marathon in 1h50min.
* I was pretty fond of physics during high school and college.
