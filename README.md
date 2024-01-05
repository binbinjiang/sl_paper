# Awesome AI Sign Language Papers & Popularization of Professional Knowledge [UPDATING]

`This repository is all you need to open the door about AI sign languages!`

**Keywords**: Sign Language, Sign Language Translation (**SLT**), Sign Language Recognition (**SLR**), Sign Language Production (**SLP**), Sign Language Linguistics

<details><summary><b>What's New</b></summary>
`Update 2023-12-23:` More concise layout & updated contents & Add the introduction of sign language knowledge.
</details>


<details open><summary><b name="table-of-content">Table of contents</b></summary>

- [Introduction](#introduction)

- [Popularization of Professional Sign Language Knowledge](#sl_knowledge)
  - [Why AI Sign Language Research?](#why_sl)
  - [Do you know the differences between SLT and SLR?](#slt_vs_slr)
  - [More details you must know about SLR tasks?](#slr_details)

- [Survey/Review Papers](#survey)

- [AI Sign Language in Timeline [Papers]](#sl_paper_timeline)
  - [2023](#sl_paper_2023)
  - [2022](#sl_paper_2022)
  - [2021](#sl_paper_2021)
  - [2020](#sl_paper_2020)
  - [2019](#sl_paper_2019)
  - [2018](#sl_paper_2018) -> `True SLT began in 2018`
  - [2017](#sl_paper_2017)
  - [Earlier](#sl_paper_earlier)

- [AI Sign Language in Well-Known Institutions [Papers]](#sl_paper_institution)
  - [XMU (厦门大学) SL](#sl_paper_xmu) -> `active`
  - [USTC (中国科学技术大学) SL](#sl_paper_ustc)
  - [ZJU (浙江大学) SL](#sl_paper_zju) -> `active`
  - [THU (清华大学) SL](#sl_paper_thu)
  - [Germany-UK (英德) SL](#sl_paper_germany-uk)

- [Sign Language Datasets](#datasets)

- [AI Sign Language Related Fields](#related_fields)
</details>


## Introduction <a name="introduction"></a>

This repository is for those interested in the field of AI sign language (SL). The collected papers have been categorized according to different criteria (btime, type, institution, etc.) for ease of searching.

If useful, please `Star` this repo, we are keeping it updated.

**NOTE**: There is overlap between the different categories. Please feel free to submit your ***Pull Requests*** for any updates.

- Collaborators & Contributors (welcome to join us!):
  - [Jiangbin Zheng](https://github.com/binbinjiang), Westlake University & Zhejiang University, China
  - [Yidong Chen](https://github.com/ydc) & [Pei Yu](https://github.com/yp20000921) & [Rui Zhao](https://github.com/rzhao-zhsq), Xiamen University, China
  - [Haodong Zhang](https://github.com/0aqz0), Zhejiang University, China
  - [Junfu Pu](https://github.com/Jevin754), University Of Science and Technology of China

## Popularization of Professional Sign Language Knowledge <a name="sl_knowledge"></a>

### - Why AI Sign Language Research? <a name="why_sl"></a>

<details open><summary><b name="table-of-content">Unfolding Details</b></summary>

<!-- ![](./src/fig1.jpg) -->
<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);width:60%" 
    src="./src/fig1.jpg">
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;">Figure 1. Communication gap between the hearing and the deaf.
</div>
</center>

Sign languages are the primary language of the deaf community. However, most hearing people find it difficult to understand sign languages. With the development of AI, researchers are trying to help people understand sign languages using AI techniques that are designed to convert sign languages into spoken languages in textual form.

</details>

### - Do you know the differences between SLT and SLR? <a name="slt_vs_slr"></a>

<details open><summary><b name="table-of-content">Unfolding Details</b></summary>

<!-- ![](./src/fig2.jpg) -->
<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
    src="./src/fig2.jpg">
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;">Figure 2. SLR (Sign Language Recognition) vs. SLT (Sign Language Translation).
</div>
</center>

At the very beggining, I wanna explain the difference between SLT and SLR, as shown in Fig. 2. I'm sure this is very important for most of you!


In early efforts, researchers explored this problem (sign languages -> text-form glosses) as a recognition problem (i.e., SLR), which converts sign languages to `glosses` ***word by word*** according to the sign languages ***sequentially***. Although glosses are in textual form, they do not provide meaningful interpretations of what a signer is saying because sign languages and glosses have their own ***specific linguistic rules***, which are quite different from spoken languages.

As a result, researchers find it terrible to ignore the linguistic properties of sign language. Contrary to SLR, sign language translaton (SLT) systems aim to translate sign language videos into spoken sentences directly. 

As far as AI technology is concerned, SLR belongs to the field of *Computer Vision + Text Recognition*, while SLT belongs to the field of *Computer Vision + Text Translation*.

</details>


### - More details you must know about SLR tasks? <a name="slr_details"></a>
<details open><summary><b name="table-of-content">Unfolding Details</b></summary>

By default, we refer to the current `Continuous SLR` as SLR because this type of SLR is the mainstream of the deep learning era.

In fact, it is important to note that SLR tasks are generally divided into three categories: **finger-spelling recognition**, **isolated word recognition** and **continuous sign language recognition**. In the early days (before about 2018), SLR works mainly focused on lexical-level tasks, such as finger-spelling recognition and isolated word recognition. Nowadays, the more practical **continuous SLR** has become mainstream sign language research

For more categorization and details, we recommend you read this [survey/review paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8764391) for a detailed look at AI Sign history.
</details>


## SURVEY/REVIEW PAPERS <a name="survey"></a>
[[Back to TOP]](#table-of-content)

- 【IEEE Access 2019 (`Recommended`)】Technical approaches to Chinese sign language processing: A review. *Suhail Muhammad Kamal; Yidong Chen; Shaozi Li; Xiaodong Shi; Jiangbin Zheng.* [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8764391) `Tags:` **Survey**


## AI Sign Language in Timeline [Papers] <a name='sl_paper_timeline'></a>

### 2023 <a name='sl_paper_2023'></a>
[[Back to TOP]](#table-of-content)

- 【CVPR 2023 `(Highlight Paper)`】CVT-SLR: Contrastive Visual-Textual Transformation for Sign Language Recognition with Variational Alignment. *Jiangbin Zheng, Yile Wang, Cheng Tan, Siyuan Li, Ge Wang, Jun Xia, Yidong Chen, Stan Z. Li.* [[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Zheng_CVT-SLR_Contrastive_Visual-Textual_Transformation_for_Sign_Language_Recognition_With_Variational_CVPR_2023_paper.html) [[code]](https://github.com/binbinjiang/CVT-SLR) `Tags:` **SLR**; Westlake University & Zhejiang University & Xiamen University & Tsinghua University
- 【IJCAI 2023】Efficient Sign Language Translation with a Curriculum-based NAR Decoder. *Pei Yu1, Liang Zhang, Biao Fu1, Yidong Chen.* [[paper]](https://www.ijcai.org/proceedings/2023/0584.pdf) *code* `Tags:` **SLT**
- 【ICASSP 2023】A Token-level Contrastive Framework for Sign Language Translation. *Biao Fu, Peigen Ye, Liang Zhang, Pei Yu, Cong Hu, Yidong Chen, Xiaodong Shi.* [[paper]](https://arxiv.org/pdf/2204.04916.pdf) *code* `Tags:` **SLT**
- 【AAAI 2023】Self-Emphasizing Network for Continuous Sign Language Recognition. *Lianyu Hu, Liqing Gao, Zekang liu, Wei Feng.* [[paper]](https://arxiv.org/pdf/2211.17081.pdf) *code* `Tags:` **SLR**
- 【EACL 2023】Scaling Back-Translation with Domain Text Generation for Sign Language Gloss Translation. *Jinhui Ye, Wenxiang Jiao, Xing Wang, Zhaopeng Tu.* [[paper]](https://arxiv.org/abs/2210.07054) *code* `Tags:` **Sign Gloss Translation**

### 2022 <a name='sl_paper_2022'></a>
[[Back to TOP]](#table-of-content)
- 【Arxiv 2022】Leveraging Graph-based Cross-modal Information Fusion for Neural Sign Language Translation. [[paper]](https://arxiv.org/pdf/2211.00526.pdf) *code* `Tags:` **SLT**
- 【CVPR 2022】A Simple Multi-Modality Transfer Learning Baseline for Sign Language Translation. *Yutong Chen, Fangyun Wei, Xiao Sun, Zhirong Wu, Stephen Lin.* [[paper]](https://arxiv.org/abs/2203.04287) *code* `Tags:` **SLT**
- 【CVPR 2022】MLSLT: Towards Multilingual Sign Language Translation. *Aoxiong Yin, Zhou Zhao, Weike Jin, Meng Zhang, Xingshan Zeng, Xiaofei He.* [[paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Yin_MLSLT_Towards_Multilingual_Sign_Language_Translation_CVPR_2022_paper.pdf) *code* `Tags:` **SLT**
- 【CVPR 2022】C2SLR: Consistency-Enhanced Continuous Sign Language Recognition. *Ronglai Zuo, Brian Mak.* [[paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Zuo_C2SLR_Consistency-Enhanced_Continuous_Sign_Language_Recognition_CVPR_2022_paper.html) *code* `Tags:` **SLR**
- 【NeurIPS 2022】Two-Stream Network for Sign Language Recognition and Translation. *Yutong Chen, Ronglai Zuo, Fangyun Wei, Yu Wu, Shujie Liu, Brian Mak.* [[paper]](https://arxiv.org/abs/2211.01367) *code* `Tags:` **SLT & SLR**
- 【EMNLP 2022】Open-Domain Sign Language Translation Learned from Online Video. *Bowen Shi, Diane Brentari, Greg Shakhnarovich, Karen Livescu.* [[paper]](https://arxiv.org/abs/2205.12870) *code* `Tags:` **SLT**
- 【NAACL 2022 Findings】Explore More Guidance: A Task-aware Instruction Network for Sign Language Translation Enhanced with Data Augmentation. *Yong Cao, Wei Li, Xianzhi Li, Min Chen, Guangyong Chen, Long Hu, Zhengdao Li, Hwang Kai.* [[paper]](https://arxiv.org/pdf/2204.05953.pdf) *code* `Tags:` **SLT**
- 【ACL 2022】WLASL-LEX: a Dataset for Recognising Phonological Properties in American Sign Language. *Federico Tavella, Viktor Schlegel, Marta Romeo, Aphrodite Galata, Angelo Cangelosi.* [[paper]](https://arxiv.org/pdf/2203.06096.pdf) *code* `Tags:` **Dataset**
- 【ACL 2022】Searching for fingerspelled content in American Sign Language. *Bowen Shi, Diane Brentari, Greg Shakhnarovich, Karen Livescu.* [[paper]](https://arxiv.org/pdf/2203.13291.pdf) *code* `Tags:` **Fingerspelled SL**
- 【ECCV 2022】Automatic dense annotation of large-vocabulary sign language videos. *Liliane Momeni, Hannah Bull, K R Prajwal, Samuel Albanie, G��l Varol, Andrew Zisserman.* [[paper]](https://arxiv.org/pdf/2208.02802.pdf) *code* `Tags:` **Annotation**
- 【ECCV 2022】Temporal Lift Pooling for Continuous Sign Language Recognition. *Lianyu Hu, Liqing Gao, Zekang Liu, Wei Feng.* [[paper]](https://arxiv.org/abs/2207.08734) *code* `Tags:` **SLR**
- 【ACMMM 2022】MC-SLT: Towards Low-Resource Signer-Adaptive Sign Language Translation. *Tao Jin, Zhou Zhao, Meng Zhang, Xingshan Zeng.* [[paper]](https://dl.acm.org/doi/abs/10.1145/3503161.3548069) *code* `Tags:` **SLT**
- 【WACV 2022】Sign Language Translation With Hierarchical Spatio-Temporal Graph Neural Network. *Jichao Kan, Kun Hu, Markus Hagenbuchner, Ah Chung Tsoi, Mohammed Bennamoun, Zhiyong Wang.* [[paper]](https://openaccess.thecvf.com/content/WACV2022/papers/Kan_Sign_Language_Translation_With_Hierarchical_Spatio-Temporal_Graph_Neural_Network_WACV_2022_paper.pdf) *code* `Tags:` **SLT**

### 2021 <a name='sl_paper_2021'></a>
[[Back to TOP]](#table-of-content)
- 【Neurocomputing 2021】Enhancing neural sign language translation by highlighting the facial expression information. [[paper]](https://www.sciencedirect.com/science/article/abs/pii/S0925231221012698) *code* `Tags:` **SLT**
- 【TMM 2021】Spatial-Temporal Multi-Cue Network for Sign Language Recognition and Translation. *Hao Zhou, Wengang Zhou, Yun Zhou, Houqiang Li.* [[paper]](https://ieeexplore.ieee.org/abstract/document/9354538/) *code* `Tags:` **SLT & SLR**
- 【ICCV 2021】YouRefIt: Embodied Reference Understanding With Language and Gesture. *Yixin Chen; Qing Li; Deqian Kong; Yik Lun Kei; Song-Chun Zhu; Tao Gao; Yixin Zhu; Siyuan Huang.* [[paper]](https://arxiv.org/abs/2109.03413) *code* `Tags:` **SLR**
- 【ICCV 2021】Speech Drives Templates: Co-Speech Gesture Synthesis With Learned Templates. *Shenhan Qian; Zhi Tu; Yihao Zhi; Wen Liu; Shenghua Gao.* [[paper]](https://arxiv.org/abs/2108.08020) *code* `Tags:` **SLR**
- 【ICCV 2021】Audio2Gestures: Generating Diverse Gestures From Speech Audio With Conditional Variational Autoencoders. *Jing Li; Di Kang; Wenjie Pei; Xuefei Zhe; Ying Zhang; Zhenyu He; Linchao Bao.* [[paper]](https://arxiv.org/abs/2108.06720) *code* `Tags:` **SLR**
- 【ICCV 2021】Aligning Subtitles in Sign Language Videos. *Hannah Bull; Triantafyllos Afouras; G��l Varol; Samuel Albanie; Liliane Momeni; Andrew Zisserman.* [[paper]](https://arxiv.org/abs/2105.02877) *code* `Tags:` **SLR**
- 【ICCV 2021】Mixed SIGNals: Sign Language Production via a Mixture of Motion Primitives. *Ben Saunders; Necati Cihan Camgoz; Richard Bowden.* [[paper]](https://arxiv.org/abs/2107.11317) *code* `Tags:` **SLR**
- 【ICCV 2021】SignBERT: Pre-Training of Hand-Model-Aware Representation for Sign Language Recognition. *Hezhen Hu; Weichao Zhao; Wengang Zhou; Yuechen Wang; Houqiang Li.* [[paper]](https://arxiv.org/pdf/2110.05382.pdf) *code* `Tags:` **SLR**
- 【ICCV 2021】Visual Alignment Constraint for Continuous Sign Language Recognition. *Yuecong Min, Aiming Hao, Xiujuan Chai, and Xilin Chen.* [[paper]](https://arxiv.org/abs/2104.02330) [[code]](https://github.com/ycmin95/VAC_CSLR) `Tags:` **SLR**
- 【ICCV 2021】Self-Mutual Distillation Learning for Continuous Sign Language Recognition. *Aiming Hao, Yuecong Min, and Xilin Chen.* [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9710140) *code* `Tags:` **SLR**
- 【CVPR 2021】Improving Sign Language Translation With Monolingual Data by Sign Back-Translation. *Hao Zhou, Wengang Zhou, Weizhen Qi, Junfu Pu, Houqiang Li.* [[paper]](https://arxiv.org/abs/2105.12397) *code* `Tags:` **SLR**
- 【CVPR 2021】How2Sign: A Large-Scale Multimodal Dataset for Continuous American Sign Language. *Amanda Duarte, Shruti Palaskar, Lucas Ventura, Deepti Ghadiyaram, Kenneth DeHaan, Florian Metze, Jordi Torres, Xavier Giro-i-Nieto.* [[paper]](https://arxiv.org/abs/2008.08143) *code* `Tags:` **SLR**
- 【CVPR 2021】Fingerspelling Detection in American Sign Language. *Bowen Shi, Diane Brentari, Greg Shakhnarovich, Karen Livescu.* [[paper]](https://arxiv.org/abs/2104.01291) *code* `Tags:` **SLR**
- 【CVPR 2021】Read and Attend: Temporal Localisation in Sign Language Videos. *G��l Varol, Liliane Momeni, Samuel Albanie, Triantafyllos Afouras, Andrew Zisserman.* [[paper]](https://arxiv.org/abs/2103.16481) *code* `Tags:` **SLR**
- 【CVPR 2021】iMiGUE: An Identity-Free Video Dataset for Micro-Gesture Understanding and Emotion Analysis. *Xin Liu, Henglin Shi, Haoyu Chen, Zitong Yu, Xiaobai Li, Guoying Zhao.* [[paper]](https://openaccess.thecvf.com/content/CVPR2021/html/Liu_iMiGUE_An_Identity-Free_Video_Dataset_for_Micro-Gesture_Understanding_and_Emotion_CVPR_2021_paper.html) *code* `Tags:` **SLR**
- 【CVPR 2021】Body2Hands: Learning To Infer 3D Hands From Conversational Gesture Body Dynamics. *Evonne Ng, Shiry Ginosar, Trevor Darrell, Hanbyul Joo.* [[paper]](https://arxiv.org/abs/2007.12287) *code* `Tags:` **SLR**
- 【CVPR 2021】Model-Aware Gesture-to-Gesture Translation. *Hezhen Hu, Weilun Wang, Wengang Zhou, Weichao Zhao, Houqiang Li.* [[paper]](https://openaccess.thecvf.com/content/CVPR2021/html/Hu_Model-Aware_Gesture-to-Gesture_Translation_CVPR_2021_paper.html) *code* `Tags:` **SLR**
- 【AAAI 2021】Hand-Model-Aware Sign Language Recognition. *Hezhen Hu, Wengang Zhou, Houqiang Li.* [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/16247) *code* `Tags:` **SLR**
- 【AAAI 2021】Regional Attention with Architecture-Rebuilt 3D Network for RGB-D Gesture Recognition. *Benjia Zhou, Yunan Li, Jun Wan.* [[paper]](https://arxiv.org/pdf/2102.05348.pdf) *code* `Tags:` **SLR**
- 【WACV 2021】Hand Pose Guided 3D Pooling for Word-level Sign Language Recognition. *Al Amin Hosain; Panneer Selvam Santhalingam; Parth Pathak; Huzefa Rangwala; Jana Kosecka.* [[paper]](https://openaccess.thecvf.com/content/WACV2021/papers/Hosain_Hand_Pose_Guided_3D_Pooling_for_Word-Level_Sign_Language_Recognition_WACV_2021_paper.pdf) *code* `Tags:` **SLR**
- 【WACV 2021】Whose hand is this? Person Identification from Egocentric Hand Gestures. *Satoshi Tsutsui; Yanwei Fu; David Crandall.* [[paper]](https://arxiv.org/abs/2011.08900) *code* `Tags:` **SLR**

### 2020 <a name='sl_paper_2020'></a>
[[Back to TOP]](#table-of-content)

- 【ACMMM 2020】INCLUDE: A Large Scale Dataset for Indian Sign Language Recognition. *Sridhar, Advaith, Rohith Gandhi Ganesan, Pratyush Kumar, and Mitesh Khapra.* [[paper]](https://dl.acm.org/doi/abs/10.1145/3394171.3413528) *code* `Tags:` **SLR**
- 【ACMMM 2020】Boosting Continuous Sign Language Recognition via Cross Modality Augmentation. *Pu, Junfu, Wengang Zhou, Hezhen Hu, and Houqiang Li.* [[paper]](https://arxiv.org/pdf/2010.05264.pdf) *code* `Tags:` **SLR**
- 【ACMMM 2020】Recognizing Camera Wearer from Hand Gestures in Egocentric Videos. *Thapar, Daksh, Aditya Nigam, and Chetan Arora.* [[paper]](http://www.cse.iitd.ac.in/~chetan/papers/daksh-mm-2020.pdf) *code* `Tags:` **SLR**
- 【NeurIPS 2020】TSPNet: Hierarchical Feature Learning via Temporal Semantic Pyramid for Sign Language Translation. *Li, Dongxu, Chenchen Xu, Xin Yu, Kaihao Zhang, Benjamin Swift, Hanna Suominen, and Hongdong Li.* [[paper]](https://proceedings.neurips.cc/paper/2020/file/8c00dee24c9878fea090ed070b44f1ab-Paper.pdf) *code* `Tags:` **SLR**
- 【FG 2020】Feature Selection for Zero-Shot Gesture Recognition. *Naveen Madapana, Juan Wachs.* [[paper]](https://www.computer.org/csdl/proceedings-article/fg/2020/307900a309/1kecI8r1WXC) *code* `Tags:` **SLR**
- 【FG 2020】Image-Based Pose Representation for Action Recognition and Hand Gesture Recognition. *Zeyi Lin, Wei Zhang, Xiaoming Deng, Cuixia Ma, Hongan Wang.* [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9320255) *code* `Tags:` **SLR**
- 【FG 2020】Neural Sign Language Translation by Learning Tokenization. *Orbay, Alptekin, and Lale Akarun.* [[paper]](https://arxiv.org/pdf/2002.00479.pdf) *code* `Tags:` **SLT**
- 【FG 2020】Sign Language Recognition in Virtual Reality. *Jacob Schioppo, Zachary Meyer, Diego Fabiano, Shaun Canavan.* [[paper]](https://www.computer.org/csdl/proceedings-article/fg/2020/307900a185/1kecI0aXAje) *code* `Tags:` **SLR**
- 【FG 2020】SILFA: Sign Language Facial Action Database for the Development of Assistive Technologies for the Deaf. *Emely Puj��lli da Silva, Paula Dornhofer Paro Costa, Kate Mamhy Oliveira Kumada, Jos�� Mario De Martino.* [[paper]](https://www.computer.org/csdl/proceedings-article/fg/2020/307900a382/1kecIdR70Y0) *code* `Tags:` **Dataset**
- 【FG 2020】FineHand: Learning Hand Shapes for American Sign Language Recognition. *Al Amin Hosain, Panneer Selvam Santhalingam, Parth Pathak, Huzefa Rangwala, Jana Ko?eck��.* [[paper]](https://arxiv.org/pdf/2003.08753.pdf) *code* `Tags:` **SLR**
- 【FG 2020】Introduction and Analysis of an Event-Based Sign Language Dataset. *Ajay Vasudevan, Pablo Negri, Bernabe Linares-Barranco, Teresa Serrano-Gotarredona.* [[paper]](https://www.computer.org/csdl/proceedings-article/fg/2020/307900a441/1kecIyj5b0c) *code* `Tags:` **Dataset**
- 【FG 2020】Towards a Visual Sign Language Dataset for Home Care Services. *D. Kosmopoulos, I. Oikonomidis, C. Constantinopoulos, N. Arvanitis, K. Antzakas, A. Bifis, G. Lydakis, A. Roussos, A. Argyros.* [[paper]](https://www.computer.org/csdl/proceedings-article/fg/2020/307900a622/1kecIMIW1Bm) *code* `Tags:` **Dataset**
- 【ECCV 2020】BSL-1K: Scaling up co-articulated sign language recognition using mouthing cues. *Samuel Albanie, G��l Varol, Liliane Momeni, Triantafyllos Afouras, Joon Son Chung, Neil Fox, Andrew Zisserman.* [[paper]](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123560035.pdf) *code* `Tags:` **SLR**
- 【ECCV 2020】Progressive Transformers for End-to-End Sign Language Production. *Ben Saunders, Necati Cihan Camgoz, and Richard Bowden.* [[paper]](https://arxiv.org/pdf/2004.14874.pdf) [[code]](https://github.com/BenSaunders27/ProgressiveTransformersSLP) `Tags:` **SLP**
- 【ECCV 2020】Stochastic Fine-grained Labeling of Multi-state Sign Glosses for Continuous Sign Language Recognition. *Niu Zhe, Brian Mak.* [[paper]](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123610171.pdf) *code* `Tags:` **SLR**
- 【ECCV 2020】Fully Convolutional Networks for Continuous Sign Language Recognition. *Ka Leong Cheng, Zhaoyang Yang, Qifeng Chen, and Yu-Wing Tai.* [[paper]](https://arxiv.org/pdf/2007.12402v1.pdf) *code* `Tags:` **SLR**
- 【ECCV 2020】Collaborative Learning of Gesture Recognition and 3D Hand Pose Estimation with Multi-Order Feature Analysis. *Yang, Siyuan, Jun Liu, Shijian Lu, Meng Hwa Er, and Alex C. Kot.* [[paper]](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123480766.pdf) *code* `Tags:` **SLR**
- 【ECCV 2020】Style Transfer for Co-Speech Gesture Animation: A Multi-Speaker Conditional-Mixture Approach. *Chaitanya Ahuja, Dong Won Lee, Yukiko I. Nakano, and Louis-Philippe Morency.* [[paper]](https://arxiv.org/pdf/2007.12553.pdf) *code* `Tags:` **SLR**
- 【ECCV 2020】Towards Efficient Coarse-to-Fine Networks for Action and Gesture Recognition. *Quader, Niamul, Juwei Lu, Peng Dai, and Wei Li.* [[paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123750035.pdf) *code* `Tags:` **SLR**
- 【CVPR 2020】Decoupled Representation Learning for Skeleton-Based Gesture Recognition. *Jianbo Liu, Yongcheng Liu, Ying Wang, V��ronique Prinet, Shiming Xiang, Chunhong Pan.* [[paper]](http://openaccess.thecvf.com/content_CVPR_2020/papers/Liu_Decoupled_Representation_Learning_for_Skeleton-Based_Gesture_Recognition_CVPR_2020_paper.pdf) *code* `Tags:` **SLR**
- 【CVPR 2020】An Efficient PointLSTM for Point Clouds Based Gesture Recognition. *Yuecong Min, Yanxiao Zhang, Xiujuan Chai, Xilin Chen.* [[paper]](http://openaccess.thecvf.com/content_CVPR_2020/papers/Min_An_Efficient_PointLSTM_for_Point_Clouds_Based_Gesture_Recognition_CVPR_2020_paper.pdf) *code* `Tags:` **SLR**
- 【CVPR 2020】Transferring Cross-Domain Knowledge for Video Sign Language Recognition. *Dongxu Li, Xin Yu, Chenchen Xu, Lars Petersson, Hongdong Li.* [[paper]](https://arxiv.org/pdf/2003.03703.pdf) *code* `Tags:` **SLR**
- 【WACV 2020】Word-level Deep Sign Language Recognition from Video: A New Large-scale Dataset and Methods Comparison. *Dongxu Li, Cristian Rodriguez, Xin Yu, Hongdong Li.* [[paper]](http://openaccess.thecvf.com/content_WACV_2020/papers/Li_Word-level_Deep_Sign_Language_Recognition_from_Video_A_New_Large-scale_WACV_2020_paper.pdf) *code* `Tags:` **Dataset**
- 【WACV 2020】Neural Sign Language Synthesis: Words Are Our Glosses. *Jan Zelinka, Jakub Kanis.* [[paper]](http://openaccess.thecvf.com/content_WACV_2020/papers/Zelinka_Neural_Sign_Language_Synthesis_Words_Are_Our_Glosses_WACV_2020_paper.pdf) *code* `Tags:` **SLP**
- 【CIN 2020】Improved Sign Language Translation Model with Explainable Adaptations for Processing Long Sign Sentences. [[paper]](https://www.hindawi.com/journals/cin/2020/8816125/) *code* `Tags:` **SLT**
- 【arXiv 2020】Multi-channel Transformers for Multi-articulatory Sign Language Translation. [[paper]](https://arxiv.org/pdf/2009.00299.pdf) *code* `Tags:` **SLT**
- 【CVPR 2020】Sign Language Transformers: Joint End-to-end Sign Language Recognition and Translation. *Necati Cihan Camgoz, Oscar Koller, Simon Hadfield, and Richard Bowden.* [[paper]](https://arxiv.org/pdf/2003.13830.pdf) [[code]](https://github.com/neccam/slt) `Tags:` **SLT**
- 【arXiv 2020】Better Sign Language Translation with STMC-Transformer. *Kayo Yin, Jesse Read.* [[paper]](https://arxiv.org/pdf/2004.00588.pdf) [[code]](https://github.com/kayoyin/transformer-slt) `Tags:` **SLT**
- 【arXiv 2020】Neural Sign Language Translation by Learning Tokenization. *Alptekin Orbay and Lale Akarun.* [[paper]](https://arxiv.org/pdf/2002.00479.pdf) *code* `Tags:` **SLT**
- 【ECCV 2020】Stochastic Fine-grained Labeling of Multi-state Sign Glosses for Continuous Sign Language Recognition. [[paper]](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123610171.pdf) [[code]](https://github.com/zheniu/stochastic-cslr) `Tags:` **SLR**
- 【ECCV 2020】Fully Convolutional Networks for Continuous Sign Language Recognition. [[paper]](https://arxiv.org/pdf/2007.12402v1.pdf) *code* `Tags:` **SLR**
- 【AAAI 2020】Spatial-Temporal Multi-Cue Network for Continuous Sign Language Recognition. [[paper]](https://arxiv.org/pdf/2002.03187.pdf) *code* `Tags:` **SLR**
- 【ECCV 2020】BSL-1K: Scaling up co-articulated sign language recognition using mouthing cues. [[paper]](https://arxiv.org/pdf/2007.12131.pdf) *code* `Tags:` **SLR**
- 【WACV 2020】Word-level Deep Sign Language Recognition from Video: A New Large-scale Dataset and Methods Comparison. [[paper]](https://arxiv.org/pdf/1910.11006.pdf) [[code]](https://github.com/dxli94/WLASL) `Tags:` **SLR**
- 【IJCV 2020】Text2Sign: Towards Sign Language Production Using Neural Machine Translation and Generative Adversarial Networks. *Stephanie Stoll, Necati Cihan Camgoz, Simon Hadfield, Richard Bowden.* [[paper]](https://link.springer.com/content/pdf/10.1007%2Fs11263-019-01281-2.pdf) *code* `Tags:` **Text2Sign**
- 【ECCV 2020】Progressive Transformers for End-to-End Sign Language Production. [[paper]](https://arxiv.org/pdf/2004.14874.pdf) *code* `Tags:` **Text2Sign**
- 【TCSVT 2020】Semantic Boundary Detection with Reinforcement Learning for Continuous Sign Language Recognition. [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9106402) *code* `Tags:` **SLR**

### 2019 <a name='sl_paper_2019'></a>
[[Back to TOP]](#table-of-content)
- 【IEEE Access 2019 (`Recommended`)】Technical approaches to Chinese sign language processing: A review. *Suhail Muhammad Kamal; Yidong Chen; Shaozi Li; Xiaodong Shi; Jiangbin Zheng.* [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8764391) *code* `Tags:` **Survey**
- 【BigMM 2019】Deep Grammatical Multi-classifier for Continuous Sign Language Recognition. [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8919458) *code* `Tags:` **SLR**
- 【ICIP 2019】Continuous Sign Language Recognition via Reinforcement Learning. [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8802972) *code* `Tags:` **SLR**
- 【ICME 2019】Dynamic Pseudo Label Decoding for Continuous Sign Language Recognition. [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8784863) *code* `Tags:` **SLR**
- 【IJCAI 2019】Dense Temporal Convolution Network for Sign Language Translation. [[paper]](https://www.ijcai.org/Proceedings/2019/0105.pdf) *code* `Tags:` **SLR**
- 【IEEE TRANSACTIONS ON MULTIMEDIA 2019】A Deep Neural Framework for Continuous Sign
Language Recognition by Iterative Training. [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8598757&tag=1) *code* `Tags:` **SLR**
- 【CVPR 2019】Iterative Alignment Network for Continuous Sign Language. [[paper]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Pu_Iterative_Alignment_Network_for_Continuous_Sign_Language_Recognition_CVPR_2019_paper.pdf) *code* `Tags:` **SLR**
- 【TPAMI 2019】Weakly Supervised Learning with Multi-Stream CNN-LSTM-HMMs to Discover Sequential Parallelism in Sign Language Videos. [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8691602) [[code]](https://github.com/huerlima/Re-Sign-Re-Aligned-End-to-End-Sequence-Modelling-with-Deep-Recurrent-CNN-HMMs) `Tags:` **SLR**
- 【arXiv 2019】SF-Net: Structured Feature Network for Continuous Sign Language Recognition. [[paper]](https://arxiv.org/pdf/1908.01341.pdf) *code* `Tags:` **SLR**
- 【IEEE ACCESS 2019】Dynamic Sign Language Recognition Based on Video Sequence With BLSTM-3D Residual Networks. [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8667292) *code* `Tags:` **SLR**
- 【ICCV 2019】Temporal Accumulative Features for Sign Language Recognition. [[paper]](https://arxiv.org/pdf/2004.01225.pdf) *code* `Tags:` **SLR**
- 【ICCCM 2019】Thai Sign Language Recognition Using 3D Convolutional Neural Networks. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3348445.3348452?download=true) *code* `Tags:` **SLR**
- 【DSAA 2019】Sign Language Recognition Analysis using Multimodal Data. [[paper]](https://arxiv.org/pdf/1909.11232.pdf) *code* `Tags:` **SLR**
- 【ICANN 2019】Spatial-Temporal Graph Convolutional Networks for Sign Language Recognition. [[paper]](https://arxiv.org/pdf/1901.11164.pdf) [[code]](https://github.com/amorim-cleison/st-gcn-sl) `Tags:` **SLR**
- 【ICCV 2019】Fingerspelling recognition in the wild with iterative visual attention. [[paper]](https://arxiv.org/pdf/1908.10546.pdf) *code* `Tags:` **SLR**
- 【SITIS 2019】Translation of sign language glosses to text using sequence-to-sequence attention models. [[paper]](https://www.researchgate.net/publication/340689060_Translation_of_Sign_Language_Glosses_to_Text_Using_Sequence-to-Sequence_Attention_Models) *code* `Tags:` **Gloss2Text**

### 2018 <a name='sl_paper_2018'></a>
[[Back to TOP]](#table-of-content)
- 【TCSVT 2018】Attention based 3D-CNNs for Large-Vocabulary Sign Language Recognition. [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8466903) *code* `Tags:` **SLR**
- 【AAAI 2018】Video-based sign language recognition without temporal segmentation. [[paper]](https://arxiv.org/pdf/1801.10111.pdf) *code* `Tags:` **SLR**
- 【AAAI 2018】Hierarchical LSTM for Sign Language Translation. [[paper]](https://pdfs.semanticscholar.org/d44c/20c48e764a546d00b9155a56b171b0dc04bc.pdf) *code* `Tags:` **SLT**
- 【ACMMM 2018】Connectionist Temporal Fusion for Sign Language Translation. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3240508.3240671) *code* `Tags:` **SLT**
- 【arXiv 2018】Neural Sign Language Translation based on Human Keypoint Estimation. *Sang-Ki Ko, Chang Jo Kim, Hyedong Jung, Choongsang Cho.* [[paper]](https://arxiv.org/pdf/1811.11436.pdf) *code* `Tags:` **SLT**
- 【CVPR 2018】Neural Sign Language Translation. *Necati Cihan Camgoz, Simon Hadfield, Oscar Koller, Hermann Ney, Richard Bowden.* [[paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Camgoz_Neural_Sign_Language_CVPR_2018_paper.pdf) [[code]](https://github.com/neccam/nslt) `Tags:` **SLT**
- 【IJCAI 2018】Dilated Convolutional Network with Iterative Optimization for Continuous Sign Language Recognition. [[paper]](https://www.ijcai.org/Proceedings/2018/0123.pdf) [[code]](https://github.com/ustc-slr/DilatedSLR) `Tags:` **SLR**
- 【ETRI 2018】Human-like sign-language learning method using deep learning. [[paper]](https://onlinelibrary.wiley.com/doi/pdf/10.4218/etrij.2018-0066) *code* `Tags:` **SLR**
- 【IJCV 2018】Deep Sign: Enabling Robust Statistical Continuous Sign Language Recognition via Hybrid CNN-HMMs. [[paper]](https://dl.acm.org/doi/10.1007/s11263-018-1121-3) *code* `Tags:` **SLR**
- 【NIPS 2018】Attention in Convolutional LSTM for Gesture Recognition. [[paper]](http://papers.nips.cc/paper/7465-attention-in-convolutional-lstm-for-gesture-recognition.pdf) [[code]](https://github.com/GuangmingZhu/AttentionConvLSTM) `Tags:` **SLR**

### 2017 <a name='sl_paper_2017'></a>
[[Back to TOP]](#table-of-content)
- 【CVPR 2017】Re-Sign: Re-Aligned End-to-End Sequence Modelling with Deep Recurrent CNN-HMMs. [[paper]](https://www-i6.informatik.rwth-aachen.de/publications/download/1031/KollerOscarZargaranSepehrNeyHermann--Re-SignRe-AlignedEnd-to-EndSequenceModellingwithDeepRecurrentCNN-HMMs--2017.pdf) [[code]](https://github.com/huerlima/Re-Sign-Re-Aligned-End-to-End-Sequence-Modelling-with-Deep-Recurrent-CNN-HMMs) `Tags:` **SLR**
- 【CVPR 2017】Recurrent Convolutional Neural Networks for Continuous Sign Language Recognition by Staged Optimization. [[paper]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Cui_Recurrent_Convolutional_Neural_CVPR_2017_paper.pdf) *code* `Tags:` **SLR**
- 【TOMM 2017】Online Early-Late Fusion Based on Adaptive HMM for Sign Language Recognition*. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3152121?download=true) *code* `Tags:` **SLR**
- 【ICCV 2017】SubUNets: End-to-End Hand Shape and Continuous Sign Language Recognition. [[paper]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Camgoz_SubUNets_End-To-End_Hand_ICCV_2017_paper.pdf) [[code]](https://github.com/neccam/SubUNets) `Tags:` **SLR**
- 【ICCV 2017】Learning Spatiotemporal Features Using 3DCNN and Convolutional LSTM for Gesture Recognition. [[paper]](http://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w44/Zhang_Learning_Spatiotemporal_Features_ICCV_2017_paper.pdf) [[code]](https://github.com/GuangmingZhu/Conv3D_BICLSTM) `Tags:` **SLR**

### Earlier <a name='sl_paper_earlier'></a>
[[Back to TOP]](#table-of-content)
- 【ICME 2016】Chinese sign language recognition with adaptive HMM. [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7552950) *code* `Tags:` **SLR**
- 【PCM2016】Sign Language Recognition with Multi-modal Features. [[paper]](https://link.springer.com/chapter/10.1007/978-3-319-48896-7_25) *code* `Tags:` **SLR**
- 【ICME2015】Sign language recognition using 3D convolutional neural networks. [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7177428) *code* `Tags:` **SLR**
- 【ICIP 2016】Sign language recognition based on adaptive HMMS with data augmentation. [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7532885) *code* `Tags:` **SLR**
- 【Pattern Recognit.Lett.2016】Continuous sign language recognition using level building based on fast hidden Markov model. [[paper]](https://www.sciencedirect.com/science/article/pii/S0167865516300344?ref=pdf_download&fr=RR-2&rr=839e188bfdd51083) *code* `Tags:` **SLR**
- 【TACCESS 2016】Sign Transition Modeling and a Scalable Solution to Continuous Sign Language Recognition for Real-World Applications. [[paper]](https://dl.acm.org/doi/pdf/10.1145/2850421?download=true) *code* `Tags:` **SLR**
- 【ICPR 2016】Using Convolutional 3D Neural Networks for User-independent continuous gesture recognition. [[paper]](http://personal.ee.surrey.ac.uk/Personal/S.Hadfield/papers/camgoz2016icprw.pdf) *code* `Tags:` **SLR**
- 【CVPR 2016】Online Detection and Classification of Dynamic Hand Gestures with Recurrent 3D Convolutional Neural Networks. [[paper]](https://research.nvidia.com/sites/default/files/pubs/2016-06_Online-Detection-and/NVIDIA_R3DCNN_cvpr2016.pdf) *code* `Tags:` **SLR**
- 【CVPR 2016】Deep Hand: How to Train a CNN on 1 Million Hand Images When Your Data is Continuous and Weakly Labelled. [[paper]](https://www-i6.informatik.rwth-aachen.de/publications/download/1000/KollerOscarNeyHermannBowdenRichard--DeepHHowtoTrainaCNNon1MillionHImagesWhenYourDataIsContinuousWeaklyLabelled--2016.pdf) *code* `Tags:` **SLR**
- 【BMVC 2016】Deep Sign: Hybrid CNN-HMM for Continuous Sign Language Recognition. [[paper]](https://pdfs.semanticscholar.org/7b2f/db4a2f79a638ad6c5328cd2860b63fdfc100.pdf) *code* `Tags:` **SLR**
- 【ICIP 2016】Sign Language Recognition With Long Short-Term Memory. [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7532884) *code* `Tags:` **SLR**
- 【ECCV 2016】Iterative Reference Driven Metric Learning for Signer Independent Isolated Sign Language Recognition. [[paper]](http://vipl.ict.ac.cn/uploadfile/upload/2018112115134267.pdf) *code* `Tags:` **SLR**
- 【LREC 2016】Automatic Alignment of HamNoSys Subunits for Continuous Sign Language Recognition. [[paper]](https://pdfs.semanticscholar.org/f6a3/c3ab709eebc91f9639fe6d26b7736c3115b2.pdf?_ga=2.172107747.1969091582.1582720499-418088591.1578543327) *code* `Tags:` **SLR**
- 【CVPRW 2015】Hand Gesture Recognition with 3D Convolutional Neural Networks. [[paper]](https://www.cv-foundation.org/openaccess/content_cvpr_workshops_2015/W15/papers/Molchanov_Hand_Gesture_Recognition_2015_CVPR_paper.pdf) *code* `Tags:` **SLR**
- 【ICCVW 2015】Deep Learning of Mouth Shapes for Sign Language. [[paper]](https://dl.acm.org/doi/10.1109/ICCVW.2015.69) *code* `Tags:` **SLR**
- 【ICME 2015】Sign Language Recognition using 3D convolutional neural networks. [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7177428) *code* `Tags:` **SLR**
- 【ACCV 2014】Curve Matching from the View of Manifold for Sign Language Recognition. [[paper]](http://whdeng.cn/FSLCV14/pdffiles/w12-o7.pdf) *code* `Tags:` **SLR**
- 【ICIMCS 2014】A Threshold-based HMM-DTW Approach for Continuous Sign Language Recognition. [[paper]](https://dl.acm.org/doi/pdf/10.1145/2632856.2632931?download=true) *code* `Tags:` **SLR**
- 【ICTA 2013】English-ASL Gloss Parallel Corpus 2012: ASLG-PC12, The Second Release. [[paper]](https://www.researchgate.net/profile/Achraf_Othman/publication/227339312_English-ASL_Gloss_Parallel_Corpus_2012_ASLG-PC12/links/09e414fe0451f44d14000000.pdf) *code* `Tags:` **Dataset**
- 【SLPAT 2013】Improving Continuous Sign Language Recognition: Speech Recognition Techniques and System Design. [[paper]](https://pdfs.semanticscholar.org/91e4/220449ea1d7ed2b49c916dd89af850c69b26.pdf) *code* `Tags:` **SLR**
- 【IWSLT 2013】Using Viseme Recognition to Improve a Sign Language Translation System. [[paper]](https://pdfs.semanticscholar.org/e567/428f531e973a4544f1884d9d7e7aa59953a6.pdf?_ga=2.235954241.1969091582.1582720499-418088591.1578543327) *code* `Tags:` **SLR**
- 【AFGR 2013】Sign Language Recognition and Translation with Kinect. [[paper]](https://pdfs.semanticscholar.org/0450/ecef50fd1f532fe115c5d32c7c3ebed6fd80.pdf?_ga=2.205538387.1969091582.1582720499-418088591.1578543327) *code* `Tags:` **SLR**
- 【CVPR 2012】Sign Language Recognition using Sequential Pattern Trees. [[paper]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.261.3830&rep=rep1&type=pdf) *code* `Tags:` **SLR**
- 【JMLR 2012】Sign language recognition using sub-units. [[paper]](http://www.jmlr.org/papers/volume13/cooper12a/cooper12a.pdf) *code* `Tags:` **SLR**
- 【CVPRW 2011】Advances in phonetics-based sub-unit modeling for transcription alignment and sign language recognition. [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5981681&tag=1) *code* `Tags:` **SLR**
- 【Eng.Appl.Artif.Intell.2011】American Sign Language word recognition with a sensory glove using artificial neural networks. [[paper]](https://www.sciencedirect.com/science/article/pii/S0952197611001230?ref=pdf_download&fr=RR-2&rr=839e85f93d2504cc) *code* `Tags:` **SLR**
- 【INTERSPEECH 2007】Speech Recognition Techniques for a Sign Language Recognition System. [[paper]](https://www-i6.informatik.rwth-aachen.de/publications/download/154/DreuwPhilippeRybachDavidDeselaersThomasZahediMortezaNeyHermann--SpeechRecognitionTechniquesforaSignLanguageRecognitionSystem--2007.pdf) *code* `Tags:` **SLR**
- 【TSMC 2007】Large-Vocabulary Continuous Sign Language Recognition Based on Transition-Movement Models. [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4032919) *code* `Tags:` **SLR**
- 【TPAMI 1998】Real-time American sign language recognition using desk and wearable computer based video. [[paper]](http://luthuli.cs.uiuc.edu/~daf/courses/Signals%20AI/Papers/HMMs/00735811.pdf) *code* `Tags:` **SLR**



## AI Sign Language in Well-Known Institutions [Papers] <a name="sl_paper_institution"></a>

### XMU for AI Sign Language <a name='sl_paper_xmu'></a>
[[Back to TOP]](#table-of-content)

- 【ICASSP 2024】An Explicit Multi-Modal Fusion Method For Sign Language Translation. *Cong Hu, Biao Fu, Pei Yu, Liang Zhang, Xiaodong Shi, Yidong Chen.*
- 【AAAI 2024】Conditional Variational Autoencoder for Sign Language Translation with Cross-Modal Alignment. *Rui Zhao, Liang Zhang, Biao Fu, Cong Hu, Jinsong Su, Yidong Chen.*  [[code]](https://github.com/rzhao-zhsq/CV-SLT) `Tags:` **SLT**
- 【CVPR 2023 `(Highlight Paper)`】CVT-SLR: Contrastive Visual-Textual Transformation for Sign Language Recognition with Variational Alignment. *Jiangbin Zheng, Yile Wang, Cheng Tan, Siyuan Li, Ge Wang, Jun Xia, Yidong Chen, Stan Z. Li.* [[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Zheng_CVT-SLR_Contrastive_Visual-Textual_Transformation_for_Sign_Language_Recognition_With_Variational_CVPR_2023_paper.html) [[code]](https://github.com/binbinjiang/CVT-SLR) `Tags:` **SLR**; Westlake University & Zhejiang University & Xiamen University & Tsinghua University
- 【IJCAI 2023】Efficient Sign Language Translation with a Curriculum-based NAR Decoder. *Pei Yu, Liang Zhang, Biao Fu, Yidong Chen.* [[paper]](https://www.ijcai.org/proceedings/2023/0584.pdf) *code* `Tags:` **SLT**
- 【ICASSP 2023】A Token-level Contrastive Framework for Sign Language Translation. *Biao Fu, Peigen Ye, Liang Zhang, Pei Yu, Cong Hu, Yidong Chen, Xiaodong Shi.* [[paper]](https://arxiv.org/pdf/2204.04916.pdf) *code* `Tags:` **SLT**
- 【Arxiv 2022】Leveraging Graph-based Cross-modal Information Fusion for Neural Sign Language Translation. [[paper]](https://arxiv.org/pdf/2211.00526.pdf) *code* `Tags:` **SLT**
- 【Neurocomputing 2021】Enhancing neural sign language translation by highlighting the facial expression information. [[paper]](https://www.sciencedirect.com/science/article/abs/pii/S0925231221012698) *code* `Tags:` **SLT**
- 【CIN 2020】Improved Sign Language Translation Model with Explainable Adaptations for Processing Long Sign Sentences. [[paper]](https://www.hindawi.com/journals/cin/2020/8816125/) *code* `Tags:` **SLT**
- 【IEEE Access 2019 (`Recommended`)】Technical approaches to Chinese sign language processing: A review. *Suhail Muhammad Kamal; Yidong Chen; Shaozi Li; Xiaodong Shi; Jiangbin Zheng.* [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8764391) *code* `Tags:` **Survey**

### USTC for AI Sign Language <a name='sl_paper_ustc'></a>
[[Back to TOP]](#table-of-content)

- 【ACMMM 2020】Boosting Continuous Sign Language Recognition via Cross Modality Augmentation. *Pu, Junfu, Wengang Zhou, Hezhen Hu, and Houqiang Li.* [[paper]](https://arxiv.org/pdf/2010.05264.pdf) *code* `Tags:` **SLR**
- 【AAAI 2020】Spatial-Temporal Multi-Cue Network for Continuous Sign Language Recognition. [[paper]](https://arxiv.org/pdf/2002.03187.pdf) *code* `Tags:` **SLR**
- 【TCSVT 2020】Semantic Boundary Detection with Reinforcement Learning for Continuous Sign Language Recognition. [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9106402) *code* `Tags:` **SLR**
- 【BigMM 2019】Deep Grammatical Multi-classifier for Continuous Sign Language Recognition. [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8919458) *code* `Tags:` **SLR**
- 【IJCAI 2019】Dense Temporal Convolution Network for Sign Language Translation. [[paper]](https://www.ijcai.org/Proceedings/2019/0105.pdf) *code* `Tags:` **SLR**
- 【IEEE TRANSACTIONS ON MULTIMEDIA 2019】A Deep Neural Framework for Continuous Sign Language Recognition by Iterative Training. [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8598757&tag=1) *code* `Tags:` **SLR**
- 【CVPR 2019】Iterative Alignment Network for Continuous Sign Language. [[paper]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Pu_Iterative_Alignment_Network_for_Continuous_Sign_Language_Recognition_CVPR_2019_paper.pdf) *code* `Tags:` **SLR**
- 【AAAI 2018】Video-based sign language recognition without temporal segmentation. [[paper]](https://arxiv.org/pdf/1801.10111.pdf) *code* `Tags:` **SLR**
- 【AAAI 2018】Hierarchical LSTM for Sign Language Translation. [[paper]](https://pdfs.semanticscholar.org/d44c/20c48e764a546d00b9155a56b171b0dc04bc.pdf) *code* `Tags:` **SLT**
- 【ACMMM 2018】Connectionist Temporal Fusion for Sign Language Translation. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3240508.3240671) *code* `Tags:` **SLT**
- 【IJCAI 2018】Dilated Convolutional Network with Iterative Optimization for Continuous Sign Language Recognition. [[paper]](https://www.ijcai.org/Proceedings/2018/0123.pdf) [[code]](https://github.com/ustc-slr/DilatedSLR) `Tags:` **SLR**
- 【ICME 2016】Chinese sign language recognition with adaptive HMM. [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7552950) *code* `Tags:` **SLR**
- 【PCM2016】Sign Language Recognition with Multi-modal Features. [[paper]](https://link.springer.com/chapter/10.1007/978-3-319-48896-7_25) *code* `Tags:` **SLR**
- 【ICME2015】Sign language recognition using 3D convolutional neural networks. [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7177428) *code* `Tags:` **SLR**
- 【ICIP 2016】Sign language recognition based on adaptive HMMS with data augmentation. [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7532885) *code* `Tags:` **SLR**
- 【ICIP 2016】Sign Language Recognition With Long Short-Term Memory. [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7532884) *code* `Tags:` **SLR**

### ZJU for AI Sign Language <a name='sl_paper_zju'></a>
[[Back to TOP]](#table-of-content)
- 【CVPR 2023 `(Highlight Paper)`】CVT-SLR: Contrastive Visual-Textual Transformation for Sign Language Recognition with Variational Alignment. *Jiangbin Zheng, Yile Wang, Cheng Tan, Siyuan Li, Ge Wang, Jun Xia, Yidong Chen, Stan Z. Li.* [[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Zheng_CVT-SLR_Contrastive_Visual-Textual_Transformation_for_Sign_Language_Recognition_With_Variational_CVPR_2023_paper.html) [[code]](https://github.com/binbinjiang/CVT-SLR) `Tags:` **SLR**; Westlake University & Zhejiang University & Xiamen University & Tsinghua University

### THU for AI Sign Language <a name='sl_paper_thu'></a>
[[Back to TOP]](#table-of-content)

- 【CVPR 2023 `(Highlight Paper)`】CVT-SLR: Contrastive Visual-Textual Transformation for Sign Language Recognition with Variational Alignment. *Jiangbin Zheng, Yile Wang, Cheng Tan, Siyuan Li, Ge Wang, Jun Xia, Yidong Chen, Stan Z. Li.* [[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Zheng_CVT-SLR_Contrastive_Visual-Textual_Transformation_for_Sign_Language_Recognition_With_Variational_CVPR_2023_paper.html) [[code]](https://github.com/binbinjiang/CVT-SLR) `Tags:` **SLR**; Westlake University & Zhejiang University & Xiamen University & Tsinghua University
- 【CVPR 2022】A Simple Multi-Modality Transfer Learning Baseline for Sign Language Translation. *Yutong Chen, Fangyun Wei, Xiao Sun, Zhirong Wu, Stephen Lin.* [[paper]](https://arxiv.org/abs/2203.04287) *code* `Tags:` **SLT**

### Germany-UK for AI Sign Language <a name='sl_paper_germany-uk'></a>
[[Back to TOP]](#table-of-content)
- 【arXiv 2020】Multi-channel Transformers for Multi-articulatory Sign Language Translation. [[paper]](https://arxiv.org/pdf/2009.00299.pdf) *code* `Tags:` **SLT**
- 【CVPR 2020】Sign Language Transformers: Joint End-to-end Sign Language Recognition and Translation. *Necati Cihan Camgoz, Oscar Koller, Simon Hadfield, and Richard Bowden.* [[paper]](https://arxiv.org/pdf/2003.13830.pdf) [[code]](https://github.com/neccam/slt) `Tags:` **SLT**
- 【TPAMI 2019】Weakly Supervised Learning with Multi-Stream CNN-LSTM-HMMs to Discover Sequential Parallelism in Sign Language Videos. [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8691602) [[code]](https://github.com/huerlima/Re-Sign-Re-Aligned-End-to-End-Sequence-Modelling-with-Deep-Recurrent-CNN-HMMs) `Tags:` **SLR**
- 【CVPR 2018】Neural Sign Language Translation. *Necati Cihan Camgoz, Simon Hadfield, Oscar Koller, Hermann Ney, Richard Bowden.* [[paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Camgoz_Neural_Sign_Language_CVPR_2018_paper.pdf) [[code]](https://github.com/neccam/nslt) `Tags:` **SLT**
- 【CVPR 2017】Re-Sign: Re-Aligned End-to-End Sequence Modelling with Deep Recurrent CNN-HMMs. [[paper]](https://www-i6.informatik.rwth-aachen.de/publications/download/1031/KollerOscarZargaranSepehrNeyHermann--Re-SignRe-AlignedEnd-to-EndSequenceModellingwithDeepRecurrentCNN-HMMs--2017.pdf) [[code]](https://github.com/huerlima/Re-Sign-Re-Aligned-End-to-End-Sequence-Modelling-with-Deep-Recurrent-CNN-HMMs) `Tags:` **SLR**
- 【ICCV 2017】SubUNets: End-to-End Hand Shape and Continuous Sign Language Recognition. [[paper]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Camgoz_SubUNets_End-To-End_Hand_ICCV_2017_paper.pdf) [[code]](https://github.com/neccam/SubUNets) `Tags:` **SLR**




## Datasets <a name="datasets"></a>
[[Back to TOP]](#table-of-content)

| Dataset                                                      | Language    | Classes | Samples | Data Type                    | Language Level |
| ------------------------------------------------------------ | ----------- | ------- | ------- | ---------------------------- | :------------- |
| **[ASLG-PC12](https://github.com/kayoyin/transformer-slt/tree/master/data)[paper](https://arxiv.org/pdf/2004.00588.pdf)** | American     | -     | 87,709 | GLOSS&Sentences     | isolated       |
| **[CSL Dataset I](http://home.ustc.edu.cn/~pjh/openresources/cslr-dataset-2015/index.html)** | Chinese     | 500     | 125,000 | Videos&Depth from Kinect     | isolated       |
| **[CSL Dataset II](http://home.ustc.edu.cn/~pjh/openresources/cslr-dataset-2015/index.html)** | Chinese     | 100     | 25,000  | Videos&Depth from Kinect     | continuous     |
| **[RWTH-PHOENIX-Weather 2014](https://www-i6.informatik.rwth-aachen.de/~koller/RWTH-PHOENIX/)** | German      | 1,081   | 6,841   | Videos                       | continuous     |
| [**RWTH-PHOENIX-Weather 2014 T**](https://www-i6.informatik.rwth-aachen.de/~koller/RWTH-PHOENIX-2014-T/) | German      | 1,066   | 8,257   | Videos                       | continuous     |
| **[ASLLVD](http://www.bu.edu/asllrp/av/dai-asllvd.html)**    | American    | 3,300   | 9,800   | Videos(multiple angles)      | isolated       |
| **[ASLLVD-Skeleton](https://www.cin.ufpe.br/~cca5/asllvd-skeleton/)** | American    | 3,300   | 9,800   | Skeleton                     | isolated       |
| **[SIGNUM](https://www.phonetik.uni-muenchen.de/forschung/Bas/SIGNUM/)** | German      | 450     | 33,210  | Videos                       | continuous     |
| [**DGS Kinect 40**](http://personal.ee.surrey.ac.uk/Personal/H.Cooper/research/papers/Ong_Sign_2012.pdf) | German      | 40      | 3,000   | Videos(multiple angles)      | isolated       |
| [**DEVISIGN-G**](http://vipl.ict.ac.cn/homepage/ksl/data.html) | Chinese     | 36      | 432     | Videos                       | isolated       |
| [**DEVISIGN-D**](http://vipl.ict.ac.cn/homepage/ksl/data.html) | Chinese     | 500     | 6,000   | Videos                       | isolated       |
| [**DEVISIGN-L**](http://vipl.ict.ac.cn/homepage/ksl/data.html) | Chinese     | 2000    | 24,000  | Videos                       | isolated       |
| [**LSA64**](http://facundoq.github.io/unlp/lsa64/)           | Argentinian | 64      | 3,200   | Videos                       | isolated       |
| [**GSL isol.**](https://vcl.iti.gr/dataset/gsl/)             | Greek       | 310     | 40,785  | Videos&Depth from RealSense  | isolated       |
| [**GSL SD**](https://vcl.iti.gr/dataset/gsl/)                | Greek       | 310     | 10,290  | Videos&Depth from RealSense  | continuous     |
| [**GSL SI**](https://vcl.iti.gr/dataset/gsl/)                | Greek       | 310     | 10,290  | Videos&Depth from RealSense  | continuous     |
| [**IIITA -ROBITA**](https://robita.iiita.ac.in/dataset.php)  | Indian      | 23      | 605     | Videos                       | isolated       |
| [**PSL Kinect**](http://vision.kia.prz.edu.pl/dynamickinect.php) | Polish      | 30      | 300     | Videos&Depth from Kinect     | isolated       |
| [**PSL ToF**](http://vision.kia.prz.edu.pl/dynamictof.php)   | Polish      | 84      | 1,680   | Videos&Depth from ToF camera | isolated       |
| [**BUHMAP-DB**](https://www.cmpe.boun.edu.tr/pilab/pilabfiles/databases/buhmap/) | Turkish     | 8       | 440     | Videos                       | isolated       |
| [**LSE-Sign**](http://lse-sign.bcbl.eu/web-busqueda/)        | Spanish     | 2,400   | 2,400   | Videos                       | isolated       |
| [**Purdue RVL-SLLL**](https://engineering.purdue.edu/RVL/Database/ASL/asl-database-front.htm) | American    | 39      | 546     | Videos                       | isolated       |
| [**RWTH-BOSTON-50**](http://www-i6.informatik.rwth-aachen.de/aslr/database-rwth-boston-50.php) | American    | 50      | 483     | Videos(multiple angles)      | isolated       |
| [**RWTH-BOSTON-104**](http://www-i6.informatik.rwth-aachen.de/aslr/database-rwth-boston-104.php) | American    | 104     | 201     | Videos(multiple angles)      | continuous     |
| [**RWTH-BOSTON-400**](http://www-i6.informatik.rwth-aachen.de/~dreuw/database.php) | American    | 400     | 843     | Videos                       | continuous     |
| [**WLASL**](https://dxli94.github.io/WLASL/)                 | American    | 2,000   | 21,083  | Videos                       | isolated       |



## AI Sign Language Related Fields <a name="related_fields"></a>
[[Back to TOP]](#table-of-content)

The related fields, such as `Large Pretrained Language Model`,`Corss-modal/Multi-modality`, `Action Recognition`, `Machine Translation`, `Speech Recognition`, `Video Captioning`, can help you gain more inspiration and knowledge