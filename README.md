# AI Systems Spring 2021

## Announcements

## Schedule (TBD)

| Week           | Lecture                                                      | 
| -------------- | ------------------------------------------------------------ | 
| Week1 3.2/4    | Course overview.<br />ML infrastructure case study (Guest lecture). | 
| Week2 3.9/11   | MLSys. Facebook AI Infra.<br />AI Hardware: GPU (Guest lecture), TPU |  
| Week3 3.16/18  | ML lifecycles. Hidden technical debt.<br />Benchmarks: MLPerf. GPU Profiling<br />Large-scale recommendation system (Guest lecture)| 
| Week4 3.23/25  | ML frameworks: TensorFlow, PyTorch, JANUS. |
| Week5 3.30/4.1 | ML Compiler: Halide, TVM.   </br>AI for Mission Critical Applications (Guest lecture) | 
| Week6 4.6/8    | ML graph optimization: TASO, FlexFlow, NeoCPU.               |  
| Week7 4.13/15  | ML scheduling optimization: Nimble, Rammer. </br> 경로시간 정확도 개선 (Guest lecture) |  
| Week8 4.20/22  | ML Distributed Training: Horovod, Parameter Server (Google PS, BytePS), Parallax, Mesh-TensorFlow, GPipe, PipeDream | 
| Week9 4.27/29  | Mid Project Presentation                                     |                          |
| Week10 5.4/6   | ML Distributed Training: Horovod, Parameter Server (Google PS, BytePS), Parallax, Mesh-TensorFlow, GPipe, PipeDream | 
| Week11 5.11/13 | ML Serving: Clipper, Pretzel, Nexus, Clockwork.              | 
| Week12 5.18/20 | GPU Cluster Management: Gandiva, Tiresias                    | 
| Week13 5.25/27 | ML Input Pipeline<br />AutoML: Vizier, Hippo, Retiarii       |  
| Week14 6.1/3   | Mobile ML                                                    |   
| Week15 6.8/10  | Final project presentation                                   |  
| Week16 6.15    | Project report due - TBD                                     | 


## Reading list

