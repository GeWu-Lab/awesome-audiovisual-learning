## Overview

This is a curated list of audio-visual learning methods and datasets, based on our survey: <Learning in Audio-visual Context: A Review, Analysis, and New Perspective>.

[[Website of Our Survey]](https://gewu-lab.github.io/audio-visual-learning), [[arXiv]](https://arxiv.org/abs/2208.09579)


## Table of contents

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

**[IEEE Transactions on Pattern Analysis and Machine Intelligence-2018]**
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

**[IEEE Transactions on Neural Networks and Learning Systems-2022]**
[Multimodal Sparse Transformer Network for Audio-visual Speech Recognition](https://ieeexplore.ieee.org/abstract/document/9755926)
<br>
**Authors:** Qiya Song, Bin Sun, Shutao Li
<br>
**Institution:** Hunan University

**[Interspeech-2022]**
[Robust Self-Supervised Audio-V\visual Speech Recognition](https://arxiv.org/abs/2201.01763)
<br>
**Authors:** Bowen Shi, Wei-Ning Hsu, Abdelrahman Mohamed
<br>
**Institution:** Toyota Technological Institute at Chicago; Meta AI


#### Speaker Recognition
**[Multimedia Tools and Applications-2016]**
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
**Authors:** Leda Sar?, Kritika Singh, Jiatong Zhou, Lorenzo Torresani, Nayan Singhal, Yatharth Saraf
<br>
**Institution:** University of Illinois at Urbana-Champaign, Facebook AI Research

**[IEEE/ACM Transactions on Audio, Speech, and Language Processing-2021]**
[Audio-visual Deep Neural Network for Robust Person Verification](https://ieeexplore.ieee.org/abstract/document/9350195)
<br>
**Authors:** Yanmin Qian, Zhengyang Chen, Shuai Wang
<br>
**Institution:** Shanghai Jiao Tong University


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

**[IEEE Transactions on Affective Computing-2021]**
[Multi-modal Sarcasm Detection and Humor Classification in Code-mixed Conversations](https://ieeexplore.ieee.org/abstract/document/9442359)
<br>
**Authors:** Manjot Bedi, Shivani Kumar, Md Shad Akhtar, Tanmoy Chakraborty
<br>
**Institution:** Indraprastha Institute of Information Technology, Delhi



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

**[IEEE Transactions on Emerging Topics in Computational Intelligence-2018]**
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

**[ICASSP-2022]**
[The Impact of Removing Head Movements on Audio-Visual Speech Enhancement](https://ieeexplore.ieee.org/abstract/document/9746401)
<br>
**Authors:** Zhiqi Kang, Mostafa Sadeghi, Radu Horaud, Xavier Alameda-Pineda, Jacob Donley, Anurag Kumar
<br>
**Institution:** Inria Grenoble; Université Grenoble Alpes; Inria Nancy Grand-Est; Reality Labs Research


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


#### Face Super-resolution and Reconstruction

**[CVPR-2020]**
[Learning to Have an Ear for Face Super-Resolution](https://openaccess.thecvf.com/content_CVPR_2020/html/Meishvili_Learning_to_Have_an_Ear_for_Face_Super-Resolution_CVPR_2020_paper.html)
<br>
**Authors:** Givi Meishvili, Simon Jenni, Paolo Favaro
<br>
**Institution:** University of Bern

**[IEEE Transactions on Circuits and Systems for Video Technology-2021]**
[Appearance Matters, So Does Audio: Revealing the Hidden Face via Cross-Modality Transfer](https://ieeexplore.ieee.org/abstract/document/9349088)
<br>
**Authors:** 
Chenqi Kong, Baoliang Chen, Wenhan Yang, Haoliang Li, Peilin Chen, Shiqi Wang
<br>
**Institution:** City University of Hong Kong; Nanyang Technological University




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

**[MM-2018]**
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

**[IEEE Transactions on Cybernetics-2022]**
[End-to-End Video-to-Speech Synthesis Using Generative Adversarial Networks](https://ieeexplore.ieee.org/abstract/document/9760273)
<br>
**Authors:** Rodrigo Mira, Konstantinos Vougioukas, Pingchuan Ma, Stavros Petridis, Bj?rn W. Schuller, Maja Pantic
<br>
**Institution:** Imperial College London; University of Augsburg; Meta AI

##### Music
**[IEEE Transactions on Multimedia-2015]**
[Real-Time Piano Music Transcription Based on Computer Vision](https://ieeexplore.ieee.org/abstract/document/7225173)
<br>
**Authors:** Mohammad Akbari, Howard Cheng
<br>
**Institution:** Simon Fraser University; University of Lethbridge 

**[MM-2017]**
[Deep Cross-Modal Audio-Visual Generation](https://dl.acm.org/doi/abs/10.1145/3126686.3126723)
<br>
**Authors:** 
Lele Chen, Sudhanshu Srivastava, 
Zhiyao Duan, Chenliang Xu
<br>
**Institution:** University of Rochester

**[NIPS-2020]**
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

**[IEEE Transactions on Image Processing-2020]**
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


#### Spatial Sound Generation
**[ACM Transactions on Graphics-2018]**
[Scene-aware audio for 360° videos](https://dl.acm.org/doi/abs/10.1145/3197517.3201391)
<br>
**Authors:** Dingzeyu Li, Timothy R.Langlois, Changxi Zheng
<br>
**Institution:** Columbia University; Adobe Research

**[NIPS-2018]**
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

**[WACV-2022]**
[Beyond Mono to Binaural: Generating Binaural Audio From Mono Audio With Depth and Cross Modal Attention](https://openaccess.thecvf.com/content/WACV2022/html/Parida_Beyond_Mono_to_Binaural_Generating_Binaural_Audio_From_Mono_Audio_WACV_2022_paper.html)
<br>
**Authors:** Kranti Kumar Parida, Siddharth Srivastava, Gaurav Sharma
<br>
**Institution:** Indian Institute of Technology Kanpur; CDAC Noida; TensorTour Inc.


#### Video Generation
##### talking face
**[ACM Transactions on Graphics-2017]**
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

**[International Journal of Computer Vision-2019]**
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

**[International Journal of Computer Vision-2020]**
[Realistic Speech-Driven Facial Animation with GANs](https://link.springer.com/article/10.1007/s11263-019-01251-8)
<br>
**Authors:** Konstantinos Vougioukas, Stavros Petridis, Maja Pantic
<br>
**Institution:** Imperial College London; Samsung AI Research Centre Cambridge

**[International Journal of Computer Vision-2020]**
[GANimation: One-Shot Anatomically Consistent Facial Animation](https://link.springer.com/article/10.1007/s11263-019-01210-3)
<br>
**Authors:** Albert Pumarola, Antonio Agudo, Aleix M. Martinez, Alberto Sanfeliu, Francesc Moreno-Noguer
<br>
**Institution:** Institut de Robòtica i Informàtica Industrial; The Ohio State University

**[ACM Transactions on Graphics-2020]**
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

##### Gesture
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

**[ACM Transactions on Graphics-2020]**
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

##### Dance
**[MM-2018]**
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

**[NIPS-2019]**
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



### Audio-visual Transfer Learning
**[NIPS-2016]**
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

**[ACM Transactions on Multimedia Computing, Communications, and Applications-2020]**
[Deep Triplet Neural Networks with Cluster-CCA for Audio-Visual Cross-Modal Retrieval](https://dl.acm.org/doi/abs/10.1145/3387164)
<br>
**Authors:** Donghuo Zeng, Yi Yu, Keizo Oyama
<br>
**Institution:** National Institute of Informatics
 
**[IEEE Transactions on Geoscience and Remote Sensing-2020]**
[Deep Cross-Modal Image–Voice Retrieval in Remote Sensing](https://ieeexplore.ieee.org/abstract/document/9044618)
<br>
**Authors:** Yaxiong Chen, Xiaoqiang Lu, Shuai Wang
<br>
**Institution:** China University of Chinese Academy of Sciences; Chinese Academy of Sciences




## Audio-visual Collaboration

### Audio-visual Representation Learning

**[ICCV-2017]**
[Look, Listen and Learn](https://openaccess.thecvf.com/content_iccv_2017/html/Arandjelovic_Look_Listen_and_ICCV_2017_paper.html)
<br>
**Authors:** Relja Arandjelovic, Andrew Zisserman
<br>
**Institution:** Google Inc.; University of Oxford

**[NIPS-2018]**
[Cooperative Learning of Audio and Video Models from Self-Supervised Synchronization](https://proceedings.neurips.cc/paper/2018/hash/c4616f5a24a66668f11ca4fa80525dc4-Abstract.html)
<br>
**Authors:** Bruno Korbar, Du Tran, Lorenzo Torresani
<br>
**Institution:** Dartmouth College; Facebook Research

**[NIPS-2020]**
[Learning Representations from Audio-Visual Spatial Alignment](https://proceedings.neurips.cc/paper/2020/hash/328e5d4c166bb340b314d457a208dc83-Abstract.html)
<br>
**Authors:** Pedro Morgado, Yi Li, Nuno Nvasconcelos
<br>
**Institution:** University of California

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

**[NIPS-2020]**
[Self-Supervised Learning by Cross-Modal Audio-Video Clustering](https://proceedings.neurips.cc/paper/2020/hash/6f2268bd1d3d3ebaabb04d6b5d099425-Abstract.html)
<br>
**Authors:** Humam Alwassel, Dhruv Mahajan, Bruno Korbar, Lorenzo Torresani, Bernard Ghanem, Du Tran
<br>
**Institution:** King Abdullah University of Science and Technology; Facebook AI Research

**[NIPS-2020]**
[Labelling Unlabelled Videos From Scratch With Multi-Modal Self-Supervision](https://proceedings.neurips.cc/paper/2020/hash/31fefc0e570cb3860f2a6d4b38c6490d-Abstract.html)
<br>
**Authors:** Yuki Asano, Mandela Patrick, Christian Rupprecht, Andrea Vedaldi
<br>
**Institution:** University of Oxford; Facebook AI Research

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

**[NIPS-2021]**
[VATT: Transformers for Multimodal Self-Supervised Learning from Raw Video, Audio and Text](https://proceedings.neurips.cc/paper/2021/hash/cb3213ada48302953cb0f166464ab356-Abstract.html)
<br>
**Authors:** Hassan Akbari, Liangzhe Yuan, Rui Qian, Wei-Hong Chuang, Shih-Fu Chang, Yin Cui, Boqing Gong
<br>
**Institution:** Columbia University; Google Inc.; Cornell University

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

**[IEEE Transactions on Pattern Analysis and Machine Intelligence-2021]**
[Learning to Localize Sound Sources in Visual Scenes: Analysis and Applications](https://ieeexplore.ieee.org/abstract/document/8894565/)
<br>
**Authors:** Arda Senocak, Tae-Hyun Oh, Junsik Kim, Ming-Hsuan Yang, In So Kweon
<br>
**Institution:** Korea Advanced Institute of Science and Technology; Pohang University of Science and Technology; University of California

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

**[IEEE Transactions on Pattern Analysis and Machine Intelligence-2021]**
[Class-aware Sounding Objects Localization via Audiovisual Correspondence](https://ieeexplore.ieee.org/abstract/document/9662191/)
<br>
**Authors:** Di Hu, Yake Wei, Rui Qian, Weiyao Lin, Ruihua Song, Ji-Rong Wen
<br>
**Institution:** Renmin University of China; Shanghai Jiao Tong University
 
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

**[IEEE Transactions on Image Processing-2020]**
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

**[2021]**
[Catch Me If You Hear Me: Audio-Visual Navigation in Complex Unmapped Environments with Moving Sounds](https://arxiv.org/abs/2111.14843)
<br>
**Authors:** Abdelrahman Younes, Daniel Honerkamp, Tim Welschehold, Abhinav Valada
<br>
**Institution:** University of Freiburg

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

**[CVPR-2022]**
[Cross-Modal Background Suppression for Audio-Visual Event Localization](https://openaccess.thecvf.com/content/CVPR2022/html/Xia_Cross-Modal_Background_Suppression_for_Audio-Visual_Event_Localization_CVPR_2022_paper.html)
<br>
**Authors:** Yan Xia, Zhou Zhao
<br>
**Institution:** Zhejiang University


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

**[NIPS-2021]**
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

**[AAAI-2021]**
[Dynamic Graph Representation Learning for Video Dialog via Multi-Modal Shuffled Transformers](https://ojs.aaai.org/index.php/AAAI/article/view/16231)
<br>
**Authors:** Shijie Geng, Peng Gao, Moitreya Chatterjee, Chiori Hori, Jonathan Le Roux, Yongfeng Zhang, Hongsheng Li, Anoop Cherian
<br>
**Institution:** Rutgers University; The Chinese University of Hong Kong; University of Illinois at Urbana Champaign; Mitsubishi Electric Research Laboratories

**[ICASSP-2022]**
[Audio-Visual Scene-Aware Dialog and Reasoning Using Audio-Visual Transformers with Joint Student-Teacher Learning](https://ieeexplore.ieee.org/abstract/document/9746481)
<br>
**Authors:** Ankit Shah, Shijie Geng, Peng Gao, Anoop Cherian, Takaaki Hori, Tim K. Marks, Jonathan Le Roux, Chiori Hori
<br>
**Institution:** Mitsubishi Electric Research Laboratories; Carnegie Mellon University; Rutgers University; The Chinese University of Hong Kong




## Datasets



| Dataset             | Year            | # Videos | Length  | Data form                   | Video source            | Task                                                          |
<br>
| ------------------- | ------- | ------- | ------- | --------------------------- | ----------------------- | ------------------------------------------------------------- |
<br>
| [LRW, LRS2 and LRS3](https://www.robots.ox.ac.uk/~vgg/data/lip_reading/)  | 2016,2018, 2018 | -        | 800h+   | video                       | in the wild             | Speech-related, speaker-related,face generation-related tasks |
<br>
| [VoxCeleb, VoxCeleb2](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox2.html) | 2017, 2018      | -        | 2,000h+ | video                       | YouTube                 | Speech-related, speaker-related,face generation-related tasks |
<br>
| [AVA-ActiveSpeaker](https://paperswithcode.com/dataset/ava-activespeaker)  | 2019            | -        | 38.5h   | video                       | YouTube                 | Speech-related task, speaker-related task                     |
<br>
| [Kinetics-400](https://deepai.org/dataset/kinetics-400)        | 2017            | 306,245  | 850h+   | video                       | YouTube                 | Action recognition                                            |
<br>
| [EPIC-KITCHENS](https://epic-kitchens.github.io/2022)       | 2018            | 39,594   | 55h     | video                       | Recorded videos         | Action recognition                                            |
<br>
| [CMU-MOSI](http://multicomp.cs.cmu.edu/resources/cmu-mosi-dataset/)            | 2016            | 2,199    | 2h+     | video                       | YouTube                 | Emotion recognition                                           |
<br>
| [CMU-MOSEI](http://multicomp.cs.cmu.edu/resources/cmu-mosei-dataset/)           | 2018            | 23,453   | 65h+    | video                       | YouTube                 | Emotion recognition                                           |
<br>
| [VGGSound](https://www.robots.ox.ac.uk/~vgg/data/vggsound/)            | 2020            | 200k+    | 550h+   | video                       | YouTube                 | Action recognition, sound localization                        |
<br>
| [AudioSet](https://paperswithcode.com/dataset/audioset)            | 2017            | 2M+      | 5,800h+ | video                       | YouTube                 | Action recognition, sound sepearation                         |
<br>
| [Greatest Hits](https://pslcdatashop.web.cmu.edu/DatasetInfo?datasetId=299)       | 2016            | 977      | 9h+     | video                       | Recorded videos         | Sound generation                                              |
<br>
| [MUSIC](https://www.kaggle.com/tiwaris436/music-dataset)               | 2018            | 714      | 23h+    | video                       | YouTube                 | Sound seperation, sound localization                          |
<br>
| [FAIR-Play](https://paperswithcode.com/dataset/fair-play)           | 2019            | 1,871    | 5.2h    | video with binaural sound   | Recorded videos         | Spatial sound generation                                      |
<br>
| [YT-ALL](https://yt-project.org/)              | 2018            | 1,146    | 113.1h  | 360 video         | YouTube                 | Spatial sound generation                                      |
<br>
| [Replica](https://github.com/facebookresearch/Replica-Dataset)             | 2019            | -        | -       | 3D environment              | 3D simulator            | Depth estimation                                              |
<br>
| [AIST++](https://google.github.io/aistplusplus_dataset/)              | 2021            | -        | 5.2h    | 3D video                    | Recorded videos         | Dance generation                                              |
<br>
| [TED](https://www.kaggle.com/datasets/357d87783a50f64e58afdb56d66cffda7aad25e2d2806c583d87c7d4b604b141)                 | 2019            | -        | 52h     | video                       | TED talks               | Gesture generation                                            |
<br>
| [SumMe](https://paperswithcode.com/dataset/summe)               | 2014            | 25       | 1h+     | video with eye-tracking     | User videos             | Saliency detection                                            |
<br>
| [AVE](https://paperswithcode.com/dataset/ave)                 | 2018            | 4,143    | 11h+    | video                       | YouTube                 | Event localization                                            |
<br>
| LLP                 | 2020            | 11,849   | 32.9h   | video                       | YouTube                 | Event parsing                                                 |
<br>
| [SoundSpaces](https://soundspaces.org/)         | 2020            | -        | -       | 3D environment              | 3D simulator            | Audio-visual navigation                                       |
<br>
| [AVSD](https://paperswithcode.com/dataset/avsd)                | 2019            | 11,816   | 98h+    | video with dialog           | Crowd-sourced           | Audio-visual dialog                                           |
<br>
| [Pano-AVQA](https://paperswithcode.com/dataset/visual-question-answering)           | 2021            | 5.4k     | 7.7h    | 360 video with QA | Video-sharing platforms | Audio-visual question answering                               |
<br>
| [MUSIC-AVQA](https://gewu-lab.github.io/MUSIC-AVQA/)          | 2022            | 9,288    | 150h+   | video with QA               | YouTube                 | Audio-visual question answering                               |