---
layout: default
--- 

## About

I work on networked systems in datacenter environments.
My research has focused on full-stack optimizations for efficient and evolvable datacenter infrastructure, 
by codesigning low-level host networking stacks (involving NICs, kernels, transport layers, and threading) and high-level datacenter applications 
from a systems perspective. 

* For networking stacks, I studied kernel-bypass stacks like RDMA and DPDK, and kernel stacks with eBPF/XDP.
* For applications, I studied fault-tolerant far memory, Paxos consensus, distributed transactions, and microsecond-scale RPCs.

I am a final-year Ph.D. candidate in Computer Science at Harvard University, advised by Prof. [Minlan Yu](http://minlanyu.seas.harvard.edu/) and Prof. [James Mickens](https://mickens.seas.harvard.edu/).
I received a B.S. in Computer Science at Peking University in 2018, working with Prof. [Tong Yang](https://yangtonghome.github.io/) on probabilistic data structures for network telemetry.
I am supported by a [Google PhD Fellowship](https://research.google/outreach/phd-fellowship/recipients/?category=2022) in Systems and Networking.

## I am on the academic job market this year! [[Materials]](./application/)

<!-- ## News -->

<!-- * Dec 2023, DINT (eBPF-accelerated distributed transactions) accepted to NSDI'24!
* Dec 2022, Electrode (eBPF-accelerated Paxos) accepted to NSDI'23!
* March 2022, Carbink (fault-tolerant far memory) accepted to OSDI'22!
* June 2021, PCAT (evolvable network telemetry) accepted to NSDI'22! -->

## Publications

### Conference

* SmartNIC Security Isolation in the Cloud with S-NIC
<br><u>Yang Zhou</u>, Mark Wilkening, James Mickens, and Minlan Yu.
<br>**EuroSys 2024**. European Conference on Computer Systems.
<br>[[paper](https://drive.google.com/file/d/1F5v2JI-MOaYymhBbxcD70s43lcsq8LqD/view?usp=sharing)] [code (coming soon)]

* DINT: Fast In-Kernel Distributed Transactions with eBPF
<br><u>Yang Zhou</u>\*, Xingyu Xiang\*, Matthew Kiley, Sowmya Dharanipragada, and Minlan Yu.
<br>**NSDI 2024**. USENIX Symposium on Networked Systems Design and Implementation.
<br>[[paper](https://drive.google.com/file/d/1pkQGPOsblB36WGHBJC3NqX0Sz8OgD4Nm/view?usp=sharing)] [code (coming soon)]

* Electrode: Accelerating Distributed Protocols with eBPF
<br><u>Yang Zhou</u>\*, Zezhou Wang\*, Sowmya Dharanipragada, and Minlan Yu.
<br>**NSDI 2023**. USENIX Symposium on Networked Systems Design and Implementation.
<br>[[paper](paper/electrode-nsdi23.pdf)] 
[[slides](slides/electrode-nsdi23-slides.pdf)] 
[[talk](https://youtu.be/E6qcR2Lb1xE)] 
[[code](https://github.com/Electrode-NSDI23/Electrode)]
<br> **<span style="color:red">Initial conversations with multiple companies</span>**

* Carbink: Fault-Tolerant Far Memory
<br><u>Yang Zhou</u>, Hassan Wassel, Sihang Liu, Jiaqi Gao, James Mickens, Minlan Yu, Chris Kennelly, Paul Turner, David Culler, Hank Levy, and Amin Vahdat.
<br>**OSDI 2022**. USENIX Symposium on Operating Systems Design and Implementation.
<br>[[paper](paper/carbink-osdi22.pdf)] 
[[slides](slides/carbink-osdi22-slides.pdf)]
[[talk](https://youtu.be/PZhqlPyhImE)] 
<br> **<span style="color:red">Joint patent with Google</span>**

* Evolvable Network Telemetry at Facebook
<br><u>Yang Zhou</u>, Ying Zhang, Minlan Yu, Guangyu Wang, Dexter Cao, Eric Sung and Starsky Wong.
<br>**NSDI 2022**. USENIX Symposium on Networked Systems Design and Implementation.
<br>[[paper](paper/pcat-nsdi22.pdf)] 
[[slides](slides/pcat-nsdi22-slides.pdf)]
[[talk](https://youtu.be/azW4vssu9T0)] 
<br> **<span style="color:red">Describing production systems and challenges</span>**

* Cold Filter: A Meta-Framework for Faster and More Accurate Stream Processing. 
<br><u>Yang Zhou</u>, Tong Yang, Jie Jiang, Bin Cui, Minlan Yu, Xiaoming Li, and Steve Uhlig.
<br>**SIGMOD 2018**. ACM SIGMOD International Conference on Management of Data.
<br>[[paper](paper/cf-sigmod18.pdf)] 
[[slides](slides/coldfilter-sigmod18-slides.pdf)]
[[Code](https://github.com/zhouyangpkuer/ColdFilter)]

* Elastic Sketch: Adaptive and Fast Network-wide Measurements.
<br>Tong Yang, Jie Jiang, Peng Liu, Qun Huang, Junzhi Gong, <u>Yang Zhou</u>, Rui Miao, Xiaoming Li, and Steve Uhlig.
<br>**SIGCOMM 2018**. ACM SIGCOMM International Conference on Data Communications.
<br>[[paper](paper/elastic-sigcomm18.pdf)] 
[[slides](slides/elastic-sigcomm18-slides.pdf)]
[[talk](https://youtu.be/w8L0opwetms?t=3172)]
[[Code](https://github.com/BlockLiu/ElasticSketchCode)]
<br> **<span style="color:red">Widely followed (cited 430+)</span>**

* A Comparison of Performance and Accuracy of Measurement Algorithms in Software.
<br>Omid Alipourfard, Masoud Moshref, <u>Yang Zhou</u>, Tong Yang, and Minlan Yu.
<br>**SOSR 2018**. ACM Symposium on SDN Research.
<br>[[paper](paper/simple-sosr18.pdf)]

* Single Hash: Use One Hash Function to Build Faster Hash Based Data Structures.
<br>Xiangyang Gou, Chenxingyu Zhao, Tong Yang, Lei Zou, <u>Yang Zhou</u>, Yibo Yan, Xiaoming Li, and Bin Cui.
<br>BigComp 2018. IEEE International Conference on Big Data and Smart Computing.
<br>[[paper](paper/singlehash-bigcomp18.pdf)]

* Pyramid Sketch: a Sketch Framework for Frequency Estimation of Data Streams.
<br>Tong Yang, <u>Yang Zhou</u>, Hao Jin, Shigang Chen, and Xiaoming Li.
<br>**VLDB 2017**. International Conference on Very Large Data Bases.
<br>[[paper](paper/pyramid-vldb17.pdf)] 
[[Code](https://github.com/zhouyangpkuer/Pyramid_Sketch_Framework)]

* One Memory Access Sketch: a More Accurate and Faster Sketch for Per-flow Measurement.
<br><u>Yang Zhou</u>, Peng Liu, Hao Jin, Tong Yang, Shoujiang Dang, and Xiaoming Li.
<br>Globecom 2017. IEEE Global Communications Conference.
<br>[[paper](paper/om-globecom17.pdf)] 
[[Code](https://github.com/zhouyangpkuer/OMsketch)]

* ABC: a Practicable Sketch Framework for Non-uniform Multisets.
<br>Junzhi Gong, Tong Yang, <u>Yang Zhou</u>, Dongsheng Yang, Shigang Chen, Bin Cui, and Xiaoming Li.
<br>BigData 2017. IEEE International Conference on Big Data.
<br>[[paper](paper/abc-bigdata17.pdf)]

### Workshop and Demo

* Accurate Per-Flow Measurement with Bloom Sketch.
<br><u>Yang Zhou</u>, Hao Jin, Peng Liu, Haowei Zhang, Tong Yang, and Xiaoming Li.
<br>INFOCOM 2018 Workshops. IEEE International Conference on Computer Communications.
<br>[[paper](paper/bs-infocom18.pdf)] 
[[Code](https://github.com/zhouyangpkuer/BloomSketch)]

### Journal

* On the Evolutionary of Bloom Filter False Positives - An Information Theoretical Approach to Optimizing Bloom Filter Parameters
<br>Zhuochen Fan, Gang Wen, Zhipeng Huang, <u>Yang Zhou</u>, Qiaobin Fu, Tong Yang, Alex X. Liu, and Bin Cui.
<br>IEEE Transactions on Knowledge and Data Engineering (TKDE) 2022.
<br>[[paper](paper/bf-tkde22.pdf)] [[Code](https://github.com/pkufzc/Bloom-Error-TKDE)]

* Pyramid Family: Generic Frameworks for Accurate and Fast Flow Size Measurement
<br>Yuanpeng Li, Xiang Yu, Yilong Yang, <u>Yang Zhou</u>, Tong Yang, Zhuo Ma, and Shigang Chen.
<br>IEEE/ACM Trasactions on Networking (TON) 2021.
<br>[[paper](paper/pyramid_family_ton21.pdf)] 
[[Code](https://github.com/Pyramid-Family/Pyramid-Family)]

* Adaptive Measurements using One Elastic Sketch.
<br>Tong Yang, Jie Jiang, Peng Liu, Qun Huang, Junzhi Gong, <u>Yang Zhou</u>, Rui Miao, Xiaoming Li, and Steve Uhlig.
<br>IEEE/ACM Trasactions on Networking (TON) 2019.
<br>[[paper](paper/elastic_ton2019.pdf)] 
[[Code](https://github.com/BlockLiu/ElasticSketchCode)]

* Fast and Accurate Stream Processing by Filtering the Cold.
<br>Tong Yang, Jie Jiang, <u>Yang Zhou</u>, Long He, Jinyang Li, Bin Cui, Steve Uhlig, and Xiaoming Li.
<br>VLDB Journal 2019.
<br>[[paper](paper/filtering_cold_vldbj19.pdf)] 
[[Code](https://github.com/zhouyangpkuer/ColdFilter)]

* Accelerating Network Measurement in Software.
<br><u>Yang Zhou</u>, Omid Alipourfard, Minlan Yu, and Tong Yang.
<br>**SIGCOMM CCR 2018** July issue, ACM SIGCOMM Computer Communication Review.
<br>[[paper](paper/agg-ccr18.pdf)] 
[[Code](https://github.com/harvard-cns/Agg-Evict)]

*: co-primary authors

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
  * Everglades National Park
  * Key West
* I did long-distance biking
  * I cycled 700 miles around Taiwan in ten days, see my [photos](./cycling.html).
* I did long-distance running
  * I finished a half-marathon in 1h50min.
* I did physics.