### 3/9
#### Required reading
- [MLSys](https://arxiv.org/pdf/1904.03257.pdf). MLSys: The Frontier of Machine Learning Systems. 
- [FacebookAIInfra](https://research.fb.com/wp-content/uploads/2017/12/hpca-2018-facebook.pdf). Applied Machine Learning at Facebook:
A Datacenter Infrastructure Perspective. Kim Hazelwood, Sarah Bird, David Brooks, Soumith Chintala, Utku Diril, Dmytro Dzhulgakov, Mohamed Fawzy, Bill Jia, Yangqing Jia, Aditya Kalro, James Law, Kevin Lee, Jason Lu, Pieter Noordhuis, Misha Smelyanskiy, Liang Xiong, Xiaodong Wang. HPCA 2018.

### 3/16
#### Required reading
- [Hidden](https://proceedings.neurips.cc/paper/2015/file/86df7dcfd896fcaf2674f757a2463eba-Paper.pdf). Hidden Technical Debt in Machine Learning Systems.
- [MLPerfTraining](https://arxiv.org/pdf/1910.01500.pdf). MLPerf Training Benchmark.
- [MLPerfInf](https://arxiv.org/pdf/1911.02549.pdf). MLPerf Inference Benchmark.

### 3/18
#### Extra reading
- Semi-Supervised Classification with Graph Convolutional Networks, ICLR 2017.
- Tripartite heterogeneous graph propagation for large-scale social recommendation, RecSys 2019.
- Graph Neural Networks in Recommender Systems: A Survey, J. ACM 2020.

### 3/23
#### Required reading
- [TensorFlow](https://www.usenix.org/system/files/conference/osdi16/osdi16-abadi.pdf). TensorFlow: A System for Large-Scale
Machine Learning. Martín Abadi, Paul Barham, Jianmin Chen, Zhifeng Chen, Andy Davis, Jeffrey Dean, Matthieu Devin, Sanjay Ghemawat, Geoffrey Irving, Michael Isard, Manjunath Kudlur, Josh Levenberg, Rajat Monga, Sherry Moore, Derek G. Murray, Benoit Steiner, Paul Tucker, Vijay Vasudevan, Pete Warden, Martin Wicke, Yuan Yu, Xiaoqiang Zheng. OSDI 2016.

#### Extra reading
- [TenorFlowDCF](https://arxiv.org/pdf/1805.01772.pdf). Dynamic Control Flow in Large-Scale Machine Learning. Yuan Yu, Martin Abadi, Paul Barham, Eugene Brevdo, Mike Burrows, Andy Davis, Jeff Dean, Sanjay Ghemawat, Tim Harley, Peter Hawkins, Michael Isard, Manjunath Kudlur, Rajat Monga, Derek Murray, Xiaoqiang Zheng. EuroSys 2018.
- [RDAG](http://spl.snu.ac.kr/wp-content/uploads/2018/04/eurosys18-rdag.pdf). Improving the Expressiveness of Deep Learning Frameworks with Recursion. Eunji Jeong*, Joo Seong Jeong*, Soojeong Kim, Gyeong-In Yu, Byung-Gon Chun. EuroSys 2018.
- [DyNet](https://arxiv.org/pdf/1701.03980.pdf). DyNet: The Dynamic Neural Network Toolkit. Graham Neubig, Chris Dyer, Yoav Goldberg, Austin Matthews, Waleed Ammar, Antonios Anastasopoulos, Miguel Ballesteros, David Chiang, Daniel Clothiaux, Trevor Cohn, Kevin Duh, Manaal Faruqui, Cynthia Gan, Dan Garrette, Yangfeng Ji, Lingpeng Kong, Adhiguna Kuncoro, Gaurav Kumar, Chaitanya Malaviya, Paul Michel, Yusuke Oda, Matthew Richardson, Naomi Saphra, Swabha Swayamdipta, Pengcheng Yin. 2017

### 3/25
#### Required reading
- [PyTorch](https://papers.nips.cc/paper/2019/file/bdbca288fee7f92f2bfa9f7012727740-Paper.pdf). PyTorch: An Imperative Style, High-Performance
Deep Learning Library. NeurIPS 2019.
- [JANUS](https://www.usenix.org/system/files/nsdi19-jeong.pdf). JANUS: Fast and Flexible Deep Learning via Symbolic Graph Execution of Imperative Programs. Eunji Jeong, Sungwoo Cho, Gyeong-In Yu, Joo Seong Jeong, Dong-Jin Shin, Byung-Gon Chun. NSDI 2019.

#### Extra reading
- [AutoGraph](https://arxiv.org/pdf/1810.08061.pdf). AutoGraph: Imperative-Style Coding with Graph-based Performance. Dan Moldovan, James M Decker, Fei Wang, Andrew A Johnson, Brian K Lee, Zachary Nado, D Sculley, Tiark Rompf, Alexander B Witschko. MLSys 2019.
- [TFEager](https://mlsys.org/Conferences/2019/doc/2019/88.pdf). TensorFlow Eager: A Multi-Stage, Python Embedded DSL for Machine Learning. Akshay Agrawal, Akshay Naresh Modi, Alexandre Passos, Allen Lavoie, Ashish Agarwal, Asim Shankar, Igor Ganichev, Josh Levenberg, Mingsheng Hong, Rajat Monga, Shanqing Cai. MLSys 2019.

### 3/30
#### Required reading
- [Halide](https://people.csail.mit.edu/jrk/halide-pldi13.pdf). Halide: A Language and Compiler for Optimizing Parallelism, Locality, and Recomputation in Image Processing Pipelines. Jonathan Ragan-Kelley, Connelly Barnes, Andrew Adams, Sylvain Paris, Fredo Durand, Saman Amarasinghe. PLDI 2013.
- [TVM](https://www.usenix.org/system/files/osdi18-chen.pdf). An Automated End-to-End Optimizing Compiler for Deep Learning. Tianqi Chen, Thierry Moreau, Ziheng Jiang, Lianmin Zheng, Eddie Yan, Haichen Shen, Meghan Cowan, Leyuan Wang, Yuwei Hu, Luis Ceze, Carlos Guestrin, Arvind Krishnamurthy. OSDI 2018.

#### Extra reading
- [TC](https://arxiv.org/pdf/1802.04730.pdf). Tensor Comprehensions: Framework-Agnostic High-Performance Machine Learning Abstractions. Nicolas Vasilache, Oleksandr Zinenko, Theodoros Theodoridis, Priya Goyal, Zachary DeVito, William S. Moses, Sven Verdoolaege, Andrew Adams, Albert Cohen. 2018.
- [TACO](http://tensor-compiler.org/kjolstad-oopsla17-tensor-compiler.pdf). The Tensor Algebra Compiler. Kjolstad, Fredrik and Kamil, Shoaib and Chou, Stephen and Lugato, David and Amarasinghe, Saman. OOPSLA 2017.
- [Ansor](https://www.usenix.org/system/files/osdi20-zheng.pdf). Lianmin Zheng, Chengfan Jia, Minmin Sun, Zhao Wu, Cody Hao Yu, Ameer Haj-Ali, Yida Wang, Jun Yang, Danyang Zhuo, Koushik Sen, Joseph E. Gonzalez, Ion Stoica. Ansor: Generating High-Performance Tensor Programs for Deep Learning. OSDI 2020.
