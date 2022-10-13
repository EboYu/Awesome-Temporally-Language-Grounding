# Awesome-Temporally-Language-Grounding[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of “Temporally Language Grounding” and related area


## Table of Contents
- [Papers](#papers)
  - [2017](#2017) - [2018](#2018) - [2019](#2019)
- [Dataset](#dataset)
- [Popular Implementations](#popular-implementations)
  - [PyTorch](#pytorch)
  - [TensorFlow](#tensorflow)


## Papers

### Survey
* [The Elements of Temporal Sentence Grounding in Videos: A Survey and Future Directions](https://arxiv.org/abs/2201.08071) - H. Zhang et al, `arxiv 2022`.

### Before
* [Grounded Language Learning from Video Described with Sentences](https://www.aclweb.org/anthology/P13-1006/) - H. Yu et al, `ACL 2013`. 
* [Visual Semantic Search: Retrieving Videos via Complex Textual Queries](<https://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Lin_Visual_Semantic_Search_2014_CVPR_paper.pdf>) - Dahua Lin et al, `CVPR 2014`.
* [Jointly Modeling Deep Video and Compositional Text to Bridge Vision and Language in a Unified Framework](https://www.aaai.org/ocs/index.php/AAAI/AAAI15/paper/view/9734) - R. Xu et al, `AAAI 2015`.
* [Unsupervised Alignment of Actions in Video with Text Descriptions](https://pdfs.semanticscholar.org/5893/7d427ff36e1470b18120245148355047e4ea.pdf) - Y. C. Song et al, `IJCAI 2016`.

### 2017
* [TALL: Temporal Activity Localization via Language Query](http://arxiv.org/abs/1705.02101) - Gao et al, `ICCV 2017`. [[code1]](https://github.com/jiyanggao/TALL) [[code2]](https://github.com/WuJie1010/Temporally-language-grounding)
* [Localizing Moments in Video with Natural Language](https://arxiv.org/pdf/1708.01641.pdf) - Hendricks et al, `ICCV 2017`. [[code]](https://github.com/LisaAnne/LocalizingMoments) 
* !(Still on arxiv 20200609)[Where to Play: Retrieval of Video Segments using Natural-Language Queries](<https://arxiv.org/abs/1707.00251>) - S. Lee et al, `arxiv 2017`.

### 2018
* [Localizing Moments in Video with Temporal Language](https://arxiv.org/pdf/1809.01337.pdf) - Hendricks et al, `EMNLP 2018`.
* [MAC: Mining Activity Concepts for Language-based Temporal Localization](https://arxiv.org/pdf/1811.08925.pdf) - Ge et al, `WACV 2018`. [[code1]](https://github.com/runzhouge/MAC) [[code2]](https://github.com/WuJie1010/Temporally-language-grounding)
* [Temporally Grounding Natural Sentence in Video](https://chenxinpeng.github.io/publication/2018_EMNLP_TGN.pdf) - Chen et al, `EMNLP 2018`.
* [Cross-modal Moment Localization in Videos](https://www.researchgate.net/publication/328374995_Cross-modal_Moment_Localization_in_Videos) - Liu et al, `ACM MM 2018`. [[code]](https://acmmm18.wixsite.com/role)
* [Attentive Moment Retrieval in Videos](https://dl.acm.org/citation.cfm?id=3210003) - Liu et al, `SIGIR 2018`. [[code]](https://sigir2018.wixsite.com/acrn)
* [Multi-modal Circulant Fusion for Video-to-Language and Backward](https://www.ijcai.org/proceedings/2018/0143.pdf) - Wu et al, `IJCAI 2018`.
* (Video Retrieval+Grounding)[Find and Focus: Retrieve and Localize Video Events with Natural Language Queries](<http://openaccess.thecvf.com/content_ECCV_2018/papers/Dian_SHAO_Find_and_Focus_ECCV_2018_paper.pdf>) - Dian Shao  et al, `ECCV 2018`.

### 2019

Supervised:
* [MAC: Mining Activity Concepts for Language-based Temporal Localization](https://arxiv.org/abs/1811.08925) - Runzhou Ge Ge et al, `WACV 2019`. [[code]](https://github.com/runzhouge/MAC)
* [Tripping through time Efficient Localization of Activities in Videos](https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&q=Tripping+through+time%3A+Efficient+Localization+of+Activities+in+Videos&btnG=
) - He et al, `CVPR Workshop 2019`.
* [Multilevel Language and Vision Integration for Text-to-Clip Retrieval](<https://arxiv.org/abs/1804.05113>) - H. Xu et al, `AAAI 2019`. [[code]](<https://github.com/VisionLearningGroup/Text-to-Clip_Retrieval>)
* [Read, Watch, and Move: Reinforcement Learning for Temporally Grounding Natural Language Descriptions in Videos](https://arxiv.org/abs/1901.06829) - He, Dongliang et al, `AAAI 2019`.
* [To Find Where You Talk: Temporal Sentence Localization in Video with Attention Based Location Regression](http://arxiv.org/abs/1804.07014) - Y. Yuan et al, `AAAI 2019`. [[code]](https://github.com/yytzsy/ABLR_code)
* [Semantic Proposal for Activity Localization in Videos via Sentence Query](http://yugangjiang.info/publication/19AAAI-actionlocalization.pdf) - S. Chen et al, `AAAI 2019`.
* [Localizing natural language in videos](https://www.aaai.org/ojs/index.php/AAAI/article/view/4827/4700) - J. Chen et al, `AAAI 2019`.
* [ExCL: Extractive Clip Localization Using Natural Language Descriptions](https://arxiv.org/abs/1904.02755) - S. Ghosh et al, `NAACL 2019`.
* [Cross-Modal Video Moment Retrieval with Spatial and Language-Temporal Attention](https://dl.acm.org/citation.cfm?id=3325019) - B. Jiang et al, `ICMR 2019`. [[code]](https://github.com/BonnieHuangxin/SLTA)
* [Language-Driven Temporal Activity Localization_ A Semantic Matching Reinforcement Learning Model](<http://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Language-Driven_Temporal_Activity_Localization_A_Semantic_Matching_Reinforcement_Learning_Model_CVPR_2019_paper.pdf>) - W. Wang et al, `CVPR 2019`. 
* [MAN: Moment Alignment Network for Natural Language Moment Retrieval via Iterative Graph Adjustment](https://arxiv.org/abs/1812.00087) - Da Zhang et al, `CVPR 2019`. 
* [Cross-Modal Interaction Networks for Query-Based Moment Retrieval in Videos](https://arxiv.org/abs/1906.02497) - Zhu Zhang et al, `SIGIR 2019`. [[code]](https://github.com/ikuinen/CMIN_moment_retrieval)
* [Semantic Conditioned Dynamic Modulation for Temporal Sentence Grounding in Videos](https://arxiv.org/pdf/1910.14303.pdf) - Yitian Yuan et al, `NeurIPS 2019`. [[code]](https://github.com/yytzsy/SCDM)
* [DEBUG: A Dense Bottom-Up Grounding Approach for Natural Language Video Localization](https://www.aclweb.org/anthology/D19-1518.pdf) - Chujie Lu et al, `EMNLP 2019`.
* !(still on arxiv 20200609)[Temporal Localization of Moments in Video Collections with Natural Language](https://arxiv.org/abs/1907.12763v1) - V. Escorcia et al, `arxiv 2019`. 

Weakly Supervised:
* [Weakly Supervised Video Moment Retrieval From Text Queries](<https://arxiv.org/abs/1904.03282>) - N. C. Mithun et al, `CVPR 2019`. 
* [Weakly-supervised spatio-temporally grounding natural sentence in video](https://www.aclweb.org/anthology/P19-1183.pdf) - Zhenfang Chen et al, `ACL 2019`. [[code]](https://github.com/JeffCHEN2017/WSSTG.git.)
* [WSLLN: Weakly Supervised Natural Language Localization Networks](https://arxiv.org/abs/1909.00239) - M. Gao et al, `EMNLP 2019`. 

### 2020

Supervised:
* [Moment Retrieval via Cross-Modal Interaction Networks With Query Reconstruction](https://ieeexplore.ieee.org/abstract/document/8962274) - Zhijie Lin et al, `TIP 2020`.
* [Rethinking the Bottom-Up Framework for Query-based Video Localization](https://aaai.org/ojs/index.php/AAAI/article/view/6627) - Long Chen et al, `AAAI 2020`.
* [Temporally Grounding Language Queries in Videos by Contextual Boundary-aware Prediction](https://arxiv.org/abs/1909.05010) - Jingwen Wang et al, `AAAI 2020`. [[code]](https://github.com/JaywongWang/CBP)
* [Learning 2D Temporal Adjacent Networks for Moment Localization with Natural Language](https://arxiv.org/pdf/1912.03590.pdf) - Songyang Zhang et al, `AAAI 2020`. [[code]](https://github.com/microsoft/2D-TAN)
* [Tree-Structured Policy based Progressive Reinforcement Learning for Temporally Language Grounding in Video](https://arxiv.org/pdf/2001.06680.pdf) - Jie Wu et al, `AAAI 2020`. [[code]](https://github.com/WuJie1010/TSP-PRL)
* [Proposal-free Temporal Moment Localization of a Natural-Language Query in Video using Guided Attention](https://arxiv.org/abs/1908.07236) - C. R. Opazo et al, `WACV 2020`. [[code]](https://github.com/crodriguezo/TMLGA)
* [Local-Global Video-Text Interactions for Temporal Grounding](http://arxiv.org/abs/2004.07514) - Mun Jonghwan et al, `CVPR 2020`. [[code]](https://github.com/JonghwanMun/LGI4temporalgrounding)
* [Dense Regression Network for Video Grounding](http://arxiv.org/abs/2004.03545) - Zeng Runhao et al, `CVPR 2020`. [[code]](https://github.com/Alvin-Zeng/DRN)
* [Tripping through time: Efficient Localization of Activities in Videos](https://arxiv.org/abs/1904.09936) - Meera Hahn et al, `BMVC 2020`.
* [Span-based Localizing Network for Natural Language Video Localization](https://www.aclweb.org/anthology/2020.acl-main.585/) - Hao Zhang et al, `ACL 2020`. [[code]](https://github.com/IsaacChanghau/VSLNet)
* [Hierarchical Visual-Textual Graph for Temporal Activity Localization via Language](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123650596.pdf) - Shaoxiang Chen et al, `ECCV 2020`. [[code]](https://github.com/forwchen/HVTG)
* [Learning Modality Interaction for Temporal Sentence Localization and Event Captioning in Videos](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123490324.pdf) - Shaoxiang Chen et al, `ECCV 2020`.
* [Jointly Cross- and Self-Modal Graph Attention Network for Query-Based Moment Localization](http://arxiv.org/abs/2008.01403) - Daizong Liu et al, `MM 2020`. [[code]](https://github.com/liudaizong/CSMGAN)
* [Fine-grained Iterative Attention Network for Temporal Language Localization in Videos](http://arxiv.org/abs/2008.02448) - Xiaoye Qu et al, `MM 2020`.
* [Dual Path Interaction Network for Video Moment Localization](https://dl.acm.org/doi/10.1145/3394171.3413975) - Hao Wang et al, `MM 2020`.
* [Adversarial Video Moment Retrieval by Jointly Modeling Ranking and Localization](https://dl.acm.org/doi/10.1145/3394171.3413841) -  et al, `MM 2020`. [[code]](https://github.com/yawenzeng/AVMR)
* [STRONG: Spatio-Temporal Reinforcement Learning for Cross-Modal Video Moment Localization](https://dl.acm.org/doi/10.1145/3394171.3413840) - Da Cao et al, `MM 2020`. [[code]](https://github.com/yawenzeng/STRONG)
* [Reinforcement Learning for Weakly Supervised Temporal Grounding of Natural Language in Untrimmed Videos](http://arxiv.org/abs/2009.08614) - Jie Wu et al, `MM 2020`.
* [Language Guided Networks for Cross-modal Moment Retrieval](http://arxiv.org/abs/2006.10457) - Kun Liu et al, `arxiv`.

Weakly Supervised:
* [Weakly-Supervised Video Moment Retrieval via Semantic Completion Network](https://arxiv.org/pdf/1911.08199.pdf) - Zhijie Lin et al, `AAAI 2020`.
* [VLANet: Video-Language Alignment Network for Weakly-Supervised Video Moment Retrieval](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123730154.pdf) - Minuk Ma et al, `ECCV 2020`.
* [Two-Stream Consensus Network for Weakly-Supervised Temporal Action Localization](https://arxiv.org/abs/2010.11594) - Yuanhao Zhai et al, `ECCV 2020`.
* [Regularized Two-Branch Proposal Networks for Weakly-Supervised Moment Retrieval in Videos](https://arxiv.org/abs/2008.08257) - Zhu Zhang et al, `MM 2020`. [[code]](https://github.com/ikuinen/regularized_two-branch_proposal_network)
* [Counterfactual Contrastive Learning for Weakly-Supervised Vision-Language Grounding](https://proceedings.neurips.cc/paper/2020/file/d27b95cac4c27feb850aaa4070cc4675-Paper.pdf) - Zhang Zhu et al, `NeruIPS 2020`.

### 2021
* [Interaction-Integrated Network for Natural Language Moment Localization](https://ieeexplore.ieee.org/abstract/document/9334438) - Ke Ning et al, 'TIP 2021'.
* [Boundary Proposal Network for Two-Stage Natural Language Video Localization](https://arxiv.org/abs/2103.08109) - Shaoning Xiao et al, `AAAI 2021`.
* [Context-Aware Biaffine Localizing Network for Temporal Sentence Grounding](https://openaccess.thecvf.com/content/CVPR2021/html/Liu_Context-Aware_Biaffine_Localizing_Network_for_Temporal_Sentence_Grounding_CVPR_2021_paper.html) - Liu et al, `CVPR 2021`. 
* [Multi-Modal Relational Graph for Cross-Modal Video Moment Retrieval](https://openaccess.thecvf.com/content/CVPR2021/html/Zeng_Multi-Modal_Relational_Graph_for_Cross-Modal_Video_Moment_Retrieval_CVPR_2021_paper.html) - Zeng et al, `CVPR 2021`. 
* [Thinking Fast and Slow: Efficient Text-to-Visual Retrieval With Transformers](https://openaccess.thecvf.com/content/CVPR2021/html/Miech_Thinking_Fast_and_Slow_Efficient_Text-to-Visual_Retrieval_With_Transformers_CVPR_2021_paper.html) - Miech et al, `CVPR 2021`. 
* [Fast Video Moment Retrieval](https://openaccess.thecvf.com/content/ICCV2021/html/Gao_Fast_Video_Moment_Retrieval_ICCV_2021_paper.html) - Gao et al, `ICCV 2021`.
* [Hierarchical Deep Residual Reasoning for Temporal Moment Localization](https://arxiv.org/abs/2111.00417) - Ma et al, `arxiv`.
* [Self-supervised learning for semi-supervised temporal language grounding](https://arxiv.org/abs/2109.11475) - Luo et al, `arxiv`.

### 2022

* [CONE: An Efficient COarse-to-fiNE Alignment Framework for Long Video Temporal Grounding](https://arxiv.org/abs/2209.10918) - Hou Z. et al, `arxiv`.
* [Mad: A scalable dataset for language grounding in videos from movie audio descriptions](https://openaccess.thecvf.com/content/CVPR2022/html/Soldan_MAD_A_Scalable_Dataset_for_Language_Grounding_in_Videos_From_CVPR_2022_paper.html) - M. Solden et al. `CVPR 2022`

## Dataset
* [TACoS](https://www.mendeley.com/catalogue/script-data-attributebased-recognition-composite-activities/)
* [Charades-STA](http://arxiv.org/abs/1705.02101)
* [ActivityNet](http://arxiv.org/abs/1705.00754)
* [DiDeMo](https://arxiv.org/abs/1708.01641)


## Popular Implementations
### PyTorch
* [WuJie1010/Temporally-language-grounding](https://github.com/WuJie1010/Temporally-language-grounding)
### TensorFlow
* [jiyanggao/TALL](https://github.com/jiyanggao/TALL)
* [yytzsy/ABLR_code](https://github.com/yytzsy/ABLR_code)

