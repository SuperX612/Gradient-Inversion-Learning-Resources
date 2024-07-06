# Gradient Inversion Learning Resources

This GitHub repository summarizes existing gradient leakage attacks and defenses in federated learning. For more details, please refer to our comprehensive survey.

We commit to diligently maintaining and updating this repository monthly to ensure it remains a valuable and up-to-date resource.

**What are Gradient Inversion?**

Gradient Leakage Attack is a privacy attack in federated learning systems where the attacker reconstructs the client's private data from shared gradient.

**Why Gradient Inversion?**

Gradient leakage attacks pose a significant threat to data privacy in federated learning. Investigating and defending against these potential gradient leakage attacks in federated learning is crucial for implementing secure distributed machine learning.

Note: Gradient leakage attacks are also commonly referred to as "Gradient Reconstruction Attacks" or "Gradient Inversion Attacks."

## News

- 2024/07/06: I update this Github
- 2024/04/18: I create this GitHub repository.

## Table of Contents

- [Survey](#survey)
- [Tools](#tools)
- [Gradient Inversion for Computer Vision](#gradient-inversion-for-computer-vision)
  - [Gradient Inversion in FedSGD](#gradient-inversion-in-fedSGD)
  
  - [Gradient Inversion in FedAvg](#gradient-inversion-in-fedAvg)
- [Gradient Inversion towards Other Tasks](#gradient-inversion-towards-other-tasks)
- [Defenses for Gradient Inversion](#defenses-for-gradient-inversion)

## Survey

**2024**

- SoK: Gradient Leakage in Federated Learning [[pdf]](https://arxiv.org/abs/2404.05403)
  - Jiacheng Du, Jiahui Hu, Zhibo Wang, Peng Sun, Neil Zhenqiang Gong, and Kui Ren. *arXiv*, 2024.
- Review of Deep Gradient Inversion Attacks and Defenses in Federated Learning [[pdf]](https://jeit.ac.cn/en/article/doi/10.11999/JEIT230541)
  - Yu Sun, Yu Yan, Jian Cui, Gaojian Xiong, Jianhua Liu. 电子学报, 2024.

**2023**

- A Comprehensive Study of Gradient Inversion Attacks in Federated Learning and Baseline Defense Strategies [[pdf]](https://ieeexplore.ieee.org/abstract/document/10089719)

  - Ovi, Pretom Roy, and Aryya Gangopadhyay. *57th Annual Conference on Information Sciences and Systems (CISS)*, 2023.
- A Survey of Image Gradient Inversion Against Federated Learning [[pdf]](https://www.techrxiv.org/doi/full/10.36227/techrxiv.18254723.v1)
  - Zhaohua Li, Le Wang, Guangyao Chen, Muhammad Shafq, and zhaoquan Gu. *Authorea Preprints*, 2023.
- Gradient leakage attacks in federated learning [[pdf]](https://link.springer.com/article/10.1007/s10462-023-10550-z)
  - Haimei Gong, Liangjun Jiang, Xiaoyang Liu, Yuanqi Wang, Omary Gastro, Lei Wang, Ke Zhang, and Zhen Guo. *Artificial Intelligence Review*, 2023.
- Gradient Leakage Attacks in Federated Learning: Research Frontiers, Taxonomy and Future Directions [[pdf]](https://ieeexplore.ieee.org/abstract/document/10107713)
  - Haomiao Yang, Mengyu Ge, Dongyun Xue, Kunlan Xiang, Hongwei Li, and Rongxing Lu. *IEEE Network*, 2023.

**2022**

- A Survey on Gradient Inversion: Attacks, Defenses and Future Directions [[pdf]](https://arxiv.org/abs/2206.07284)
  - Rui Zhang, Song Guo, Junxiao Wang, Xin Xie and Dacheng Tao. *International Joint Conference on Artificial Intelligence*, 2022.

## Tools

- [breaching](https://github.com/JonasGeiping/breaching)

## Gradient Inversion for Computer Vision

### Gradient Inversion in FedSGD

**2024**

- SPEAR:Exact Gradient Inversion of Batches in Federated Learning [[pdf]](https://ui.adsabs.harvard.edu/abs/2024arXiv240303945D/abstract)
  - Dimitar I. Dimitrov, Maximilian Baader, Mark Niklas Müller, Martin Vechev.  arXiv, 2024.
- Hiding in Plain Sight: Disguising Data Stealing Attacks in Federated Learning [[pdf]](https://openreview.net/forum?id=krx55l2A6G) [[code]](https://github.com/insait-institute/seer)
  - Kostadin Garov, Dimitar I. Dimitrov, Nikola Jovanovic, Martin Vechev. ICLR, 2024.

- Maximum Knowledge Orthogonality Reconstruction with Gradients in Federated Learning [[pdf]](https://openaccess.thecvf.com/content/WACV2024/html/Wang_Maximum_Knowledge_Orthogonality_Reconstruction_With_Gradients_in_Federated_Learning_WACV_2024_paper.html) [[code]](https://github.com/wfwf10/MKOR)
  - Feng Wang, Senem Velipasalar, M. Cenk Gursoy. IEEE/CVF Winter Conference on Applications of Computer Vision (WACV), 2024.
- SIA: A sustainable inference attack framework in split learning [[pdf]](https://www.sciencedirect.com/science/article/pii/S0893608023007402)
  - Fangchao Yu, Lina Wang, Bo Zeng, Kai Zhao, Tian Wu, Zhi Pang. Neural Networks, 2024.
- Understanding Deep Gradient Leakage via Inversion Influence Functions [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2023/hash/0c4dd7e3d9f528f0b4f2aca9fbcdca8d-Abstract-Conference.html) [[code]](https://github.com/illidanlab/inversion-influence-function)
  - Haobo Zhang, Junyuan Hong, Yuyang Deng, Mehrdad Mahdavi, Jiayu Zhou. NeurIPS, 2024.
- Generative Image Reconstruction From Gradients [[pdf]](https://ieeexplore.ieee.org/abstract/document/10495167/)

  - Ekanut Sotthiwat, Liangli Zhen, Chi Zhang, Zengxiang Li, Rick Siow Mong Goh. TNNLS, 2024.
- LOKI: Large-scale Data Reconstruction Attack against Federated Learning through Model Manipulation [[pdf]](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a030/1RjEa6sC0I8) [[code]](https://github.com/Manishpandey-0/Adversarial-reconstruction-attack-on-FL-using-LOKI)
  - Joshua C. Zhao, Atul Sharma, Ahmed Roushdy Elkordy, Yahya H. Ezzeldin. IEEE Symposium on Security and Privacy, 2024.
- On Data Distribution Leakage in Cross-Silo Federated Learning [[pdf]](https://ieeexplore.ieee.org/abstract/document/10380460/)
  - Yangfan Jiang, Xinjian Luo, Yuncheng Wu, Xiaochen Zhu, Xiaokui Xiao, Beng Chin Ooi. IEEE Transactions on Knowledge and Data Engineering, 2024.

**2023**

- Scale-MIA: A Scalable Model Inversion Attack against Secure Federated Learning via Latent Space Reconstruction [[pdf]](https://ui.adsabs.harvard.edu/abs/2023arXiv231105808S/abstract)
  - Shanghao Shi, Ning Wang, Yang Xiao, Chaoyu Zhang, Yi Shi, Y.Thomas Hou, Wenjing Lou. arXiv, 2023.
- Minimal Model Structure Analysis for Input Reconstruction in Federated Learning [[pdf]](https://arxiv.org/abs/2010.15718)

  - Jia Qian, Hiba Nassar, Lars kai Hansen. arXiv, 2023.
- The Resource Problem of Using Linear Layer Leakage Attack in Federated Learning [[pdf]](https://openaccess.thecvf.com/content/CVPR2023/html/Zhao_The_Resource_Problem_of_Using_Linear_Layer_Leakage_Attack_in_CVPR_2023_paper.html)
  - Joshua C. Zhao, Ahmed Roushdy Elkordy, Atul Sharma, Yahya H. Ezzeldin, Salman Avestimehr, Saurabh Bagchi. CVPR, 2023.
- Fast Generation-Based Gradient Leakage Attacks against Highly Compressed Gradients [[pdf]](https://ieeexplore.ieee.org/abstract/document/10229091/) [[code]](https://github.com/pigeon-dove/FGLA)
  - Dongyun Xue, Haomiao Yang, Mengyu Ge, Jingwei Li, Guowen Xu, Hongwei Li. Infocom, 2023.
- GAN You See Me? Enhanced Data Reconstruction Attacks against Split Inference [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2023/hash/ab003a4f85ecb1b7b1514ff539dc7395-Abstract-Conference.html) [[code]](https://github.com/ziang1i/GLASS)
  - Ziang Li, Mengda Yang, Yaxin Liu, Juan Wang, Hongxin Hu, Wenzhe Yi, Xiaoyang Xu. NeurIPS, 2023.
- Generative Gradient Inversion via Over-Parameterized Networks in Federated Learning [[pdf]](http://openaccess.thecvf.com/content/ICCV2023/html/Zhang_Generative_Gradient_Inversion_via_Over-Parameterized_Networks_in_Federated_Learning_ICCV_2023_paper.html) [[code]](https://github.com/czhang024/ci-net)
  - Chi Zhang, Xiaoman Zhang, Ekanut Sotthiwat, Yanyu Xu, Ping Liu, Liangli Zhen, Yong Liu. ICCV, 2023.
- Cocktail Party Attack: Breaking Aggregation-Based Privacy in Federated Learning using Independent Component Analysis [[pdf]](https://proceedings.mlr.press/v202/kariyappa23a.html) [[code]](https://github.com/facebookresearch/cocktail_party_attack)

  - Sanjay Kariyappa, Chuan Guo, Kiwan Maeng, Wenjie Xiong, G. Edward Suh, Moinuddin K Qureshi, Hsien-Hsin S. Lee. ICML, 2023.

- Dropout Is NOT All You Need to Prevent Gradient Leakage [[pdf]](https://ojs.aaai.org/index.php/AAAI/article/view/26163) [[code]](https://github.com/dAI-SY-Group/DropoutInversionAttack)

  - Daniel Scheliga, Patrick Mader, Marco Seeland. AAAI, 2023.
- Gradient Obfuscation Gives a False Sense of Security in Federated Learning [[pdf]](https://www.usenix.org/conference/usenixsecurity23/presentation/yue) [[code]](https://github.com/KAI-YUE/rog)

  - Kai Yue, Richeng Jin, Chau-Wai Wong, Dror Baron, Huaiyu Dai. USENIX Security, 2023.
- EGIA: An External Gradient Inversion Attack in Federated Learning [[pdf]](https://ieeexplore.ieee.org/abstract/document/10209197/)

  - Haotian Liang, Youqi Li, Chuan Zhang, Ximeng Liu, Liehuang Zhu. TIFS, 2023.
- Learning To Invert: Simple Adaptive Attacks for Gradient Inversion in Federated Learning [[pdf]](https://proceedings.mlr.press/v216/wu23a.html) [[code]](https://github.com/wrh14/Learning_to_Invert)

  - Ruihan Wu, Xiangyu Chen, Chuan Guo, Kilian Q. Weinberger. Thirty-Ninth Conference on Uncertainty in Artificial Intelligence (PMLR), 2023.
- Using Highly Compressed Gradients in Federated Learning for Data Reconstruction Attacks [[pdf]](https://ieeexplore.ieee.org/abstract/document/10003066/) [[code]](https://github.com/SuperX612/HCGLA)
  - Haomiao Yang, Mengyu Ge, Kunlan Xiang, Jingwei Li. TIFS, 2023.
- When the Curious Abandon Honesty: Federated Learning Is Not Private [[pdf]](https://ieeexplore.ieee.org/abstract/document/10190537/) [[code]](https://github.com/JonasGeiping/breaching)
  - Franziska Boenisch, Adam Dziedzic, Roei Schuster, Ali Shahin Shamsabadi, Ilia Shumailov, Nicolas Papernot. EuroS&P, 2023.
- Reconstructing Individual Data Points in Federated Learning Hardened with Differential Privacy and Secure Aggregation [[pdf]](https://ieeexplore.ieee.org/abstract/document/10190489/)

  - Franziska Boenisch, Adam Dziedzic, Roei Schuster, Ali Shahin Shamsabadi, Ilia Shumailov, Nicolas Papernot. EuroS&P, 2023.
- When the Curious Abandon Honesty: Federated Learning Is Not Private [[pdf]](https://ieeexplore.ieee.org/abstract/document/10190537/) [[code]](https://github.com/JonasGeiping/breaching)
  - Franziska Boenisch, Adam Dziedzic, Roei Schuster, Ali Shahin Shamsabadi, Ilia Shumailov. IEEE 8th European Symposium on Security and Privacy (EuroS&P), 2023.
- Retracted: Defending Privacy Inference Attacks to Federated Learning for Intelligent IoT with Parameter Compression [[pdf]](https://onlinelibrary.wiley.com/doi/full/10.1155/2024/9856054)
  - Yongsheng Zhu, Hongbo Cao, Yuange Ren, Wanqi Wang, Bin Wang, Mingqing Hu, Baigen Cai, Wei Wang. Security and Communication Networks, 2023.
- Do Gradient Inversion Attacks Make Federated Learning Unsafe? [[pdf]](https://ieeexplore.ieee.org/abstract/document/10025466/)

  - Ali Hatamizadeh, Hongxu Yin, Pavlo Molchanov, Andriy Myronenko, Wenqi Li, Prerna Dogra, Andrew Feng, Mona G. Flores, Jan Kautz, Daguang Xu, and Holger R. Roth. TMI, 2023.
- Improved Gradient Inversion Attacks and Defenses in Federated Learning [[pdf]](https://ieeexplore.ieee.org/abstract/document/10024757/)

  - Jiahui Geng, Yongli Mou, Qing Li, Feifei Li, Oya Beyan, Stefan Decker, Chunming Rong. IEEE Transactions on Big Data, 2023.

**2022**

- Towards General Deep Leakage in Federated Learning [[pdf]](https://arxiv.org/abs/2110.09074)
  - Jiahui Geng, Yongli Mou, Feifei Li, Qing Li, Oya Beyan, Stefan Decker, Chunming Rong. arXiv, 2022.

- Bayesian framework for gradient leakage [[pdf]](https://arxiv.org/abs/2111.04706) [[code]](https://github.com/eth-sri/bayes-framework-leakage)
  - Mislav Balunovi ́ c, Dimitar I. Dimitrov, Robin Staab, Martin Vechev. ICLR, 2022.
- Compromise Privacy in Large-Batch Federated Learning via Malicious Model Parameters [[pdf]](https://link.springer.com/chapter/10.1007/978-3-031-22677-9_4)
  - Shuaishuai Zhang, Jie Huang, ZepingZhang, and Chunyang Qi. International Conference on Algorithms and Architectures for Parallel Processing, 2022.
- Stealing Secrecy from Outside: A Novel Gradient Inversion Attack in Federated Learning [[pdf]](https://ieeexplore.ieee.org/abstract/document/10077902/)
  - Chuan Zhang, Haotian Liang, Youqi Li, Tong Wu, Liehuang Zhu, Weiting Zhang. International Conference on Parallel and Distributed Systems (ICPADS), 2022.
- Theory-Oriented Deep Leakage from Gradients via Linear Equation Solver [[pdf]](https://www.usenix.org/conference/usenixsecurity22/presentation/pan-exploring)
  - Xudong Pan, Mi Zhang, Yifan Yan, Jiaming Zhu, and Min Yang. 31st USENIX Security Symposium, 2022.
- Fishing for User Data in Large-Batch Federated Learning via Gradient Magnification [[pdf]](https://proceedings.mlr.press/v162/wen22a.html) [[code]](https://github.com/JonasGeiping/breaching)
  - Yuxin Wen, Jonas A. Geiping, Liam Fowl, Micah Goldblum, Tom Goldstein. International Conference on Machine Learning. PMLR, 2022.
- Robbing the Fed: Directly Obtaining Private Data in Federated Learning with Modified Models [[pdf]](https://openreview.net/forum?id=fwzUgo0FM9v&ref=morioh.com&utm_source=morioh.com) [[code1]](https://github.com/JonasGeiping/breaching) [[code2]](https://github.com/lhfowl/robbing_the_fed)
  - Liam H Fowl, Jonas Geiping, Wojciech Czaja, Micah Goldblum, Tom Goldstein. ICLR, 2022.
- Auditing Privacy Defenses in Federated Learning via Generative Gradient Leakage [[pdf]](http://openaccess.thecvf.com/content/CVPR2022/html/Li_Auditing_Privacy_Defenses_in_Federated_Learning_via_Generative_Gradient_Leakage_CVPR_2022_paper.html) [[code]](https://github.com/zhuohangli/GGL)
  - Zhuohang Li, Jiaxin Zhang, Luyang Liu, Jian Liu. CVPR, 2022.
- Privacy Leakage of Adversarial Training Models in Federated Learning Systems [[pdf]](http://openaccess.thecvf.com/content/CVPR2022W/ArtOfRobust/html/Zhang_Privacy_Leakage_of_Adversarial_Training_Models_in_Federated_Learning_Systems_CVPRW_2022_paper.html) [[code]](https://github.com/zjysteven/PrivayAttack_AT_FL)

  - Jingyang Zhang, Yiran Chen, Hai Li. CVPR, 2022.
- APRIL: Finding the Achilles' Heel on Privacy for Vision Transformers [[pdf]](http://openaccess.thecvf.com/content/CVPR2022/html/Lu_APRIL_Finding_the_Achilles_Heel_on_Privacy_for_Vision_Transformers_CVPR_2022_paper.html) [[code]](https://github.com/JonasGeiping/breaching)
  - Jiahao Lu, Xi Sheryl Zhang, Tianli Zhao, Xiangyu He, Jian Cheng. CVPR, 2022.
- GradViT: Gradient Inversion of Vision Transformers [[pdf]](http://openaccess.thecvf.com/content/CVPR2022/html/Hatamizadeh_GradViT_Gradient_Inversion_of_Vision_Transformers_CVPR_2022_paper.html)

  - Ali Hatamizadeh, Hongxu Yin, Holger Roth, Wenqi Li, Jan Kautz, Daguang Xu, Pavlo Molchanov. ICCV, 2022.
- BI-GAN: batch inversion membership inference attack on federated learning [[pdf]](https://dl.acm.org/doi/abs/10.1145/3556548.3559636) 
  - Hiep Vo, Mingjian Tang, Xi (James) Zheng, Shui Yu. 17th ACM Workshop on Mobility in the Evolving Internet Architecture, MobiArch 2022.
- Enhancing Trajectory Recovery From Gradients via Mobility Prior Knowledge [[pdf]](https://ieeexplore.ieee.org/abstract/document/9951065/)
  - Kaiyue Zhang, Zipei Fan, Xuan Song, Shui Yu. IEEE Internet of Things Journal, 2022.
- GRNN: Generative Regression Neural Network - A Data Leakage Attack for Federated Learning [[pdf]](https://dl.acm.org/doi/abs/10.1145/3510032) [[code]](https://github.com/Rand2AI/GRNN)
  - Hanchi Ren, Jingjing Deng, Xianghua Xie. ACM Transactions on Intelligent Systems and Technology (TIST), 2022.
- CGIR: Conditional Generative Instance Reconstruction Attacks Against Federated Learning [[pdf]](https://ieeexplore.ieee.org/abstract/document/9980415/)

  - Xiangrui Xu, Pengrui Liu, Wei Wang, Hong-Liang Ma, Bin Wang, Zhen Han, Yufei Han. TDSC, 2022.
- Shielding Federated Learning: Aligned Dual Gradient Pruning Against Gradient Leakage [[pdf]](https://openreview.net/forum?id=Fjw_7Hv-mwB)

  - Shengshan Hu*,* Lulu Xue, Ruizhi Zhao, Leo Yu Zhang, Chaowei Xiao, Lichao Sun, Minghui Li, Hai Jin. OpenReview 2022.

**2021**

- Revealing and Protecting Labels in Distributed Training [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2021/hash/0d924f0e6b3fd0d91074c22727a53966-Abstract.html) [[code]](https://github.com/googleinterns/learning-bag-of-words)
  - Trung Dang, Om Thakkar, Swaroop Ramaswamy, Rajiv Mathews, Peter Chin, Françoise Beaufays. NeurIPS, 2021.
- Gradient Inversion with Generative Image Prior [[pdf]](https://proceedings.neurips.cc/paper/2021/hash/fa84632d742f2729dc32ce8cb5d49733-Abstract.html) [[code]](https://github.com/ml-postech/gradient-inversion-generative-image-prior)
  - Jinwoo Jeon, Jaechang Kim, Kangwook Lee, Sewoong Oh, Jungseul Ok. NeurIPS, 2021.
- CAFE: Catastrophic Data Leakage in Vertical Federated Learning [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2021/hash/08040837089cdf46631a10aca5258e16-Abstract.html) [[code]](https://github.com/DeRafael/CAFE)
  - Xiao Jin, Pin-Yu Chen, Chia-Yi Hsu, Chia-Mu Yu, Tianyi Chen. NeurIPS, 2021.
- Evaluating Gradient Inversion Attacks and Defenses in Federated Learning [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2021/hash/3b3fff6463464959dcd1b68d0320f781-Abstract.html) [[code]](https://github.com/RuslandGadget/FCN-Inv)

  - Yangsibo Huang, Samyak Gupta, Zhao Song, Kai Li, Sanjeev Arora. NeurIPS, 2021.
- Understanding Training-Data Leakage from Gradients in Neural Networks for ImageClassifications [[pdf]](https://arxiv.org/abs/2111.10178)
  - Cangxiong Chen, Neill D. F. Campbell. NeurIPS Workshop Privacy in Machine Learning, 2021.
- From Gradient Leakage To Adversarial Attacks In Federated Learning [[pdf]](https://ieeexplore.ieee.org/abstract/document/9506589/) [[code]](https://github.com/Jiaqi0602/adversarial-attack-from-leakage)

  - Jia Qi Lim, Chee Seng Chan. IEEE International Conference on Image Processing, 2021.
- Gradient-Leakage Resilient Federated Learning [[pdf]](https://ieeexplore.ieee.org/abstract/document/9546481/) [[code]](https://github.com/git-disl/Fed-CDP)

  - Wenqi Wei, Ling Liu, Yanzhao Wu, Gong Su, Arun Iyengar. International Conference on Distributed Computing Systems, 2021.

- See Through Gradients: Image Batch Recovery via GradInversion [[pdf]](http://openaccess.thecvf.com/content/CVPR2021/html/Yin_See_Through_Gradients_Image_Batch_Recovery_via_GradInversion_CVPR_2021_paper.html) [[code]](https://github.com/Koukyosyumei/AIJack)

  - Hongxu Yin, Arun Mallya, Arash Vahdat, Jose M. Alvarez, Jan Kautz, Pavlo Molchanov. CVPR, 2021.

**2020**

- Information Leakage by Model Weights on Federated Learning [[pdf]](https://dl.acm.org/doi/abs/10.1145/3411501.3419423)
  - Xiaoyun Xu, Jingzheng Wu, Mutian Yang, Tianyue Luo, Xu Duan, Weiheng Li. Proceedings of the 2020 workshop on privacy-preserving machine learning in practice, 2020.

- R-GAP: Recursive Gradient Attack on Privacy [[pdf]](https://arxiv.org/abs/2010.07733) [[code]](On Data Distribution Leakage in Cross-Silo Federated Learning)
  - Junyi Zhu, Matthew Blaschko. ICLR, 2020.
- Inverting Gradients - How easy is it to break privacy in federated learning? [[pdf]](https://proceedings.neurips.cc/paper/2020/hash/c4ede56bbd98819ae6112b20ac6bf145-Abstract.html) [[code]](https://github.com/JonasGeiping/invertinggradients)

  - Jonas Geiping, Hartmut Bauermeister, Hannah Dröge, Michael Moeller. NeurIPS, 2020.
- PLFG: A Privacy Attack Method Based on Gradients for Federated Learning [[pdf]](https://link.springer.com/chapter/10.1007/978-981-15-9129-7_14)

  - Feng Wu. Security and Privacy in Digital Economy: First International Conference, SPDE 2020.

**2019**

- Deep Leakage from Gradients [[pdf]](https://proceedings.neurips.cc/paper/2019/hash/60a6c4002cc7b29142def8871531281a-Abstract.html) [[code]](https://github.com/mit-han-lab/dlg)

  - Ligeng Zhu, Zhijian Liu, Song Han. NeurIPS, 2019.

**2017**

- Privacy-Preserving Deep Learning: Revisited and Enhanced [[pdf]](https://link.springer.com/chapter/10.1007/978-981-10-5421-1_9)
  - Le Trieu Phong, Yoshinori Aono, Takuya Hayashi, Lihua Wang, and Shiho Moriai. Applications and Techniques in Information Security: 8th International Conference, 2017.

### Gradient Inversion in FedAvg

**2023**

- Approximate and Weighted Data Reconstruction Attack in Federated Learning [[pdf]](https://arxiv.org/abs/2308.06822)
  - Yongcun Song, Ziqi Wang, and Enrique Zuazua. arXiv, 2023.
- LOKI: Large-scale Data Reconstruction Attack against Federated Learning through Model Manipulation [[pdf]](https://arxiv.org/abs/2303.12233) [[code]](https://github.com/Manishpandey-0/Adversarial-reconstruction-attack-on-FL-using-LOKI)
  - Joshua C. Zhao, Atul Sharma, Ahmed Roushdy Elkordy, Yahya H. Ezzeldin, Salman Avestimehr, Saurabh Bagchi. arXiv, 2023.
- Surrogate Model Extension (SME): A Fast and Accurate Weight Update Attack on Federated Learning [[pdf]](https://proceedings.mlr.press/v202/zhu23m.html) [[code]](https://github.com/JunyiZhu-AI/surrogate_model_extension)
  - Junyi Zhu, Ruicong Yao, Matthew B. Blaschko. International Conference on Machine Learning, 2023.

**2022**

- AGIC: Approximate Gradient Inversion Attack on Federated Learning [[pdf]](https://ieeexplore.ieee.org/abstract/document/9996844/)
  - Jin Xu, Chi Hong, Jiyue Huang, Lydia Y. Chen, J ́ er ́ emie Decouchant. International Symposium on Reliable Distributed Systems (SRDS), 2022.
- Data Leakage in Federated Averaging [[pdf]](https://openreview.net/forum?id=e7A0B99zJf) [[code]](https://github.com/eth-sri/fedavg_leakage)
  - Dimitar I. Dimitrov, Mislav Balunović, Nikola Konstantinov, Martin Vechev. Transactions on Machine Learning Research, 2022.

## Gradient Inversion towards Other Tasks

### Gradient Inversion in Natural Language Processing (NLP)

**2024**

- DAGER: Exact Gradient Inversion for Large Language Models [[pdf]](https://arxiv.org/abs/2405.15586)

  - Ivo Petrov, Dimitar I. Dimitrov, Maximilian Baader, Mark Niklas Müller, Martin Vechev. arXiv, 2024.
- FLTrojan: Privacy Leakage Attacks against Federated Language Models Through Selective Weight Tampering [[pdf]](https://arxiv.org/abs/2310.16152)
  - Md Rafi Ur Rashid, Vishnu Asutosh Dasu, Kang Gu, Najrin Sultana, Shagufta Mehnaz. arXiv, 2024.
- FLAT-Chat: A Word Recovery Attack on Federated Language Model Training [[pdf]](https://openreview.net/forum?id=GrunXMbdXY)
  - Qiongkai Xu, Jun Wang, Olga Ohrimenko, Trevor Cohn. Rejected by ICLR, 2024.
- Privacy-Preserving Federal Learning Chain for Internet of Things [[pdf]](https://ieeexplore.ieee.org/abstract/document/10136376/)
  - Yihang Xu, Yuxing Mao, Simou Li, Jian Li, Xueshuo Chen. IEEE Internet of Things Journal, 2024.

**2023**

- Beyond Gradient and Priors in Privacy Attacks: Leveraging Pooler Layer Inputs of Language Models in Federated Learning [[pdf]](https://arxiv.org/abs/2312.05720)
  - Jianwei Li, Sheng Liu, Qi Lei. arXiv, 2023.
- Decepticons: Corrupted Transformers Breach Privacy in Federated Learning for Language Models [[pdf] ](https://arxiv.org/abs/2201.12675) [[code]](https://github.com/JonasGeiping/breaching)

  - Liam Fowl, Jonas Geiping, Steven Reich, Yuxin Wen, Wojtek Czaja, Micah Goldblum, Tom Goldstein. ICLR, 2023.
- Panning for Gold in Federated Learning: Targeted Text Extraction under Arbitrarily Large-Scale Aggregation [[pdf]](https://drive.google.com/file/d/1c9r6UjgPGT6vJ33fyljh5vHfJC5yLoeh/view)
  - Hong-Min Chu, Jonas Geiping, Liam Fowl, Micah Goldblum, Tom Goldstein. ICLR, 2023.
- Reconstructing Training Data from Model Gradient, Provably [[pdf]](https://proceedings.mlr.press/v206/wang23g.html)
  - Zihan Wang, Jason D. Lee, Qi Lei. International Conference on Artificial Intelligence and Statistics, PMLR, 2023.
- Revealing and Protecting Labels in Distributed Training [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2021/hash/0d924f0e6b3fd0d91074c22727a53966-Abstract.html) [[code]](https://github.com/googleinterns/learning-bag-of-words)
  - Trung Dang, Om Thakkar, Swaroop Ramaswamy, Rajiv Mathews, Peter Chin, Françoise Beaufays. NeurIPS, 2021.
- TAG: Gradient Attack on Transformer-based Language Models [[pdf]](https://arxiv.org/abs/2103.06819) [[code]](https://github.com/JonasGeiping/breaching)
  - Jieren Deng, Yijue Wang, Ji Li, Chenghong Wang, Chao Shang, Hang Liu, Sanguthevar Rajasekaran, Caiwen Ding. The 2021 Conference on Empirical Methods in Natural Language Processing, 2021.

**2022**

- LAMP: Extracting Text from Gradients with Language Model Priors [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2022/hash/32375260090404f907ceae19f3564a7e-Abstract-Conference.html) [[code]](FLTrojan: Privacy Leakage Attacks against Federated Language Models Through Selective Weight Tampering)
  - Mislav Balunovi ́, Dimitar I. Dimitrov,∗Nikola Jovanovi ́ c, Martin Vechev. NeurIPS, 2022.
- Recovering Private Text in Federated Learning of Language Models [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2022/hash/35b5c175e139bff5f22a5361270fce87-Abstract-Conference.html) [[code]](https://github.com/Princeton-SysML/FILM)
  - Samyak Gupta, Yangsibo Huang, Zexuan Zhong, Tianyu Gao, Kai Li, Danqi Chen. NeurIPS, 2022.

**2019**

- Deep Leakage from Gradients [[pdf]](https://proceedings.neurips.cc/paper/2019/hash/60a6c4002cc7b29142def8871531281a-Abstract.html) [[code]](https://github.com/mit-han-lab/dlg)

  - Ligeng Zhu, Zhijian Liu, Song Han. NeurIPS, 2019.


### Gradient Inversion in Table

- TabLeak: Tabular Data Leakage in Federated Learning [[pdf]](https://proceedings.mlr.press/v202/vero23a.html) [[code]](https://github.com/eth-sri/tableak)
  - Mark Vero, Mislav Balunovic´, Dimitar I. Dimitrov, Martin Vechev. ICML, 2023.

### Gradient Inversion in Speech Processing

- Speech Privacy Leakage from Shared Gradients in Distributed Learning [[pdf]](https://ieeexplore.ieee.org/document/10095443)
  - Zhuohang Li, Jiaxin Zhang, Jian Liu. ICASSP, 2023.

## Defenses for Gradient Inversion

**2024**

- Concealing Sensitive Samples against Gradient Leakage in Federated Learning [[pdf]](https://ojs.aaai.org/index.php/AAAI/article/view/30171) [[code]](https://github.com/JingWu321/DCS-2)
  - Jing Wu, Munawar Hayat, Mingyi Zhou, Mehrtash Harandi. AAAI, 2024.
- Mixing Gradients in Neural Networks as a Strategy To Enhance Privacy in Federated Learning [[pdf]](https://openaccess.thecvf.com/content/WACV2024/html/Eloul_Mixing_Gradients_in_Neural_Networks_as_a_Strategy_To_Enhance_WACV_2024_paper.html)
  - Shaltiel Eloul, Fran Silavong, Sanket Kamthe, Antonios Georgiadis, and Sean J. Moran CTO, JPMorgan Chase. IEEE/CVF Winter Conference on Applications of Computer Vision, 2024.
- Differentially Private Federated Learning With an Adaptive Noise Mechanism [[pdf]](https://ieeexplore.ieee.org/abstract/document/10262055/)
  - Rui Xue, Kaiping Xue, Bin Zhu, Xinyi Luo, Tianwei Zhang, Qibin Sun, Jun Lu. TIFS, 2024.
- Vulnerabilities of Data Protection in Vertical Federated Learning Training and Countermeasures [[pdf]](https://ieeexplore.ieee.org/abstract/document/10430093/)
  - Derui Zhu, Jinfu Chen, Xuebing Zhou, Weiyi Shang, Ahmed E. Hassan, Jens Grossklags. TIFS, 2024.
- HashVFL: Defending Against Data Reconstruction Attacks in Vertical Federated Learning [[pdf]](https://ieeexplore.ieee.org/abstract/document/10409241/)
  - Pengyu Qiu, Xuhong Zhang, Shouling Ji, Chong Fu, Xing Yang, Ting Wang. TIFS, 2024.
- <i>TAPFed</i> : Threshold Secure Aggregation for Privacy-Preserving Federated Learning [[pdf]](https://ieeexplore.ieee.org/abstract/document/10381802/)
  - Runhua Xu, Bo Li, Chao Li, James Joshi, Shuai Ma, Jianxin Li. TDSC, 2024.
- SIREN+: Robust Federated Learning with Proactive Alarming and Differential Privacy [[pdf]](https://ieeexplore.ieee.org/abstract/document/10423198/) [[code]](https://github.com/AISIGSJTU/Siren-Plus)
  - Hanxi Guo, Hao Wang, Tao Song, Yang Hua Ruhui Ma, Xiulang Jin, Zhengui Xue, Haibing Guan. IEEE Transactions on Dependable and Secure Computing, 2024.
- FLSG: A Novel Defense Strategy Against Inference Attacks in Vertical Federated Learning [[pdf]](https://ieeexplore.ieee.org/abstract/document/10210670/)
  - Kai Fan, Jingtao Hong, Wenjie Li, Xingwen Zhao, Hui Li, Yintang Yang. IEEE Internet of Things Journal, 2024.
- PA-iMFL: Communication-Efficient Privacy Amplification Method Against Data Reconstruction Attack in Improved Multi-Layer Federated Learning [[pdf]](https://ieeexplore.ieee.org/abstract/document/10416901/)
  - Jianhua Wang, Xiaolin Chang, Jelena Mišić, Vojislav B. Mišić, Zhi Chen, and Junchao Fan. IEEE Internet of Things Journal, 2024.
- More than Enough is Too Much: Adaptive Defenses against Gradient Leakage in Production Federated Learning [[pdf]](https://ieeexplore.ieee.org/abstract/document/10477938/) [[code]](https://github.com/TL-System/plato)
  - Fei Wang, Ethan Hugh, Baochun Li. IEEE/ACM Transactions on Networking, 2024.
- GFL-ALDPA: a gradient compression federated learning framework based on adaptive local differential privacy budget allocation [[pdf]](https://link.springer.com/article/10.1007/s11042-023-16543-y)
  - Jiawei Yang, Shuhong Chen, Guojun Wang, Zijia Wang, Zhiyong Jie, Muhammad Arif. Multimedia Tools and Applications, 2024.
- Protecting Label Distribution in Cross-Silo Federated Learning [[pdf]](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a113/1Ub23mqt0hG)
  - Yangfan Jiang, Xinjian Luo, Yuncheng Wu, Xiaokui Xiao, and Beng Chin Ooi. IEEE Symposium on Security and Privacy (SP), 2024.

**2023**

- OASIS: Offsetting Active Reconstruction Attacks in Federated Learning [[pdf]](https://arxiv.org/abs/2311.13739)
  - Tre’ R. Jeter, Truc Nguyen, Raed Alharbi, My T. Thai. arXiv, 2023.
- Gradient Leakage Defense with Key-Lock Module for Federated Learning [[pdf]](https://arxiv.org/abs/2305.04095) [[code]](https://github.com/rand2ai/fedkl)
  - Hanchi Ren, Jingjing Deng, Xianghua Xie, Xiaoke Ma, Jianfeng Ma. arXiv, 2023.
- Enhancing Privacy Preservation in Federated Learning via Learning Rate Perturbation [[pdf]](http://openaccess.thecvf.com/content/ICCV2023/html/Wan_Enhancing_Privacy_Preservation_in_Federated_Learning_via_Learning_Rate_Perturbation_ICCV_2023_paper.html)
  - Guangnian Wan, Haitao Du, Xuejing Yuan, Jun Yang, Meiling Chen, Jie Xu. ICCV, 2023.
- DPAUC: Differentially Private AUC Computation in Federated Learning [[pdf]](https://ojs.aaai.org/index.php/AAAI/article/view/26770) [[code]](https://github.com/bytedance/fedlearner/tree/master/example/privacy/DPAUC)
  - Jiankai Sun, Xin Yang, Yuanshun Yao, Junyuan Xie, Di Wu, Chong Wang. AAAI, 2023.
- Dropout Is NOT All You Need to Prevent Gradient Leakage [[pdf]](https://ojs.aaai.org/index.php/AAAI/article/view/26163)
  - Daniel Scheliga, Patrick M ̈ ader, Marco Seeland. AAAI, 2023.
- Mixed Quantization Enabled Federated Learning To Tackle Gradient Inversion Attacks [[pdf]](https://openaccess.thecvf.com/content/CVPR2023W/FedVision/html/Ovi_Mixed_Quantization_Enabled_Federated_Learning_To_Tackle_Gradient_Inversion_Attacks_CVPRW_2023_paper.html)
  - Pretom Roy Ovi, Emon Dey, Nirmalya Roy, Aryya Gangopadhyay. CVPR, 2023.
- Privacy-Preserving Federated Learning via Disentanglement [[pdf]](https://dl.acm.org/doi/abs/10.1145/3583780.3615014)
  - Wenjie Zhou, Piji Li, Zhaoyang Han, Xiaozhen Lu, Juan Li, Zhaochun Ren, Zhe Liu. Proceedings of the 32nd ACM International Conference on Information and Knowledge Management, 2023.
- Gradient-less Federated Gradient Boosting Tree with Learnable Learning Rates [[pdf]](https://dl.acm.org/doi/abs/10.1145/3578356.3592579) [[code]](https://github.com/adap/flower)
  - Chenyang Ma, Xinchi Qiu, Daniel J. Beutel, Nicholas D. Lane. Proceedings of the 3rd Workshop on Machine Learning and Systems. 2023.
- Privacy-Encoded Federated Learning Against Gradient-Based Data Reconstruction Attacks [[pdf]](https://ieeexplore.ieee.org/abstract/document/10231369/)
  - Hongfu Liu, Bin Li, Changlong Gao, Pei Xie, Chenglin Zhao. TIFS, 2023.
- Compressed Sensing-Based Practical and Efficient Privacy-Preserving Federated Learning [[pdf]](https://ieeexplore.ieee.org/abstract/document/10342861/)
  - Siguang Chen, Yifeng Miao, Xue Li, Chuanxin Zhao. IEEE Internet of Things Journal, 2023.
- Accuracy–Security Tradeoff With Balanced Aggregation and Artificial Noise for Wireless Federated Learning [[pdf]](https://ieeexplore.ieee.org/abstract/document/10129127/)
  - Zhigang Yan, Dong Li, Zhichao Zhang, Jiguang He. IEEE Internet of Things Journal, 2023.
- Automatic Transformation Search Against Deep Leakage From Gradients [[pdf]](https://ieeexplore.ieee.org/abstract/document/10086616/) [[code]](https://github.com/gaow0007/ATSPrivacy)
  - Wei Gao, Xu Zhang, Shangwei Guo, Tianwei Zhang, Tao Xiang, Han Qiu, Yonggang Wen, Yang Liu. IEEE Transactions on Pattern Analysis and Machine Intelligence, 2023.
- Blockchain-Based Swarm Learning for the Mitigation of Gradient Leakage in Federated Learning [[pdf]](https://ieeexplore.ieee.org/abstract/document/10047894/)
  - Hussain Ahmad Madni, Rao Muhammad Umer, Gian Luca Foresti. IEEE Access, 2023.
- DEFEAT: A decentralized federated learning against gradient attacks [[pdf]](https://www.sciencedirect.com/science/article/pii/S2667295223000260)
  - Guangxi Lu, Zuobin Xiong, Ruinian Li, Nael Mohammad, Yingshu Li, Wei Li. High-Confidence Computing, 2023.
- EFMVFL: An Efficient and Flexible Multi-party Vertical Federated Learning without a Third Party [[pdf]](https://dl.acm.org/doi/abs/10.1145/3627993)
  - Yimin Huang, Wanwan Wang, Xingying Zhao, Yukun Wang, Xinyu Feng, Hao He, Ming Yao, Authors Info & Claims. ACM Transactions on Knowledge Discovery from Data, 2023.
- Fedlabx: a practical and privacy-preserving framework for federated learning [[pdf]](https://link.springer.com/article/10.1007/s40747-023-01184-3)
  - Yuping Yan, Mohammed B. M. Kamel, Marcell Zoltay, Marcell Gál, Roland Hollós, Yaochu Jin, Ligeti Péter, Ákos Tényi. Complex & Intelligent Systems, 2023.
- Performance Optimization for Noise Interference Privacy Protection in Federated Learning [[pdf]](https://ieeexplore.ieee.org/abstract/document/10147264/)
  - Zihao Peng, Boyuan Li, Le Li, Shengbo Chen, Guanghui Wang, Hong Rao, Cong Shen. IEEE Transactions on Cognitive Communications and Networking, 2023.
- RoFL: Robustness of Secure Federated Learning [[pdf]](https://ieeexplore.ieee.org/abstract/document/10179400/) [[code1]](https://github.com/pps-lab/rofl-project-code) [[code2]](https://github.com/pps-lab/fl-analysis)
  - Hidde Lycklama, Lukas Burkhalter, Alexander Viand, Nicolas K ̈ uchler, Anwar Hithnawi. IEEE Symposium on Security and Privacy (SP), 2023.
- VFLR: An Efficient and Privacy-Preserving Vertical Federated Framework for Logistic Regression [[pdf]](https://ieeexplore.ieee.org/abstract/document/10050157/)
  - Jiaqi Zhao, Hui Zhu, Fengwei Wang, Rongxing Lu, ErmeiWang, Linfeng Li, Hui Li. IEEE Transactions on Cloud Computing, 2023.
- Shield Against Gradient Leakage Attacks: Adaptive Privacy-Preserving Federated Learning [[pdf]](https://ieeexplore.ieee.org/abstract/document/10264857/)
  - Jiahui Hu, Zhibo Wang, Yongsheng Shen, Bohan Lin, Peng Sun, Xiaoyi Pang, Jian Liu, Kui Ren. IEEE/ACM Transactions on Networking, 2023.

**2022**

- Refiner: Data Refining against Gradient Leakage Attacks in Federated Learning [[pdf]](https://arxiv.org/abs/2212.02042)
  - Mingyuan Fan, Cen Chen, Chengyu Wang, Wenmeng Zhou, Jun Huang, Ximeng Liu, Wenzhong Guo. arXiv, 2022. 
- Mixed Precision Quantization to Tackle Gradient Leakage Attacks in Federated Learning [[pdf]](https://arxiv.org/abs/2210.13457)
  - Pretom Roy Ovi, Emon Dey, Nirmalya Roy, Aryya Gangopadhyay. arXiv, 2022.
- Enhancing Privacy against Inversion Attacks in Federated Learning by using Mixing Gradients Strategies [[pdf]](https://arxiv.org/abs/2204.12495)
  - Shaltiel Eloul, Fran Silavong, Sanket Kamthe, Antonios Georgiadis, Sean J. Moran. arXiv, 2022.
- Combining Variational Modeling with Partial Gradient Perturbation to Prevent Deep Gradient Leakage [[pdf]](https://arxiv.org/abs/2208.04767)
  - Daniel Scheliga, Patrick M  ̈ ader, Marco Seeland. arXiv, 2022.
- Defense Against Gradient Leakage Attacks via Learning to Obscure Data [[pdf]](https://arxiv.org/abs/2206.00769)
  - Yuxuan Wan, Han Xu, Xiaorui Liu, Jie Ren, Wenqi Fan, Jiliang Tang. arXiv, 2022.
- Defense against Privacy Leakage in Federated Learning [[pdf]](https://arxiv.org/abs/2209.05724)
  - Jing Wu, Munawar Hayat, Mingyi Zhou, Mehrtash Harandi. arXiv, 2022.
- SoteriaFL: A Unified Framework for Private Federated Learning with Communication Compression [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2022/hash/1b645a77cf48821afc3ee7e5b5d42617-Abstract-Conference.html) [[code]](https://github.com/haoyuzhao123/soteriafl)
  - Zhize Li, Haoyu Zhao, Boyue Li, Yuejie Chi. NeurIPS, 2022.
- PRECODE - A Generic Model Extension to Prevent Deep Gradient Leakage [[pdf]](http://openaccess.thecvf.com/content/WACV2022/html/Scheliga_PRECODE_-_A_Generic_Model_Extension_To_Prevent_Deep_Gradient_WACV_2022_paper.html) [[code]](https://github.com/SECSY-Group/PRECODE)
  - Daniel Scheliga, Patrick M ̈ ader, Marco Seeland. Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision, 2022.
- Protect Privacy from Gradient Leakage Attack in Federated Learning [[pdf]](https://ieeexplore.ieee.org/abstract/document/9796841/)
  - Junxiao Wang, Song Guo, Xin Xie, Heng Qi. IEEE INFOCOM, 2022.
- FedDef: Defense Against Gradient Leakage in Federated Learning-based Network Intrusion Detection Systems [[pdf]](https://ieeexplore.ieee.org/abstract/document/10188921/)
  - Jiahui Chen, Yi Zhao, Qi Li, Ke Xu. TIFS, 2022.
- PVD-FL: A Privacy-Preserving and Verifiable Decentralized Federated Learning Framework [[pdf]](https://ieeexplore.ieee.org/abstract/document/9777682/)
  - Jiaqi Zhao, Hui Zhu, Fengwei Wang, Rongxing Lu, Zhe Liu, Hui Li. TIFS, 2022.
- Defending Batch-Level Label Inference and Replacement Attacks in Vertical Federated Learning [[pdf]](https://ieeexplore.ieee.org/abstract/document/9833321/)
  - Tianyuan Zou, Yang Liu, Yan Kang, Wenhan Liu, Yuanqin He, Zhihao Yi, Qiang Yang, Ya-Qin Zhang. IEEE Transactions on Big Data, 2022.
- Practical Private Aggregation in Federated Learning Against Inference Attack [[pdf]](https://ieeexplore.ieee.org/abstract/document/9866515/)
  - Ping Zhao, Zhikui Cao, Jin Jiang, and Fei Gao. IEEE Internet of Things Journal, 2022.

**2021**

- Defending against Reconstruction Attack in Vertical Federated Learning [[pdf]](https://fl-icml.github.io/2021/papers/FL-ICML21_paper_21.pdf)
  - Jiankai Sun, Yuanshun Yao, Weihao Gao, Junyuan Xie, Chong Wang. ICML, 2021.
- Privacy-preserving Collaborative Learning with Automatic Transformation Search [[pdf]](http://openaccess.thecvf.com/content/CVPR2021/html/Gao_Privacy-Preserving_Collaborative_Learning_With_Automatic_Transformation_Search_CVPR_2021_paper.html) [[code1]](https://github.com/gaow0007/ATSPrivacy) [[code2]](https://github.com/eth-sri/bayes-framework-leakage) [[code3]](https://github.com/ytingma/ppidsg)
  - Wei Gao, Shangwei Guo, Tianwei Zhang, Han Qiu, Yonggang Wen, Yang Liu. CVPR, 2021.
- Soteria: Provable Defense against Privacy Leakage in Federated Learning from Representation Perspective [[pdf]](http://openaccess.thecvf.com/content/CVPR2021/html/Sun_Soteria_Provable_Defense_Against_Privacy_Leakage_in_Federated_Learning_From_CVPR_2021_paper.html) [[code]](https://github.com/jeremy313/Soteria)
  - Jingwei Sun, Ang Li, Binghui Wang, Huanrui Yang, Hai Li, Yiran Chen. CVPR, 2021.
- PPFL: privacy-preserving federated learning with trusted execution environments [[pdf]](https://dl.acm.org/doi/abs/10.1145/3458864.3466628) [[code]](https://github.com/mofanv/PPFL)
  - Fan Mo, Hamed Haddadi, Kleomenis Katevas, Eduard Marin, Diego Perino, Nicolas Kourtellis. Proceedings of the 19th annual international conference on mobile systems, applications, and services, 2021.
- A Fine-Grained Differentially Private Federated Learning Against Leakage From Gradients [[pdf]](https://ieeexplore.ieee.org/abstract/document/9627872/) [[code]](https://github.com/zlh-thu/DPFL)
  - Linghui Zhu, Xinyi Liu, Yiming Li, Xue Yang, Shu-Tao Xia, Rongxing Lu. IEEE Internet of Things Journal, 2021.
- Privacy-Preserving Federated Learning Framework Based on Chained Secure Multiparty Computing [[pdf]](https://ieeexplore.ieee.org/abstract/document/9187932/) [[code]](https://github.com/ITSEGMQ/Chain-PPFL)
  - Yong Li, Yipeng Zhou, Alireza Jolfaei, Dongjin Yu, Gaochao Xu, Xi Zheng.  IEEE Internet of Things Journal, 2021.
- Digestive neural networks: A novel defense strategy against inference attacks in federated learning [[pdf]](https://www.sciencedirect.com/science/article/pii/S0167404821002029)
  - Hongkyu Lee, Jeehyeong Kim, Seyoung Ahn, Rasheed Hussain, Sunghyun Cho, Junggab Son. computers & security, 2021.
- Gradient Leakage Attack Resilient Deep Learning [[pdf]](https://ieeexplore.ieee.org/abstract/document/9666855/)
  - Wenqi Wei, Ling Liu. TIFS, 2021.

**2020**

- Provable Defense against Privacy Leakage in Federated Learning from Representation Perspective [[pdf]](https://arxiv.org/abs/2012.06043) [[code]](https://github.com/jeremy313/Soteria)
  - Jingwei Sun, Ang Li, Binghui Wang, Huanrui Yang, Hai Li, Yiran Chen. arXiv, 2020.
- InstaHide: Instance-hiding Schemes for Private Distributed Learning [[pdf]](http://proceedings.mlr.press/v119/huang20i.html) [[code]](https://github.com/Hazelsuko07/InstaHide_Challenge)
  - Yangsibo Huang, Zhao Song, Kai Li, Sanjeev Arora. ICML, 2020.
- Labels are Culprits: Defending Gradient Attack On Privacy [[pdf]](http://proceedings.mlr.press/v119/huang20i.html) [[code]](https://github.com/zhaohuali/Label-based-Defense)
  - Zhaohua Li, Le Wang, Zhaoquan Gu, Yang Lv, Zhihong Tian. ICML, 2020.

**2015**

- An Optimized Sparse Response Mechanism for Differentially Private Federated Learning [[pdf]](https://ieeexplore.ieee.org/abstract/document/10210511/)
  - Jiating Ma, Yipeng Zhou, Laizhong Cui, Song Guo. TDSC, 2015.
