<a name="top"></a>
# Overview

This is a curated list of audio-visual learning methods and datasets, based on our survey: <Learning in Audio-visual Context: A Review, Analysis, and New Perspective>. This list will continue to be updated, please feel free to nominate good related works with Pull Requests!

[[Website of Our Survey]](https://gewu-lab.github.io/audio-visual-learning), [[arXiv]](https://arxiv.org/abs/2208.09579)

# Table of contents

- [Overview](#overview)
- [Table of contents](#table-of-contents)
  - [Audio-visual Boosting](#audio-visual-boosting)
    - [Audio-visual Recognition](#audio-visual-recognition)
      - [Speech Recognition](#speech-recognition)
      - [Speaker Recognition](#speaker-recognition)
      - [Action Recognition](#action-recognition)
      - [Emotion Recognition](#emotion-recognition)
    - [Uni-modal Enhancement](#uni-modal-enhancement)
      - [Speech Enhancement and Separation](#speech-enhancement-and-separation)
      - [Object Sound Separation](#object-sound-separation)
      - [Face Super-resolution and Reconstruction](#face-super-resolution-and-reconstruction)
  - [Cross-modal Perception](#cross-modal-perception)
    - [Cross-modal Generation](#cross-modal-generation)
      - [Mono Sound Generation](#mono-sound-generation)
        - [Speech](#speech)
        - [Music](#music)
        - [Natural Sound](#natural-sound)
      - [Spatial Sound Generation](#spatial-sound-generation)
      - [Video Generation](#video-generation)
        - [talking face](#talking-face)
      - [Gesture](#gesture)
        - [Dance](#dance)
      - [Image Manipulation](#image-manipulation)
      - [Depth Estimation](#depth-estimation)
    - [Audio-visual Transfer Learning](#audio-visual-transfer-learning)
    - [Cross-modal Retrieval](#cross-modal-retrieval)
  - [Audio-visual Collaboration](#audio-visual-collaboration)
    - [Audio-visual Representation Learning](#audio-visual-representation-learning)
    - [Audio-visual Localization](#audio-visual-localization)
      - [Sound Localization in Videos](#sound-localization-in-videos)
      - [Audio-visual Saliency Detection](#audio-visual-saliency-detection)
      - [Audio-visual Navigation](#audio-visual-navigation)
    - [Audio-visual Event Localization and Parsing](#audio-visual-event-localization-and-parsing)
      - [Localization](#localization)
      - [Parsing](#parsing)
    - [Audio-visual Question Answering and Dialog](#audio-visual-question-answering-and-dialog)
      - [Question Answering](#question-answering)
      - [Dialog](#dialog)
  - [Datasets](#datasets)




## Audio-visual Boosting

### Audio-visual Recognition

#### Speech Recognition
**[Applied Intelligence-2015]**
[Audio-visual Speech Recognition Using Deep Learning](https://link.springer.com/article/10.1007/s10489-014-0629-7)
<br>
**Authors:** Kuniaki Noda, Yuki Yamaguchi, Kazuhiro Nakadai, Hiroshi G. Okuno, Tetsuya Ogata 
<br>
**Institution:** Waseda University; Kyoto University; Honda Research Institute Japan Co., Ltd.

**[CVPR-2016]**
[Temporal Multimodal Learning in Audiovisual Speech Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/Hu_Temporal_Multimodal_Learning_CVPR_2016_paper.pdf)
<br>
**Authors:** Di Hu, Xuelong Li, Xiaoqiang Lu
<br>
**Institution:** Northwestern Polytechnical University; Chinese Academy of Sciences

**[AVSP-2017]**
[End-To-End Audiovisual Fusion With LSTMs](https://arxiv.org/abs/1709.04343)
<br>
**Authors:** Stavros Petridis, Yujiang Wang, Zuwei Li, Maja Pantic
<br>
**Institution:** Imperial College London; University of Twente

**[IEEE TPAMI-2018]**
[Deep Audio-visual Speech Recognition](https://ieeexplore.ieee.org/abstract/document/8585066)
<br>
**Authors:** Triantafyllos Afouras, Joon Son Chung, Andrew Senior, Oriol Vinyals, Andrew Zisserman
<br>
**Institution:** University of Oxford; Google Inc.

**[2019]**
[Explicit Sparse Transformer: Concentrated Attention Through Explicit Selection](https://arxiv.org/abs/1912.11637)
<br>
**Authors:** Guangxiang Zhao, Junyang Lin, Zhiyuan Zhang, Xuancheng Ren, Qi Su, Xu Sun
<br>
**Institution:** Peking University

**[IEEE TNNLS-2022]**
[Multimodal Sparse Transformer Network for Audio-visual Speech Recognition](https://ieeexplore.ieee.org/abstract/document/9755926)
<br>
**Authors:** Qiya Song, Bin Sun, Shutao Li
<br>
**Institution:** Hunan University

**[Interspeech-2022]**
[Robust Self-Supervised Audio-visual Speech Recognition](https://arxiv.org/abs/2201.01763)
<br>
**Authors:** Bowen Shi, Wei-Ning Hsu, Abdelrahman Mohamed
<br>
**Institution:** Toyota Technological Institute at Chicago; Meta AI

**[2022]**
[Bayesian Neural Network Language Modeling for Speech Recognition](https://arxiv.org/abs/2208.13259)
<br>
**Authors:** Boyang Xue, Shoukang Hu, Junhao Xu, Mengzhe Geng, Xunying Liu, Helen Meng
<br>
**Institution:** the Chinese University of Hong Kong

**[Interspeech-2022]**
[Visual Context-driven Audio Feature Enhancement for Robust End-to-End Audio-Visual Speech Recognition](https://arxiv.org/abs/2207.06020)
<br>
**Authors:** Joanna Hong, Minsu Kim, Daehun Yoo, Yong Man Ro
<br>
**Institution:** Korea Advanced Institute of Science and Technology; Genesis Lab Inc.

**[MLSP-2022]**
[Rethinking Audio-visual Synchronization for Active Speaker Detection](https://arxiv.org/abs/2206.10421)
<br>
**Authors:** Abudukelimu Wuerkaixi, You Zhang, Zhiyao Duan, Changshui Zhang
<br>
**Institution:** Tsinghua University; Beijing National Research Center for Information Science and Technology; University of Rochester

**[NeurIPS-2022]**
[A Single Self-Supervised Model for Many Speech Modalities Enables Zero-Shot Modality Transfer](https://arxiv.org/pdf/2207.07036.pdf)
<br>
**Authors:** Wei-Ning Hsu, Bowen Shi
<br>
**Institution:** Toyota Technological Institute at Chicago

**[ITOEC-2022]**
[FSMS: An Enhanced Polynomial Sampling Fusion Method for Audio-Visual Speech Recognition](https://ieeexplore.ieee.org/document/9734622)
<br>
**Authors:** Chenghan Li; Yuxin Zhang; Huaichang Du
<br>
**Institution:** Communication University of China

**[IJCNN-2022]**
[Continuous Phoneme Recognition based on Audio-Visual Modality Fusion](https://ieeexplore.ieee.org/document/9892053)
<br>
**Authors:** Julius Richter; Jeanine Liebold; Timo Gerkamnn
<br>
**Institution:** Universität Hamburg

**[ICIP-2022]**
[Learning Contextually Fused Audio-Visual Representations For Audio-Visual Speech Recognition](https://ieeexplore.ieee.org/document/9897235/)
<br>
**Authors:** Zi-Qiang Zhang, Jie Zhang, Jian-Shu Zhang, Ming-Hui Wu, Xin Fang, Li-Rong Dai
<br>
**Institution:** University of Science and Technology of China; Chinese Academy of Sciences; iFLYTEK Co., Ltd.

**[ICASSP-2023]**
[Self-Supervised Audio-Visual Speech Representations Learning By Multimodal Self-Distillation](https://arxiv.org/abs/2212.02782)
<br>
**Authors:** Jing-Xuan Zhang, Genshun Wan, Zhen-Hua Ling, Jia Pan, Jianqing Gao, Cong Liu
<br>
**Institution:** University of Science and Technology of China; iFLYTEK Co. Ltd.

**[CVPR-2022]**
[Improving Multimodal Speech Recognition by Data Augmentation and Speech Representations](https://arxiv.org/abs/2204.13206)
<br>
**Authors:** Dan Oneaţă, Horia Cucu
<br>
**Institution:** University POLITEHNICA of Bucharest

**[AAAI-2022]**
[Distinguishing Homophenes Using Multi-Head Visual-Audio Memory for Lip Reading](https://arxiv.org/abs/2204.01725)
<br>
**Authors:** Minsu Kim, Jeong Hun Yeo, Yong Man Ro
<br>
**Institution:** Korea Advanced Institute of Science and Technology

**[AAAI-2023]**
[Leveraging Modality-specific Representations for Audio-visual Speech Recognition via Reinforcement Learning](https://arxiv.org/abs/2212.05301)
<br>
**Authors:** Chen Chen, Yuchen Hu, Qiang Zhang, Heqing Zou, Beier Zhu, Eng Siong Chng
<br>
**Institution:** Nanyang Technological University; ZJU-Hangzhou Global Scientific and Technological Innovation Center; Zhejiang University

**[WACV-2023]**
[Audio-Visual Efficient Conformer for Robust Speech Recognition](https://ieeexplore.ieee.org/document/10030963)
<br>
**Authors:** Maxime Burchi, Radu Timofte
<br>
**Institution:** University of Würzburg

**[2023]**
[Prompt Tuning of Deep Neural Networks for Speaker-adaptive Visual Speech Recognition](https://arxiv.org/abs/2302.08102)
<br>
**Authors:** Minsu Kim, Hyung-Il Kim, Yong Man Ro
<br>
**Institution:** Korea Advanced Institute of Science and Technology; Electronics and Telecommunications Research Institute

**[2023]**
[Multimodal Speech Recognition for Language-Guided Embodied Agents](https://arxiv.org/abs/2302.14030)
<br>
**Authors:** Allen Chang, Xiaoyuan Zhu, Aarav Monga, Seoho Ahn, Tejas Srinivasan, Jesse Thomason
<br>
**Institution:** University of Southern California

**[2023]**
[MuAViC: A Multilingual Audio-Visual Corpus for Robust Speech Recognition and Robust Speech-to-Text Translation](https://arxiv.org/abs/2303.00628)
<br>
**Authors:** Mohamed Anwar, Bowen Shi, Vedanuj Goswami, Wei-Ning Hsu, Juan Pino, Changhan Wang
<br>
**Institution:** Meta AI

**[ICASSP-2023]**
[The NPU-ASLP System for Audio-Visual Speech Recognition in MISP 2022 Challenge](https://arxiv.org/abs/2303.06341)
<br>
**Authors:** Pengcheng Guo, He Wang, Bingshen Mu, Ao Zhang, Peikun Chen
<br>
**Institution:** Northwestern Polytechnical University

**[CVPR-2023]**
[Watch or Listen: Robust Audio-Visual Speech Recognition with Visual Corruption Modeling and Reliability Scoring](https://arxiv.org/abs/2303.08536)
<br>
**Authors:** Joanna Hong, Minsu Kim, Jeongsoo Choi, Yong Man Ro
<br>
**Institution:** Korea Advanced Institute of Science and Technology

**[ICASSP-2023]**
[Auto-AVSR: Audio-Visual Speech Recognition with Automatic Labels](https://arxiv.org/abs/2303.14307)
<br>
**Authors:** Pingchuan Ma, Alexandros Haliassos, Adriana Fernandez-Lopez, Honglie Chen, Stavros Petridis, Maja Pantic
<br>
**Institution:** Imperial College London; Meta AI

**[CVPR-2023]**
[AVFormer: Injecting Vision into Frozen Speech Models for Zero-Shot AV-ASR](https://arxiv.org/abs/2303.16501)
<br>
**Authors:** Paul Hongsuck Seo, Arsha Nagrani, Cordelia Schmid
<br>
**Institution:** Google Research

**[CVPR-2023]**
[SynthVSR: Scaling Up Visual Speech Recognition With Synthetic Supervision](https://arxiv.org/abs/2303.17200)
<br>
**Authors:** Xubo Liu, Egor Lakomkin, Konstantinos Vougioukas, Pingchuan Ma, Honglie Chen, Ruiming Xie, Morrie Doulaty, Niko Moritz, Jáchym Kolář, Stavros Petridis, Maja Pantic, Christian Fuegen
<br>
**Institution:** University of Surrey; Meta AI

**[ICASSP-2023]**
[Multi-Temporal Lip-Audio Memory for Visual Speech Recognition](https://ieeexplore.ieee.org/document/10094693)
<br>
**Authors:** Jeong Hun Yeo, Minsu Kim, Yong Man Ro
<br>
**Institution:** Korea Advanced Institute of Science and Technology

**[ICASSP-2023]**
[On the Role of LIP Articulation in Visual Speech Perception](https://ieeexplore.ieee.org/document/10096012)
<br>
**Authors:** Zakaria Aldeneh, Masha Fedzechkina, Skyler Seto, Katherine Metcalf, Miguel Sarabia, Nicholas Apostoloff, Barry-John Theobald
<br>
**Institution:** Apple Inc.

**[ICASSP-2023]**
[Practice of the Conformer Enhanced Audio-Visual Hubert on Mandarin and English](https://ieeexplore.ieee.org/document/10094579/)
<br>
**Authors:** Xiaoming Ren, Chao Li, Shenjian Wang, Biao Li
<br>
**Institution:** Beijing OPPO Telecommunications Corp., ltd.

**[ICASSP-2023]**
[Robust Audio-Visual ASR with Unified Cross-Modal Attention](https://ieeexplore.ieee.org/document/10096893/)
<br>
**Authors:** Jiahong Li, Chenda Li, Yifei Wu, Yanmin Qian
<br>
**Institution:** Shanghai Jiao Tong University

**[IJCAI-2023]**
[Cross-Modal Global Interaction and Local Alignment for Audio-Visual Speech Recognition](https://arxiv.org/abs/2305.09212)
<br>
**Authors:** Yuchen Hu, Ruizhe Li, Chen Chen, Heqing Zou, Qiushi Zhu, Eng Siong Chng
<br>
**Institution:** Nanyang Technological University; University of Aberdeen; University of Science and Technology of China

**[Interspeech-2023]**
[Prompting the Hidden Talent of Web-Scale Speech Models for Zero-Shot Task Generalization](https://arxiv.org/abs/2305.11095)
<br>
**Authors:** Puyuan Peng, Brian Yan, Shinji Watanabe, David Harwath
<br>
**Institution:** The University of Texas at Austin; Carnegie Mellon University

**[Interspeech-2023]**
[Improving the Gap in Visual Speech Recognition Between Normal and Silent Speech Based on Metric Learning](https://arxiv.org/abs/2305.14203)
<br>
**Authors:** Sara Kashiwagi, Keitaro Tanaka, Qi Feng, Shigeo Morishima
<br>
**Institution:** Waseda University; Waseda Research Institute for Science and Engineering

**[ACL-2023]**
[AV-TranSpeech: Audio-Visual Robust Speech-to-Speech Translation](https://arxiv.org/abs/2305.15403)
<br>
**Authors:** Rongjie Huang, Huadai Liu, Xize Cheng, Yi Ren, Linjun Li, Zhenhui Ye, Jinzheng He, Lichao Zhang, Jinglin Liu, Xiang Yin, Zhou Zhao
<br>
**Institution:** Zhejiang University; ByteDance

**[ACL-2023]**
[Hearing Lips in Noise: Universal Viseme-Phoneme Mapping and Transfer for Robust Audio-Visual Speech Recognition](https://arxiv.org/abs/2306.10563)
<br>
**Authors:** Yuchen Hu, Ruizhe Li, Chen Chen, Chengwei Qin, Qiushi Zhu, Eng Siong Chng
<br>
**Institution:** Nanyang Technological University; University of Aberdeen; University of Science and Technology of China

**[ACL-2023]**
[MIR-GAN: Refining Frame-Level Modality-Invariant Representations with Adversarial Network for Audio-Visual Speech Recognition](https://arxiv.org/abs/2306.10567)
<br>
**Authors:** Yuchen Hu, Chen Chen, Ruizhe Li, Heqing Zou, Eng Siong Chng
<br>
**Institution:** Nanyang Technological University; University of Aberdeen

**[IJCNN-2023]**
[Exploiting Deep Learning for Sentence-Level Lipreading](https://ieeexplore.ieee.org/document/10191888)
<br>
**Authors:** Isabella Wu, Xin Wang
<br>
**Institution:** Choate Rosemary Hall; Stony Brook University

**[IJCNN-2023]**
[GLSI Texture Descriptor Based on Complex Networks for Music Genre Classification](https://ieeexplore.ieee.org/document/10191818)
<br>
**Authors:** Andrés Eduardo, Coca Salazar
<br>
**Institution:** Federal University of Technology - Paraná

**[ICME-2023]**
[Improving Audio-Visual Speech Recognition by Lip-Subword Correlation Based Visual Pre-training and Cross-Modal Fusion Encoder](https://arxiv.org/abs/2308.08488)
<br>
**Authors:** Yusheng Dai, Hang Chen, Jun Du, Xiaofei Ding, Ning Ding, Feijun Jiang, Chin-Hui Lee
<br>
**Institution:** University of Science and Technology of China; Alibaba Group; Georgia Institute of Technology

**[ICME-2023]**
[Multi-Scale Hybrid Fusion Network for Mandarin Audio-Visual Speech Recognition](https://ieeexplore.ieee.org/document/10219999)
<br>
**Authors:** Jinxin Wang, Zhongwen Guo, Chao Yang, Xiaomei Li, Ziyuan Cui
<br>
**Institution:** Ocean University of China; University of Technology Sydney

**[AAAI-2024]**
[Multichannel AV-wav2vec2: A Framework for Learning Multichannel Multi-Modal Speech Representation](https://arxiv.org/abs/2401.03468)
<br>
**Authors:** Qiushi Zhu, Jie Zhang, Yu Gu, Yuchen Hu, Lirong Dai
<br>
**Institution:** NERC-SLIP, University of Science and Technology of China (USTC), Hefei, China; Tencent AI LAB; Nanyang Technological University, Singapore

**[CVPR-2024]**
[A Study of Dropout-Induced Modality Bias on Robustness to Missing Video Frames for Audio-Visual Speech Recognition](https://arxiv.org/abs/2403.04245)
<br>
**Authors:** Yusheng Dai, Hang Chen, Jun Du, Ruoyu Wang, Shihao Chen, Jiefeng Ma, Haotian Wang, Chin-Hui Lee
<br>
**Institution:** University of Science and Technology of China, Hefei, China; Georgia Institute of Technology, Atlanta, America

**[IJCNN-2024]**
[Target Speech Extraction with Pre-trained AV-HuBERT and Mask-And-Recover Strategy](https://arxiv.org/abs/2403.16078)
<br>
**Authors:** Wenxuan Wu, Xueyuan Chen, Xixin Wu, Haizhou Li, Helen Meng
<br>
**Institution:**  The Chinese University of Hong Kong

#### Speaker Recognition

**[MTA-2016]**
[Audio-visual Speaker Diarization Using Fisher Linear Semi-discriminant Analysis](https://link.springer.com/article/10.1007/s11042-014-2274-x)
<br>
**Authors:** Nikolaos Sarafianos, Theodoros Giannakopoulos, Sergios Petridis
<br>
**Institution:** National Center for Scientific Research “Demokritos”

**[ICASSP-2018]**
[Audio-visual Person Recognition in Multimedia Data From the Iarpa Janus Program](https://ieeexplore.ieee.org/abstract/document/8462122)
<br>
**Authors:** Gregory Sell, Kevin Duh, David Snyder, Dave Etter, Daniel Garcia-Romero
<br>
**Institution:** The Johns Hopkins University

**[ICASSP-2019]**
[Noise-tolerant Audio-visual Online Person Verification Using an Attention-based Neural Network Fusion](https://ieeexplore.ieee.org/abstract/document/8683477)
<br>
**Authors:** Suwon Shon, Tae-Hyun Oh, James Glass
<br>
**Institution:** MIT Computer Science and Artificial Intelligence Laboratory, Cambridge

**[Interspeech-2019]**
[Who Said That?: Audio-visual Speaker Diarisation Of Real-World Meetings](https://arxiv.org/abs/1906.10042)
<br>
**Authors:** Joon Son Chung, Bong-Jin Lee, Icksang Han
<br>
**Institution:** Naver Corporation

**[ICASSP-2020]**
[Self-Supervised Learning for Audio-visual Speaker Diarization](https://ieeexplore.ieee.org/abstract/document/9054376)
<br>
**Authors:** Yifan Ding, Yong Xu, Shi-Xiong Zhang, Yahuan Cong, Liqiang Wang
<br>
**Institution:** University of Central Florida; Tencent AI Lab; Beijing University of Posts and Telecommunications

**[ICASSP-2021]**
[A Multi-View Approach to Audio-visual Speaker Verification](https://ieeexplore.ieee.org/abstract/document/9414260)
<br>
**Authors:** Leda Sari, Kritika Singh, Jiatong Zhou, Lorenzo Torresani, Nayan Singhal, Yatharth Saraf
<br>
**Institution:** University of Illinois at Urbana-Champaign, Facebook AI Research

**[IEEE/ACM TASLP-2021]**
[Audio-visual Deep Neural Network for Robust Person Verification](https://ieeexplore.ieee.org/abstract/document/9350195)
<br>
**Authors:** Yanmin Qian, Zhengyang Chen, Shuai Wang
<br>
**Institution:** Shanghai Jiao Tong University

**[ICDIP 2022]**
[End-To-End Audiovisual Feature Fusion for Active Speaker Detection](https://arxiv.org/abs/2207.13434)
<br>
**Authors:** Fiseha B. Tesema, Zheyuan Lin, Shiqiang Zhu, Wei Song, Jason Gu, Hong Wu
<br>
**Institution:** Interdisciplinary Innovation Research Institute, Zhejiang Lab; Dalhousie University; University of Electronic 
Science and Technology of China; Zhejiang University

**[EUVIP-2022]**
[Active Speaker Recognition using Cross Attention Audio-Video Fusion](https://ieeexplore.ieee.org/document/9922810/)
<br>
**Authors:** Bogdan Mocanu, Tapu Ruxandra
<br>
**Institution:** University "Politehnica" of Bucharest; Télécom SudParis

**[2022]**
[Audio-Visual Activity Guided Cross-Modal Identity Association for Active Speaker Detection](https://arxiv.org/abs/2212.00539)
<br>
**Authors:** Rahul Sharma, Shrikanth Narayanan
<br>
**Institution:** University of Southern California

**[SLT-2023]**
[Push-Pull: Characterizing the Adversarial Robustness for Audio-Visual Active Speaker Detection](https://ieeexplore.ieee.org/document/10022646)
<br>
**Authors:** Xuanjun Chen, Haibin Wu, Helen Meng, Hung-yi Lee, Jyh-Shing Roger Jang
<br>
**Institution:** National Taiwan University; The Chinese University of Hong Kong

**[ICAI-2023]**
[Speaker Recognition in Realistic Scenario Using Multimodal Data](https://arxiv.org/abs/2302.13033)
<br>
**Authors:** Saqlain Hussain Shah, Muhammad Saad Saeed, Shah Nawaz, Muhammad Haroon Yousaf
<br>
**Institution:** University of Engineering and Technology Taxila; Swarm Robotics Lab NCRA; Deutsches Elektronen-Synchrotron DESY

**[CVPR-2023]**
[A Light Weight Model for Active Speaker Detection](https://arxiv.org/abs/2303.04439)
<br>
**Authors:** Junhua Liao, Haihan Duan, Kanghui Feng, Wanbing Zhao, Yanbing Yang, Liangyin Chen
<br>
**Institution:** Sichuan University; The Chinese University of Hong Kong

**[ICASSP-2023]**
[The Multimodal Information based Speech Processing (MISP) 2022 Challenge: Audio-Visual Diarization and Recognition](https://arxiv.org/abs/2303.06326)
<br>
**Authors:** Zhe Wang, Shilong Wu, Hang Chen, Mao-Kui He, Jun Du, Chin-Hui Lee, Jingdong Chen, Shinji Watanabe, Sabato Siniscalchi, Odette Scharenborg, Diyuan Liu, Baocai Yin, Jia Pan, Jianqing Gao, Cong Liu
<br>
**Institution:** University of Science and Technology of China; Georgia Institute of Technology; Carnegie Mellon University; Kore University of Enna; iFlytek; Northwestern Polytechnical University; Delft University of Technology

**[ICASSP-2023]**
[ImagineNet: Target Speaker Extraction with Intermittent Visual Cue Through Embedding Inpainting](https://ieeexplore.ieee.org/document/10097232/)
<br>
**Authors:** Zexu Pan, Wupeng Wang, Marvin Borsdorf, Haizhou Li
<br>
**Institution:** National University of Singapore; University of Bremen; The Chinese University of Hong Kong

**[ICASSP-2023]**
[Speaker Recognition with Two-Step Multi-Modal Deep Cleansing](https://ieeexplore.ieee.org/document/10096814)
<br>
**Authors:** Ruijie Tao, Kong Aik Lee, Zhan Shi, Haizhou Li
<br>
**Institution:** National University of Singapore; A*STAR; The Chinese University of Hong Kong; University of Bremen; Shenzhen Research Institute of Big Data

**[ICASSP-2023]**
[Audio-Visual Speaker Diarization in the Framework of Multi-User Human-Robot Interaction](https://ieeexplore.ieee.org/document/10096295)
<br>
**Authors:** Timothée Dhaussy, Bassam Jabaian, Fabrice Lefèvre, Radu Horaud
<br>
**Institution:** Avignon University; Université Grenoble Alpes

**[ICASSP-2023]**
[Cross-Modal Audio-Visual Co-Learning for Text-Independent Speaker Verification](https://ieeexplore.ieee.org/document/10095883/)
<br>
**Authors:** Meng Liu, Kong Aik Lee, Longbiao Wang, Hanyi Zhang, Chang Zeng, Jianwu Dang
<br>
**Institution:** Tianjin University; A⋆STAR;Singapore Institute of Technology; National Institute of Informatics

**[ICASSP-2023]**
[Multi-Speaker End-to-End Multi-Modal Speaker Diarization System for the MISP 2022 Challenge](https://ieeexplore.ieee.org/document/10096327/)
<br>
**Authors:** Tao Liu, Zhengyang Chen, Yanmin Qian, Kai Yu
<br>
**Institution:** Shanghai Jiao Tong University

**[ICASSP-2023]**
[Av-Sepformer: Cross-Attention Sepformer for Audio-Visual Target Speaker Extraction](https://ieeexplore.ieee.org/document/10094306/)
<br>
**Authors:** Jiuxin Lin, Xinyu Cai, Heinrich Dinkel, Jun Chen, Zhiyong Yan, Yongqing Wang, Junbo Zhang, Zhiyong Wu, Yujun Wang, Helen Meng
<br>
**Institution:** Tsinghua University; Xiaomi Inc.; The Chinese University of Hong Kong

**[ICASSP-2023]**
[The WHU-Alibaba Audio-Visual Speaker Diarization System for the MISP 2022 Challenge](https://ieeexplore.ieee.org/document/10095802/)
<br>
**Authors:** Ming Cheng, Haoxu Wang, Ziteng Wang, Qiang Fu, Ming Li
<br>
**Institution:** Wuhan University; Duke Kunshan University; Alibaba Group

**[ICASSP-2023]**
[Self-Supervised Audio-Visual Speaker Representation with Co-Meta Learning](https://ieeexplore.ieee.org/document/10096925)
<br>
**Authors:** Hui Chen, Hanyi Zhang, Longbiao Wang, Kong Aik Lee, Meng Liu, Jianwu Dang
<br>
**Institution:** Tianjin University; A*STAR

**[Interspeech-2023]**
[Target Active Speaker Detection with Audio-visual Cues](https://arxiv.org/abs/2305.12831)
<br>
**Authors:** Yidi Jiang, Ruijie Tao, Zexu Pan, Haizhou Li
<br>
**Institution:** National University of Singapore; The Chinese University of Hong Kong

**[Interspeech-2023]**
[CN-Celeb-AV: A Multi-Genre Audio-Visual Dataset for Person Recognition](https://arxiv.org/abs/2305.16049)
<br>
**Authors:** Lantian Li, Xiaolou Li, Haoyu Jiang, Chen Chen, Ruihai Hou, Dong Wang
<br>
**Institution:** Tsinghua University; Beijing University of Posts and Telecommunications

**[Interspeech-2023]**
[Rethinking the visual cues in audio-visual speaker extraction](https://arxiv.org/abs/2306.02625)
<br>
**Authors:** Junjie Li, Meng Ge, Zexu pan, Rui Cao, Longbiao Wang, Jianwu Dang, Shiliang Zhang
<br>
**Institution:** Tianjin University; National University of Singapore; Shenzhen Research Institute of Big Data

**[ICAI-2023]**
[Speaker Recognition in Realistic Scenario Using Multimodal Data](https://ieeexplore.ieee.org/document/10136626/)
<br>
**Authors:** Saqlain Hussain Shah, Muhammad Saad Saeed, Shah Nawaz, Muhammad Haroon Yousaf
<br>
**Institution:** University of Engineering and Technology Taxila; National Centre of Robotics and Automation; Deutsches Elektronen-Synchrotron

**[ACL-2023]**
[OpenSR: Open-Modality Speech Recognition via Maintaining Multi-Modality Alignment](https://arxiv.org/abs/2306.06410)
<br>
**Authors:** Xize Cheng, Tao Jin, Linjun Li, Wang Lin, Xinyu Duan, Zhou Zhao
<br>
**Institution:** Zhejiang University; Huawei Cloud

**[ICASSP-2023]**
[AV-SepFormer: Cross-Attention SepFormer for Audio-Visual Target Speaker Extraction](https://arxiv.org/abs/2306.14170)
<br>
**Authors:** Jiuxin Lin, Xinyu Cai, Heinrich Dinkel, Jun Chen, Zhiyong Yan, Yongqing Wang, Junbo Zhang, Zhiyong Wu, Yujun Wang, Helen Meng
<br>
**Institution:** Tsinghua University; Xiaomi Inc.; The Chinese University of Hong Kong

**[Interspeech-2023]**
[PIAVE: A Pose-Invariant Audio-Visual Speaker Extraction Network](https://arxiv.org/abs/2309.06723)
<br>
**Authors:** Qinghua Liu, Meng Ge, Zhizheng Wu, Haizhou Li
<br>
**Institution:** Shenzhen Research Institute of Big Data;  The Chinese University of Hong Kong; National University of Singapore

**[IEEE/ACM TASLP-2023]**
[A Dynamic Convolution Framework for Session-Independent Speaker Embedding Learning](https://ieeexplore.ieee.org/document/10250941/)
<br>
**Authors:** Bin Gu, Jie Zhang, Wu Guo
<br>
**Institution:** University of Science and Technology of China

**[IEEE/ACM TASLP-2024]**
[Self-Supervised Learning With Cluster-Aware-DINO for High-Performance Robust Speaker Verification](https://ieeexplore.ieee.org/document/10314722/)
<br>
**Authors:** Bing Han, Zhengyang Chen, Yanmin Qian
<br>
**Institution:** Shanghai Jiao Tong University

**[ICASSP-2024]**
[Look, Listen and Recognise: Character-Aware Audio-Visual Subtitling](https://arxiv.org/abs/2401.12039)
<br>
**Authors:** Bruno Korbar, Jaesung Huh, Andrew Zisserman
<br>
**Institution:** Visual Geometry Group, Department of Engineering Science, University of Oxford, UK

**[FG-2024]**
[Dynamic Cross Attention for Audio-Visual Person Verification](https://arxiv.org/abs/2403.04661)
<br>
**Authors:** R. Gnana Praveen, Jahangir Alam
<br>
**Institution:** Computer Research Institute of Montreal (CRIM), Montreal, Canada

#### Action Recognition
**[IJCNN-2016]**
[Exploring Multimodal Video Representation For Action Recognition](https://ieeexplore.ieee.org/abstract/document/7727435)
<br>
**Authors:** Cheng Wang; Haojin Yang; Christoph Meinel
<br>
**Institution:** University of Potsdam

**[CVPR-2018]**
[The ActivityNet Large-Scale Activity Recognition Challenge 2018 Summary](https://arxiv.org/abs/1808.03766)
<br>
**Authors:** Bernard Ghanem, Juan Carlos Niebles, Cees Snoek, Fabian Caba Heilbron, Humam Alwassel, Victor Escorcia, Ranjay Krishna, Shyamal Buch, Cuong Duc Dao
<br>
**Institution:** King Abdullah University of Science and Technology; Stanford University; Universidad del Norte; Universiteit van Amsterdam

**[ICCV-2019]**
[EPIC-Fusion: Audio-Visual Temporal Binding for Egocentric Action Recognition](https://ieeexplore.ieee.org/document/9010900)
<br>
**Authors:** Evangelos Kazakos, Arsha Nagrani, Andrew Zisserman, Dima Damen
<br>
**Institution:** University of Bristol; University of Oxford

**[ICCV-2019]**
[SCSampler: Sampling Salient Clips From Video for Efficient Action Recognition](https://openaccess.thecvf.com/content_ICCV_2019/html/Korbar_SCSampler_Sampling_Salient_Clips_From_Video_for_Efficient_Action_Recognition_ICCV_2019_paper.html)
<br>
**Authors:** Bruno Korbar, Du Tran, Lorenzo Torresani
<br>
**Institution:** Facebook AI Research

**[ICCV-2019]**
[Uncertainty-Aware Audiovisual Activity Recognition Using Deep Bayesian Variational Inference](https://ieeexplore.ieee.org/document/9008242)
<br>
**Authors:** Mahesh Subedar, Ranganath Krishnan, Paulo Lopez Meyer, Omesh Tickoo, Jonathan Huang
<br>
**Institution:** Intel Labs

**[CVPR-2020]**
[Listen to Look: Action Recognition by Previewing Audio](https://openaccess.thecvf.com/content_CVPR_2020/html/Gao_Listen_to_Look_Action_Recognition_by_Previewing_Audio_CVPR_2020_paper.html)
<br>
**Authors:** Ruohan Gao, Tae-Hyun Oh, Kristen Grauman, Lorenzo Torresani
<br>
**Institution:** The University of Texas at Austin; Facebook AI Research

**[2020]**
[Audiovisual SlowFast Networks for Video Recognition](https://arxiv.org/abs/2001.08740)
<br>
**Authors:** Fanyi Xiao, Yong Jae Lee, Kristen Grauman, Jitendra Malik, Christoph Feichtenhofer
<br>
**Institution:** University of California; Facebook AI Research

**[ICCV-2021]**
[AdaMML: Adaptive Multi-Modal Learning for Efficient Video Recognition](https://openaccess.thecvf.com/content/ICCV2021/html/Panda_AdaMML_Adaptive_Multi-Modal_Learning_for_Efficient_Video_Recognition_ICCV_2021_paper.html)
<br>
**Authors:** Rameswar Panda, Chun-Fu(Richard) Chen, Quanfu Fan, Ximeng Sun, Kate Saenko, Aude Oliva, Rogerio Feris
<br>
**Institution:** MIT-IBM Watson AI Lab; Boston University; Massachusetts Institute of Technology

**[2021]**
[Cross-Domain First Person Audio-Visual Action Recognition through Relative Norm Alignment](https://arxiv.org/abs/2106.01689)
<br>
**Authors:** Mirco Planamente, Chiara Plizzari, Emanuele Alberti, Barbara Caputo
<br>
**Institution:** Politecnico di Torino; Istituto Italiano di Tecnologia

**[WACV-2022]**
[Domain Generalization Through Audio-Visual Relative Norm Alignment in First Person Action Recognition](https://openaccess.thecvf.com/content/WACV2022/html/Planamente_Domain_Generalization_Through_Audio-Visual_Relative_Norm_Alignment_in_First_Person_WACV_2022_paper.html)
<br>
**Authors:** Mirco Planamente, Chiara Plizzari, Emanuele Alberti, Barbara Caputo
<br>
**Institution:** Politecnico di Torino; Istituto Italiano di Tecnologia; CINI Consortium

**[CVPR-2022]**
[Audio-Adaptive Activity Recognition Across Video Domains](https://openaccess.thecvf.com/content/CVPR2022/html/Zhang_Audio-Adaptive_Activity_Recognition_Across_Video_Domains_CVPR_2022_paper.html)
<br>
**Authors:** Yunhua Zhang, Hazel Doughty, Ling Shao, Cees G. M. Snoek
<br>
**Institution:** University of Amsterdam; Inception Institute of Artificial Intelligence

**[WACV-2022]**
[MM-ViT: Multi-Modal Video Transformer for Compressed Video Action Recognition](https://openaccess.thecvf.com/content/WACV2022/html/Chen_MM-ViT_Multi-Modal_Video_Transformer_for_Compressed_Video_Action_Recognition_WACV_2022_paper.html)
<br>
**Authors:** Jiawei Chen, Chiu Man Ho
<br>
**Institution:** OPPO US Research Center

**[CVPR-2022]**
[Learnable Irrelevant Modality Dropout for Multimodal Action Recognition on Modality-Specific Annotated Videos](https://openaccess.thecvf.com/content/CVPR2022/html/Alfasly_Learnable_Irrelevant_Modality_Dropout_for_Multimodal_Action_Recognition_on_Modality-Specific_CVPR_2022_paper.html)
<br>
**Authors:** Saghir Alfasly, Jian Lu, Chen Xu, Yuru Zou
<br>
**Institution:** Shenzhen University; Guangdong Key Laboratory of Intelligent Information Processing; Pazhou Lab

**[2022]**
[Noise-Tolerant Learning for Audio-Visual Action Recognition](https://arxiv.org/abs/2205.07611v1)
<br>
**Authors:** Haochen Han, Qinghua Zheng, Minnan Luo, Kaiyao Miao, Feng Tian, Yan Chen
<br>
**Institution:** Xi’an Jiaotong University,  the Shanxi Provincial Key Laboratory of Institute of Multimedia
Knowledge Fusion and Engineering; the Ministry of Education Key Laboratory for
Intelligent Networks and Network Security

**[ICLR-2023]**
[Exploring Temporally Dynamic Data Augmentation for Video Recognition](https://arxiv.org/abs/2206.15015)
<br>
**Authors:** Taeoh Kim, Jinhyung Kim, Minho Shim, Sangdoo Yun, Myunggu Kang, Dongyoon Wee, Sangyoun Lee
<br>
**Institution:** NAVER Clova; Korea Advanced Institute of Science and Technology; NAVER AI Lab; Yonsei University

**[ICASSP-2023]**
[Epic-Sounds: A Large-scale Dataset of Actions That Sound](https://arxiv.org/abs/2302.00646)
<br>
**Authors:** Jaesung Huh, Jacob Chalk, Evangelos Kazakos, Dima Damen, Andrew Zisserman
<br>
**Institution:** University of Oxford; University of Bristol

**[ICASSP-2023]**
[AV-TAD: Audio-Visual Temporal Action Detection With Transformer](https://ieeexplore.ieee.org/document/10095592/)
<br>
**Authors:** Yangcheng Li, Zefang Yu, Suncheng Xiang, Ting Liu, Yuzhuo Fu
<br>
**Institution:** Shanghai Jiao Tong University

**[ICCV-2023]**
[Audio-Visual Glance Network for Efficient Video Recognition](https://arxiv.org/abs/2308.09322)
<br>
**Authors:** Muhammad Adi Nugroho, Sangmin Woo, Sumin Lee, Changick Kim
<br>
**Institution:** Korea Advanced Institute of Science and Technology

**[IEEE TMM-2023]**
[Audio-Visual Contrastive and Consistency Learning for Semi-Supervised Action Recognition](https://ieeexplore.ieee.org/document/10243145/)
<br>
**Authors:** Maregu Assefa, Wei Jiang, Jinyu Zhan, Kumie Gedamu, Getinet Yilma, Melese Ayalew, Deepak Adhikari
<br>
**Institution:** University of Electronic Science and Technology of China; Sichuan Artificial Intelligence Research Institute; Adama Science and Technology University

**[CVPR-2024]**
[TIM: A Time Interval Machine for Audio-Visual Action Recognition](https://arxiv.org/abs/2404.05559)
<br>
**Authors:** Jacob Chalk, Jaesung Huh, Evangelos Kazakos, Andrew Zisserman, Dima Damen
<br>
**Institution:**  University of Bristol; VGG, University of Oxford;  Czech Technical University in Prague

#### Emotion Recognition
**[EMNLP-2017]**
[Tensor Fusion Network for Multimodal Sentiment Analysis](https://arxiv.org/abs/1707.07250)
<br>
**Authors:** Amir Zadeh, Minghai Chen, Soujanya Poria, Erik Cambria, Louis-Philippe Morency
<br>
**Institution:** Carnegie Mellon University; Nanyang Technological University

**[AAAI-2018]**
[Multi-attention Recurrent Network for Human Communication Comprehension](https://ojs.aaai.org/index.php/AAAI/article/view/12024)
<br>
**Authors:** Amir Zadeh, Paul Pu Liang, Soujanya Poria, Prateek Vij, Erik Cambria, Louis-Philippe Morency
<br>
**Institution:** Carnegie Mellon University; Nanyang Technological University

**[AAAI-2018]**
[Memory Fusion Network for Multi-view Sequential Learning](https://ojs.aaai.org/index.php/AAAI/article/view/12021)
<br>
**Authors:** Amir Zadeh, Paul Pu Liang, Navonil Mazumder, Soujanya Poria, Erik Cambria, Louis-Philippe Morency
<br>
**Institution:** Carnegie Mellon University; Instituto Polite cnico Nacional; Nanyang Technological University

**[NAACL-2018]**
[Conversational Memory Network for Emotion Recognition in Dyadic Dialogue Videos](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7098709/)
<br>
**Authors:** Devamanyu Hazarika, Soujanya Poria, Amir Zadeh, Erik Cambria, Louis-Philippe Morency, Roger Zimmermann
<br>
**Institution:** National University of Singapore

**[EMNLP-2018]**
[Contextual Inter-modal Attention for Multi-modal Sentiment Analysis](https://aclanthology.org/D18-1382/)
<br>
**Authors:** Deepanway Ghosal, Md Shad Akhtar, Dushyant Chauhan, Soujanya Poria, Asif Ekbal, Pushpak Bhattacharyya
<br>
**Institution:** Indian Institute of Technology Patna; Nanyang Technological University

**[ACL-2019]**
[Multi-Modal Sarcasm Detection in Twitter with Hierarchical Fusion Model](https://aclanthology.org/P19-1239/?ref=https://githubhelp.com)
<br>
**Authors:** Yitao Cai, Huiyu Cai, Xiaojun Wan
<br>
**Institution:** Peking University

**[ACL-2020]**
[Sentiment and Emotion help Sarcasm? A Multi-task Learning Framework for Multi-Modal Sarcasm, Sentiment and Emotion Analysis](https://aclanthology.org/2020.acl-main.401/)
<br>
**Authors:** Dushyant Singh Chauhan, Dhanush S R, Asif Ekbal and Pushpak Bhattacharyya
<br>
**Institution:** Indian Institute of Technology Patna

**[ACL-2020]**
[A Transformer-based joint-encoding for Emotion Recognition and Sentiment Analysis](https://aclanthology.org/2020.challengehml-1.1/)
<br>
**Authors:** Jean-Benoit Delbrouck, Noe Tits, Mathilde Brousmiche, Stephane Dupont
<br>
**Institution:** University of Mons

**[ACL-2020]**
[Multilogue-Net: A Context Aware RNN for Multi-modal Emotion Detection and Sentiment Analysis in Conversation](https://arxiv.org/abs/2002.08267)
<br>
**Authors:** Aman Shenoy, Ashish Sardana
<br>
**Institution:** Birla Institute of Technology and Science, Pilani; NVIDIA Graphics

**[CVPR-2021]**
[Progressive Modality Reinforcement for Human Multimodal Emotion Recognition From Unaligned Multimodal Sequences](https://openaccess.thecvf.com/content/CVPR2021/html/Lv_Progressive_Modality_Reinforcement_for_Human_Multimodal_Emotion_Recognition_From_Unaligned_CVPR_2021_paper.html)
<br>
**Authors:** Fengmao Lv, Xiang Chen, Yanyong Huang, Lixin Duan, Guosheng Lin
<br>
**Institution:** Southwest Jiaotong University; Southwestern University of Finance and Economics; Tencent; University of Electronic Science and Technology of China; Nanyang Technological University

**[IEEE TAFFC-2021]**
[Multi-modal Sarcasm Detection and Humor Classification in Code-mixed Conversations](https://ieeexplore.ieee.org/abstract/document/9442359)
<br>
**Authors:** Manjot Bedi, Shivani Kumar, Md Shad Akhtar, Tanmoy Chakraborty
<br>
**Institution:** Indraprastha Institute of Information Technology, Delhi

**[IEEE SLT-2021]**
[Detecting expressions with multimodal transformers](https://ieeexplore.ieee.org/document/9383573)
<br>
**Authors:** Srinivas Parthasarathy, Shiva Sundaram
<br>
**Institution:** Amazon

**[CVPR-2022]**
[M2FNet: Multi-modal Fusion Network for Emotion Recognition in Conversation](https://arxiv.org/abs/2206.02187)
<br>
**Authors:** Vishal Chudasama, Purbayan Kar, Ashish Gudmalwar, Nirmesh Shah, Pankaj Wasnik, Naoyuki Onoe
<br>
**Institution:** Sony Research India

**[CCC-2022]**
[A Multimodal Emotion Perception Model based on Context-Aware Decision-Level Fusion](https://ieeexplore.ieee.org/document/9902799)
<br>
**Authors:** Yishan Chen; Zhiyang Jia; Kaoru Hirota; Yaping Dai
<br>
**Institution:** Beijing Institute of Technology; State Key Laboratory of Intelligent Control and Decision of Complex Systems

**[IJCNN-2022]**
[Sense-aware BERT and Multi-task Fine-tuning for Multimodal Sentiment Analysis](https://ieeexplore.ieee.org/document/9892116/)
<br>
**Authors:** Lingyong Fang, Gongshen Liu, Ru Zhang
<br>
**Institution:** Shanghai Jiao Tong University; Beijing University Posts and Telecommunications

**[IEEE/ACM TASLP-2022]**
[EmoInt-Trans: A Multimodal Transformer for Identifying Emotions and Intents in Social Conversations](https://ieeexplore.ieee.org/document/9961847)
<br>
**Authors:** Gopendra Vikram Singh, Mauajama Firdaus, Asif Ekbal, Pushpak Bhattacharyya
<br>
**Institution:** Indian Institute of Technology

**[ICPR-2022]**
[Self-attention fusion for audiovisual emotion recognition with incomplete data](https://ieeexplore.ieee.org/document/9956592)
<br>
**Authors:** Kateryna Chumachenko, Alexandros Iosifidis, Moncef Gabbouj
<br>
**Institution:** Tampere University; Aarhus University

**[IEEE TAFFC-2023]**
[Audio-Visual Emotion Recognition With Preference Learning Based on Intended and Multi-Modal Perceived Labels](https://ieeexplore.ieee.org/document/10008998)
<br>
**Authors:** Yuanyuan Lei, Houwei Cao
<br>
**Institution:** Texas A&M University; New York Institute of Technology

**[IEEE T-BIOM-2023]**
[Audio-Visual Fusion for Emotion Recognition in the Valence-Arousal Space Using Joint Cross-Attention](https://ieeexplore.ieee.org/document/10005783)
<br>
**Authors:** R Gnana Praveen, Patrick Cardinal, Eric Granger
<br>
**Institution:** Ecole de technologie supérieure

**[ICASSP-2023]**
[Adapted Multimodal Bert with Layer-Wise Fusion for Sentiment Analysis](https://ieeexplore.ieee.org/document/10094923/)
<br>
**Authors:** Odysseas S. Chlapanis, Georgios Paraskevopoulos, Alexandros Potamianos
<br>
**Institution:** National Technical University of Athens; Institute for Language and Speech Processing

**[ICASSP-2023]**
[Recursive Joint Attention for Audio-Visual Fusion in Regression Based Emotion Recognition](https://ieeexplore.ieee.org/document/10095234/)
<br>
**Authors:** R Gnana Praveen, Eric Granger, Patrick Cardinal
<br>
**Institution:** École de Technologie supérieure

**[IEEE/ACM TASLP-2023]**
[Exploring Semantic Relations for Social Media Sentiment Analysis](https://ieeexplore.ieee.org/document/10149413)
<br>
**Authors:** Jiandian Zeng, Jiantao Zhou, Caishi Huang
<br>
**Institution:** Beijing Normal University; China University of Macau; University of Macau

**[CVPR-2023]**
[Weakly Supervised Video Emotion Detection and Prediction via Cross-Modal Temporal Erasing Network](https://ieeexplore.ieee.org/document/10203999)
<br>
**Authors:** Zhicheng Zhang, Lijuan Wang, Jufeng Yang
<br>
**Institution:** Nankai University

**[ACM MM-2023]**
[Hierarchical Audio-Visual Information Fusion with Multi-label Joint Decoding for MER 2023](https://arxiv.org/abs/2309.07925)
<br>
**Authors:** Haotian Wang, Yuxuan Xi, Hang Chen, Jun Du, Yan Song, Qing Wang, Hengshun Zhou, Chenxi Wang, Jiefeng Ma, Pengfei Hu, Ya Jiang, Shi Cheng, Jie Zhang, Yuzhe Weng
<br>
**Institution:** University of Science and Technology of China; Northwestern Polytechnical University

**[arxiv-2024]**
[HiCMAE: Hierarchical Contrastive Masked Autoencoder for Self-Supervised Audio-Visual Emotion Recognition](https://arxiv.org/abs/2401.05698)
<br>
**Authors:** Licai Sun, Zheng Lian, Bin Liu, Jianhua Tao
<br>
**Institution:** School of Artificial Intelligence, University of Chinese Academy of Sciences, Beijing, China; Institute of Automation, Chinese Academy of Sciences, Beijing, China; Department of Automation, Tsinghua University, Beijing, China; Beijing National Research Center for Information Science and Technology, Tsinghua University, Beijing, China

**[IJCAI-2024]**
[HyDiscGAN: A Hybrid Distributed cGAN for Audio-Visual Privacy Preservation in Multimodal Sentiment Analysis](https://arxiv.org/abs/2404.11938)
<br>
**Authors:** Zhuojia Wu, Qi Zhang, Duoqian Miao, Kun Yi, Wei Fan, Liang Hu
<br>
**Institution:**  Tongji University; Beijing Institute of Technology; University of Oxford; DeepBlue Academy of Sciences

### Uni-modal Enhancement

#### Speech Enhancement and Separation
**[Interspeech-2018]**
[Visual Speech Enhancement](https://arxiv.org/abs/1711.08789)
<br>
**Authors:** Aviv Gabbay, Asaph Shamir, Shmuel Peleg
<br>
**Institution:** The Hebrew University of Jerusalem

**[Interspeech-2018]**
[The Conversation: Deep Audio-Visual Speech Enhancement](https://arxiv.org/abs/1804.04121)
<br>
**Authors:** Triantafyllos Afouras, Joon Son Chung, Andrew Zisserman
<br>
**Institution:** University of Oxford

**[IEEE TETCI-2018]**
[Audio-Visual Speech Enhancement Using Multimodal Deep Convolutional Neural Networks](https://ieeexplore.ieee.org/abstract/document/8323326)
<br>
**Authors:** 
Jen-Cheng Hou, Syu-Siang Wang, Ying-Hui Lai, Yu Tsao, Hsiu-Wen Chang, Hsin-Min Wang 
<br>
**Institution:** Research Center for Information Technology Innovation; National Taiwan University; National Yang-Ming University; Mackay Medical College; Academia Sinica

**[ICASSP-2018]**
[Seeing Through Noise: Visually Driven Speaker Separation And Enhancement](https://ieeexplore.ieee.org/abstract/document/8462527)
<br>
**Authors:** Aviv Gabbay, Ariel Ephrat, Tavi Halperin, Shmuel Peleg
<br>
**Institution:** The Hebrew University of Jerusalem

**[GlobalSIP-2019]**
[Visually Assisted Time-Domain Speech Enhancement](https://ieeexplore.ieee.org/abstract/document/8969244)
<br>
**Authors:** Elham Ideli, Bruce Sharpe, Ivan V. Baji?, Rodney G. Vaughan
<br>
**Institution:** Simon Fraser University; SingSoftNext

**[ICASSP-2019]**
[On Training Targets and Objective Functions for Deep-learning-based Audio-visual Speech Enhancement](https://ieeexplore.ieee.org/abstract/document/8682790)
<br>
**Authors:** Daniel Michelsanti, Zheng-Hua Tan, Sigurdur Sigurdsson, Jesper Jensen
<br>
**Institution:** Aalborg University; Oticon A/S

**[InterSpeech-2019]**
[Multimodal SpeakerBeam: Single Channel Target Speech Extraction with Audio-Visual Speaker Clues](https://www.isca-speech.org/archive_v0/Interspeech_2019/pdfs/1513.pdf)
<br>
**Authors:** Tsubasa Ochiai, Marc Delcroix, Keisuke Kinoshita, Atsunori Ogawa, Tomohiro Nakatani
<br>
**Institution:** Nippon Telegraph & Telephone Corporation

**[Interspeech-2019]**
[My Lips Are Concealed: Audio-Visual Speech Enhancement Through Obstructions](https://arxiv.org/abs/1907.04975)
<br>
**Authors:** Triantafyllos Afouras, Joon Son Chung, Andrew Zisserman
<br>
**Institution:** University of Oxford; Naver Corporation

**[2020]**
[Facefilter: Audio-Visual Speech Separation Using Still Images](https://arxiv.org/abs/2005.07074)
<br>
**Authors:** Soo-Whan Chung, Soyeon Choe, Joon Son Chung, Hong-Goo Kang
<br>
**Institution:** Yonsei University; Naver Corporation

**[ICASSP-2020]**
[Robust Unsupervised Audio-Visual Speech Enhancement Using a Mixture of Variational Autoencoders](https://ieeexplore.ieee.org/abstract/document/9053730/)
<br>
**Authors:** Mostafa Sadeghi, Xavier Alameda-Pineda
<br>
**Institution:** Inria Grenoble Rhone-Alpes

**[CVPR-2021]**
[Looking Into Your Speech: Learning Cross-Modal Affinity for Audio-Visual Speech Separation](https://openaccess.thecvf.com/content/CVPR2021/html/Lee_Looking_Into_Your_Speech_Learning_Cross-Modal_Affinity_for_Audio-Visual_Speech_CVPR_2021_paper.html?ref=https://githubhelp.com)
<br>
**Authors:** Jiyoung Lee, Soo-Whan Chung, Sunok Kim, Hong-Goo Kang, Kwanghoon Sohn
<br>
**Institution:** Yonsei University; Naver Corporation; Korea Aerospace University

**[ISCAS-2021]**
[Audio-Visual Target Speaker Enhancement on Multi-Talker Environment using Event-Driven Cameras](https://arxiv.org/abs/1912.02671)
<br>
**Authors:** Ander Arriandiaga, Giovanni Morrone, Luca Pasa, Leonardo Badino, Chiara Bartolozzi
<br>
**Institution:** Istituto Italiano di Tecnologia; University of Modena and Reggio Emilia

**[ICASSP-2022]**
[The Impact of Removing Head Movements on Audio-Visual Speech Enhancement](https://ieeexplore.ieee.org/abstract/document/9746401)
<br>
**Authors:** Zhiqi Kang, Mostafa Sadeghi, Radu Horaud, Xavier Alameda-Pineda, Jacob Donley, Anurag Kumar
<br>
**Institution:** Inria Grenoble; Université Grenoble Alpes; Inria Nancy Grand-Est; Reality Labs Research

**[2022]**
[Dual-path Attention is All You Need for Audio-Visual Speech Extraction](https://arxiv.org/abs/2207.04213)
<br>
**Authors:** Zhongweiyang Xu, Xulin Fan, Mark Hasegawa-Johnson
<br>
**Institution:** University of Illinois at Urbana-Champaign

**[ICASSP-2022]**
[Audio-visual multi-channel speech separation, dereverberation and recognition](https://arxiv.org/abs/2204.01977)
<br>
**Authors:** Guinan Li, Jianwei Yu, Jiajun Deng, Xunying Liu, Helen Meng
<br>
**Institution:** The Chinese University of Hong Kong; Tencent AI lab

**[2022]**
[Audio-visual speech separation based on joint feature representation with cross-modal attention](https://arxiv.org/abs/2203.02655)
<br>
**Authors:** Junwen Xiong, Peng Zhang, Lei Xie, Wei Huang, Yufei Zha, Yanning Zhang
<br>
**Institution:** Northwestern Polytechnical University; Nanchang University

**[CVPR-2022]**
[Audio-Visual Speech Codecs: Rethinking Audio-Visual Speech Enhancement by Re-Synthesis](https://arxiv.org/abs/2203.17263)
<br>
**Authors:** Karren Yang, Dejan Marković, Steven Krenn, Vasu Agrawal, Alexander Richard
<br>
**Institution:** Massachusetts Institute of Technology; Meta Reality Labs Research

**[IEEE MMSP-2022]**
[As We Speak: Real-Time Visually Guided Speaker Separation and Localization](https://ieeexplore.ieee.org/document/9949329)
<br>
**Authors:** Piotr Czarnecki, Jakub Tkaczuk
<br>
**Institution:** Warsaw University of Technology

**[IEEE HEALTHCOM-2022]**
[A Novel Frame Structure for Cloud-Based Audio-Visual Speech Enhancement in Multimodal Hearing-aids](https://ieeexplore.ieee.org/document/9982772)
<br>
**Authors:** Abhijeet Bishnu, Ankit Gupta, Mandar Gogate, Kia Dashtipour, Ahsan Adeel, Amir Hussain, Mathini Sellathurai, Tharmalingam Ratnarajah
<br>
**Institution:** University of Edinburgh; Heriot-Watt Watt University; Edinburgh Napier University; University of Wolverhampton

**[CVPR-2022]**
[Reading to Listen at the Cocktail Party: Multi-Modal Speech Separation](https://ieeexplore.ieee.org/document/9879155)
<br>
**Authors:** Akam Rahimi, Triantafyllos Afouras, Andrew Zisserman
<br>
**Institution:** University of Oxford

**[WACV-2023]**
[BirdSoundsDenoising: Deep Visual Audio Denoising for Bird Sounds](https://arxiv.org/abs/2210.10196)
<br>
**Authors:** Youshan Zhang, Jialu Li
<br>
**Institution:** Yeshiva University; Cornell University

**[SLT-2023]**
[AVSE Challenge: Audio-Visual Speech Enhancement Challenge](https://ieeexplore.ieee.org/document/10023284)
<br>
**Authors:** Andrea Lorena Aldana Blanco, Cassia Valentini-Botinhao, Ondrej Klejch, Mandar Gogate, Kia Dashtipour, Amir Hussain, Peter Bell
<br>
**Institution:** University of Edinburgh

**[ICLR-2023]**
[Filter-Recovery Network for Multi-Speaker Audio-Visual Speech Separation](https://openreview.net/forum?id=fiB2RjmgwQ6)
<br>
**Authors:** Haoyue Cheng, Zhaoyang Liu, Wayne Wu, Limin Wang
<br>
**Institution:** Nanjing University; SenseTime

**[WACV-2023]**
[Unsupervised Audio-Visual Lecture Segmentation](https://ieeexplore.ieee.org/document/10030327/)
<br>
**Authors:** Darshan Singh S, Anchit Gupta, C. V. Jawahar, Makarand Tapaswi
<br>
**Institution:** International Institute of Information Technology, Hyderabad

**[ISCSLP-2022]**
[Multi-Task Joint Learning for Embedding Aware Audio-Visual Speech Enhancement](https://ieeexplore.ieee.org/document/10038268/)
<br>
**Authors:** Chenxi Wang, Hang Chen, Jun Du, Baocai Yin, Jia Pan
<br>
**Institution:** University of Science and Technology of China; iFlytek

**[ICASSP-2023]**
[Real-Time Audio-Visual End-to-End Speech Enhancement](https://arxiv.org/abs/2303.07005)
<br>
**Authors:** Zirun Zhu, Hemin Yang, Min Tang, Ziyi Yang, Sefik Emre Eskimez, Huaming Wang
<br>
**Institution:** Microsoft

**[ICASSP-2023]**
[Efficient Intelligibility Evaluation Using Keyword Spotting: A Study on Audio-Visual Speech Enhancement](https://ieeexplore.ieee.org/document/10096479/)
<br>
**Authors:** Cassia Valentini-Botinhao, Andrea Lorena Aldana Blanco, Ondrej Klejch, Peter Bell
<br>
**Institution:** University of Edinburgh

**[ICASSP-2023]**
[Incorporating Visual Information Reconstruction into Progressive Learning for Optimizing audio-visual Speech Enhancement](https://ieeexplore.ieee.org/document/10096507)
<br>
**Authors:** Chenyue Zhang, Hang Chen, Jun Du, Baocai Yin, Jia Pan, Chinhui Lee
<br>
**Institution:** University of Science and Technology of China; iFlytek Co., Ltd.; Georgia Institute of Technology

**[ICASSP-2023]**
[Real-Time Audio-Visual End-To-End Speech Enhancement](https://ieeexplore.ieee.org/document/10094724)
<br>
**Authors:** Zirun Zhu, Hemin Yang, Min Tang, Ziyi Yang, Sefik Emre Eskimez, Huaming Wang
<br>
**Institution:** Microsoft

**[ICASSP-2023]**
[Audio-Visual Speech Enhancement with a Deep Kalman Filter Generative Model](https://ieeexplore.ieee.org/document/10094849)
<br>
**Authors:** Ali Golmakani, Mostafa Sadeghi, Romain Serizel
<br>
**Institution:** Université de Lorraine

**[ICASSP-2023]**
[A Multi-Scale Feature Aggregation Based Lightweight Network for Audio-Visual Speech Enhancement](https://ieeexplore.ieee.org/document/10096565)
<br>
**Authors:** Haitao Xu, Liangfa Wei, Jie Zhang, Jianming Yang, Yannan Wang, Tian Gao, Xin Fang, Lirong Dai
<br>
**Institution:** University of Science and Technology of China; Ethereal Audio Lab; Tsinghua Shenzhen International Graduate School

**[ICASSP-2023]**
[Egocentric Audio-Visual Noise Suppression](https://ieeexplore.ieee.org/document/10095890)
<br>
**Authors:** Roshan Sharma, Weipeng He, Ju Lin, Egor Lakomkin, Yang Liu, Kaustubh Kalgaonkar
<br>
**Institution:** Carnegie Mellon University; Meta

**[ICASSP-2023]**
[Dual-Path Cross-Modal Attention for Better Audio-Visual Speech Extraction](https://ieeexplore.ieee.org/document/10096732/)
<br>
**Authors:** Zhongweiyang Xu, Xulin Fan, Mark Hasegawa-Johnson
<br>
**Institution:** University of Illinois at Urbana-Champaign

**[ICASSP-2023]**
[On the Role of Visual Context in Enriching Music Representations](https://ieeexplore.ieee.org/document/10094915/)
<br>
**Authors:** Kleanthis Avramidis, Shanti Stewart, Shrikanth Narayanan
<br>
**Institution:** University of Southern California

**[ICASSP-2023]**
[LA-VOCE: LOW-SNR Audio-Visual Speech Enhancement Using Neural Vocoders](https://ieeexplore.ieee.org/document/10096390/)
<br>
**Authors:** Rodrigo Mira, Buye Xu, Jacob Donley, Anurag Kumar, Stavros Petridis, Vamsi Krishna Ithapu, Maja Pantic
<br>
**Institution:** Imperial College London; Meta

**[ICASSP-2023]**
[Learning Audio-Visual Dereverberation](https://ieeexplore.ieee.org/document/10095818)
<br>
**Authors:** Changan Chen, Wei Sun, David Harwath, Kristen Grauman
<br>
**Institution:** The University of Texas at Austin; Meta AI

**[Interspeech-2023]**
[Incorporating Ultrasound Tongue Images for Audio-Visual Speech Enhancement through Knowledge Distillation](https://arxiv.org/abs/2305.14933)
<br>
**Authors:** Rui-Chen Zheng, Yang Ai, Zhen-Hua Ling
<br>
**Institution:** University of Science and Technology of China

**[Interspeech-2023]**
[Audio-Visual Speech Separation in Noisy Environments with a Lightweight Iterative Model](https://arxiv.org/abs/2306.00160)
<br>
**Authors:** Héctor Martel, Julius Richter, Kai Li, Xiaolin Hu, Timo Gerkmann
<br>
**Institution:** Tsinghua University; Universität Hamburg; Chinese Institute for Brain Research

**[ITG-2023]**
[Audio-Visual Speech Enhancement with Score-Based Generative Models](https://arxiv.org/abs/2306.01432)
<br>
**Authors:** Julius Richter, Simone Frintrop, Timo Gerkmann
<br>
**Institution:** Universität Hamburg

**[Interspeech-2023]**
[Speech inpainting: Context-based speech synthesis guided by video](https://arxiv.org/abs/2306.00489)
<br>
**Authors:** Juan F. Montesinos, Daniel Michelsanti, Gloria Haro, Zheng-Hua Tan, Jesper Jensen
<br>
**Institution:** Universitat Pompeu Fabra; Aalborg University; Oticon A/S

**[EUSIPCO-2023]**
[Audio-Visual Speech Enhancement With Selective Off-Screen Speech Extraction](https://arxiv.org/abs/2306.06495)
<br>
**Authors:** Tomoya Yoshinaga, Keitaro Tanaka, Shigeo Morishima
<br>
**Institution:** Waseda University; Waseda Research Institute for Science and Engineering

**[IEEE/ACM TASLP-2023]**
[Audio-visual End-to-end Multi-channel Speech Separation, Dereverberation and Recognition](https://arxiv.org/abs/2307.02909)
<br>
**Authors:** Guinan Li, Jiajun Deng, Mengzhe Geng, Zengrui Jin, Tianzi Wang, Shujie Hu, Mingyu Cui, Helen Meng, Xunying Liu
<br>
**Institution:** The Chinese University of Hong Kong

**[ICCV-2023]**
[AdVerb: Visually Guided Audio Dereverberation](https://arxiv.org/abs/2308.12370)
<br>
**Authors:** Sanjoy Chowdhury, Sreyan Ghosh, Subhrajyoti Dasgupta, Anton Ratnarajah, Utkarsh Tyagi, Dinesh Manocha
<br>
**Institution:** University of Maryland; University of Montreal

**[TEEE/ACM TASLP-2023]**
[Multi-Cue Guided Semi-Supervised Learning Toward Target Speaker Separation in Real Environments](https://ieeexplore.ieee.org/document/10287627)
<br>
**Authors:** Jiaming Xu, Jian Cui, Yunzhe Hao, Bo Xu
<br>
**Institution:** Xiaomi Corporation; University of Chinese Academy of Sciences

**[ICASSP-2024]**
[Consistent and Relevant: Rethink the Query Embedding in General Sound Separation](https://arxiv.org/abs/2312.15463)
<br>
**Authors:** Yuanyuan Wang, Hangting Chen, Dongchao Yang, Jianwei Yu, Chao Weng, Zhiyong Wu, Helen Meng
<br>
**Institution:** Shenzhen International Graduate School, Tsinghua University, Shenzhen, China;  Tencent AI Lab, Audio and Speech Signal Processing Oteam, China; The Chinese University of Hong Kong, Hong Kong SAR, China;

**[ICASSP-2024]**
[SECP: A Speech Enhancement-Based Curation Pipeline For Scalable Acquisition Of Clean Speech](https://arxiv.org/abs/2402.12482)
<br>
**Authors:** Adam Sabra, Cyprian Wronka, Michelle Mao, Samer Hijazi
<br>
**Institution:** Cisco Systems, Inc

**[IJCAI-2024]**
[Separate in the Speech Chain: Cross-Modal Conditional Audio-Visual Target Speech Extraction](https://arxiv.org/abs/2404.12725)
<br>
**Authors:** Zhaoxi Mu, Xinyu Yang
<br>
**Institution:**  Xi’an Jiaotong University

#### Object Sound Separation
**[ECCV-2018]**
[Learning to Separate Object Sounds by Watching Unlabeled Video](https://openaccess.thecvf.com/content_ECCV_2018/html/Ruohan_Gao_Learning_to_Separate_ECCV_2018_paper.html)
<br>
**Authors:** Ruohan Gao, Rogerio Feris, Kristen Grauman
<br>
**Institution:** The University of Texas at Austin; IBM Research; Facebook AI Research

**[ECCV-2018]**
[The Sound of Pixels](https://openaccess.thecvf.com/content_ECCV_2018/html/Hang_Zhao_The_Sound_of_ECCV_2018_paper.html)
<br>
**Authors:** Hang Zhao, Chuang Gan, Andrew Rouditchenko, Carl Vondrick, Josh McDermott
<br>
**Institution:** Massachusetts Institute of Technology; MIT-IBM Watson AI Lab; Columbia University

**[ICASSP-2019]**
[Self-supervised Audio-visual Co-segmentation](https://ieeexplore.ieee.org/abstract/document/8682467)
<br>
**Authors:** Andrew Rouditchenko, Hang Zhao, Chuang Gan, Josh McDermott, Antonio Torralba
<br>
**Institution:** Massachusetts Institute of Technology; MIT-IBM Watson AI Lab

**[ICCV-2019]**
[The Sound of Motions](https://openaccess.thecvf.com/content_ICCV_2019/html/Zhao_The_Sound_of_Motions_ICCV_2019_paper.html)
<br>
**Authors:** Hang Zhao, Chuang Gan, Wei-Chiu Ma, Antonio Torralba
<br>
**Institution:** Massachusetts Institute of Technology; MIT-IBM Watson AI Lab

**[ICCV-2019]**
[Recursive Visual Sound Separation Using Minus-Plus Net](https://openaccess.thecvf.com/content_ICCV_2019/html/Xu_Recursive_Visual_Sound_Separation_Using_Minus-Plus_Net_ICCV_2019_paper.html)
<br>
**Authors:** Xudong Xu, Bo Dai, Dahua Lin
<br>
**Institution:** The Chinese University of Hong Kong

**[ICCV-2019]**
[Co-Separating Sounds of Visual Objects](https://openaccess.thecvf.com/content_ICCV_2019/html/Gao_Co-Separating_Sounds_of_Visual_Objects_ICCV_2019_paper.html)
<br>
**Authors:** Ruohan Gao, Kristen Grauman
<br>
**Institution:** The University of Texas at Austin; Facebook AI Research

**[ACCV-2020]**
[Visually Guided Sound Source Separation using Cascaded Opponent Filter Network](https://openaccess.thecvf.com/content/ACCV2020/html/Zhu_Visually_Guided_Sound_Source_Separation_using_Cascaded_Opponent_Filter_Network_ACCV_2020_paper.html)
<br>
**Authors:** Lingyu Zhu, Esa Rahtu
<br>
**Institution:** Tampere University

**[CVPR-2020]**
[Music Gesture for Visual Sound Separation](https://openaccess.thecvf.com/content_CVPR_2020/html/Gan_Music_Gesture_for_Visual_Sound_Separation_CVPR_2020_paper.html)
<br>
**Authors:** Chuang Gan, Deng Huang, Hang Zhao, Joshua B. Tenenbaum, Antonio Torralba
<br>
**Institution:** Massachusetts Institute of Technology;  MIT-IBM Watson AI Lab

**[ICCV-2021]**
[Visual Scene Graphs for Audio Source Separation](https://openaccess.thecvf.com/content/ICCV2021/html/Chatterjee_Visual_Scene_Graphs_for_Audio_Source_Separation_ICCV_2021_paper.html)
<br>
**Authors:** Moitreya Chatterjee, Jonathan Le Roux, Narendra Ahuja, Anoop Cherian
<br>
**Institution:** University of Illinois at Urbana-Champaign; Mitsubishi Electric Research Laboratories

**[CVPR-2021]**
[Cyclic Co-Learning of Sounding Object Visual Grounding and Sound Separation](https://openaccess.thecvf.com/content/CVPR2021/html/Tian_Cyclic_Co-Learning_of_Sounding_Object_Visual_Grounding_and_Sound_Separation_CVPR_2021_paper.html)
<br>
**Authors:** Yapeng Tian, Di Hu, Chenliang Xu
<br>
**Institution:** University of Rochester; Renmin University of China; Beijing Key Laboratory of Big Data Management and Analysis Methods

**[ECCV-2022]**
[AudioScopeV2: Audio-Visual Attention Architectures for Calibrated Open-Domain On-Screen Sound Separation](https://arxiv.org/abs/2207.10141)
<br>
**Authors:** Efthymios Tzinis, Scott Wisdom, Tal Remez, John R. Hershey
<br>
**Institution:** Google Research; University of Illinois Urbana-Champaign

**[ECCV-2022]**
[AudioScopeV2: Audio-Visual Attention Architectures for Calibrated Open-Domain On-Screen Sound Separation](https://arxiv.org/abs/2207.10141)
<br>
**Authors:** Efthymios Tzinis, Scott Wisdom, Tal Remez, John R. Hershey
<br>
**Institution:** Google Research; University of Illinois Urbana-Champaign

**[ICIP-2022]**
[Visual Sound Source Separation with Partial Supervision Learning](https://ieeexplore.ieee.org/document/9897739/)
<br>
**Authors:** Huasen Wang, Lingling Gao, Qianchao Tan, Luping Ji
<br>
**Institution:** University of Electronic Science and Technology of China

**[NeurIPS-2022]**
[Learning Audio-Visual Dynamics Using Scene Graphs for Audio Source Separation](https://arxiv.org/abs/2210.16472)
<br>
**Authors:** Moitreya Chatterjee, Narendra Ahuja, Anoop Cherian
<br>
**Institution:** University of Illinois; Mitsubishi Electric Research Labs

**[ICLR-2023]**
[CLIPSep: Learning Text-queried Sound Separation with Noisy Unlabeled Videos](https://arxiv.org/abs/2212.07065) 
<br>
**Authors:** Hao-Wen Dong, Naoya Takahashi, Yuki Mitsufuji, Julian McAuley, Taylor Berg-Kirkpatrick
<br>
**Institution:** Sony Group Corporation; University of California San Diego

**[CVPR-2023]**
[Language-Guided Audio-Visual Source Separation via Trimodal Consistency](https://arxiv.org/abs/2303.16342) 
<br>
**Authors:** Reuben Tan, Arijit Ray, Andrea Burns, Bryan A. Plummer, Justin Salamon, <br>
**Institution:** Oriol Nieto, Bryan Russell, Kate Saenko
Boston University; Adobe Research; MIT-IBM Watson AI Lab, IBM Research

**[CVPR-2023]**
[iQuery: Instruments As Queries for Audio-Visual Sound Separation](https://arxiv.org/abs/2212.03814)
<br>
**Authors:** Jiaben Chen, Renrui Zhang, Dongze Lian, Jiaqi Yang, Ziyao Zeng, Jianbo Shi
<br>
**Institution:** University of California San Diego; Shanghai AI Laboratory; The Chinese University of Hong Kong; National University of Singapore; ShanghaiTech University; University of Pennsylvania

**[ICCV-2023]**
[Separating Invisible Sounds Toward Universal Audiovisual Scene-Aware Sound Separation](https://arxiv.org/abs/2310.11713)
<br>
**Authors:** Yiyang Su, Ali Vosoughi, Shijian Deng, Yapeng Tian, Chenliang Xu
<br>
**Institution:** Michigan State University; University of Rochester; University of Texas at Dallas

**[WACV-2024]**
[LAVSS: Location-Guided Audio-Visual Spatial Audio Separation](https://arxiv.org/abs/2310.20446)
<br>
**Authors:** Yuxin Ye, Wenming Yang, Yapeng Tian
<br>
**Institution:** Tsinghua University; The University of Texas at Dallas

#### Face Super-resolution and Reconstruction
**[CVPR-2020]**
[Learning to Have an Ear for Face Super-Resolution](https://openaccess.thecvf.com/content_CVPR_2020/html/Meishvili_Learning_to_Have_an_Ear_for_Face_Super-Resolution_CVPR_2020_paper.html)
<br>
**Authors:** Givi Meishvili, Simon Jenni, Paolo Favaro
<br>
**Institution:** University of Bern

**[IEEE TCSVT-2021]**
[Appearance Matters, So Does Audio: Revealing the Hidden Face via Cross-Modality Transfer](https://ieeexplore.ieee.org/abstract/document/9349088)
<br>
**Authors:** 
Chenqi Kong, Baoliang Chen, Wenhan Yang, Haoliang Li, Peilin Chen, Shiqi Wang
<br>
**Institution:** City University of Hong Kong; Nanyang Technological University

**[ICASSP-2022]**
[Deep Video Inpainting Guided by Audio-Visual Self-Supervision](https://ieeexplore.ieee.org/abstract/document/9747073/)
<br>
**Authors:** Kyuyeon Kim; Junsik Jung; Woo Jae Kim; Sung-Eui Yoon
<br>
**Institution:** Korea Advanced Institute of Science and Technology

**[CVPR-2022]**
[Cross-Modal Perceptionist: Can Face Geometry be Gleaned from Voices?](https://arxiv.org/abs/2203.09824)
<br>
**Authors:** Cho-Ying Wu, Chin-Cheng Hsu, Ulrich Neumann
<br>
**Institution:** University of Southern California

**[WACV-2023]**
[Audio-Visual Face Reenactment](https://arxiv.org/abs/2210.02755)
<br>
**Authors:** Madhav Agarwal, Rudrabha Mukhopadhyay, Vinay Namboodiri, C V Jawahar
<br>
**Institution:** International Institute of Information Technology, Hyderabad; University of Bath

**[ICASSP-2023]**
[Hearing and Seeing Abnormality: Self-Supervised Audio-Visual Mutual Learning for Deepfake Detection](https://ieeexplore.ieee.org/document/10095247/)
<br>
**Authors:** Changsung Sung, Juncheng Chen, Chusong Chen
<br>
**Institution:** National Taiwan University; Academia Sinica

**[CVPR-2023]**
[AVFace: Towards Detailed Audio-Visual 4D Face Reconstruction](https://arxiv.org/abs/2304.13115)
<br>
**Authors:** Aggelina Chatziagapi, Dimitris Samaras
<br>
**Institution:** Stony Brook University

**[CVPR-2023]**
[Parametric Implicit Face Representation for Audio-Driven Facial Reenactment](https://openaccess.thecvf.com/content/CVPR2023/papers/Huang_Parametric_Implicit_Face_Representation_for_Audio-Driven_Facial_Reenactment_CVPR_2023_paper.pdf)
<br>
**Authors:** Ricong Huang, Peiwen Lai, Yipeng Qin, Guanbin Li
<br>
**Institution:** Sun Yat-sen University; Cardiff University

**[CVPR-2023]**
[CodeTalker: Speech-Driven 3D Facial Animation with Discrete Motion Prior](https://ieeexplore.ieee.org/document/10204746)
<br>
**Authors:** Jinbo Xing, Menghan Xia, Yuechen Zhang, Xiaodong Cun, Jue Wang, Tien-Tsin Wong
<br>
**Institution:** The Chinese University of Hong Kong; Tencent AI Lab

**[ICASSP-2024]**
[Fusion of Audio and Visual Embeddings for Sound Event Localization and Detection](https://arxiv.org/abs/2312.09034)
<br>
**Authors:** Davide Berghi, Peipei Wu, Jinzheng Zhao, Wenwu Wang, Philip J. B. Jackson
<br>
**Institution:** Centre for Vision, Speech and Signal Processing (CVSSP), University of Surrey, Guildford, U.K.

## Cross-modal Perception

### Cross-modal Generation

#### Mono Sound Generation
##### Speech
**[ICASSP-2017]**
[Vid2speech: Speech Reconstruction From Silent Video](https://ieeexplore.ieee.org/abstract/document/7953127)
<br>
**Authors:** Ariel Ephrat, Shmuel Peleg
<br>
**Institution:** The Hebrew University of Jerusalem

**[ICCV-2017]**
[Improved Speech Reconstruction From Silent Video](https://openaccess.thecvf.com/content_ICCV_2017_workshops/w8/html/Ephrat_Improved_Speech_Reconstruction_ICCV_2017_paper.html)
<br>
**Authors:** Ariel Ephrat, Tavi Halperin, Shmuel Peleg
<br>
**Institution:** The Hebrew University of Jerusalem

**[ICASSP-2018]**
[Lip2Audspec: Speech Reconstruction from Silent Lip Movements Video](https://ieeexplore.ieee.org/abstract/document/8461856)
<br>
**Authors:** Hassan Akbari, Himani Arora, Liangliang Cao, Nima Mesgarani 
<br>
**Institution:** Columbia University

**[ACM MM-2018]**
[Harnessing AI for Speech Reconstruction using Multi-view Silent Video Feed](https://arxiv.org/abs/1807.00619)
<br>
**Authors:** Yaman Kumar, Mayank Aggarwa, Pratham Nawal, Shin’ichi Satoh, Rajiv Ratn Shah, Roger Zimmermann
<br>
**Institution:** Netaji Subhas Institute of Technology; National Institute of Informatics; Indraprastha Institute of Information; National University of Singapore

**[2019]**
[Video-Driven Speech Reconstruction using Generative Adversarial Networks](https://arxiv.org/abs/1906.06301)
<br>
**Authors:** Konstantinos Vougioukas, Pingchuan Ma, Stavros Petridis, Maja Pantic
<br>
**Institution:** Imperial College London; Samsung AI Centre

**[Interspeech-2019]**
[Hush-Hush Speak: Speech Reconstruction Using Silent Videos](https://www.researchgate.net/publication/335829284_Hush-Hush_Speak_Speech_Reconstruction_Using_Silent_Videos)
<br>
**Authors:** Shashwat Uttam, Yaman Kumar Singla, Dhruva Sahrawat, Mansi Agarwal
<br>
**Institution:** Netaji Subhas Institute of Technology; Adobe Research; National University of Singapore; Delhi Technological University

**[ICASSP-2021]**
[Learning Audio-Visual Correlations From Variational Cross-Modal Generation](https://ieeexplore.ieee.org/document/9414296)
<br>
**Authors:** Ye Zhu, Yu Wu, Hugo Latapie, Yi Yang, Yan Yan
<br>
**Institution:** Illinois Institute of Technology; University of Technology Sydney; Cisco

**[IEEE TCYB-2022]**
[End-to-End Video-to-Speech Synthesis Using Generative Adversarial Networks](https://ieeexplore.ieee.org/abstract/document/9760273)
<br>
**Authors:** Rodrigo Mira, Konstantinos Vougioukas, Pingchuan Ma, Stavros Petridis, Bj?rn W. Schuller, Maja Pantic
<br>
**Institution:** Imperial College London; University of Augsburg; Meta AI

**[ICPR-2022]**
[Learning Speaker-specific Lip-to-Speech Generation](https://ieeexplore.ieee.org/document/9956600/)
<br>
**Authors:** Munender Varshney, Ravindra Yadav, Vinay P. Namboodiri, Rajesh M Hegde
<br>
**Institution:** Indian institute of Technology; University of Bath

**[ICASSP-2023]**
[Imaginary Voice: Face-styled Diffusion Model for Text-to-Speech](https://arxiv.org/abs/2302.13700)
<br>
**Authors:** Jiyoung Lee, Joon Son Chung, Soo-Whan Chung
<br>
**Institution:** NAVER AI Lab; Korea Advanced Institute of Science and Technology; NAVER Cloud

**[CVPR-2023]**
[ReVISE: Self-Supervised Speech Resynthesis With Visual Input for Universal and Generalized Speech Regeneration](https://openaccess.thecvf.com/content/CVPR2023/papers/Hsu_ReVISE_Self-Supervised_Speech_Resynthesis_With_Visual_Input_for_Universal_and_CVPR_2023_paper.pdf)
<br>
**Authors:** Wei-Ning Hsu, Tal Remez, Bowen Shi, Jacob Donley, Yossi Adi
<br>
**Institution:** Meta AI; Meta Reality Labs Research; Toyota Technological Institute at Chicago; The Hebrew University of Jerusalem

**[ICCV-2023]**
[DiffV2S: Diffusion-based Video-to-Speech Synthesis with Vision-guided Speaker Embedding](https://arxiv.org/abs/2308.07787)
<br>
**Authors:** Jeongsoo Choi, Joanna Hong, Yong Man Ro
<br>
**Institution:** Korea Advanced Institute of Science and Technology

**[CVPR-2024]**
[Seeing and Hearing: Open-domain Visual-Audio Generation with Diffusion Latent Aligners](https://arxiv.org/abs/2402.17723)
<br>
**Authors:** Yazhou Xing, Yingqing He, Zeyue Tian, Xintao Wang, Qifeng Chen
<br>
**Institution:** HKUST; ARCLab,Tencent PCG

##### Music
**[IEEE TMM-2015]**
[Real-Time Piano Music Transcription Based on Computer Vision](https://ieeexplore.ieee.org/abstract/document/7225173)
<br>
**Authors:** Mohammad Akbari, Howard Cheng
<br>
**Institution:** Simon Fraser University; University of Lethbridge 

**[ACM MM-2017]**
[Deep Cross-Modal Audio-Visual Generation](https://dl.acm.org/doi/abs/10.1145/3126686.3126723)
<br>
**Authors:** 
Lele Chen, Sudhanshu Srivastava, 
Zhiyao Duan, Chenliang Xu
<br>
**Institution:** University of Rochester

**[NeurIPS-2020]**
[Audeo: Audio Generation for a Silent Performance Video](https://proceedings.neurips.cc/paper/2020/hash/227f6afd3b7f89b96c4bb91f95d50f6d-Abstract.html)
<br>
**Authors:** Kun Su, Xiulong Liu, Eli Shlizerman
<br>
**Institution:** University of Washington

**[ECCV-2020]**
[Foley Music: Learning to Generate Music from Videos](https://link.springer.com/chapter/10.1007/978-3-030-58621-8_44)
<br>
**Authors:** Chuang Gan, Deng Huang, Peihao Chen, Joshua B. Tenenbaum, Antonio Torralba 
<br>
**Institution:** Cambridge

**[ICASSP-2020]**
[Sight to Sound: An End-to-End Approach for Visual Piano Transcription](https://ieeexplore.ieee.org/abstract/document/9053115)
<br>
**Authors:** A. Sophia Koepke, Olivia Wiles
, Yael Moses, Andrew Zisserman
<br>
**Institution:** University of Oxford; The Interdisciplinary Center

**[2020]**
[Multi-Instrumentalist Net: Unsupervised Generation of Music from Body Movements](https://arxiv.org/abs/2012.03478)
<br>
**Authors:** Kun Su, Xiulong Liu, Eli Shlizerman
<br>
**Institution:** University of Washington

**[ICASSP-2021]**
[Collaborative Learning to Generate Audio-Video Jointly](https://ieeexplore.ieee.org/abstract/document/9413802/)
<br>
**Authors:** Vinod K Kurmi, Vipul Bajaj, Badri N Patro, K S Venkatesh, Vinay P Namboodiri, Preethi Jyothi
<br>
**Institution:** Indian Institute of Technology Kanpur; University of Bath; Indian Institute of Technology Bombay

**[ACM-2021]**
[Video Background Music Generation with Controllable Music Transformer](https://dl.acm.org/doi/abs/10.1145/3474085.3475195)
<br>
**Authors:** Shangzhe Di, 
Zeren Jiang, Si Liu, Zhaokai Wang, Leyan Zhu, Zexin He, Hongming Liu, Shuicheng Yan
<br>
**Institution:** Beihang University; Charterhouse School, Godalming, Surrey; Sea AI Lab

**[2022]**
[Vis2Mus: Exploring Multimodal Representation Mapping for Controllable Music Generation](https://arxiv.org/abs/2211.05543)
<br>
**Authors:** Runbang Zhang, Yixiao Zhang, Kai Shao, Ying Shan, Gus Xia
<br>
**Institution:** New York University, Shanghai; Queen Mary University of London; Tencent Inc.; Mohamed bin Zayed University of Artificial Intelligence

**[CVPR-2023]**
[Conditional Generation of Audio from Video via Foley Analogies](https://arxiv.org/abs/2304.08490)
<br>
**Authors:** Yuexi Du, Ziyang Chen, Justin Salamon, Bryan Russell, Andrew Owens
<br>
**Institution:** University of Michigan; Yale University; Adobe Research

**[ICML-2023]**
[Long-Term Rhythmic Video Soundtracker](https://arxiv.org/abs/2305.01319)
<br>
**Authors:** Jiashuo Yu, Yaohui Wang, Xinyuan Chen, Xiao Sun, Yu Qiao
<br>
**Institution:** Shanghai Artificial Intelligence Laboratory

##### Natural Sound
**[CVPR-2016]**
[Visually Indicated Sounds](https://openaccess.thecvf.com/content_cvpr_2016/html/Owens_Visually_Indicated_Sounds_CVPR_2016_paper.html)
<br>
**Authors:** Andrew Owens, Phillip Isola, Josh McDermott, Antonio Torralba, Edward H. Adelson, William T. Freeman
<br>
**Institution:** Massachusetts Institute of Technology; U.C. Berkeley; Google Research

**[CVPR-2018]**
[Visual to Sound: Generating Natural Sound for Videos in the Wild](https://openaccess.thecvf.com/content_cvpr_2018/html/Zhou_Visual_to_Sound_CVPR_2018_paper.html)
<br>
**Authors:** Yipin Zhou, Zhaowen Wang, Chen Fang, Trung Bui, Tamara L. Berg
<br>
**Institution:** University of North Carolina at Chapel Hill; Adobe Research

**[IEEE TIP-2020]**
[Generating Visually Aligned Sound From Videos](https://ieeexplore.ieee.org/abstract/document/9151258)
<br>
**Authors:** 
Peihao Chen, Yang Zhang, Mingkui Tan, Hongdong Xiao, Deng Huang, Chuang Gan, 
<br>
**Institution:** South China University of Technology; China Pazhou Laboratory; MIT-IBM Watson AI Lab

**[BMVC-2021]**
[Taming Visually Guided Sound Generation](https://arxiv.org/abs/2110.08791)
<br>
**Authors:** Vladimir Iashin, Esa Rahtu
<br>
**Institution:** Tampere University

**[IEEE TCSVT-2022]**
[Towards an End-to-End Visual-to-Raw-Audio Generation With GAN](https://ieeexplore.ieee.org/document/9430540)
<br>
**Authors:** Shiguang Liu; Sijia Li; Haonan Cheng
<br>
**Institution:** Tianjin University

**[ICASSP-2023]**
[I Hear Your True Colors: Image Guided Audio Generation](https://arxiv.org/abs/2211.03089)
<br>
**Authors:** Roy Sheffer, Yossi Adi
<br>
**Institution:** The Hebrew University of Jerusalem

**[CVPR-2023]**
[Physics-Driven Diffusion Models for Impact Sound Synthesis from Videos](https://arxiv.org/abs/2303.16897)
<br>
**Authors:** Kun Su, Kaizhi Qian, Eli Shlizerman, Antonio Torralba, Chuang Gan
<br>
**Institution:** University of Washington; MIT-IBM Watson AI Lab; MIT; UMass Amherst

#### Spatial Sound Generation
**[ACM TOG-2018]**
[Scene-aware audio for 360° videos](https://dl.acm.org/doi/abs/10.1145/3197517.3201391)
<br>
**Authors:** Dingzeyu Li, Timothy R.Langlois, Changxi Zheng
<br>
**Institution:** Columbia University; Adobe Research

**[NeurIPS-2018]**
[Self-Supervised Generation of Spatial Audio for 360° Video](https://proceedings.neurips.cc/paper/2018/hash/01161aaa0b6d1345dd8fe4e481144d84-Abstract.html)
<br>
**Authors:** Pedro Morgado, Nuno Nvasconcelos, Timothy Langlois, Oliver Wang
<br>
**Institution:** University of California San Diego; Adobe Research

**[CVPR-2019]**
[2.5D Visual Sound](https://openaccess.thecvf.com/content_CVPR_2019/html/Gao_2.5D_Visual_Sound_CVPR_2019_paper.html)
<br>
**Authors:** Ruohan Gao, Kristen Grauman
<br>
**Institution:** The University of Texas at Austin; Facebook AI Research

**[ICIP-2019]**
[Self-Supervised Audio Spatialization with Correspondence Classifier](https://ieeexplore.ieee.org/abstract/document/8803494/)
<br>
**Authors:** Yu-Ding Lu, Hsin-Ying Lee, Hung-Yu Tseng, Ming-Hsuan Yang
<br>
**Institution:** University of California at Merced

**[ECCV-2020]**
[Sep-Stereo: Visually Guided Stereophonic Audio Generation by Associating Source Separation](https://link.springer.com/chapter/10.1007/978-3-030-58610-2_4)
<br>
**Authors:** Hang Zhou, Xudong Xu, Dahua Lin, Xiaogang Wang, Ziwei Liu
<br>
**Institution:** The Chinese University of Hong Kong

**[CVPR-2021]**
[Visually Informed Binaural Audio Generation without Binaural Audios](https://openaccess.thecvf.com/content/CVPR2021/html/Xu_Visually_Informed_Binaural_Audio_Generation_without_Binaural_Audios_CVPR_2021_paper.html)
<br>
**Authors:** Xudong Xu, Hang Zhou, Ziwei Liu, Bo Dai, Xiaogang Wang, Dahua Lin
<br>
**Institution:** The Chinese University of Hong Kong; Nanyang Technological University

**[AAAI-2021]**
[Exploiting Audio-Visual Consistency with Partial Supervision for Spatial Audio Generation](https://ojs.aaai.org/index.php/AAAI/article/view/16302)
<br>
**Authors:** Yan-Bo Lin, Yu-Chiang Frank Wang
<br>
**Institution:** National Taiwan University; ASUS Intelligent Cloud Services

**[TOG-2021]**
[Binaural Audio Generation via Multi-task Learning](https://arxiv.org/abs/2109.00748)
<br>
**Authors:** Sijia Li, Shiguang Liu, Dinesh Manocha
<br>
**Institution:** Tianjin University; University of Maryland at College Park

**[WACV-2022]**
[Beyond Mono to Binaural: Generating Binaural Audio From Mono Audio With Depth and Cross Modal Attention](https://openaccess.thecvf.com/content/WACV2022/html/Parida_Beyond_Mono_to_Binaural_Generating_Binaural_Audio_From_Mono_Audio_WACV_2022_paper.html)
<br>
**Authors:** Kranti Kumar Parida, Siddharth Srivastava, Gaurav Sharma
<br>
**Institution:** Indian Institute of Technology Kanpur; CDAC Noida; TensorTour Inc.

**[CVPR-2023]**
[Novel-View Acoustic Synthesis](https://ieeexplore.ieee.org/document/10204911)
<br>
**Authors:** Changan Chen, Alexander Richard, Roman Shapovalov, Vamsi Krishna Ithapu, Natalia Neverova, Kristen Grauman, Andrea Vedaldi
<br>
**Institution:** University of Texas at Austin; Meta AI

#### Video Generation
##### talking face
**[ACM TOG-2017]**
[Synthesizing Obama: learning lip sync from audio](https://dl.acm.org/doi/abs/10.1145/3072959.3073640)
<br>
**Authors:** Supasorn Suwajanakorn, Steven Maxwell Seitz, Ira Kemelmacher-Shlizerman
<br>
**Institution:** University of Washington

**[ECCV-2018]**
[Lip Movements Generation at a Glance](https://openaccess.thecvf.com/content_ECCV_2018/html/Lele_Chen_Lip_Movements_Generation_ECCV_2018_paper.html)
<br>
**Authors:** Lele Chen, Zhiheng Li, Ross K Maddox, Zhiyao Duan, Chenliang Xu
<br>
**Institution:** University of Rochester

**[IJCV-2019]**
[You Said That?: Synthesising Talking Faces from Audio](https://link.springer.com/article/10.1007/s11263-019-01150-y)
<br>
**Authors:** Amir Jamaludin, Joon Son Chung, Andrew Zisserman
<br>
**Institution:** University of Oxford

**[ICCV-2019]**
[Few-Shot Adversarial Learning of Realistic Neural Talking Head Models](https://openaccess.thecvf.com/content_ICCV_2019/html/Zakharov_Few-Shot_Adversarial_Learning_of_Realistic_Neural_Talking_Head_Models_ICCV_2019_paper.html)
<br>
**Authors:** Egor Zakharov, Aliaksandra Shysheya, Egor Burkov, Victor Lempitsky
<br>
**Institution:** Samsung AI Center; Skolkovo Institute of Science and Technology

**[IJCV-2020]**
[Realistic Speech-Driven Facial Animation with GANs](https://link.springer.com/article/10.1007/s11263-019-01251-8)
<br>
**Authors:** Konstantinos Vougioukas, Stavros Petridis, Maja Pantic
<br>
**Institution:** Imperial College London; Samsung AI Research Centre Cambridge

**[IJCV-2020]**
[GANimation: One-Shot Anatomically Consistent Facial Animation](https://link.springer.com/article/10.1007/s11263-019-01210-3)
<br>
**Authors:** Albert Pumarola, Antonio Agudo, Aleix M. Martinez, Alberto Sanfeliu, Francesc Moreno-Noguer
<br>
**Institution:** Institut de Robòtica i Informàtica Industrial; The Ohio State University

**[ACM TOG-2020]**
[Makelttalk: Speaker-Aware Talking-Head Animation](https://dl.acm.org/doi/abs/10.1145/3414685.3417774)
<br>
**Authors:** Yang Zhou, Xintong Han, Eli Shechtman, Jose Echevarria, Evangelos Kalogerakis, Dingzeyu Li
<br>
**Institution:** University of Massachusetts Amherst; Huya Inc.; Adobe Research

**[CVPR-2020]**
[FReeNet: Multi-Identity Face Reenactment](https://openaccess.thecvf.com/content_CVPR_2020/html/Zhang_FReeNet_Multi-Identity_Face_Reenactment_CVPR_2020_paper.html)
<br>
**Authors:** Jiangning Zhang, Xianfang Zeng, Mengmeng Wang, Yusu Pan, Liang Liu, Yong Liu, Yu Ding, Changjie Fan
<br>
**Institution:** Zhejiang University; Fuxi AI Lab 

**[ECCV-2020]**
[Neural Voice Puppetry: Audio-driven Facial Reenactment](https://justusthies.github.io/posts/neural-voice-puppetry/)
<br>
**Authors:** Justus Thies, Mohamed Elgharib, Ayush Tewari, Christian Theobalt, Matthias Nie?ner
<br>
**Institution:** Technical University of Munich; Saarland Informatics Campus

**[CVPR-2020]**
[Rotate-and-Render: Unsupervised Photorealistic Face Rotation from Single-View Images](https://arxiv.org/abs/2003.08124)
<br>
**Authors:** Hang Zhou, Jihao Liu, Ziwei Liu, Yu Liu, Xiaogang Wang
<br>
**Institution:** The Chinese University of Hong Kong; SenseTime Research 

**[ECCV-2020]**
[MEAD: A Large-scale Audio-visual Dataset for Emotional Talking-face Generation](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660698.pdf)
<br>
**Authors:** Kaisiyuan Wang, Qianyi Wu, Linsen Song, Zhuoqian Yang, Wayne Wu, Chen Qian, Ran He, Yu Qiao, Chen Change Loy
<br>
**Institution:** SenseTime Research; Carnegie Mellon University; Center for Research on Intelligent Perception and Computing, CASIA; University of Chinese Academy of Sciences; Shenzhen Institutes of Advanced Technology, Chinese Academy of Science; Nanyang Technological University

**[AAAI-2021]**
[Write-a-speaker: Text-based Emotional and Rhythmic Talking-head Generation](https://ojs.aaai.org/index.php/AAAI/article/view/16286)
<br>
**Authors:** Lincheng Li, Suzhen Wang, Zhimeng Zhang, Yu Ding, Yixing Zheng, Xin Yu, Changjie Fan
<br>
**Institution:** Netease Fuxi AI Lab; University of Technology Sydney

**[CVPR-2021]**
[Pose-Controllable Talking Face Generation by Implicitly Modularized Audio-Visual Representation](https://openaccess.thecvf.com/content/CVPR2021/html/Zhou_Pose-Controllable_Talking_Face_Generation_by_Implicitly_Modularized_Audio-Visual_Representation_CVPR_2021_paper.html)
<br>
**Authors:** Hang Zhou, Yasheng Sun, Wayne Wu, Chen Change Loy, Xiaogang Wang, Ziwei Liu
<br>
**Institution:** The Chinese University of Hong Kong; SenseTime Research; Tokyo Institute of Technology; Nanyang Technological University

**[CVPR-2021]**
[Audio-Driven Emotional Video Portraits](https://openaccess.thecvf.com/content/CVPR2021/html/Ji_Audio-Driven_Emotional_Video_Portraits_CVPR_2021_paper.html)
<br>
**Authors:** Xinya Ji, Hang Zhou, Kaisiyuan Wang, Wayne Wu, Chen Change Loy, Xun Cao, Feng Xu
<br>
**Institution:** Nanjing University; The Chinese University of Hong Kong; The University of Sydney; SenseTime Research; Nanyang Technological University; Tsinghua University

**[AAAI-2022]**
[One-shot Talking Face Generation from Single-speaker Audio-Visual Correlation Learning](https://arxiv.org/abs/2112.02749)
<br>
**Authors:** Suzhen Wang, Lincheng Li, Yu Ding, Xin Yu
<br>
**Institution:** Netease Fuxi AI Lab; University of Technology Sydney

**[TVCG-2022]**
[Generating talking face with controllable eye movements by disentangled blinking feature](https://ieeexplore.ieee.org/document/9858334/)
<br>
**Authors:** Shiguang Liu, Jiaqi Hao
<br>
**Institution:** Tianjin University

**[AAAI-2022]**
[SyncTalkFace: Talking Face Generation with Precise Lip-Syncing via Audio-Lip Memory](https://arxiv.org/abs/2211.00924)
<br>
**Authors:** Se Jin Park, Minsu Kim, Joanna Hong, Jeongsoo Choi, Yong Man Ro
<br>
**Institution:** Korea Advanced Institute of Science and Technology

**[CVPR-2022]**
[FaceFormer: Speech-Driven 3D Facial Animation with Transformers](https://ieeexplore.ieee.org/document/9878591)
<br>
**Authors:** Yingruo Fan, Zhaojiang Lin, Jun Saito, Wenping Wang, Taku Komura
<br>
**Institution:** The University of Hong Kong; The Hong Kong University of Science and Technology; Adobe Research; Texas A&M University

**[CVPR-2023]**
[Seeing What You Said: Talking Face Generation Guided by a Lip Reading Expert](https://arxiv.org/abs/2303.17480)
<br>
**Authors:** Jiadong Wang, Xinyuan Qian, Malu Zhang, Robby T. Tan, Haizhou Li
<br>
**Institution:** National University of Singapore; University of Science and Technology Beijing; University of Electronic Science and Technology of China; The Chinese University of Hong Kong

**[ICASSP-2023]**
[Free-View Expressive Talking Head Video Editing](https://ieeexplore.ieee.org/document/10095745/)
<br>
**Authors:** Yuantian Huang, Satoshi Iizuka, Kazuhiro Fukui
<br>
**Institution:** University of Tsukuba

**[ICASSP-2023]**
[Audio-Driven Facial Landmark Generation in Violin Performance using 3DCNN Network with Self Attention Model](https://ieeexplore.ieee.org/document/10096358/)
<br>
**Authors:** Tingwei Lin, Chaolin Liu, Li Su
<br>
**Institution:** Taiwan International Graduate Program; Academia Sinica; National Chengchi University

**[ICASSP-2023]**
[Naturalistic Head Motion Generation from Speech](https://ieeexplore.ieee.org/document/10095684)
<br>
**Authors:** Trisha Mittal, Zakaria Aldeneh, Masha Fedzechkina, Anurag Ranjan, Barry-John Theobald
<br>
**Institution:** University of Maryland; Apple Inc.

**[ICASSP-2023]**
[Audio-Visual Inpainting: Reconstructing Missing Visual Information with Sound](https://ieeexplore.ieee.org/document/10095447/)
<br>
**Authors:** Valentina Sanguineti, Sanket Thakur, Pietro Morerio, Alessio Del Bue, Vittorio Murino
<br>
**Institution:** Istituto Italiano di Tecnologia; University of Genova

**[CVPR-2023]**
[Identity-Preserving Talking Face Generation with Landmark and Appearance Priors](https://arxiv.org/abs/2305.08293)
<br>
**Authors:** Weizhi Zhong, Chaowei Fang, Yinqi Cai, Pengxu Wei, Gangming Zhao, Liang Lin, Guanbin Li
<br>
**Institution:** Sun Yat-sen University; Xidian University; The University of Hong Kong

**[CVPR-2023]**
[SadTalker: Learning Realistic 3D Motion Coefficients for Stylized Audio-Driven Single Image Talking Face Animation](https://arxiv.org/abs/2211.12194)
<br>
**Authors:** Wenxuan Zhang, Xiaodong Cun, Xuan Wang, Yong Zhang, Xi Shen, Yu Guo, Ying Shan, Fei Wang
<br>
**Institution:** Xi’an Jiaotong University; National Key Laboratory of Human-Machine Hybrid Augmented Intelligence; Tencent AI Lab; Ant Group

**[ACM MM-2023]**
[Hierarchical Semantic Perceptual Listener Head Video Generation: A High-performance Pipeline](https://arxiv.org/abs/2307.09821)
<br>
**Authors:** Zhigang Chang, Weitai Hu, Qing Yang, Shibao Zheng
<br>
**Institution:** Du Xiaoman Financial; Shanghai Jiao Tong University

**[CVPR-2023]**
[LipFormer: High-fidelity and Generalizable Talking Face Generation with A Pre-learned Facial Codebook](https://ieeexplore.ieee.org/document/10203891)
<br>
**Authors:** Jiayu Wang, Kang Zhao, Shiwei Zhang, Yingya Zhang, Yujun Shen, Deli Zhao, Jingren Zhou
<br>
**Institution:** Alibaba Group

#### Gesture
**[IVA-2018]**
[Evaluation of Speech-to-Gesture Generation Using Bi-Directional LSTM Network](https://dl.acm.org/doi/abs/10.1145/3267851.3267878)
<br>
**Authors:** Dai Hasegawa, Naoshi Kaneko, Shinichi Shirakawa, Hiroshi Sakuta, Kazuhiko Sumi
<br>
**Institution:** Hokkai Gakuen University Sapporo; Aoyama Gakuin University; Yokohama National University

**[IVA-2019]**
[Analyzing Input and Output Representations for Speech-Driven Gesture Generation](https://dl.acm.org/doi/abs/10.1145/3308532.3329472)
<br>
**Authors:** Taras Kucherenko, Dai Hasegawa, Gustav Eje Henter, Naoshi Kaneko, Hedvig Kjellstr?m
<br>
**Institution:** KTH Royal Institute of Technology in Stockholm; Hokkai Gakuen University; Aoyama Gakuin University; 

**[CVPR-2019]**
[Learning Individual Styles of Conversational Gesture](https://openaccess.thecvf.com/content_CVPR_2019/html/Ginosar_Learning_Individual_Styles_of_Conversational_Gesture_CVPR_2019_paper.html)
<br>
**Authors:** Shiry Ginosar, Amir Bar, Gefen Kohavi, Caroline Chan, Andrew Owens, Jitendra Malik
<br>
**Institution:** University of California, Berkeley; Zebra Medical Vision; Massachusetts Institute of Technology

**[ICMI-2019]**
[To React or not to React: End-to-End Visual Pose Forecasting for Personalized Avatar during Dyadic Conversations](https://dl.acm.org/doi/abs/10.1145/3340555.3353725), 
<br>
**Authors:** Chaitanya Ahuja, Shugao Ma, Louis-Philippe Morency, Yaser Sheikh
<br>
**Institution:** Carnegie Mellon University; Facebook Reality Labs

**[EUROGRAPHICS-2020]**
[Style-Controllable Speech-Driven Gesture Synthesis Using Normalising Flows](https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.13946)
<br>
**Authors:** Simon Alexanderson, Gustav Eje Henter, Taras Kucherenko, Jonas Beskow
<br>
**Institution:** KTH Royal Institute of Technology

**[ICMI-2020]**
[Gesticulator: A Framework For Semantically-Aware Speech-Driven Gesture Generation](https://dl.acm.org/doi/abs/10.1145/3382507.3418815)
<br>
**Authors:** Taras Kucherenko, Patrik Jonell, Sanne van Waveren, Gustav Eje Henter, Simon Alexandersson, Iolanda Leite, Hedvig Kjellstr?m
<br>
**Institution:** KTH Royal Institute of Technology 

**[2020]**
[Style Transfer for Co-Speech Gesture Animation: A Multi-Speaker Conditional-Mixture Approach](https://arxiv.org/abs/2007.12553)
<br>
**Authors:** Chaitanya Ahuja, Dong Won Lee, Yukiko I. Nakano, Louis-Philippe Morency
<br>
**Institution:** Carnegie Mellon University; Seikei University

**[ACM TOG-2020]**
[Speech Gesture Generation From The Trimodal Context Of Text, Audio, And Speaker Identity](https://dl.acm.org/doi/abs/10.1145/3414685.3417838)
<br>
**Authors:** Youngwoo Yoon, Bok Cha, Joo-Haeng Lee, Minsu Jang, Jaeyeon Lee, Jaehong Kim, Geehyuk Lee
<br>
**Institution:** Korea Advanced Institute of Science and Technology; University of Science and Technology; Electronics and Telecommunications Research Institute

**[CVPR-2022]**
[SEEG: Semantic Energized Co-Speech Gesture Generation](https://openaccess.thecvf.com/content/CVPR2022/html/Liang_SEEG_Semantic_Energized_Co-Speech_Gesture_Generation_CVPR_2022_paper.html)
<br>
**Authors:** Yuanzhi Liang, Qianyu Feng, Linchao Zhu, Li Hu, Pan Pan, Yi Yang
<br>
**Institution:** Alibaba; University of Technology Sydney; Zhejiang University 

**[IEEE TNNLS-2022]**
[VAG: A Uniform Model for Cross-Modal Visual-Audio Mutual Generation](https://ieeexplore.ieee.org/document/9753685)
<br>
**Authors:** Wangli Hao; He Guan; Zhaoxiang Zhang
<br>
**Institution:** Chinese Academy of Sciences; University of Chinese Academy of Sciences

**[CVPR-2023]**
[Taming Diffusion Models for Audio-Driven Co-Speech Gesture Generation](https://arxiv.org/abs/2303.09119)
<br>
**Authors:** Lingting Zhu, Xian Liu, Xuanyu Liu, Rui Qian, Ziwei Liu, Lequan Yu
<br>
**Institution:** The University of Hong Kong; The Chinese University of Hong Kong; Nanyang Technological University

##### Dance
**[ACM MM-2018]**
[Dance with Melody: An LSTM-autoencoder Approach to Music-oriented Dance Synthesis](https://dl.acm.org/doi/abs/10.1145/3240508.3240526)
<br>
**Authors:** Taoran Tang, Jia Jia, Hanyang Mao
<br>
**Institution:** Tsinghua University

**[CVPR-2018]**
[Audio to Body Dynamics](https://openaccess.thecvf.com/content_cvpr_2018/html/Shlizerman_Audio_to_Body_CVPR_2018_paper.html)
<br>
**Authors:** Eli Shlizerman, Lucio Dery, Hayden Schoen, Ira Kemelmacher-Shlizerman
<br>
**Institution:** Facebook Inc.; Stanford University; University of Washington

**[NeurIPS-2019]**
[Dancing to Music](https://proceedings.neurips.cc/paper/2019/hash/7ca57a9f85a19a6e4b9a248c1daca185-Abstract.html)
<br>
**Authors:** Hsin-Ying Lee, Xiaodong Yang, Ming-Yu Liu, Ting-Chun Wang, Yu-Ding Lu, Ming-Hsuan Yang, Jan Kautz
<br>
**Institution:** University of California; NVIDIA 

**[ICLR-2021]**
[Dance Revolution: Long-Term Dance Generation with Music via Curriculum Learning](https://arxiv.org/abs/2006.06119)
<br>
**Authors:** Ruozi Huang, Huang Hu, Wei Wu, Kei Sawada, Mi Zhang, Daxin Jiang
<br>
**Institution:** Fudan University; Microsoft STCA; Meituan; Rinna AI

**[ICCV-2021]**
[AI Choreographer: Music Conditioned 3D Dance Generation With AIST++](https://openaccess.thecvf.com/content/ICCV2021/html/Li_AI_Choreographer_Music_Conditioned_3D_Dance_Generation_With_AIST_ICCV_2021_paper.html)
<br>
**Authors:** Ruilong Li, Shan Yang, David A. Ross, Angjoo Kanazawa
<br>
**Institution:** University of Southern California; Google Research; University of California, Berkeley

**[ICASSP-2022]**
[Genre-Conditioned Long-Term 3D Dance Generation Driven by Music](https://ieeexplore.ieee.org/abstract/document/9747838/)
<br>
**Authors:** Yuhang Huang, Junjie Zhang, Shuyan Liu, Qian Bao, Dan Zeng, Zhineng Chen, Wu Liu
<br>
**Institution:** Shanghai University; University of Chinese Academy of Sciences; JD AI Research; Fudan University

**[CVPR-2022]**
[Bailando: 3D Dance Generation by Actor-Critic GPT with Choreographic Memory](https://arxiv.org/pdf/2203.13055.pdf)
<br>
**Authors:** Li Siyao, Weijiang Yu, Tianpei Gu, Chunze Lin, Quan Wang, Chen Qian, Chen Chang Loy, Ziwei Liu
<br>
**Institution:**  Nanyang Technological University; Sun Yat-Sen University; University of California, Los Angeles; SenseTime Research

**[CVPR-2023]**
[MM-Diffusion: Learning Multi-Modal Diffusion Models for
Joint Audio and Video Generation](https://openaccess.thecvf.com/content/CVPR2023/papers/Ruan_MM-Diffusion_Learning_Multi-Modal_Diffusion_Models_for_Joint_Audio_and_Video_CVPR_2023_paper.pdf)
<br>
**Authors:** Ludan Ruan, Yiyang Ma, Huan Yang, Huiguo He, Bei Liu, Jianlong Fu, Nicholas Jing Yuan, Qin Jin, Baining Guo
<br>
**Institution:** Renmin University of China; Peking University; Microsoft Research

**[IEEE TMM-2023]**
[Learning Music-Dance Representations through Explicit-Implicit Rhythm Synchronization](https://ieeexplore.ieee.org/document/10214079)
<br>
**Authors:** Jiashuo Yu, Junfu Pu, Ying Cheng, Rui Feng, Ying Shan
<br>
**Institution:** Shanghai Key Lab of Intelligent Information Processing; Fudan University; Tencent

**[VCJ-2024]**
[QEAN: Quaternion-Enhanced Attention Network for Visual Dance Generation](https://arxiv.org/abs/2403.11626)
<br>
**Authors:** Zhizhen Zhou, Yejing Huo, Guoheng Huang, An Zeng, Xuhang Chen, Lian Huang, Zinuo Li
<br>
**Institution:** Guangdong University of Technology, Guangdong, China; Huizhou University, Guangdong, China; Guangdong Mechanical and Electrical College, Guangdong, China; University of Western Australia, WA, Australia

#### Image Manipulation
**[2021]**
[Sound-guided semantic image manipulation](https://arxiv.org/abs/2112.00007)
Seung Hyun Lee, Wonseok Roh, Wonmin Byeon, Sang Ho Yoon, Chan Young Kim, Jinkyu Kim, Sangpil Kim
Korea University; Korea Advanced Institute of Science and Technology; NVIDIA Corp.

**[2022]**
[Learning visual styles from audio-visual associations](https://arxiv.org/abs/2205.05072)
Tingle Li, Yichen Liu, Andrew Owens, Hang Zhao
Tsinghua University; University of Michigan; Shanghai Qi Zhi Institute

**[CVPR-2023]**
[Sound to Visual Scene Generation by Audio-to-Visual Latent Alignment](https://arxiv.org/abs/2303.17490)
<br>
**Authors:** Kim Sung-Bin, Arda Senocak, Hyunwoo Ha, Andrew Owens, Tae-Hyun Oh
<br>
**Institution:** Pohang University of Science and Technology; Korea Advanced Institute of Science and Technology; University of Michigan; Yonsei University

#### Depth Estimation
**[ICRA-2020]**
[BatVision: Learning to See 3D Spatial Layout with Two Ears](https://ieeexplore.ieee.org/abstract/document/9196934/)
<br>
**Authors:** Jesper Haahr Christensen; Sascha Hornauer; Stella X. Yu
<br>
**Institution:** Technical University of Denmark; University of California

**[ECCV-2020]**
[VISUALECHOES: Spatial Image Representation Learning Through Echolocation](https://link.springer.com/chapter/10.1007/978-3-030-58545-7_38)
<br>
**Authors:** Ruohan Gao, Changan Chen, Ziad Al-Halah, Carl Schissler, Kristen Grauman 
<br>
**Institution:** The University of Texas at Austin; Facebook Reality Lab; Facebook AI Research

**[CVPR-2021]**
[Beyond Image to Depth: Improving Depth Prediction Using Echoes](https://openaccess.thecvf.com/content/CVPR2021/html/Parida_Beyond_Image_to_Depth_Improving_Depth_Prediction_Using_Echoes_CVPR_2021_paper.html)
<br>
**Authors:** Kranti Kumar Parida, Siddharth Srivastava, Gaurav Sharma
<br>
**Institution:** Indian Institute of Technology Kanpur; Centre for Development of Advanced Computing Noida; TensorTour Inc.

**[ICASSP-2022]**
[Co-Attention-Guided Bilinear Model for Echo-Based Depth Estimation](https://ieeexplore.ieee.org/abstract/document/9746476/)
<br>
**Authors:** Go Irie, Takashi Shibata, Akisato Kimura
<br>
**Institution:** Nippon Telegraph & Telephone Corporation

**[NeurIPS-2022]**
[Learning Neural Acoustic Fields](https://arxiv.org/abs/2204.00628)
<br>
**Authors:** Andrew Luo, Yilun Du, Michael Tarr, Josh Tenenbaum, Antonio Torralba, Chuang Gan
<br>
**Institution:** Carnegie Mellon University; Massachusetts Institute of Technology; MIT-IBM Watson AI Lab

**[NeurIPS-2022]**
[Few-Shot Audio-Visual Learning of Environment Acoustics](https://arxiv.org/abs/2206.04006)
<br>
**Authors:** Sagnik Majumder, Changan Chen, Ziad Al-Halah, Kristen Grauman
<br>
**Institution:** The University of Texas at Austin; Facebook AI Research

### Audio-visual Transfer Learning
**[NeurIPS-2016]**
[SoundNet: Learning Sound Representations from Unlabeled Video](https://proceedings.neurips.cc/paper/2016/hash/7dcd340d84f762eba80aa538b0c527f7-Abstract.html)
<br>
**Authors:** Yusuf Aytar, Carl Vondrick, Antonio Torralba
<br>
**Institution:** Massachusetts Institute of Technology

**[ICCV-2019]**
[Self-Supervised Moving Vehicle Tracking With Stereo Sound](https://openaccess.thecvf.com/content_ICCV_2019/html/Gan_Self-Supervised_Moving_Vehicle_Tracking_With_Stereo_Sound_ICCV_2019_paper.html)
<br>
**Authors:** Chuang Gan, Hang Zhao, Peihao Chen, David Cox, Antonio Torralba
<br>
**Institution:** Massachusetts Institute of Technology; MIT-IBM Watson AI Lab; IBM Research AI

**[CVPR-2021]**
[There Is More Than Meets the Eye: Self-Supervised Multi-Object Detection and Tracking With Sound by Distilling Multimodal Knowledge](https://openaccess.thecvf.com/content/CVPR2021/html/Valverde_There_Is_More_Than_Meets_the_Eye_Self-Supervised_Multi-Object_Detection_CVPR_2021_paper.html?ref=https://githubhelp.com)
<br>
**Authors:** Francisco Rivera Valverde, Juana Valeria Hurtado, Abhinav Valada
<br>
**Institution:** University of Freiburg

**[AAAI-2021]**
[Enhanced Audio Tagging via Multi- to Single-Modal Teacher-Student Mutual Learning](https://ojs.aaai.org/index.php/AAAI/article/view/17280)
<br>
**Authors:** Yifang Yin, Harsh Shrivastava, Ying Zhang, Zhenguang Liu, Rajiv Ratn Shah, Roger Zimmermann
<br>
**Institution:** National University of Singapore; National University of Singapore Northwestern Polytechnical University; Zhejiang Gongshang University; Indraprastha Institute of Information Technology, Delhi

**[Interspeech-2021]**
[Knowledge Distillation from Multi-Modality to Single-Modality for Person Verification](https://www.researchgate.net/publication/354221457_Knowledge_Distillation_from_Multi-Modality_to_Single-Modality_for_Person_Verification)
<br>
**Authors:** Leying Zhang, Zhengyang Chen, Yanmin Qian
<br>
**Institution:** Shanghai Jiao Tong University

**[ICCV-2021]**
[Multimodal Knowledge Expansion](https://openaccess.thecvf.com/content/ICCV2021/html/Xue_Multimodal_Knowledge_Expansion_ICCV_2021_paper.html)
<br>
**Authors:** Zihui Xue, Sucheng Ren, Zhengqi Gao, Hang Zhao
<br>
**Institution:** Shanghai Qi Zhi Institute; UT Austin; South China University of Technology; Massachusetts Institute of Technology; Tsinghua University

**[CVPR-2021]**
[Distilling Audio-visual Knowledge by Compositional Contrastive Learning](https://openaccess.thecvf.com/content/CVPR2021/papers/Chen_Distilling_Audio-Visual_Knowledge_by_Compositional_Contrastive_Learning_CVPR_2021_paper.pdf)
<br>
**Authors:** Yanbei Chen, Yongqin Xian, A. Sophia Koepke, Ying Shan, Zeynep Akata
<br>
**Institution:** University of Tubingen; MPI for Informatics; Tencent; Max Planck Institute for Intelligent Systems

**[2022]**
[Estimating Visual Information From Audio Through Manifold Learning](https://arxiv.org/abs/2208.02337)
<br>
**Authors:** Fabrizio Pedersoli, Dryden Wiebe, Amin Banitalebi, Yong Zhang, George Tzanetakis, Kwang Moo Yi
<br>
**Institution:** University of British Columbia; Huawei Technologies Canada Co., Ltd; University of Victoria

**[DCASE-2021]**
[Audio-Visual Scene Classification Using A Transfer Learning Based Joint Optimization Strategy](https://arxiv.org/abs/2204.11420)
<br>
**Authors:** Chengxin Chen, Meng Wang, Pengyuan Zhang
<br>
**Institution:** Institute of Acoustics, CAS; University of Chinese Academy of Sciences

**[Interspeech-2021]**
[Audiovisual transfer learning for audio tagging and sound event detection](https://arxiv.org/abs/2106.05408)
<br>
**Authors:** Wim Boes, Hugo Van hamme
<br>
**Institution:** ESAT, KU Leuven

**[2023]**
[Revisiting Pre-training in Audio-Visual Learning](https://arxiv.org/abs/2302.03533)
<br>
**Authors:** Ruoxuan Feng, Wenke Xia, Di Hu
<br>
**Institution:** Hunan University; Renmin University of China

**[IJCNN-2023]**
[A Generative Approach to Audio-Visual Generalized Zero-Shot Learning: Combining Contrastive and Discriminative Techniques](https://ieeexplore.ieee.org/document/10191705)
<br>
**Authors:** Qichen Zheng, Jie Hong, Moshiur Farazi
<br>
**Institution:** Australian National University; CSIRO Data61

**[ICCV-2023]**
[Audio-Visual Class-Incremental Learning](https://arxiv.org/abs/2308.11073)
<br>
**Authors:** Weiguo Pian, Shentong Mo, Yunhui Guo, Yapeng Tian
<br>
**Institution:** The University of Texas at Dallas; Carnegie Mellon University

**[ICCV-2023]**
[Hyperbolic Audio-visual Zero-shot Learning](https://arxiv.org/abs/2308.12558)
<br>
**Authors:** Jie Hong, Zeeshan Hayder, Junlin Han, Pengfei Fang, Mehrtash Harandi, Lars Petersson
<br>
**Institution:** Australian National University; CSIRO Data61

**[CVPR-2023]**
[Multimodality Helps Unimodality: Cross-Modal Few-Shot Learning with Multimodal Models](https://ieeexplore.ieee.org/document/10205126)
<br>
**Authors:** Zhiqiu Lin, Samuel Yu, Zhiyi Kuang, Deepak Pathak, Deva Ramanan
<br>
**Institution:** Carnegie Mellon University

**[ICCV-2023]**
[Class-Incremental Grouping Network for Continual Audio-Visual Learning](https://arxiv.org/abs/2309.05281)
<br>
**Authors:** Shentong Mo, Weiguo Pian, Yapeng Tian
<br>
**Institution:** Carnegie Mellon University; University of Texas at Dallas

**[ICCV-2023]**
[Dense 2D-3D Indoor Prediction with Sound via Aligned Cross-Modal Distillation](https://arxiv.org/abs/2309.11081)
<br>
**Authors:** Heeseung Yun, Joonil Na, Gunhee Kim
<br>
**Institution:** Seoul National University

### Cross-modal Retrieval
**[2017]**
[Content-Based Video-Music Retrieval Using Soft Intra-Modal Structure Constraint](https://arxiv.org/abs/1704.06761)
<br>
**Authors:** Sungeun Hong, Woobin Im, Hyun S. Yang

**[ICCV-2017]**
[Image2song: Song Retrieval via Bridging Image Content and Lyric Words](https://openaccess.thecvf.com/content_ICCV_2017/papers/Li_Image2song_Song_Retrieval_ICCV_2017_paper.pdf)
<br>
**Authors:** Xuelong Li, Di Hu, Xiaoqiang Lu
<br>
**Institution:** Chinese Academy of Sciences; Northwestern Polytechnical University

**[CVPR-2018]**
[Seeing voices and hearing faces: Cross-modal biometric matching](https://openaccess.thecvf.com/content_cvpr_2018/papers/Nagrani_Seeing_Voices_and_CVPR_2018_paper.pdf)
<br>
**Authors:** Arsha Nagrani, Samuel Albanie, Andrew Zisserman
<br>
**Institution:** University of Oxford

**[ECCV-2018]**
[Cross-modal Embeddings for Video and Audio Retrieval](https://openaccess.thecvf.com/content_eccv_2018_workshops/w24/html/Suris_Cross-modal_Embeddings_for_Video_and_Audio_Retrieval_ECCVW_2018_paper.html)
<br>
**Authors:** Didac Suris, Amanda Duarte, Amaia Salvador, Jordi Torres, Xavier Giro-i-Nieto
<br>
**Institution:** Universitat Politecnica de Catalunya; Barcelona Supercomputing Center

**[ISM-2018]**
[Audio-Visual Embedding for Cross-Modal Music Video Retrieval through Supervised Deep CCA](https://ieeexplore.ieee.org/abstract/document/8603275/)
<br>
**Authors:** Donghuo Zeng, Yi Yu, Keizo Oyama
<br>
**Institution:** National Institute of Informatics

**[TOMCCAP-2020]**
[Deep Triplet Neural Networks with Cluster-CCA for Audio-Visual Cross-Modal Retrieval](https://dl.acm.org/doi/abs/10.1145/3387164)
<br>
**Authors:** Donghuo Zeng, Yi Yu, Keizo Oyama
<br>
**Institution:** National Institute of Informatics

**[IEEE TGRS-2020]**
[Deep Cross-Modal Image–Voice Retrieval in Remote Sensing](https://ieeexplore.ieee.org/abstract/document/9044618)
<br>
**Authors:** Yaxiong Chen, Xiaoqiang Lu, Shuai Wang
<br>
**Institution:** China University of Chinese Academy of Sciences; Chinese Academy of Sciences

**[2021]**
[Learning Explicit and Implicit Latent Common Spaces for Audio-Visual Cross-Modal Retrieval](https://arxiv.org/abs/2110.13556)
<br>
**Authors:** Donghuo Zeng, Jianming Wu, Gen Hattori, Yi Yu, Rong Xu
<br>
**Institution:** KDDI Research, Inc.; National Institute of Informatics, SOKENDAI

**[ICCV-2021]**
[Temporal Cue Guided Video Highlight Detection With Low-Rank Audio-Visual Fusion](https://ieeexplore.ieee.org/document/9710903/)
<br>
**Authors:** Qinghao Ye, Xiyue Shen, Yuan Gao, Zirui Wang, Qi Bi, Ping Li, Guang Yang
<br>
**Institution:** Hangzhou Dianzi University; University of California; East China Normal University; University of Oxford; Wuhan University; Imperial College London

**[ICMR-2024]**
[Anchor-aware Deep Metric Learning for Audio-visual Retrieval](https://arxiv.org/abs/2404.13789)
<br>
**Authors:** Donghuo Zeng, Yanan Wang, Kazushi Ikeda, Yi Yu
<br>
**Institution:**  KDDI Research, Inc.;  Hiroshima University

**[IJCAI-2022]**
[Unsupervised Voice-Face Representation Learning by Cross-Modal Prototype Contrast](https://www.ijcai.org/proceedings/2022/526)
<br>
**Authors:** Boqing Zhu, Kele Xu, Changjian Wang, Zheng Qin, Tao Sun, Huaimin Wang, Yuxing Peng
<br>
**Institution:** National University of Defense Technology

**[IEEE ISM-2022]**
[Complete Cross-triplet Loss in Label Space for Audio-visual Cross-modal Retrieval](https://arxiv.org/abs/2211.03434)
<br>
**Authors:** Donghuo Zeng, Yanan Wang, Jianming Wu, Kazushi Ikeda
<br>
**Institution:** KDDI Research, Inc.

**[IEEE SMC-2022]**
[Graph Network based Approaches for Multi-modal Movie Recommendation System](https://ieeexplore.ieee.org/document/9945488)
<br>
**Authors:** Daipayan Chakder, Prabir Mondal, Subham Raj, Sriparna Saha, Angshuman Ghosh, Naoyuki Onoe
<br>
**Institution:** Indian Institute of Technology; Sony Research

**[CVPR-2022]**
[Visual Acoustic Matching](https://arxiv.org/abs/2202.06875)
<br>
**Authors:** Changan Chen, Ruohan Gao, Paul Calamia, Kristen Grauman
<br>
**Institution:** University of Texas at Austin; Stanford University; Meta AI

**[IEEE TMM-2023]**
[Deep Cross-Modal Retrieval Between Spatial Image and Acoustic Speech](https://ieeexplore.ieee.org/document/10285477)
<br>
**Authors:** Xinyuan Qian, Wei Xue, Qiquan Zhang, Ruijie Tao, Haizhou Li
<br>
**Institution:** University of Science and Technology; Hong Kong University of Science and Technology; University of New South Wales; National University of Singapore; The Chinese University of Hong Kong-Shenzhen

[Back to Top](#top)

## Audio-visual Collaboration

### Audio-visual Representation Learning
**[ICCV-2017]**
[Look, Listen and Learn](https://openaccess.thecvf.com/content_iccv_2017/html/Arandjelovic_Look_Listen_and_ICCV_2017_paper.html)
<br>
**Authors:** Relja Arandjelovic, Andrew Zisserman
<br>
**Institution:** Google Inc.; University of Oxford

**[NeurIPS-2018]**
[Cooperative Learning of Audio and Video Models from Self-Supervised Synchronization](https://proceedings.neurips.cc/paper/2018/hash/c4616f5a24a66668f11ca4fa80525dc4-Abstract.html)
<br>
**Authors:** Bruno Korbar, Du Tran, Lorenzo Torresani
<br>
**Institution:** Dartmouth College; Facebook Research

**[NeurIPS-2020]**
[Learning Representations from Audio-Visual Spatial Alignment](https://proceedings.neurips.cc/paper/2020/hash/328e5d4c166bb340b314d457a208dc83-Abstract.html)
<br>
**Authors:** Pedro Morgado, Yi Li, Nuno Nvasconcelos
<br>
**Institution:** University of California

**[NeurIPS-2020]**
[Self-Supervised Learning by Cross-Modal Audio-Video Clustering](https://proceedings.neurips.cc/paper/2020/hash/6f2268bd1d3d3ebaabb04d6b5d099425-Abstract.html)
<br>
**Authors:** Humam Alwassel, Dhruv Mahajan, Bruno Korbar, Lorenzo Torresani, Bernard Ghanem, Du Tran
<br>
**Institution:** King Abdullah University of Science and Technology; Facebook AI Research

**[NeurIPS-2020]**
[Labelling Unlabelled Videos From Scratch With Multi-Modal Self-Supervision](https://proceedings.neurips.cc/paper/2020/hash/31fefc0e570cb3860f2a6d4b38c6490d-Abstract.html)
<br>
**Authors:** Yuki Asano, Mandela Patrick, Christian Rupprecht, Andrea Vedaldi
<br>
**Institution:** University of Oxford; Facebook AI Research

**[CVPR-2021]**
[Audio-Visual Instance Discrimination with Cross-Modal Agreement](https://openaccess.thecvf.com/content/CVPR2021/html/Morgado_Audio-Visual_Instance_Discrimination_with_Cross-Modal_Agreement_CVPR_2021_paper.html)
<br>
**Authors:** Pedro Morgado, Nuno Vasconcelos, Ishan Misra
<br>
**Institution:** University of California San Diego; Facebook AI Research

**[CVPR-2021]**
[Robust Audio-Visual Instance Discrimination](https://openaccess.thecvf.com/content/CVPR2021/html/Morgado_Robust_Audio-Visual_Instance_Discrimination_CVPR_2021_paper.html)
<br>
**Authors:** Pedro Morgado, Ishan Misra, Nuno Vasconcelos
<br>
**Institution:** University of California San Diego; Facebook AI Research

**[2021]**
[Unsupervised Sound Localization via Iterative Contrastive Learning](https://arxiv.org/abs/2104.00315)
<br>
**Authors:** Yan-Bo Lin, Hung-Yu Tseng, Hsin-Ying Lee, Yen-Yu Lin, Ming-Hsuan Yang
<br>
**Institution:** National Yang Ming Chiao Tung University; University of California; Snap Inc.; Google Research

**[ICCV-2021]**
[Multimodal Clustering Networks for Self-Supervised Learning From Unlabeled Videos](https://openaccess.thecvf.com/content/ICCV2021/html/Chen_Multimodal_Clustering_Networks_for_Self-Supervised_Learning_From_Unlabeled_Videos_ICCV_2021_paper.html)
<br>
**Authors:** Brian Chen, Andrew Rouditchenko, Kevin Duarte, Hilde Kuehne, Samuel Thomas, Angie Boggust, Rameswar Panda, Brian Kingsbury, Rogerio Feris, David Harwath, James Glass, Michael Picheny, Shih-Fu Chang
<br>
**Institution:** Columbia University; Massachusetts Institute of Technology; University of Central Florida; Goethe University Frankfurt; IBM Research AI; MIT-IBM Watson AI Lab; The University of Texas at Austin; NYU-Courant CS & CDS

**[2021]**
[OPT: Omni-Perception Pre-Trainer for Cross-Modal Understanding and Generation](https://arxiv.org/abs/2107.00249)
<br>
**Authors:** Jing Liu, Xinxin Zhu, Fei Liu, Longteng Guo, Zijia Zhao, Mingzhen Sun, Weining Wang, Hanqing Lu, Shiyu Zhou, Jiajun Zhang, Jinqiao Wang
<br>
**Institution:** Chinese Academy of Sciences

**[NeurIPS-2021]**
[VATT: Transformers for Multimodal Self-Supervised Learning from Raw Video, Audio and Text](https://proceedings.neurips.cc/paper/2021/hash/cb3213ada48302953cb0f166464ab356-Abstract.html)
<br>
**Authors:** Hassan Akbari, Liangzhe Yuan, Rui Qian, Wei-Hong Chuang, Shih-Fu Chang, Yin Cui, Boqing Gong
<br>
**Institution:** Columbia University; Google Inc.; Cornell University

**[2021]**
[Audio-visual Representation Learning for Anomaly Events Detection in Crowds](https://arxiv.org/abs/2110.14862)
<br>
**Authors:** Junyu Gao, Maoguo Gong, Xuelong Li
<br>
**Institution:** Xidian University; Northwestern Polytechnical University

**[ICASSP-2022]**
[Audioclip: Extending Clip to Image, Text and Audio](https://ieeexplore.ieee.org/abstract/document/9747631/)
<br>
**Authors:** Andrey Guzhov, Federico Raue, Jorn Hees, Andreas Dengel
<br>
**Institution:** Germany TU Kaiserslautern; Deutsches Forschungszentrum für Künstliche Intelligenz GmbH

**[CVPR-2022]**
[MERLOT Reserve: Neural Script Knowledge Through Vision and Language and Sound](https://openaccess.thecvf.com/content/CVPR2022/html/Zellers_MERLOT_Reserve_Neural_Script_Knowledge_Through_Vision_and_Language_and_CVPR_2022_paper.html)
<br>
**Authors:** Rowan Zellers, Jiasen Lu, Ximing Lu, Youngjae Yu, Yanpeng Zhao, Mohammadreza Salehi, Aditya Kusupati, Jack Hessel, Ali Farhadi, Yejin Choi
<br>
**Institution:** University of Washington; Allen Institute for Artificial Intelligence; University of Edinburgh

**[2022]**
[Probing Visual-Audio Representation for Video Highlight Detection via Hard-Pairs Guided Contrastive Learning](https://arxiv.org/abs/2206.10157)
<br>
**Authors:** Shuaicheng Li, Feng Zhang, Kunlin Yang, Lingbo Liu, Shinan Liu, Jun Hou, Shuai Yi
<br>
**Institution:** Sensetime Research; The Hong Kong Polytechnic University

**[NeurIPS-2022]**
[Non-Linguistic Supervision for Contrastive Learning of Sentence Embeddings](https://arxiv.org/abs/2209.09433)
<br>
**Authors:** Yiren Jian, Chongyang Gao, Soroush Vosoughi
<br>
**Institution:** Dartmouth College; Northwestern University

**[IEEE TMM-2022]**
[Multimodal Information Bottleneck: Learning Minimal Sufficient Unimodal and Multimodal Representations](https://arxiv.org/abs/2210.17444)
<br>
**Authors:** Sijie Mai, Ying Zeng, Haifeng Hu
<br>
**Institution:** Sun Yat-sen University;  National Natural Science Foundation of China

**[CVPR-2022]**
[Audiovisual Generalised Zero-shot Learning with Cross-modal Attention and Language](https://ieeexplore.ieee.org/document/9880403)
<br>
**Authors:** Otniel-Bogdan Mercea, Lukas Riesch, A. Sophia Koepke, Zeynep Akata
<br>
**Institution:** University of Tübingen; Robert Bosch GmbH; Max Planck Institute

**[CVPRW-2022]**
[Multi-task Learning for Human Affect Prediction with Auditory–Visual Synchronized Representation](https://ieeexplore.ieee.org/document/9856974)
<br>
**Authors:** Euiseok Jeong;, Geesung Oh, Sejoon Lim
<br>
**Institution:** Kookmin University

**[CVPR-2023]**
[Vision Transformers are Parameter-Efficient Audio-Visual Learners](https://arxiv.org/abs/2212.07983)
<br>
**Authors:** Yan-Bo Lin, Yi-Lin Sung, Jie Lei, Mohit Bansal, Gedas Bertasius
<br>
**Institution:** The University of North Carolina at Chapel Hill

**[CVPR-2022]**
[Audio-visual Generalised Zero-shot Learning with Cross-modal Attention and Language](https://arxiv.org/abs/2203.03598)
<br>
**Authors:** Otniel-Bogdan Mercea, Lukas Riesch, A. Sophia Koepke, Zeynep Akata
<br>
**Institution:** University of Tubingen; Robert Bosch GmbH; Max Planck Institute

**[ECCV-2022]**
[Temporal and cross-modal attention for audio-visual zero-shot learning](https://arxiv.org/abs/2207.09966)
<br>
**Authors:** Otniel-Bogdan Mercea, Thomas Hummel, A. Sophia Koepke, Zeynep Akata
<br>
**Institution:** University of Tuebingen; Max Planck Institute

**[NeurIPS-2022]**
[u-HuBERT: Unified Mixed-Modal Speech Pretraining And Zero-Shot Transfer to Unlabeled Modality](https://arxiv.org/abs/2207.07036)
<br>
**Authors:** Wei-Ning Hsu, Bowen Shi
<br>
**Institution:** Meta AI

**[NeurIPS-2022]**
[Scaling Multimodal Pre-Training via Cross-Modality Gradient Harmonization](https://arxiv.org/abs/2211.02077)
<br>
**Authors:** Junru Wu, Yi Liang, Feng Han, Hassan Akbari, Zhangyang Wang, Cong Yu
<br>
**Institution:** Texas A&M University; Google Research; University of Texas at Austin; Celonis Inc.

**[AAAI-2023]**
[Self-Supervised Audio-Visual Representation Learning with Relaxed Cross-Modal Synchronicity](https://arxiv.org/abs/2111.05329)
<br>
**Authors:** Pritam Sarkar, Ali Etemad
<br>
**Institution:** Queen’s University; Vector Institute

**[ICLR-2023]**
[Contrastive Audio-Visual Masked Autoencoder](https://arxiv.org/abs/2210.07839)
<br>
**Authors:** Yuan Gong, Andrew Rouditchenko, Alexander H. Liu, David Harwath, Leonid Karlinsky, Hilde Kuehne, James R. Glass
<br>
**Institution:** Massachusetts Institute of Technology; The University of Texas at Austin; MIT-IBM Watson AI Lab; Goethe University Frankfurt

**[ICLR-2023]**
[Jointly Learning Visual and Auditory Speech Representations from Raw Data](https://arxiv.org/abs/2212.06246)
<br>
**Authors:** Alexandros Haliassos, Pingchuan Ma, Rodrigo Mira, Stavros Petridis, Maja Pantic
<br>
**Institution:** Imperial College London; Meta AI

**[WACV-2023]**
[Audio Representation Learning by Distilling Video as Privileged Information](https://ieeexplore.ieee.org/document/10041728)
<br>
**Authors:** Amirhossein Hajavi, Ali Etemad
<br>
**Institution:** Queen's University, Canada


**[2023]**
[AV-data2vec: Self-supervised Learning of Audio-Visual Speech Representations with Contextualized Target Representations](https://arxiv.org/abs/2302.06419)
<br>
**Authors:** Jiachen Lian, Alexei Baevski, Wei-Ning Hsu, Michael Auli
<br>
**Institution:** University of California; Meta AI

**[AAAI-2023]**
[Audio-Visual Contrastive Learning with Temporal Self-Supervision](https://arxiv.org/abs/2302.07702)
<br>
**Authors:** Simon Jenni, Alexander Black, John Collomosse
<br>
**Institution:** Adobe Research; University of Surrey

**[CVPR-2023]**
[ImageBind One Embedding Space to Bind Them All](https://ieeexplore.ieee.org/document/10203733)
<br>
**Authors:** Rohit Girdhar, Alaaeldin El-Nouby, Zhuang Liu, Mannat Singh, Kalyan Vasudev Alwala, Armand Joulin, Ishan Misra
<br>
**Institution:** Meta AI

**[NeurIPS-2023]**
[Cross-modal Prompts: Adapting Large Pre-trained Models for Audio-Visual Downstream Tasks](https://arxiv.org/abs/2311.05152)
<br>
**Authors:** Haoyi Duan, Yan Xia, Mingze Zhou, Li Tang, Jieming Zhu, Zhou Zhao
<br>
**Institution:** Zhejiang University; Shanghai Artificial Intelligence Laboratory; Huawei Noah’s Ark Lab

**[WACV-2024]**
[OmniVec: Learning robust representations with cross modal sharing](https://arxiv.org/abs/2311.05709)
<br>
**Authors:** Siddharth Srivastava, Gaurav Sharma
<br>
**Institution:** TensorTour Inc.

### Audio-visual Localization

#### Sound Localization in Videos
**[ECCV-2018]**
[Objects that Sound](https://openaccess.thecvf.com/content_ECCV_2018/html/Relja_Arandjelovic_Objects_that_Sound_ECCV_2018_paper.html)
<br>
**Authors:** Relja Arandjelovic, Andrew Zisserman
<br>
**Institution:** Google Inc.; University of Oxford

**[ECCV-2018]**
[Audio-Visual Scene Analysis with Self-Supervised Multisensory Features](https://openaccess.thecvf.com/content_ECCV_2018/html/Andrew_Owens_Audio-Visual_Scene_Analysis_ECCV_2018_paper.html)
<br>
**Authors:** Andrew Owens, Alexei A. Efros
<br>
**Institution:** University of California, Berkeley

**[ECCV-2018]**
[The Sound of Pixels](https://openaccess.thecvf.com/content_ECCV_2018/html/Hang_Zhao_The_Sound_of_ECCV_2018_paper.html)
<br>
**Authors:** Hang Zhao, Chuang Gan, Andrew Rouditchenko, Carl Vondrick, Josh McDermott, Antonio Torralba
<br>
**Institution:** Massachusetts Institute of Technology; MIT-IBM Watson AI Lab; Columbia University

**[ICASSP-2019]**
[Self-supervised Audio-visual Co-segmentation](https://ieeexplore.ieee.org/abstract/document/8682467)
<br>
**Authors:** Andrew Rouditchenko, Hang Zhao, Chuang Gan, Josh McDermott, Antonio Torralba
<br>
**Institution:** Massachusetts Institute of Technology; MIT-IBM Watson AI Lab

**[ICCV-2019]**
[The Sound of Motions](https://openaccess.thecvf.com/content_ICCV_2019/html/Zhao_The_Sound_of_Motions_ICCV_2019_paper.html)
<br>
**Authors:** Hang Zhao, Chuang Gan, Wei-Chiu Ma, Antonio Torralba
<br>
**Institution:** Massachusetts Institute of Technology; MIT-IBM Watson AI Lab

**[CVPR-2019]**
[Deep Multimodal Clustering for Unsupervised Audiovisual Learning](https://openaccess.thecvf.com/content_CVPR_2019/html/Hu_Deep_Multimodal_Clustering_for_Unsupervised_Audiovisual_Learning_CVPR_2019_paper.html)
<br>
**Authors:** Di Hu, Feiping Nie, Xuelong Li
<br>
**Institution:** Northwestern Polytechnical University

**[CVPR-2021]**
[Localizing Visual Sounds the Hard Way](https://openaccess.thecvf.com/content/CVPR2021/html/Chen_Localizing_Visual_Sounds_the_Hard_Way_CVPR_2021_paper.html)
<br>
**Authors:** Honglie Chen, Weidi Xie, Triantafyllos Afouras, Arsha Nagrani, Andrea Vedaldi, Andrew Zisserman
<br>
**Institution:** University of Oxford

**[IEEE TPAMI-2021]**
[Class-aware Sounding Objects Localization via Audiovisual Correspondence](https://ieeexplore.ieee.org/abstract/document/9662191/)
<br>
**Authors:** Di Hu, Yake Wei, Rui Qian, Weiyao Lin, Ruihua Song, Ji-Rong Wen
<br>
**Institution:** Renmin University of China; Shanghai Jiao Tong University

**[IEEE TPAMI-2021]**
[Learning to Localize Sound Sources in Visual Scenes: Analysis and Applications](https://ieeexplore.ieee.org/abstract/document/8894565/)
<br>
**Authors:** Arda Senocak, Tae-Hyun Oh, Junsik Kim, Ming-Hsuan Yang, In So Kweon
<br>
**Institution:** Korea Advanced Institute of Science and Technology; Pohang University of Science and Technology; University of California

**[CVPR-2022]**
[Mix and Localize: Localizing Sound Sources in Mixtures](https://openaccess.thecvf.com/content/CVPR2022/html/Hu_Mix_and_Localize_Localizing_Sound_Sources_in_Mixtures_CVPR_2022_paper.html)
<br>
**Authors:** Xixi Hu, Ziyang Chen, Andrew Owens
<br>
**Institution:** University of Michigan; The University of Texas at Austin

**[ECCV-2022]**
[Audio-Visual Segmentation](https://arxiv.org/abs/2207.05042)
<br>
**Authors:** Jinxing Zhou, Jianyuan Wang, Jiayi Zhang, Weixuan Sun, Jing Zhang, Stan Birchfield, Dan Guo, Lingpeng Kong, Meng Wang, Yiran Zhong
<br>
**Institution:** Hefei University of Technology; SenseTime Research; Australian National University; Beihang University; NVIDIA; The University of Hong Kong; 7Shanghai Artificial Intelligence Laboratory

**[2022]**
[Egocentric Deep Multi-Channel Audio-Visual Active Speaker Localization](https://arxiv.org/abs/2201.01928)
<br>
**Authors:** Hao Jiang, Calvin Murdock, Vamsi Krishna Ithapu
<br>
**Institution:** Meta Reality Labs

**[ACM MM-2022]**
[Exploiting Transformation Invariance and Equivariance for Self-supervised Sound Localisation](https://arxiv.org/abs/2206.12772)
<br>
**Authors:** Jinxiang Liu, Chen Ju, Weidi Xie, Ya Zhang
<br>
**Institution:** Shanghai Jiao Tong University; Shanghai AI Laboratory

**[CVPR-2022]**
[Self-Supervised Predictive Learning: A Negative-Free Method for Sound Source Localization in Visual Scenes](https://arxiv.org/abs/2203.13412v1)
<br>
**Authors:** Zengjie Song, Yuxi Wang, Junsong Fan, Tieniu Tan, Zhaoxiang Zhang
<br>
**Institution:** Chinese Academy of Science; University of Chinese Academy of Sciences

**[CVPR-2022]**
[Self-supervised object detection from audio-visual correspondence](https://ieeexplore.ieee.org/document/9879445/)
<br>
**Authors:** Triantafyllos Afouras; Yuki M. Asano; Francois Fagan; Andrea Vedaldi; Florian Metze
<br>
**Institution:** University of Oxford; University of Amsterdam; Meta AI

**[EUSIPCO-2022]**
[Visually Assisted Self-supervised Audio Speaker Localization and Tracking](https://ieeexplore.ieee.org/document/9909535/)
<br>
**Authors:** Jinzheng Zhao, Peipei Wu, Shidrokh Goudarzi, Xubo Liu, Jianyuan Sun, Yong Xu, Wenwu Wang
<br>
**Institution:** University of Surrey; Tencent AI Lab, Bellevue

**[CVPR-2022]**
[Mix and Localize: Localizing Sound Sources in Mixtures](https://arxiv.org/abs/2211.15058)
<br>
**Authors:** Xixi Hu, Ziyang Chen, Andrew Owens
<br>
**Institution:** University of Michigan; The University of Texas at Austin

**[ICASSP-2023]**
[MarginNCE: Robust Sound Localization with a Negative Margin](https://arxiv.org/abs/2211.01966)
<br>
**Authors:** Sooyoung Park, Arda Senocak, Joon Son Chung
<br>
**Institution:** Korea Advanced Institute of Science and Technology; Electronics and Telecommunications Research Institute, South Korea

**[IEEE TMM-2022]**
[Cross modal video representations for weakly supervised active speaker localization](https://ieeexplore.ieee.org/document/9991097)
<br>
**Authors:** Rahul Sharma, Krishna Somandepalli, Shrikanth Narayanan
<br>
**Institution:** University of Southern California; Google Inc.

**[NeurIPS-2022]**
[A Closer Look at Weakly-Supervised Audio-Visual Source Localization](https://arxiv.org/abs/2209.09634)
<br>
**Authors:** Shentong Mo, Pedro Morgado
<br>
**Institution:** Carnegie Mellon University; University of Wisconsin-Madison

**[AAAI-2022]**
[Visual Sound Localization in the Wild by Cross-Modal Interference Erasing](https://arxiv.org/abs/2202.06406)
<br>
**Authors:** Xian Liu, Rui Qian, Hang Zhou, Di Hu, Weiyao Lin, Ziwei Liu, Bolei Zhou, Xiaowei Zhou
<br>
**Institution:** The Chinese University of Hong Kong; Zhejiang University; Shanghai Jiao Tong University; Renmin University of China; Nanyang Technological University

**[ECCV-2022]**
[Sound Localization by Self-Supervised Time Delay Estimation](https://arxiv.org/abs/2204.12489)
<br>
**Authors:** Ziyang Chen, David F. Fouhey, Andrew Owens
<br>
**Institution:** University of Michigan

**[IEEE/ACM TASLP-2023]**
[Audio-Visual Cross-Attention Network for Robotic Speaker Tracking](https://ieeexplore.ieee.org/document/9968308/)
<br>
**Authors:** Xinyuan Qian, Zhengdong Wang, Jiadong Wang, Guohui Guan, Haizhou Li
<br>
**Institution:** University of Science and Technology Beijing; Chinese University of Hong Kong; Shenzhen Research Institute of Big dataNational University of Singapore; Univeristy of California at Berkeley; University of Bremen

**[WACV-2023]**
[Hear The Flow: Optical Flow-Based Self-Supervised Visual Sound Source Localization](https://arxiv.org/abs/2211.03019)
<br>
**Authors:** Dennis Fedorishin, Deen Dayal Mohan, Bhavin Jawade, Srirangaraj Setlur, Venu Govindaraju
<br>
**Institution:** University at Buffalo

**[WACV-2023]**
[Exploiting Visual Context Semantics for Sound Source Localization](https://ieeexplore.ieee.org/document/10030749/)
<br>
**Authors:** Xinchi Zhou, Dongzhan Zhou, Di Hu, Hang Zhou, Wanli Ouyang
<br>
**Institution:** The University of Sydney; Renmin University of China; Baidu Inc.

**[2023]**
[Audio-Visual Segmentation with Semantics](https://arxiv.org/abs/2301.13190)
<br>
**Authors:** Jinxing Zhou, Xuyang Shen, Jianyuan Wang, Jiayi Zhang, Weixuan Sun, Jing Zhang, Stan Birchfield, Dan Guo, Lingpeng Kong, Meng Wang, Yiran Zhong
<br>
**Institution:** Hefei University of Technology; SenseTime Research; University of Oxford; Australian National University; Beihang University; NVIDIA; The University of Hong Kong; Shanghai Artificial Intelligence Laboratory

**[CVPR-2023]**
[Learning Audio-Visual Source Localization via False Negative Aware Contrastive Learning](https://arxiv.org/abs/2303.11302)
<br>
**Authors:** Weixuan Sun, Jiayi Zhang, Jianyuan Wang, Zheyuan Liu, Yiran Zhong, Tianpeng Feng, Yandong Guo, Yanhao Zhang, Nick Barnes
<br>
**Institution:** Australian National University; Beihang University; The University of Oxford; Shanghai AI Lab; OPPO Research Institute

**[CVPR-2023]**
[Egocentric Audio-Visual Object Localization](https://arxiv.org/abs/2303.13471)
<br>
**Authors:** Chao Huang, Yapeng Tian, Anurag Kumar, Chenliang Xu
<br>
**Institution:** University of Rochester; Meta Reality Labs Research

**[CVPR-2023]**
[Learning Audio-Visual Source Localization via False Negative Aware Contrastive Learning](https://arxiv.org/abs/2303.11302)
<br>
**Authors:** Weixuan Sun, Jiayi Zhang, Jianyuan Wang, Zheyuan Liu, Yiran Zhong, Tianpeng Feng, Yandong Guo, Yanhao Zhang, Nick Barnes
<br>
**Institution:** Australian National University; Beihang University; The University of Oxford; Shanghai AI Lab; OPPO Research Institute

**[CVPR-2023]**
[Audio-Visual Grouping Network for Sound Localization from Mixtures](https://arxiv.org/abs/2303.17056)
<br>
**Authors:** Shentong Mo, Yapeng Tian
<br>
**Institution:** Carnegie Mellon University; University of Texas at Dallas

**[ICASSP-2023]**
[Flowgrad: Using Motion for Visual Sound Source Localization](https://ieeexplore.ieee.org/document/10094965)
<br>
**Authors:** Rajsuryan Singh, Pablo Zinemanas, Xavier Serra, Juan Pablo Bello, Magdalena Fuentes
<br>
**Institution:** Universitat Pompeu Fabra; New York University

**[ACM MM-2023]**
[Audio-visual segmentation, sound localization, semantic-aware sounding objects localization](https://arxiv.org/abs/2307.16620)
<br>
**Authors:** Chen Liu, Peike Li, Xingqun Qi, Hu Zhang, Lincheng Li, Dadong Wang, Xin Yu
<br>
**Institution:** University of Technology Sydney; The University of Queensland; Futureverse; The Hong Kong University of Science and Technology; CSIRO DATA61; Netease Fuxi AI Lab

**[ACM MM-2023]**
[Induction Network: Audio-Visual Modality Gap-Bridging for Self-Supervised Sound Source Localization](https://arxiv.org/abs/2308.04767)
<br>
**Authors:** Tianyu Liu, Peng Zhang, Wei Huang, Yufei Zha, Tao You, Yanning Zhang
<br>
**Institution:** Northwestern Polytechnical University; Nanchang University

**[ACM MM-2023]**
[Audio-Visual Spatial Integration and Recursive Attention for Robust Sound Source Localization](https://arxiv.org/abs/2308.06087)
<br>
**Authors:** Sung Jin Um, Dongjin Kim, Jung Uk Kim
<br>
**Institution:** Kyung Hee University

**[IJCAI-2023]**
[Discovering Sounding Objects by Audio Queries for Audio Visual Segmentation](https://arxiv.org/abs/2309.09501)
<br>
**Authors:** Shaofei Huang, Han Li, Yuqing Wang, Hongji Zhu, Jiao Dai, Jizhong Han, Wenge Rong, Si Liu
<br>
**Institution:** Chinese Academy of Sciences; University of Chinese Academy of Sciences;  Beihang University; Alibaba Group

**[ICCV-2023]**
[Sound Source Localization is All about Cross-Modal Alignment](https://arxiv.org/abs/2309.10724)
<br>
**Authors:** Arda Senocak, Hyeonggon Ryu, Junsik Kim, Tae-Hyun Oh, Hanspeter Pfister, Joon Son Chung
<br>
**Institution:** Korea Advanced Institute of Science and Technology; Harvard University; Pohang University of Science and Technology; Yonsei University

**[ICCV-2023]**
[Multimodal Variational Auto-encoder based Audio-Visual Segmentation](https://arxiv.org/abs/2310.08303)
<br>
**Authors:** Yuxin Mao, Jing Zhang, Mochu Xiang, Yiran Zhong, Yuchao Dai
<br>
**Institution:** Northwestern Polytechnical University; Shaanxi Key Laboratory of Information Acquisition and Processing; Australian National University; Shanghai AI Laboratory

**[WACV-2024]**
[Can CLIP Help Sound Source Localization?](https://arxiv.org/abs/2311.04066)
<br>
**Authors:** Sooyoung Park, Arda Senocak, Joon Son Chung
<br>
**Institution:** Korea Advanced Institute of Science and Technology; Electronics and Telecommunications Research Institute

**[NeurIPS-2023]**
[Dual Mean-Teacher: An Unbiased Semi-Supervised Framework for Audio-Visual Source Localization](https://arxiv.org/abs/2403.03145)
<br>
**Authors:** Yuxin Guo, Shijie Ma, Hu Su, Zhiqing Wang, Yuhao Zhao, Wei Zou，Siyang Sun, Yun Zheng
<br>
**Institution:** School of Artificial Intelligence, University of Chinese Academy of Sciences, Beijing, China; State Key Laboratory of Multimodal Artificial Intelligence Systems (MAIS), Institute of Automation of Chinese Academy of Sciences, Beijing, China; DAMOAcademy, Alibaba Group 

**[ICASSP-2024]**
[Cross Pseudo-Labeling for Semi-Supervised Audio-Visual Source Localization](https://arxiv.org/abs/2403.03095)
<br>
**Authors:** Yuxin Guo, Shijie Ma, Yuhao Zhao, Hu Su, Wei Zou
<br>
**Institution:** School of Artificial Intelligence, University of Chinese Academy of Sciences; State Key Laboratory of Multimodal Artificial Intelligence Systems (MAIS);  Institute of Automation of Chinese Academy of Sciences

**[CVPR-2024]**
[Audio-Visual Segmentation via Unlabeled Frame Exploitation](https://arxiv.org/abs/2403.11074)
<br>
**Authors:** Jinxiang Liu, Yikun Liu, Fei Zhang, Chen Ju, Ya Zhang, Yanfeng Wang
<br>
**Institution:** Cooperative Medianet Innovation Center, Shanghai Jiao Tong University; Shanghai AI Laboratory

#### Audio-visual Saliency Detection
**[2019]**
[DAVE: A Deep Audio-Visual Embedding for Dynamic Saliency Prediction](https://arxiv.org/abs/1905.10693)
<br>
**Authors:** Hamed R. Tavakoli, Ali Borji, Esa Rahtu, Juho Kannala
<br>
**Institution:** Aalto University; Tampere University

**[CVPR-2020]**
[STAViS: Spatio-Temporal AudioVisual Saliency Network](https://openaccess.thecvf.com/content_CVPR_2020/html/Tsiami_STAViS_Spatio-Temporal_AudioVisual_Saliency_Network_CVPR_2020_paper.html)
<br>
**Authors:** Antigoni Tsiami, Petros Koutras, Petros Maragos
<br>
**Institution:** National Technical University of Athens

**[IEEE TIP-2020]**
[A Multimodal Saliency Model for Videos With High Audio-visual Correspondence](https://ieeexplore.ieee.org/abstract/document/8962278/)
<br>
**Authors:** 
Xiongkuo Min, Guangtao Zhai, Jiantao Zhou, Xiao-Ping Zhang, Xiaokang Yang, Xinping Guan
<br>
**Institution:** Shanghai Jiao Tong University; University of Macau; Ryerson University

**[IROS-2021]**
[ViNet: Pushing the limits of Visual Modality for Audio-Visuav Saliency Prediction](https://ieeexplore.ieee.org/abstract/document/9635989)
<br>
**Authors:** Samyak Jain, Pradeep Yarlagadda, Shreyank Jyoti, Shyamgopal Karthik, Ramanathan Subramanian, Vineet Gandhi
<br>
**Institution:** International Institute for Information Technology; University of Canberra 

**[CVPR-2021]**
[From Semantic Categories to Fixations: A Novel Weakly-Supervised Visual-Auditory Saliency Detection Approach](https://openaccess.thecvf.com/content/CVPR2021/html/Wang_From_Semantic_Categories_to_Fixations_A_Novel_Weakly-Supervised_Visual-Auditory_Saliency_CVPR_2021_paper.html)
<br>
**Authors:** Guotao Wang, Chenglizhao Chen, Deng-Ping Fan, Aimin Hao, Hong Qin
<br>
**Institution:** Beihang University; Qingdao University; Chinese Academy of Medical Sciences

**[ICME-2021]**
[Lavs: A Lightweight Audio-Visual Saliency Prediction Model](https://ieeexplore.ieee.org/document/9428415)
<br>
**Authors:** Dandan Zhu; Defang Zhao; Xiongkuo Min; Tian Han; Qiangqiang Zhou; Shaobo Yu; Yongqing Chen; Guangtao Zhai; Xiaokang Yang
<br>
**Institution:** Shanghai Jiao Tong University; Tongji University; Stevens Institute of Technology; Jiangxi Normal University; East China Normal University; Hainan University

**[2022]**
[A Comprehensive Survey on Video Saliency Detection with Auditory Information: the Audio-visual Consistency Perceptual is the Key!](https://arxiv.org/abs/2206.13390)
<br>
**Authors:** Chenglizhao Chen, Mengke Song, Wenfeng Song, Li Guo, Muwei Jian
<br>
**Institution:** China University of Petroleum; Shandong University of Finance and Economics; Beijing Information Science and Technology University

**[TOMCCAP-2022]**
[PAV-SOD: A New Task Towards Panoramic Audiovisual Saliency Detection](https://dl.acm.org/doi/abs/10.1145/3565267)
<br>
**Authors:** Yi Zhang, Fang-Yi Chao, Wassim Hamidouche, Olivier Deforges
<br>
**Institution:** University Rennes; Institut National des Sciences Appliquées Rennes; Centre national de la recherche scientifique; Trinity College Dublin

**[CVPR-2023]**
[CASP-Net: Rethinking Video Saliency Prediction from an Audio-VisualConsistency Perceptual Perspective](https://arxiv.org/abs/2303.06357)
<br>
**Authors:** Junwen Xiong, Ganglai Wang, Peng Zhang, Wei Huang, Yufei Zha, Guangtao Zhai
<br>
**Institution:** Northwestern Polytechnical University; Ningbo Institute of Northwestern Polytechnical University; Nanchang University; Shanghai Jiao Tong University

**[CVPR-2023]**
[Self-Supervised Video Forensics by Audio-Visual Anomaly Detection](https://arxiv.org/abs/2301.01767)
<br>
**Authors:** Chao Feng, Ziyang Chen, Andrew Owens
<br>
**Institution:** University of Michigan

**[CVPR-2023]**
[CASP-Net: Rethinking Video Saliency Prediction From an Audio-Visual Consistency Perceptual Perspective](https://openaccess.thecvf.com/content/CVPR2023/papers/Xiong_CASP-Net_Rethinking_Video_Saliency_Prediction_From_an_Audio-Visual_Consistency_Perceptual_CVPR_2023_paper.pdf)
<br>
**Authors:** Junwen Xiong, Ganglai Wang, Peng Zhang, Wei Huang, Yufei Zha, Guangtao Zhai
<br>
**Institution:** Northwestern Polytechnical University; Ningbo Institute of Northwestern Polytechnical University; Nanchang University; Shanghai Jiao Tong University

**[IJCNN-2023]**
[3DSEAVNet: 3D-Squeeze-and-Excitation Networks for Audio-Visual Saliency Prediction](https://ieeexplore.ieee.org/document/10191383)
<br>
**Authors:** Silong Liang, Chunxiao Li, Naying Cui, Minghui Sun, Hao Xue
<br>
**Institution:** JiLin University

**[IEEE TMM-2023]**
[SVGC-AVA: 360-Degree Video Saliency Prediction with Spherical Vector-Based Graph Convolution and Audio-Visual Attention](https://ieeexplore.ieee.org/document/10224292)
<br>
**Authors:** Qin Yang, Yuqi Li, Chenglin Li, Hao Wang, Sa Yan, Li Wei, Wenrui Dai, Junni Zou, Hongkai Xiong, Pascal Frossard
<br>
**Institution:** Shanghai Jiao Tong University; École Polytechnique Fédérale de Lausanne

**[TMM-2023]**
[Unified Audio-Visual Saliency Model for Omnidirectional Videos With Spatial Audio](https://ieeexplore.ieee.org/abstract/document/10109890)
<br>
**Authors:** Dandan Zhu, Kaiwei Zhang, Nana Zhang, Qiangqiang Zhou, Xiongkuo Min, Guangtao Zhai, Xiaokang Yang
<br>
**Institution:** Institute of AI Education, Shanghai, East China Normal University;Institute of Image Communication and Network Engineering, Shanghai Jiao Tong University; School of Computer Science and Technology, Donghua University; School of Software, Jiangxi Normal University; MoE Key Lab of Artificial Intelligence, AI Institute, Shanghai Jiao Tong University

**[CVPR-2024]**
[DiffSal: Joint Audio and Video Learning for Diffusion Saliency Prediction](https://arxiv.org/abs/2403.01226)
<br>
**Authors:** Junwen Xiong, Peng Zhang, Tao You, Chuanyue Li, Wei Huang, Yufei Zha
<br>
**Institution:** Northwestern Polytechnical University; Ningbo Institute of Northwestern Polytechnical University; Nanchang University

#### Audio-visual Navigation
**[ECCV-2020]**
[SoundSpaces: Audio-Visual Navigation in 3D Environments](https://link.springer.com/chapter/10.1007/978-3-030-58539-6_2)
<br>
**Authors:** Changan Chen, Unnat Jain, Carl Schissler, Sebastia Vicenc Amengual Gari, Ziad Al-Halah, Vamsi Krishna Ithapu, Philip Robinson, Kristen Grauman
<br>
**Institution:** The University of Texas at Austin; University of Illinois at Urbana-Champaign; Facebook Reality Labs; Facebook AI Research 

**[ICRA-2020]**
[Look, Listen, and Act: Towards Audio-Visual Embodied Navigation](https://ieeexplore.ieee.org/abstract/document/9197008)
<br>
**Authors:** Chuang Gan, Yiwei Zhang, Jiajun Wu, Boqing Gong, Joshua B. Tenenbaum
<br>
**Institution:** MIT-IBM Watson AI Lab; Tsinghua University; Massachusetts Institute of Technology; Google Inc.

**[ICLR-2021]**
[Learning to Set Waypoints for Audio-Visual Navigation](https://arxiv.org/abs/2008.09622)
<br>
**Authors:** Changan Chen, Sagnik Majumder, Ziad Al-Halah, Ruohan Gao, Santhosh Kumar Ramakrishnan, Kristen Grauman
<br>
**Institution:** The University of Texas at Austin; Facebook AI Research

**[CVPR-2021]**
[Semantic Audio-Visual Navigation](https://openaccess.thecvf.com/content/CVPR2021/html/Chen_Semantic_Audio-Visual_Navigation_CVPR_2021_paper.html)
<br>
**Authors:** Changan Chen, Ziad Al-Halah, Kristen Grauman
<br>
**Institution:** The University of Texas at Austin; Facebook AI Research

**[ICCV-2021]**
[Move2Hear: Active Audio-Visual Source Separation](https://openaccess.thecvf.com/content/ICCV2021/html/Majumder_Move2Hear_Active_Audio-Visual_Source_Separation_ICCV_2021_paper.html)
<br>
**Authors:** Sagnik Majumder, Ziad Al-Halah, Kristen Grauman
<br>
**Institution:** The University of Texas at Austin; Facebook AI Research

**[2022]**
[Sound Adversarial Audio-Visual Navigation](https://arxiv.org/abs/2202.10910)
<br>
**Authors:** Yinfeng Yu, Wenbing Huang, Fuchun Sun, Changan Chen, Yikai Wang, Xiaohong Liu
<br>
**Institution:** Tsinghua University; Xinjiang University; The University of Texas at Austin; JD Explore Academy

**[CVPR-2022]**
[Towards Generalisable Audio Representations for Audio-Visual Navigation](https://arxiv.org/abs/2206.00393)
<br>
**Authors:** Shunqi Mao, Chaoyi Zhang, Heng Wang, Weidong Cai
<br>
**Institution:** University of Sydney

**[NeurIPS-2022]**
[SoundSpaces 2.0: A Simulation Platform for Visual-Acoustic Learning](https://arxiv.org/abs/2206.08312v1)
<br>
**Authors:** Changan Chen, Carl Schissler, Sanchit Garg, Philip Kobernik, Alexander Clegg, Paul
<br>
**Institution:** The University of Texas at Austin; Reality Labs at Meta; Georgia Tech; Meta AI

**[NeurIPS-2022]**
[AVLEN: Audio-Visual-Language Embodied Navigation in 3D Environments](https://arxiv.org/abs/2210.07940)
<br>
**Authors:** Sudipta Paul, Amit K. Roy-Chowdhury, Anoop Cherian
<br>
**Institution:** University of California; Mitsubishi Electric Research Labs, Cambridge

**[BMVC-2022]**
[Pay Self-Attention to Audio-Visual Navigation](https://arxiv.org/abs/2210.01353)
<br>
**Authors:** Yinfeng Yu, Lele Cao, Fuchun Sun, Xiaohong Liu, Liejun Wang
<br>
**Institution:** Tsinghua University; Motherbrain, EQT; Xinjiang University

**[CVPR-2022]**
[Finding Fallen Objects Via Asynchronous Audio-Visual Integration](https://arxiv.org/abs/2207.03483)
<br>
**Authors:** Chuang Gan, Yi Gu, Siyuan Zhou, Jeremy Schwartz, Seth Alter, James Traer, Dan Gutfreund, Joshua B. Tenenbaum, Josh McDermott, Antonio Torralba
<br>
**Institution:** Massachusetts Institute of Technology; MIT-IBM Watson AI Lab

**[CVPR-2022]**
[ObjectFolder 2.0: A Multisensory Object Dataset for Sim2Real Transfer](https://arxiv.org/abs/2204.02389)
<br>
**Authors:** Ruohan Gao, Zilin Si, Yen-Yu Chang, Samuel Clarke, Jeannette Bohg, Li Fei-Fei, Wenzhen Yuan, Jiajun Wu
<br>
**Institution:** Stanford Univeristy; Carnegie Mellon University

**[IEEE RAL-2023]**
[Catch Me If You Hear Me: Audio-Visual Navigation in Complex Unmapped Environments with Moving Sounds](https://arxiv.org/abs/2111.14843)
<br>
**Authors:** Abdelrahman Younes, Daniel Honerkamp, Tim Welschehold, Abhinav Valada
<br>
**Institution:** University of Freiburg

**[2023]**
[Audio Visual Language Maps for Robot Navigation](https://arxiv.org/abs/2303.07522)
<br>
**Authors:** Chenguang Huang, Oier Mees, Andy Zeng, Wolfram Burgard
<br>
**Institution:** University of Freiburg; Google Research; University of Technology Nuremberg

**[ICCV-2023]**
[Omnidirectional Information Gathering for Knowledge Transfer-based Audio-Visual Navigation](https://arxiv.org/abs/2308.10306)
<br>
**Authors:** Jinyu Chen, Wenguan Wang, Si Liu, Hongsheng Li, Yi Yang
<br>
**Institution:** Beihang University; Zhejiang University; The Chinese University of Hong Kong

### Audio-visual Event Localization and Parsing
#### Localization
**[ECCV-2018]**
[Audio-visual Event Localization in Unconstrained Videos](https://openaccess.thecvf.com/content_ECCV_2018/html/Yapeng_Tian_Audio-Visual_Event_Localization_ECCV_2018_paper.html)
<br>
**Authors:** Yapeng Tian, Jing Shi, Bochen Li, Zhiyao Duan, Chenliang Xu
<br>
**Institution:** University of Rochester

**[ICASSP-2019]**
[Dual-modality Seq2Seq Network for Audio-visual Event Localization](https://ieeexplore.ieee.org/abstract/document/8683226/)
<br>
**Authors:** Yan-Bo Lin, Yu-Jhe Li, Yu-Chiang Frank Wang
<br>
**Institution:** National Taiwan University

**[ICCV-2019]**
[Dual Attention Matching for Audio-Visual Event Localization](https://openaccess.thecvf.com/content_ICCV_2019/html/Wu_Dual_Attention_Matching_for_Audio-Visual_Event_Localization_ICCV_2019_paper.html)
<br>
**Authors:** Yu Wu, Linchao Zhu, Yan Yan, Yi Yang
<br>
**Institution:** Baidu Research; University of Technology Sydney; Texas State University

**[AAAI-2020]**
[Cross-Modal Attention Network for Temporal Inconsistent Audio-Visual Event Localization](https://ojs.aaai.org/index.php/AAAI/article/view/5361)
<br>
**Authors:** Hanyu Xuan, Zhenyu Zhang, Shuo Chen, Jian Yang, Yan Yan
<br>
**Institution:** Nanjing University of Science and Technology

**[ACCV-2020]**
[Audiovisual Transformer with Instance Attention for Audio-Visual Event Localization](https://openaccess.thecvf.com/content/ACCV2020/html/Lin_Audiovisual_Transformer_with_Instance_Attention_for_Audio-Visual_Event_Localization_ACCV_2020_paper.html)
<br>
**Authors:** Yan-Bo Lin, Yu-Chiang Frank Wang
<br>
**Institution:** National Taiwan University; ASUS Intelligent Cloud Services

**[WACV-2021]**
[Audio-Visual Event Localization via Recursive Fusion by Joint Co-Attention](https://openaccess.thecvf.com/content/WACV2021/html/Duan_Audio-Visual_Event_Localization_via_Recursive_Fusion_by_Joint_Co-Attention_WACV_2021_paper.html)
<br>
**Authors:** Bin Duan, Hao Tang, Wei Wang, Ziliang Zong, Guowei Yang, Yan Yan
<br>
**Institution:** Illinois Institute of Technology; University of Trento; Texas State University

**[CVPR-2021]**
[Positive Sample Propagation along the Audio-Visual Event Line](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhou_Positive_Sample_Propagation_Along_the_Audio-Visual_Event_Line_CVPR_2021_paper.pdf)
<br>
**Authors:** Jinxing Zhou, Liang Zheng, Yiran Zhong, Shijie Hao, Meng Wang
<br>
**Institution:** Hefei University of Technology; Intelligent Interconnected Systems Laboratory of Anhui Province; Australian National University

**[AIKE-2021]**
[Audio-Visual Event Localization based on Cross-Modal Interacting Guidance](https://ieeexplore.ieee.org/document/9723768)
<br>
**Authors:** Qiurui Yue; Xiaoyu Wu; Jiayi Gao
<br>
**Institution:** Communication University of China

**[TMM-2021]**
[Audio-Visual Event Localization by Learning Spatial and Semantic Co-attention](https://ieeexplore.ieee.org/document/9615027)
<br>
**Authors:** Cheng Xue, Xionghu Zhong, Minjie Cai, Hao Chen, Wenwu Wang
<br>
**Institution:** Hunan University; United Kingdom of Great Britain and Northern Ireland

**[CVPR-2022]**
[Cross-Modal Background Suppression for Audio-Visual Event Localization](https://openaccess.thecvf.com/content/CVPR2022/html/Xia_Cross-Modal_Background_Suppression_for_Audio-Visual_Event_Localization_CVPR_2022_paper.html)
<br>
**Authors:** Yan Xia, Zhou Zhao
<br>
**Institution:** Zhejiang University

**[ICASSP-2022]**
[Bi-Directional Modality Fusion Network For Audio-Visual Event Localization](https://ieeexplore.ieee.org/abstract/document/9746280/)
<br>
**Authors:** Shuo Liu; Weize Quan; Yuan Liu; Dong-Ming Yan
<br>
**Institution:** Chinese Academy of Sciences; Alibaba Group

**[ICSIP-2022]**
[Audio-Visual Event and Sound Source Localization Based on Spatial-Channel Feature Fusion](https://ieeexplore.ieee.org/document/9886106/)
<br>
**Authors:** Xiaolong Zheng, Ying Wei
<br>
**Institution:** Shandong University

**[IJCNN-2022]**
[Look longer to see better: Audio-visual event localization by exploiting long-term correlation](https://ieeexplore.ieee.org/document/9892495/)
<br>
**Authors:** Longyin Guo, Qijun Zhao, Hongmei Gao
<br>
**Institution:** Sichuan University; Tibet University

**[EUSIPCO-2022]**
[Audio Visual Graph Attention Networks for Event Detection in Sports Video](https://ieeexplore.ieee.org/document/9909552/)
<br>
**Authors:** Taichi Ishiwatari, Makiko Azuma, Takuya Handa, Masaki Takahashi, Takahiro Mochizuki, Masanori Sano
<br>
**Institution:** Science and Technology Research Laboratories, NHK; Tokyo Institute of Technology

**[IEEE TPAMI-2022]**
[Contrastive Positive Sample Propagation along the Audio-Visual Event Line](https://ieeexplore.ieee.org/abstract/document/9956870/)
<br>
**Authors:** Jinxing Zhou, Dan Guo, Meng Wang
<br>
**Institution:** Hefei University of Technology

**[IEEE TPAMI-2022]**
[Semantic and Relation Modulation for Audio-Visual Event Localization](https://ieeexplore.ieee.org/abstract/document/9990903)
<br>
**Authors:** Hao Wang, Zheng-Jun Zha, Liang Li, Xuejin Chen, Jiebo Luo
<br>
**Institution:** University of Science and Technology of China; Chinese Academy of Sciences; University of Rochester

**[WACV-2023]**
[AVE-CLIP: AudioCLIP-based Multi-window Temporal Transformer for Audio Visual Event Localization](https://ieeexplore.ieee.org/document/10030779/)
<br>
**Authors:** Tanvir Mahmud, Diana Marculescu
<br>
**Institution:** The University of Texas at Austin

**[WACV-2023]**
[Event-Specific Audio-Visual Fusion Layers: A Simple and New Perspective on Video Understanding](https://ieeexplore.ieee.org/document/10030378)
<br>
**Authors:** Arda Senocak, Junsik Kim, Tae-Hyun Oh, Dingzeyu Li, In So Kweon
<br>
**Institution:** Korea Advanced Institute of Science & Technology; Harvard University; Pohang University of Science and Technology; Adobe Research

**[ICASSP-2023]**
[A dataset for Audio-Visual Sound Event Detection in Movies](https://arxiv.org/abs/2302.07315)
<br>
**Authors:** Rajat Hebbar, Digbalay Bose, Krishna Somandepalli, Veena Vijai, Shrikanth Narayanan
<br>
**Institution:** University of Southern California

**[CVPR-2023]**
[Dense-Localizing Audio-Visual Events in Untrimmed Videos: A Large-Scale Benchmark and Baseline](https://arxiv.org/abs/2303.12930)
<br>
**Authors:** Tiantian Geng, Teng Wang, Jinming Duan, Runmin Cong, Feng Zheng
<br>
**Institution:** Southern University of Science and Technology; University of Birmingham; The University of Hong Kong; Shandong University; Peng Cheng Laboratory

**[CVPR-2023]**
[Collaborative Noisy Label Cleaner: Learning Scene-aware Trailers for Multi-modal Highlight Detection in Movies](https://arxiv.org/abs/2303.14768)
<br>
**Authors:** Bei Gan, Xiujun Shu, Ruizhi Qiao, Haoqian Wu, Keyu Chen, Hanjun Li, Bo Ren
<br>
**Institution:** Tencent YouTu Lab

**[ICASSP-2023]**
[Collaborative Audio-Visual Event Localization Based on Sequential Decision and Cross-Modal Consistency](https://ieeexplore.ieee.org/document/10095807/)
<br>
**Authors:** Yuqian Kuang, Xiaopeng Fan
<br>
**Institution:** Harbin Institute of Technology; PengCheng Lab

**[CVPR-2023]**
[Collecting Cross-Modal Presence-Absence Evidence for Weakly-Supervised Audio-Visual Event Perception](https://openaccess.thecvf.com/content/CVPR2023/papers/Gao_Collecting_Cross-Modal_Presence-Absence_Evidence_for_Weakly-Supervised_Audio-Visual_Event_Perception_CVPR_2023_paper.pdf)
<br>
**Authors:** Junyu Gao, Mengyuan Chen, Changsheng Xu
<br>
**Institution:** Chinese Academy of Sciences; University of Chinese Academy of Sciences; Peng Cheng Laboratory

**[IJCNN-2023]**
[Specialty may be better: A decoupling multi-modal fusion network for Audio-visual event localization](https://ieeexplore.ieee.org/document/10191112)
<br>
**Authors:** Jinqiao Dou, Xi Chen, Yuehai Wang
<br>
**Institution:** Zhejiang University

**[AAAI-2023]**
[Furnishing Sound Event Detection with Language Model Abilities](https://arxiv.org/abs/2308.11530)
<br>
**Authors:** Hualei Wang, Jianguo Mao, Zhifang Guo, Jiarui Wan, Hong Liu, Xiangdong Wang
<br>
**Institution:** Chinese Academy of Sciences; University of Chinese Academy of Sciences; Beijing Jiaotong University

**[IEEE TMM-2023]**
[Leveraging the Video-level Semantic Consistency of Event for Audio-visual Event Localization](https://ieeexplore.ieee.org/document/10286391/)
<br>
**Authors:** Yuanyuan Jiang, Jianqin Yin, Yonghao Dang
<br>
**Institution:** Beijing University of Posts and Telecommunications

**[CVPR-2024]**
[T-VSL: Text-Guided Visual Sound Source Localization in Mixtures](https://arxiv.org/abs/2404.01751)
<br>
**Authors:** Tanvir Mahmud, Yapeng Tian, Diana Marculescu
<br>
**Institution:**  University of Texas at Austin

#### Parsing
**[ECCV-2020]**
[Unified Multisensory Perception: Weakly-Supervised Audio-Visual Video Parsing](https://link.springer.com/chapter/10.1007/978-3-030-58580-8_26)
<br>
**Authors:** Yapeng Tian, Dingzeyu Li, Chenliang Xu
<br>
**Institution:** University of Rochester; Adobe Research

**[CVPR-2021]**
[Exploring Heterogeneous Clues for Weakly-Supervised Audio-Visual Video Parsing](https://openaccess.thecvf.com/content/CVPR2021/html/Wu_Exploring_Heterogeneous_Clues_for_Weakly-Supervised_Audio-Visual_Video_Parsing_CVPR_2021_paper.html)
<br>
**Authors:** Yu Wu, Yi Yang
<br>
**Institution:** Baidu Research; University of Technology Sydney

**[NeurIPS-2021]**
[Exploring Cross-Video and Cross-Modality Signals for Weakly-Supervised Audio-Visual Video Parsing](https://proceedings.neurips.cc/paper/2021/hash/5f93f983524def3dca464469d2cf9f3e-Abstract.html)
<br>
**Authors:** Yan-Bo Lin, Hung-Yu Tseng, Hsin-Ying Lee, Yen-Yu Lin, Ming-Hsuan Yang
<br>
**Institution:** National Yang Ming Chiao Tung University; UNC Chapel Hill; University of California, Merced; Snap Research; Google Research; Yonsei University

**[2022]**
[Investigating Modality Bias in Audio Visual Video Parsing](https://arxiv.org/abs/2203.16860)
<br>
**Authors:** Piyush Singh Pasi, Shubham Nemani, Preethi Jyothi, Ganesh Ramakrishnan
<br>
**Institution:** Indian Institute of Technology

**[ICASSP-2022]**
[Distributed Audio-Visual Parsing Based On Multimodal Transformer and Deep Joint Source Channel Coding](https://ieeexplore.ieee.org/abstract/document/9746660/)
<br>
**Authors:** Penghong Wang, Jiahui Li, Mengyao Ma, Xiaopeng Fan
<br>
**Institution:** Harbin Institute of Technology; Wireless Technology Lab

**[ECCV-2022]**
[Joint-Modal Label Denoising for Weakly-Supervised Audio-Visual Video Parsing](https://arxiv.org/pdf/2204.11573)
<br>
**Authors:** Haoyue Cheng, Zhaoyang Liu, Hang Zhou, Chen Qian, Wayne Wu, Limin Wang
<br>
**Institution:** Nanjing University; SenseTime Research; The Chinese University of Hong Kong; Shanghai AI Laboratory

**[NeurIPS-2022]**
[Multi-modal Grouping Network for Weakly-Supervised Audio-Visual Video Parsing](https://openreview.net/forum?id=zfo2LqFEVY)
<br>
**Authors:** Shentong Mo, Yapeng Tian
<br>
**Institution:** Carnegie Mellon University; University of Texas at Dallas

**[2023]**
[Improving Audio-Visual Video Parsing with Pseudo Visual Labels](https://arxiv.org/abs/2303.02344)
<br>
**Authors:** Jinxing Zhou, Dan Guo, Yiran Zhong, Meng Wang
<br>
**Institution:** Hefei University of Technology; Shanghai AI Lab

**[ICASSP-2023]**
[CM-CS: Cross-Modal Common-Specific Feature Learning For Audio-Visual Video Parsing](https://ieeexplore.ieee.org/document/10097072/)
<br>
**Authors:** Hongbo Chen, Dongchen Zhu, Guanghui Zhang, Wenjun Shi, Xiaolin Zhang, Jiamao Li
<br>
**Institution:** Chinese Academy of Sciences; ShanghaiTech University; University of Chinese Academy of Sciences

**[2023]**
[Towards Long Form Audio-visual Video Understanding](https://arxiv.org/abs/2306.09431)
<br>
**Authors:** Wenxuan Hou, Guangyao Li, Yapeng Tian, Di Hu
<br>
**Institution:** Renmin University of China; The University of Texas at Dallas

**[CVPR-2023]**
[Collecting Cross-Modal Presence-Absence Evidence for Weakly-Supervised Audio- Visual Event Perception](https://ieeexplore.ieee.org/document/10205301)
<br>
**Authors:** Junyu Gao, Mengyuan Chen, Changsheng Xu
<br>
**Institution:** Chinese Academy of Sciences; University of Chinese Academy of Sciences; Peng Cheng Laboratory

**[ACM MM-2023]**
[TMac: Temporal Multi-Modal Graph Learning for Acoustic Event Classification](https://arxiv.org/abs/2309.11845)
<br>
**Authors:** Meng Liu, Ke Liang, Dayu Hu, Hao Yu, Yue Liu, Lingyuan Meng, Wenxuan Tu, Sihang Zhou, Xinwang Liu
<br>
**Institution:** National University of Defense Technology

**[WACV-2024]**
[Rethink Cross-Modal Fusion in Weakly-Supervised Audio-Visual Video Parsing](https://arxiv.org/abs/2311.08151)
<br>
**Authors:** Yating Xu, Conghui Hu, Gim Hee Lee
<br>
**Institution:** National University of Singapore

### Audio-visual Question Answering and Dialog
#### Question Answering
**[ICCV-2021]**
[Pano-AVQA: Grounded Audio-Visual Question Answering on 360deg Videos](https://openaccess.thecvf.com/content/ICCV2021/html/Yun_Pano-AVQA_Grounded_Audio-Visual_Question_Answering_on_360deg_Videos_ICCV_2021_paper.html)
<br>
**Authors:** Heeseung Yun, Youngjae Yu, Wonsuk Yang, Kangil Lee, Gunhee Kim
<br>
**Institution:** Seoul National University; Allen Institute for AI; University of Oxford; Hyundai Motor Company

**[CVPR-2022]**
[Learning To Answer Questions in Dynamic Audio-Visual Scenarios](https://openaccess.thecvf.com/content/CVPR2022/html/Li_Learning_To_Answer_Questions_in_Dynamic_Audio-Visual_Scenarios_CVPR_2022_paper.html)
<br>
**Authors:** Guangyao Li, Yake Wei, Yapeng Tian, Chenliang Xu, Ji-Rong Wen, Di Hu
<br>
**Institution:** Renmin University of China; Beijing Key Laboratory of Big Data Management and Analysis Methods; University of Rochester

**[NeurIPS-2022]**
[Language Models with Image Descriptors are Strong Few-Shot Video-Language Learners](https://arxiv.org/abs/2205.10747)
<br>
**Authors:** Zhenhailong Wang, Manling Li, Ruochen Xu, Luowei Zhou, Jie Lei, Xudong Lin ·  Shuohang Wang · Ziyi Yang · Chenguang Zhu · Derek Hoiem · Shih-Fu Chang · Mohit Bansal · Heng Ji
<br>
**Institution:** University of Illinois at Urbana-Champaign; MSR; The University of North Carolina at Chapel Hill; Columbia University

**[ACM MM-2023]**
[Progressive Spatio-temporal Perception for Audio-Visual Question Answering](https://arxiv.org/abs/2308.05421)
<br>
**Authors:** Guangyao Li, Wenxuan Hou, Di Hu
<br>
**Institution:** Renmin Uniiversity of China

**[WACV-2024]**
[CAD -- Contextual Multi-modal Alignment for Dynamic AVQA](https://arxiv.org/abs/2310.16754)
<br>
**Authors:** Asmar Nadeem, Adrian Hilton, Robert Dawes, Graham Thomas, Armin Mustafa
<br>
**Institution:** University of Surrey; BBC Research and Development

**[AAAI-2024]**
[Object-aware Adaptive-Positivity Learning for Audio-Visual Question Answering](https://arxiv.org/abs/2312.12816)
<br>
**Authors:** Zhangbin Li, Dan Guo, Jinxing Zhou, Jing Zhang, Meng Wang
<br>
**Institution:** School of Computer Science and Information Engineering, Hefei University of Technology; Institute of Artificial Intelligence, Hefei Comprehensive National Science Center

#### Dialog
**[CVPR-2019]**
[Audio Visual Scene-Aware Dialog](https://openaccess.thecvf.com/content_CVPR_2019/html/Alamri_Audio_Visual_Scene-Aware_Dialog_CVPR_2019_paper.html)
<br>
**Authors:** Huda Alamri, Vincent Cartillier, Abhishek Das, Jue Wang, Anoop Cherian, Irfan Essa, Dhruv Batra, Tim K. Marks, Chiori Hori, Peter Anderson, Stefan Lee, Devi Parikh
<br>
**Institution:** Georgia Institute of Technology; Mitsubishi Electric Research Laboratories

**[Interspeech-2019]**
[Joint Student-Teacher Learning for Audio-Visual Scene-Aware Dialog](https://www.merl.com/publications/docs/TR2019-097.pdf)
<br>
**Authors:** Hori, C.; Cherian, A.; Marks, T.; Hori, T.
<br>
**Institution:** Mitsubishi Electric Research Laboratories, Inc.

**[ICASSP-2019]**
[End-to-end Audio Visual Scene-aware Dialog Using Multimodal Attention-based Video Features](https://ieeexplore.ieee.org/abstract/document/8682583)
<br>
**Authors:** Chiori Hori, Huda Alamri, Jue Wang, Gordon Wichern, Takaaki Hori, Anoop Cherian, Tim K. Marks, Vincent Cartillier, Raphael Gontijo Lopes, Abhishek Das, Irfan Essa, Dhruv Batra, Devi Parikh
<br>
**Institution:** Mitsubishi Electric Research Laboratories; Georgia Institute of Technology

**[CVPR-2019]**
[A Simple Baseline for Audio-Visual Scene-Aware Dialog](https://openaccess.thecvf.com/content_CVPR_2019/html/Schwartz_A_Simple_Baseline_for_Audio-Visual_Scene-Aware_Dialog_CVPR_2019_paper.html)
<br>
**Authors:** Idan Schwartz, Alexander G. Schwing, Tamir Hazan
<br>
**Institution:** Technion; University of Illinois at Urbana-Champaign

**[CVPR-2019]**
[Exploring Context, Attention and Audio Features for Audio Visual Scene-Aware Dialog](https://arxiv.org/abs/1912.10132)
<br>
**Authors:** Shachi H Kumar, Eda Okur, Saurav Sahay, Jonathan Huang, Lama Nachman
<br>
**Institution:** Anticipatory Computing Lab

**[2020]**
[TMT: A Transformer-based Modal Translator for Improving Multimodal Sequence Representations in Audio Visual Scene-aware Dialog](https://arxiv.org/abs/2010.10839)
<br>
**Authors:** Wubo Li, Dongwei Jiang, Wei Zou, Xiangang Li
<br>
**Institution:** Didi Chuxing

**[AAAI-2021]**
[Dynamic Graph Representation Learning for Video Dialog via Multi-Modal Shuffled Transformers](https://ojs.aaai.org/index.php/AAAI/article/view/16231)
<br>
**Authors:** Shijie Geng, Peng Gao, Moitreya Chatterjee, Chiori Hori, Jonathan Le Roux, Yongfeng Zhang, Hongsheng Li, Anoop Cherian
<br>
**Institution:** Rutgers University; The Chinese University of Hong Kong; University of Illinois at Urbana Champaign; Mitsubishi Electric Research Laboratories

**[2021]**
[VX2TEXT: End-to-End Learning of Video-Based Text Generation From Multimodal Inputs](https://arxiv.org/abs/2101.12059)
<br>
**Authors:** Xudong Lin, Gedas Bertasius, Jue Wang, Shih-Fu Chang, Devi Parikh, Lorenzo Torresani
<br>
**Institution:** Columbia University; Facebook AI; Georgia Tech; Dartmouth

**[ICASSP-2022]**
[Audio-Visual Scene-Aware Dialog and Reasoning Using Audio-Visual Transformers with Joint Student-Teacher Learning](https://ieeexplore.ieee.org/abstract/document/9746481)
<br>
**Authors:** Ankit Shah, Shijie Geng, Peng Gao, Anoop Cherian, Takaaki Hori, Tim K. Marks, Jonathan Le Roux, Chiori Hori
<br>
**Institution:** Mitsubishi Electric Research Laboratories; Carnegie Mellon University; Rutgers University; The Chinese University of Hong Kong

**[WACV-2022]**
[QUALIFIER: Question-Guided Self-Attentive Multimodal Fusion Network for Audio Visual Scene-Aware Dialog](https://ieeexplore.ieee.org/document/9706866)
<br>
**Authors:** Muchao Ye;Quanzeng You;Fenglong Ma
<br>
**Institution:** University Park; Microsoft Azure Computer Vision

**[TACL-2022]**
[Learning English with Peppa Pig](https://arxiv.org/abs/2202.12917)
<br>
**Authors:** Mitja Nikolaus, Afra Alishahi, Grzegorz Chrupała
<br>
**Institution:** Aix-Marseille University; Tilburg University

**[2022]**
[End-to-End Multimodal Representation Learning for Video Dialog](https://arxiv.org/abs/2210.14512)
<br>
**Authors:** Huda Alamri, Anthony Bilic, Michael Hu, Apoorva Beedu, Irfan Essa
<br>
**Institution:** Georgia Institute of Technology

**[AAAI-2022]**
[Audio Visual Scene-Aware Dialog Generation with Transformer-based Video Representations](https://arxiv.org/abs/2202.09979)
<br>
**Authors:** Yoshihiro Yamazaki, Shota Orihashi, Ryo Masumura, Mihiro Uchida, Akihiko Takashima
<br>
**Institution:** Nippon Telegraph and Telephone Corporation

**[IEEE/ACM TASLP-2023]**
[DialogMCF: Multimodal Context Flow for Audio Visual Scene-Aware Dialog](https://ieeexplore.ieee.org/document/10147255)
<br>
**Authors:** Zhe Chen, Hongcheng Liu, Yu Wang
<br>
**Institution:** Shanghai Jiao Tong University; Shanghai Artificial Intelligence Laboratory

**[IEEE-ACM T AUDIO SPE-2023]**
[DialogMCF: Multimodal Context Flow for Audio
Visual Scene-Aware Dialog](https://ieeexplore.ieee.org/document/10147255)
<br>
**Authors:** Zhe Chen, Hongcheng Liu, Yu Wang
<br>
**Institution:** Cooperative Medianet Innovation Center, Shanghai Jiao Tong University

## Datasets

| Dataset | Year | Videos | Length  | Data form | Video source            | Task                                               |
| :-------------------: | :-------: | :-------: | :-------: | :---------------------------: | :-----------------------: | :-------------------------------------------------------------: |
| [LRW, LRS2 and LRS3](https://www.robots.ox.ac.uk/~vgg/data/lip_reading/)  | 2016,2018, 2018 | -        | 800h+   | video                       | in the wild             | Speech-related, speaker-related,face generation-related tasks |
| [VoxCeleb, VoxCeleb2](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox2.html) | 2017, 2018      | -        | 2,000h+ | video                       | YouTube                 | Speech-related, speaker-related,face generation-related tasks |
| [AVA-ActiveSpeaker](https://paperswithcode.com/dataset/ava-activespeaker)  | 2019            | -        | 38.5h   | video                       | YouTube                 | Speech-related task, speaker-related task                     |
| [Kinetics-400](https://deepai.org/dataset/kinetics-400)        | 2017            | 306,245  | 850h+   | video                       | YouTube                 | Action recognition                                            |
| [EPIC-KITCHENS](https://epic-kitchens.github.io/2022)       | 2018            | 39,594   | 55h     | video                       | Recorded videos         | Action recognition                                            |
| [CMU-MOSI](http://multicomp.cs.cmu.edu/resources/cmu-mosi-dataset/)            | 2016            | 2,199    | 2h+     | video                       | YouTube                 | Emotion recognition                                           |
| [CMU-MOSEI](http://multicomp.cs.cmu.edu/resources/cmu-mosei-dataset/)           | 2018            | 23,453   | 65h+    | video                       | YouTube                 | Emotion recognition                                           |
| [VGGSound](https://www.robots.ox.ac.uk/~vgg/data/vggsound/)            | 2020            | 200k+    | 550h+   | video                       | YouTube                 | Action recognition, sound localization                        |
| [AudioSet](https://paperswithcode.com/dataset/audioset)            | 2017            | 2M+      | 5,800h+ | video                       | YouTube                 | Action recognition, sound sepearation                         |
| [Greatest Hits](https://pslcdatashop.web.cmu.edu/DatasetInfo?datasetId=299)       | 2016            | 977      | 9h+     | video                       | Recorded videos         | Sound generation                                              |
| [MUSIC](https://www.kaggle.com/tiwaris436/music-dataset)               | 2018            | 714      | 23h+    | video                       | YouTube                 | Sound seperation, sound localization                          |
| [FAIR-Play](https://paperswithcode.com/dataset/fair-play)           | 2019            | 1,871    | 5.2h    | video with binaural sound   | Recorded videos         | Spatial sound generation                                      |
| [YT-ALL](https://proceedings.neurips.cc/paper/2018/file/01161aaa0b6d1345dd8fe4e481144d84-Paper.pdf)              | 2018            | 1,146    | 113.1h  | 360 video         | YouTube                 | Spatial sound generation                                      |
| [Replica](https://github.com/facebookresearch/Replica-Dataset)             | 2019            | -        | -       | 3D environment              | 3D simulator            | Depth estimation                                              |
| [AIST++](https://google.github.io/aistplusplus_dataset/)              | 2021            | -        | 5.2h    | 3D video                    | Recorded videos         | Dance generation                                              |
| [TED](https://www.kaggle.com/datasets/357d87783a50f64e58afdb56d66cffda7aad25e2d2806c583d87c7d4b604b141)                 | 2019            | -        | 52h     | video                       | TED talks               | Gesture generation                                            |
| [SumMe](https://paperswithcode.com/dataset/summe)               | 2014            | 25       | 1h+     | video with eye-tracking     | User videos             | Saliency detection                                            |
| [AVE](https://paperswithcode.com/dataset/ave)                 | 2018            | 4,143    | 11h+    | video                       | YouTube                 | Event localization                                            |
| [LLP](https://link.springer.com/chapter/10.1007/978-3-030-58580-8_26)                 | 2020            | 11,849   | 32.9h   | video                       | YouTube                 | Event parsing                                                 |
| [SoundSpaces](https://soundspaces.org/)         | 2020            | -        | -       | 3D environment              | 3D simulator            | Audio-visual navigation                                       |
| [AVSD](https://paperswithcode.com/dataset/avsd)                | 2019            | 11,816   | 98h+    | video with dialog           | Crowd-sourced           | Audio-visual dialog                                           |
| [Pano-AVQA](https://paperswithcode.com/dataset/visual-question-answering)           | 2021            | 5.4k     | 7.7h    | 360 video with QA | Video-sharing platforms | Audio-visual question answering                               |
| [MUSIC-AVQA](https://gewu-lab.github.io/MUSIC-AVQA/)          | 2022            | 9,288    | 150h+   | video with QA               | YouTube                 | Audio-visual question answering                               |
| [AVSBench](https://arxiv.org/abs/2207.05042)         | 2022            | 5,356    | 14.8h+   | video         | YouTube                 | Audio-visual segmentation, sound localization                             |
| [RAF](https://arxiv.org/abs/2403.18821) | 2024 | - | 95h+ | 3D environment | Recorded videos | Spatial Sound Generation |
