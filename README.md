# AI Systems Spring 2021

## Announcements

## Schedule (TBD)

| Week           | Lecture                                                      | 
| -------------- | ------------------------------------------------------------ | 
| Week1 3.2/4    | Course overview.<br />ML infrastructure case study (Guest lecture). | 
| Week2 3.9/11   | MLSys. Facebook AI Infra.<br />AI Hardware: GPU (Guest lecture), TPU |  
| Week3 3.16/18  | ML lifecycles. Hidden technical debt.<br />Benchmarks: MLPerf. GPU Profiling<br />Large-scale recommendation system (Guest lecture)| 
| Week4 3.23/25  | ML frameworks: TensorFlow, PyTorch, JANUS. </br>AI for Mission Critical Applications (Geust lecture)|
| Week5 3.30/4.1 | ML Compiler: Halide, TVM.                                    | 
| Week6 4.6/8    | ML graph optimization: TASO, FlexFlow, NeoCPU.               |  
| Week7 4.13/15  | ML scheduling optimization: Nimble, Rammer.                  |  
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
- [PyTorch](https://papers.nips.cc/paper/2019/file/bdbca288fee7f92f2bfa9f7012727740-Paper.pdf). PyTorch: An Imperative Style, High-Performance
Deep Learning Library. NeurIPS 2019.

#### Extra reading
- [TenorFlowDCF](https://arxiv.org/pdf/1805.01772.pdf). Dynamic Control Flow in Large-Scale Machine Learning. Yuan Yu, Martin Abadi, Paul Barham, Eugene Brevdo, Mike Burrows, Andy Davis, Jeff Dean, Sanjay Ghemawat, Tim Harley, Peter Hawkins, Michael Isard, Manjunath Kudlur, Rajat Monga, Derek Murray, Xiaoqiang Zheng. EuroSys 2018.
- [RDAG](http://spl.snu.ac.kr/wp-content/uploads/2018/04/eurosys18-rdag.pdf). Improving the Expressiveness of Deep Learning Frameworks with Recursion. Eunji Jeong*, Joo Seong Jeong*, Soojeong Kim, Gyeong-In Yu, Byung-Gon Chun. EuroSys 2018.
- [DyNet](https://arxiv.org/pdf/1701.03980.pdf). DyNet: The Dynamic Neural Network Toolkit. Graham Neubig, Chris Dyer, Yoav Goldberg, Austin Matthews, Waleed Ammar, Antonios Anastasopoulos, Miguel Ballesteros, David Chiang, Daniel Clothiaux, Trevor Cohn, Kevin Duh, Manaal Faruqui, Cynthia Gan, Dan Garrette, Yangfeng Ji, Lingpeng Kong, Adhiguna Kuncoro, Gaurav Kumar, Chaitanya Malaviya, Paul Michel, Yusuke Oda, Matthew Richardson, Naomi Saphra, Swabha Swayamdipta, Pengcheng Yin. 2017
