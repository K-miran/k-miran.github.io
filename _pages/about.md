---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am an Associate Professor in the [Department of Mathematics](http://math.hanyang.ac.kr/frontpage.asp?catalogid=math&language=en&calltype=redirect) at [Hanyang University](https://www.hanyang.ac.kr/web/eng) and hold an affiliated faculty position at the [Department of Computer Science](http://cs.hanyang.ac.kr) at Hanyang University. My research mainly focuses on Privacy-Enhancing Cryptography (PEC), which aims to develop advanced cryptographic primitives to protect sensitive data of individuals. 
In particular, I have been actively working on the development of homomorphic encryption, which enables to compute any function on encrypted data without decryption. Also, I have been working on privacy-preserving protocols in a wide range of applications such as data query processing, genomic analysis, and machine learning. 


# Advertisement
Positions are available for postdocs, graduate students, and interns (junior or senior student) in areas in security, privacy, and deep learning. If you are interested in applying for a position, please send an email to me.

# 🔥 News
- Our team received the Grand Prize at the 2025 National Cryptographic Technology Contest, organized by the National Intelligence Service of Korea. [[URL]](https://www.yna.co.kr/view/AKR20251023108400017?input=1195m)
- Our paper "Empowering AI with Homomorphic Encryption for Secure Deep Reinforcement Learning" will appear in Nature Machine Intelligence. 
- Our paper ["THOR: Secure Transformer Inference with Homomorphic Encryption"](https://eprint.iacr.org/2024/1881) was accepted to ACM CCS!
- Our paper ["Provably Secure Approximate Computation Protocols from CKKS"](https://eprint.iacr.org/2025/395) has been appeared in Cryptology ePrint Archive. 
- Our paper ["More Efficient Lattice-based OLE from Circuit-private Linear HE with Polynomial Overhead"](https://eprint.iacr.org/2024/1534) has been appeared in Cryptology ePrint Archive.

# 📖 Publications
  * THOR: Secure Transformer Inference with Homomorphic Encryption [[pdf]](https://eprint.iacr.org/2024/1881) [[slide]](https://github.com/K-miran/k-miran.github.io/blob/main/assets/thor_ccs_2025.pdf) 
     * Jungho Moon, Dongwoo Yoo, Xiaoqian Jiang, **Miran Kim**
     * _Proceedings of the ACM SIGSAC Conference on Computer and Communications Security (CCS)_, 2025.

  * Descriptor: Benchmarking Secure Neural Network Evaluation Methods for Protein Sequence Classification (iDASH24) [[pdf]](https://ieeexplore.ieee.org/abstract/document/10720824)
     * Arif Ozgun Harmanci, Luyao Chen, **Miran Kim**, Xiaoqian Jiang
     * _IEEE Data Descriptions_, 2024
       
  * Finding Highly Similar Regions of Genomic Sequences Through Homomorphic Encryption [[pdf]](https://www.liebertpub.com/doi/10.1089/cmb.2023.0050)
     * Magsarjav Bataa, Siwoo Song, Kunsoo Park, **Miran Kim**, Jung Hee Cheon, Sun Kim
     * _JOURNAL OF COMPUTATIONAL BIOLOGY_, 2024

  * Accelerating HE Operations from Key Decomposition Technique [[pdf]](https://link.springer.com/chapter/10.1007/978-3-031-38551-3_3) [[code]](https://github.com/SNUCP/fast-ksw)
     * **Miran Kim**, Dongwon Lee, Jinyeong Seo, Yongsoo Song
     * _Advances in Cryptology – CRYPTO_, 2023
       
  * COLLAGENE enables privacy-aware federated and collaborative genomic data analysis [[pdf]](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-023-03039-z) [[code]](https://github.com/harmancilab/COLLAGENE)
     * Wentao Li, **Miran Kim**, Kai Zhang, Han Chen, Xiaoqian Jiang, Arif Ozgun Harmanci
     * _Genome Biology_; 2023.
       
  * Secure Human Action Recognition by Encrypted Neural Network Inference [[pdf]](https://www.nature.com/articles/s41467-022-32168-5) [[code]](https://github.com/K-miran/HEAR)
     * **Miran Kim**, Xiaoqian Jiang, Kristin Lauter, Elkhan Ismayilzada, Shayan Shams
     * _Nature Communications_; 13(1), 1-13, 2022. 
     
  * Privacy-aware Estimation of Relatedness in Admixed Populations [[pdf]](https://doi.org/10.1093/bib/bbac473)
     * Su Wang, **Miran Kim**, Wentao Li, Xiaoqian Jiang, Han Chen, Arif Harmanci
     * _Briefings in Bioinformatics_; 23(6), 1-16, 2022.  
      
  * The Evolving Privacy and Security Concerns for Genomic Data Analysis and Sharing as Observed from the iDASH Competition [[pdf]](https://doi.org/10.1093/jamia/ocac165)
     * Tsung-Ting Kuo, Xiaoqian Jiang, Haixu Tang, XiaoFeng Wang, Arif Harmanci, **Miran Kim**, Kai Post, Diyue Bu, Tyler Bath, Jihoon Kim, Weijie Liu, Hongbo Chen, Lucila Ohno-Machado
     * _Journal of the American Medical Informatics Association_; 29(12), 2182-2190, 2022.

  * Evaluation of Vicinity-based Hidden Markov Models for Genotype Imputation [[pdf]](https://doi.org/10.1186/s12859-022-04896-4)
      * Su Wang, **Miran Kim**, Xiaoqian Jiang, Arif O. Harmanci
      * _BMC Bioinformatics_; 23(356), 1-26, 2022. 
  
  * SVAT: Secure Outsourcing of Variant Annotation and Genotype Aggregation [[pdf]](https://doi.org/10.1186/s12859-022-04959-6) [[code]](https://github.com/harmancilab/SVAT)
      * **Miran Kim**, Su Wang, Xiaoqian Jiang, Arif O. Harmanci
      * _BMC Bioinformatics_; 23(409), 1-39, 2022. 
      
  * Trusted Monitoring Service [[pdf]](https://link.springer.com/chapter/10.1007/978-3-030-77287-1_5) 
     * Xiaoqian Jiang, **Miran Kim**, Kristin Lauter, Tim Scott, Shayan Shams
     * _Protecting Privacy through Homomorphic Encryption_; 87-95, Springer, Cham, 2022.

  * Introduction to Homomorphic Encryption and Schemes [[pdf]](https://link.springer.com/chapter/10.1007/978-3-030-77287-1_1)
     * Jung Hee Cheon, Anamaria Costache, Radames Cruz Moreno, Wei Dai, Nicolas Gama, Mariya Geogieva, Shai Halevi, **Miran Kim**, Sunwoong Kim, Kim Laine, Yuriy Polyakov, Yongsoo Song
     * _Protecting Privacy through Homomorphic Encryption_; 3-28, Springer, Cham, 2022.
       
  * Ultra-Fast Homomorphic Encryption Models enable Secure Outsourcing of Genotype Imputation [[pdf]](https://www.cell.com/cell-systems/fulltext/S2405-4712(21)00288-X) [[code]](https://github.com/K-miran/secure-imputation)
      * **Miran Kim**, Arif Harmanci, Jean-Philippe Bossuat, Sergiu Carpov, Jung Hee Cheon, Ilaria Chillotti, Wonhee Cho, David Froelicher, Nicolas Gama, Mariya Georgieva, Seungwan Hong, Jean-Pierre Hubaux, Duhyeong Kim, Kristin Lauter, Yiping Ma, Lucila Ohno-Machado, Heidi Sofia, Yongha Son, Yongsoo Song, Juan Troncoso-Pastoriza, Xiaoqian Jiang
      * _Cell Systems_; 12(10), 950-952, 2021. (IF:11.091)
      
  * Efficient Homomorphic Conversion Between (Ring) LWE Ciphertexts [[pdf]](https://link.springer.com/chapter/10.1007/978-3-030-78372-3_18)
      * Hao Chen, Wei Dai, **Miran Kim**, Yongsoo Song
      * _Proceedings of the International Conference on Applied Cryptography and Network Security (ACNS)_, 2021.

  * Open Imputation Server Provides Secure Imputation Services with Provable Genomic Privacy [[pdf]](https://www.biorxiv.org/content/10.1101/2021.09.30.462262v1)
      * Arif O. Harmanci, **Miran Kim**, Su Wang, Wentao Li, Yongsoo Song, Kristin Lauter, Xiaoqian Jiang
      * biorXiv:2021.09.30.462262. 2021.
      
  * Maliciously Secure Matrix Multiplication with Applications to Private Deep Learning [[pdf]](https://link.springer.com/chapter/10.1007/978-3-030-64840-4_2)
      * Hao Chen, **Miran Kim**, Ilya Razenshteyn, Dragos Rotaru, Yongsoo Song, Sameer Wagh
      * _Advances in Cryptology – ASIACRYPT_, 2020. 

  * Homomorphic Computation of Local Alignment [[pdf]](https://ieeexplore.ieee.org/abstract/document/9313199)
      * Magsarjav Bataa, Siwoo Song, Kunsoo Park, **Miran Kim**, Jung Hee Cheon, and Sun Kim.
      * _Proceedings of the IEEE International Conference on Bioinformatics and Biomedicine (BIBM)_, 2020.
      
  * A Secure System for Genomics Clinical Decision Support [[pdf]](https://www.sciencedirect.com/science/article/pii/S1532046420302306?dgcid=coauthor)
      * Seemeen Karimi, Xiaoqian Jiang, Robert Dolin, **Miran Kim**, Aziz Boxwala
      * _Journal of Biomedical Informatics_; 112, 2020.
      
  * Semi-Parallel Logistic Regression for GWAS on Encrypted Data [[pdf]](https://bmcmedgenomics.biomedcentral.com/articles/10.1186/s12920-020-0724-z)
      * **Miran Kim**, Yongsoo Song, Baiyu Li, Daniele Micciancio
      * _BMC Medical Genomics_; 13(7):1-13, 2020. 
      
  * SCOR: A secure international informatics infrastructure to investigate COVID-19 [[pdf]](https://academic.oup.com/jamia/article/doi/10.1093/jamia/ocaa172/5869802)
      * J L Raisaro, Francesco Marino, Juan Troncoso-Pastoriza, Raphaelle Beau-Lejdstrom, Riccardo Bellazzi, Robert Murphy, Elmer V Bernstam, Henry Wang, Mauro Bucalo, Yong Chen, Assaf Gottlieb, Arif Harmanci, **Miran Kim**, Yejin Kim, Jeffrey Klann, Catherine Klersy, Bradley A Malin, Marie Méan, Fabian Prasser, Luigia Scudeller, Ali Torkamani, Julien Vaucher, Mamta Puppala, Stephen T C Wong, Milana Frenkel-Morgenstern, Hua Xu, Baba Maiyaki Musa, Abdulrazaq G Habib, Trevor Cohen, Adam Wilcox, Hamisu M Salihu, Heidi Sofia, Xiaoqian Jiang, Jean-Pierre Hubaux
      * _Journal of the American Medical Informatics Association (JAMIA)_; ocaa172, 2020.

  * Secure and Differentially Private Bayesian Learning on Distributed Data [[pdf]](https://arxiv.org/abs/2005.11007)
      * Yeongjae Gil, Xiaoqian Jiang, **Miran Kim**, Junghye Lee
      * arXiv:2005.11007. (2020). 
      
  * Efficient Multi-Key Homomorphic Encryption with Packed Ciphertexts with Application to Oblivious Neural Network Inference [[pdf]](https://dl.acm.org/doi/10.1145/3319535.3363207)
      * Hao Chen, Wei Dai, **Miran Kim**, Yongsoo Song
      * _Proceedings of the ACM SIGSAC Conference on Computer and Communications Security (CCS)_, 2019.
      
  * Secure and Differentially Private Logistic Regression for Horizontally Distributed Data [[pdf]](https://ieeexplore.ieee.org/abstract/document/8747377)
      * **Miran Kim**, Junghye Lee, Lucila Ohno-Machado, Xiaoqian Jiang
      * _IEEE Transactions on Information Forensics and Security (TIFS)_; 15(1):695-710, 2019. 
      
  * SecureLR: Secure Logistic Regression Model via a Hybrid Cryptographic Protocol [[pdf]](https://ieeexplore.ieee.org/document/8355587)
      * Yichen Jiang, Jenny Hamer, Chenghong Wang, Xiaoqian Jiang, **Miran Kim**, Yongsoo Song, Yuhou Xia, Noman Mohammed, Md Nazmus Sadat, Shuang Wang
      * _IEEE/ACM Transactions on Computational Biology and Bioinformatics_; 16(1):113-123, 2019.
  
  * Secure Outsourced Matrix Computation and Application to Neural Networks [[pdf]](https://k-miran.github.io/files/2018_HEMat_CCS.pdf) [[code]](https://dl.acm.org/doi/10.1145/3243734.3243837)
      * Xiaoqian Jiang, **Miran Kim**, Kristin Lauter, Yongsoo Song
      * _Proceedings of the ACM SIGSAC Conference on Computer and Communications Security (CCS)_, 2018.
   
  * A Full RNS Variant of Approximate Homomorphic Encryption [[pdf]](https://link.springer.com/chapter/10.1007/978-3-030-10970-7_16) [[code]](https://github.com/HanKyoohyung/FullRNS-HEAAN)
      * Jung Hee Cheon, Kyoohyung Han, Andrey Kim, **Miran Kim**, Yongsoo Song
      * _Proceedings of the International Conference on Selected Areas in Cryptography (SAC)_, 2018.

  * Bootstrapping for Approximate Homomorphic Encryption [[pdf]](https://link.springer.com/chapter/10.1007/978-3-319-78381-9_14) [[code]](https://github.com/kimandrik/HEAANBOOT)
      * Jung Hee Cheon, Kyoohyung Han, Andrey Kim, **Miran Kim**, Yongsoo Song
      * _Advances in Cryptology – EUROCRYPT_, 2018
 
  * Logistic Regression Model Training based on the Approximate Homomorphic Encryption [[pdf]](https://bmcmedgenomics.biomedcentral.com/articles/10.1186/s12920-018-0401-7) [[code]](https://github.com/kimandrik/IDASH2017)
      * Andrey Kim, Yongsoo Song, **Miran Kim**, Kiwoo Lee, Jung Hee Cheon
      * _BMC Medical Genomics_; 11(Suppl 4):83, 2018.

  * Secure Logistic Regression Based on Homomorphic Encryption: Design and Evaluation [[pdf]](https://medinform.jmir.org/2018/2/e19/) [[code]](https://github.com/K-miran/HELR)
      * **Miran Kim**, Yongsoo Song, Shuang Wang, Yuhou Xia, Xiaoqian Jiang
      * _JMIR Medical Informatics_; 6(2), 2018.

  * Homomorphic Encryption for Arithmetic of Approximate Numbers [[pdf]](https://link.springer.com/chapter/10.1007/978-3-319-70694-8_15) [[code]](https://github.com/snucrypto/HEAAN)
      * Jung Hee Cheon, Andrey Kim, **Miran Kim**, Yongsoo Song
      * _Advances in Cryptology – ASIACRYPT_, 2017. 
      
  *  A Standard API FOR RLWE-based Homomorphic Encryption [[pdf]](http://homomorphicencryption.org/white_papers/API_homomorphic_encryption_white_paper.pdf)
      * Michael Brenner, Wei Dai, Shai Halevi, Kyoohyung Han, Amir Jalali, **Miran Kim**, Kim Laine, Alex Malozemoff, Pascal Paillier, Yuriy Polyakov, Kurt Rohloff, Erkay Savas, Berk Sunar
      * Draft Homomorphic Encryption Standard, available at HomomorphicEncryption.org. 2017.

  * Secure Searching of Biomarkers Using Hybrid Homomorphic Encryption Scheme [[pdf]](https://bmcmedgenomics.biomedcentral.com/articles/10.1186/s12920-017-0280-3) [[code]](https://github.com/K-miran/HybridHE)
      * **Miran Kim**, Yongsoo Song, Jung Hee Cheon
      * _BMC Medical Genomics_; 10(42), 2017.
      
  * Encrypting Controller using Fully Homomorphic Encryption for Security of Cyber-Physical Systems [[pdf]](ttps://www.sciencedirect.com/science/article/pii/S2405896316319796)
      * Junsoo Kim, Chanhwa Lee, Hyungboo Shim, Jung Hee Cheon, Andrey Kim, **Miran Kim**, Yongsoo Song
      * _Proceedings of the IFAC Workshop on Distributed Estimation and Control in Networked Systems (NECSYS)_, 2016.
      
  * Optimized Search-and-Compute Circuits and Their Application to Query Evaluation on Encrypted Data [[pdf]](https://ieeexplore.ieee.org/document/7279139)
      * Jung Hee Cheon, **Miran Kim**, Myungsun Kim
      * _IEEE Transactions on Information Forensics and Security (TIFS)_; 11(1):188--199, 2016.
  
  * HEALER: Homomorphic computation of ExAct Logistic rEgRession for secure rare disease variants analysis in GWAS [[pdf]](https://academic.oup.com/bioinformatics/article/32/2/211/1744166)
      * Shuang Wang, Yuchen Zhang, Wenrui Dai, Kristin Lauter, **Miran Kim**, Yuzhe Tang, Hongkai Xiong, Xiaoqian Jiang
      * _Bioinformatics_; 32(2):211--218, 2016.
    
  * Search-and-Compute on Encrypted Data [[pdf]](https://link.springer.com/chapter/10.1007/978-3-662-48051-9_11)
      * Jung Hee Cheon, **Miran Kim**, Myungsun Kim
      * _Proceedings of the Financial Cryptography and Data Security (FC)_, 2015.
       
  * Homomorphic Computation of Edit Distance [[pdf]](https://link.springer.com/chapter/10.1007/978-3-662-48051-9_15)  
     * Jung Hee Cheon, **Miran Kim**, Kristin Lauter  
     * _Proceedings of the Financial Cryptography and Data Security (FC)_, 2015.  

  * Private Genome Analysis through Homomorphic Encryption [[pdf]](https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/1472-6947-15-S5-S3)  
     * **Miran Kim**, Kristin Lauter  
     * _BMC medical informatics and decision making_; 15(Suppl 5):S3, 2015.


# 🎖 Honors
  * Grand Prize Crypto Contest Oct 2025. Korea Cryptography Forum [[URL]](https://www.news1.kr/it-science/general-it/5951403)
    
  * Silver Prize, The 29th Samsung Humantech Paper Awards, 2023
      * Accelerating HE Operations from Key Decomposition Technique
         
  * First Prize, iDASH Genomic Data Privacy and Security Protection Competition 2018 [[URL]](http://www.humangenomeprivacy.org/2018/)
      * Secure parallel Genome Wide Association Studies using homomorphic encryption [[Result]](https://k-miran.github.io/files/2018result.png)
  
  * NC Cultural Foundation Awards for Young Korean Female Mathematicians 2018 [[URL]](http://www.kwms.or.kr/index.php?mt=page&mp=5_4&mm=oxbbs&oxid=63&cpage=1&key=&val=&CAT_ID=0&BID=1003&cmd=view) 
  
  * Nominated at Marquis’s Who’s Who in the World 2018. Marquis’s Who’s Who.

  * First Prize, iDASH Genomic Data Privacy and Security Protection Competition 2017 [[URL]](http://www.humangenomeprivacy.org/2017/)
      * Secure logistic regression model training [[Result]](https://k-miran.github.io/files/2017_idashresult.png)
  
  * Excellence Award, Crypto Contest Oct 2017. Korea Cryptography Forum 
  
  * Second Prize, iDASH Genomic Data Privacy and Security Protection Competition 2016 [[URL]](http://www.humangenomeprivacy.org/2016/)

  * Grand Prize Crypto Contest Oct 2016. Korea Cryptography Forum [[URL]](http://www.etnews.com/20161123000272)

  * Special Prize Crypto Contest Nov 2015. Korea Cryptography Forum

  * First Prize, iDASH Genomic Data Privacy and Security Protection Competition 2015 [[URL]](http://www.humangenomeprivacy.org/2015) [[Media]](http://blogs.technet.com/b/inside_microsoft_research/archive/2015/03/20/cryptographers-challenge-keeping-genetic-secrets-while-advancing-genetic-research.aspx) [[Media]](http://news.donga.com/3/all/20150313/70100744/1)

# 📖 Education
  * Ph.D in Mathematical Sciences, Seoul National University, February 2017
     * Research area: Cryptography
     * Advisor: [Dr. Jung Hee Cheon](http://www.math.snu.ac.kr/~jhcheon/xe2/)
  * M.S. in Mathematical Sciences, Seoul National University, February 2012
  * B.S. in Mathematical Education, Seoul National University, February 2010

# 💻 Experience
  * Sep. 2024 - Present: Associate Professor
    * Department of Mathematics, Hanyang University
    * Department of Computer Science, Hanyang University

  * Sep. 2022 - Aug. 2024: Assistant Professor
    * Department of Mathematics, Hanyang University
    * Department of Computer Science, Hanyang University

  * August 2020 - August 2022: Assistant Professor
    * Department of Computer Science and Engineering, Ulsan National Institute of Science and Technology (UNIST)
    * Graduate School of Artificial Intelligence, UNIST

  * May 2018 - July 2020: Assistant Professor
    * School of Biomedical Informatics, University of Texas, Health Science Center at Houston

  * March 2017 - April 2018: Postdoctoral Researcher
    * Division of Biomedical Informatics, University of California, San Diego
    * Supervisor: Dr. Xiaoqian Jiang

  * Spring 2015: Research Intern
    * Microsoft Research
    * Supervisor: [Dr. Kristin Lauter](https://www.microsoft.com/en-us/research/people/klauter/?from=http%3A%2F%2Fresearch.microsoft.com%2F%7Eklauter%2F)

