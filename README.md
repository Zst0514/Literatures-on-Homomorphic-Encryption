# Literature on Homomorphic Encryption Acceleration

A reading list for Acceleration on Homomorphic Encryption, including but not limited to related research on software and hardware level. The list covers related papers, conferences, tools, books, blogs, courses and other resources. We have a [team of Maintaners](#Maintainers) responsible for maintainance, meanwhile also welcome contributions from anyone.

Literatures in this page are arranged from a classification perspective, including the following topics:
- [Literature on Graph Neural Networks Acceleration](#Literature-on-Homomorphic-Encryption-Acceleration)
  - [Hardware Acceleration for Homomorphic Encryption](#Hardware-Acceleration-for-Homomorphic-Encryption)
  - [System Designs for Homomorphic Encryption](#System-Designs-for-Homomorphic-Encryption)
  - [Algorithmic Acceleration for Homomorphic Encryption](#Algorithmic-Acceleration-for-Homomorphic-Encryption)
  - [Surveys and Performance Analysis on Homomorphic Encryption](#Surveys-and-Performance-Analysis-on-Homomorphic-Encryption)
  - [Maintainers](#maintainers)

Click [here](./By-Time.md) to view these literatures in a reverse chronological order. You can also find [Related Conferences](./General%20Resources/Conference.md), [Homomorphic Encryption Learning Tools](./General%20Resources/Frameworks%20%26%20Tools/), [Learning Materials on Homomorphic Encryption](./General%20Resources/Learning%20Materials) and Other Resources in [General Resources](./General%20Resources).



---
## Hardware Acceleration for Homomorphic Encryption

* [**HPCA 2019**]  [**BFV**] FPGA-Based High-Performance Parallel Architecture for Homomorphic Computing on Encrypted Data.
  
  >*Sujoy S, Furkan, T, Kimmo J, et al.* [[Paper]](https://ieeexplore.ieee.org/document/8675244)
  
* [**ISSCC 2022**] [**CKKS**] A 28nm 48KOPS 3.4J Op Agile Crypto-Processor for Post Quantum Cryptograph on Multi Mathematical Problems.
  
  >*Zhu Y, Wei S, Liu L et al.* [[Paper]](https://ieeexplore.ieee.org/document/9731783)
  
* [**ISCA 2022**] [**CKKS**] BTS: An Accelerator for Bootstrappable Fully Homomorphic Encryption.
  
  >*Kim S, Kim J, Ahn Jung et al.* [[Paper]](https://dl.acm.org/doi/10.1145/3470496.3527415)
  
* [**ISCA 2022**] [**FHE**] CraterLake: A Hardware Accelerator for Efficient Unbounded Computation on Encrypted Data.
  
  >*Samardzic N, Feldmann A, Krastev A, et al.* [[Paper]](https://people.csail.mit.edu/devadas/pubs/craterlake.pdf)
  
* [**DATE 2020**] [**CKKS**] A Flexible and Scalable NTT Hardware:Applications from Homomorphically Encrypted Deep Learning to Post-Quantum Cryptography.
  
  >*Mert A, Karabulut E, Aysu A, et al* [[Paper]](https://ieeexplore.ieee.org/document/9116470)
  
* [**CICC 2019**] [**NTT**] A 55nm 50nJ_encode 13nJ_decode Homomorphic Encryption Crypto-Engine for IoT Nodes to Enable Secure Computation on Encrypted Data. 1-4.
  
  >*Yoon I, Cao N, Amaravati A, et al* [[Paper]](https://ieeexplore.ieee.org/document/8780277)
  
* [**CICC 2021**] [**Pairing**] A Low-Power Elliptic Curve Pairing Crypto-Processor for Secure Embedded Blockchain and Functional Encryption.
  
  >*Utsav Banerjee, Anantha P. Chandrakasan* [[Paper]](https://ieeexplore.ieee.org/document/9431552)
  
* [**TCAD 2021**] [**PQC**] Model-Architecture Co-Design for High Performance Temporal GNN Inference on FPGA.
  
  >*Canto A, Kermani M, Azarderakhsh R, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9179769)
  
* [**DAC 2020**] [**NTT**] CryptoPIM: In-memory Acceleration for Lattice-based Cryptographic Hardware. 
  
  >*Nejatollahi H, Gupta S, Dut N, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9218730)
  
* [**DAC 2021**] [**FHE-PIM**] (Invited)Accelerating Fully Homomorphic Encryption with Processing in Memory.
  
  >*Saransh Gupta, Tajana Simunic Rosing* [[Paper]](https://ieeexplore.ieee.org/document/9586285/)
  
* [**DAC 2022**] [**TFHE**] MATCHA: A Fast and Energy-Efficient Accelerator for Fully Homomorphic Encryption over the Torus.
  
  >*Lei Jiang, Qian Lou, Nrushad Joshi* [[Paper]](https://dl.acm.org/doi/10.1145/3489517.3530435)
  
* [**ICCAD 2022**] [**TFHE**] Accelerating N-bit Operations over TFHE on Commodity CPU-FPGA.
  
  >*Nam K, Moon H, Paek Y, et al.* [[Paper]](https://dl.acm.org/doi/10.1016/j.sysarc.2022.102596)
  
* [**ICCAD 2022**] [**Polynomial Multiplication**] Fast and Compact Interleaved Modular Multiplication based on Carry Save Addition. 
  
  >*Mazonka O, Chielle E, Maniatakos M, et al* [[Paper]]( https://www.semanticscholar.org/paper/Faster-Interleaved-Modular-Multiplication-Based-on-Knezevic-Vercauteren/339dbecb72e03aacacdc8651b69a74f1f1dad232) 
  
* [**ICCAD 2022**] [**In-SRAM hash**] Inhale: Enabling High-Performance and Energy-Efficient In-SRAM Cryptographic Hash for IoT. 
  
  >*Jingyao Zhang, Elaheh Sadredini.* [[Paper]](https://arxiv.org/abs/2208.07570)
  
* [**ASPLOS 2020**] [**CKKS**] HEAX: An Architecture for Computing on Encrypted Data.
  
  >*M. Sadegh Riazi, Blake Pelton, Wei Dai, et al.* [[Paper]](https://arxiv.org/abs/1909.09731)
  
* [**ASPLOS 2022**] [**CKKS, BFV**] CHOCO: Client-Optimized Algorithms and Acceleration for Encrypted Compute Offloading
  
  >*McKenzie van der Hagen, Brandon Lucia.* [[Paper]](https://dl.acm.org/doi/abs/10.1145/3503222.3507737)
  
* [**MICRO 2021**] [**CKKS**] F1: A Fast and Programmable Accelerator for Fully Homomorphic Encryption (Extended Version)
  
  >*Feldmann A, Samardzic N, Sanchez D, et al.* [[Paper]](https://dl.acm.org/doi/10.1145/3466752.3480070)
  
* [**TVLSI 2020**] [**BFV**] Design and Implementation of Encryption/Decryption Architectures for BFV Homomorphic Encryption Scheme. 
  
  >*Ahmet Can Mert , ErdinÖztürk, and Erkay Savas* [[Paper]](https://ieeexplore.ieee.org/abstract/document/8866755)
  
* [**TVLSI 2020**] [**BFV**] Computing-in-Memory for Performance and Energy-Efficient Homomorphic Encryption.

  >*Reis D,  Takeshita J, Xiaobo Sharon Hu.* [[Paper]](https://ieeexplore.ieee.org/document/9179010)

* [**TVLSI 2022**] [**BFV, CKKS**] A Highly Unified Reconfigurable Multicore Architecture to Speed Up NTT/INTT for Homomorphic Polynomial Multiplication.

  >*Su Y, Yang B, Liu Y, et al.*  [[Paper]](https://ieeexplore.ieee.org/abstract/document/9761841/)

* [**TVLSI 2022**] [**BFV**] Efficient Homomorphic Convolution Designs on FPGA for Secure Inference.

  >*Xiao Hu, Minghao Li, Zhongfeng Wang, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9866023)

* [**TVLSI 2022**] [**AES**] VLSI Design of Advanced-Features AES Cryptoprocessor in the Framework of the European Processor Initiative.

  >*Nannipieri P, Matteo S, Fanucci L, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9631958/)

* [**ISCAS 2021**] [**NTT, RNS** ] A Multi-Layer Parallel Hardware Architecture for Homomorphic Computation in Machine Learning. 
  
  >*Guozhu Xin, Yifan Zhao, Jun Han* [[Paper]](http://arxiv.org/abs/2206.08536)
  
* [**ISCAS 2021**] [**Polynomial Multiplication**] High-throughput Polynomial Multiplier Architecture for Lattice-based Cryptography.

  >*Taishin Shimada, Makoto Ikeda* [[Paper]](https://ieeexplore.ieee.org/document/9401755/)

* [**ISCAS 2021**] [**BN curve**] BN-254 based Multi-Core, Multi-Pairing Crypto-Processor for Functional Encryption.

  >*Ryohei Nakayama, Makoto Ikeda* [[Paper]](https://ieeexplore.ieee.org/document/9401283/)

* [**HEPC 2014**] [**FHE**] An FPGA co-processor implementation of Homomorphic Encryption.

  >*David B, John G, Kurt R, et al.* [[Paper]](https://ieee-hpec.org/2014/CD/index_htm_files/FinalPapers/38.pdf)

* [**ASAP 2015**] [**Bootstrapping**] Accelerating Bootstrapping in FHEW using GPUs.

  >*Moon L, Yongje L, Jung H*et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/7245720)

* [**DSD 2019**] [**NTT**] Design and Implementation of a Fast and Scalable NTT-Based Polynomial Multiplier Architecture.

  >*Ahmet Can Mert, Erdinc Ozturk, Erkay Savas.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/8875148)

* [**FCCM  2020**] [**NTT, Bootstrapping**] Hardware Architecture of a Number Theoretic Transform for a Bootstrappable RNS-based Homomorphic Encryption Scheme.

  >*Sunwoong K, Keewoo L, Wonhee C, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9114594)

* [**TCAS-I 2020**] [**Modular Multiplication**] Lattice-Based Cryptoprocessor for CCA-Secure Identity-Based Encryption.

  >*Claudia P. Rentería-Mejía, Jaime Velasco-Medina* [[Paper]](https://ieeexplore.ieee.org/document/9046808)

* [**TCAS-I 2022**] [**NTT**] NTT Architecture for a Linux-Ready RISC-V Fully-Homomorphic Encryption Accelerator.

  >*Rogério Paludo, Leonel Sousa.* [[Paper]](https://ieeexplore.ieee.org/document/9763876/)

* [**TCAS-I 2022**] [**BFV**] ReMCA: A Reconfigurable Multi-Core Architecture for Full RNS Variant of BFV Homomorphic Evaluation.

  >*Yang Su, Yang B, Song-Yin Zhao, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9755024/)

* [**IEEE Access 2020**] [**BGV**] FPGA-Based Hardware Accelerator for Leveled Ring-LWE Fully Homorphic Encryption. 

  >*Yang Su, Bailong Yang, Luogeng Tian, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9194003)

* [**T-C 2020**] [**FHE**] HEAWS: An Accelerator for Homomorphic Encryption on the Amazon AWS FPGA.

  >*Furkan Turan, Sujoy Sinha Roy, and Ingrid Verbauwhede* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9072637)

* [**T-C 2015**] [**FHE**] Accelerating Fully Homomorphic Encryption in Hardware.

  >*Yarkın Doroz, Erdinc Ozturk, and Berk Sunar* [[Paper]](https://ieeexplore.ieee.org/abstract/document/6871300)

* [**TETCI 2017**] [**FHE, CRT**] Designing an FPGA-Accelerated Homomorphic Encryption Co-Processor.,

  >*David C, Kurt Rf and Daniel S.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/6871300)
  
* [**Computer Science Machine Learning 2021**] [**Paillier**] FPGA-Based Hardware Accelerator for Leveled Ring-LWE Fully Homorphic Encryption. 

  >*Cheng X, Lu W, Chen S, et al.* [[Paper]](https://arxiv.org/abs/2107.13797)
  
* [**Computing Science Cryptography and Security 2020**] [**Paillier**] FPGA-Based Hardware Accelerator of Homomorphic Encryption for Efficient Federated Learning.

  >*Zhaoxiong Yang, Shuihai Hu, Kai Chen.* [[Paper]](https://arxiv.org/abs/2007.10560)


---
## System Designs for Homomorphic Encryption


* [**DAC 2021**] [**Polynomial Multiplication**] Efficient Implementation of Finite Field Arithmetic for Binary Ring-LWE Post Quantum Cryptography Through a Novel Lookup-Table-Like Method. 

  >*Jiafeng Xie,Pengzhou He, Wujie Wen.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9586151/)
  
* [**ISCA 2022**] [**CKKS**] Graphite: optimizing graph neural networks on CPUs through cooperative software-hardware techniques. 

  >*Gong Z, Ji H, Yao Y, et al.* [[Paper]](https://dl.acm.org/doi/10.1145/3470496.3527403)
  
* [**DATE 2022**] [**CKKS**] coxHE: A software-hardware co-design framework for FPGA acceleration of homomorphic computation.

  >*Han M, Zhu Y, Lei Ju, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9774559)
  
* [**MICRO 2022**] [**CKKS**] ARK: Fully Homomorphic Encryption Accelerator with Runtime Data Generation and Inter-Operation Key Reuse.

  >*Kim J, Lee G, Ahn J, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9923889/)
  
* [**ESSCIRC 2022**] [**PQC**] Configurable Energy-Efficient Lattice-Based PostQuantum Cryptography Processor for IoT Devices.

  >*Kim B, Park J, Sim J, et al* [[Paper]](https://ieeexplore.ieee.org/document/9911531/)
  
* [**ISCAS 2020**] [**AES**] Accelerating Post-Quantum Cryptography using an Energy-Efficient TLS Crypto-Processor.

  >*Utsav Banerjee, Siddharth Das, Anantha P. Chandrakasan* [[Paper]](https://ieeexplore.ieee.org/document/9180550)

---
## Algorithmic Acceleration and Application for Homomorphic Encryption


* [**DAC 2020**] [**TFHE**] ROMEO: Conversion and Evaluation of HDL Designs in the Encrypted Domain.

  >*Charles Gouert and Nektarios Georgios Tsoutsos.* [[Paper]](https://ieeexplore.ieee.org/document/9218579/)

* [**HPCA 2021**] [**BFV**] Cheetah: Optimizing and Accelerating Homomorphic Encryption for Private Inference.

  >*Reagen B, Choi W, Brooks D, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9407118)

* [**DATE 2021**] [**BFV**] Real-time Private Membership Test using Homomorphic Encryption.
  
  >*Eduardo Chielle, Homer Gamil, Michail Maniatakos.* [[Paper]](https://ieeexplore.ieee.org/document/9473968/)
  
* [**TCAD 2020**] [**FHE**] Efficient Comparison and Addition for FHE With Weighted Computational Complexity Model.
  
  >*Neng Zhang, Shaojun Wei, Leibo Liu, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9224873/)
  
* [**TCAD 2022**] [**BGV**] Efficient FHE Radix-2 Arithmetic Operations Based on Redundant Encoding. 
  
  >*Hou Z, Shaojun Wei, Leibo Liu, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9502150)
  
* [**ICCAD 2022**] [**BFV, BGV, CKKS**]Accelerating Fully Homomorphic Encryption by Bridging Modular and Bit-Level Arithmetic.
  
  >*Chielle E, Mazonka O, Maniatakos M* [[Paper]](https://arxiv.org/abs/2204.12201)
  
* [**ISCAS 2020**] [**BGV**] VLSI Architecture of Polynomial Multiplication for BGV Fully Homomorphic Encryption.
  
  >*Hsu H and Shieh M* [[Paper]](https://arxiv.org/pdf/2203.10428.pdf) [](https://ieeexplore.ieee.org/document/9181192/)
  
* [**ISCAS 2021**] [**BGV**] On Compare-and-Swap Optimization for Fully Homomorphic Encrypted Data.
  
  >*Chien-Chih Huang, Jyun-Neng Ji and Ming-Der Shieh.* [[Paper]](https://ieeexplore.ieee.org/document/9401078/)
  
* [**TCAS-I 2020**] [**Modular Multiplication**] Design and Implementation of a Low-Latency Modular Multiplication Algorithm.
  
  >*Erdinç Öztürk*  [[Paper]](https://ieeexplore.ieee.org/document/8968620)
  
* [**TCAS-I 2021**] [**Scalar Multiplication**] Radix-2w Arithmetic for Scalar Multiplication in Elliptic Curve Cryptography. 
  
  >*Abdelkrim Kamel Oudjida, Ahmed Liacha.* [[Paper]](https://ieeexplore.ieee.org/document/9349769)
  
* [**TCAS-I 2022**] [**Polynomial Multiplication**] Faster NTRU on ARM Cortex-M4 With TMVP-Based Multiplication. 
  
  >*Irem Keskinkurt Paksoy, Murat Cenk.* [[Paper]](https://ieeexplore.ieee.org/document/9835023/) 
  
* [**AAAI 2019**] [**FHE**] Logistic Regression on Homomorphic Encrypted Data at Scale.
  
  >*Kyoohyung H, Seungwan H, Jung C.* [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/5000) 
  
* [**AsiaCrypt 2022**] [**Bootstrapping**] High-Precision Bootstrapping for Approximate Homomorphic Encryption by Error Variance Minimization.
  
  >*Yongwoo L,  Joon-Woo L, Young K, et al.* [[Paper]](https://iacr.org/submit/files/slides/2022/eurocrypt/eurocrypt2022/239/slides.pdf) 
  
* [**CHES 2021**] [**Bootstrapping**] Over 100x Faster Bootstrapping in Fully Homomorphic Encryption through Memory-centric Optimization with GPUs.
  
  >*Wonkyung J, Sangpyo K, Jung A, et al.* [[Paper]](https://tches.iacr.org/index.php/TCHES/article/view/9062) 
  
* [**CHES 2018**] [**BFV**] High-Performance FV Somewhat Homomorphic Encryption on GPUs: An Implementation using CUDA.
  
  >*Ahmad B, Bharadwaj V, Chan M, et al.* [[Paper]](https://www.researchgate.net/profile/Ahmad-Al-Badawi/publication/346706228_High-Performance_FV_Somewhat_Homomorphic_Encryption_on_GPUs_An_Implementation_using_CUDA/links/6131df9238818c2eaf7ae5c9/High-Performance-FV-Somewhat-Homomorphic-Encryption-on-GPUs-An-Implementation-using-CUDA.pdf) 
  
* [**Crypto 2021**] [**BGV**] Faster Homomorphic Linear Transformations in HElib.
  
  >*Shai Halevi and Victor Shoup.* [[Paper]](https://www.iacr.org/archive/crypto2018/10993198/10993198.pdf) 
  
* [**Crypto 2013**] [**Bootstrapping**] Practical Bootstrapping in Quasilinear Time.
  
  >*Jacob Alperin-Sheriff and Chris Peikert* [[Paper]](https://web.eecs.umich.edu/~cpeikert/pubs/simpleboot.pdf) 
  
* [**EUPOCRYPT 2018**] [**Bootstrapping**] Homomorphic Lower Digits Removal and Improved FHE Bootstrapping.
  
  >*Hao Chen and Kyoohyung Han* [[Paper]](https://www.researchgate.net/profile/Han-Kyoohyung/publication/324110348_Homomorphic_Lower_Digits_Removal_and_Improved_FHE_Bootstrapping/links/5b57d4e90f7e9bc79a60a2e0/Homomorphic-Lower-Digits-Removal-and-Improved-FHE-Bootstrapping.pdf) 
  
* [**EUPOCRYPT 2018**] [**Bootstrapping**] Bootstrapping for Approximate Homomorphic Encryption.

  >*Jung C, Andrey K, Yongsoo S, et al.* [[Paper]](https://ir.cwi.nl/pub/23686/23686B.pdf) 

* [**EUPOCRYPT 2017**] [**CKKS**] Homomorphic Encryption for Arithmetic of Approximate Numbers.
  
  >*Jung C, Andrey K, Yongsoo S, et al.* [[Paper]](https://eprint.iacr.org/2016/421.pdf?ref=https://codemonkey.link) 
  
* [**EUPOCRYPT 2015**] [**FHEW**] FHEW: Bootstrapping Homomorphic Encryption in less than a second.

  >*Leo D, Daniele M, Centrum W, et al.* [[Paper]](https://ir.cwi.nl/pub/23686/23686B.pdf) 

* [**HOST 2020**] [**TFHE**] CPU and GPU Accelerated Fully Homomorphic Encryption.

  >*Toufifique M, Md M and Noman M* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9300288/) 

* [**IEEE Access 2020**] [**FHE**] PrivFT: Private and Fast Text Classification With Homomorphic Encryption.

  >*Ahmad B, Louie H, Chan M, et al. [[Paper]](https://ieeexplore.ieee.org/abstract/document/9296754) 

* [**IEEE Access 2020**] [**FHE**] Privacy-Preserving Machine Learning With Fully Homomorphic Encryption for Deep Neural Network.

  >*Joon-woo L, Hyungchul K, Jong-Seon N, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9734024) 

* [**IISWC 2020**] [**NTT, Bootstrapping**] Accelerating Number Theoretic Transformations for Bootstrappable Homomorphic Encryption on GPUs.

  >*Sangpyo K, Wonkyung J, Jaiyoung P, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9251245) 

* [**JMIR 2018**] [**FHE, Logistic Regression**] Secure Logistic Regression Based on Homomorphic Encryption: Design and Evaluation.

  >*Miran K, Yongsoo S, Shuang Wang, et al.* [[Paper]](https://www.researchgate.net/profile/Yongsoo-Song/publication/324583361_Secure_Logistic_Regression_Based_on_Homomorphic_Encryption_Design_and_Evaluation/links/5bd3e4b992851c6b27920987/Secure-Logistic-Regression-Based-on-Homomorphic-Encryption-Design-and-Evaluation.pdf) 

* [**PLDI 2019**] [**FHE**] CHET: An Optimizing Compiler for Fully-Homomorphic Neural-Network Inferencing.

  >*Roshan D, Olli S, Todd M, et al.* [[Paper]](https://www.cs.utexas.edu/~roshan/CHET.pdf) 

* [**Reconfig 2019**] [**FHE, Modular Multiplier**] FPGA-based Accelerators of Fully Pipelined Modular Multipliers for Homomorphic Encryption.

  >*Sunwoong K, Keewoo L, Wonhee C, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/8994793/) 

* [**SAC 2018**] [**BFV, RNS**] A Full RNS Variant of Approximate Homomorphic Encryption.

  >*Jung C , Kyoohyung H, Yongsoo S, et al.* [[Paper]](https://www.researchgate.net/profile/Han-Kyoohyung/publication/330341753_A_Full_RNS_Variant_of_Approximate_Homomorphic_Encryption_25th_International_Conference_Calgary_AB_Canada_August_15-17_2018_Revised_Selected_Papers/links/5cd27fdaa6fdccc9dd93a38a/A-Full-RNS-Variant-of-Approximate-Homomorphic-Encryption-25th-International-Conference-Calgary-AB-Canada-August-15-17-2018-Revised-Selected-Papers.pdf) 

* [**SAC 2016**] [**FHE, Logistic Regression**] A Full RNS Variant of FV like Somewhat Homomorphic Encryption Schemes.

  >*Jean-Claude B, Julien E, Vincent Z, et al.* [[Paper]](https://webusers.imj-prg.fr/~jean-claude.bajard/MesPublis/SAC2016.pdf) 

* [**TETCI 2019**] [**BFV, RNS**] Implementation and Performance Evaluation of RNS Variants of the BFV Homomorphic Encryption Scheme.

  >*Ahmad B, Yuriy P, Kurt R, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/8657794/)

* [**WAHC 2021**] [**FHE**] Intel HEXL: Accelerating Homomorphic Encryption with Intel AVX512-IFMA52.

  >*Fabian B, Sejun K, Vinodh G, et al.* [[Paper]](https://fabianboemer.com/files/intel-hexl.pdf)

* [**IACR Cryptology ePrint Archive 2018**] [**FHE**] Homomorphic Encryption Standard.

  >*Martin A, Melissa C, Vinod V, et al* [[Paper]](https://link.springer.com/chapter/10.1007/978-3-030-77287-1_2)

* [**IACR Cryptology ePrint Archive 2015**] [**FHE**] A Guide to Fully Homomorphic Encryption.

  >*Frederik A, Colin B, Martin S, et al.* [[Paper]](https://eprint.iacr.org/2015/1192)
  
* [**ArXiv 2022**] [**FHE, Bootstrapping**]FAB: An FPGA-based Accelerator for Bootstrappable Fully Homomorphic Encryption. 

  >*Rashmi A, Leo de, Ajay J, et al.*[[Paper]](https://arxiv.org/abs/2207.11872)

  


---
## Surveys and Performance Analysis on Homomorphic Encryption

* [**IEEE proceedings 2022**] Survey on Fully Homomorphic Encryption, Theory, and Applications.

  >*Chiara M, Victor S, Marc M, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9910347)

* [**CSUR 2022**] A Survey on Homomorphic Encryption Schemes_Theory and Implementation. 

  >*Abbas Acar, Hidayet Aksu, A. Selcuk Uluagac.* [[Paper]]( https://dl.acm.org/doi/10.1145/3214303)
  
* [**IACR Cryptology ePrint Archive 2015**] [**FHE**]  A Guide to Fully Homomorphic Encryption.

  >*Frederik A, Colin B, Martin S, et al.* [[Paper]](https://eprint.iacr.org/2015/1192)
  
* [**IACR Cryptology ePrint Archive 2018**] [**FHE**] Homomorphic Encryption Standard.

  >*Martin A, Melissa C, Vinod V, et al* [[Paper]](https://link.springer.com/chapter/10.1007/978-3-030-77287-1_2)
  
* [**EUPOCRYPT 2017**] [**CKKS方案开山之作**] Homomorphic Encryption for Arithmetic of Approximate Numbers.

  >*Jung C, Andrey K, Yongsoo S, et al.* [[Paper]](https://eprint.iacr.org/2016/421.pdf?ref=https://codemonkey.link) 
  
* [**EUPOCRYPT 2015**] [**FHEW方案开山之作**] FHEW: Bootstrapping Homomorphic Encryption in less than a second.

  >*Leo D, Daniele M, Centrum W, et al.* [[Paper]](https://ir.cwi.nl/pub/23686/23686B.pdf) 

---
## Maintainers

- Ao Zhou, Beihang University. [[GitHub]](https://github.com/ZhouAo-ZA)
- Yingjie Qi, Beihang University. [[GitHub]](https://github.com/Kevin7Qi)
- Tong Qiao, Beihang University. [[GitHub]](https://github.com/qiaotonggg)
- Shangtong Zhang, Beihang University. [[GitHub]](https://github.com/Zst0514)

