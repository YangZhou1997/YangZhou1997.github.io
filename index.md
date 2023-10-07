---
layout: default
--- 

## Bio

I work on networked systems and distributed systems by co-designing low-level networking stacks and high-level microsecond-scale applications for resource efficiency and performance.

* In the networking stack side, I focus on kernel-bypass stacks like RDMA and DPDK, and kernel stacks with eBPF/XDP;
* in the application side, I focus on memory disaggregation, microsecond RPCs, Paxos fault tolerance, and distributed transactions.

I am a final-year Ph.D. candidate at Harvard University, advised by Prof. [Minlan Yu](http://minlanyu.seas.harvard.edu/) and Prof. [James Mickens](https://mickens.seas.harvard.edu/).
I received a B.S. in Computer Science at Peking University in 2018, advised by Prof. [Tong Yang](https://yangtonghome.github.io/), where I worked on one-pass randomized algorithms.
I am supported by a [Google PhD Fellowship](https://research.google/outreach/phd-fellowship/recipients/?category=2022) in Systems and Networking.
[Google Scholar](https://scholar.google.com/citations?user=c3KgJJ8AAAAJ).
<!-- My [CV](cv_yang.pdf) and [Google Scholar](https://scholar.google.com/citations?user=c3KgJJ8AAAAJ). -->

## I am on the academic job market this year!

## News

* Dec 2022, Electrode (eBPF-accelerated Paxos) accepted to NSDI'23!
* March 2022, Carbink (fault-tolerant far memory) accepted to OSDI'22!
* June 2021, PCAT (evolvable network telemetry) accepted to NSDI'22!

## Publications

### 2023

* [Electrode: Accelerating Distributed Protocols with eBPF](paper/electrode-nsdi23.pdf)
<br><u>Yang Zhou</u>\*, Zezhou Wang\*, Sowmya Dharanipragada, Minlan Yu.
<br>**NSDI 2023**. USENIX Symposium on Networked Systems Design and Implementation.

### 2022

* [Carbink: Fault-Tolerant Far Memory](paper/carbink-osdi22.pdf)
<br><u>Yang Zhou</u>, Hassan Wassel, Sihang Liu, Jiaqi Gao, James Mickens, Minlan Yu, Chris Kennelly, Paul Turner, David Culler, Hank Levy, Amin Vahdat.
<br>**OSDI 2022**. USENIX Symposium on Operating Systems Design and Implementation.

* [Evolvable Network Telemetry at Facebook](paper/pcat-nsdi22.pdf)
<br><u>Yang Zhou</u>, Ying Zhang, Minlan Yu, Guangyu Wang, Dexter Cao, Eric Sung and Starsky Wong.
<br>**NSDI 2022**. USENIX Symposium on Networked Systems Design and Implementation.

* [On the Evolutionary of Bloom Filter False Positives - An Information Theoretical Approach to Optimizing Bloom Filter Parameters](paper/bf-tkde22.pdf)
<br>Zhuochen Fan, Gang Wen, Zhipeng Huang, <u>Yang Zhou</u>, Qiaobin Fu, Tong Yang, Alex X. Liu, Bin Cui.
<br>IEEE Transactions on Knowledge and Data Engineering (TKDE) 2022.

### 2021

* [Pyramid Family: Generic Frameworks for Accurate and Fast Flow Size Measurement](paper/pyramid_family_ton21.pdf)
<br>Yuanpeng Li, Xiang Yu, Yilong Yang, <u>Yang Zhou</u>, Tong Yang, Zhuo Ma, Shigang Chen.
<br>IEEE/ACM Trasactions on Networking (TON) 2021.

### 2019

* [Adaptive Measurements using One Elastic Sketch.](paper/elastic_ton2019.pdf)
<br>Tong Yang, Jie Jiang, Peng Liu, Qun Huang, Junzhi Gong, <u>Yang Zhou</u>, Rui Miao, Xiaoming Li, Steve Uhlig.
<br>IEEE/ACM Trasactions on Networking (TON) 2019.

* [Fast and Accurate Stream Processing by Filtering the Cold.](paper/filtering_cold_vldbj19.pdf)
<br>Tong Yang, Jie Jiang, <u>Yang Zhou</u>, Long He, Jinyang Li, Bin Cui, Steve Uhlig, Xiaoming Li.
<br>VLDB Journal 2019.

### 2018

* [Elastic Sketch: Adaptive and Fast Network-wide Measurements.](paper/elastic-sigcomm18.pdf)
<br>Tong Yang, Jie Jiang, Peng Liu, Qun Huang, Junzhi Gong, <u>Yang Zhou</u>, Rui Miao, Xiaoming Li, Steve Uhlig.
<br>**SIGCOMM 2018**. ACM SIGCOMM International Conference on Data Communications.

* [Cold Filter: A Meta-Framework for Faster and More Accurate Stream Processing.](paper/cf-sigmod18.pdf)
<br><u>Yang Zhou</u>, Tong Yang, Jie Jiang, Bin Cui, Minlan Yu, Xiaoming Li, and Steve Uhlig.
<br>**SIGMOD 2018**. ACM SIGMOD International Conference on Management of Data.

* [Accelerating Network Measurement in Software.](paper/agg-ccr18.pdf)
<br><u>Yang Zhou</u>, Omid Alipourfard, Minlan Yu, and Tong Yang.
<br>**SIGCOMM CCR** July issue, ACM SIGCOMM Computer Communication Review.

* [Accurate Per-Flow Measurement with Bloom Sketch.](paper/bs-infocom18.pdf)
<br><u>Yang Zhou</u>, Hao Jin, Peng Liu, Haowei Zhang, Tong Yang, Xiaoming Li.
<br>INFOCOM 2018 (poster). IEEE International Conference on Computer Communications.

* [A Comparison of Performance and Accuracy of Measurement Algorithms in Software.](paper/simple-sosr18.pdf)
<br>Omid Alipourfard, Masoud Moshref, <u>Yang Zhou</u>, Tong Yang, and Minlan Yu.
<br>**SOSR 2018**. ACM Symposium on SDN Research.

* [Single Hash: Use One Hash Function to Build Faster Hash Based Data Structures.](paper/singlehash-bigcomp18.pdf)
<br>Xiangyang Gou, Chenxingyu Zhao, Tong Yang, Lei Zou, <u>Yang Zhou</u>, Yibo Yan, Xiaoming Li, and Bin Cui.
<br>BigComp 2018. IEEE International Conference on Big Data and Smart Computing.

### 2017

* [Pyramid Sketch: a Sketch Framework for Frequency Estimation of Data Streams.](paper/pyramid-vldb17.pdf)
<br>Tong Yang, <u>Yang Zhou</u>, Hao Jin, Shigang Chen, and Xiaoming Li.
<br>**VLDB 2017**. International Conference on Very Large Data Bases.

* [One Memory Access Sketch: a More Accurate and Faster Sketch for Per-flow Measurement.](paper/om-globecom17.pdf)
<br><u>Yang Zhou</u>, Peng Liu, Hao Jin, Tong Yang, Shoujiang Dang, and Xiaoming Li.
<br>Globecom 2017. IEEE Global Communications Conference.

* [ABC: a Practicable Sketch Framework for Non-uniform Multisets.](paper/abc-bigdata17.pdf)
<br>Junzhi Gong, Tong Yang, <u>Yang Zhou</u>, Dongsheng Yang, Shigang Chen, Bin Cui, and Xiaoming Li.
<br>BigData 2017. IEEE International Conference on Big Data.

*: co-primary authors

## Highlighted Projects

* Adding the feature of direct message passing to opensource serverless platform -- OpenWhisk.
  * Code: [openwhisk-lambda-mpi](https://github.com/YangZhou1997/openwhisk-lambda-mpi)
  * Using docker overlay network for socket connection.
  * Implementing a zero-overhead DNS service among serverless instances.

## Miscellaneous

* I do skiing and traveling, see my [photos](./travelling.html) from Japan, White Mountain, Ecuador, Zion, Acadia, Salem, Puerco Rico, Olympic National Park, Mount Rainer, Great Smoky Mountains, Bryce Canyon, Capitol Reef, Death Valley, Crater Lake, Rocky Mountain, Mount Evans, Mount Baker, Yosemite, Grand Teton, Yellowstone.
* I did long-distance biking. I cycled 700 miles around Taiwan in ten days, see my [photos](./cycling.html).
* I did long-distance running. I finished a half-marathon in 1h50min.
* I did physics.
