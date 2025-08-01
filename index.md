---
layout: default
--- 

## About

I am a PostDoc at UC Berkeley advised by [Ion Stoica](https://people.eecs.berkeley.edu/~istoica/). I have equal interests in core systems and ML systems research, e.g., efficient LLMs, GPU communication, heterogeneous computing. 
I am currently working on [UCCL](https://github.com/uccl-project/uccl) for GPU communication. 

<span style="color:red;">I will be joining UC Davis CS as an Assistant Professor, starting July 2025.</span>

<!-- I have multiple PhD openings at UC Davis (apply [here](https://apply.grad.ucdavis.edu/apply/) by Dec 15, 2024). Feel free to drop me an email if you are interested. 
* UC Davis is ranked 28th in Best National University and 36th in Best Computer Science Schools by US News. 
* UC Davis has a great location: 20min drive from Sacramento (capital of California) and 1.5h from Silicon Valley (Google, Meta, Amazon).
* Perhaps more importantly, it is a 50min drive from the famous Napa Valley (wine) and 2h from the great Lake Tahoe (skiing and more!). -->

I finished my PhD in Computer Science at Harvard University in 2024, advised by [Minlan Yu](http://minlanyu.seas.harvard.edu/) and [James Mickens](https://mickens.seas.harvard.edu/).
I received my B.S. in Computer Science at Peking University in 2018, advised by [Tong Yang](https://yangtonghome.github.io/) on probabilistic data structures and streaming algorithms.
I was supported by a Google PhD Fellowship in Systems and Networking (see my [app materials](./materials/google_fellowship_cv_rs.pdf)). 

## Updates
* July 2025, UCCL talk at Meta, ByteDance (Seed), SJTU IPADS
* June 2025, UCCL talk at ByteDance (Networking), NVIDIA
* May 2025, UCCL talk at UC Berkeley SkyLab Summer Retreat, Broadcom
* Jan 2025, UCCL talk at UC Berkeley SkyLab Winter Retreat

## Students

Current: 
* Shuang Ma (2025-now, PhD), from USTC
* Yihan Zhang (2025-now, PhD), from UIUC

Mentored: 
* Zhongjie Chen (2024-now), Tsinghua University PhD
* Xuanlin Jiang (2024), Peking University undergrad → Harvard PhD
* Matt Kiley (2023), Harvard College undergrad → Clockwork Systems
* [Yunxi Shen](https://yxshen20.github.io/) (2023-2024), Tsinghua University undergrad → Cornell PhD
* [Xingyu Xiang](https://xyxiang7.github.io/) (2023-now), Peking University undergrad → Harvard PhD
* Zezhou Wang (2022), Peking University undergrad → University of Washington PhD

## Publications

### Preprints

* LEANN: a Low-Storage Vector Index
<br> Yichuan Wang, Shu Liu, Zhifei Li, Yongji Wu, Ziming Mao, Yilong Zhao, Xiao Yan, Zhiying Xu, <u>Yang Zhou</u>, Ion Stoica, Sewon Min, Matei Zaharia, Joseph E. Gonzalez
<br>[[Arxiv June 2025](https://arxiv.org/pdf/2506.08276)]

* UCCL: an Efficient Collective Communication Library for GPUs
<br> <u>Yang Zhou</u>\*, Zhongjie Chen\*, Ziming Mao, ChonLam Lao, Shuo Yang, Pravein Govindan Kannan, Jiaqi Gao, Yilong Zhao, Yongji Wu, Kaichao You, Fengyuan Ren, Zhiying Xu, Costin Raiciu, Ion Stoica
<br>[[Arxiv April 2025](https://arxiv.org/pdf/2504.17307)] [[homepage](https://uccl-project.github.io/)] [[slides](slides/uccl_sky_summer_retreat.pdf)] [[code](https://github.com/uccl-project/uccl)]

* Locality-Aware Fair Scheduling in LLM Serving
<br>Shiyi Cao\*, Yichuan Wang\*, Ziming Mao, Pin-Lun Hsu, Liangsheng Yin, Tian Xia, Dacheng Li, Shu Liu, Yineng Zhang, <u>Yang Zhou</u>, Ying Sheng, Joseph Gonzalez, Ion Stoica
<br>[[Arxiv Jan 2025](https://arxiv.org/pdf/2501.14312)]

* BlendServe: Optimizing Offline Inference for Auto-regressive Large Models with Resource-aware Batching
<br>Yilong Zhao\*, Shuo Yang\*, Kan Zhu, Lianmin Zheng, Baris Kasikci, Yifan Qiao, <u>Yang Zhou</u>, Jiarong Xing, Ion Stoica
<br>[[Arxiv Nov 2024](https://arxiv.org/pdf/2411.16102)]

* ConServe: Harvesting GPUs for Low-Latency and High-Throughput Large Language Model Serving
<br> Yifan Qiao, Shu Anzai, Shan Yu, Haoran Ma, Shuo Yang, Yang Wang, Miryung Kim, Yongji Wu, <u>Yang Zhou</u>, Jiarong Xing, Joseph Gonzalez, Ion Stoica, Harry Xu
<br> [[Arxiv Oct 2024](https://arxiv.org/pdf/2410.01228)]

* Post-Training Sparse Attention with Double Sparsity
<br>Shuo Yang, Ying Sheng, Yilong Zhao, Joseph Gonzalez, <u>Yang Zhou</u>, Ion Stoica, Lianmin Zheng
<br>[[Arxiv Aug 2024](https://arxiv.org/pdf/2408.07092)]

### Conference

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

* A Comparison of Performance and Accuracy of Measurement Algorithms in Software.
<br>Omid Alipourfard, Masoud Moshref, <u>Yang Zhou</u>, Tong Yang, Minlan Yu
<br>**SOSR 2018**. ACM Symposium on SDN Research
<br>[[paper](paper/simple-sosr18.pdf)]

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

### Workshop and Demo

* Accurate Per-Flow Measurement with Bloom Sketch.
<br><u>Yang Zhou</u>, Hao Jin, Peng Liu, Haowei Zhang, Tong Yang, Xiaoming Li
<br>INFOCOM 2018 Workshops. IEEE International Conference on Computer Communications
<br>[[paper](paper/bs-infocom18.pdf)] 
[[Code](https://github.com/zhouyangpkuer/BloomSketch)]

### Journal

* On the Evolutionary of Bloom Filter False Positives - An Information Theoretical Approach to Optimizing Bloom Filter Parameters
<br>Zhuochen Fan, Gang Wen, Zhipeng Huang, <u>Yang Zhou</u>, Qiaobin Fu, Tong Yang, Alex X. Liu, Bin Cui
<br>IEEE Transactions on Knowledge and Data Engineering (TKDE) 2022
<br>[[paper](paper/bf-tkde22.pdf)] [[Code](https://github.com/pkufzc/Bloom-Error-TKDE)]

* Pyramid Family: Generic Frameworks for Accurate and Fast Flow Size Measurement
<br>Yuanpeng Li, Xiang Yu, Yilong Yang, <u>Yang Zhou</u>, Tong Yang, Zhuo Ma, Shigang Chen
<br>IEEE/ACM Trasactions on Networking (TON) 2021
<br>[[paper](paper/pyramid_family_ton21.pdf)] 
[[Code](https://github.com/Pyramid-Family/Pyramid-Family)]

* Adaptive Measurements using One Elastic Sketch.
<br>Tong Yang, Jie Jiang, Peng Liu, Qun Huang, Junzhi Gong, <u>Yang Zhou</u>, Rui Miao, Xiaoming Li, Steve Uhlig
<br>IEEE/ACM Trasactions on Networking (TON) 2019
<br>[[paper](paper/elastic_ton2019.pdf)] 
[[Code](https://github.com/BlockLiu/ElasticSketchCode)]

* Fast and Accurate Stream Processing by Filtering the Cold.
<br>Tong Yang, Jie Jiang, <u>Yang Zhou</u>, Long He, Jinyang Li, Bin Cui, Steve Uhlig, Xiaoming Li
<br>VLDB Journal 2019
<br>[[paper](paper/filtering_cold_vldbj19.pdf)] 
[[Code](https://github.com/zhouyangpkuer/ColdFilter)]

* Accelerating Network Measurement in Software.
<br><u>Yang Zhou</u>, Omid Alipourfard, Minlan Yu, Tong Yang
<br>**SIGCOMM CCR 2018** July issue, ACM SIGCOMM Computer Communication Review
<br>[[paper](paper/agg-ccr18.pdf)] 
[[Code](https://github.com/harvard-cns/Agg-Evict)]

*: co-primary authors

## Service

* Organizer:
  * Co-Chair for SIGCOMM Artifact Evaluation 2024  
* Program Committee: 
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
* I did long-distance biking
  * I cycled 700 miles around Taiwan in ten days, see my [photos](./cycling.html).
* I did long-distance running
  * I finished a half-marathon in 1h50min.
* I was pretty fond of physics during high school and college.
