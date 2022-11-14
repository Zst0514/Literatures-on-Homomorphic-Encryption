# Literature on Acceleration on Homomorphic Encryption

A reading list for Acceleration on Homomorphic Encryption, including but not limited to related research on software and hardware level. The list covers related papers, conferences, tools, books, blogs, courses and other resources. We have a [team of Maintaners](#Maintainers) responsible for maintainance, meanwhile also welcome contributions from anyone.

Literatures in this page are arranged from a classification perspective, including the following topics:
- [Literature on Graph Neural Networks Acceleration](#literature-on-graph-neural-networks-acceleration)
  - [Hardware Acceleration for Homomorphic Encryption](#Hardware-Acceleration-for-Homomorphic-Encryption)
  - [Soft/Hardware Codesign for Homomorphic Encryption](#Soft/Hardware-Codesign-for-Homomorphic-Encryption)
  - [Algorithmic Acceleration for Homomorphic Encryption](#Algorithmic-Acceleration-for-Homomorphic-Encryption)
  - [Surveys and Performance Analysis on Homomorphic Encryption](#Surveys-and-Performance-Analysis-on-Homomorphic-Encryption)
  - [Maintainers](#maintainers)

Click [here](./By-Time.md) to view these literatures in a reverse chronological order. You can also find [Related Conferences](./General%20Resources/Conference.md), [Graph Learning Tools](./General%20Resources/Frameworks%20%26%20Tools/), [Learning Materials on GNNs](./General%20Resources/Learning%20Materials) and Other Resources in [General Resources](./General%20Resources).



---
## Hardware Acceleration for Homomorphic Encryption

* [**HPCA 2019**] FPGA-Based High-Performance Parallel Architecture for Homomorphic Computing on Encrypted Data.
  
  >*Sujoy S, Furkan, T, Kimmo J, et al.* [[Paper]](https://ieeexplore.ieee.org/document/8675244)
  
* [**ISSCC 2022**] A_28nm_48KOPS_3.4J_Op_Agile_Crypto-Processor_for_Post Quantum_Cryptograph_on_Multi-Mathematical_Problems.
  
  >*Zhu Y, Wei S, Liu L et al.* [[Paper]](https://ieeexplore.ieee.org/document/9731783)
  
* [**ISCA 2022**] BTS: An Accelerator for Bootstrappable Fully Homomorphic Encryption.
  
  >*Kim S, Kim J, Ahn Jung et al.* [[Paper]](https://dl.acm.org/doi/10.1145/3470496.3527415)
  
* [**ISCA 2022**] CraterLake: A Hardware Accelerator for Efficient Unbounded Computation on Encrypted Data.
  
  >*Samardzic N, Feldmann A, Krastev A, et al.* [[Paper]](CraterLake: a hardware accelerator for efficient unbounded computation on encrypted data)
  
* [**DATE 2020**] A Flexible and Scalable NTT Hardware:Applications from Homomorphically Encrypted Deep Learning to Post-Quantum Cryptography.
  
  >*Mert A, Karabulut E, Aysu A, et al* [[Paper]](https://ieeexplore.ieee.org/document/9116470)
  
* [**DATE 2022**] Improving GNN-Based Accelerator Design Automation with Meta Learning. 
  
  >*Bai Y, Sohrabizadeh A, Sun Y, et al.* [[Paper]](https://vast.cs.ucla.edu/sites/default/files/publications/_DAC_22__GNN_DSE_MAML.pdf)
  
* [**DATE 2022**] Improving GNN-Based Accelerator Design Automation with Meta Learning. 
  
  >*Bai Y, Sohrabizadeh A, Sun Y, et al.* [[Paper]](https://vast.cs.ucla.edu/sites/default/files/publications/_DAC_22__GNN_DSE_MAML.pdf)
  
* [**CICC 2019**] A 55nm 50nJ_encode 13nJ_decode Homomorphic Encryption Crypto-Engine for IoT Nodes to Enable Secure Computation on Encrypted Data. 1-4.
  
  >*Yoon I, Cao N, Amaravati A, et al* [[Paper]](https://ieeexplore.ieee.org/document/8780277)
  
* [**CICC 2021**] A Low-Power Elliptic Curve Pairing Crypto-Processor for Secure Embedded Blockchain and Functional Encryption.
  
  >*Utsav Banerjee, Anantha P. Chandrakasan* [[Paper]](https://ieeexplore.ieee.org/document/9431552)
  
  [**TCAD 2021**] Model-Architecture Co-Design for High Performance Temporal GNN Inference on FPGA.
  
  >*Canto A, Kermani M, Azarderakhsh R, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9179769)
  
* [**DAC 2020**] CryptoPIM: In-memory Acceleration for Lattice-based Cryptographic Hardware. 
  
  >*Nejatollahi H, Gupta S, Dut N, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9218730)
  
* [**DAC 2021**] (Invited)Accelerating Fully Homomorphic Encryption with Processing in Memory.
  
  >*Saransh Gupta, Tajana Simunic Rosing* [[Paper]](https://ieeexplore.ieee.org/document/9586285/)
  
* [**DAC 2022**] MATCHA: A Fast and Energy-Efficient Accelerator for Fully Homomorphic Encryption over the Torus.
  
  >*Lei Jiang, Qian Lou, Nrushad Joshi* [[Paper]](https://dl.acm.org/doi/10.1145/3489517.3530435)
  
* [**ICCAD 2022**] Accelerating N-bit Operations over TFHE on Commodity CPU-FPGA.
  
  >*Nam K, Moon H, Paek Y, et al.* [[Paper]](https://dl.acm.org/doi/10.1016/j.sysarc.2022.102596)
  
* [**ICCAD 2022**] Fast and Compact Interleaved Modular Multiplication based on Carry Save Addition. 
  
  >*Mazonka O, Chielle E, Maniatakos M, et al* [[Paper]]( https://www.semanticscholar.org/paper/Faster-Interleaved-Modular-Multiplication-Based-on-Knezevic-Vercauteren/339dbecb72e03aacacdc8651b69a74f1f1dad232) 
  
* [**ICCAD 2022**] Inhale: Enabling High-Performance and Energy-Efficient In-SRAM Cryptographic Hash for IoT. 
  
  >*Jingyao Zhang, Elaheh Sadredini.* [[Paper]](https://arxiv.org/abs/2208.07570)
  
* [**ASPLOS 2020**] HEAX: An Architecture for Computing on Encrypted Data.
  
  >*M. Sadegh Riazi, Blake Pelton, Wei Dai, et al.* [[Paper]](HEAX: An Architecture for Computing on Encrypted Data)
  
* [**ASPLOS 2022**] CHOCO: Client-Optimized Algorithms and Acceleration for Encrypted Compute Offloading
  
  >*McKenzie van der Hagen, Brandon Lucia.* [[Paper]](https://dl.acm.org/doi/abs/10.1145/3503222.3507737)
  
* [**MICRO 2021**] F1: A Fast and Programmable Accelerator for Fully Homomorphic Encryption (Extended Version)
  
  >*Feldmann A, Samardzic N, Sanchez D, et al.* [[Paper]](https://dl.acm.org/doi/10.1145/3466752.3480070)
  
* [**TVLSI 2020**] Design and Implementation of Encryption/Decryption Architectures for BFV Homomorphic Encryption Scheme. 
  
  >*Ahmet Can Mert , ErdinÖztürk, and Erkay Savas* [[Paper]](https://ieeexplore.ieee.org/abstract/document/8866755)
  
* [**TVLSI 2020**] Computing-in-Memory for Performance and Energy-Efficient Homomorphic Encryption.

  >*Reis D,  Takeshita J, Xiaobo Sharon Hu.* [[Paper]](https://ieeexplore.ieee.org/document/9179010)

* [**TVLSI 2022**] A Highly Unified Reconfigurable Multicore Architecture to Speed Up NTT/INTT for Homomorphic Polynomial Multiplication.

  >*Su Y, Yang B, Liu Y, et al.*  [[Paper]](https://ieeexplore.ieee.org/abstract/document/9761841/)

* [**TVLSI 2022**] Efficient Homomorphic Convolution Designs on FPGA for Secure Inference.

  >*Xiao Hu, Minghao Li, Zhongfeng Wang, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9866023)

* [**TVLSI 2022**] VLSI Design of Advanced-Features AES Cryptoprocessor in the Framework of the European Processor Initiative.

  >*Nannipieri P, Matteo S, Fanucci L, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9631958/)

* [**ISCAS 2021**] A Multi-Layer Parallel Hardware Architecture for Homomorphic Computation in Machine Learning. 
  
  >*Guozhu Xin, Yifan Zhao, Jun Han* [[Paper]](http://arxiv.org/abs/2206.08536)
  
* [**ISCAS 2021**] High-throughput Polynomial Multiplier Architecture for Lattice-based Cryptography.

  >*Taishin Shimada, Makoto Ikeda* [[Paper]](https://ieeexplore.ieee.org/document/9401755/)

* [**ISCAS 2021**] BN-254 based Multi-Core, Multi-Pairing Crypto-Processor for Functional Encryption.

  >*Ryohei Nakayama, Makoto Ikeda* [[Paper]](https://ieeexplore.ieee.org/document/9401283/)

* [**TCAS-I 2020**] Lattice-Based Cryptoprocessor for CCA-Secure Identity-Based Encryption.

  >*Claudia P. Rentería-Mejía, Jaime Velasco-Medina* [[Paper]](https://ieeexplore.ieee.org/document/9046808)

* [**TCAS-I 2022**] NTT Architecture for a Linux-Ready RISC-V Fully-Homomorphic Encryption Accelerator.

  >*Rogério Paludo, Leonel Sousa.* [[Paper]](https://ieeexplore.ieee.org/document/9763876/)

* [**TCAS-I 2022**] ReMCA: A Reconfigurable Multi-Core Architecture for Full RNS Variant of BFV Homomorphic Evaluation.

  >*Yang Su, Yang B, Song-Yin Zhao, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9755024/)

* [**Access 2020**] FPGA-Based Hardware Accelerator for Leveled Ring-LWE Fully Homorphic Encryption. 

  >*Yang Su, Bailong Yang, Luogeng Tian, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9194003)

* [**Computer Science Machine Learning 2021**] FPGA-Based Hardware Accelerator for Leveled Ring-LWE Fully Homorphic Encryption. 

  >*Cheng X, Lu W, Chen S, et al.* [[Paper]](https://arxiv.org/abs/2107.13797)

* [**Computing Science Cryptography and Security 2020**] FPGA-Based Hardware Accelerator of Homomorphic Encryption for Efficient Federated Learning.

  >*Zhaoxiong Yang, Shuihai Hu, Kai Chen.* [[Paper]](https://arxiv.org/abs/2007.10560)

* 


---
## Soft/Hardware Codesign for Homomorphic Encryption


* [**DAC 2021**] Efficient Implementation of Finite Field Arithmetic for Binary Ring-LWE Post Quantum Cryptography Through a Novel Lookup-Table-Like Method. 

  >*Jiafeng Xie,Pengzhou He, Wujie Wen.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9586151/)
* [**DATE 2022**] coxHE: A software-hardware co-design framework for FPGA acceleration of homomorphic computation.

  >*Han M, Zhu Y, Lei Ju, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9774559)
* [**ISCA 2022**] Graphite: optimizing graph neural networks on CPUs through cooperative software-hardware techniques. 

  >*Gong Z, Ji H, Yao Y, et al.* [[Paper]](https://dl.acm.org/doi/10.1145/3470496.3527403)
* [**MICRO 2022**] ARK: Fully Homomorphic Encryption Accelerator with Runtime Data Generation and Inter-Operation Key Reuse.

  >*Kim J, Lee G, Ahn J, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9923889/)
* [**ESSCIRC 2022**] Configurable Energy-Efficient Lattice-Based PostQuantum Cryptography Processor for IoT Devices.

  >*Kim B, Park J, Sim J, et al* [[Paper]](https://ieeexplore.ieee.org/document/9911531/)
* [**ISCAS 2020**] Accelerating Post-Quantum Cryptography using an Energy-Efficient TLS Crypto-Processor.

  >*Utsav Banerjee, Siddharth Das, Anantha P. Chandrakasan* [[Paper]](https://ieeexplore.ieee.org/document/9180550)
* [**TVLSI 2020**] A Programmable SoC-Based Accelerator for Privacy-Enhancing Technologies and Functional Encryption.

  >*Milad Bahadori, Kimmo Järvinen.* [[Paper]]( https://ieeexplore.ieee.org/document/9153178/)
* [**HPDC 2022**] TLPGNN: A Lightweight Two-Level Parallelism Paradigm for Graph Neural Network Computation on GPU. 

  >*Fu Q, Ji Y, Huang H H.* [[Paper]](https://doi.org/10.1145/3502181.3531467)
* [**arXiv 2022**] Improved Aggregating and Accelerating Training Methods for Spatial Graph Neural Networks on Fraud Detection.
  >*Zeng Y, Tang J.* [[Paper]](http://arxiv.org/abs/2202.06580)
* [**arXiv 2022**] Marius++: Large-scale training of graph neural networks on a single machine. 
  >*Waleffe R, Mohoney J, Rekatsinas T, et al.* [[Paper]](https://arxiv.org/abs/2202.02365)
* [**CLUSTER 2021**] 2PGraph: Accelerating GNN Training over Large Graphs on GPU Clusters.
  >*Zhang L, Lai Z, Li S, et al.* [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9556026)
* [**JPDC  2021**] Accurate, efficient and scalable training of Graph Neural Networks. 
  >*Zeng H, Zhou H, Srivastava A, et al.* [[Paper]](https://www.sciencedirect.com/science/article/pii/S0743731520303579) [[GitHub]](https://github.com/GraphSAINT/GraphSAINT)
* [**JPDC  2021**] High performance GPU primitives for graph-tensor learning operations. 
  >*Zhang T, Kan W, Liu X Y.* [[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S0743731520304007)
* [**OSDI  2021**] Dorylus: Affordable, Scalable, and Accurate GNN Training with Distributed CPU Servers and Serverless Threads. 

  >*Thorpe J, Qiao Y, Eyolfson J, et al.* [[Paper]](https://arxiv.org/abs/2105.11118) [[GitHub]](https://github.com/uclasystem/dorylus)
* [**OSDI   2021**] GNNAdvisor: An Adaptive and Efﬁcient Runtime System for GNN Acceleration on GPUs 
  >*Wang Y, Feng B, Li G, et al.* [[Paper]](https://www.usenix.org/system/files/osdi21-wang-yuke.pdf) [[GitHub]](https://github.com/YukeWang96/OSDI21_AE)
* [**EuroSys 2021**] DGCL: an efficient communication library for distributed GNN training. 

  >*Cai Z, Yan X, Wu Y, et al.* [[Paper]](https://dl.acm.org/doi/abs/10.1145/3447786.3456233)
* [**EuroSys  2021**] FlexGraph: a flexible and efficient distributed framework for GNN training. 
  >*Wang L, Yin Q, Tian C, et al.* [[Paper]](https://dl.acm.org/doi/abs/10.1145/3447786.3456229) [[GitHub]](https://github.com/snudatalab/FlexGraph)
* [**EuroSys 2021**] Seastar: vertex-centric programming for graph neural networks. 
  >*Wu Y, Ma K, Cai Z, et al.* [[Paper]](https://doi.org/10.1145/3447786.3456247)
* [**TPDS  2021**] Efficient Data Loader for Fast Sampling-Based GNN Training on Large Graphs. 
  >*Bai Y, Li C, Lin Z, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9376972)
* [**GNNSys 2021**] FedGraphNN: A Federated Learning System and Benchmark for Graph Neural Networks.
  >*He C, Balasubramanian K, Ceyani E, et al.* [[Paper]](https://gnnsys.github.io/papers/GNNSys21_paper_3.pdf) [[Poster]](https://gnnsys.github.io/posters/GNNSys21_poster_3.pdf) [[GitHub]](https://github.com/FedML-AI/FedGraphNN)
* [**GNNSys 2021**] Graphiler: A Compiler for Graph Neural Networks.
  >*Xie Z, Ye Z, Wang M, et al.* [[Paper]](https://gnnsys.github.io/papers/GNNSys21_paper_10.pdf) [[Poster]](https://gnnsys.github.io/posters/GNNSys21_poster_10.pdf)
* [**GNNSys 2021**] IGNNITION: A framework for fast prototyping of Graph Neural Networks.
  >*Pujol Perich D, Suárez-Varela Maciá J R, Ferriol Galmés M, et al.* [[Paper]](https://gnnsys.github.io/papers/GNNSys21_paper_4.pdf) [[Poster]](https://gnnsys.github.io/posters/GNNSys21_poster_4.pdf)
* [**GNNSys 2021**] Load Balancing for Parallel GNN Training.
  >*Su Q, Wang M, Zheng D, et al* [[Paper]](https://gnnsys.github.io/papers/GNNSys21_paper_18.pdf) [[Poster]](https://gnnsys.github.io/posters/GNNSys21_poster_18.pdf)
* [**IPDPS  2021**] FusedMM: A Unified SDDMM-SpMM Kernel for Graph Embedding and Graph Neural Networks. 
  >*Rahman M K, Sujon M H, Azad A.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9460486) [[GitHub]](https://github.com/HipGraph/FusedMM)
* [**arXiv  2021**] PyTorch Geometric Temporal: Spatiotemporal Signal Processing with Neural Machine Learning Models. 
  >*Rozemberczki B, Scherer P, He Y, et al.* [[Paper]](https://arxiv.org/abs/2104.07788) [[GitHub]](https://github.com/benedekrozemberczki/pytorch_geometric_temporal)
* [**arXiv 2021**] QGTC: Accelerating Quantized GNN via GPU Tensor Core. 
  >*Wang Y, Feng B, Ding Y.* [[Paper]](http://arxiv.org/abs/2111.09547) [[GitHub]](https://github.com/YukeWang96/PPoPP22_QGTC)
* [**arXiv 2021**] TC-GNN: Accelerating Sparse Graph Neural Network Computation Via Dense Tensor Core on GPUs. 
  >*Wang Y, Feng B, Ding Y.* [[Paper]](http://arxiv.org/abs/2112.02052) [[GitHub]](https://github.com/YukeWang96/TCGNN-Pytorch)
* [**ICCAD 2020**] fuseGNN: accelerating graph convolutional neural network training on GPGPU. 
  >*Chen Z, Yan M, Zhu M, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9256702) [[GitHub]](https://github.com/apuaaChen/gcnLib)
* [**SC 2020**] FeatGraph: A Flexible and Efficient Backend for Graph Neural Network Systems. 
  >*Hu Y, Ye Z, Wang M, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9355318) [[Github]](https://github.com/amazon-research/FeatGraph)
* [**MLSys  2020**] Improving the Accuracy, Scalability, and Performance of  Graph Neural Networks with Roc. 

  >*Jia Z, Lin S, Gao M, et al.* [[Paper]](https://www-cs.stanford.edu/people/matei/papers/2020/mlsys_roc.pdf)
* [**CVPR 2020**] L2-GCN: Layer-Wise and Learned Efficient Training of Graph Convolutional Networks.
  >*You Y, Chen T, Wang Z, et al.* [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/You_L2-GCN_Layer-Wise_and_Learned_Efficient_Training_of_Graph_Convolutional_Networks_CVPR_2020_paper.html) 
* [**TPDS  2020**] EDGES: An Efficient Distributed Graph Embedding System on GPU Clusters. 
  >*Yang D, Liu J, Lai J.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9272876)
* [**AccML  2020**] GIN : High-Performance, Scalable Inference for Graph Neural Networks. 
  >*Fu Q, Huang H H.* [[Paper]](https://workshops.inf.ed.ac.uk/accml/papers/2020/AccML_2020_paper_6.pdf)
* [**SoCC  2020**] PaGraph: Scaling GNN training on large graphs via computation-aware caching. 

  >*Lin Z, Li C, Miao Y, et al.* [[Paper]](https://dl.acm.org/doi/abs/10.1145/3419111.3421281)
* [**IPDPS  2020**] Pcgcn: Partition-centric processing for accelerating graph convolutional network. 
  >*Tian C, Ma L, Yang Z, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9139807/)
* [**IA3  2020**] DistDGL: Distributed Graph Neural Network Training for Billion-Scale Graphs. 

  >*Zheng D, Ma C, Wang M, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9407264)
* [**CoRR  2019**] Deep Graph Library: Towards Efficient and Scalable Deep Learning on Graphs. 

  >*Wang M Y.* [[Paper]](https://arxiv.org/abs/1909.01315v2) [[GitHub]](https://github.com/dmlc/dgl/) [[Home Page]](https://www.dgl.ai/)
* [**ICLR  2019**] Fast Graph Representation Learning with PyTorch Geometric. 

  >*Fey M, Lenssen J E.* [[Paper]](https://arxiv.org/abs/1903.02428) [[GitHub]](https://github.com/rusty1s/pytorch_geometric) [[Documentation]](https://pytorch-geometric.readthedocs.io/en/latest/)
* [**KDD  2019**] AliGraph: a comprehensive graph neural network platform. 
  >*Yang H.* [[Paper]](https://dl.acm.org/doi/abs/10.1145/3292500.3340404) [[GitHub]](https://github.com/alibaba/graph-learn)
* [**SysML 2019**] PyTorch-BigGraph: A Large-scale Graph Embedding System. 

  >*Lerer A, Wu L, Shen J, et al.* [[Paper]](https://dl.acm.org/doi/abs/10.1145/3292500.3340404) [[GitHub]](https://github.com/facebookresearch/PyTorch-BigGraph)
* [**ATC  2019**] NeuGraph: Parallel Deep Neural Network Computation on Large Graphs. 
  >*Ma L, Yang Z, Miao Y, et al.* [[Paper]](https://www.usenix.org/conference/atc19/presentation/ma)
* [**arXiv 2018**] Relational inductive biases, deep learning, and graph networks. 
  >*Battaglia P W, Hamrick J B, Bapst V, et al.* [[Paper]](https://arxiv.org/abs/1806.01261) [[GitHub]](https://github.com/deepmind/graph_nets)

---
## Algorithmic Acceleration for Homomorphic Encryption


* [**HPCA 2021**] Cheetah: Optimizing and Accelerating Homomorphic Encryption for Private Inference.

  >*Reagen B, Choi W, Brooks D, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9407118)

* [**DATE 2021**] Real-time Private Membership Test using Homomorphic Encryption.
  
  >*Eduardo Chielle, Homer Gamil, Michail Maniatakos.* [[Paper]](https://ieeexplore.ieee.org/document/9473968/)
  
* [**TCAD 2020**] Efficient Comparison and Addition for FHE With Weighted Computational Complexity Model.
  
  >*Neng Zhang, Shaojun Wei, Leibo Liu, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9224873/)
  
* [**TCAD 2022**] Efficient FHE Radix-2 Arithmetic Operations Based on Redundant Encoding. 
  
  >*Hou Z, Shaojun Wei, Leibo Liu, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9502150)
  
* [**ICCAD 2022**] Accelerating Fully Homomorphic Encryption by Bridging Modular and Bit-Level Arithmetic.
  
  >*Chielle E, Mazonka O, Maniatakos M* [[Paper]](https://arxiv.org/abs/2204.12201)
  
* [**ISCAS 2020**] VLSI Architecture of Polynomial Multiplication for BGV Fully Homomorphic Encryption.
  
  >*Hsu H and Shieh M* [[Paper]](https://arxiv.org/pdf/2203.10428.pdf) [](https://ieeexplore.ieee.org/document/9181192/)
  
* [**ISCAS 2021**] On Compare-and-Swap Optimization for Fully Homomorphic Encrypted Data.
  
  >*Chien-Chih Huang, Jyun-Neng Ji and Ming-Der Shieh.* [[Paper]](https://ieeexplore.ieee.org/document/9401078/)
  
* [**TCAS-I 2020**] Design and Implementation of a Low-Latency Modular Multiplication Algorithm.
  
  >*Erdinç Öztürk*  [[Paper]](https://ieeexplore.ieee.org/document/8968620)
  
* [**TCAS-I 2021**] Radix-2w Arithmetic for Scalar Multiplication in Elliptic Curve Cryptography. 
  
  >*Abdelkrim Kamel Oudjida, Ahmed Liacha.* [[Paper]](https://ieeexplore.ieee.org/document/9349769)
  
* [**TCAS-I 2022**] Faster NTRU on ARM Cortex-M4 With TMVP-Based Multiplication. 
  
  >*Irem Keskinkurt Paksoy, Murat Cenk.* [[Paper]](https://ieeexplore.ieee.org/document/9835023/) 
  
* [**ICML 2022**] GraphFM: Improving Large-Scale GNN Training via Feature Momentum. 
  >*Yu H, Wang L, Wang B, et al.* [[Paper]](https://arxiv.org/abs/2206.07161) [[GitHub]](https://github.com/divelab/DIG)
  
* [**MLSys 2022**] BNS-GCN: Efficient Full-Graph Training of Graph Convolutional Networks with Boundary Node Sampling. 
  >*Wan C, Li Y, Li A, et al.* [[Paper]](https://arxiv.org/pdf/2203.10983.pdf) [[GitHub]](https://github.com/RICE-EIC/BNS-GCN)
  
* [**MLSys 2022**] Graphiler: Optimizing Graph Neural Networks with Message Passing Data Flow Graph. 
  >*Xie Z, Wang M, Ye Z, et al.* [[Paper]](https://proceedings.mlsys.org/paper/2022/hash/a87ff679a2f3e71d9181a67b7542122c-Abstract.html)
  
* [**MLSys 2022**] Sequential Aggregation and Rematerialization: Distributed Full-batch Training of Graph Neural Networks on Large Graphs. 
  >*Mostafa H.* [[Paper]](https://proceedings.mlsys.org/paper/2022/hash/5fd0b37cd7dbbb00f97ba6ce92bf5add-Abstract.html) [[GitHub]](https://github.com/intellabs/sar)
  
* [**WWW 2022**] Fograph: Enabling Real-Time Deep Graph Inference with Fog Computing. 
  >*Zeng L, Huang P, Luo K, et al.* [[Paper]](https://dl.acm.org/doi/fullHtml/10.1145/3485447.3511982)
  
* [**www 2022**] PaSca: A Graph Neural Architecture Search System under the Scalable Paradigm. 
  >*Zhang W, Shen Y, Lin Z, et al.* [[Paper]](https://dl.acm.org/doi/10.1145/3485447.3511986)
  
* [**www 2022**] Resource-Efficient Training for Large Graph Convolutional Networks with Label-Centric Cumulative Sampling. 
  >*Lin M, Li W, Li D, et al.* [[Paper]](https://dl.acm.org/doi/10.1145/3485447.3512165)
  
* [**FPGA 2022**] DecGNN: A Framework for Mapping Decoupled GNN Models onto CPU-FPGA Heterogeneous Platform. 
  >*Zhang B, Zeng H, Prasanna V K.* [[Paper]]( https://dl.acm.org/doi/abs/10.1145/3490422.3502326)
  
* [**FPGA 2022**] HP-GNN: Generating High Throughput GNN Training Implementation on CPU-FPGA Heterogeneous Platform. 
  >*Lin Y C, Zhang B, Prasanna V.* [[Paper]]( https://dl.acm.org/doi/pdf/10.1145/3490422.3502359)
  
* [**arXiv 2022**] SUGAR: Efficient Subgraph-level Training via Resource-aware Graph Partitioning. 
  >*Xue Z, Yang Y, Yang M, et al.* [[Paper]](https://arxiv.org/pdf/2202.00075.pdf)
  
* [**CAL 2022**] Characterizing and Understanding Distributed GNN Training on GPUs. 
  >*Lin H, Yan M, Yang X, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9760056)
  
* [**ICLR  2021**] Degree-Quant: Quantization-Aware Training for Graph Neural Networks. 
  >*Tailor S A, Fernandez-Marques J, Lane N D.* [[Paper]](https://arxiv.org/abs/2008.05000)
  
* [**ICLR 2021 Open Review**] FGNAS: FPGA-AWARE GRAPH NEURAL ARCHITECTURE SEARCH. 
  >*Lu Q, Jiang W, Jiang M, et al.* [[Paper]](https://openreview.net/pdf?id=cq4FHzAz9eA)
  
* [**ICML 2021**] GraphNorm: A Principled Approach to Accelerating Graph Neural Network Training. 
  >*Cai T, Luo S, Xu K, et al.* [[Paper]](http://proceedings.mlr.press/v139/cai21e/cai21e.pdf)
  
* [**ICML 2021**] Optimization of Graph Neural Networks: Implicit Acceleration by Skip Connections and More Depth. 
  >*Xu K, Zhang M, Jegelka S, et al.* [[Paper]](http://proceedings.mlr.press/v139/xu21k/xu21k.pdf)
  
* [**KDD 2021**] DeGNN: Improving Graph Neural Networks with Graph Decomposition. 
  >*Miao X, Gürel N M, Zhang W, et al.* [[Paper]](https://dl.acm.org/doi/10.1145/3447548.3467312)
  
* [**KDD 2021**] Performance-Adaptive Sampling Strategy Towards Fast and Accurate Graph Neural Networks. 
  >*Yoon M, Gervet T, Shi B, et al.* [[Paper]](https://dl.acm.org/doi/10.1145/3447548.3467284)
  
* [**KDD 2021**] Global Neighbor Sampling for Mixed CPU-GPU Training on Giant Graphs. 
  >*Dong J, Zheng D, Yang L F, et al.* [[Paper]](https://dl.acm.org/doi/10.1145/3447548.3467437)
  
* [**CVPR  2021**] Binary Graph Neural Networks. 
  >*Bahri M, Bahl G, Zafeiriou S.* [[Paper]](https://arxiv.org/abs/2012.15823)
  
* [**CVPR  2021**] Bi-GCN: Binary Graph Convolutional Network. 
  >*Wang J, Wang Y, Yang Z, et al.* [[Paper]](https://arxiv.org/abs/2010.07565) [[GitHub]](https://github.com/bywmm/Bi-GCN)
  
* [**NeurIPS 2021**] Graph Differentiable Architecture Search with Structure Learning. 
  >*Qin Y, Wang X, Zhang Z, et al.* [[Paper]](https://papers.nips.cc/paper/2021/file/8c9f32e03aeb2e3000825c8c875c4edd-Paper.pdf)
  
* [**ICCAD 2021**] G-CoS: GNN-Accelerator Co-Search Towards Both Better Accuracy and Efficiency. 
  >*Zhang Y, You H, Fu Y, et al.* [[Paper]](https://arxiv.org/pdf/2109.08983.pdf)
  
* [**GNNSys 2021**] Efficient Data Loader for Fast Sampling-based GNN Training on Large Graphs.
  >*Bai Y, Li C, Lin Z, et al.* [[Paper]](https://gnnsys.github.io/papers/GNNSys21_paper_8.pdf) [[Poster]](https://gnnsys.github.io/posters/GNNSys21_poster_8.pdf)
  
* [**GNNSys 2021**] Effiicent Distribution for Deep Learning on Large Graphs.
  >*Hoang L, Chen X, Lee H, et al.* [[Paper]](https://gnnsys.github.io/papers/GNNSys21_paper_16.pdf) [[Poster]](https://gnnsys.github.io/posters/GNNSys21_poster_16.pdf)
  
* [**GNNSys 2021**] Adaptive Filters and Aggregator Fusion for Efficient Graph Convolutions.
  >*Tailor S A, Opolka F L, Lio P, et al.* [[Paper]](https://arxiv.org/abs/2104.01481) [[GitHub]](https://github.com/shyam196/egc)
  
* [**PMLR 2021**] A Unified Lottery Ticket Hypothesis for Graph Neural Networks. 
  >*Chen T, Sui Y, Chen X, et al.* [[Paper]](http://proceedings.mlr.press/v139/chen21p.html)
  
* [**PVLDB 2021**] Accelerating Large Scale Real-Time GNN Inference using Channel Pruning. 
  >*Zhou H, Srivastava A, Zeng H, et al.* [[Paper]](https://doi.org/10.14778/3461535.3461547) [[GitHub]](https://github.com/tedzhouhk/GCNP)
  
* [**SC 2021**] Efficient scaling of dynamic graph neural networks.
  >*Chakaravarthy V T, Pandian S S, Raje S, et al.* [[Paper]](https://doi.org/10.1145/3458817.3480858)
  
* [**RTAS 2021**] Optimizing Memory Efficiency of Graph Neural Networks on Edge Computing Platforms. 
  >*Zhou A, Yang J, Gao Y, et al.* [[Paper]](https://arxiv.org/abs/2104.03058) [[GitHub]](https://github.com/BUAA-CI-Lab/GNN-Feature-Decomposition)
  
* [**ICDM 2021**] GraphANGEL: Adaptive aNd Structure-Aware Sampling on Graph NEuraL Networks. 
  
  >*Peng J, Shen Y, Chen L.* [[Paper]](https://ieeexplore.ieee.org/document/9679081)
  
* [**GLSVLSI 2021**] Co-Exploration of Graph Neural Network and Network-on-Chip Design Using AutoML. 
  >*Manu D, Huang S, Ding C, et al.* [[Paper]](https://dl.acm.org/doi/abs/10.1145/3453688.3461741)
  
* [**arXiv 2021**] Edge-featured Graph Neural Architecture Search.
  >*Cai S, Li L, Han X, et al.* [[Paper]](http://arxiv.org/abs/2109.01356)
  
* [**arXiv 2021**] GNNSampler: Bridging the Gap between Sampling Algorithms of GNN and Hardware. 
  >*Liu X, Yan M, Song S, et al.* [[Paper]](https://arxiv.org/abs/2108.11571v1) [[GitHub]](https://github.com/temp-gimlab/gnnsampler)
  
* [**KDD  2020**] TinyGNN: Learning Efficient Graph Neural Networks. 
  >*Yan B, Wang C, Guo G, et al.* [[Paper]](https://dl.acm.org/doi/abs/10.1145/3394486.3403236)
  
* [**ICLR 2020**] GraphSAINT: Graph Sampling Based Inductive Learning Method. 
  >*Zeng H, Zhou H, Srivastava A, et al.* [[Paper]](https://arxiv.org/pdf/1907.04931) [[GitHub]](https://github.com/GraphSAINT/GraphSAINT)
  
* [**NeurIPS 2020**] Gcn meets gpu: Decoupling “when to sample” from “how to sample”.
  >*Ramezani M, Cong W, Mahdavi M, et al.* [[Paper]](https://proceedings.neurips.cc/paper/2020/file/d714d2c5a796d5814c565d78dd16188d-Paper.pdf)
  
* [**SC 2020**] Reducing Communication in Graph Neural Network Training. 
  >*Tripathy A, Yelick K, Buluç A.* [[Paper]](https://arxiv.org/abs/2005.03300) [[GitHub]](https://github.com/PASSIONLab/gnn_training)
  
* [**ICTAI 2020**] SGQuant: Squeezing the Last Bit on Graph Neural Networks with Specialized Quantization. 
  
  >*Feng B, Wang Y, Li X, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9288186)
  
* [**arXiv 2020**] Learned Low Precision Graph Neural Networks. 
  >*Zhao Y, Wang D, Bates D, et al.* [[Paper]](https://www.euromlsys.eu/pub/zhao21euromlsys.pdf)
  
* [**IPDPS 2019**] Accurate, efficient and scalable graph embedding. 
  >*Zeng H, Zhou H, Srivastava A, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/8820993)




---
## Surveys and Performance Analysis on Homomorphic Encryption

* [**DAC 2020**] ROMEO: Conversion and Evaluation of HDL Designs in the Encrypted Domain.
  
  >*Charles Gouert and Nektarios Georgios Tsoutsos.* [[Paper]](https://ieeexplore.ieee.org/document/9218579/)
* [**arXiv 2022**] Parallel and Distributed Graph Neural Networks: An In-Depth Concurrency Analysis. 
  >*Besta M, Hoefler T.* [[Paper]](https://arxiv.org/abs/2205.09702)
* [**arXiv 2022**] Survey on Graph Neural Network Acceleration: An Algorithmic Perspective. 
  
  >*Liu X, Yan M, Deng L, et al.* [[Paper]]( https://arxiv.org/pdf/2202.04822)
* [**GNNSys 2021**] Analyzing the Performance of Graph Neural Networks with Pipe Parallelism.
  >*Dearing M T, Wang X.* [[Paper]](https://gnnsys.github.io/papers/GNNSys21_paper_12.pdf) [[Poster]](https://gnnsys.github.io/posters/GNNSys21_poster_12.pdf)
* [**IJCAI 2021**] Automated Machine Learning on Graphs: A Survey. 
  >*Zhang Z, Wang X, Zhu W.* [[Paper]](https://arxiv.org/abs/2103.00742)
* [**PPoPP 2021**] Understanding and bridging the gaps in current GNN performance optimizations. 
  >*Huang K, Zhai J, Zheng Z, et al.* [[Paper]](https://dl.acm.org/doi/abs/10.1145/3437801.3441585)
* [**ISCAS 2021**] Characterizing the Communication Requirements of GNN Accelerators: A Model-Based Approach. 
  
  >*Guirado R, Jain A, Abadal S, et al.* [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9401612)
* [**ISPASS  2021**] GNNMark: A Benchmark Suite to Characterize Graph Neural Network Training on GPUs. 
  >*Baruah T, Shivdikar K, Dong S, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9408205)
* [**ISPASS  2021**] Performance Analysis of Graph Neural Network Frameworks. 
  
  >*Wu J, Sun J, Sun H, et al.* [[Paper]](https://www.semanticscholar.org/paper/Performance-Analysis-of-Graph-Neural-Network-Wu-Sun/b6da3ab0a6e710f16e11e5890818a107d1d5735c)
* [**CAL 2021**] Making a Better Use of Caches for GCN Accelerators with Feature Slicing and Automatic Tile Morphing. 
  >*Yoo M, Song J, Lee J, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9461595/)
* [**arXiv 2021**] Understanding GNN Computational Graph: A Coordinated Computation, IO, and Memory Perspective. 
  >*Zhang H, Yu Z, Dai G, et al.* [[Paper]](http://arxiv.org/abs/2110.09524)
* [**arXiv 2021**] Understanding the Design Space of Sparse/Dense Multiphase Dataflows for Mapping Graph Neural Networks on Spatial Accelerators. 
  >*Garg R, Qin E, Muñoz-Martínez F, et al.* [[Paper]](https://arxiv.org/pdf/2103.07977)
* [**arXiv 2021**] A Taxonomy for Classification and Comparison of Dataflows for GNN Accelerators. 
  >*Garg R, Qin E, Martínez F M, et al.* [[Paper]](https://arxiv.org/abs/2103.07977)
* [**arXiv  2021**] Graph Neural Networks: Methods, Applications, and Opportunities. 
  >*Waikhom L, Patgiri R.* [[Paper]](http://arxiv.org/abs/2108.10733)
* [**arXiv 2021**] Sampling methods for efficient training of graph convolutional networks: A survey. 
  >*Liu X, Yan M, Deng L, et al.* [[Paper]](https://arxiv.org/abs/2103.05872)
* [**KDD 2020**] Deep Graph Learning: Foundations, Advances and Applications. 
  >*Rong Y, Xu T, Huang J, et al.* [[Paper]](https://dl.acm.org/doi/10.1145/3394486.3406474)
* [**TKDE 2020**] Deep Learning on Graphs: A Survey. 
  
  >*Zhang Z, Cui P, Zhu W.*[[paper]](https://ieeexplore.ieee.org/abstract/document/9039675)
* [**CAL 2020**] Characterizing and Understanding GCNs on GPU. 
  >*Yan M, Chen Z, Deng L, et al.* [[Paper]](https://arxiv.org/abs/2010.00130)
* [**arXiv 2020**] Computing Graph Neural Networks: A Survey from Algorithms to Accelerators. 
  >*Abadal S, Jain A, Guirado R, et al.* [[Paper]](https://arxiv.org/abs/2010.00130)











---
###Maintainers

- Ao Zhou, Beihang University. [[GitHub]](https://github.com/ZhouAo-ZA)
- Yingjie Qi, Beihang University. [[GitHub]](https://github.com/Kevin7Qi)
- Tong Qiao, Beihang University. [[GitHub]](https://github.com/qiaotonggg)



