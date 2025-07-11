
[![paper](https://img.shields.io/badge/Paper-arxiv-b31b1b)](https://arxiv.org/pdf/2405.03770)
&nbsp;
[![welcome](https://img.shields.io/badge/Issues&#44;%20Comments&#44;%20and%20Questions-are%20all%20welcomed&#33;-f39f37)](https://github.com/NeeluMadan/ViFM_Survey/issues)


# [Foundation Models for Video Understanding: A Survey](https://arxiv.org/pdf/2405.03770)
Neelu Madan, Andreas Moegelmose, Rajat Modi, Yogesh S. Rawat, Thomas B. Moeslund


![benchmark](./Images/video_papers.png)

# Motivation
The field of video understanding is undergoing significant advancement, as evidenced by the increasing number of research publications focused on various video understanding tasks (Figure below). This growth coincides with the development of large-scale pretraining techniques. These techniques have demonstrated remarkable capabilities in adapting to diverse tasks, requiring minimal additional training with robust generalization. As a result, researchers are actively investigating the role of these foundational models to address a broad spectrum of video understanding challenges. We surveyed more than 200 foundation models, analyzing their performance over several common video tasks. Our survey, [Foundation Model for Video Understanding: A Survey](https://arxiv.org/pdf/2405.03770), also provides an overview of 16 different video tasks, including their benchmarks and evaluation metrics.

![benchmark](./Images/Model_Task_Progress.png)

# Main Classification
![benchmark](./Images/MainClassification.png)

# Menu
- [Image-based Video Foundation Models](#Image-based)
- [Video-based Video Foundation Models](#Video-based)
- [Universal Foundation Models](#Universal)


# Image-based
**Distilling Vision-Language Models on Millions of Videos.** _(Distill-VLM)_. [CVPR, 2024]. <br>
*Yue Zhao, Long Zhao, Xingyi Zhou, Jialin Wu, Chun-Te Chu, Hui Miao, Florian Schroff, Hartwig Adam, Ting Liu, Boqing Gong, Philipp Krähenbühl, Liangzhe Yuan.*<br>
[[Paper](https://arxiv.org/pdf/2401.06129.pdf)] 

**COSA: Concatenated Sample Pretrained Vision-Language Foundation Model.** _(COSA)_. [ICLR, 2024]. <br>
*Sihan Chen, Xingjian He, Handong Li, Xiaojie Jin, Jiashi Feng, Jing Liu.*<br>
[[Paper](https://openreview.net/pdf?id=bDkisS75zy)] [[Code](https://github.com/TXH-mercury/COSA)]

**FROSTER: Frozen CLIP Is A Strong Teacher for Open-Vocabulary Action Recognition.** _(FROSTER)_. [ICLR, 2024]. <br>
*Xiaohu Huang, Hao Zhou, Kun Yao, Kai Han.*<br>
[[Paper](https://arxiv.org/pdf/2402.03241)] [[Code](https://github.com/Visual-AI/FROSTER)]

**EZ-CLIP: Efficient Zeroshot Video Action Recognition.** _(EZ-CLIP)_. [arxiv, 2024]. <br>
*Shahzad Ahmad, Sukalpa Chanda, Yogesh S Rawat.*<br>
[[Paper](https://arxiv.org/pdf/2312.08010)] [[Code](https://github.com/Shahzadnit/EZ-CLIP)]

**M2-CLIP: A Multimodal, Multi-task Adapting Framework for Video Action Recognition.** _(M2-CLIP)_. [arxiv, 2024]. <br>
*Mengmeng Wang, Jiazheng Xing, Boyuan Jiang, Jun Chen, Jianbiao Mei, Xingxing Zuo, Guang Dai, Jingdong Wang, Yong Liu.*<br>
[[Paper](https://arxiv.org/pdf/2401.11649)] 

**PaLM2-VAdapter: Progressively Aligned Language Model Makes a Strong Vision-language Adapter.** _(PaLM2-VAdapter)_. [arxiv, 2024]. <br>
*Junfei Xiao, Zheng Xu, Alan Yuille, Shen Yan, Boyu Wang.*<br>
[[Paper](https://arxiv.org/pdf/2402.10896)] 

**Question-Instructed Visual Descriptions for Zero-Shot Video Question Answering.** _(Q-ViD)_. [arxiv, 2024]. <br>
*David Romero, Thamar Solorio.*<br>
[[Paper](https://arxiv.org/pdf/2402.10698)] 

**Revealing Single Frame Bias for Video-and-Language Learning.** _(Singularity)_. [ACL, 2023]. <br>
*Jie Lei, Tamara L Berg, Mohit Bansal.*<br>
[[Paper](https://aclanthology.org/2023.acl-long.29.pdf)] [[Code](https://github.com/jayleicn/singularity)]

**AdaCLIP: Towards Pragmatic Multimodal Video Retrieval.** _(AdaCLIP)_. [ACM-MM, 2023]. <br>
*Zhiming Hu, Angela Ning Ye, Salar Hosseini Khorasgani, Iqbal Mohomed.*<br>
[[Paper](https://dl.acm.org/doi/pdf/10.1145/3581783.3612161)] [[Code](https://github.com/SamsungLabs/AdaCLIP)]

**CLIP4Caption: CLIP for Video Caption.** _(CLIP4Caption)_. [ACM-MM, 2023]. <br>
*Mingkang Tang, Zhanyu Wang, Zhenhua Liu, Fengyun Rao, Dian Li, Xiu Li.*<br>
[[Paper](https://dl.acm.org/doi/pdf/10.1145/3474085.3479207)] 

**RTQ: Rethinking Video-language Understanding Based on Image-text Model.** _(RTQ)_. [ACM Multimedia, 2023]. <br>
*Kunchang Li, Yali Wang, Yizhuo Li, Yi Wang, Yinan He, Limin Wang, Yu Qiao.*<br>
[[Paper](https://dl.acm.org/doi/pdf/10.1145/3581783.3612152)] [[Code](https://github.com/SCZwangxiao/RTQ-MM2023)]

**Seeing in Flowing: Adapting CLIP for Action Recognition with Motion Prompts Learning.** [ACM Multimedia, 2023]. <br>
*Qiang Wang, Junlong Du, Ke Yan, Shouhong Ding.*<br>
[[Paper](https://arxiv.org/pdf/2308.04828)]

**Align your Latents: High-Resolution Video Synthesis with Latent Diffusion Models.** _(VideoLDM)_. [CVPR, 2023]. <br>
*Wenhao Wu, Xiaohan Wang, Haipeng Luo, Jingdong Wang, Yi Yang, Wanli Ouyang.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Blattmann_Align_Your_Latents_High-Resolution_Video_Synthesis_With_Latent_Diffusion_Models_CVPR_2023_paper.pdf)] 

**Bidirectional Cross-Modal Knowledge Exploration for Video Recognition with Pre-trained Vision-Language Models.** _(BIKE)_. [CVPR, 2023]. <br>
*Wenhao Wu, Xiaohan Wang, Haipeng Luo, Jingdong Wang, Yi Yang, Wanli Ouyang.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Wu_Bidirectional_Cross-Modal_Knowledge_Exploration_for_Video_Recognition_With_Pre-Trained_Vision-Language_CVPR_2023_paper.pdf)] [[Code](https://github.com/whwu95/BIKE)]

**Dual-path Adaptation from Image to Video Transformers.** _(DualPath)_. [CVPR, 2023]. <br>
*Jungin Park, Jiyoung Lee, Kwanghoon Sohn.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Park_Dual-Path_Adaptation_From_Image_to_Video_Transformers_CVPR_2023_paper.pdf)] [[Code](https://github.com/park-jungin/DualPath.git)]

**Fine-tuned CLIP Models are Efficient Video Learners.** _(ViFi-CLIP)_. [CVPR, 2023]. <br>
*Hanoona Rasheed, Muhammad Uzair Khattak, Muhammad Maaz, Salman Khan, Fahad Shahbaz Khan.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Rasheed_Fine-Tuned_CLIP_Models_Are_Efficient_Video_Learners_CVPR_2023_paper.pdf)] [[Code](https://github.com/muzairkhattak/ViFi-CLIP)]

**VoP: Text-Video Co-operative Prompt Tuning for Cross-Modal Retrieval.** _(VoP)_. [CVPR, 2023]. <br>
*Siteng Huang, Biao Gong, Yulin Pan, Jianwen Jiang, Yiliang Lv, Yuyuan Li, Donglin Wang.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Huang_VoP_Text-Video_Co-Operative_Prompt_Tuning_for_Cross-Modal_Retrieval_CVPR_2023_paper.pdf)] [[Code](https://github.com/bighuang624/VoP)]

**Vita-CLIP: Video and text adaptive CLIP via Multimodal Prompting.** _(Vita-CLIP)_. [CVPR, 2023]. <br>
*Syed Talal Wasim, Muzammal Naseer, Salman Khan, Fahad Shahbaz Khan, Mubarak Shah.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Wasim_Vita-CLIP_Video_and_Text_Adaptive_CLIP_via_Multimodal_Prompting_CVPR_2023_paper.pdf)] [[Code](https://github.com/TalalWasim/Vita-CLIP)]

**Disentangling Spatial and Temporal Learning for Efficient Image-to-Video Transfer Learning.** _(DiST)_. [ICCV, 2023]. <br>
*Zhiwu Qing, Shiwei Zhang, Ziyuan Huang, Yingya Zhang, Changxin Gao, Deli Zhao, Nong Sang.*<br>
[[Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Qing_Disentangling_Spatial_and_Temporal_Learning_for_Efficient_Image-to-Video_Transfer_Learning_ICCV_2023_paper.pdf)] [[Code](https://github.com/alibaba-mmai-research/DiST)]

**Preserve Your Own Correlation: A Noise Prior for Video Diffusion Models.** _(pyoco)_. [ICCV, 2023]. <br>
*Kunchang Li, Yali Wang, Yizhuo Li, Yi Wang, Yinan He, Limin Wang, Yu Qiao.*<br>
[[Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Ge_Preserve_Your_Own_Correlation_A_Noise_Prior_for_Video_Diffusion_ICCV_2023_paper.pdf)] [[Demo](https://research.nvidia.com/labs/dir/pyoco/)]

**Unmasked Teacher: Towards Training-Efficient Video Foundation Models.** _(UMT)_. [ICCV, 2023]. <br>
*Kunchang Li, Yali Wang, Yizhuo Li, Yi Wang, Yinan He, Limin Wang, Yu Qiao.*<br>
[[Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_Unmasked_Teacher_Towards_Training-Efficient_Video_Foundation_Models_ICCV_2023_paper.pdf)] [[Code](https://github.com/OpenGVLab/unmasked_teacher.git)]
 
**Alignment and Generation Adapter for Efficient Video-text Understanding.** _(AG-Adapter)_. [ICCVW, 2023]. <br>
*Han Fang, Zhifei Yang, Yuhan Wei, Xianghao Zang, Chao Ban, Zerun Feng, Zhongjiang He, Yongxiang Li, Hao Sun.*<br>
[[Paper](https://openaccess.thecvf.com/content/ICCV2023W/CLVL/papers/Fang_Alignment_and_Generation_Adapter_for_Efficient_Video-Text_Understanding_ICCVW_2023_paper.pdf)] 

**AIM: Adapting Image Models for Efficient Video Action Recognition.** _(AIM)_. [ICLR, 2023]. <br>
*Taojiannan Yang, Yi Zhu, Yusheng Xie, Aston Zhang, Chen Chen, Mu Li.*<br>
[[Paper](https://openreview.net/pdf?id=CIoSZ_HKHS7)] [[Code](https://adapt-image-models.github.io/)]

**MAtch, eXpand and Improve: Unsupervised Finetuning for Zero-Shot Action Recognition with Language Knowledge.** _(MAXI)_. [ICCV, 2023]. <br>
*Wei Lin, Leonid Karlinsky, Nina Shvetsova, Horst Possegger, Mateusz Kozinski, Rameswar Panda, Rogerio Feris, Hilde Kuehne, Horst Bischof.*<br>
[[Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Lin_MAtch_eXpand_and_Improve_Unsupervised_Finetuning_for_Zero-Shot_Action_Recognition_ICCV_2023_paper.pdf)] [[Code](https://github.com/wlin-at/MAXI)]

**Prompt Switch: Efficient CLIP Adaptation for Text-Video Retrieval.** _(PromptSwitch)_. [ICCV, 2023]. <br>
*Chaorui Deng, Qi Chen, Pengda Qin, Da Chen, Qi Wu.*<br>
[[Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Deng_Prompt_Switch_Efficient_CLIP_Adaptation_for_Text-Video_Retrieval_ICCV_2023_paper.pdf)] [[Code](https://github.com/bladewaltz1/PromptSwitch)]

**Progressive Spatio-Temporal Prototype Matching for Text-Video Retrieval.** _(ProST)_. [ICCV, 2023]. <br>
*Pandeng Li, Chen-Wei Xie, Liming Zhao, Hongtao Xie, Jiannan Ge, Yun Zheng, Deli Zhao, Yongdong Zhang.*<br>
[[Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_Progressive_Spatio-Temporal_Prototype_Matching_for_Text-Video_Retrieval_ICCV_2023_paper.pdf)] [[Code](https://github.com/IMCCretrieval/ProST)]

**Tem-adapter: Adapting Image-Text Pretraining for Video Question Answer.** _(Temp-adapter)_. [ICCV, 2023]. <br>
*Guangyi Chen, Xiao Liu, Guangrun Wang, Kun Zhang, Philip H.S.Torr, Xiao-Ping Zhang, Yansong Tang.*<br>
[[Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Chen_Tem-Adapter_Adapting_Image-Text_Pretraining_for_Video_Question_Answer_ICCV_2023_paper.pdf)] [[Code](https://github.com/XLiu443/Tem-adapter)]

**Tracking Anything with Decoupled Video Segmentation.** _(DEVA)_. [ICCV, 2023]. <br>
*Guangyi Chen, Xiao Liu, Guangrun Wang, Kun Zhang, Philip H.S.Torr, Xiao-Ping Zhang, Yansong Tang.*<br>
[[Paper](https://arxiv.org/pdf/2309.03903)] [[Code](https://github.com/hkchengrex/Tracking-Anything-with-DEVA)]

**Alignment and Generation Adapter for Efficient Video-text Understanding.** _(AG-Adapter)_. [ICCVW, 2023]. <br>
*Han Fang; Zhifei Yang; Yuhan Wei; Xianghao Zang; Chao Ban; Zerun Feng; Zhongjiang He; Yongxiang Li; Hao Sun.*<br>
[[Paper](https://openaccess.thecvf.com/content/ICCV2023W/CLVL/papers/Fang_Alignment_and_Generation_Adapter_for_Efficient_Video-Text_Understanding_ICCVW_2023_paper.pdf)] 

**Zero-Shot and Few-Shot Video Question Answering with Multi-Modal Prompts.** _(ViTiS)_. [ICCVW, 2023]. <br>
*Deniz Engin, Yannis Avrithis.*<br>
[[Paper](https://arxiv.org/pdf/2309.15915)] [[Code](https://github.com/engindeniz/vitis)]

**CLIP-ViP: Adapting Pre-trained Image-Text Model to Video-Language Representation Alignment.** _(CLIP-ViP)_. [ICLR, 2023]. <br>
*Hongwei Xue, Yuchong Sun, Bei Liu, Jianlong Fu, Ruihua Song, Houqiang Li, Jiebo Luo.*<br>
[[Paper](https://arxiv.org/pdf/2209.06430.pdf)] [[Code](https://github.com/microsoft/XPretrain/tree/main/CLIP-ViP)]

**Alternating Gradient Descent and Mixture-of-Experts for Integrated Multimodal Perception.** _(IMP)_. [NeurIPS, 2023]. <br>
*Hassan Akbari, Dan Kondratyuk, Yin Cui, Rachel Hornung, Huisheng Wang, Hartwig Adam.*<br>
[[Paper](https://openreview.net/pdf?id=uTlKUAm68H)]

**Bootstrapping Vision-Language Learning with Decoupled Language Pre-training.** _(P-Former)_. [NeurIPS, 2023]. <br>
*Yiren Jian, Chongyang Gao, Soroush Vosoughi.*<br>
[[Paper](https://openreview.net/pdf?id=8Kch0ILfQH)] [[Code](https://github.com/yiren-jian/BLIText)]

**InstructBLIP: Towards General-purpose Vision-Language Models with Instruction Tuning.** _(InstructBLIP)_. [NeurIPS, 2023]. <br>
*Wenliang Dai, Junnan Li, Dongxu Li, Anthony Meng Huat Tiong, Junqi Zhao, Weisheng Wang, Boyang Li, Pascale Fung, Steven Hoi.*<br>
[[Paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/9a6a435e75419a836fe47ab6793623e6-Paper-Conference.pdf)] [[Code](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip)]

**Language-based Action Concept Spaces Improve Video Self-Supervised Learning.** _(LSS)_. [NeurIPS, 2023]. <br>
*Kanchana Ranasinghe, Michael Ryoo.*<br>
[[Paper](https://openreview.net/pdf?id=oyFyOPZUCs)] 

**MaMMUT: A Simple Architecture for Joint Learning for MultiModal Tasks.** _(MaMMUT)_. [TMLR, 2023]. <br>
*Weicheng Kuo, AJ Piergiovanni, Dahun Kim, Xiyang Luo, Ben Caine, Wei Li, Abhijit Ogale, Luowei Zhou, Andrew Dai, Zhifeng Chen, Claire Cui, Anelia Angelova.*<br>
[[Paper](https://openreview.net/pdf?id=FqOG4osY7C)] [[Code](https://github.com/lucidrains/MaMMUT-pytorch)]

**MEME: Multi-Encoder Multi-Expert Framework with Data Augmentation for Video Retrieval.** _(MEME)_. [SIGIR, 2023]. <br>
*Seong-Min Kang, Yoon-Sik Cho.*<br>
[[Paper](https://dl.acm.org/doi/pdf/10.1145/3539618.3591726)] [[Code](https://github.com/kang7734/MEME__/tree/main/X-CLIP)]

**EVA-CLIP: Improved Training Techniques for CLIP at Scale.** _(EVA-CLIP)_. [arxiv, 2023]. <br>
*Quan Sun, Yuxin Fang, Ledell Wu, Xinlong Wang, Yue Cao.*<br>
[[Paper](https://arxiv.org/pdf/2303.15389)] [[Code](https://github.com/baaivision/EVA/tree/master/EVA-CLIP)]

**Fine-grained Text-Video Retrieval with Frozen Image Encoders.** _(CrossVTR)_. [arxiv, 2023]. <br>
*Zuozhuo Dai, Fangtao Shao, Qingkun Su, Zilong Dong, Siyu Zhu.*<br>
[[Paper](https://arxiv.org/pdf/2307.09972)] 

**Harvest Video Foundation Models via Efficient Post-Pretraining.** _(Harvest)_. [arxiv, 2023]. <br>
*Yizhuo Li, Kunchang Li, Yinan He, Yi Wang, Yali Wang, Limin Wang, Yu Qiao, Ping Luo.*<br>
[[Paper](https://arxiv.org/pdf/2310.19554.pdf)] [[Code](https://github.com/OpenGVLab/InternVideo)]

**Motion-Conditioned Diffusion Model for Controllable Video Synthesis.** _(MCDiff)_. [arxiv, 2023]. <br>
*Tsai-Shien Chen, Chieh Hubert Lin, Hung-Yu Tseng, Tsung-Yi Lin, Ming-Hsuan Yang.*<br>
[[Paper](https://arxiv.org/pdf/2304.14404)] 

**Mug-STAN: Adapting Image-Language Pretrained Models for General Video Understanding.** _(Mug-STAN)_. [arxiv, 2023]. <br>
*Ruyang Liu, Jingjia Huang, Wei Gao, Thomas H. Li, Ge Li.*<br>
[[Paper](https://arxiv.org/pdf/2311.15075)] [[Code](https://github.com/farewellthree/STAN)]

**PaLM2-VAdapter: Progressively Aligned Language Model Makes a Strong Vision-language Adapter.** _(PaLM2-VAdapter)_. [arxiv, 2023]. <br>
*Junfei Xiao, Zheng Xu, Alan Yuille, Shen Yan, Boyu Wang.*<br>
[[Paper](https://arxiv.org/pdf/2402.10896)] 

**RefSAM: Efficiently Adapting Segmenting Anything Model for Referring Video Object Segmentation.** _(RefSAM)_. [arxiv, 2023]. <br>
*Yonglin Li, Jing Zhang, Xiao Teng, Long Lan.*<br>
[[Paper](https://arxiv.org/pdf/2307.00997)] 

**Segment and Track Anything.** _(SAM-Track)_. [arxiv, 2023]. <br>
*Yangming Cheng, Liulei Li, Yuanyou Xu, Xiaodi Li, Zongxin Yang, Wenguan Wang, Yi Yang.*<br>
[[Paper](https://arxiv.org/pdf/2305.06558)] [[Code](https://github.com/z-x-yang/Segment-and-Track-Anything)]

**Segment Anything Meets Point Tracking.** _(SAM-PT)_. [arxiv, 2023]. <br>
*Frano Rajič, Lei Ke, Yu-Wing Tai, Chi-Keung Tang, Martin Danelljan, Fisher Yu.*<br>
[[Paper](https://arxiv.org/pdf/2307.01197)] [[Code](https://github.com/SysCV/sam-pt)]

**Track Anything: Segment Anything Meets Videos.** _(TAM)_. [arxiv, 2023]. <br>
*Jinyu Yang, Mingqi Gao, Zhe Li, Shang Gao, Fangjing Wang, Feng Zheng.*<br>
[[Paper](https://arxiv.org/pdf/2304.11968)] [[Code](https://github.com/gaomingqi/Track-Anything)]

**Tracking Anything in High Quality.** _(HQTrack)_. [arxiv, 2023]. <br>
*Jiawen Zhu, Zhenyu Chen, Zeqi Hao, Shijie Chang, Lu Zhang, Dong Wang, Huchuan Lu, Bin Luo, Jun-Yan He, Jin-Peng Lan, Hanyuan Chen, Chenyang Li.*<br>
[[Paper](https://arxiv.org/pdf/2307.13974)] [[Code](https://github.com/jiawen-zhu/HQTrack)]

**TaCA: Upgrading Your Visual Foundation Model with Task-agnostic Compatible Adapter.** _(TaCA)_. [arxiv, 2023]. <br>
*Binjie Zhang, Yixiao Ge, Xuyuan Xu, Ying Shan, Mike Zheng Shou.*<br>
[[Paper](https://arxiv.org/pdf/2306.12642)] 

**UVOSAM: A Mask-free Paradigm for Unsupervised Video Object Segmentation via Segment Anything Model.** _(UVOSAM)_. [arxiv, 2023]. <br>
*Zhenghao Zhang, Shengfan Zhang, Zhichao Wei, Zuozhuo Dai, Siyu Zhu.*<br>
[[Paper](https://arxiv.org/pdf/2305.12659)] [[Code](https://github.com/alibaba/UVOSAM)] 

**Videoprompter: an ensemble of foundational models for zero-shot video understanding.** _(Videoprompter)_. [arxiv, 2023]. <br>
*Adeel Yousaf, Muzammal Naseer, Salman Khan, Fahad Shahbaz Khan, Mubarak Shah.*<br>
[[Paper](https://arxiv.org/pdf/2310.15324)] 
 
**ZEETAD: Adapting Pretrained Vision-Language Model for Zero-Shot End-to-End Temporal Action Detection.** _(ZEETAD)_. [WACV, 2024]. <br>
*Thinh Phan, Khoa Vo, Duy Le, Gianfranco Doretto, Donald Adjeroh, Ngan Le.*<br>
[[Paper](https://openaccess.thecvf.com/content/WACV2024/papers/Phan_ZEETAD_Adapting_Pretrained_Vision-Language_Model_for_Zero-Shot_End-to-End_Temporal_Action_WACV_2024_paper.pdf)] [[Code](https://github.com/leexinhao/ZeroI2V)]

**ZeroI2V: Zero-Cost Adaptation of Pre-trained Transformers from Image to Video.** _(ZeroI2V)_. [arxiv, 2023]. <br>
*Xinhao Li, Limin Wang.*<br>
[[Paper](https://arxiv.org/pdf/2310.01324)] [[Code](https://github.com/leexinhao/ZeroI2V)]

**FitCLIP: Refining Large-Scale Pretrained Image-Text Models for Zero-Shot Video Understanding Tasks.** _(FitCLIP)_. [BMVC, 2022]. <br>
*Santiago Castro and Fabian Caba.*<br>
[[Paper](https://bmvc2022.mpi-inf.mpg.de/0939.pdf)] [[Code](https://github.com/bryant1410/fitclip)]

**Cross Modal Retrieval with Querybank Normalisation.** _(QB-Norm)_. [CVPR, 2022]. <br>
*Simion-Vlad Bogolin, Ioana Croitoru, Hailin Jin, Yang Liu, Samuel Albanie.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Bogolin_Cross_Modal_Retrieval_With_Querybank_Normalisation_CVPR_2022_paper.pdf)] [[Code](https://github.com/ioanacroi/qb-norm)]

**Revisiting the "Video" in Video-Language Understanding.** _(ATP)_. [CVPR, 2022]. <br>
*Shyamal Buch, Cristóbal Eyzaguirre, Adrien Gaidon, Jiajun Wu, Li Fei-Fei, Juan Carlos Niebles.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Buch_Revisiting_the_Video_in_Video-Language_Understanding_CVPR_2022_paper.pdf)] [[Code](https://github.com/StanfordVL/atp-video-language)]

**X-Pool: Cross-Modal Language-Video Attention for Text-Video Retrieval.** _(X-Pool)_. [CVPR, 2022]. <br>
*Satya Krishna Gorti, Noel Vouitsis, Junwei Ma, Keyvan Golestan, Maksims Volkovs, Animesh Garg, Guangwei Yu.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Gorti_X-Pool_Cross-Modal_Language-Video_Attention_for_Text-Video_Retrieval_CVPR_2022_paper.pdf)] [[Code](https://github.com/layer6ai-labs/xpool)]

**Frozen CLIP models are Efficient Video Learners.**  _(EVL)_. [ECCV, 2022]. <br>
*Ziyi Lin, Shijie Geng, Renrui Zhang, Peng Gao, Gerard de Melo, Xiaogang Wang, Jifeng Dai, Yu Qiao, Hongsheng Li.*<br>
[[Paper](https://arxiv.org/pdf/2208.03550.pdf)] [[Code](https://github.com/OpenGVLab/efficient-video-recognition.git)]

**Prompting Visual-Language Models for Efficient Video Understanding.** _(Prompt-CLIP)_. [ECCV, 2022]. <br>
*Chen Ju, Tengda Han, Kunhao Zheng, Ya Zhang, Weidi Xie.*<br>
[[Paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136950104.pdf)] [[Code](https://github.com/ju-chen/Efficient-Prompt)]

**Expanding Language-Image Pretrained Models for General Video Recognition.** _(X-CLIP)_. [ECCV, 2022]. <br>
*Bolin Ni, Houwen Peng, Minghao Chen, Songyang Zhang, Gaofeng Meng, Jianlong Fu, Shiming Xiang, Haibin Ling.*<br>
[[Paper](https://arxiv.org/pdf/2208.02816)] [[Code](https://github.com/microsoft/VideoX/tree/master/X-CLIP)]

**ST-Adapter: Parameter-Efficient Image-to-Video Transfer Learning.** _(St-Adapter)_. [NeurIPS, 2022]. <br>
*Junting Pan, Ziyi Lin, Xiatian Zhu, Jing Shao, Hongsheng Li.*<br>
[[Paper](https://openreview.net/pdf?id=uRTW_PgXvc7)] [[Code](https://github.com/linziyi96/st-adapter)]

**CLIP4Clip: An Empirical Study of CLIP for End to End Video Clip Retrieval.** _(CLIP4Clip)_. [Neurocomputing, 2022]. <br>
*Huaishao Luo, Lei Ji, Ming Zhong, Yang Chen, Wen Lei, Nan Duan, Tianrui Li.*<br>
[[Paper](https://arxiv.org/pdf/2104.08860)] [[Code](https://github.com/ArrowLuo/CLIP4Clip)]

**Transferring Image-CLIP to Video-Text Retrieval via Temporal Relations.** _(CLIP2Video)_. [TMM, 2022]. <br>
*Han Fang, Pengfei Xiong, Luhui Xu, Wenhan Luo.*<br>
[[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9973385)] 

**CenterCLIP: Token Clustering for Efficient Text-Video Retrieval.** _(CenterCLIP)_. [SIGIR, 2022]. <br>
*Shuai Zhao, Linchao Zhu, Xiaohan Wang, Yi Yang.*<br>
[[Paper](https://dl.acm.org/doi/pdf/10.1145/3477495.3531950)] [[Code](https://github.com/mzhaoshuai/CenterCLIP)]

**Cross-Modal Adapter for Text-Video Retrieval.** _(Cross-Modal-Adapter)_. [arxiv, 2022]. <br>
*Haojun Jiang, Jianke Zhang, Rui Huang, Chunjiang Ge, Zanlin Ni, Jiwen Lu, Jie Zhou, Shiji Song, Gao Huang.*<br>
[[Paper](https://arxiv.org/pdf/2211.09623)] [[Code](https://github.com/LeapLabTHU/Cross-Modal-Adapter)]

**Imagen Video: High Definition Video Generation with Diffusion Models.** _(Imagen Video)_. [arxiv, 2022]. <br>
*Jonathan Ho, William Chan, Chitwan Saharia, Jay Whang, Ruiqi Gao, Alexey Gritsenko, Diederik P. Kingma, Ben Poole, Mohammad Norouzi, David J. Fleet, Tim Salimans.*<br>
[[Paper](https://arxiv.org/pdf/2210.02303)] [[Demo](https://imagen.research.google/video/)]

**Multimodal Open-Vocabulary Video Classification via Pre-Trained Vision and Language Models.** _(MOV)_. [arxiv, 2022]. <br>
*Rui Qian, Yeqing Li, Zheng Xu, Ming-Hsuan Yang, Serge Belongie, Yin Cui.*<br>
[[Paper](https://arxiv.org/pdf/2207.07646)] 

**VideoCoCa: Video-Text Modeling with Zero-Shot Transfer from Contrastive Captioners.** _(Video-CoCa)_. [arxiv, 2022]. <br>
*Shen Yan, Tao Zhu, Zirui Wang, Yuan Cao, Mi Zhang, Soham Ghosh, Yonghui Wu, Jiahui Yu.*<br>
[[Paper](https://arxiv.org/pdf/2212.04979.pdf)] 
 
**Frozen in Time: A Joint Video and Image Encoder for End-to-End Retrieval.** _(Frozen)_. [ICCV, 2021]. <br>
*Max Bain, Arsha Nagrani, Gül Varol, Andrew Zisserman.*<br>
[[Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Bain_Frozen_in_Time_A_Joint_Video_and_Image_Encoder_for_ICCV_2021_paper.pdf)] [[Code](https://github.com/m-bain/frozen-in-time)]

**ActionCLIP: A New Paradigm for Video Action Recognition.** _(ActionCLIP)_. [arxiv, 2021]. <br>
*Mengmeng Wang, Jiazheng Xing, Yong Liu.*<br>
[[Paper](https://arxiv.org/pdf/2109.08472)] [[Code](https://github.com/sallymmx/ActionCLIP)]

**Improving Video-Text Retrieval by Multi-Stream Corpus Alignment and Dual Softmax Loss.** _(CAMoE)_. [arxiv, 2021]. <br>
*Xing Cheng, Hezheng Lin, Xiangyu Wu, Fan Yang, Dong Shen.*<br>
[[Paper](https://arxiv.org/pdf/2109.04290)]

**End-to-End Learning of Visual Representations from Uncurated Instructional Videos.** _(MIL-NCE)_. [CVPR, 2020]. <br>
*Antoine Miech, Jean-Baptiste Alayrac, Lucas Smaira, Ivan Laptev, Josef Sivic, Andrew Zisserman.*<br>
[[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Miech_End-to-End_Learning_of_Visual_Representations_From_Uncurated_Instructional_Videos_CVPR_2020_paper.pdf)] [[Code](https://github.com/antoine77340/MIL-NCE_HowTo100M.git)]


# Video-based
**MovieChat: From Dense Token to Sparse Memory for Long Video Understanding.** _(MovieChat)_. [CVPR, 2024]. <br>
*Enxin Song, Wenhao Chai, Guanhong Wang, Yucheng Zhang, Haoyang Zhou, Feiyang Wu, Haozhe Chi, Xun Guo, Tian Ye, Yanting Zhang, Yan Lu, Jenq-Neng Hwang, Gaoang Wang.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Song_MovieChat_From_Dense_Token_to_Sparse_Memory_for_Long_Video_CVPR_2024_paper.pdf)] [[Code](https://github.com/rese1f/MovieChat)]

**SRTube: Video-Language Pre-Training with Action-Centric Video Tube Features and Semantic Role Labeling.** _(SRTube)_. [CVPR, 2024]. <br>
*Ju-Hee Lee and Je-Won Kang.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Lee_SRTube_Video-Language_Pre-Training_with_Action-Centric_Video_Tube_Features_and_Semantic_CVPR_2024_paper.pdf)] 

**VidLA: Video-Language Alignment at Scale.** _(VidLA)_. [CVPR, 2024]. <br>
*Mamshad Nayeem Rizve, Fan Fei, Jayakrishnan Unnikrishnan, Son Tran, Benjamin Z. Yao, Belinda Zeng, Mubarak Shah, Trishul Chilimbi.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Rizve_VidLA_Video-Language_Alignment_at_Scale_CVPR_2024_paper.pdf)] 

**ControlVideo: Training-free Controllable Text-to-Video Generation.** _(ControlVideo)_. [ICLR, 2024]. <br>
*Yabo Zhang, Yuxiang Wei, Dongsheng Jiang, Xiaopeng Zhang, Wangmeng Zuo, Qi Tian.*<br>
[[Paper](https://openreview.net/pdf?id=5a79AqFr0c)] [[Code](https://github.com/YBYBZhang/ControlVideo)]

**InternVid: A Large-scale Video-Text Dataset for Multimodal Understanding and Generation.** _(ViCLIP)_. [ICLR, 2024]. <br>
*Yi Wang, Yinan He, Yizhuo Li, Kunchang Li, Jiashuo Yu, Xin Ma, Xinhao Li, Guo Chen, Xinyuan Chen, Yaohui Wang, Ping Luo, Ziwei Liu, Yali Wang, Limin Wang, Yu Qiao.*<br>
[[Paper](https://openreview.net/pdf?id=MLBdiWu4Fw)] [[Code](https://github.com/OpenGVLab/InternVideo/tree/main/Data/InternVid)]

**Mora: Enabling Generalist Video Generation via A Multi-Agent Framework.** _(MORA)_. [arxiv, 2024]. <br>
*Zhengqing Yuan, Ruoxi Chen, Zhaoxu Li, Haolong Jia, Lifang He, Chi Wang, Lichao Sun.*<br>
[[Paper](https://arxiv.org/pdf/2403.13248)] [[Code](https://github.com/lichao-sun/Mora)]

**Memory Consolidation Enables Long-Context Video Understanding.** _(MC-ViT)_. [ICML, 2024]. <br>
*Ivana Balažević, Yuge Shi, Pinelopi Papalampidi, Rahma Chaabouni, Skanda Koppula, Olivier J. Hénaff.*<br>
[[Paper](https://arxiv.org/pdf/2402.05861)]

**Lumiere: A Space-Time Diffusion Model for Video Generation.** _(Lumiere)_. [arxiv, 2024]. <br>
*Omer Bar-Tal, Hila Chefer, Omer Tov, Charles Herrmann, Roni Paiss, Shiran Zada, Ariel Ephrat, Junhwa Hur, Guanghui Liu, Amit Raj, Yuanzhen Li, Michael Rubinstein, Tomer Michaeli, Oliver Wang, Deqing Sun, Tali Dekel, Inbar Mosseri.*<br>
[[Paper](https://arxiv.org/pdf/2401.12945)] [[Demo](https://lumiere-video.github.io/)]

**VideoChat: Chat-Centric Video Understanding.** _(VideoChat)_. [arxiv, 2024]. <br>
*KunChang Li, Yinan He, Yi Wang, Yizhuo Li, Wenhai Wang, Ping Luo, Yali Wang, Limin Wang, Yu Qiao.*<br>
[[Paper](https://arxiv.org/pdf/2305.06355)] [[Code](https://github.com/OpenGVLab/Ask-Anything)]

**VILA: On Pre-training for Visual Language Models.** _(VILA)_. [arxiv, 2024]. <br>
*Ji Lin, Hongxu Yin, Wei Ping, Yao Lu, Pavlo Molchanov, Andrew Tao, Huizi Mao, Jan Kautz, Mohammad Shoeybi, Song Han.*<br>
[[Paper](https://arxiv.org/pdf/2312.07533)] [[Code](https://github.com/NVlabs/VILA)]

**World Model on Million-Length Video And Language With Blockwise RingAttention.** _(LWM)_. [arxiv, 2024]. <br>
*Hao Liu, Wilson Yan, Matei Zaharia, Pieter Abbeel.*<br>
[[Paper](https://arxiv.org/pdf/2402.08268)] [[Code](https://github.com/LargeWorldModel/LWM)]

**Video generation models as world simulators.** _(SORA)_. [OpenAI, 2024]. <br>
*OpenAI.*<br>
[[Link](https://openai.com/index/video-generation-models-as-world-simulators/)] 

**All in One: Exploring Unified Video-Language Pre-training.** _(All-in-One)_. [CVPR, 2023]. <br>
*Alex Jinpeng Wang, Yixiao Ge, Rui Yan, Yuying Ge, Xudong Lin, Guanyu Cai, Jianping Wu, Ying Shan, Xiaohu Qie, Mike Zheng Shou.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_All_in_One_Exploring_Unified_Video-Language_Pre-Training_CVPR_2023_paper.pdf)] [[Code](https://github.com/showlab/all-in-one)]

**Clover: Towards A Unified Video-Language Alignment and Fusion Model.** _(Clover)_. [CVPR, 2023]. <br>
*Jingjia Huang, Yinan Li, Jiashi Feng, Xinglong Wu, Xiaoshuai Sun, Rongrong Ji.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Huang_Clover_Towards_a_Unified_Video-Language_Alignment_and_Fusion_Model_CVPR_2023_paper.pdf)] [[Code](https://github.com/LeeYN-43/Clover)]

**HierVL: Learning Hierarchical Video-Language Embeddings.** _(HierVL)_. [CVPR, 2023]. <br>
*Kumar Ashutosh, Rohit Girdhar, Lorenzo Torresani, Kristen Grauman.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Ashutosh_HierVL_Learning_Hierarchical_Video-Language_Embeddings_CVPR_2023_paper.pdf)] [[Code](https://github.com/facebookresearch/HierVL)]

**LAVENDER: Unifying Video-Language Understanding as Masked Language Modeling.** _(LAVENDER)_. [CVPR, 2023]. <br>
*Linjie Li, Zhe Gan, Kevin Lin, Chung-Ching Lin, Zicheng Liu, Ce Liu, Lijuan Wang.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_LAVENDER_Unifying_Video-Language_Understanding_As_Masked_Language_Modeling_CVPR_2023_paper.pdf)] [[Code](https://github.com/microsoft/LAVENDER)]

**Learning Video Representations from Large Language Models.** _(LaViLa)_. [CVPR, 2023]. <br>
*Yue Zhao, Ishan Misra, Philipp Krähenbühl, Rohit Girdhar.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhao_Learning_Video_Representations_From_Large_Language_Models_CVPR_2023_paper.pdf)] [[Code](https://github.com/facebookresearch/LaViLa)]

**Masked Video Distillation: Rethinking Masked Feature Modeling for Self-supervised Video Representation Learning.** _(MVD)_. [CVPR, 2023]. <br>
*Rui Wang, Dongdong Chen, Zuxuan Wu, Yinpeng Chen, Xiyang Dai, Mengchen Liu, Lu Yuan, Yu-Gang Jiang.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_Masked_Video_Distillation_Rethinking_Masked_Feature_Modeling_for_Self-Supervised_Video_CVPR_2023_paper.pdf)] [[Code](https://github.com/ruiwang2021/mvd)]

**MELTR: Meta Loss Transformer for Learning to Fine-tune Video Foundation Models.** _(MELTR)_. [CVPR, 2023]. <br>
*Dohwan Ko, Joonmyung Choi, Hyeong Kyu Choi, Kyoung-Woon On, Byungseok Roh, Hyunwoo J. Kim.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Ko_MELTR_Meta_Loss_Transformer_for_Learning_To_Fine-Tune_Video_Foundation_CVPR_2023_paper.pdf)] [[Code](https://github.com/mlvlab/MELTR)]

**Tell Me What Happened: Unifying Text-guided Video Completion via Multimodal Masked Video Generation.** _(MMVG)_. [CVPR, 2023]. <br>
*Linjie Li, Zhe Gan, Kevin Lin, Chung-Ching Lin, Zicheng Liu, Ce Liu, Lijuan Wang.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Fu_Tell_Me_What_Happened_Unifying_Text-Guided_Video_Completion_via_Multimodal_CVPR_2023_paper.pdf)] [[Code](https://github.com/tsujuifu/pytorch_tvc)]

**Test of Time: Instilling Video-Language Models with a Sense of Time.** _(TACT)_. [CVPR, 2023]. <br>
*Piyush Bagad, Makarand Tapaswi, Cees G. M. Snoek.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Bagad_Test_of_Time_Instilling_Video-Language_Models_With_a_Sense_of_CVPR_2023_paper.pdf)] [[Code](https://github.com/bpiyush/TestOfTime)]
 
**VideoMAE V2: Scaling Video Masked Autoencoders with Dual Masking.** _(VideoMAEv2)_. [CVPR, 2023]. <br>
*Tsu-Jui Fu, Licheng Yu, Ning Zhang, Cheng-Yang Fu, Jong-Chyi Su, William Yang Wang, Sean Bell.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_VideoMAE_V2_Scaling_Video_Masked_Autoencoders_With_Dual_Masking_CVPR_2023_paper.pdf)] [[Code](https://github.com/OpenGVLab/VideoMAEv2)]

**VindLU: A Recipe for Effective Video-and-Language Pretraining.** _(VindLU)_. [CVPR, 2023]. <br>
*Feng Cheng, Xizi Wang, Jie Lei, David Crandall, Mohit Bansal, Gedas Bertasius.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Cheng_VindLU_A_Recipe_for_Effective_Video-and-Language_Pretraining_CVPR_2023_paper.pdf)] [[Code](https://github.com/klauscc/VindLU)]

**Temporal-Oriented Recipe for Transferring Large Vision-Language Model to Video Understanding.** _(Temporal Recipe)_. [arxiv, 2025]. <br>
*Thong Nguyen, Zhiyuan Hu, Xu Lin, Cong-Duy Nguyen, See-Kiong Ng, Luu Anh Tuan.*<br>
[[Paper](https://arxiv.org/abs/2505.12605)] [[Code](https://github.com/nguyentthong/temporal_recipe)]

**An Empirical Study of End-to-End Video-Language Transformers with Masked Visual Modeling.** _(Violetv2)_. [CVPR, 2023]. <br>
*Tsu-Jui Fu, Linjie Li, Zhe Gan, Kevin Lin, William Yang Wang, Lijuan Wang, Zicheng Liu.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Fu_An_Empirical_Study_of_End-to-End_Video-Language_Transformers_With_Masked_Visual_CVPR_2023_paper.pdf)] [[Code](https://github.com/tsujuifu/pytorch_empirical-mvm)]

**Video-LLaMA: An Instruction-tuned Audio-Visual Language Model for Video Understanding.** _(Video-LLaMA)_. [EMNLP, 2023]. <br>
*Hang Zhang, Xin Li, Lidong Bing.*<br>
[[Paper](https://aclanthology.org/2023.emnlp-demo.49.pdf)] [[Code](https://github.com/DAMO-NLP-SG/Video-LLaMA)]

**Audiovisual Masked Autoencoders.** _(AudVis MAE)_. [ICCV, 2023]. <br>
*Mariana-Iuliana Georgescu, Eduardo Fonseca, Radu Tudor Ionescu, Mario Lucic, Cordelia Schmid, Anurag Arnab.*<br>
[[Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Georgescu_Audiovisual_Masked_Autoencoders_ICCV_2023_paper.pdf)]

**FateZero: Fusing Attentions for Zero-shot Text-based Video Editing.** _(FateZero)_. [ICCV, 2023]. <br>
*Chenyang Qi, Xiaodong Cun, Yong Zhang, Chenyang Lei, Xintao Wang, Ying Shan, Qifeng Chen.*<br>
[[Paper](https://arxiv.org/pdf/2303.09535)] [[Code](https://github.com/ChenyangQiQi/FateZero)]

**HiTeA: Hierarchical Temporal-Aware Video-Language Pre-training.** _(Hitea)_. [ICCV, 2023]. <br>
*Qinghao Ye, Guohai Xu, Ming Yan, Haiyang Xu, Qi Qian, Ji Zhang, Fei Huang.*<br>
[[Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Ye_HiTeA_Hierarchical_Temporal-Aware_Video-Language_Pre-training_ICCV_2023_paper.pdf)]

**MGMAE: Motion Guided Masking for Video Masked Autoencoding.** _(MGMAE)_. [ICCV, 2023]. <br>
*Bingkun Huang, Zhiyu Zhao, Guozhen Zhang, Yu Qiao, Limin Wang.*<br>
[[Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Huang_MGMAE_Motion_Guided_Masking_for_Video_Masked_Autoencoding_ICCV_2023_paper.pdf)] [[Code](https://github.com/MCG-NJU/MGMAE)]

**Progressive Spatio-Temporal Prototype Matching for Text-Video Retrieval.** _(ProST)_. [ICCV, 2023]. <br>
*Pandeng Li, Chen-Wei Xie, Liming Zhao, Hongtao Xie, Jiannan Ge, Yun Zheng, Deli Zhao, Yongdong Zhang·*<br>
[[Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_Progressive_Spatio-Temporal_Prototype_Matching_for_Text-Video_Retrieval_ICCV_2023_paper.pdf)] [[Code](https://github.com/IMCCretrieval/ProST)]

**StableVideo: Text-driven Consistency-aware Diffusion Video Editing.** _(StableVideo)_. [ICCV, 2023]. <br>
*Wenhao Chai, Xun Guo, Gaoang Wang, Yan Lu·*<br>
[[Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Chai_StableVideo_Text-driven_Consistency-aware_Diffusion_Video_Editing_ICCV_2023_paper.pdf)] [[Code](https://github.com/rese1f/StableVideo)]

**Verbs in Action: Improving verb understanding in video-language models.** _(VFC)_. [ICCV, 2023]. <br>
*Liliane Momeni, Mathilde Caron, Arsha Nagrani, Andrew Zisserman, Cordelia Schmid.*<br>
[[Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Momeni_Verbs_in_Action_Improving_Verb_Understanding_in_Video-Language_Models_ICCV_2023_paper.pdf)] [[Code](https://github.com/google-research/scenic/tree/main/scenic/projects/verbs_in_action)]

**Paxion: Patching Action Knowledge in Video-Language Foundation Models.** _(PAXION)_. [NeurIPS, 2023]. <br>
*Zhenhailong Wang, Ansel Blume, Sha Li, Genglin Liu, Jaemin Cho, Zineng Tang, Mohit Bansal, Heng Ji.*<br>
[[Paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/420492060687ca7448398c4c3fa10366-Paper-Conference.pdf)] [[Code](https://github.com/MikeWangWZHL/Paxion)]

**ChatVideo: A Tracklet-centric Multimodal and Versatile Video Understanding System.** _(ChatVideo)_. [arxiv, 2023]. <br>
*Junke Wang, Dongdong Chen, Chong Luo, Xiyang Dai, Lu Yuan, Zuxuan Wu, Yu-Gang Jiang.*<br>
[[Paper](https://arxiv.org/pdf/2304.14407)] 

**Control-A-Video: Controllable Text-to-Video Generation with Diffusion Models.** _(Control-A-Video)_. [arxiv, 2023]. <br>
*Weifeng Chen, Yatai Ji, Jie Wu, Hefeng Wu, Pan Xie, Jiashi Li, Xin Xia, Xuefeng Xiao, Liang Lin.*<br>
[[Paper](https://arxiv.org/pdf/2305.13840)] [[Code](https://github.com/Weifeng-Chen/control-a-video)]

**Dreamix: Video Diffusion Models are General Video Editors.** _(Dreammix)_. [arxiv, 2023]. <br>
*Eyal Molad, Eliahu Horwitz, Dani Valevski, Alex Rav Acha, Yossi Matias, Yael Pritch, Yaniv Leviathan, Yedid Hoshen.*<br>
[[Paper](https://arxiv.org/pdf/2302.01329)] 

**MM-VID: Advancing Video Understanding with GPT-4V(ision).** _(MM-VID)_. [arxiv, 2023]. <br>
*Kevin Lin, Faisal Ahmed, Linjie Li, Chung-Ching Lin, Ehsan Azarnasab, Zhengyuan Yang, Jianfeng Wang, Lin Liang, Zicheng Liu, Yumao Lu, Ce Liu, Lijuan Wang.*<br>
[[Paper](https://arxiv.org/pdf/2310.19773)] [[Demo](https://multimodal-vid.github.io/#video-demos)]

**MuLTI: Efficient Video-and-Language Understanding with Text-Guided MultiWay-Sampler and Multiple Choice Modeling.** _(MuLTI)_. [arxiv, 2023]. <br>
*Jiaqi Xu, Bo Liu, Yunkuo Chen, Mengli Cheng, Xing Shi.*<br>
[[Paper](https://arxiv.org/pdf/2303.05707)] 

**Stable Video Diffusion: Scaling Latent Video Diffusion Models to Large Datasets.** _(SV3D)_. [arxiv, 2023]. <br>
*Andreas Blattmann, Tim Dockhorn, Sumith Kulal, Daniel Mendelevitch, Maciej Kilian, Dominik Lorenz, Yam Levi, Zion English, Vikram Voleti, Adam Letts, Varun Jampani, Robin Rombach.*<br>
[[Paper](https://arxiv.org/pdf/2311.15127)] [[Code](https://github.com/Stability-AI/generative-models)]

**Valley: Video Assistant with Large Language model Enhanced abilitY.** _(Valley)_. [arxiv, 2023]. <br>
*Ruipu Luo, Ziwang Zhao, Min Yang, Junwei Dong, Da Li, Pengcheng Lu, Tao Wang, Linmei Hu, Minghui Qiu, Zhongyu Wei.*<br>
[[Paper](https://arxiv.org/pdf/2306.07207)] 

**Video-Bench: A Comprehensive Benchmark and Toolkit for Evaluating Video-based Large Language Models.** _(Video-Bench)_. [arxiv, 2023]. <br>
*Munan Ning, Bin Zhu, Yujia Xie, Bin Lin, Jiaxi Cui, Lu Yuan, Dongdong Chen, Li Yuan.*<br>
[[Paper](https://arxiv.org/pdf/2311.16103)] [[Code](https://github.com/PKU-YuanGroup/Video-Bench)]

**Video-ChatGPT: Towards Detailed Video Understanding via Large Vision and Language Models.** _(Video-ChatGPT)_. [arxiv, 2023]. <br>
*Muhammad Maaz, Hanoona Rasheed, Salman Khan, Fahad Shahbaz Khan.*<br>
[[Paper](https://arxiv.org/pdf/2306.05424)] [[Code](https://github.com/mbzuai-oryx/Video-ChatGPT)]

**VideoDirectorGPT: Consistent Multi-scene Video Generation via LLM-Guided Planning.** _(VALOR)_. [arxiv, 2023]. <br>
*Han Lin, Abhay Zala, Jaemin Cho, Mohit Bansal.*<br>
[[Paper](https://github.com/HL-hanlin/VideoDirectorGPT)] [[Code](https://arxiv.org/pdf/2309.15091)]

**VideoGLUE: Video General Understanding Evaluation of Foundation Models.** _(Video-GLUE)_. [arxiv, 2023]. <br>
*Liangzhe Yuan, Nitesh Bharadwaj Gundavarapu, Long Zhao, Hao Zhou, Yin Cui, Lu Jiang, Xuan Yang, Menglin Jia, Tobias Weyand, Luke Friedman, Mikhail Sirotenko, Huisheng Wang, Florian Schroff, Hartwig Adam, Ming-Hsuan Yang, Ting Liu, Boqing Gong.*<br>
[[Paper](https://arxiv.org/pdf/2307.03166)] [[Code](https://github.com/tensorflow/models/tree/master/official/projects/videoglue)]

**Video-LLaVA: Learning United Visual Representation by Alignment Before Projection.** _(Video-LLaVA)_. [arxiv, 2023]. <br>
*Bin Lin, Yang Ye, Bin Zhu, Jiaxi Cui, Munan Ning, Peng Jin, Li Yuan.*<br>
[[Paper](https://arxiv.org/pdf/2311.10122)] [[Code](https://github.com/PKU-YuanGroup/Video-LLaVA)]

**Advancing High-Resolution Video-Language Representation with Large-Scale Video Transcriptions.** _(HD-VILA)_. [CVPR, 2022]. <br>
*Hongwei Xue, Tiankai Hang, Yanhong Zeng, Yuchong Sun, Bei Liu, Huan Yang, Jianlong Fu, Baining Guo.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Xue_Advancing_High-Resolution_Video-Language_Representation_With_Large-Scale_Video_Transcriptions_CVPR_2022_paper.pdf)] [[Code](https://github.com/microsoft/XPretrain/tree/main/hd-vila)]

**Align and Prompt: Video-and-Language Pre-training with Entity Prompts.** _(MCQ)_. [CVPR, 2022]. <br>
*Dongxu Li, Junnan Li, Hongdong Li, Juan Carlos Niebles, Steven C.H. Hoi.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_Align_and_Prompt_Video-and-Language_Pre-Training_With_Entity_Prompts_CVPR_2022_paper.pdf)] [[Code](https://github.com/salesforce/ALPRO)]

**BEVT: BERT Pretraining of Video Transformers.** _(Bevt)_. [CVPR, 2022]. <br>
*Rui Wang, Dongdong Chen, Zuxuan Wu, Yinpeng Chen, Xiyang Dai, Mengchen Liu, Yu-Gang Jiang, Luowei Zhou, Lu Yuan.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_BEVT_BERT_Pretraining_of_Video_Transformers_CVPR_2022_paper.pdf)] [[Code](https://github.com/xyzforever/BEVT/tree/main)]

**Bridging Video-text Retrieval with Multiple Choice Questions.** _(ALPRO)_. [CVPR, 2022]. <br>
*Yuying Ge, Yixiao Ge, Xihui Liu, Dian Li, Ying Shan, Xiaohu Qie, Ping Luo.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Ge_Bridging_Video-Text_Retrieval_With_Multiple_Choice_Questions_CVPR_2022_paper.pdf)] [[Code](https://github.com/TencentARC/MCQ)]

**End-to-end Generative Pretraining for Multimodal Video Captioning.** _(MV-GPT)_. [CVPR, 2022]. <br>
*Paul Hongsuck Seo, Arsha Nagrani, Anurag Arnab, Cordelia Schmid.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Seo_End-to-End_Generative_Pretraining_for_Multimodal_Video_Captioning_CVPR_2022_paper.pdf)] 

**Object-aware Video-language Pre-training for Retrieval.** _(OA-Trans)_. [CVPR, 2022]. <br>
*Alex Jinpeng Wang, Yixiao Ge, Guanyu Cai, Rui Yan, Xudong Lin, Ying Shan, Xiaohu Qie, Mike Zheng Shou.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_Object-Aware_Video-Language_Pre-Training_for_Retrieval_CVPR_2022_paper.pdf)] [[Code](https://github.com/FingerRec/OA-Transformer)]

**SwinBERT: End-to-End Transformers with Sparse Attention for Video Captioning.** _(SwinBERT)_. [CVPR, 2022]. <br>
*Kevin Lin, Linjie Li, Chung-Ching Lin, Faisal Ahmed, Zhe Gan, Zicheng Liu, Yumao Lu, Lijuan Wang.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Lin_SwinBERT_End-to-End_Transformers_With_Sparse_Attention_for_Video_Captioning_CVPR_2022_paper.pdf)] [[Code](https://github.com/microsoft/SwinBERT)]

**MILES: Visual BERT Pre-training with Injected Language Semantics for Video-text Retrieval.** _(MILES)_. [ECCV, 2022]. <br>
*Yuying Ge, Yixiao Ge, Xihui Liu, Alex Jinpeng Wang, Jianping Wu, Ying Shan, Xiaohu Qie, Ping Luo.*<br>
[[Paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136950685.pdf)] [[Code](https://github.com/TencentARC/MCQ/blob/main/MILES.md)]

**Long-Form Video-Language Pre-Training with Multimodal Temporal Contrastive Learning.** _(LF-VILA)_. [NeurIPS, 2022]. <br>
*Yuchong Sun, Hongwei Xue, Ruihua Song, Bei Liu, Huan Yang, Jianlong Fu.*<br>
[[Paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/f8290ccc2905538be1a7f7914ccef629-Paper-Conference.pdf)] [[Code](https://github.com/microsoft/XPretrain/tree/main/LF-VILA)]

**Text-Adaptive Multiple Visual Prototype Matching for Video-Text Retrieval.** _(TMVM)_. [NeurIPS, 2022]. <br>
*Chengzhi Lin, Ancong Wu, Junwei Liang, Jun Zhang, Wenhang Ge, Wei-Shi Zheng, Chunhua Shen.*<br>
[[Paper](https://openreview.net/pdf?id=XevwsaZ-4z)] 

**Masked Autoencoders As Spatiotemporal Learners.** _(ST-MAE)_. [NeurIPS, 2022]. <br>
*Christoph Feichtenhofer, Haoqi Fan, Yanghao Li, Kaiming He.*<br>
[[Paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/e97d1081481a4017df96b51be31001d3-Paper-Conference.pdf)] [[Code](https://github.com/facebookresearch/mae_st)]

**VideoMAE: Masked Autoencoders are Data-Efficient Learners for Self-Supervised Video Pre-Training.** _(VideoMAE)_. [NeurIPS, 2022]. <br>
*Zhan Tong, Yibing Song, Jue Wang, Limin Wang.*<br>
[[Paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/416f9cb3276121c42eebb86352a4354a-Paper-Conference.pdf)] [[Code](https://github.com/MCG-NJU/VideoMAE)]

**TVLT: Textless Vision-Language Transformer.** _(TVLT)_. [NeurIPS, 2022]. <br>
*Zineng Tang, Jaemin Cho, Yixin Nie, Mohit Bansal.*<br>
[[Paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/3ea3134345f2e6228a29f35b86bce24d-Paper-Conference.pdf)] [[Code](https://github.com/zinengtang/TVLT)]

**It Takes Two: Masked Appearance-Motion Modeling for Self-supervised Video Transformer Pre-training.** _(MAM<sup>2</sup>)_. [arxiv, 2022]. <br>
*Yuxin Song, Min Yang, Wenhao Wu, Dongliang He, Fu Li, Jingdong Wang.*<br>
[[Paper](https://arxiv.org/pdf/2210.05234)] 

**Make-A-Video: Text-to-Video Generation without Text-Video Data.** _(Make-A-Video)_. [arxiv, 2022]. <br>
*Uriel Singer, Adam Polyak, Thomas Hayes, Xi Yin, Jie An, Songyang Zhang, Qiyuan Hu, Harry Yang, Oron Ashual, Oran Gafni, Devi Parikh, Sonal Gupta, Yaniv Taigman.*<br>
[[Paper](https://arxiv.org/pdf/2209.14792)] 

**SimVTP: Simple Video Text Pre-training with Masked Autoencoders.** _(SimVTP)_. [arxiv, 2022]. <br>
*Yue Ma, Tianyu Yang, Yin Shan, Xiu Li.*<br>
[[Paper](https://arxiv.org/pdf/2212.03490)] [[Code](https://github.com/Simoyuan/SimVTP)]

**VIOLET : End-to-End Video-Language Transformers with Masked Visual-token Modeling.** _(Violet)_. [arxiv, 2022]. <br>
*Tsu-Jui Fu, Linjie Li, Zhe Gan, Kevin Lin, William Yang Wang, Lijuan Wang, Zicheng Liu.*<br>
[[Paper](https://arxiv.org/pdf/2111.12681)] [[Code](https://github.com/tsujuifu/pytorch_violet)]

**VideoCLIP: Contrastive Pre-training for Zero-shot Video-Text Understanding.** _(VideoCLIP)_. [EMNLP, 2021]. <br>
*Hu Xu, Gargi Ghosh, Po-Yao Huang, Dmytro Okhonko, Armen Aghajanyan, Florian Metze, Luke Zettlemoyer, Christoph Feichtenhofer.*<br>
[[Paper](https://aclanthology.org/2021.emnlp-main.544.pdf)] [[Code](https://github.com/facebookresearch/fairseq/tree/main/examples/MMPT)]

**Just Ask: Learning to Answer Questions from Millions of Narrated Videos.** _(Just-Ask)_. [ICCV, 2021]. <br>
*Antoine Yang, Antoine Miech, Josef Sivic, Ivan Laptev, Cordelia Schmid.*<br>
[[Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Yang_Just_Ask_Learning_To_Answer_Questions_From_Millions_of_Narrated_ICCV_2021_paper.pdf)] [[Code](https://github.com/antoyang/just-ask)]

**VIMPAC: Video Pre-Training via Masked Token Prediction and Contrastive Learning.** _(Vimpac)_. [arxiv, 2021]. <br>
*Hao Tan, Jie Lei, Thomas Wolf, Mohit Bansal.*<br>
[[Paper](https://arxiv.org/pdf/2106.11250)] [[Code](https://github.com/airsplay/vimpac)]

**UniVL: A Unified Video and Language Pre-Training Model for Multimodal Understanding and Generation.** _(UniVL)_. [arxiv, 2020]. <br>
*Huaishao Luo, Lei Ji, Botian Shi, Haoyang Huang, Nan Duan, Tianrui Li, Jason Li, Taroon Bharti, Ming Zhou.*<br>
[[Paper](https://arxiv.org/pdf/2002.06353)] [[Code](https://github.com/microsoft/UniVL)]


# Universal
**Chat-UniVi: Unified Visual Representation Empowers Large Language Models with Image and Video Understanding.** _(Chat-UniVi)_. [CVPR, 2024]. <br>
*Peng Jin, Ryuichi Takanobu, Wancai Zhang, Xiaochun Cao, Li Yuan.*<br>
[[Paper](https://arxiv.org/pdf/2311.08046)] [[Code](https://github.com/PKU-YuanGroup/Chat-UniVi)]

**Dysen-VDM: Empowering Dynamics-aware Text-to-Video Diffusion with LLMs.** _(Dysen-VDM)_. [CVPR, 2024]. <br>
*Hao Fei, Shengqiong Wu, Wei Ji, Hanwang Zhang, Tat-Seng Chua.*<br>
[[Paper](https://arxiv.org/pdf/2308.13812)] [[Code](https://github.com/scofield7419/Dysen)]

**General Object Foundation Model for Images and Videos at Scale.** _(GLEE)_. [CVPR, 2024]. <br>
*Junfeng Wu, Yi Jiang, Qihao Liu, Zehuan Yuan, Xiang Bai, Song Bai.*<br>
[[Paper](https://arxiv.org/pdf/2312.09158)] [[Code](https://github.com/FoundationVision/GLEE)]

**MA-LMM: Memory-Augmented Large Multimodal Model for Long-Term Video Understanding.** _(MA-LMM)_. [CVPR, 2024]. <br>
*Bo He, Hengduo Li, Young Kyun Jang, Menglin Jia, Xuefei Cao, Ashish Shah, Abhinav Shrivastava, Ser-Nam Lim.*<br>
[[Paper](https://arxiv.org/pdf/2404.05726)] [[Code](https://github.com/boheumd/MA-LMM)]

**Timechat: A time-sensitive multimodal large language model for long video understanding.** _(TimeChat)_. [CVPR, 2024]. <br>
*Shuhuai Ren, Linli Yao, Shicheng Li, Xu Sun, Lu Hou.*<br>
[[Paper](https://arxiv.org/pdf/2312.02051)] [[Code](https://github.com/RenShuhuai-Andy/TimeChat)]

**VideoLLM-online: Online Video Large Language Model for Streaming Video.** _(VideoLLM-online)_. [CVPR, 2024]. <br>
*Joya Chen, Zhaoyang Lv, Shiwei Wu, Kevin Qinghong Lin, Chenan Song, Difei Gao, Jia-Wei Liu, Ziteng Gao, Dongxing Mao, Mike Zheng Shou.*<br>
[[Paper](https://arxiv.org/pdf/2406.11816)] [[Code](https://github.com/showlab/VideoLLM-online)]

**LongVLM: Efficient Long Video Understanding via Large Language Models** _(LongVLM)_. [ECCV, 2024]. <br>
*Yuetian Weng, Mingfei Han, Haoyu He, Xiaojun Chang, Bohan Zhuang.*<br>
[[Paper](https://arxiv.org/pdf/2404.03384)] [[Code](https://github.com/ziplab/LongVLM)]

**LanguageBind: Extending Video-Language Pretraining to N-modality by Language-based Semantic Alignment.** _(LanguageBind)_. [ICLR, 2024]. <br>
*Bin Zhu, Bin Lin, Munan Ning, Yang Yan, Jiaxi Cui, HongFa Wang, Yatian Pang, Wenhao Jiang, Junwu Zhang, Zongwei Li, Wancai Zhang, Zhifeng Li, Wei Liu, Li Yuan.*<br>
[[Paper](https://arxiv.org/pdf/2310.01852)] [[Code](https://github.com/PKU-YuanGroup/LanguageBind)]

**X<sup>2</sup>-VLM: All-In-One Pre-trained Model For Vision-Language Tasks.** _(X<sup>2</sup>-VLM)_. [TPAMI, 2024]. <br>
*Yan Zeng, Xinsong Zhang, Hang Li, Jiawei Wang, Jipeng Zhang, Wangchunshu Zhou.*<br>
[[Paper](https://arxiv.org/pdf/2211.12402)] [[Code](https://github.com/PKU-YuanGroup/LanguageBind)]

**InternVideo2: Scaling Video Foundation Models for Multimodal Video Understanding.** _(InternVideo2)_. [arxiv, 2024]. <br>
*Yi Wang, Kunchang Li, Xinhao Li, Jiashuo Yu, Yinan He, Guo Chen, Baoqi Pei, Rongkun Zheng, Jilan Xu, Zun Wang, Yansong Shi, Tianxiang Jiang, Songze Li, Hongjie Zhang, Yifei Huang, Yu Qiao, Yali Wang, Limin Wang.*<br>
[[Paper](https://arxiv.org/pdf/2403.15377)] [[Code](https://github.com/OpenGVLab/InternVideo2)]

**Video-LaVIT: Unified Video-Language Pre-training with Decoupled Visual-Motional Tokenization.** _(Video-LaVIT)_. [arxiv, 2024]. <br>
*Yang Jin, Zhicheng Sun, Kun Xu, Kun Xu, Liwei Chen, Hao Jiang, Quzhe Huang, Chengru Song, Yuliang Liu, Di Zhang, Yang Song, Kun Gai, Yadong Mu.*<br>
[[Paper](https://arxiv.org/pdf/2402.03161)] [[Code](https://github.com/jy0205/LaVIT/tree/main/VideoLaVIT)]

**VideoPoet: A Large Language Model for Zero-Shot Video Generation.** _(VideoPoet)_. [arxiv, 2024]. <br>
*Dan Kondratyuk, Lijun Yu, Xiuye Gu, José Lezama, Jonathan Huang, Grant Schindler, Rachel Hornung, Vighnesh Birodkar, Jimmy Yan, Ming-Chang Chiu, Krishna Somandepalli, Hassan Akbari, Yair Alon, Yong Cheng, Josh Dillon, Agrim Gupta, Meera Hahn, Anja Hauth, David Hendon, Alonso Martinez, David Minnen, Mikhail Sirotenko, Kihyuk Sohn, Xuan Yang, Hartwig Adam, Ming-Hsuan Yang, Irfan Essa, Huisheng Wang, David A. Ross, Bryan Seybold, Lu Jiang.*<br>
[[Paper](https://arxiv.org/pdf/2312.14125)] 

**VideoPrism: A Foundational Visual Encoder for Video Understanding.** _(VideoPrism)_. [arxiv, 2024]. <br>
*Long Zhao, Nitesh B. Gundavarapu, Liangzhe Yuan, Hao Zhou, Shen Yan, Jennifer J. Sun, Luke Friedman, Rui Qian, Tobias Weyand, Yue Zhao, Rachel Hornung, Florian Schroff, Ming-Hsuan Yang, David A. Ross, Huisheng Wang, Hartwig Adam, Mikhail Sirotenko, Ting Liu, Boqing Gong.*<br>
[[Paper](https://arxiv.org/pdf/2402.13217)] 

**OmniMAE: Single Model Masked Pretraining on Images and Videos.** _(OmniMAE)_. [CVPR, 2023]. <br>
*Rohit Girdhar, Alaaeldin El-Nouby, Mannat Singh, Kalyan Vasudev Alwala, Armand Joulin, Ishan Misra.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Girdhar_OmniMAE_Single_Model_Masked_Pretraining_on_Images_and_Videos_CVPR_2023_paper.pdf)] [[Code](https://github.com/facebookresearch/omnivore/tree/main/omnimae)]

**TESTA: Temporal-Spatial Token Aggregation for Long-form Video-Language Understanding.** _(TESTA)_. [EMNLP, 2023]. <br>
*Shuhuai Ren, Sishuo Chen, Shicheng Li, Xu Sun, Lu Hou.*<br>
[[Paper](https://arxiv.org/pdf/2310.19060)] [[Code](https://github.com/RenShuhuai-Andy/TESTA)]

**SMAUG: Sparse Masked Autoencoder for Efficient Video-Language Pre-training.** _(Smaug)_. [ICCV, 2023]. <br>
*Yuanze Lin, Chen Wei, Huiyu Wang, Alan Yuille, Cihang Xie.*<br>
[[Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Lin_SMAUG_Sparse_Masked_Autoencoder_for_Efficient_Video-Language_Pre-Training_ICCV_2023_paper.pdf)] 

**mPLUG-2: A Modularized Multi-modal Foundation Model Across Text, Image and Video.** _(mPLUG-2)_. [ICML, 2023]. <br>
*Haiyang Xu, Qinghao Ye, Ming Yan, Yaya Shi, Jiabo Ye, Yuanhong Xu, Chenliang Li, Bin Bi, Qi Qian, Wei Wang, Guohai Xu, Ji Zhang, Songfang Huang, Fei Huang, Jingren Zhou.*<br>
[[Paper](https://proceedings.mlr.press/v202/xu23s/xu23s.pdf)] [[Code](https://github.com/X-PLUG/mPLUG-2)]

**Contrastive Audio-Visual Masked Autoencoder.** _(CAV-MAE)_. [ICLR, 2023]. <br>
*Yuan Gong, Andrew Rouditchenko, Alexander H. Liu, David Harwath, Leonid Karlinsky, Hilde Kuehne, James Glass.*<br>
[[Paper](https://openreview.net/pdf?id=QPtMRyk5rb)] [[Code](https://github.com/YuanGongND/cav-mae)]

**VAST: A Vision-Audio-Subtitle-Text Omni-Modality Foundation Model and Dataset.** _(VAST)_. [NeurIPS, 2023]. <br>
*Sihan Chen, Handong Li, Qunbo Wang, Zijia Zhao, Mingzhen Sun, Xinxin Zhu, Jing Liu.*<br>
[[Paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/e6b2b48b5ed90d07c305932729927781-Paper-Conference.pdf)] [[Code](https://github.com/TXH-mercury/VAST)]

**Perceiver-VL: Efficient Vision-and-Language Modeling with Iterative Latent Attention.** _(Perceiver-VL)_. [WACV, 2023]. <br>
*Zineng Tang, Jaemin Cho, Jie Lei, Mohit Bansal.*<br>
[[Paper](https://openaccess.thecvf.com/content/WACV2023/papers/Tang_Perceiver-VL_Efficient_Vision-and-Language_Modeling_With_Iterative_Latent_Attention_WACV_2023_paper.pdf)] [[Code](https://github.com/zinengtang/Perceiver_VL)]

**Fine-grained Audio-Visual Joint Representations for Multimodal Large Language Models.** _(FAVOR)_. [arxiv, 2023]. <br>
*Guangzhi Sun, Wenyi Yu, Changli Tang, Xianzhao Chen, Tian Tan, Wei Li, Lu Lu, Zejun Ma, Chao Zhang.*<br>
[[Paper](https://arxiv.org/pdf/2310.05863)] [[Code](https://github.com/BriansIDP/AudioVisualLLM)]

**Macaw-LLM: Multi-Modal Language Modeling with Image, Audio, Video, and Text Integration.** _(Macaw-LLM)_. [arxiv, 2023]. <br>
*Chenyang Lyu, Minghao Wu, Longyue Wang, Xinting Huang, Bingshuai Liu, Zefeng Du, Shuming Shi, Zhaopeng Tu.*<br>
[[Paper](https://arxiv.org/pdf/2306.09093)] [[Code](https://github.com/lyuchenyang/Macaw-LLM)]

**PG-Video-LLaVA: Pixel Grounding Large Video-Language Models.** _(PG-Video-LLaVA)_. [arxiv, 2023]. <br>
*Shehan Munasinghe, Rusiru Thushara, Muhammad Maaz, Hanoona Abdul Rasheed, Salman Khan, Mubarak Shah, Fahad Khan.*<br>
[[Paper](https://arxiv.org/pdf/2311.13435)] [[Code](https://github.com/mbzuai-oryx/Video-LLaVA)]

**TVTSv2: Learning Out-of-the-box Spatiotemporal Visual Representations at Scale.** _(TVTSv2)_. [arxiv, 2023]. <br>
*Ziyun Zeng, Yixiao Ge, Zhan Tong, Xihui Liu, Shu-Tao Xia, Ying Shan.*<br>
[[Paper](https://arxiv.org/pdf/2305.14173)] [[Code](https://github.com/TencentARC/TVTS)]

**ViC-MAE: Self-Supervised Representation Learning from Images and Video with Contrastive Masked Autoencoders.** _(Vic-MAE)_. [arxiv, 2023]. <br>
*Jefferson Hernandez, Ruben Villegas, Vicente Ordonez.*<br>
[[Paper](https://arxiv.org/pdf/2303.12001)]

**VALOR: Vision-Audio-Language Omni-Perception Pretraining Model and Dataset.** _(VALOR)_. [arxiv, 2023]. <br>
*Jefferson Hernandez, Ruben Villegas, Vicente Ordonez.*<br>
[[Paper](https://arxiv.org/pdf/2304.08345)] [[Code](https://github.com/TXH-mercury/VALOR)]

**Masked Feature Prediction for Self-Supervised Visual Pre-Training.** _(MaskFeat)_. [CVPR, 2022]. <br>
*Chen Wei, Haoqi Fan, Saining Xie, Chao-Yuan Wu, Alan Yuille, Christoph Feichtenhofer.*<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Wei_Masked_Feature_Prediction_for_Self-Supervised_Visual_Pre-Training_CVPR_2022_paper.pdf)] [[Code](https://github.com/facebookresearch/SlowFast/tree/main/projects/maskfeat)]

**OmniVL:One Foundation Model for Image-Language and Video-Language Tasks.** _(OmniVL)_. [NeurIPS, 2022]. <br>
*Junke Wang, Dongdong Chen, Zuxuan Wu, Chong Luo, Luowei Zhou, Yucheng Zhao, Yujia Xie, Ce Liu, Yu-Gang Jiang, Lu Yuan.*<br>
[[Paper](https://openreview.net/pdf?id=u4ihlSG240n)] 

**InternVideo: General Video Foundation Models via Generative and Discriminative Learning.** _(InternVideo)_. [arxiv, 2022]. <br>
*Yi Wang, Kunchang Li, Yizhuo Li, Yinan He, Bingkun Huang, Zhiyu Zhao, Hongjie Zhang, Jilan Xu, Yi Liu, Zun Wang, Sen Xing, Guo Chen, Junting Pan, Jiashuo Yu, Yali Wang, Limin Wang, Yu Qiao.*<br>
[[Paper](https://arxiv.org/pdf/2212.03191)] [[Code](https://github.com/OpenGVLab/InternVideo/tree/main/InternVideo1)]

**Self-supervised video pretraining yields human-aligned visual representations.** _(VITO)_. [arxiv, 2022]. <br>
*Nikhil Parthasarathy, S. M. Ali Eslami, João Carreira, Olivier J. Hénaff.*<br>
[[Paper](https://arxiv.org/pdf/2210.06433)] 

**VLM: Task-agnostic Video-Language Model Pre-training for Video Understanding.** _(VLM)_. [ACL, 2021]. <br>
*Hu Xu, Gargi Ghosh, Po-Yao Huang, Prahal Arora, Masoumeh Aminzadeh, Christoph Feichtenhofer, Florian Metze, Luke Zettlemoyer.*<br>
[[Paper](https://aclanthology.org/2021.findings-acl.370.pdf)] [[Code](https://github.com/facebookresearch/fairseq/tree/main/examples/MMPT)]

**MERLOT: Multimodal Neural Script Knowledge Models.** _(MERLOT)_. [NeurIPS, 2021]. <br>
*Rowan Zellers, Ximing Lu, Jack Hessel, Youngjae Yu, Jae Sung Park, Jize Cao, Ali Farhadi, Yejin Choi.*<br>
[[Paper](https://proceedings.neurips.cc/paper_files/paper/2021/file/c6d4eb15f1e84a36eff58eca3627c82e-Paper.pdf)] [[Code](https://github.com/rowanz/merlot)]

**VATT: Transformers for Multimodal Self-Supervised Learning from Raw Video, Audio and Text.** _(VATT)_. [NeurIPS, 2021]. <br>
*Hassan Akbari, Liangzhe Yuan, Rui Qian, Wei-Hong Chuang, Shih-Fu Chang, Yin Cui, Boqing Gong.*<br>
[[Paper](https://proceedings.neurips.cc/paper_files/paper/2021/file/cb3213ada48302953cb0f166464ab356-Paper.pdf)] [[Code](https://github.com/google-research/google-research/tree/master/vatt)]


