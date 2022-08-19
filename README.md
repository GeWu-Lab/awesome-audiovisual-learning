# awesome-audiovisual-learning



## Table of contents

- [awesome-audiovisual-learning](#awesome-audiovisual-learning)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
  - [Boosting Single Modality Learning](#boosting-single-modality-learning)
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
    - [Audio-visual Generation](#audio-visual-generation)
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
  - [Audio-visual Collaborative Learning](#audio-visual-collaborative-learning)
    - [Audio-visual Representation Learning](#audio-visual-representation-learning)
      - [Audio-visual Consistency](#audio-visual-consistency)
      - [Deep Clustering](#deep-clustering)
      - [Pre-training Models](#pre-training-models)
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


## Overview

This is a curated list of audio-visual learning methods and datasets.

## Boosting Single Modality Learning

### Audio-visual Recognition

#### Speech Recognition

* [Audio-visual Speech Recognition Using Deep Learning](https://link.springer.com/article/10.1007/s10489-014-0629-7), 2015
* [End-To-End Audiovisual Fusion With LSTMs](https://arxiv.org/abs/1709.04343), 2017
* [Lip Reading Sentences in the Wild](https://openaccess.thecvf.com/content_cvpr_2017/html/Chung_Lip_Reading_Sentences_CVPR_2017_paper.html), 2017
* [Deep Audio-visual Speech Recognition](https://ieeexplore.ieee.org/abstract/document/8585066), 2018
* [Explicit Sparse Transformer: Concentrated Attention Through Explicit Selection](https://arxiv.org/abs/1912.11637), 2019
* [Multimodal Sparse Transformer Network for Audio-V\visual Speech Recognition](https://ieeexplore.ieee.org/abstract/document/9755926), 2022
* [Robust Self-Supervised Audio-V\visual Speech Recognition](https://arxiv.org/abs/2201.01763), 2022

#### Speaker Recognition
* [Audio-visual Speaker Diarization Using Fisher Linear Semi-discriminant Analysis](https://link.springer.com/article/10.1007/s11042-014-2274-x), 2016
* [Audio-visual Person Recognition in Multimedia Data From the Iarpa Janus Program](https://ieeexplore.ieee.org/abstract/document/8462122), 2018
* [Noise-tolerant Audio-visual Online Person Verification Using an Attention-based Neural Network Fusion](https://ieeexplore.ieee.org/abstract/document/8683477), 2019
* [Who Said That?: Audio-visual Speaker Diarisation Of Real-World Meetings](https://arxiv.org/abs/1906.10042), 2019
* [Self-Supervised Learning for Audio-visual Speaker Diarization](https://ieeexplore.ieee.org/abstract/document/9054376), 2020
* [A Multi-View Approach to Audio-visual Speaker Verification](https://ieeexplore.ieee.org/abstract/document/9414260), 2021
* [Audio-visual Deep Neural Network for Robust Person Verification](https://ieeexplore.ieee.org/abstract/document/9350195), 2021

#### Action Recognition

* [Exploring Multimodal Video Representation For Action Recognition](https://ieeexplore.ieee.org/abstract/document/7727435), 2016
* [The ActivityNet Large-Scale Activity Recognition Challenge 2018 Summary](https://arxiv.org/abs/1808.03766), 2018
* [EPIC-Fusion: Audio-Visual Temporal Binding for Egocentric Action Recognition](https://openaccess.thecvf.com/content_ICCV_2019/html/Kazakos_EPIC-Fusion_Audio-Visual_Temporal_Binding_for_Egocentric_Action_Recognition_ICCV_2019_paper.html), 2019
* [SCSampler: Sampling Salient Clips From Video for Efficient Action Recognition](https://openaccess.thecvf.com/content_ICCV_2019/html/Korbar_SCSampler_Sampling_Salient_Clips_From_Video_for_Efficient_Action_Recognition_ICCV_2019_paper.html), 2019
* [Listen to Look: Action Recognition by Previewing Audio](https://openaccess.thecvf.com/content_CVPR_2020/html/Gao_Listen_to_Look_Action_Recognition_by_Previewing_Audio_CVPR_2020_paper.html), 2020
* [Audiovisual SlowFast Networks for Video Recognition](https://arxiv.org/abs/2001.08740), 2020
* [AdaMML: Adaptive Multi-Modal Learning for Efficient Video Recognition](https://openaccess.thecvf.com/content/ICCV2021/html/Panda_AdaMML_Adaptive_Multi-Modal_Learning_for_Efficient_Video_Recognition_ICCV_2021_paper.html), 2021
* [Cross-Domain First Person Audio-Visual Action Recognition through Relative Norm Alignment](https://arxiv.org/abs/2106.01689), 2021
* [Domain Generalization Through Audio-Visual Relative Norm Alignment in First Person Action Recognition](https://openaccess.thecvf.com/content/WACV2022/html/Planamente_Domain_Generalization_Through_Audio-Visual_Relative_Norm_Alignment_in_First_Person_WACV_2022_paper.html), 2022
* [Audio-Adaptive Activity Recognition Across Video Domains](https://openaccess.thecvf.com/content/CVPR2022/html/Zhang_Audio-Adaptive_Activity_Recognition_Across_Video_Domains_CVPR_2022_paper.html), 2022
* [MM-ViT: Multi-Modal Video Transformer for Compressed Video Action Recognition](https://openaccess.thecvf.com/content/WACV2022/html/Chen_MM-ViT_Multi-Modal_Video_Transformer_for_Compressed_Video_Action_Recognition_WACV_2022_paper.html), 2022
* [Learnable Irrelevant Modality Dropout for Multimodal Action Recognition on Modality-Specific Annotated Videos](https://openaccess.thecvf.com/content/CVPR2022/html/Alfasly_Learnable_Irrelevant_Modality_Dropout_for_Multimodal_Action_Recognition_on_Modality-Specific_CVPR_2022_paper.html), 2022


#### Emotion Recognition

* [Tensor Fusion Network for Multimodal Sentiment Analysis](https://arxiv.org/abs/1707.07250), 2017
* [Multi-attention Recurrent Network for Human Communication Comprehension](https://ojs.aaai.org/index.php/AAAI/article/view/12024), 2018
* [Memory Fusion Network for Multi-view Sequential Learning](https://ojs.aaai.org/index.php/AAAI/article/view/12021), 2018
* [Conversational Memory Network for Emotion Recognition in Dyadic Dialogue Videos](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7098709/), 2018
* [Contextual Inter-modal Attention for Multi-modal Sentiment Analysis](https://aclanthology.org/D18-1382/), 2018
* [Multi-Modal Sarcasm Detection in Twitter with Hierarchical Fusion Model](https://aclanthology.org/P19-1239/?ref=https://githubhelp.com), 2019 
* [Sentiment and Emotion help Sarcasm? A Multi-task Learning Framework for Multi-Modal Sarcasm, Sentiment and Emotion Analysis](https://aclanthology.org/2020.acl-main.401/), 2020
* [A Transformer-based joint-encoding for Emotion Recognition and Sentiment Analysis](https://aclanthology.org/2020.challengehml-1.1/)
* [Multilogue-Net: A Context Aware RNN for Multi-modal Emotion Detection and Sentiment Analysis in Conversation](https://arxiv.org/abs/2002.08267), 2020
* [Progressive Modality Reinforcement for Human Multimodal Emotion Recognition From Unaligned Multimodal Sequences](https://openaccess.thecvf.com/content/CVPR2021/html/Lv_Progressive_Modality_Reinforcement_for_Human_Multimodal_Emotion_Recognition_From_Unaligned_CVPR_2021_paper.html), 2021
* [Multi-modal Sarcasm Detection and Humor Classification in Code-mixed Conversations](https://ieeexplore.ieee.org/abstract/document/9442359), 2021



### Uni-modal Enhancement

#### Speech Enhancement and Separation

* [Visual Speech Enhancement](https://arxiv.org/abs/1711.08789), 2018
* [The Conversation: Deep Audio-Visual Speech Enhancement](https://arxiv.org/abs/1804.04121), 2018
* [Audio-Visual Speech Enhancement Using Multimodal Deep Convolutional Neural Networks](https://ieeexplore.ieee.org/abstract/document/8323326), 2018
* [Seeing Through Noise: Visually Driven Speaker Separation And Enhancement](https://ieeexplore.ieee.org/abstract/document/8462527), 2018
* [Visually Assisted Time-Domain Speech Enhancement](https://ieeexplore.ieee.org/abstract/document/8969244), 2019
* [On Training Targets and Objective Functions for Deep-learning-based Audio-visual Speech Enhancement](https://ieeexplore.ieee.org/abstract/document/8682790), 2019
* [Multimodal SpeakerBeam: Single Channel Target Speech Extraction with Audio-Visual Speaker Clues](https://www.isca-speech.org/archive_v0/Interspeech_2019/pdfs/1513.pdf), 2019
* [My Lips Are Concealed: Audio-Visual Speech Enhancement Through Obstructions](https://arxiv.org/abs/1907.04975), 2019
* [Facefilter: Audio-Visual Speech Separation Using Still Images](https://arxiv.org/abs/2005.07074), 2020
* [Robust Unsupervised Audio-Visual Speech Enhancement Using a Mixture of Variational Autoencoders](https://ieeexplore.ieee.org/abstract/document/9053730/), 2020
* [Looking Into Your Speech: Learning Cross-Modal Affinity for Audio-Visual Speech Separation](https://openaccess.thecvf.com/content/CVPR2021/html/Lee_Looking_Into_Your_Speech_Learning_Cross-Modal_Affinity_for_Audio-Visual_Speech_CVPR_2021_paper.html?ref=https://githubhelp.com), 2021
* [The Impact of Removing Head Movements on Audio-Visual Speech Enhancement](https://ieeexplore.ieee.org/abstract/document/9746401), 2022


#### Object Sound Separation

* [Learning to Separate Object Sounds by Watching Unlabeled Video](https://openaccess.thecvf.com/content_ECCV_2018/html/Ruohan_Gao_Learning_to_Separate_ECCV_2018_paper.html), 2018
* [The Sound of Pixels](https://openaccess.thecvf.com/content_ECCV_2018/html/Hang_Zhao_The_Sound_of_ECCV_2018_paper.html), 2018
* [Self-supervised Audio-visual Co-segmentation](https://ieeexplore.ieee.org/abstract/document/8682467), 2019
* [The Sound of Motions](https://openaccess.thecvf.com/content_ICCV_2019/html/Zhao_The_Sound_of_Motions_ICCV_2019_paper.html), 2019
* [Recursive Visual Sound Separation Using Minus-Plus Net](https://openaccess.thecvf.com/content_ICCV_2019/html/Xu_Recursive_Visual_Sound_Separation_Using_Minus-Plus_Net_ICCV_2019_paper.html), 2019
* [Co-Separating Sounds of Visual Objects](https://openaccess.thecvf.com/content_ICCV_2019/html/Gao_Co-Separating_Sounds_of_Visual_Objects_ICCV_2019_paper.html), 2019
* [Visually Guided Sound Source Separation using Cascaded Opponent Filter Network](https://openaccess.thecvf.com/content/ACCV2020/html/Zhu_Visually_Guided_Sound_Source_Separation_using_Cascaded_Opponent_Filter_Network_ACCV_2020_paper.html), 2020
* [Music Gesture for Visual Sound Separation](https://openaccess.thecvf.com/content_CVPR_2020/html/Gan_Music_Gesture_for_Visual_Sound_Separation_CVPR_2020_paper.html), 2020
* [Visual Scene Graphs for Audio Source Separation](https://openaccess.thecvf.com/content/ICCV2021/html/Chatterjee_Visual_Scene_Graphs_for_Audio_Source_Separation_ICCV_2021_paper.html), 2021
* [Cyclic Co-Learning of Sounding Object Visual Grounding and Sound Separation](https://openaccess.thecvf.com/content/CVPR2021/html/Tian_Cyclic_Co-Learning_of_Sounding_Object_Visual_Grounding_and_Sound_Separation_CVPR_2021_paper.html), 2021


#### Face Super-resolution and Reconstruction

* [Learning to Have an Ear for Face Super-Resolution](https://openaccess.thecvf.com/content_CVPR_2020/html/Meishvili_Learning_to_Have_an_Ear_for_Face_Super-Resolution_CVPR_2020_paper.html), 2020
* [Appearance Matters, So Does Audio: Revealing the Hidden Face via Cross-Modality Transfer](https://ieeexplore.ieee.org/abstract/document/9349088), 2021




## Cross-modal Perception

### Audio-visual Generation

#### Mono Sound Generation
##### Speech
* [Vid2speech: Speech Reconstruction From Silent Video](https://ieeexplore.ieee.org/abstract/document/7953127), 2017
* [Improved Speech Reconstruction From Silent Video](https://openaccess.thecvf.com/content_ICCV_2017_workshops/w8/html/Ephrat_Improved_Speech_Reconstruction_ICCV_2017_paper.html), 2017
* [Lip2Audspec: Speech Reconstruction from Silent Lip Movements Video](https://ieeexplore.ieee.org/abstract/document/8461856), 2018
* [Harnessing AI for Speech Reconstruction using Multi-view Silent Video Feed](https://arxiv.org/abs/1807.00619), 2018
* [Video-Driven Speech Reconstruction using Generative Adversarial Networks](https://arxiv.org/abs/1906.06301), 2019
* [Hush-Hush Speak: Speech Reconstruction Using Silent Videos](https://www.isca-speech.org/archive_v0/Interspeech_2019/pdfs/3269.pdf), 2019
* [End-to-End Video-to-Speech Synthesis Using Generative Adversarial Networks](https://ieeexplore.ieee.org/abstract/document/9760273), 2022

##### Music
* [Real-Time Piano Music Transcription Based on Computer Vision](https://ieeexplore.ieee.org/abstract/document/7225173), 2015
* [Deep Cross-Modal Audio-Visual Generation](https://dl.acm.org/doi/abs/10.1145/3126686.3126723), 2017
* [Audeo: Audio Generation for a Silent Performance Video](https://proceedings.neurips.cc/paper/2020/hash/227f6afd3b7f89b96c4bb91f95d50f6d-Abstract.html), 2020
* [Foley Music: Learning to Generate Music from Videos](https://link.springer.com/chapter/10.1007/978-3-030-58621-8_44), 2020
* [Sight to Sound: An End-to-End Approach for Visual Piano Transcription](https://ieeexplore.ieee.org/abstract/document/9053115), 2020
* [Multi-Instrumentalist Net: Unsupervised Generation of Music from Body Movements](https://arxiv.org/abs/2012.03478), 2020
* [Collaborative Learning to Generate Audio-Video Jointly](https://ieeexplore.ieee.org/abstract/document/9413802/), 2021
* [Video Background Music Generation with Controllable Music Transformer](https://dl.acm.org/doi/abs/10.1145/3474085.3475195), 2021


##### Natural Sound
* [Visually Indicated Sounds](https://openaccess.thecvf.com/content_cvpr_2016/html/Owens_Visually_Indicated_Sounds_CVPR_2016_paper.html), 2016
* [Visual to Sound: Generating Natural Sound for Videos in the Wild](https://openaccess.thecvf.com/content_cvpr_2018/html/Zhou_Visual_to_Sound_CVPR_2018_paper.html), 2018
* [Generating Visually Aligned Sound From Videos](https://ieeexplore.ieee.org/abstract/document/9151258), 2020
* [Taming Visually Guided Sound Generation](https://arxiv.org/abs/2110.08791), 2021 



#### Spatial Sound Generation
* [Scene-aware audio for 360° videos](https://dl.acm.org/doi/abs/10.1145/3197517.3201391), 2018
* [Self-Supervised Generation of Spatial Audio for 360° Video](https://proceedings.neurips.cc/paper/2018/hash/01161aaa0b6d1345dd8fe4e481144d84-Abstract.html), 2018
* [2.5D Visual Sound](https://openaccess.thecvf.com/content_CVPR_2019/html/Gao_2.5D_Visual_Sound_CVPR_2019_paper.html), 2019  
* [Self-Supervised Audio Spatialization with Correspondence Classifier](https://ieeexplore.ieee.org/abstract/document/8803494/), 2019
* [Sep-Stereo: Visually Guided Stereophonic Audio Generation by Associating Source Separation](https://link.springer.com/chapter/10.1007/978-3-030-58610-2_4), 2020
* [Visually Informed Binaural Audio Generation without Binaural Audios](https://openaccess.thecvf.com/content/CVPR2021/html/Xu_Visually_Informed_Binaural_Audio_Generation_without_Binaural_Audios_CVPR_2021_paper.html), 2021
* [Exploiting Audio-Visual Consistency with Partial Supervision for Spatial Audio Generation](https://ojs.aaai.org/index.php/AAAI/article/view/16302), 2021
* [Beyond Mono to Binaural: Generating Binaural Audio From Mono Audio With Depth and Cross Modal Attention](https://openaccess.thecvf.com/content/WACV2022/html/Parida_Beyond_Mono_to_Binaural_Generating_Binaural_Audio_From_Mono_Audio_WACV_2022_paper.html), 2022



#### Video Generation
##### talking face
* [Synthesizing Obama: learning lip sync from audio](https://dl.acm.org/doi/abs/10.1145/3072959.3073640), 2017
* [Lip Movements Generation at a Glance](https://openaccess.thecvf.com/content_ECCV_2018/html/Lele_Chen_Lip_Movements_Generation_ECCV_2018_paper.html), 2018
* [You Said That?: Synthesising Talking Faces from Audio](https://link.springer.com/article/10.1007/s11263-019-01150-y), 2019
* [Few-Shot Adversarial Learning of Realistic Neural Talking Head Models](https://openaccess.thecvf.com/content_ICCV_2019/html/Zakharov_Few-Shot_Adversarial_Learning_of_Realistic_Neural_Talking_Head_Models_ICCV_2019_paper.html), 2019
* [Realistic Speech-Driven Facial Animation with GANs](https://link.springer.com/article/10.1007/s11263-019-01251-8), 2020
* [GANimation: One-Shot Anatomically Consistent Facial Animation](https://link.springer.com/article/10.1007/s11263-019-01210-3), 2020
* [Makelttalk: Speaker-Aware Talking-Head Animation](https://dl.acm.org/doi/abs/10.1145/3414685.3417774), 2020
* [FReeNet: Multi-Identity Face Reenactment](https://openaccess.thecvf.com/content_CVPR_2020/html/Zhang_FReeNet_Multi-Identity_Face_Reenactment_CVPR_2020_paper.html), 2020
* [Neural Voice Puppetry: Audio-driven Facial Reenactment](https://justusthies.github.io/posts/neural-voice-puppetry/), 2020
* [Rotate-and-Render: Unsupervised Photorealistic Face Rotation from Single-View Images](https://arxiv.org/abs/2003.08124), 2020
* [MEAD: A Large-scale Audio-visual Dataset for Emotional Talking-face Generation](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660698.pdf), 2020
* [Write-a-speaker: Text-based Emotional and Rhythmic Talking-head Generation](https://ojs.aaai.org/index.php/AAAI/article/view/16286), 2021
* [Pose-Controllable Talking Face Generation by Implicitly Modularized Audio-Visual Representation](https://openaccess.thecvf.com/content/CVPR2021/html/Zhou_Pose-Controllable_Talking_Face_Generation_by_Implicitly_Modularized_Audio-Visual_Representation_CVPR_2021_paper.html), 2021
* [Audio-Driven Emotional Video Portraits](https://openaccess.thecvf.com/content/CVPR2021/html/Ji_Audio-Driven_Emotional_Video_Portraits_CVPR_2021_paper.html), 2021



##### Gesture
* [Evaluation of Speech-to-Gesture Generation Using Bi-Directional LSTM Network](https://dl.acm.org/doi/abs/10.1145/3267851.3267878), 2018
* [Analyzing Input and Output Representations for Speech-Driven Gesture Generation](https://dl.acm.org/doi/abs/10.1145/3308532.3329472), 2019 
* [Learning Individual Styles of Conversational Gesture](https://openaccess.thecvf.com/content_CVPR_2019/html/Ginosar_Learning_Individual_Styles_of_Conversational_Gesture_CVPR_2019_paper.html), 2019 
* [To React or not to React: End-to-End Visual Pose Forecasting for Personalized Avatar during Dyadic Conversations](https://dl.acm.org/doi/abs/10.1145/3340555.3353725), 2019
* [Style-Controllable Speech-Driven Gesture Synthesis Using Normalising Flows](https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.13946), 2020
* [Gesticulator: A Framework For Semantically-Aware Speech-Driven Gesture Generation](https://dl.acm.org/doi/abs/10.1145/3382507.3418815), 2020
* [Style Transfer for Co-Speech Gesture Animation: A Multi-Speaker Conditional-Mixture Approach](https://arxiv.org/abs/2007.12553), 2020
* [Speech Gesture Generation From The Trimodal Context Of Text, Audio, And Speaker Identity](https://dl.acm.org/doi/abs/10.1145/3414685.3417838), 2020
* [SEEG: Semantic Energized Co-Speech Gesture Generation](https://openaccess.thecvf.com/content/CVPR2022/html/Liang_SEEG_Semantic_Energized_Co-Speech_Gesture_Generation_CVPR_2022_paper.html), 2022



##### Dance
* [Dance with Melody: An LSTM-autoencoder Approach to Music-oriented Dance Synthesis](https://dl.acm.org/doi/abs/10.1145/3240508.3240526), 2018
* [Audio to Body Dynamics](https://openaccess.thecvf.com/content_cvpr_2018/html/Shlizerman_Audio_to_Body_CVPR_2018_paper.html), 2018
* [Dancing to Music](https://proceedings.neurips.cc/paper/2019/hash/7ca57a9f85a19a6e4b9a248c1daca185-Abstract.html), 2019
* [Dance Revolution: Long-Term Dance Generation with Music via Curriculum Learning](https://arxiv.org/abs/2006.06119), 2020
* [AI Choreographer: Music Conditioned 3D Dance Generation With AIST++](https://openaccess.thecvf.com/content/ICCV2021/html/Li_AI_Choreographer_Music_Conditioned_3D_Dance_Generation_With_AIST_ICCV_2021_paper.html), 2021 
* [Genre-Conditioned Long-Term 3D Dance Generation Driven by Music](https://ieeexplore.ieee.org/abstract/document/9747838/), 2022


#### Depth Estimation
* [BatVision: Learning to See 3D Spatial Layout with Two Ears](https://ieeexplore.ieee.org/abstract/document/9196934/), 2020
* [VISUALECHOES: Spatial Image Representation Learning Through Echolocation](https://link.springer.com/chapter/10.1007/978-3-030-58545-7_38), 2020 
* [Beyond Image to Depth: Improving Depth Prediction Using Echoes](https://openaccess.thecvf.com/content/CVPR2021/html/Parida_Beyond_Image_to_Depth_Improving_Depth_Prediction_Using_Echoes_CVPR_2021_paper.html), 2021
* [Co-Attention-Guided Bilinear Model for Echo-Based Depth Estimation](https://ieeexplore.ieee.org/abstract/document/9746476/), 2022 

### Audio-visual Transfer Learning
* [SoundNet: Learning Sound Representations from Unlabeled Video](https://proceedings.neurips.cc/paper/2016/hash/7dcd340d84f762eba80aa538b0c527f7-Abstract.html), 2016
* [Self-Supervised Moving Vehicle Tracking With Stereo Sound](https://openaccess.thecvf.com/content_ICCV_2019/html/Gan_Self-Supervised_Moving_Vehicle_Tracking_With_Stereo_Sound_ICCV_2019_paper.html), 2019
* [There Is More Than Meets the Eye: Self-Supervised Multi-Object Detection and Tracking With Sound by Distilling Multimodal Knowledge](https://openaccess.thecvf.com/content/CVPR2021/html/Valverde_There_Is_More_Than_Meets_the_Eye_Self-Supervised_Multi-Object_Detection_CVPR_2021_paper.html?ref=https://githubhelp.com), 2021
* [Enhanced Audio Tagging via Multi- to Single-Modal Teacher-Student Mutual Learning](https://ojs.aaai.org/index.php/AAAI/article/view/17280), 2021 
* [Knowledge Distillation from Multi-Modality to Single-Modality for Person Verification](https://drive.google.com/file/d/1ISP0ot1WFxZz_IhTAOiWu4nT-Q1bXWtH/view), 2021
* [Multimodal Knowledge Expansion](https://openaccess.thecvf.com/content/ICCV2021/html/Xue_Multimodal_Knowledge_Expansion_ICCV_2021_paper.html), 2021

### Cross-modal Retrieval
* [Content-Based Video-Music Retrieval Using Soft Intra-Modal Structure Constraint](https://arxiv.org/abs/1704.06761), 2017
* [Cross-modal Embeddings for Video and Audio Retrieval](https://openaccess.thecvf.com/content_eccv_2018_workshops/w24/html/Suris_Cross-modal_Embeddings_for_Video_and_Audio_Retrieval_ECCVW_2018_paper.html), 2018
* [Audio-Visual Embedding for Cross-Modal Music Video Retrieval through Supervised Deep CCA](https://ieeexplore.ieee.org/abstract/document/8603275/), 2019
* [Audio-Visual Embedding for Cross-Modal MusicVideo Retrieval through Supervised Deep CCA](https://arxiv.org/abs/1908.03744), 2019
* [Deep Triplet Neural Networks with Cluster-CCA for Audio-Visual Cross-Modal Retrieval](https://dl.acm.org/doi/abs/10.1145/3387164), 2020  
* [Deep Cross-Modal Image–Voice Retrieval in Remote Sensing](https://ieeexplore.ieee.org/abstract/document/9044618), 2020





## Audio-visual Collaborative Learning

### Audio-visual Representation Learning
#### Audio-visual Consistency
* [Look, Listen and Learn](https://openaccess.thecvf.com/content_iccv_2017/html/Arandjelovic_Look_Listen_and_ICCV_2017_paper.html), 2017
* [Cooperative Learning of Audio and Video Models from Self-Supervised Synchronization](https://proceedings.neurips.cc/paper/2018/hash/c4616f5a24a66668f11ca4fa80525dc4-Abstract.html), 2018
* [Learning Representations from Audio-Visual Spatial Alignment](https://proceedings.neurips.cc/paper/2020/hash/328e5d4c166bb340b314d457a208dc83-Abstract.html), 2020
* [Audio-Visual Instance Discrimination with Cross-Modal Agreement](https://openaccess.thecvf.com/content/CVPR2021/html/Morgado_Audio-Visual_Instance_Discrimination_with_Cross-Modal_Agreement_CVPR_2021_paper.html), 2021  
* [Robust Audio-Visual Instance Discrimination](https://openaccess.thecvf.com/content/CVPR2021/html/Morgado_Robust_Audio-Visual_Instance_Discrimination_CVPR_2021_paper.html), 2021
* [Unsupervised Sound Localization via Iterative Contrastive Learning](https://arxiv.org/abs/2104.00315), 2021


#### Deep Clustering
* [Self-Supervised Learning by Cross-Modal Audio-Video Clustering](https://proceedings.neurips.cc/paper/2020/hash/6f2268bd1d3d3ebaabb04d6b5d099425-Abstract.html), 2020
* [Labelling Unlabelled Videos From Scratch With Multi-Modal Self-Supervision](https://proceedings.neurips.cc/paper/2020/hash/31fefc0e570cb3860f2a6d4b38c6490d-Abstract.html), 2020
* [Multimodal Clustering Networks for Self-Supervised Learning From Unlabeled Videos](https://openaccess.thecvf.com/content/ICCV2021/html/Chen_Multimodal_Clustering_Networks_for_Self-Supervised_Learning_From_Unlabeled_Videos_ICCV_2021_paper.html), 2021


#### Pre-training Models
* [OPT: Omni-Perception Pre-Trainer for Cross-Modal Understanding and Generation](https://arxiv.org/abs/2107.00249), 2021
* [VATT: Transformers for Multimodal Self-Supervised Learning from Raw Video, Audio and Text](https://proceedings.neurips.cc/paper/2021/hash/cb3213ada48302953cb0f166464ab356-Abstract.html), 2021
* [Audioclip: Extending Clip to Image, Text and Audio](https://ieeexplore.ieee.org/abstract/document/9747631/), 2022
* [MERLOT Reserve: Neural Script Knowledge Through Vision and Language and Sound](https://openaccess.thecvf.com/content/CVPR2022/html/Zellers_MERLOT_Reserve_Neural_Script_Knowledge_Through_Vision_and_Language_and_CVPR_2022_paper.html), 2022 



### Audio-visual Localization

#### Sound Localization in Videos
* [Objects that Sound](https://openaccess.thecvf.com/content_ECCV_2018/html/Relja_Arandjelovic_Objects_that_Sound_ECCV_2018_paper.html), 2018
* [Audio-Visual Scene Analysis with Self-Supervised Multisensory Features](https://openaccess.thecvf.com/content_ECCV_2018/html/Andrew_Owens_Audio-Visual_Scene_Analysis_ECCV_2018_paper.html), 2018
* [The Sound of Pixels](https://openaccess.thecvf.com/content_ECCV_2018/html/Hang_Zhao_The_Sound_of_ECCV_2018_paper.html), 2018
* [Learning to Localize Sound Sources in Visual Scenes: Analysis and Applications](https://ieeexplore.ieee.org/abstract/document/8894565/), 2019
* [Self-supervised Audio-visual Co-segmentation](https://ieeexplore.ieee.org/abstract/document/8682467), 2019
* [The Sound of Motions](https://openaccess.thecvf.com/content_ICCV_2019/html/Zhao_The_Sound_of_Motions_ICCV_2019_paper.html), 2019
* [Deep Multimodal Clustering for Unsupervised Audiovisual Learning](https://openaccess.thecvf.com/content_CVPR_2019/html/Hu_Deep_Multimodal_Clustering_for_Unsupervised_Audiovisual_Learning_CVPR_2019_paper.html), 2019
* [Localizing Visual Sounds the Hard Way](https://openaccess.thecvf.com/content/CVPR2021/html/Chen_Localizing_Visual_Sounds_the_Hard_Way_CVPR_2021_paper.html), 2021
* [Class-aware Sounding Objects Localization via Audiovisual Correspondence](https://ieeexplore.ieee.org/abstract/document/9662191/), 2021   
* [Mix and Localize: Localizing Sound Sources in Mixtures](https://openaccess.thecvf.com/content/CVPR2022/html/Hu_Mix_and_Localize_Localizing_Sound_Sources_in_Mixtures_CVPR_2022_paper.html), 2022
* [Audio-Visual Segmentation](https://arxiv.org/abs/2207.05042), 2022


#### Audio-visual Saliency Detection
* [DAVE: A Deep Audio-Visual Embedding for Dynamic Saliency Prediction](https://arxiv.org/abs/1905.10693), 2019
* [STAViS: Spatio-Temporal AudioVisual Saliency Network](https://openaccess.thecvf.com/content_CVPR_2020/html/Tsiami_STAViS_Spatio-Temporal_AudioVisual_Saliency_Network_CVPR_2020_paper.html), 2020
* [A Multimodal Saliency Model for Videos With High Audio-visual Correspondence](https://ieeexplore.ieee.org/abstract/document/8962278/), 2020   
* [ViNet: Pushing the limits of Visual Modality for Audio-Visuav Saliency Prediction](https://ieeexplore.ieee.org/abstract/document/9635989), 2021
* [From Semantic Categories to Fixations: A Novel Weakly-Supervised Visual-Auditory Saliency Detection Approach](https://openaccess.thecvf.com/content/CVPR2021/html/Wang_From_Semantic_Categories_to_Fixations_A_Novel_Weakly-Supervised_Visual-Auditory_Saliency_CVPR_2021_paper.html), 2021


#### Audio-visual Navigation
* [SoundSpaces: Audio-Visual Navigation in 3D Environments](https://link.springer.com/chapter/10.1007/978-3-030-58539-6_2), 2020
* [Look, Listen, and Act: Towards Audio-Visual Embodied Navigation](https://ieeexplore.ieee.org/abstract/document/9197008), 2020
* [Learning to Set Waypoints for Audio-Visual Navigation](https://arxiv.org/abs/2008.09622), 2020
* [Semantic Audio-Visual Navigation](https://openaccess.thecvf.com/content/CVPR2021/html/Chen_Semantic_Audio-Visual_Navigation_CVPR_2021_paper.html), 2021
* [Catch Me If You Hear Me: Audio-Visual Navigation in Complex Unmapped Environments with Moving Sounds](https://arxiv.org/abs/2111.14843), 2021
* [Move2Hear: Active Audio-Visual Source Separation](https://openaccess.thecvf.com/content/ICCV2021/html/Majumder_Move2Hear_Active_Audio-Visual_Source_Separation_ICCV_2021_paper.html), 2021
* [Sound Adversarial Audio-Visual Navigation](https://arxiv.org/abs/2202.10910), 2022 



### Audio-visual Event Localization and Parsing
#### Localization
* [Audio-visual Event Localization in Unconstrained Videos](https://openaccess.thecvf.com/content_ECCV_2018/html/Yapeng_Tian_Audio-Visual_Event_Localization_ECCV_2018_paper.html), 2018
* [Dual-modality Seq2Seq Network for Audio-visual Event Localization](https://ieeexplore.ieee.org/abstract/document/8683226/), 2019 
* [Dual Attention Matching for Audio-Visual Event Localization](https://openaccess.thecvf.com/content_ICCV_2019/html/Wu_Dual_Attention_Matching_for_Audio-Visual_Event_Localization_ICCV_2019_paper.html), 2019
* [Cross-Modal Attention Network for Temporal Inconsistent Audio-Visual Event Localization](https://ojs.aaai.org/index.php/AAAI/article/view/5361), 2020
* [Audiovisual Transformer with Instance Attention for Audio-Visual Event Localization](https://openaccess.thecvf.com/content/ACCV2020/html/Lin_Audiovisual_Transformer_with_Instance_Attention_for_Audio-Visual_Event_Localization_ACCV_2020_paper.html), 2020 
* [Audio-Visual Event Localization via Recursive Fusion by Joint Co-Attention](https://openaccess.thecvf.com/content/WACV2021/html/Duan_Audio-Visual_Event_Localization_via_Recursive_Fusion_by_Joint_Co-Attention_WACV_2021_paper.html), 2021
* [Positive Sample Propagation along the Audio-Visual Event Line](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhou_Positive_Sample_Propagation_Along_the_Audio-Visual_Event_Line_CVPR_2021_paper.pdf), 2021
* [Cross-Modal Background Suppression for Audio-Visual Event Localization](https://openaccess.thecvf.com/content/CVPR2022/html/Xia_Cross-Modal_Background_Suppression_for_Audio-Visual_Event_Localization_CVPR_2022_paper.html), 2022


#### Parsing
* [Unified Multisensory Perception: Weakly-Supervised Audio-Visual Video Parsing](https://link.springer.com/chapter/10.1007/978-3-030-58580-8_26), 2020
* [Exploring Heterogeneous Clues for Weakly-Supervised Audio-Visual Video Parsing](https://openaccess.thecvf.com/content/CVPR2021/html/Wu_Exploring_Heterogeneous_Clues_for_Weakly-Supervised_Audio-Visual_Video_Parsing_CVPR_2021_paper.html), 2021
* [Exploring Cross-Video and Cross-Modality Signals for Weakly-Supervised Audio-Visual Video Parsing](https://proceedings.neurips.cc/paper/2021/hash/5f93f983524def3dca464469d2cf9f3e-Abstract.html), 2021
* [Investigating Modality Bias in Audio Visual Video Parsing](https://arxiv.org/abs/2203.16860), 2022
* [Distributed Audio-Visual Parsing Based On Multimodal Transformer and Deep Joint Source Channel Coding](https://ieeexplore.ieee.org/abstract/document/9746660/), 2022  



### Audio-visual Question Answering and Dialog
#### Question Answering
* [Pano-AVQA: Grounded Audio-Visual Question Answering on 360deg Videos](https://openaccess.thecvf.com/content/ICCV2021/html/Yun_Pano-AVQA_Grounded_Audio-Visual_Question_Answering_on_360deg_Videos_ICCV_2021_paper.html), 2021
* [Learning To Answer Questions in Dynamic Audio-Visual Scenarios](https://openaccess.thecvf.com/content/CVPR2022/html/Li_Learning_To_Answer_Questions_in_Dynamic_Audio-Visual_Scenarios_CVPR_2022_paper.html), 2022


#### Dialog
* [Audio Visual Scene-Aware Dialog](https://openaccess.thecvf.com/content_CVPR_2019/html/Alamri_Audio_Visual_Scene-Aware_Dialog_CVPR_2019_paper.html), 2019
* [Joint Student-Teacher Learning for Audio-Visual Scene-Aware Dialog](https://www.merl.com/publications/docs/TR2019-097.pdf), 2019
* [End-to-end Audio Visual Scene-aware Dialog Using Multimodal Attention-based Video Features](https://ieeexplore.ieee.org/abstract/document/8682583), 2019
* [A Simple Baseline for Audio-Visual Scene-Aware Dialog](https://openaccess.thecvf.com/content_CVPR_2019/html/Schwartz_A_Simple_Baseline_for_Audio-Visual_Scene-Aware_Dialog_CVPR_2019_paper.html), 2019
* [Dynamic Graph Representation Learning for Video Dialog via Multi-Modal Shuffled Transformers](https://ojs.aaai.org/index.php/AAAI/article/view/16231), 2021
* [Audio-Visual Scene-Aware Dialog and Reasoning Using Audio-Visual Transformers with Joint Student-Teacher Learning](https://ieeexplore.ieee.org/abstract/document/9746481), 2022  


## Datasets


| Dataset             | Year            | # Videos | Length  | # Classes        | Video source             | Task                                                           |
| ------------------- | --------------- | -------- | ------- | ---------------- | ------------------------ | -------------------------------------------------------------- |
| LRW, LR2, LR3       | 2016, 2018,2018 | -        | 800h+   | 5k+ (identities) | in the wild              | Speech-related, speaker-related, face generation related tasks |
| VoxCeleb, VoxCeleb2 | 2017,2018       | -        | 2000h+  | 7k+(identities)  | Youtube                  | Speech-related, speaker-related, face generation related tasks |
| AVA-AvtiveSpeakers  | 2019            | -        | 38.5h+  | -                | YouTube                  | Speech-related task, speaker-related task                      |
| Kinetics-400        | 2017            | 306,245  | 850h+   | 400              | Youtube                  | Action recognition                                             |
| EPIC-KITCHENS       | 2018            | 39,594   | 55h     | 32               | Recorded videos          | Action recognition                                             |
| CMU-MOSI            | 2016            | 2,199    | 2h+     | 8                | YouTube                  | Emotion recognition                                            |
| CMU-MOSEI           | 2018            | 23,453   | 65h+    | -                | YouTube                  | Emotion recognition                                            |
| VGGSound            | 2020            | 200k+    | 550h+   | 310+             | YouTube                  | Action recognition, sound localization                         |
| AudioSet            | 2017            | 2M+      | 5,800h+ | 632              | YouTube                  | Action recognition, sound sepearation                          |
| Greatest Hits       | 2016            | 977      | 9h+     | -                | Recorded videos          | Sound generation                                               |
| MUSIC               | 2018            | 714      | 23h+    | 11               | YouTube                  | Sound seperation, sound localization                           |
| FAIR-Play           | 2019            | 1,871    | 5.2h    | -                | Recorded videos          | Spatial sound generation                                       |
| YT-ALL              | 2018            | 1,146    | 113.1h  | -                | YouTube                  | Spatial sound generation                                       |
| Replica             | 2019            | -        | -       | 88               | Photo-realistic 3D scene | Depth estimation                                               |
| AIST++              | 2021            | -        | 5.2h    | -                | Recorded videos          | Motin generation                                               |
| TED                 | 2019            | -        | 52h     | -                | TED talks                | Gesture generation                                             |
| SumMe               | 2014            | 25       | 1h+     | -                | User videos              | Saliency detection                                             |
| AVE                 | 2018            | 4,143    | 11h+    | 28               | YouTube                  | Event localization                                             |
| LLP                 | 2020            | 11,849   | 32.9h   | 25               | YouTube                  | Event parsing                                                  |
| SoundSpaces         | 2020            | -        | -       | -                | 3D environment           | Audio-visual navigation                                        |
| AVSD                | 2019            | 11,816   | 98h+    | -                | Crowd-sourced            | Audio-visual dialog                                            |
| Pano-AVQA           | 2021            | 5.4k     | 7.7h    | -                | Video-sharing platforms  | Audio-visual question answering                                |
| MUSIC-AVQA          | 2022            | 9,288    | 150h+   | -                | YouTube                  | Audio-visual question answering                                |



