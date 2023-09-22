---
layout: default
--- 

# Bio

I work on networked systems and distributed systems by co-designing low-level networking stacks and high-level microsecond-scale applications for resource efficiency and performance.

* In the networking stack side, I focus on kernel-bypass stacks like RDMA and DPDK, and kernel stacks with eBPF/XDP;
* in the appliction side, I focus on memory disaggregation, microsecond RPCs, Paxos fault tolerance, and distributed transactions.

I am a final-year Ph.D. candidate at Harvard University, advised by Prof. [Minlan Yu](http://minlanyu.seas.harvard.edu/) and Prof. [James Mickens](https://mickens.seas.harvard.edu/).
I received a B.S. in Computer Science at Peking University in 2018, advised by Prof. [Tong Yang](https://yangtonghome.github.io/), where I worked on one-pass randomized algorithms.
I am supported by a [Google PhD Fellowship](https://research.google/outreach/phd-fellowship/recipients/?category=2022) in Systems and Networking.
My [CV](cv_yang.pdf) and [Google Scholar](https://scholar.google.com/citations?user=c3KgJJ8AAAAJ).

<p style="margin-top: 2em"><font size="5">I am on the academic job market this year!</font></p>

_E-mail:_ yangzhou{at}g.harvard.edu, yanggepkuer15{at}gmail.com<br>
_Address:_ SEC 4.429, 150 Western Ave, Allston, MA 02134

# News

* Dec 2022, Electrode (eBPF-accelerated Paxos) accepted to NSDI'23!
* March 2022, Carbink (fault-tolerant far memory) accepted to OSDI'22!
* June 2021, PCAT (evolvable network telemetry) accepted to NSDI'22!

# Publications

### 2023

1. [Electrode: Accelerating Distributed Protocols with eBPF](paper/electrode-nsdi23.pdf)
<br>**Yang Zhou\***, Zezhou Wang\*, Sowmya Dharanipragada, Minlan Yu.
<br>**NSDI 2023**. USENIX Symposium on Networked Systems Design and Implementation.

### 2022

1. [Carbink: Fault-Tolerant Far Memory](paper/carbink-osdi22.pdf)
<br>**Yang Zhou**, Hassan Wassel, Sihang Liu, Jiaqi Gao, James Mickens, Minlan Yu, Chris Kennelly, Paul Turner, David Culler, Hank Levy, Amin Vahdat.
<br>**OSDI 2022**. USENIX Symposium on Operating Systems Design and Implementation.

1. [Evolvable Network Telemetry at Facebook](paper/pcat-nsdi22.pdf)
<br>**Yang Zhou**, Ying Zhang, Minlan Yu, Guangyu Wang, Dexter Cao, Eric Sung and Starsky Wong.
<br>**NSDI 2022**. USENIX Symposium on Networked Systems Design and Implementation.

1. [On the Evolutionary of Bloom Filter False Positives - An Information Theoretical Approach to Optimizing Bloom Filter Parameters](paper/bf-tkde22.pdf)
<br>Zhuochen Fan, Gang Wen, Zhipeng Huang, **Yang Zhou**, Qiaobin Fu, Tong Yang, Alex X. Liu, Bin Cui.
<br>IEEE Transactions on Knowledge and Data Engineering (TKDE) 2022.

### 2021

1. [Pyramid Family: Generic Frameworks for Accurate and Fast Flow Size Measurement](paper/pyramid_family_ton21.pdf)
<br>Yuanpeng Li, Xiang Yu, Yilong Yang, **Yang Zhou**, Tong Yang, Zhuo Ma, Shigang Chen.
<br>IEEE/ACM Trasactions on Networking (TON) 2021.

### 2019

1. [Adaptive Measurements using One Elastic Sketch.](paper/elastic_ton2019.pdf)
<br>Tong Yang, Jie Jiang, Peng Liu, Qun Huang, Junzhi Gong, **Yang Zhou**, Rui Miao, Xiaoming Li, Steve Uhlig.
<br>IEEE/ACM Trasactions on Networking (TON) 2019.

1. [Fast and Accurate Stream Processing by Filtering the Cold.](paper/filtering_cold_vldbj19.pdf)
<br>Tong Yang, Jie Jiang, **Yang Zhou**, Long He, Jinyang Li, Bin Cui, Steve Uhlig, Xiaoming Li.
<br>VLDB Journal 2019.

### 2018

1. [Elastic Sketch: Adaptive and Fast Network-wide Measurements.](paper/elastic-sigcomm18.pdf)
<br>Tong Yang, Jie Jiang, Peng Liu, Qun Huang, Junzhi Gong, **Yang Zhou**, Rui Miao, Xiaoming Li, Steve Uhlig.
<br>**SIGCOMM 2018**. ACM SIGCOMM International Conference on Data Communications.

1. [Cold Filter: A Meta-Framework for Faster and More Accurate Stream Processing.](paper/cf-sigmod18.pdf)
<br>**Yang Zhou**, Tong Yang, Jie Jiang, Bin Cui, Minlan Yu, Xiaoming Li, and Steve Uhlig.
<br>**SIGMOD 2018**. ACM SIGMOD International Conference on Management of Data.

1. [Accelerating Network Measurement in Software.](paper/agg-ccr18.pdf)
<br>**Yang Zhou**, Omid Alipourfard, Minlan Yu, and Tong Yang.
<br>**SIGCOMM CCR** July issue, ACM SIGCOMM Computer Communication Review.

1. [Accurate Per-Flow Measurement with Bloom Sketch.](paper/bs-infocom18.pdf)
<br>**Yang Zhou**, Hao Jin, Peng Liu, Haowei Zhang, Tong Yang, Xiaoming Li.
<br>**INFOCOM 2018 (poster)**. IEEE International Conference on Computer Communications.

1. [A Comparison of Performance and Accuracy of Measurement Algorithms in Software.](paper/simple-sosr18.pdf)
<br>Omid Alipourfard, Masoud Moshref, **Yang Zhou**, Tong Yang, and Minlan Yu.
<br>**SOSR 2018**. ACM Symposium on SDN Research.

1. [Single Hash: Use One Hash Function to Build Faster Hash Based Data Structures.](paper/singlehash-bigcomp18.pdf)
<br>Xiangyang Gou, Chenxingyu Zhao, Tong Yang, Lei Zou, **Yang Zhou**, Yibo Yan, Xiaoming Li, and Bin Cui.
<br>**BigComp 2018**. IEEE International Conference on Big Data and Smart Computing.

### 2017

1. [Pyramid Sketch: a Sketch Framework for Frequency Estimation of Data Streams.](paper/pyramid-vldb17.pdf)
<br>Tong Yang, **Yang Zhou**, Hao Jin, Shigang Chen, and Xiaoming Li.
<br>**VLDB 2017**. International Conference on Very Large Data Bases.

1. [One Memory Access Sketch: a More Accurate and Faster Sketch for Per-flow Measurement.](paper/om-globecom17.pdf)
<br>**Yang Zhou**, Peng Liu, Hao Jin, Tong Yang, Shoujiang Dang, and Xiaoming Li.
<br>**Globecom 2017**. IEEE Global Communications Conference.

1. [ABC: a Practicable Sketch Framework for Non-uniform Multisets.](paper/abc-bigdata17.pdf)
<br>Junzhi Gong, Tong Yang, **Yang Zhou**, Dongsheng Yang, Shigang Chen, Bin Cui, and Xiaoming Li.
<br>**BigData 2017**. IEEE International Conference on Big Data.

*: co-primary authors

# Highlighted Projects

* Adding the feature of direct message passing to opensource serverless platform -- OpenWhisk.
  * Code: [openwhisk-lambda-mpi](https://github.com/YangZhou1997/openwhisk-lambda-mpi)
  * Using docker overlay network for socket connection.
  * Implementing a zero-overhead DNS service among serverless instances.

# Miscellaneous

* I do skiing and traveling.
* I did long-distance running. Half-marathon in 1h50min.
* I did long-distance biking. Cycling 700 miles around Taiwan in ten days [More](./cycling.html).
* I did physics.
