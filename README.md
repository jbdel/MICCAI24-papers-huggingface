# MICCAI 2024 Papers

Welcome to the MICCAI 2024 Papers repository! Below is a list of all accepted papers with their details.



Use it via API! [Documentation here](https://huggingface.co/spaces/MICCAI/MICCAI2024-papers?view=api).
```python
from gradio_client import Client
import json

client = Client("MICCAI/MICCAI2024-papers")
result = client.predict(
    title_search_query="LLM",
    filter_names=["Model"],
    presentation_type="(ALL)",
    book_type="(ALL)",
    column_names=["Title", "Type", "Book", "Paper page", "Authors claimed", "👍", "💬", "Proceedings", "GitHub", "Spaces",
                  "Models"],
    api_name="/filter"
)
print(json.dumps(result, indent=4))
```


## Disease Progression Prediction Incorporating Genotype-Environment Interactions: A Longitudinal Neurodegenerative Disorder Study<br/>
**Authors:** Zhang, Jin, Shang, Muheng, Yang, Yan, Guo, Lei, Han, Junwei, Du, Lei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2009_paper.pdf)<br/>

---

## BrainWaveNet: Wavelet-based Transformer for Autism Spectrum Disorder Diagnosis<br/>
**Authors:** Jeong, Ah-Yeong, Heo, Da-Woon, Kang, Eunsong, Suk, Heung-Il<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1241_paper.pdf)<br/>

---

## Unified Prompt-Visual Interactive Segmentation of Clinical Target Volume in CT for Nasopharyngeal Carcinoma with Prior Anatomical Information<br/>
**Authors:** Khor, Hee Guan, Yang, Xin, Sun, Yihua, Wang, Jie, Huang, Sijuan, Wang, Shaobin, Lu, Bai, Ma, Longfei, Liao, Hongen<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2115_paper.pdf)<br/>

---

## [Medical Image Synthesis via Fine-Grained Image-Text Alignment and Anatomy-Pathology Prompting](https://arxiv.org/abs/2403.06835)<br/>
**Authors:** Chen, Wenting, Wang, Pengyu, Ren, Hui, Sun, Lichao, Li, Quanzheng, Yuan, Yixuan, Li, Xiang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3619_paper.pdf)<br/>
**arXiv:** [2403.06835](https://arxiv.org/abs/2403.06835)<br/>

---

## Biophysics-based data assimilation of longitudinal tau and amyloid-β PET scans<br/>
**Authors:** Wen, Zheyu, Ghafouri, Ali, Biros, George<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0453_paper.pdf)<br/>

---

## WSSADN: A Weakly Supervised Spherical Age-Disentanglement Network for Detecting Developmental Disorders with Structural MRI<br/>
**Authors:** Xue, Pengcheng, Nie, Dong, Zhu, Meijiao, Yang, Ming, Zhang, Han, Zhang, Daoqiang, Wen, Xuyun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0336_paper.pdf)<br/>

---

## Med-Former: A Transformer based Architecture for Medical Image Classification<br/>
**Authors:** Chowdary, G. Jignesh, Yin, Zhaozheng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0867_paper.pdf)<br/>

---

## Enabling Text-free Inference in Language-guided Segmentation of Chest X-rays via Self-guidance<br/>
**Authors:** Ye, Shuchang, Meng, Mingyuan, Li, Mingjian, Feng, Dagan, Kim, Jinman<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0556_paper.pdf)<br/>

---

## [Slice-Consistent 3D Volumetric Brain CT-to-MRI Translation with 2D Brownian Bridge Diffusion Model](https://arxiv.org/abs/2407.05059)<br/>
**Authors:** Choo, Kyobin, Jun, Youngjun, Yun, Mijin, Hwang, Seong Jae<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0531_paper.pdf)<br/>
**arXiv:** [2407.05059](https://arxiv.org/abs/2407.05059)<br/>

---

## [DSCENet: Dynamic Screening and Clinical-Enhanced Multimodal Fusion for MPNs Subtype Classification](https://arxiv.org/abs/2407.08167)<br/>
**Authors:** Zhang, Yuan, Qi, Yaolei, Qi, Xiaoming, Wei, Yongyue, Yang, Guanyu<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1741_paper.pdf)<br/>
**arXiv:** [2407.08167](https://arxiv.org/abs/2407.08167)<br/>

---

## LaTiM: Longitudinal representation learning in continuous-time models to predict disease progression<br/>
**Authors:** Zeghlache, Rachid, Conze, Pierre-Henri, El Habib Daho, Mostafa, Li, Yihao, Le Boité, Hugo, Tadayoni, Ramin, Massin, Pascale, Cochener, Béatrice, Rezaei, Alireza, Brahim, Ikram, Quellec, Gwenolé, Lamard, Mathieu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0263_paper.pdf)<br/>

---

## A Bayesian Approach to Weakly-supervised Laparoscopic Image Segmentation<br/>
**Authors:** Zheng, Zhou, Hayashi, Yuichiro, Oda, Masahiro, Kitasaka, Takayuki, Mori, Kensaku<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0219_paper.pdf)<br/>

---

## Endora: Video Generation Models as Endoscopy Simulators<br/>
**Authors:** Li, Chenxin, Liu, Hengyu, Liu, Yifan, Feng, Brandon Y., Li, Wuyang, Liu, Xinyu, Chen, Zhen, Shao, Jing, Yuan, Yixuan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0470_paper.pdf)<br/>

---

## [Towards Integrating Epistemic Uncertainty Estimation into the Radiotherapy Workflow](https://arxiv.org/abs/2409.18628)<br/>
**Authors:** Teichmann, Marvin Tom, Datar, Manasi, Kratzke, Lisa, Vega, Fernando, Ghesu, Florin C.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2441_paper.pdf)<br/>
**arXiv:** [2409.18628](https://arxiv.org/abs/2409.18628)<br/>

---

## [CoReEcho: Continuous Representation Learning for 2D+time Echocardiography Analysis](https://arxiv.org/abs/2403.10164)<br/>
**Authors:** Maani, Fadillah Adamsyah, Saeed, Numan, Matsun, Aleksandr, Yaqub, Mohammad<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2916_paper.pdf)<br/>
**arXiv:** [2403.10164](https://arxiv.org/abs/2403.10164)<br/>

---

## [Few-Shot Domain Adaptive Object Detection for Microscopic Images](https://arxiv.org/abs/2407.07633)<br/>
**Authors:** Inayat, Sumayya, Dilawar, Nimra, Sultani, Waqas, Ali, Mohsen<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/4161_paper.pdf)<br/>
**arXiv:** [2407.07633](https://arxiv.org/abs/2407.07633)<br/>

---

## A New Dataset and Baseline Model for Rectal Cancer Risk Assessment in Endoscopic Ultrasound Videos<br/>
**Authors:** Zhang, Jiansong, Wu, Shengnan, Liu, Peizhong, Shen, Linlin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/4098_paper.pdf)<br/>

---

## Deform-Mamba Network for MRI Super-Resolution<br/>
**Authors:** Ji, Zexin, Zou, Beiji, Kui, Xiaoyan, Vera, Pierre, Ruan, Su<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3762_paper.pdf)<br/>

---

## [Dynamic Pseudo Label Optimization in Point-Supervised Nuclei Segmentation](https://arxiv.org/abs/2406.16427)<br/>
**Authors:** Wang, Ziyue, Zhang, Ye, Wang, Yifeng, Cai, Linghan, Zhang, Yongbing<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0814_paper.pdf)<br/>
**arXiv:** [2406.16427](https://arxiv.org/abs/2406.16427)<br/>

---

## Multilevel Causality Learning for Multi-label Gastric Atrophy Diagnosis<br/>
**Authors:** Cui, Xiaoxiao, Jiang, Shanzhi, Sun, Baolin, Li, Yiran, Cao, Yankun, Li, Zhen, Lv, Chaoyang, Liu, Zhi, Cui, Lizhen, Li, Shuo<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3296_paper.pdf)<br/>

---

## Low-Shot Prompt Tuning for Multiple Instance Learning based Histology Classification<br/>
**Authors:** Chikontwe, Philip, Kang, Myeongkyun, Luna, Miguel, Nam, Siwoo, Park, Sang Hyun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2700_paper.pdf)<br/>

---

## Eddeep: Fast eddy-current distortion correction for diffusion MRI with deep learning<br/>
**Authors:** Legouhy, Antoine, Callaghan, Ross, Stee, Whitney, Peigneux, Philippe, Azadbakht, Hojjat, Zhang, Hui<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3783_paper.pdf)<br/>

---

## [XCoOp: Explainable Prompt Learning for Computer-Aided Diagnosis via Concept-guided Context Optimization](https://arxiv.org/abs/2403.09410)<br/>
**Authors:** Bie, Yequan, Luo, Luyang, Chen, Zhixuan, Chen, Hao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0077_paper.pdf)<br/>
**arXiv:** [2403.09410](https://arxiv.org/abs/2403.09410)<br/>

---

## [Clinical-grade Multi-Organ Pathology Report Generation for Multi-scale Whole Slide Images via a Semantically Guided Medical Text Foundation Model](https://arxiv.org/abs/2409.15574)<br/>
**Authors:** Tan, Jing Wei, Kim, SeungKyu, Kim, Eunsu, Lee, Sung Hak, Ahn, Sangjeong, Jeong, Won-Ki<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1738_paper.pdf)<br/>
**arXiv:** [2409.15574](https://arxiv.org/abs/2409.15574)<br/>

---

## [Semantics-Aware Attention Guidance for Diagnosing Whole Slide Images](https://arxiv.org/abs/2404.10894)<br/>
**Authors:** Liu, Kechun, Wu, Wenjun, Elmore, Joann G., Shapiro, Linda G.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1524_paper.pdf)<br/>
**arXiv:** [2404.10894](https://arxiv.org/abs/2404.10894)<br/>

---

## [Interpretable Representation Learning of Cardiac MRI via Attribute Regularization](https://arxiv.org/abs/2406.08282)<br/>
**Authors:** Di Folco, Maxime, Bercea, Cosmin I., Chan, Emily, Schnabel, Julia A.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1877_paper.pdf)<br/>
**arXiv:** [2406.08282](https://arxiv.org/abs/2406.08282)<br/>

---

## Cross-conditioned Diffusion Model for Medical Image to Image Translation<br/>
**Authors:** Xing, Zhaohu, Yang, Sicheng, Chen, Sixiang, Ye, Tian, Yang, Yijun, Qin, Jing, Zhu, Lei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0714_paper.pdf)<br/>

---

## Exploiting Supervision Information in Weakly Paired Images for IHC Virtual Staining<br/>
**Authors:** Li, Yueheng, Guan, Xianchao, Wang, Yifeng, Zhang, Yongbing<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3332_paper.pdf)<br/>

---

## [Tri-modal Confluence with Temporal Dynamics for Scene Graph Generation in Operating Rooms](https://arxiv.org/abs/2404.09231)<br/>
**Authors:** Guo, Diandian, Lin, Manxi, Pei, Jialun, Tang, He, Jin, Yueming, Heng, Pheng-Ann<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0281_paper.pdf)<br/>
**arXiv:** [2404.09231](https://arxiv.org/abs/2404.09231)<br/>

---

## Black-Box Adaptation for Medical Image Segmentation<br/>
**Authors:** Paranjape, Jay N., Sikder, Shameema, Vedula, S. Swaroop, Patel, Vishal M.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0668_paper.pdf)<br/>

---

## Efficient and Gender-adaptive Graph Vision Mamba for Pediatric Bone Age Assessment<br/>
**Authors:** Zhou, Lingyu, Yi, Zhang, Zhou, Kai, Xu, Xiuyuan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2831_paper.pdf)<br/>

---

## [CAVM: Conditional Autoregressive Vision Model for Contrast-Enhanced Brain Tumor MRI Synthesis](https://arxiv.org/abs/2406.16074)<br/>
**Authors:** Gui, Lujun, Ye, Chuyang, Yan, Tianyi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1909_paper.pdf)<br/>
**arXiv:** [2406.16074](https://arxiv.org/abs/2406.16074)<br/>

---

## [Forecasting Disease Progression with Parallel Hyperplanes in Longitudinal Retinal OCT](https://arxiv.org/abs/2409.20195)<br/>
**Authors:** Chakravarty, Arunava, Emre, Taha, Lachinov, Dmitrii, Rivail, Antoine, Scholl, Hendrik P. N., Fritsche, Lars, Sivaprasad, Sobha, Rueckert, Daniel, Lotery, Andrew, Schmidt-Erfurth, Ursula, Bogunović, Hrvoje<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3334_paper.pdf)<br/>
**arXiv:** [2409.20195](https://arxiv.org/abs/2409.20195)<br/>

---

## Trexplorer: Recurrent DETR for Topologically Correct Tree Centerline Tracking<br/>
**Authors:** Naeem, Roman, Hagerman, David, Svensson, Lennart, Kahl, Fredrik<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2112_paper.pdf)<br/>

---

## FedEvi: Improving Federated Medical Image Segmentation via Evidential Weight Aggregation<br/>
**Authors:** Chen, Jiayi, Ma, Benteng, Cui, Hengfei, Xia, Yong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2717_paper.pdf)<br/>

---

## CT-based brain ventricle segmentation via diffusion Schrödinger Bridge without target domain ground truths<br/>
**Authors:** Teimouri, Reihaneh, Kersten-Oertel, Marta, Xiao, Yiming<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1439_paper.pdf)<br/>

---

## Is this hard for you? Personalized human difficulty estimation for skin lesion diagnosis<br/>
**Authors:** Kampen, Peter Johannes Tejlgaard, Christensen, Anders Nymark, Hannemose, Morten Rieger<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3180_paper.pdf)<br/>

---

## Cross-Modality Cardiac Insight Transfer: A Contrastive Learning Approach to Enrich ECG with CMR Features<br/>
**Authors:** Ding, Zhengyao, Hu, Yujian, Li, Ziyu, Zhang, Hongkun, Wu, Fei, Xiang, Yilang, Li, Tian, Liu, Ziyi, Chu, Xuesen, Huang, Zhengxing<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1010_paper.pdf)<br/>

---

## Representation Learning with a Transformer-Based Detection Model for Localized Chest X-Ray Disease and Progression Detection<br/>
**Authors:** Eshraghi Dehaghani, Mehrdad, Sabour, Amirhossein, Madu, Amarachi B., Lourentzou, Ismini, Moradi, Mehdi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3269_paper.pdf)<br/>

---

## [BIMCV-R: A Landmark Dataset for 3D CT Text-Image Retrieval](https://huggingface.co/papers/2403.15992)<br/>
**Authors:** Chen, Yinda, Liu, Che, Liu, Xiaoyu, Arcucci, Rossella, Xiong, Zhiwei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1194_paper.pdf)<br/>
**arXiv:** [2403.15992](https://arxiv.org/abs/2403.15992)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2403.15992](https://huggingface.co/papers/2403.15992)<br/>
**🤗 Datasets:** [cyd0806/BIMCV-R](https://huggingface.co/datasets/cyd0806/BIMCV-R)<br/>

---

## MRScore: Evaluating Medical Report with LLM-based Reward System<br/>
**Authors:** Liu, Yunyi, Wang, Zhanyu, Li, Yingshu, Liang, Xinyu, Liu, Lingqiao, Wang, Lei, Zhou, Luping<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1151_paper.pdf)<br/>

---

## CausalCLIPSeg: Unlocking CLIP’s Potential in Referring Medical Image Segmentation with Causal Intervention<br/>
**Authors:** Chen, Yaxiong, Wei, Minghong, Zheng, Zixuan, Hu, Jingliang, Shi, Yilei, Xiong, Shengwu, Zhu, Xiao Xiang, Mou, Lichao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3127_paper.pdf)<br/>

---

## [Online 3D reconstruction and dense tracking in endoscopic videos](https://arxiv.org/abs/2409.06037)<br/>
**Authors:** Hayoz, Michel, Hahne, Christopher, Kurmann, Thomas, Allan, Max, Beldi, Guido, Candinas, Daniel, Márquez-Neila, Pablo, Sznitman, Raphael<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0373_paper.pdf)<br/>
**arXiv:** [2409.06037](https://arxiv.org/abs/2409.06037)<br/>

---

## [Accelerated Multi-Contrast MRI Reconstruction via Frequency and Spatial Mutual Learning](https://arxiv.org/abs/2409.14113)<br/>
**Authors:** Chen, Qi, Xing, Xiaohan, Chen, Zhen, Xiong, Zhiwei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2570_paper.pdf)<br/>
**arXiv:** [2409.14113](https://arxiv.org/abs/2409.14113)<br/>

---

## MetaStain: Stain-generalizable Meta-learning for Cell Segmentation and Classification with Limited Exemplars<br/>
**Authors:** Konwer, Aishik, Prasanna, Prateek<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2372_paper.pdf)<br/>

---

## HRDecoder: High-Resolution Decoder Network for Fundus Image Lesion Segmentation<br/>
**Authors:** Ding, Ziyuan, Liang, Yixiong, Kan, Shichao, Liu, Qing<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/4020_paper.pdf)<br/>

---

## A Hyperreflective Foci Segmentation Network for OCT Images with Multi-dimensional Semantic Enhancement<br/>
**Authors:** Wang, Xingguo, Ma, Yuhui, Guo, Xinyu, Zheng, Yalin, Zhang, Jiong, Liu, Yonghuai, Zhao, Yitian<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/4063_paper.pdf)<br/>

---

## Causality-Informed Fusion Network for Automated Assessment of Parkinsonian Body Bradykinesia<br/>
**Authors:** Quan, Yuyang, Zhang, Chencheng, Guo, Rui, Qian, Xiaohua<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/4133_paper.pdf)<br/>

---

## [Genomics-guided Representation Learning for Pathologic Pan-cancer Tumor Microenvironment Subtype Prediction](https://arxiv.org/abs/2406.06517)<br/>
**Authors:** Meng, Fangliangzi, Zhang, Hongrun, Yan, Ruodan, Chuai, Guohui, Li, Chao, Liu, Qi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1063_paper.pdf)<br/>
**arXiv:** [2406.06517](https://arxiv.org/abs/2406.06517)<br/>

---

## A Domain Adaption Approach for EEG-based Automated Seizure Classification with Temporal-Spatial-Spectral Attention<br/>
**Authors:** Fan, Xiaoya, Xu, Pengzhi, Zhao, Qi, Hao, Chenru, Zhao, Zheng, Wang, Zhong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1802_paper.pdf)<br/>

---

## Self-supervised Denoising and Bulk Motion Artifact Removal of 3D Optical Coherence Tomography Angiography of Awake Brain<br/>
**Authors:** Li, Zhenghong, Ren, Jiaxiang, Zou, Zhilin, Garigapati, Kalyan, Du, Congwu, Pan, Yingtian, Ling, Haibin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0736_paper.pdf)<br/>

---

## [Diff3Dformer: Leveraging Slice Sequence Diffusion for Enhanced 3D CT Classification with Transformer Networks](https://arxiv.org/abs/2406.17173)<br/>
**Authors:** Jin, Zihao, Fang, Yingying, Huang, Jiahao, Xu, Caiwen, Walsh, Simon, Yang, Guang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0750_paper.pdf)<br/>
**arXiv:** [2406.17173](https://arxiv.org/abs/2406.17173)<br/>

---

## Towards realistic needle insertion training simulator using partitioned model order reduction<br/>
**Authors:** Vanneste, Félix, Martin, Claire, Goury, Olivier, Courtecuisse, Hadrien, Pernod, Erik, Cotin, Stéphane, Duriez, Christian<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2954_paper.pdf)<br/>

---

## Domain Adaptation for Unsupervised Cancer Detection: An application for skin Whole Slides Images from an interhospital dataset<br/>
**Authors:** P. García-de-la-Puente, Natalia, López-Pérez, Miguel, Launet, Laëtitia, Naranjo, Valery<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3110_paper.pdf)<br/>

---

## Multi-Modal Data Fusion with Missing Data Handling for Mild Cognitive Impairment Progression Prediction<br/>
**Authors:** Liu, Shuting, Zhang, Baochang, Zimmer, Veronika A., Rueckert, Daniel<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1443_paper.pdf)<br/>

---

## Medical Cross-Modal Prompt Hashing with Robust Noisy Correspondence Learning<br/>
**Authors:** Liu, Yishu, Wu, Zhongqi, Chen, Bingzhi, Zhang, Zheng, Lu, Guangming<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2150_paper.pdf)<br/>

---

## Correlation-adaptive Multi-view CEUS Fusion for Liver Cancer Diagnosis<br/>
**Authors:** Wan, Peng, Zhang, Shukang, Shao, Wei, Zhao, Junyong, Yang, Yinkai, Kong, Wentao, Xue, Haiyan, Zhang, Daoqiang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0746_paper.pdf)<br/>

---

## Striving for Simplicity: Simple Yet Effective Prior-Aware Pseudo-Labeling for Semi-Supervised Ultrasound Image Segmentation<br/>
**Authors:** Chen, Yaxiong, Wang, Yujie, Zheng, Zixuan, Hu, Jingliang, Shi, Yilei, Xiong, Shengwu, Zhu, Xiao Xiang, Mou, Lichao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2948_paper.pdf)<br/>

---

## Anatomically-Guided Segmentation of Cerebral Microbleeds in T1-weighted and T2*-weighted MRI<br/>
**Authors:** Kwon, Junmo, Seo, Sang Won, Park, Hyunjin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2508_paper.pdf)<br/>

---

## Joint EM Image Denoising and Segmentation with Instance-aware Interaction<br/>
**Authors:** Wang, Zhicheng, Li, Jiacheng, Chen, Yinda, Shou, Jiateng, Deng, Shiyu, Huang, Wei, Xiong, Zhiwei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1351_paper.pdf)<br/>

---

## GBT: Geometric-oriented Brain Transformer for Autism Diagnosis<br/>
**Authors:** Peng, Zhihao, He, Zhibin, Jiang, Yu, Wang, Pengyu, Yuan, Yixuan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2778_paper.pdf)<br/>

---

## HoG-Net: Hierarchical Multi-Organ Graph Network for Head and Neck Cancer Recurrence Prediction from CT Images<br/>
**Authors:** Bae, Joseph, Kapse, Saarthak, Zhou, Lei, Mani, Kartik, Prasanna, Prateek<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3878_paper.pdf)<br/>

---

## [HATs: Hierarchical Adaptive Taxonomy Segmentation for Panoramic Pathology Image Analysis](https://arxiv.org/abs/2407.00596)<br/>
**Authors:** Deng, Ruining, Liu, Quan, Cui, Can, Yao, Tianyuan, Xiong, Juming, Bao, Shunxing, Li, Hao, Yin, Mengmeng, Wang, Yu, Zhao, Shilin, Tang, Yucheng, Yang, Haichun, Huo, Yuankai<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1451_paper.pdf)<br/>
**arXiv:** [2407.00596](https://arxiv.org/abs/2407.00596)<br/>

---

## Deep intra-operative illumination calibration of hyperspectral cameras<br/>
**Authors:** Baumann, Alexander, Ayala, Leonardo, Studier-Fischer, Alexander, Sellner, Jan, Özdemir, Berkin, Kowalewski, Karl-Friedrich, Ilic, Slobodan, Seidlitz, Silvia, Maier-Hein, Lena<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3323_paper.pdf)<br/>

---

## Multi-sequence learning for multiple sclerosis lesion segmentation in spinal cord MRI<br/>
**Authors:** Walsh, Ricky, Gaubert, Malo, Meurée, Cédric, Hussein, Burhan Rashid, Kerbrat, Anne, Casey, Romain, Combès, Benoit, Galassi, Francesca<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3549_paper.pdf)<br/>

---

## Aligning and Restoring Imperfect ssEM images for Continuity Reconstruction<br/>
**Authors:** Lv, Yanan, Jia, Haoze, Chen, Xi, Yan, Haiyang, Han, Hua<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1172_paper.pdf)<br/>

---

## Semi-supervised Segmentation through Rival Networks Collaboration with Saliency Map in Diabetic Retinopathy<br/>
**Authors:** Kim, Eunjin, Kwon, Gitaek, Kim, Jaeyoung, Park, Hyunjin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1033_paper.pdf)<br/>

---

## Enhanced-quickDWI: Achieving equivalent clinical quality by denoising heavily sub-sampled diffusion-weighted imaging data<br/>
**Authors:** Zormpas-Petridis, Konstantinos, Candito, Antonio, Messiou, Christina, Koh, Dow-Mu, Blackledge, Matthew D.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3447_paper.pdf)<br/>

---

## RIP-AV: Joint Representative Instance Pre-training with Context Aware Network for Retinal Artery/Vein Segmentation<br/>
**Authors:** Dai, Wei, Yao, Yinghao, Kong, Hengte, Chen, Zhen Ji, Wang, Sheng, Bai, Qingshi, Sun, Haojun, Yang, Yongxin, Su, Jianzhong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1711_paper.pdf)<br/>

---

## TAPoseNet: Teeth Alignment based on Pose estimation via multi-scale Graph Convolutional Network<br/>
**Authors:** Deng, Qingxin, Yang, Xunyu, Huang, Minghan, Jiang, Landu, Zhang, Dian<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2802_paper.pdf)<br/>

---

## DSNet: A Spatio-Temporal Consistency Network for Cerebrovascular Segmentation in Digital Subtraction Angiography Sequences<br/>
**Authors:** Xie, Qihang, Zhang, Dan, Mou, Lei, Wang, Shanshan, Zhao, Yitian, Guo, Mengguo, Zhang, Jiong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1357_paper.pdf)<br/>

---

## Refining Intraocular Lens Power Calculation: A Multi-modal Framework Using Cross-layer Attention and Effective Channel Attention<br/>
**Authors:** Zhou, Qian, Zou, Hua, Wang, Zhongyuan, Jiang, Haifeng, Wang, Yong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3136_paper.pdf)<br/>

---

## [Memory-efficient High-resolution OCT Volume Synthesis with Cascaded Amortized Latent Diffusion Models](https://arxiv.org/abs/2405.16516)<br/>
**Authors:** Huang, Kun, Ma, Xiao, Zhang, Yuhan, Su, Na, Yuan, Songtao, Liu, Yong, Chen, Qiang, Fu, Huazhu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1438_paper.pdf)<br/>
**arXiv:** [2405.16516](https://arxiv.org/abs/2405.16516)<br/>

---

## Cycle-consistent Learning for Fetal Cortical Surface Reconstruction<br/>
**Authors:** Dong, Xiuyu, Wu, Zhengwang, Ma, Laifa, Wang, Ya, Tang, Kaibo, Zhang, He, Lin, Weili, Li, Gang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3476_paper.pdf)<br/>

---

## [Integrating Clinical Knowledge into Concept Bottleneck Models](https://arxiv.org/abs/2407.06600)<br/>
**Authors:** Pang, Winnie, Ke, Xueyi, Tsutsui, Satoshi, Wen, Bihan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1786_paper.pdf)<br/>
**arXiv:** [2407.06600](https://arxiv.org/abs/2407.06600)<br/>

---

## MPMNet: Modal Prior Mutual-support Network for Age-related Macular Degeneration Classification<br/>
**Authors:** Li, Yuanyuan, Hao, Huaying, Zhang, Dan, Fu, Huazhu, Liu, Mengting, Shan, Caifeng, Zhao, Yitian, Zhang, Jiong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0967_paper.pdf)<br/>

---

## Fetal MRI Reconstruction by Global Diffusion and Consistent Implicit Representation<br/>
**Authors:** Tan, Junpeng, Zhang, Xin, Qing, Chunmei, Yang, Chaoxiang, Zhang, He, Li, Gang, Xu, Xiangmin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3884_paper.pdf)<br/>

---

## ABP: Asymmetric Bilateral Prompting for Text-guided Medical Image Segmentation<br/>
**Authors:** Zeng, Xinyi, Zeng, Pinxian, Cui, Jiaqi, Li, Aibing, Liu, Bo, Wang, Chengdi, Wang, Yan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1674_paper.pdf)<br/>

---

## [An Empirical Study on the Fairness of Foundation Models for Multi-Organ Image Segmentation](https://arxiv.org/abs/2406.12646)<br/>
**Authors:** Li, Qing, Zhang, Yizhe, Li, Yan, Lyu, Jun, Liu, Meng, Sun, Longyu, Sun, Mengting, Li, Qirong, Mao, Wenyue, Wu, Xinran, Zhang, Yajing, Chu, Yinghua, Wang, Shuo, Wang, Chengyan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1289_paper.pdf)<br/>
**arXiv:** [2406.12646](https://arxiv.org/abs/2406.12646)<br/>

---

## [TaGAT: Topology-Aware Graph Attention Network For Multi-modal Retinal Image Fusion](https://arxiv.org/abs/2407.14188)<br/>
**Authors:** Tian, Xin, Anantrasirichai, Nantheera, Nicholson, Lindsay, Achim, Alin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0115_paper.pdf)<br/>
**arXiv:** [2407.14188](https://arxiv.org/abs/2407.14188)<br/>

---

## Cut to the Mix: Simple Data Augmentation Outperforms Elaborate Ones in Limited Organ Segmentation Datasets<br/>
**Authors:** Liu, Chang, Fan, Fuxin, Schwarz, Annette, Maier, Andreas<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0674_paper.pdf)<br/>

---

## [Controllable and Efficient Multi-Class Pathology Nuclei Data Augmentation using Text-Conditioned Diffusion Models](https://arxiv.org/abs/2407.14426)<br/>
**Authors:** Oh, Hyun-Jic, Jeong, Won-Ki<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0251_paper.pdf)<br/>
**arXiv:** [2407.14426](https://arxiv.org/abs/2407.14426)<br/>

---

## [MARVEL: MR Fingerprinting with Additional micRoVascular Estimates using bidirectional LSTMs](https://arxiv.org/abs/2407.10512)<br/>
**Authors:** Barrier, Antoine, Coudert, Thomas, Delphin, Aurélien, Lemasson, Benjamin, Christen, Thomas<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2226_paper.pdf)<br/>
**arXiv:** [2407.10512](https://arxiv.org/abs/2407.10512)<br/>

---

## LB-UNet: A Lightweight Boundary-assisted UNet for Skin Lesion Segmentation<br/>
**Authors:** Xu, Jiahao, Tong, Lyuyang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2135_paper.pdf)<br/>

---

## [PathM3: A Multimodal Multi-Task Multiple Instance Learning Framework for Whole Slide Image Classification and Captioning](https://arxiv.org/abs/2403.08967)<br/>
**Authors:** Zhou, Qifeng, Zhong, Wenliang, Guo, Yuzhi, Xiao, Michael, Ma, Hehuan, Huang, Junzhou<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3991_paper.pdf)<br/>
**arXiv:** [2403.08967](https://arxiv.org/abs/2403.08967)<br/>

---

## fTSPL: Enhancing Brain Analysis with fMRI-Text Synergistic Prompt Learning<br/>
**Authors:** Wang, Pengyu, Zhang, Huaqi, He, Zhibin, Peng, Zhihao, Yuan, Yixuan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2709_paper.pdf)<br/>

---

## Prior Activation Map Guided Cervical OCT Image Classification<br/>
**Authors:** Wang, Qingbin, Wong, Wai Chon, Yin, Mi, Ma, Yutao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1307_paper.pdf)<br/>

---

## [Interpretable Spatio-Temporal Embedding for Brain Structural-Effective Network with Ordinary Differential Equation](https://arxiv.org/abs/2405.13190)<br/>
**Authors:** Tang, Haoteng, Liu, Guodong, Dai, Siyuan, Ye, Kai, Zhao, Kun, Wang, Wenlu, Yang, Carl, He, Lifang, Leow, Alex, Thompson, Paul, Huang, Heng, Zhan, Liang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0919_paper.pdf)<br/>
**arXiv:** [2405.13190](https://arxiv.org/abs/2405.13190)<br/>

---

## [DinoBloom: A Foundation Model for Generalizable Cell Embeddings in Hematology](https://huggingface.co/papers/2404.05022)<br/>
**Authors:** Koch, Valentin, Wagner, Sophia J., Kazeminia, Salome, Sancar, Ece, Hehr, Matthias, Schnabel, Julia A., Peng, Tingying, Marr, Carsten<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3584_paper.pdf)<br/>
**arXiv:** [2404.05022](https://arxiv.org/abs/2404.05022)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2404.05022](https://huggingface.co/papers/2404.05022)<br/>
**🤗 Models:** [1aurent/vit_base_patch14_224.dinobloom](https://huggingface.co/1aurent/vit_base_patch14_224.dinobloom), [1aurent/vit_small_patch14_224.dinobloom](https://huggingface.co/1aurent/vit_small_patch14_224.dinobloom), [1aurent/vit_large_patch14_224.dinobloom](https://huggingface.co/1aurent/vit_large_patch14_224.dinobloom), [1aurent/vit_giant_patch14_224.dinobloom](https://huggingface.co/1aurent/vit_giant_patch14_224.dinobloom)<br/>

---

## Harnessing Temporal Information for Precise Frame-Level Predictions in Endoscopy Videos<br/>
**Authors:** Mobadersany, Pooya, Parmar, Chaitanya, Damasceno, Pablo F., Fadnavis, Shreyas, Chaitanya, Krishna, Li, Shilong, Schwab, Evan, Xiao, Jaclyn, Surace, Lindsey, Mansi, Tommaso, Cula, Gabriela Oana, Ghanem, Louis R., Standish, Kristopher<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3604_paper.pdf)<br/>

---

## IPLC: Iterative Pseudo Label Correction Guided by SAM for Source-Free Domain Adaptation in Medical Image Segmentation<br/>
**Authors:** Zhang, Guoning, Qi, Xiaoran, Yan, Bo, Wang, Guotai<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1958_paper.pdf)<br/>

---

## StereoDiffusion: Temporally Consistent Stereo Depth Estimation with Diffusion Models<br/>
**Authors:** Xu, Haozheng, Xu, Chi, Giannarou, Stamatia<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0240_paper.pdf)<br/>

---

## MEGFormer: enhancing speech decoding from brain activity through extended semantic representations<br/>
**Authors:** Boyko, Maria, Druzhinina, Polina, Kormakov, Georgii, Beliaeva, Aleksandra, Sharaev, Maxim<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1369_paper.pdf)<br/>

---

## [Enhanced Scale-aware Depth Estimation for Monocular Endoscopic Scenes with Geometric Modeling](https://arxiv.org/abs/2408.07266)<br/>
**Authors:** Wei, Ruofeng, Li, Bin, Chen, Kai, Ma, Yiyao, Liu, Yunhui, Dou, Qi<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1856_paper.pdf)<br/>
**arXiv:** [2408.07266](https://arxiv.org/abs/2408.07266)<br/>

---

## Optimizing Efficiency and Effectiveness in Sequential Prompt Strategy for SAM using Reinforcement Learning<br/>
**Authors:** Huang, Yifei, Shen, Chuyun, Li, Wenhao, Wang, Xiangfeng, Jin, Bo, Cai, Haibin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1442_paper.pdf)<br/>

---

## Multi-disease Detection in Retinal Images Guided by Disease Causal Estimation<br/>
**Authors:** Xie, Jianyang, Chen, Xiuju, Zhao, Yitian, Meng, Yanda, Zhao, He, Nguyen, Anh, Li, Xiaoxin, Zheng, Yalin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0973_paper.pdf)<br/>

---

## A Graph-Embedded Latent Space Learning and Clustering Framework for Incomplete Multimodal Multiclass Alzheimer’s Disease Diagnosis<br/>
**Authors:** Ou, Zaixin, Jiang, Caiwen, Liu, Yuxiao, Zhang, Yuanwang, Cui, Zhiming, Shen, Dinggang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1165_paper.pdf)<br/>

---

## [A Patient-Specific Framework for Autonomous Spinal Fixation via a Steerable Drilling Robot](https://arxiv.org/abs/2405.17606)<br/>
**Authors:** Sharma, Susheela, Go, Sarah, Yakay, Zeynep, Kulkarni, Yash, Kapuria, Siddhartha, Amadio, Jordan P., Rajebi, Reza, Khadem, Mohsen, Navab, Nassir, Alambeigi, Farshid<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3962_paper.pdf)<br/>
**arXiv:** [2405.17606](https://arxiv.org/abs/2405.17606)<br/>

---

## [Toward Universal Medical Image Registration via Sharpness-Aware Meta-Continual Learning](https://arxiv.org/abs/2406.17575)<br/>
**Authors:** Wang, Bomin, Luo, Xinzhe, Zhuang, Xiahai<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0150_paper.pdf)<br/>
**arXiv:** [2406.17575](https://arxiv.org/abs/2406.17575)<br/>

---

## [EM-Net: Efficient Channel and Frequency Learning with Mamba for 3D Medical Image Segmentation](https://arxiv.org/abs/2409.17675)<br/>
**Authors:** Chang, Ao, Zeng, Jiajun, Huang, Ruobing, Ni, Dong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1923_paper.pdf)<br/>
**arXiv:** [2409.17675](https://arxiv.org/abs/2409.17675)<br/>

---

## [Spatial-Division Augmented Occupancy Field for Bone Shape Reconstruction from Biplanar X-Rays](https://arxiv.org/abs/2407.15433)<br/>
**Authors:** Chen, Jixiang, Lin, Yiqun, Sun, Haoran, Li, Xiaomeng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2205_paper.pdf)<br/>
**arXiv:** [2407.15433](https://arxiv.org/abs/2407.15433)<br/>

---

## Causal Intervention for Brain tumor Segmentation<br/>
**Authors:** Liu, Hengxin, Li, Qiang, Nie, Weizhi, Xu, Zibo, Liu, Anan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2795_paper.pdf)<br/>

---

## Deep Model Reference: Simple yet Effective Confidence Estimation for Image Classification<br/>
**Authors:** Zheng, Yuanhang, Qiu, Yiqiao, Che, Haoxuan, Chen, Hao, Zheng, Wei-Shi, Wang, Ruixuan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2136_paper.pdf)<br/>

---

## TinyU-Net: Lighter yet Better U-Net with Cascaded Multi-Receptive Fields<br/>
**Authors:** Chen, Junren, Chen, Rui, Wang, Wei, Cheng, Junlong, Zhang, Lei, Chen, Liangyin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2191_paper.pdf)<br/>

---

## [TeleOR: Real-time Telemedicine System for Full-Scene Operating Room](https://arxiv.org/abs/2407.19763)<br/>
**Authors:** Wu, Yixuan, Hu, Kaiyuan, Shao, Qian, Chen, Jintai, Chen, Danny Z., Wu, Jian<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0757_paper.pdf)<br/>
**arXiv:** [2407.19763](https://arxiv.org/abs/2407.19763)<br/>

---

## SBC-AL: Structure and Boundary Consistency-based Active Learning for Medical Image Segmentation<br/>
**Authors:** Zhou, Taimin, Yang, Jin, Cui, Lingguo, Zhang, Nan, Chai, Senchun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3047_paper.pdf)<br/>

---

## WIA-LD2ND: Wavelet-based Image Alignment for Self-supervised Low-Dose CT Denoising<br/>
**Authors:** Zhao, Haoyu, Gu, Yuliang, Zhao, Zhou, Du, Bo, Xu, Yongchao, Yu, Rui<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0783_paper.pdf)<br/>

---

## [MemWarp: Discontinuity-Preserving Cardiac Registration with Memorized Anatomical Filters](https://arxiv.org/abs/2407.08093)<br/>
**Authors:** Zhang, Hang, Chen, Xiang, Hu, Renjiu, Liu, Dongdong, Li, Gaolei, Wang, Rongguang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1764_paper.pdf)<br/>
**arXiv:** [2407.08093](https://arxiv.org/abs/2407.08093)<br/>

---

## Controllable Counterfactual Generation for Interpretable Medical Image Classification<br/>
**Authors:** Liu, Shiyu, Wang, Fan, Ren, Zehua, Lian, Chunfeng, Ma, Jianhua<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1911_paper.pdf)<br/>

---

## [RoCoSDF: Row-Column Scanned Neural Signed Distance Fields for Freehand 3D Ultrasound Imaging Shape Reconstruction](https://arxiv.org/abs/2408.07325)<br/>
**Authors:** Chen, Hongbo, Gao, Yuchong, Zhang, Shuhang, Wu, Jiangjie, Ma, Yuexin, Zheng, Rui<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2031_paper.pdf)<br/>
**arXiv:** [2408.07325](https://arxiv.org/abs/2408.07325)<br/>

---

## HistoSyn: Histomorphology-Focused Pathology Image Synthesis<br/>
**Authors:** Yin, Chong, Liu, Siqi, Wong, Vincent Wai-Sun, Yuen, Pong C.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0215_paper.pdf)<br/>

---

## [Enhancing Human-Computer Interaction in Chest X-ray Analysis using Vision and Language Model with Eye Gaze Patterns](https://arxiv.org/abs/2404.02370)<br/>
**Authors:** Kim, Yunsoo, Wu, Jinge, Abdulle, Yusuf, Gao, Yue, Wu, Honghan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3261_paper.pdf)<br/>
**arXiv:** [2404.02370](https://arxiv.org/abs/2404.02370)<br/>

---

## Superpixel-Guided Segment Anything Model for Liver Tumor Segmentation with Couinaud Segment Prompt<br/>
**Authors:** Lyu, Fei, Xu, Jingwen, Zhu, Ye, Wong, Grace Lai-Hung, Yuen, Pong C.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0139_paper.pdf)<br/>

---

## [Revisiting Deep Ensemble Uncertainty for Enhanced Medical Anomaly Detection](https://arxiv.org/abs/2409.17485)<br/>
**Authors:** Gu, Yi, Lin, Yi, Cheng, Kwang-Ting, Chen, Hao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1356_paper.pdf)<br/>
**arXiv:** [2409.17485](https://arxiv.org/abs/2409.17485)<br/>

---

## [SiNGR: Brain Tumor Segmentation via Signed Normalized Geodesic Transform Regression](https://huggingface.co/papers/2405.16813)<br/>
**Authors:** Dang, Trung, Nguyen, Huy Hoang, Tiulpin, Aleksei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2261_paper.pdf)<br/>
**arXiv:** [2405.16813](https://arxiv.org/abs/2405.16813)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2405.16813](https://huggingface.co/papers/2405.16813)<br/>

---

## [Across-subject ensemble-learning alleviates the need for large samples for fMRI decoding](https://arxiv.org/abs/2407.12056)<br/>
**Authors:** Aggarwal, Himanshu, Al-Shikhley, Liza, Thirion, Bertrand<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2040_paper.pdf)<br/>
**arXiv:** [2407.12056](https://arxiv.org/abs/2407.12056)<br/>

---

## [CardioSpectrum: Comprehensive Myocardium Motion Analysis with 3D Deep Learning and Geometric Insights](https://arxiv.org/abs/2407.03794)<br/>
**Authors:** Zuler, Shahar, Tejman-Yarden, Shai, Raviv, Dan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1314_paper.pdf)<br/>
**arXiv:** [2407.03794](https://arxiv.org/abs/2407.03794)<br/>

---

## [Location embedding based pairwise distance learning for fine-grained diagnosis of urinary stones](https://arxiv.org/abs/2407.00431)<br/>
**Authors:** Jin, Qiangguo, Huang, Jiapeng, Sun, Changming, Cui, Hui, Xuan, Ping, Su, Ran, Wei, Leyi, Wu, Yu-Jie, Wu, Chia-An, Duh, Henry B. L., Lu, Yueh-Hsun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1064_paper.pdf)<br/>
**arXiv:** [2407.00431](https://arxiv.org/abs/2407.00431)<br/>

---

## Real-world Visual Navigation for Cardiac Ultrasound View Planning<br/>
**Authors:** Bao, Mingkun, Wang, Yan, Wei, Xinlong, Jia, Bosen, Fan, Xiaolin, Lu, Dong, Gu, Yifan, Cheng, Jian, Zhang, Yingying, Wang, Chuanyu, Zhu, Haogang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0730_paper.pdf)<br/>

---

## [ModelMix: A New Model-Mixup Strategy to Minimize Vicinal Risk across Tasks for Few-scribble based Cardiac Segmentation](https://arxiv.org/abs/2406.13237)<br/>
**Authors:** Zhang, Ke, Patel, Vishal M.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2265_paper.pdf)<br/>
**arXiv:** [2406.13237](https://arxiv.org/abs/2406.13237)<br/>

---

## Adversarial Diffusion Model for Domain-Adaptive Depth Estimation in Bronchoscopic Navigation<br/>
**Authors:** Yang, Yiguang, Ning, Guochen, Zhong, Changhao, Liao, Hongen<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1749_paper.pdf)<br/>

---

## Energy-Based Controllable Radiology Report Generation with Medical Knowledge<br/>
**Authors:** Hou, Zeyi, Yan, Ruixin, Yan, Ziye, Lang, Ning, Zhou, Xiuzhuang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0765_paper.pdf)<br/>

---

## FRCNet: Frequency and Region Consistency for Semi-supervised Medical Image Segmentation<br/>
**Authors:** He, Along, Li, Tao, Wu, Yanlin, Zou, Ke, Fu, Huazhu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0245_paper.pdf)<br/>

---

## [MedCLIP-SAM: Bridging Text and Image Towards Universal Medical Image Segmentation](https://arxiv.org/abs/2403.20253)<br/>
**Authors:** Koleilat, Taha, Asgariandehkordi, Hojat, Rivaz, Hassan, Xiao, Yiming<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2311_paper.pdf)<br/>
**arXiv:** [2403.20253](https://arxiv.org/abs/2403.20253)<br/>

---

## MCAD: Multi-modal Conditioned Adversarial Diffusion Model for High-Quality PET Image Reconstruction<br/>
**Authors:** Cui, Jiaqi, Zeng, Xinyi, Zeng, Pinxian, Liu, Bo, Wu, Xi, Zhou, Jiliu, Wang, Yan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1340_paper.pdf)<br/>

---

## Simulation Based Inference for PET iterative reconstruction<br/>
**Authors:** Bergere, Bastien, Dautremer, Thomas, Comtat, Claude<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3386_paper.pdf)<br/>

---

## XA-Sim2Real: Adaptive Representation Learning for Vessel Segmentation in X-ray Angiography<br/>
**Authors:** Zhang, Baochang, Zhang, Zichen, Liu, Shuting, Faghihroohi, Shahrooz, Schunkert, Heribert, Navab, Nassir<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1441_paper.pdf)<br/>

---

## [Rethinking Histology Slide Digitization Workflows for Low-Resource Settings](https://arxiv.org/abs/2405.08169)<br/>
**Authors:** Zehra, Talat, Marino, Joseph, Wang, Wendy, Frantsuzov, Grigoriy, Nadeem, Saad<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2279_paper.pdf)<br/>
**arXiv:** [2405.08169](https://arxiv.org/abs/2405.08169)<br/>

---

## [Towards Multi-modality Fusion and Prototype-based Feature Refinement for Clinically Significant Prostate Cancer Classification in Transrectal Ultrasound](https://arxiv.org/abs/2406.14069)<br/>
**Authors:** Wu, Hong, Fu, Juan, Ye, Hongsheng, Zhong, Yuming, Zou, Xuebin, Zhou, Jianhua, Wang, Yi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0721_paper.pdf)<br/>
**arXiv:** [2406.14069](https://arxiv.org/abs/2406.14069)<br/>

---

## Attention-Enhanced Fusion of Structural and Functional MRI for Analyzing HIV-Associated Asymptomatic Neurocognitive Impairment<br/>
**Authors:** Fang, Yuqi, Wang, Wei, Wang, Qianqian, Li, Hong-Jun, Liu, Mingxia<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0262_paper.pdf)<br/>

---

## [Iterative Online Image Synthesis via Diffusion Model for Imbalanced Classification](https://arxiv.org/abs/2403.08407)<br/>
**Authors:** Li, Shuhan, Lin, Yi, Chen, Hao, Cheng, Kwang-Ting<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0901_paper.pdf)<br/>
**arXiv:** [2403.08407](https://arxiv.org/abs/2403.08407)<br/>

---

## Modeling and Understanding Uncertainty in Medical Image Classification<br/>
**Authors:** Chen, Aobo, Li, Yangyi, Qian, Wei, Morse, Kathryn, Miao, Chenglin, Huai, Mengdi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1623_paper.pdf)<br/>

---

## Prediction of Disease-Related Femur Shape Changes Using Geometric Encoding and Clinical Context on a Hip Disease CT Database<br/>
**Authors:** Li, Ganping, Otake, Yoshito, Soufi, Mazen, Masuda, Masachika, Uemura, Keisuke, Takao, Masaki, Sugano, Nobuhiko, Sato, Yoshinobu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/4076_paper.pdf)<br/>

---

## Uncertainty-Aware Multi-View Learning for Prostate Cancer Grading with DWI<br/>
**Authors:** Dong, Zhicheng, Yue, Xiaodong, Chen, Yufei, Zhou, Xujing, Liang, Jiye<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2652_paper.pdf)<br/>

---

## [This actually looks like that: Proto-BagNets for local and global interpretability-by-design](https://arxiv.org/abs/2406.15168)<br/>
**Authors:** Djoumessi, Kerol, Bah, Bubacarr, Kühlewein, Laura, Berens, Philipp, Koch, Lisa<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0480_paper.pdf)<br/>
**arXiv:** [2406.15168](https://arxiv.org/abs/2406.15168)<br/>

---

## Inter-Intra High-Order Brain Network for ASD Diagnosis via Functional MRIs<br/>
**Authors:** Han, Xiangmin, Xue, Rundong, Du, Shaoyi, Gao, Yue<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1263_paper.pdf)<br/>

---

## DermaVQA: A Multilingual Visual Question Answering Dataset for Dermatology<br/>
**Authors:** Yim, Wen-wai, Fu, Yujuan, Sun, Zhaoyi, Ben Abacha, Asma, Yetisgen, Meliha, Xia, Fei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2444_paper.pdf)<br/>

---

## DES-SAM: Distillation-Enhanced Semantic SAM for Cervical Nuclear Segmentation with Box Annotation<br/>
**Authors:** Huang, Lina, Liang, Yixiong, Liu, Jianfeng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2521_paper.pdf)<br/>

---

## [MH-pFLGB: Model Heterogeneous personalized Federated Learning via Global Bypass for Medical Image Analysis](https://arxiv.org/abs/2407.00474)<br/>
**Authors:** Xie, Luyuan, Lin, Manqing, Xu, ChenMing, Luan, Tianyu, Zeng, Zhipeng, Qian, Wenjun, Li, Cong, Fang, Yuejian, Shen, Qingni, Wu, Zhonghai<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0040_paper.pdf)<br/>
**arXiv:** [2407.00474](https://arxiv.org/abs/2407.00474)<br/>

---

## [LKM-UNet: Large Kernel Vision Mamba UNet for Medical Image Segmentation](https://arxiv.org/abs/2403.07332)<br/>
**Authors:** Wang, Jinhong, Chen, Jintai, Chen, Danny Z., Wu, Jian<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0286_paper.pdf)<br/>
**arXiv:** [2403.07332](https://arxiv.org/abs/2403.07332)<br/>

---

## Improving Neoadjuvant Therapy Response Prediction by Integrating Longitudinal Mammogram Generation with Cross-Modal Radiological Reports: A Vision-Language Alignment-guided Model<br/>
**Authors:** Gao, Yuan, Zhou, Hong-Yu, Wang, Xin, Zhang, Tianyu, Han, Luyi, Lu, Chunyao, Liang, Xinglong, Teuwen, Jonas, Beets-Tan, Regina, Tan, Tao, Mann, Ritse<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1552_paper.pdf)<br/>

---

## IHRRB-DINO: Identifying High-Risk Regions of Breast Masses in Mammogram Images Using Data-Driven Instance Noise (DINO)<br/>
**Authors:** Kasem, Mahmoud SalahEldin, Abdallah, Abdelrahman, Abdelhalim, Ibrahim, Alghamdi, Norah Saleh, Contractor, Sohail, El-Baz, Ayman<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3797_paper.pdf)<br/>

---

## [Hallucination Index: An Image Quality Metric for Generative Reconstruction Models](https://arxiv.org/abs/2407.12780)<br/>
**Authors:** Tivnan, Matthew, Yoon, Siyeop, Chen, Zhennong, Li, Xiang, Wu, Dufan, Li, Quanzheng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3513_paper.pdf)<br/>
**arXiv:** [2407.12780](https://arxiv.org/abs/2407.12780)<br/>

---

## [Spatial-aware Attention Generative Adversarial Network for Semi-supervised Anomaly Detection in Medical Image](https://arxiv.org/abs/2405.12872)<br/>
**Authors:** Zhang, Zerui, Sun, Zhichao, Liu, Zelong, Zhao, Zhou, Yu, Rui, Du, Bo, Xu, Yongchao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1816_paper.pdf)<br/>
**arXiv:** [2405.12872](https://arxiv.org/abs/2405.12872)<br/>

---

## LUCIDA: Low-dose Universal-tissue CT Image Domain Adaptation For Medical Segmentation<br/>
**Authors:** Chen, Yixin, Meng, Xiangxi, Wang, Yan, Zeng, Shuang, Liu, Xi, Xie, Zhaoheng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0562_paper.pdf)<br/>

---

## [PRISM: A Promptable and Robust Interactive Segmentation Model with Visual Prompts](https://arxiv.org/abs/2404.15028)<br/>
**Authors:** Li, Hao, Liu, Han, Hu, Dewei, Wang, Jiacheng, Oguz, Ipek<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0293_paper.pdf)<br/>
**arXiv:** [2404.15028](https://arxiv.org/abs/2404.15028)<br/>

---

## [TP-DRSeg: Improving Diabetic Retinopathy Lesion Segmentation with Explicit Text-Prompts Assisted SAM](https://arxiv.org/abs/2406.15764)<br/>
**Authors:** Li, Wenxue, Xiong, Xinyu, Xia, Peng, Ju, Lie, Ge, Zongyuan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0014_paper.pdf)<br/>
**arXiv:** [2406.15764](https://arxiv.org/abs/2406.15764)<br/>

---

## [GCAN: Generative Counterfactual Attention-guided Network for Explainable Cognitive Decline Diagnostics based on fMRI Functional Connectivity](https://arxiv.org/abs/2403.01758)<br/>
**Authors:** Shen, Xiongri, Song, Zhenxi, Zhang, Zhiguo<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2633_paper.pdf)<br/>
**arXiv:** [2403.01758](https://arxiv.org/abs/2403.01758)<br/>

---

## Towards Rapid Mycetoma Species Diagnosis: A Deep Learning Approach for Stain-Invariant Classification on H   E Images from Senegal<br/>
**Authors:** Zinsou, Kpêtchéhoué Merveille Santi, Diop, Cheikh Talibouya, Diop, Idy, Tsirikoglou, Apostolia, Siddig, Emmanuel Edwar, Sow, Doudou, Ndiaye, Maodo<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1516_paper.pdf)<br/>

---

## SegMamba: Long-range Sequential Modeling Mamba For 3D Medical Image Segmentation<br/>
**Authors:** Xing, Zhaohu, Ye, Tian, Yang, Yijun, Liu, Guang, Zhu, Lei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0663_paper.pdf)<br/>

---

## PEPSI: Pathology-Enhanced Pulse-Sequence-Invariant Representations for Brain MRI<br/>
**Authors:** Liu, Peirong, Puonti, Oula, Sorby-Adams, Annabel, Kimberly, W. Taylor, Iglesias, Juan E.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0253_paper.pdf)<br/>

---

## See, Predict, Plan: Diffusion for Procedure Planning in Robotic Surgical Videos<br/>
**Authors:** Zhao, Ziyuan, Fang, Fen, Yang, Xulei, Xu, Qianli, Guan, Cuntai, Zhou, S. Kevin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2373_paper.pdf)<br/>

---

## Characterizing the left ventricular ultrasound dynamics in the frequency domain to estimate the cardiac function<br/>
**Authors:** Carrera-Pinzón, Andrés Felipe, Toro-Quitian, Leonard, Torres, Juan Camilo, Cerón, Alexander, Sarmiento, Wilsón, Mendez-Toro, Arnold, Cruz-Roa, Angel, Gutiérrez-Carvajal, R. E., Órtiz-Davila, Carlos, González, Fabio, Romero, Eduardo, Iregui Guerrero, Marcela<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3315_paper.pdf)<br/>

---

## Label-guided Teacher for Surgical Phase Recognition via Knowledge Distillation<br/>
**Authors:** Guan, Jiale, Zou, Xiaoyang, Tao, Rong, Zheng, Guoyan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1997_paper.pdf)<br/>

---

## SOM2LM: Self-Organized Multi-Modal Longitudinal Maps<br/>
**Authors:** Ouyang, Jiahong, Zhao, Qingyu, Adeli, Ehsan, Zaharchuk, Greg, Pohl, Kilian M.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0405_paper.pdf)<br/>

---

## An Evaluation of State-of-the-Art Projectors in the Presence of Noise and Nonlinearity in the Beer-Lambert Law<br/>
**Authors:** Xie, Shiyu, Zhang, Kai, Entezari, Alireza<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1606_paper.pdf)<br/>

---

## BrainSCK: Brain Structure and Cognition Alignment via Knowledge Injection and Reactivation for Diagnosing Brain Disorders<br/>
**Authors:** Wang, Lilong, Liu, Mianxin, Zhang, Shaoting, Wang, Xiaosong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1779_paper.pdf)<br/>

---

## Conditional 4D Motion Diffusion Models with Masked Observations to Forecast Deformations<br/>
**Authors:** Thibeault, Sylvain, Romaguera, Liset Vazquez, Kadoury, Samuel<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0595_paper.pdf)<br/>

---

## DiffDGSS: Generalizable Retinal Image Segmentation with Deterministic Representation from Diffusion Models<br/>
**Authors:** Xie, Yingpeng, Qu, Junlong, Xie, Hai, Wang, Tianfu, Lei, Baiying<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1173_paper.pdf)<br/>

---

## Automatic Mandibular Semantic Segmentation of Teeth Pulp Cavity and Root Canals, and Inferior Alveolar Nerve on Pulpy3D Dataset<br/>
**Authors:** Gamal, Mahmoud, Baraka, Marwa, Torki, Marwan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1419_paper.pdf)<br/>

---

## Follow Sonographers’ Visual Scan-path: Adjusting CNN Model for Diagnosing Gout from Musculoskeletal Ultrasound<br/>
**Authors:** Tang, Xin, Cao, Zhi, Zhang, Weijing, Zhao, Di, Liao, Hongen, Zhang, Daoqiang, Chen, Fang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1614_paper.pdf)<br/>

---

## DiffuseReg: Denoising Diffusion Model for Obtaining Deformation Fields in Unsupervised Deformable Image Registration<br/>
**Authors:** Zhuo, Yongtai, Shen, Yiqing<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1193_paper.pdf)<br/>

---

## [Continual Domain Incremental Learning for Privacy-aware Digital Pathology](https://arxiv.org/abs/2409.06455)<br/>
**Authors:** Kumari, Pratibha, Reisenbüchler, Daniel, Luttner, Lucas, Schaadt, Nadine S., Feuerhake, Friedrich, Merhof, Dorit<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2182_paper.pdf)<br/>
**arXiv:** [2409.06455](https://arxiv.org/abs/2409.06455)<br/>

---

## [Shortcut Learning in Medical Image Segmentation](https://arxiv.org/abs/2403.06748)<br/>
**Authors:** Lin, Manxi, Weng, Nina, Mikolaj, Kamil, Bashir, Zahra, Svendsen, Morten B. S., Tolsgaard, Martin G., Christensen, Anders Nymark, Feragen, Aasa<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0423_paper.pdf)<br/>
**arXiv:** [2403.06748](https://arxiv.org/abs/2403.06748)<br/>

---

## EMF-former: An Efficient and Memory-Friendly Transformer for Medical Image Segmentation<br/>
**Authors:** Hao, Zhaoquan, Quan, Hongyan, Lu, Yinbin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1181_paper.pdf)<br/>

---

## AutoSkull: Learning-based Skull Estimation for Automated Pipelines<br/>
**Authors:** Milojevic, Aleksandar, Peter, Daniel, Huber, Niko B., Azevedo, Luis, Latyshev, Andrei, Sailer, Irena, Gross, Markus, Thomaszewski, Bernhard, Solenthaler, Barbara, Gözcü, Baran<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2202_paper.pdf)<br/>

---

## [Biophysics Informed Pathological Regularisation for Brain Tumour Segmentation](https://arxiv.org/abs/2403.09136)<br/>
**Authors:** Zhang, Lipei, Cheng, Yanqi, Liu, Lihao, Schönlieb, Carola-Bibiane, Aviles-Rivero, Angelica I<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2262_paper.pdf)<br/>
**arXiv:** [2403.09136](https://arxiv.org/abs/2403.09136)<br/>

---

## A Scanning Laser Ophthalmoscopy Image Database and Trustworthy Retinal Disease Detection Method<br/>
**Authors:** Hu, Yichen, Wang, Chao, Song, Weitao, Tiulpin, Aleksei, Liu, Qing<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1108_paper.pdf)<br/>

---

## LSSNet: A Method for Colon Polyp Segmentation Based on Local Feature Supplementation and Shallow Feature Supplementation<br/>
**Authors:** Wang, Wei, Sun, Huiying, Wang, Xin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1926_paper.pdf)<br/>

---

## [FedFMS: Exploring Federated Foundation Models for Medical Image Segmentation](https://arxiv.org/abs/2403.05408)<br/>
**Authors:** Liu, Yuxi, Luo, Guibo, Zhu, Yuesheng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0366_paper.pdf)<br/>
**arXiv:** [2403.05408](https://arxiv.org/abs/2403.05408)<br/>

---

## ESPA: An Unsupervised Harmonization Framework via Enhanced Structure Preserving Augmentation<br/>
**Authors:** Eshaghzadeh Torbati, Mahbaneh, Minhas, Davneet S., Tafti, Ahmad P., DeCarli, Charles S., Tudorascu, Dana L., Hwang, Seong Jae<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1131_paper.pdf)<br/>

---

## Conditional diffusion model with spatial attention and latent embedding for medical image segmentation<br/>
**Authors:** Hejrati, Behzad, Banerjee, Soumyanil, Glide-Hurst, Carri, Dong, Ming<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3622_paper.pdf)<br/>

---

## Anatomy-guided Pathology Segmentation<br/>
**Authors:** Jaus, Alexander, Seibold, Constantin, Reiß, Simon, Heine, Lukas, Schily, Anton, Kim, Moon, Bahnsen, Fin Hendrik, Herrmann, Ken, Stiefelhagen, Rainer, Kleesiek, Jens<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1464_paper.pdf)<br/>

---

## [Mitigating attribute amplification in counterfactual image generation](https://arxiv.org/abs/2403.09422)<br/>
**Authors:** Xia, Tian, Roschewitz, Mélanie, De Sousa Ribeiro, Fabio, Jones, Charles, Glocker, Ben<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1002_paper.pdf)<br/>
**arXiv:** [2403.09422](https://arxiv.org/abs/2403.09422)<br/>

---

## [Towards Explainable Automated Neuroanatomy](https://arxiv.org/abs/2404.05814)<br/>
**Authors:** Qian, Kui, Qiao, Litao, Friedman, Beth, O’Donnell, Edward, Kleinfeld, David, Freund, Yoav<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2587_paper.pdf)<br/>
**arXiv:** [2404.05814](https://arxiv.org/abs/2404.05814)<br/>

---

## [CUTS: A Deep Learning and Topological Framework for Multigranular Unsupervised Medical Image Segmentation](https://arxiv.org/abs/2209.11359)<br/>
**Authors:** Liu, Chen, Amodio, Matthew, Shen, Liangbo L., Gao, Feng, Avesta, Arman, Aneja, Sanjay, Wang, Jay C., Del Priore, Lucian V., Krishnaswamy, Smita<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1569_paper.pdf)<br/>
**arXiv:** [2209.11359](https://arxiv.org/abs/2209.11359)<br/>

---

## CheXtriev: Anatomy-Centered Representation for Case-Based Retrieval of Chest Radiographs<br/>
**Authors:** Akash R.  J., Naren, Tadanki, Arihanth, Sivaswamy, Jayanthi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3636_paper.pdf)<br/>

---

## Universal Semi-Supervised Learning for Medical Image Classification<br/>
**Authors:** Ju, Lie, Wu, Yicheng, Feng, Wei, Yu, Zhen, Wang, Lin, Zhu, Zhuoting, Ge, Zongyuan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/4152_paper.pdf)<br/>

---

## LGA: A Language Guide Adapter for Advancing the SAM Model’s Capabilities in Medical Image Segmentation<br/>
**Authors:** Hu, Jihong, Li, Yinhao, Sun, Hao, Song, Yu, Zhang, Chujie, Lin, Lanfen, Chen, Yen-Wei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3350_paper.pdf)<br/>

---

## Advancing H   E-to-IHC Virtual Staining with Task-Specific Domain Knowledge for HER2 Scoring<br/>
**Authors:** Peng, Qiong, Lin, Weiping, Hu, Yihuang, Bao, Ailisi, Lian, Chenyu, Wei, Weiwei, Yue, Meng, Liu, Jingxin, Yu, Lequan, Wang, Liansheng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3227_paper.pdf)<br/>

---

## Unsupervised Ultrasound Image Quality Assessment with Score Consistency and Relativity Co-learning<br/>
**Authors:** Guo, Juncheng, Lin, Jianxin, Tan, Guanghua, Lu, Yuhuan, Gao, Zhan, Li, Shengli, Li, Kenli<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3238_paper.pdf)<br/>

---

## [Realistic Surgical Image Dataset Generation Based On 3D Gaussian Splatting](https://arxiv.org/abs/2407.14846)<br/>
**Authors:** Zeng, Tianle, Loza Galindo, Gerardo, Hu, Junlei, Valdastri, Pietro, Jones, Dominic<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1448_paper.pdf)<br/>
**arXiv:** [2407.14846](https://arxiv.org/abs/2407.14846)<br/>

---

## [EndoDAC: Efficient Adapting Foundation Model for Self-Supervised Depth Estimation from Any Endoscopic Camera](https://arxiv.org/abs/2405.08672)<br/>
**Authors:** Cui, Beilei, Islam, Mobarakol, Bai, Long, Wang, An, Ren, Hongliang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0225_paper.pdf)<br/>
**arXiv:** [2405.08672](https://arxiv.org/abs/2405.08672)<br/>

---

## Continually Tuning a Large Language Model for Multi-domain Radiology Report Generation<br/>
**Authors:** Sun, Yihua, Khor, Hee Guan, Wang, Yuanzheng, Wang, Zhuhao, Zhao, Hongliang, Zhang, Yu, Ma, Longfei, Zheng, Zhuozhao, Liao, Hongen<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0254_paper.pdf)<br/>

---

## Semi-supervised Lymph Node Metastasis Classification with Pathology-guided Label Sharpening and Two-streamed Multi-scale Fusion<br/>
**Authors:** Li, Haoshen, Wang, Yirui, Zhu, Jie, Guo, Dazhou, Yu, Qinji, Yan, Ke, Lu, Le, Ye, Xianghua, Zhang, Li, Wang, Qifeng, Jin, Dakai<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0793_paper.pdf)<br/>

---

## [Conditional Score-Based Diffusion Model for Cortical Thickness Trajectory Prediction](https://arxiv.org/abs/2403.06940)<br/>
**Authors:** Xiao, Qing, Yoon, Siyeop, Ren, Hui, Tivnan, Matthew, Sun, Lichao, Li, Quanzheng, Liu, Tianming, Zhang, Yu, Li, Xiang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2542_paper.pdf)<br/>
**arXiv:** [2403.06940](https://arxiv.org/abs/2403.06940)<br/>

---

## HUP-3D: A 3D multi-view synthetic dataset for assisted-egocentric hand-ultrasound-probe pose estimation<br/>
**Authors:** Birlo, Manuel, Caramalau, Razvan, Edwards, Philip J. “Eddie”, Dromey, Brian, Clarkson, Matthew J., Stoyanov, Danail<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1531_paper.pdf)<br/>

---

## Misaligned 3D Texture Optimization in MIS Utilizing Generative Framework<br/>
**Authors:** Zheng, Jieyu, Li, Xiaojian, Mo, Hangjie, Li, Ling, Ma, Xiang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2885_paper.pdf)<br/>

---

## [All-In-One Medical Image Restoration via Task-Adaptive Routing](https://arxiv.org/abs/2405.19769)<br/>
**Authors:** Yang, Zhiwen, Chen, Haowei, Qian, Ziniu, Yi, Yang, Zhang, Hui, Zhao, Dan, Wei, Bingzheng, Xu, Yan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0787_paper.pdf)<br/>
**arXiv:** [2405.19769](https://arxiv.org/abs/2405.19769)<br/>

---

## A Novel Tracking Framework for Devices in X-ray Leveraging Supplementary Cue-Driven Self-Supervised Features<br/>
**Authors:** Islam, Saahil, Murthy, Venkatesh N., Neumann, Dominik, Cimen, Serkan, Sharma, Puneet, Maier, Andreas, Comaniciu, Dorin, Ghesu, Florin C.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2053_paper.pdf)<br/>

---

## [Diffusion as Sound Propagation: Physics-inspired Model for Ultrasound Image Generation](https://arxiv.org/abs/2407.05428)<br/>
**Authors:** Domínguez, Marina, Velikova, Yordanka, Navab, Nassir, Azampour, Mohammad Farid<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2125_paper.pdf)<br/>
**arXiv:** [2407.05428](https://arxiv.org/abs/2407.05428)<br/>

---

## [Nonrigid Reconstruction of Freehand Ultrasound without a Tracker](https://arxiv.org/abs/2407.05767)<br/>
**Authors:** Li, Qi, Shen, Ziyi, Yang, Qianye, Barratt, Dean C., Clarkson, Matthew J., Vercauteren, Tom, Hu, Yipeng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2245_paper.pdf)<br/>
**arXiv:** [2407.05767](https://arxiv.org/abs/2407.05767)<br/>

---

## Fine-grained Prompt Tuning: A Parameter and Memory Efficient Transfer Learning Method for High-resolution Medical Image Classification<br/>
**Authors:** Huang, Yijin, Cheng, Pujin, Tam, Roger, Tang, Xiaoying<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2750_paper.pdf)<br/>

---

## [LiverUSRecon: Automatic 3D Reconstruction and Volumetry of the Liver with a Few Partial Ultrasound Scans](https://arxiv.org/abs/2406.19336)<br/>
**Authors:** Sivayogaraj, Kaushalya, Guruge, Sahan I. T., Liyanage, Udari A., Udupihille, Jeevani J., Jayasinghe, Saroj, Fernando, Gerard M. X., Rodrigo, Ranga, Liyanaarachchi, Rukshani<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3416_paper.pdf)<br/>
**arXiv:** [2406.19336](https://arxiv.org/abs/2406.19336)<br/>

---

## [Improving cone-beam CT Image Quality with Knowledge Distillation-Enhanced Diffusion Model in Imbalanced Data Settings](https://arxiv.org/abs/2409.12539)<br/>
**Authors:** Hwang, Joonil, Park, Sangjoon, Park, NaHyeon, Cho, Seungryong, Kim, Jin Sung<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1234_paper.pdf)<br/>
**arXiv:** [2409.12539](https://arxiv.org/abs/2409.12539)<br/>

---

## Deep-learning-based groupwise registration for motion correction of cardiac T1 mapping<br/>
**Authors:** Zhang, Yi, Zhao, Yidong, Huang, Lu, Xia, Liming, Tao, Qian<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2857_paper.pdf)<br/>

---

## IMG-GCN: Interpretable Modularity-Guided Structure-Function Interactions Learning for Brain Cognition and Disorder Analysis<br/>
**Authors:** Xia, Jing, Chan, Yi Hao, Girish, Deepank, Rajapakse, Jagath C.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2884_paper.pdf)<br/>

---

## DINO-Reg: General Purpose Image Encoder for Training-free Multi-modal Deformable Medical Image Registration<br/>
**Authors:** Song, Xinrui, Xu, Xuanang, Yan, Pingkun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2230_paper.pdf)<br/>

---

## [SynCellFactory: Generative Data Augmentation for Cell Tracking](https://arxiv.org/abs/2404.16421)<br/>
**Authors:** Sturm, Moritz, Cerrone, Lorenzo, Hamprecht, Fred A.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3680_paper.pdf)<br/>
**arXiv:** [2404.16421](https://arxiv.org/abs/2404.16421)<br/>

---

## [Geometric Transformation Uncertainty for Improving 3D Fetal Brain Pose Prediction from Freehand 2D Ultrasound Videos](https://arxiv.org/abs/2405.13235)<br/>
**Authors:** Ramesh, Jayroop, Dinsdale, Nicola, Yeung, Pak-Hei, Namburete, Ana I. L.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2943_paper.pdf)<br/>
**arXiv:** [2405.13235](https://arxiv.org/abs/2405.13235)<br/>

---

## [SurvRNC: Learning Ordered Representations for Survival Prediction using Rank-N-Contrast](https://arxiv.org/abs/2403.10603)<br/>
**Authors:** Saeed, Numan, Ridzuan, Muhammad, Maani, Fadillah Adamsyah, Alasmawi, Hussain, Nandakumar, Karthik, Yaqub, Mohammad<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3191_paper.pdf)<br/>
**arXiv:** [2403.10603](https://arxiv.org/abs/2403.10603)<br/>

---

## [Subject-Adaptive Transfer Learning Using Resting State EEG Signals for Cross-Subject EEG Motor Imagery Classification](https://arxiv.org/abs/2405.19346)<br/>
**Authors:** An, Sion, Kang, Myeongkyun, Kim, Soopil, Chikontwe, Philip, Shen, Li, Park, Sang Hyun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0192_paper.pdf)<br/>
**arXiv:** [2405.19346](https://arxiv.org/abs/2405.19346)<br/>

---

## Reciprocal Collaboration for Semi-supervised Medical Image Classification<br/>
**Authors:** Zeng, Qingjie, Lu, Zilin, Xie, Yutong, Lu, Mengkang, Ma, Xinke, Xia, Yong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1844_paper.pdf)<br/>

---

## [Comprehensive Generative Replay for Task-Incremental Segmentation with Concurrent Appearance and Semantic Forgetting](https://arxiv.org/abs/2406.19796)<br/>
**Authors:** Li, Wei, Zhang, Jingyang, Heng, Pheng-Ann, Gu, Lixu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0187_paper.pdf)<br/>
**arXiv:** [2406.19796](https://arxiv.org/abs/2406.19796)<br/>

---

## [UnWave-Net: Unrolled Wavelet Network for Compton Tomography Image Reconstruction](https://arxiv.org/abs/2406.03413)<br/>
**Authors:** Ayad, Ishak, Tarpau, Cécilia, Cebeiro, Javier, Nguyen, Maï K.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2336_paper.pdf)<br/>
**arXiv:** [2406.03413](https://arxiv.org/abs/2406.03413)<br/>

---

## [SlideGCD: Slide-based Graph Collaborative Training with Knowledge Distillation for Whole Slide Image Classification](https://arxiv.org/abs/2407.08968)<br/>
**Authors:** Shu, Tong, Shi, Jun, Sun, Dongdong, Jiang, Zhiguo, Zheng, Yushan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2479_paper.pdf)<br/>
**arXiv:** [2407.08968](https://arxiv.org/abs/2407.08968)<br/>

---

## [Cross-Phase Mutual Learning Framework for Pulmonary Embolism Identification on Non-Contrast CT Scans](https://arxiv.org/abs/2407.11529)<br/>
**Authors:** Bai, Bizhe, Zhou, Yan-Jie, Hu, Yujian, Mok, Tony C. W., Xiang, Yilang, Lu, Le, Zhang, Hongkun, Xu, Minfeng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2986_paper.pdf)<br/>
**arXiv:** [2407.11529](https://arxiv.org/abs/2407.11529)<br/>

---

## Deformation-Aware Segmentation Network Robust to Motion Artifacts for Brain Tissue Segmentation using Disentanglement Learning<br/>
**Authors:** Jung, Sunyoung, Choi, Yoonseok, Al-masni, Mohammed A., Jung, Minyoung, Kim, Dong-Hyun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1643_paper.pdf)<br/>

---

## [MEDBind: Unifying Language and Multimodal Medical Data Embeddings](https://arxiv.org/abs/2403.12894)<br/>
**Authors:** Gao, Yuan, Kim, Sangwook, Austin, David E, McIntosh, Chris<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2333_paper.pdf)<br/>
**arXiv:** [2403.12894](https://arxiv.org/abs/2403.12894)<br/>

---

## Disentangled Hybrid Transformer for Identification of Infants with Prenatal Drug Exposure<br/>
**Authors:** Cheng, Jiale, Wu, Zhengwang, Yuan, Xinrui, Wang, Li, Lin, Weili, Grewen, Karen, Li, Gang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3719_paper.pdf)<br/>

---

## Anatomic-constrained Medical Image Synthesis via Physiological Density Sampling<br/>
**Authors:** Chu, Yuetan, Yang, Changchun, Luo, Gongning, Qiu, Zhaowen, Gao, Xin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1746_paper.pdf)<br/>

---

## IHCSurv: Effective Immunohistochemistry Priors for Cancer Survival Analysis in Gigapixel Multi-stain Whole Slide Images<br/>
**Authors:** Zhang, Yejia, Chao, Hanqing, Qiu, Zhongwei, Liu, Wenbin, Shen, Yixuan, Sapkota, Nishchal, Gu, Pengfei, Chen, Danny Z., Lu, Le, Yan, Ke, Jin, Dakai, Bian, Yun, Jiang, Hui<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0495_paper.pdf)<br/>

---

## UinTSeg: Unified Infant Brain Tissue Segmentation with Anatomy Delineation<br/>
**Authors:** Liu, Jiameng, Liu, Feihong, Sun, Kaicong, Sun, Yuhang, Huang, Jiawei, Jiang, Caiwen, Rekik, Islem, Shen, Dinggang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0074_paper.pdf)<br/>

---

## Overlay Mantle-Free for Semi-Supervised Medical Image Segmentation<br/>
**Authors:** Liu, Jiacheng, Qian, Wenhua, Cao, Jinde, Liu, Peng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0481_paper.pdf)<br/>

---

## Missing as Masking: Arbitrary Cross-modal Feature Reconstruction for Incomplete Multimodal Brain Tumor Segmentation<br/>
**Authors:** Zeng, Zhilin, Peng, Zelin, Yang, Xiaokang, Shen, Wei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0067_paper.pdf)<br/>

---

## [Textual Inversion and Self-supervised Refinement for Radiology Report Generation](https://arxiv.org/abs/2405.20607)<br/>
**Authors:** Luo, Yuanjiang, Li, Hongxiang, Wu, Xuan, Cao, Meng, Huang, Xiaoshuang, Zhu, Zhihong, Liao, Peixi, Chen, Hu, Zhang, Yi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1810_paper.pdf)<br/>
**arXiv:** [2405.20607](https://arxiv.org/abs/2405.20607)<br/>

---

## [Enable the Right to be Forgotten with Federated Client Unlearning in Medical Imaging](https://arxiv.org/abs/2407.02356)<br/>
**Authors:** Deng, Zhipeng, Luo, Luyang, Chen, Hao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1632_paper.pdf)<br/>
**arXiv:** [2407.02356](https://arxiv.org/abs/2407.02356)<br/>

---

## DCrownFormer: Morphology-aware Point-to-Mesh Generation Transformer for Dental Crown Prosthesis from 3D Scan Data of Antagonist and Preparation Teeth<br/>
**Authors:** Yang, Su, Han, Jiyong, Lim, Sang-Heon, Yoo, Ji-Yong, Kim, SuJeong, Song, Dahyun, Kim, Sunjung, Kim, Jun-Min, Yi, Won-Jin<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0638_paper.pdf)<br/>

---

## SaSaMIM: Synthetic Anatomical Semantics-Aware Masked Image Modeling for Colon Tumor Segmentation in Non-contrast Abdominal Computed Tomography<br/>
**Authors:** Dai, Pengyu, Ou, Yafei, Yang, Yuqiao, Liu, Dichao, Hashimoto, Masahiro, Jinzaki, Masahiro, Miyake, Mototaka, Suzuki, Kenji<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1664_paper.pdf)<br/>

---

## Material Decomposition in Photon-Counting CT: A Deep Learning Approach Driven by Detector Physics and ASIC Modeling<br/>
**Authors:** Yu, Xiaopeng, Wu, Qianyu, Qin, Wenhui, Zhong, Tao, Su, Mengqing, Ma, Jinglu, Zhang, Yikun, Ji, Xu, Quan, Guotao, Chen, Yang, Du, Yanfeng, Lai, Xiaochun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3032_paper.pdf)<br/>

---

## EndoSelf: Self-Supervised Monocular 3D Scene Reconstruction of Deformable Tissues with Neural Radiance Fields on Endoscopic Videos<br/>
**Authors:** Li, Wenda, Hayashi, Yuichiro, Oda, Masahiro, Kitasaka, Takayuki, Misawa, Kazunari, Mori, Kensaku<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1656_paper.pdf)<br/>

---

## HF-ResDiff: High-Frequency-guided Residual Diffusion for Multi-dose PET Reconstruction<br/>
**Authors:** Tang, Zixin, Jiang, Caiwen, Cui, Zhiming, Shen, Dinggang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1415_paper.pdf)<br/>

---

## [Whole Heart 3D+T Representation Learning Through Sparse 2D Cardiac MR Images](https://arxiv.org/abs/2406.00329)<br/>
**Authors:** Zhang, Yundi, Chen, Chen, Shit, Suprosanna, Starck, Sophie, Rueckert, Daniel, Pan, Jiazhen<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1466_paper.pdf)<br/>
**arXiv:** [2406.00329](https://arxiv.org/abs/2406.00329)<br/>

---

## [Enhancing Spatiotemporal Disease Progression Models via Latent Diffusion and Prior Knowledge](https://arxiv.org/abs/2405.03328)<br/>
**Authors:** Puglisi, Lemuel, Alexander, Daniel C., Ravì, Daniele<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0511_paper.pdf)<br/>
**arXiv:** [2405.03328](https://arxiv.org/abs/2405.03328)<br/>

---

## [Topological SLAM in colonoscopies leveraging deep features and topological priors](https://arxiv.org/abs/2409.16806)<br/>
**Authors:** Morlana, Javier, Tardós, Juan D., Montiel, José M. M.<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1110_paper.pdf)<br/>
**arXiv:** [2409.16806](https://arxiv.org/abs/2409.16806)<br/>

---

## Vessel-aware aneurysm detection using multi-scale deformable 3D attention<br/>
**Authors:** Ceballos-Arroyo, Alberto M., Nguyen, Hieu T., Zhu, Fangrui, Yadav, Shrikanth M., Kim, Jisoo, Qin, Lei, Young, Geoffrey, Jiang, Huaizu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2366_paper.pdf)<br/>

---

## [Prompt Your Brain: Scaffold Prompt Tuning for Efficient Adaptation of fMRI Pre-trained Model](https://arxiv.org/abs/2408.10567)<br/>
**Authors:** Dong, Zijian, Wu, Yilei, Chen, Zijiao, Zhang, Yichi, Jin, Yueming, Zhou, Juan Helen<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2127_paper.pdf)<br/>
**arXiv:** [2408.10567](https://arxiv.org/abs/2408.10567)<br/>

---

## [Estimation and Analysis of Slice Propagation Uncertainty in 3D Anatomy Segmentation](https://arxiv.org/abs/2403.12290)<br/>
**Authors:** Nihalaani, Rachaell, Kataria, Tushar, Adams, Jadie, Elhabian, Shireen Y.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3515_paper.pdf)<br/>
**arXiv:** [2403.12290](https://arxiv.org/abs/2403.12290)<br/>

---

## Swin-UMamba: Mamba-based UNet with ImageNet-based pretraining<br/>
**Authors:** Liu, Jiarun, Yang, Hao, Zhou, Hong-Yu, Xi, Yan, Yu, Lequan, Li, Cheng, Liang, Yong, Shi, Guangming, Yu, Yizhou, Zhang, Shaoting, Zheng, Hairong, Wang, Shanshan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1627_paper.pdf)<br/>

---

## Super-Field MRI Synthesis for Infant Brains Enhanced by Dual Channel Latent Diffusion<br/>
**Authors:** Tapp, Austin, Zhao, Can, Roth, Holger R., Tanedo, Jeffrey, Anwar, Syed Muhammad, Bourke, Niall J., Hajnal, Joseph V., Nankabirwa, Victoria, Deoni, Sean, Lepore, Natasha, Linguraru, Marius George<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3995_paper.pdf)<br/>

---

## [EndoGSLAM: Real-Time Dense Reconstruction and Tracking in Endoscopic Surgeries using Gaussian Splatting](https://huggingface.co/papers/2403.15124)<br/>
**Authors:** Wang, Kailing, Yang, Chen, Wang, Yuehao, Li, Sikuang, Wang, Yan, Dou, Qi, Yang, Xiaokang, Shen, Wei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1232_paper.pdf)<br/>
**arXiv:** [2403.15124](https://arxiv.org/abs/2403.15124)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2403.15124](https://huggingface.co/papers/2403.15124)<br/>

---

## Tagged-to-Cine MRI Sequence Synthesis via Light Spatial-Temporal Transformer<br/>
**Authors:** Liu, Xiaofeng, Xing, Fangxu, Bian, Zhangxing, Arias-Vergara, Tomas, Pérez-Toro, Paula Andrea, Maier, Andreas, Stone, Maureen, Zhuo, Jiachen, Prince, Jerry L., Woo, Jonghye<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0448_paper.pdf)<br/>

---

## Textmatch: Using Text Prompts to Improve Semi-supervised Medical Image Segmentation<br/>
**Authors:** Li, Aibing, Zeng, Xinyi, Zeng, Pinxian, Ding, Sixian, Wang, Peng, Wang, Chengdi, Wang, Yan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0960_paper.pdf)<br/>

---

## DCDiff: Dual-Domain Conditional Diffusion for CT Metal Artifact Reduction<br/>
**Authors:** Shen, Ruochong, Li, Xiaoxu, Li, Yuan-Fang, Sui, Chao, Peng, Yu, Ke, Qiuhong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1608_paper.pdf)<br/>

---

## [Learning from Partial Label Proportions for Whole Slide Image Segmentation](https://arxiv.org/abs/2405.09041)<br/>
**Authors:** Matsuo, Shinnosuke, Suehiro, Daiki, Uchida, Seiichi, Ito, Hiroaki, Terada, Kazuhiro, Yoshizawa, Akihiko, Bise, Ryoma<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1667_paper.pdf)<br/>
**arXiv:** [2405.09041](https://arxiv.org/abs/2405.09041)<br/>

---

## [Feature Extraction for Generative Medical Imaging Evaluation: New Evidence Against an Evolving Trend](https://arxiv.org/abs/2311.13717)<br/>
**Authors:** Woodland, McKell, Castelo, Austin, Al Taie, Mais, Albuquerque Marques Silva, Jessica, Eltaher, Mohamed, Mohn, Frank, Shieh, Alexander, Kundu, Suprateek, Yung, Joshua P., Patel, Ankit B., Brock, Kristy K.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2251_paper.pdf)<br/>
**arXiv:** [2311.13717](https://arxiv.org/abs/2311.13717)<br/>

---

## [Reference-free Axial Super-resolution of 3D Microscopy Images using Implicit Neural Representation with a 2D Diffusion Prior](https://arxiv.org/abs/2408.08616)<br/>
**Authors:** Lee, Kyungryun, Jeong, Won-Ki<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2483_paper.pdf)<br/>
**arXiv:** [2408.08616](https://arxiv.org/abs/2408.08616)<br/>

---

## FACMIC: Federated Adaptative CLIP Model for Medical Image Classification<br/>
**Authors:** Wu, Yihang, Desrosiers, Christian, Chaddad, Ahmad<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1577_paper.pdf)<br/>

---

## [Goal-conditioned reinforcement learning for ultrasound navigation guidance](https://arxiv.org/abs/2405.01409)<br/>
**Authors:** Amadou, Abdoul Aziz, Singh, Vivek, Ghesu, Florin C., Kim, Young-Ho, Stanciulescu, Laura, Sai, Harshitha P., Sharma, Puneet, Young, Alistair, Rajani, Ronak, Rhode, Kawal<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1889_paper.pdf)<br/>
**arXiv:** [2405.01409](https://arxiv.org/abs/2405.01409)<br/>

---

## [MoRA: LoRA Guided Multi-Modal Disease Diagnosis with Missing Modality](https://arxiv.org/abs/2408.09064)<br/>
**Authors:** Shi, Zhiyi, Kim, Junsik, Li, Wanhua, Li, Yicong, Pfister, Hanspeter<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1536_paper.pdf)<br/>
**arXiv:** [2408.09064](https://arxiv.org/abs/2408.09064)<br/>

---

## [Deep Spectral Methods for Unsupervised Ultrasound Image Interpretation](https://arxiv.org/abs/2408.02043)<br/>
**Authors:** Tmenova, Oleksandra, Velikova, Yordanka, Saleh, Mahdi, Navab, Nassir<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0483_paper.pdf)<br/>
**arXiv:** [2408.02043](https://arxiv.org/abs/2408.02043)<br/>

---

## Noise Removed Inconsistency Activation Map for Unsupervised Registration of Brain Tumor MRI between Pre-operative and Follow-up Phases<br/>
**Authors:** Wu, Chongwei, Zeng, Xiaoyu, Wang, Hao, Zhang, Xu, Fang, Wei, Li, Qiang, Wang, Zhiwei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1262_paper.pdf)<br/>

---

## MoME: Mixture of Multimodal Experts for Cancer Survival Prediction<br/>
**Authors:** Xiong, Conghao, Chen, Hao, Zheng, Hao, Wei, Dong, Zheng, Yefeng, Sung, Joseph J. Y., King, Irwin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2168_paper.pdf)<br/>

---

## [Medical Image Segmentation via Single-Source Domain Generalization with Random Amplitude Spectrum Synthesis](https://arxiv.org/abs/2409.04768)<br/>
**Authors:** Qiao, Qiang, Wang, Wenyu, Qu, Meixia, Su, Kun, Jiang, Bin, Guo, Qiang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/4012_paper.pdf)<br/>
**arXiv:** [2409.04768](https://arxiv.org/abs/2409.04768)<br/>

---

## Immune-guided AI for Reproducible Regions of Interest Selection in Multiplex Immunofluorescence Pathology Imaging<br/>
**Authors:** Gautam, Tanishq, Gonzalez, Karina P., Salvatierra, Maria E., Serrano, Alejandra, Chen, Pingjun, Pan, Xiaoxi, Shokrollahi, Yasin, Ranjbar, Sara, Rodriguez, Leticia, Team, Patient Mosaic, Solis-Soto, Luisa, Yuan, Yinyin, Castillo, Simon P.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3757_paper.pdf)<br/>

---

## SDCL: Students Discrepancy-Informed Correction Learning for Semi-supervised Medical Image Segmentation<br/>
**Authors:** Song, Bentao, Wang, Qingfeng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0821_paper.pdf)<br/>

---

## [Embracing Massive Medical Data](https://arxiv.org/abs/2407.04687)<br/>
**Authors:** Chou, Yu-Cheng, Zhou, Zongwei, Yuille, Alan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0065_paper.pdf)<br/>
**arXiv:** [2407.04687](https://arxiv.org/abs/2407.04687)<br/>

---

## [Lifelong Histopathology Whole Slide Image Retrieval via Distance Consistency Rehearsal](https://arxiv.org/abs/2407.08153)<br/>
**Authors:** Zhu, Xinyu, Jiang, Zhiguo, Wu, Kun, Shi, Jun, Zheng, Yushan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1854_paper.pdf)<br/>
**arXiv:** [2407.08153](https://arxiv.org/abs/2407.08153)<br/>

---

## Feature Fusion Based on Mutual-Cross-Attention Mechanism for EEG Emotion Recognition<br/>
**Authors:** Zhao, Yimin, Gu, Jin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1767_paper.pdf)<br/>

---

## Algebraic Sphere Surface Fitting for Accurate and Efficient Mesh Reconstruction from Cine CMR Images<br/>
**Authors:** He, Jin, Liu, Weizhou, Zhao, Shifeng, Tian, Yun, Wang, Shuo<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2017_paper.pdf)<br/>

---

## [Non-Adversarial Learning: Vector-Quantized Common Latent Space for Multi-Sequence MRI](https://arxiv.org/abs/2407.02911)<br/>
**Authors:** Han, Luyi, Tan, Tao, Zhang, Tianyu, Wang, Xin, Gao, Yuan, Lu, Chunyao, Liang, Xinglong, Dou, Haoran, Huang, Yunzhi, Mann, Ritse<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0936_paper.pdf)<br/>
**arXiv:** [2407.02911](https://arxiv.org/abs/2407.02911)<br/>

---

## [Patient-Specific Real-Time Segmentation in Trackerless Brain Ultrasound](https://arxiv.org/abs/2405.09959)<br/>
**Authors:** Dorent, Reuben, Torio, Erickson, Haouchine, Nazim, Galvin, Colin, Frisken, Sarah, Golby, Alexandra, Kapur, Tina, Wells III, William M.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1788_paper.pdf)<br/>
**arXiv:** [2405.09959](https://arxiv.org/abs/2405.09959)<br/>

---

## [Noise Level Adaptive Diffusion Model for Robust Reconstruction of Accelerated MRI](https://arxiv.org/abs/2403.05245)<br/>
**Authors:** Huang, Shoujin, Luo, Guanxiong, Wang, Xi, Chen, Ziran, Wang, Yuwan, Yang, Huaishui, Heng, Pheng-Ann, Zhang, Lingyan, Lyu, Mengye<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1511_paper.pdf)<br/>
**arXiv:** [2403.05245](https://arxiv.org/abs/2403.05245)<br/>

---

## Embryo Graphs: Predicting Human Embryo Viability from 3D Morphology<br/>
**Authors:** He, Chloe, Karpavičiūtė, Neringa, Hariharan, Rishabh, Jacques, Céline, Chambost, Jérôme, Malmsten, Jonas, Zaninovic, Nikica, Wouters, Koen, Fréour, Thomas, Hickman, Cristina, Vasconcelos, Francisco<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1468_paper.pdf)<br/>

---

## [One registration is worth two segmentations](https://arxiv.org/abs/2405.10879)<br/>
**Authors:** Huang, Shiqi, Xu, Tingfa, Shen, Ziyi, Saeed, Shaheer Ullah, Yan, Wen, Barratt, Dean C., Hu, Yipeng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1540_paper.pdf)<br/>
**arXiv:** [2405.10879](https://arxiv.org/abs/2405.10879)<br/>

---

## Dual-Modality Watershed Fusion Network for Thyroid Nodule Classification of Dual-View CEUS Video<br/>
**Authors:** Li, Rui, Ruan, Jingliang, Lu, Yao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2837_paper.pdf)<br/>

---

## [TeethDreamer: 3D Teeth Reconstruction from Five Intra-oral Photographs](https://arxiv.org/abs/2407.11419)<br/>
**Authors:** Xu, Chenfan, Liu, Zhentao, Liu, Yuan, Dou, Yulong, Wu, Jiamin, Wang, Jiepeng, Wang, Minjiao, Shen, Dinggang, Cui, Zhiming<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1038_paper.pdf)<br/>
**arXiv:** [2407.11419](https://arxiv.org/abs/2407.11419)<br/>

---

## MuGI: Multi-Granularity Interactions of Heterogeneous Biomedical Data for Survival Prediction<br/>
**Authors:** Long, Lifan, Cui, Jiaqi, Zeng, Pinxian, Li, Yilun, Liu, Yuanjun, Wang, Yan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1471_paper.pdf)<br/>

---

## F2TNet: FMRI to T1w MRI Knowledge Transfer Network for Brain Multi-phenotype Prediction<br/>
**Authors:** He, Zhibin, Li, Wuyang, Jiang, Yu, Peng, Zhihao, Wang, Pengyu, Li, Xiang, Liu, Tianming, Han, Junwei, Zhang, Tuo, Yuan, Yixuan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0615_paper.pdf)<br/>

---

## A Deep Learning Approach for Placing Magnetic Resonance Spectroscopy Voxels in Brain Tumors<br/>
**Authors:** Lee, Sangyoon, Branzoli, Francesca, Nguyen, Thanh, Andronesi, Ovidiu, Lin, Alexander, Liserre, Roberto, Melkus, Gerd, Chen, Clark, Marjańska, Małgorzata, Bolan, Patrick J.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1668_paper.pdf)<br/>

---

## No-New-Denoiser: A Critical Analysis of Diffusion Models for Medical Image Denoising<br/>
**Authors:** Pfaff, Laura, Wagner, Fabian, Vysotskaya, Nastassia, Thies, Mareike, Maul, Noah, Mei, Siyuan, Wuerfl, Tobias, Maier, Andreas<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2146_paper.pdf)<br/>

---

## In vivo deep learning estimation of diffusion coefficients of nanoparticles<br/>
**Authors:** Kirkegaard, Julius B., Kutuzov, Nikolay P., Netterstrøm, Rasmus, Darkner, Sune, Lauritzen, Martin, Lauze, François<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2899_paper.pdf)<br/>

---

## Can Crowdsourced Annotations Improve AI-based Congestion Scoring For Bedside Lung Ultrasound?<br/>
**Authors:** Asgari-Targhi, Ameneh, Ungi, Tamas, Jin, Mike, Harrison, Nicholas, Duggan, Nicole, Duhaime, Erik P., Goldsmith, Andrew, Kapur, Tina<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3582_paper.pdf)<br/>

---

## DPMNet: Dual-Path MLP-based Network for Aneurysm Image Segmentation<br/>
**Authors:** Wang, Shudong, Zhao, Xue, Zhang, Yulin, Zhao, Yawu, Zhao, Zhiyuan, Ding, Hengtao, Chen, Tianxing, Qiao, Sibo<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2829_paper.pdf)<br/>

---

## Analyzing Cross-Population Domain Shift in Chest X-Ray Image Classification and Mitigating the Gap with Deep Supervised Domain Adaptation<br/>
**Authors:** Musa, Aminu, Ibrahim Adamu, Mariya, Kakudi, Habeebah Adamu, Hernandez, Monica, Lawal, Yusuf<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0442_paper.pdf)<br/>

---

## [MedContext: Learning Contextual Cues for Efficient Volumetric Medical Segmentation](https://arxiv.org/abs/2402.17725)<br/>
**Authors:** Gani, Hanan, Naseer, Muzammal, Khan, Fahad, Khan, Salman<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/4230_paper.pdf)<br/>
**arXiv:** [2402.17725](https://arxiv.org/abs/2402.17725)<br/>

---

## GMM-CoRegNet: A Multimodal Groupwise Registration Framework Based on Gaussian Mixture Model<br/>
**Authors:** Li, Zhenyu, Yu, Fan, Lu, Jie, Qian, Zhen<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1178_paper.pdf)<br/>

---

## [Structural Attention: Rethinking Transformer for Unpaired Medical Image Synthesis](https://arxiv.org/abs/2406.18967)<br/>
**Authors:** Phan, Vu Minh Hieu, Xie, Yutong, Zhang, Bowen, Qi, Yuankai, Liao, Zhibin, Perperidis, Antonios, Phung, Son Lam, Verjans, Johan W., To, Minh-Son<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0456_paper.pdf)<br/>
**arXiv:** [2406.18967](https://arxiv.org/abs/2406.18967)<br/>

---

## PromptSmooth: Certifying Robustness of Medical Vision-Language Models via Prompt Learning<br/>
**Authors:** Hussein, Noor, Shamshad, Fahad, Naseer, Muzammal, Nandakumar, Karthik<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3451_paper.pdf)<br/>

---

## VolumeNeRF: CT Volume Reconstruction from a Single Projection View<br/>
**Authors:** Liu, Jiachen, Bai, Xiangzhi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3061_paper.pdf)<br/>

---

## [Anatomical Positional Embeddings](https://arxiv.org/abs/2409.10291)<br/>
**Authors:** Goncharov, Mikhail, Samokhin, Valentin, Soboleva, Eugenia, Sokolov, Roman, Shirokikh, Boris, Belyaev, Mikhail, Kurmukov, Anvar, Oseledets, Ivan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3539_paper.pdf)<br/>
**arXiv:** [2409.10291](https://arxiv.org/abs/2409.10291)<br/>

---

## Self-Paced Sample Selection for Barely-Supervised Medical Image Segmentation<br/>
**Authors:** Su, Junming, Shen, Zhiqiang, Cao, Peng, Yang, Jinzhu, Zaiane, Osmar R.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3156_paper.pdf)<br/>

---

## [PathoTune: Adapting Visual Foundation Model to Pathological Specialists](https://arxiv.org/abs/2403.16497)<br/>
**Authors:** Lu, Jiaxuan, Yan, Fang, Zhang, Xiaofan, Gao, Yue, Zhang, Shaoting<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1648_paper.pdf)<br/>
**arXiv:** [2403.16497](https://arxiv.org/abs/2403.16497)<br/>

---

## Self-Supervised Contrastive Graph Views for Learning Neuron-level Circuit Network<br/>
**Authors:** Li, Junchi, Wan, Guojia, Liao, Minghui, Liao, Fei, Du, Bo<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2059_paper.pdf)<br/>

---

## [Simultaneous Tri-Modal Medical Image Fusion and Super-Resolution using Conditional Diffusion Model](https://arxiv.org/abs/2404.17357)<br/>
**Authors:** Xu, Yushen, Li, Xiaosong, Jie, Yuchan, Tan, Haishu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3901_paper.pdf)<br/>
**arXiv:** [2404.17357](https://arxiv.org/abs/2404.17357)<br/>

---

## [Binary Noise for Binary Tasks: Masked Bernoulli Diffusion for Unsupervised Anomaly Detection](https://arxiv.org/abs/2403.11667)<br/>
**Authors:** Wolleb, Julia, Bieder, Florentin, Friedrich, Paul, Zhang, Peter, Durrer, Alicia, Cattin, Philippe C.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0424_paper.pdf)<br/>
**arXiv:** [2403.11667](https://arxiv.org/abs/2403.11667)<br/>

---

## [Biomechanics-informed Non-rigid Medical Image Registration and its Inverse Material Property Estimation with Linear and Nonlinear Elasticity](https://arxiv.org/abs/2407.03292)<br/>
**Authors:** Min, Zhe, Baum, Zachary M. C., Saeed, Shaheer Ullah, Emberton, Mark, Barratt, Dean C., Taylor, Zeike A., Hu, Yipeng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0208_paper.pdf)<br/>
**arXiv:** [2407.03292](https://arxiv.org/abs/2407.03292)<br/>

---

## [D-CoRP: Differentiable Connectivity Refinement for Functional Brain Networks](https://arxiv.org/abs/2405.18658)<br/>
**Authors:** Hu, Haoyu, Zhang, Hongrun, Li, Chao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2022_paper.pdf)<br/>
**arXiv:** [2405.18658](https://arxiv.org/abs/2405.18658)<br/>

---

## Implicit Representation Embraces Challenging Attributes of Pulmonary Airway Tree Structures<br/>
**Authors:** Zhang, Minghui, Zhang, Hanxiao, You, Xin, Yang, Guang-Zhong, Gu, Yun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0885_paper.pdf)<br/>

---

## URCDM: Ultra-Resolution Image Synthesis in Histopathology<br/>
**Authors:** Cechnicka, Sarah, Ball, James, Baugh, Matthew, Reynaud, Hadrien, Simmonds, Naomi, Smith, Andrew P.T., Horsfield, Catherine, Roufosse, Candice, Kainz, Bernhard<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0770_paper.pdf)<br/>

---

## [Generating Progressive Images from Pathological Transitions via Diffusion Model](https://arxiv.org/abs/2311.12316)<br/>
**Authors:** Liu, Zeyu, Zhang, Tianyi, He, Yufang, Zhang, Guanglei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2051_paper.pdf)<br/>
**arXiv:** [2311.12316](https://arxiv.org/abs/2311.12316)<br/>

---

## [Fundus2Video: Cross-Modal Angiography Video Generation from Static Fundus Photography with Clinical Knowledge Guidance](https://arxiv.org/abs/2408.15217)<br/>
**Authors:** Zhang, Weiyi, Huang, Siyu, Yang, Jiancheng, Chen, Ruoyu, Ge, Zongyuan, Zheng, Yingfeng, Shi, Danli, He, Mingguang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1347_paper.pdf)<br/>
**arXiv:** [2408.15217](https://arxiv.org/abs/2408.15217)<br/>

---

## BPaCo: Balanced Parametric Contrastive Learning for Long-tailed Medical Image Classification<br/>
**Authors:** Cai, Zhiyuan, Wei, Tianyunxi, Lin, Li, Chen, Hao, Tang, Xiaoying<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2020_paper.pdf)<br/>

---

## ccRCC Metastasis Prediction via Exploring High-Order Correlations on Multiple WSIs<br/>
**Authors:** Zhou, Huijian, Tian, Zhiqiang, Han, Xiangmin, Du, Shaoyi, Gao, Yue<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0727_paper.pdf)<br/>

---

## Open-Set Semi-Supervised Medical Image Classification with Learnable Prototypes and Outlier Filter<br/>
**Authors:** He, Along, Li, Tao, Zhao, Yitian, Zhao, Junyong, Fu, Huazhu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0244_paper.pdf)<br/>

---

## Polyp-Mamba: Polyp Segmentation with Visual Mamba<br/>
**Authors:** Xu, Zhongxing, Tang, Feilong, Chen, Zhe, Zhou, Zheng, Wu, Weishan, Yang, Yuyao, Liang, Yu, Jiang, Jiyu, Cai, Xuyue, Su, Jionglong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0697_paper.pdf)<br/>

---

## Cache-Driven Spatial Test-Time Adaptation for Cross-Modality Medical Image Segmentation<br/>
**Authors:** Li, Xiang, Fang, Huihui, Wang, Changmiao, Liu, Mingsi, Duan, Lixin, Xu, Yanwu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1458_paper.pdf)<br/>

---

## DTCA: Dual-Branch Transformer with Cross-Attention for EEG and Eye Movement Data Fusion<br/>
**Authors:** Zhang, Xiaoshan, Shi, Enze, Yu, Sigang, Zhang, Shu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1793_paper.pdf)<br/>

---

## MOST: Multi-Formation Soft Masking for Semi-Supervised Medical Image Segmentation<br/>
**Authors:** Liu, Xinyu, Chen, Zhen, Yuan, Yixuan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0906_paper.pdf)<br/>

---

## [Weakly Supervised Learning of Cortical Surface Reconstruction from Segmentations](https://arxiv.org/abs/2406.12650)<br/>
**Authors:** Ma, Qiang, Li, Liu, Robinson, Emma C., Kainz, Bernhard, Rueckert, Daniel<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1517_paper.pdf)<br/>
**arXiv:** [2406.12650](https://arxiv.org/abs/2406.12650)<br/>

---

## [Lost in Tracking: Uncertainty-guided Cardiac Cine MRI Segmentation at Right Ventricle Base](https://arxiv.org/abs/2410.03320)<br/>
**Authors:** Zhao, Yidong, Zhang, Yi, Simonetti, Orlando, Han, Yuchi, Tao, Qian<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2877_paper.pdf)<br/>
**arXiv:** [2410.03320](https://arxiv.org/abs/2410.03320)<br/>

---

## [Debiased Noise Editing on Foundation Models for Fair Medical Image Classification](https://arxiv.org/abs/2403.06104)<br/>
**Authors:** Jin, Ruinan, Deng, Wenlong, Chen, Minghui, Li, Xiaoxiao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2733_paper.pdf)<br/>
**arXiv:** [2403.06104](https://arxiv.org/abs/2403.06104)<br/>

---

## Overcoming Atlas Heterogeneity in Federated Learning for Cross-site Connectome-based Predictive Modeling<br/>
**Authors:** Liang, Qinghao, Adkinson, Brendan D., Jiang, Rongtao, Scheinost, Dustin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3324_paper.pdf)<br/>

---

## COVID19 to Pneumonia: Multi Region Lung Severity Classification using CNN Transformer Position-Aware Feature Encoding Network<br/>
**Authors:** Lee, Jong Bub, Kim, Jung Soo, Lee, Hyun Gyu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1495_paper.pdf)<br/>

---

## TE-SSL: Time and Event-aware Self Supervised Learning for Alzheimer’s Disease Progression Analysis<br/>
**Authors:** Thrasher, Jacob, Devkota, Alina, Tafti, Ahmad P., Bhattarai, Binod, Gyawali, Prashnna, the Alzheimer’s Disease Neuroimaging Initiative<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3866_paper.pdf)<br/>

---

## S-SYNTH: Knowledge-Based, Synthetic Generation of Skin Images<br/>
**Authors:** Kim, Andrea, Saharkhiz, Niloufar, Sizikova, Elena, Lago, Miguel, Sahiner, Berkman, Delfino, Jana, Badano, Aldo<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1426_paper.pdf)<br/>

---

## Region-Specific Retrieval Augmentation for Longitudinal Visual Question Answering: A Mix-and-Match Paradigm<br/>
**Authors:** Yung, Ka-Wai, Sivaraj, Jayaram, Stoyanov, Danail, Loukogeorgakis, Stavros, Mazomenos, Evangelos B.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2219_paper.pdf)<br/>

---

## FM-ABS: Promptable Foundation Model Drives Active Barely Supervised Learning for 3D Medical Image Segmentation<br/>
**Authors:** Xu, Zhe, Chen, Cheng, Lu, Donghuan, Sun, Jinghan, Wei, Dong, Zheng, Yefeng, Li, Quanzheng, Tong, Raymond Kai-yu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0050_paper.pdf)<br/>

---

## FM-OSD: Foundation Model-Enabled One-Shot Detection of Anatomical Landmarks<br/>
**Authors:** Miao, Juzheng, Chen, Cheng, Zhang, Keli, Chuai, Jie, Li, Quanzheng, Heng, Pheng-Ann<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0320_paper.pdf)<br/>

---

## Adaptive Subtype and Stage Inference for Alzheimer’s Disease<br/>
**Authors:** Wang, Xinkai, Shi, Yonggang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3688_paper.pdf)<br/>

---

## [Learning 3D Gaussians for Extremely Sparse-View Cone-Beam CT Reconstruction](https://arxiv.org/abs/2407.01090)<br/>
**Authors:** Lin, Yiqun, Wang, Hualiang, Chen, Jixiang, Li, Xiaomeng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0250_paper.pdf)<br/>
**arXiv:** [2407.01090](https://arxiv.org/abs/2407.01090)<br/>

---

## PG-MLIF: Multimodal Low-rank Interaction Fusion Framework Integrating Pathological Images and Genomic Data for Cancer Prognosis Prediction<br/>
**Authors:** Pan, Xipeng, An, Yajun, Lan, Rushi, Liu, Zhenbing, Liu, Zaiyi, Lu, Cheng, Yang, Huihua<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1221_paper.pdf)<br/>

---

## Pair Shuffle Consistency for Semi-supervised Medical Image Segmentation<br/>
**Authors:** He, Jianjun, Cai, Chenyu, Li, Qiong, Ma, Andy J<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0942_paper.pdf)<br/>

---

## MiHATP:A Multi-Hybrid Attention Super-Resolution Network for Pathological Image Based on Transformation Pool Contrastive Learning<br/>
**Authors:** Xu, Zhufeng, Qin, Jiaxin, Li, Chenhao, Bu, Dechao, Zhao, Yi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1260_paper.pdf)<br/>

---

## [Estimating Neural Orientation Distribution Fields on High Resolution Diffusion MRI Scans](https://arxiv.org/abs/2409.09387)<br/>
**Authors:** Dwedari, Mohammed Munzer, Consagra, William, Müller, Philip, Turgut, Özgün, Rueckert, Daniel, Rathi, Yogesh<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2292_paper.pdf)<br/>
**arXiv:** [2409.09387](https://arxiv.org/abs/2409.09387)<br/>

---

## Weak-supervised Attention Fusion Network for Carotid Artery Vessel Wall Segmentation<br/>
**Authors:** Lei, Haijun, Tong, Guanjiie, Su, Huaqiang, Lei, Baiying<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1398_paper.pdf)<br/>

---

## Generating Anatomically Accurate Heart Structures via Neural Implicit Fields<br/>
**Authors:** Yang, Jiancheng, Sedykh, Ekaterina, Adhinarta, Jason Ken, Le, Hieu, Fua, Pascal<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0411_paper.pdf)<br/>

---

## ASPS: Augmented Segment Anything Model for Polyp Segmentation<br/>
**Authors:** Li, Huiqian, Zhang, Dingwen, Yao, Jieru, Han, Longfei, Li, Zhongyu, Han, Junwei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/4128_paper.pdf)<br/>

---

## Learning to Segment Multiple Organs from Multimodal Partially Labeled Datasets<br/>
**Authors:** Liu, Hong, Wei, Dong, Lu, Donghuan, Sun, Jinghan, Zheng, Hao, Zheng, Yefeng, Wang, Liansheng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1759_paper.pdf)<br/>

---

## A New Perspective to Boost Performance Fairness For Medical Federated Learning<br/>
**Authors:** Yan, Yunlu, Zhu, Lei, Li, Yuexiang, Xu, Xinxing, Goh, Rick Siow Mong, Liu, Yong, Khan, Salman, Feng, Chun-Mei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1953_paper.pdf)<br/>

---

## Subgroup-Specific Risk-Controlled Dose Estimation in Radiotherapy<br/>
**Authors:** Fischer, Paul, Willms, Hannah, Schneider, Moritz, Thorwarth, Daniela, Muehlebach, Michael, Baumgartner, Christian F.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0603_paper.pdf)<br/>

---

## [Neural Cellular Automata for Lightweight, Robust and Explainable Classification of White Blood Cell Images](https://arxiv.org/abs/2404.05584)<br/>
**Authors:** Deutges, Michael, Sadafi, Ario, Navab, Nassir, Marr, Carsten<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3422_paper.pdf)<br/>
**arXiv:** [2404.05584](https://arxiv.org/abs/2404.05584)<br/>

---

## M2Fusion: Multi-time Multimodal Fusion for Prediction of Pathological Complete Response in Breast Cancer<br/>
**Authors:** Zhang, Song, Du, Siyao, Sun, Caixia, Li, Bao, Shao, Lizhi, Zhang, Lina, Wang, Kun, Liu, Zhenyu, Tian, Jie<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0979_paper.pdf)<br/>

---

## AMONuSeg: A Histological Dataset for African Multi-Organ Nuclei Semantic Segmentation<br/>
**Authors:** Zerouaoui, Hasnae, Oderinde, Gbenga Peter, Lefdali, Rida, Echihabi, Karima, Akpulu, Stephen Peter, Agbon, Nosereme Abel, Musa, Abraham Sunday, Yeganeh, Yousef, Farshad, Azade, Navab, Nassir<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2801_paper.pdf)<br/>

---

## Common Vision-Language Attention for Text-Guided Medical Image Segmentation of Pneumonia<br/>
**Authors:** Guo, Yunpeng, Zeng, Xinyi, Zeng, Pinxian, Fei, Yuchen, Wen, Lu, Zhou, Jiliu, Wang, Yan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2599_paper.pdf)<br/>

---

## [HistGen: Histopathology Report Generation via Local-Global Feature Encoding and Cross-modal Context Interaction](https://arxiv.org/abs/2403.05396)<br/>
**Authors:** Guo, Zhengrui, Ma, Jiabo, Xu, Yingxue, Wang, Yihui, Wang, Liansheng, Chen, Hao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0796_paper.pdf)<br/>
**arXiv:** [2403.05396](https://arxiv.org/abs/2403.05396)<br/>

---

## [Incorporating Clinical Guidelines through Adapting Multi-modal Large Language Model for Prostate Cancer PI-RADS Scoring](https://arxiv.org/abs/2405.08786)<br/>
**Authors:** Zhang, Tiantian, Lin, Manxi, Guo, Hongda, Zhang, Xiaofan, Chiu, Ka Fung Peter, Feragen, Aasa, Dou, Qi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2830_paper.pdf)<br/>
**arXiv:** [2405.08786](https://arxiv.org/abs/2405.08786)<br/>

---

## [Diffusion-based Generative Image Outpainting for Recovery of FOV-Truncated CT Images](https://arxiv.org/abs/2406.04769)<br/>
**Authors:** Liman, Michelle Espranita, Rueckert, Daniel, Fintelmann, Florian J., Müller, Philip<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0872_paper.pdf)<br/>
**arXiv:** [2406.04769](https://arxiv.org/abs/2406.04769)<br/>

---

## Multi-stage Multi-granularity Focus-tuned Learning Paradigm for Medical HSI Segmentation<br/>
**Authors:** Dong, Haichuan, Zhou, Runjie, Yun, Boxiang, Zhou, Huihui, Zhang, Benyan, Li, Qingli, Wang, Yan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0621_paper.pdf)<br/>

---

## Swin SMT: Global Sequential Modeling for Enhancing 3D Medical Image Segmentation<br/>
**Authors:** Płotka, Szymon, Chrabaszcz, Maciej, Biecek, Przemyslaw<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0415_paper.pdf)<br/>

---

## Spatio-temporal Contrast Network for Data-efficient Learning of Coronary Artery Disease in Coronary CT Angiography<br/>
**Authors:** Ma, Xinghua, Zou, Mingye, Fang, Xinyan, Liu, Yang, Luo, Gongning, Wang, Wei, Wang, Kuanquan, Qiu, Zhaowen, Gao, Xin, Li, Shuo<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0006_paper.pdf)<br/>

---

## IarCAC: Instance-aware Representation for Coronary Artery Calcification Segmentation in Cardiac CT angiography<br/>
**Authors:** Jiang, Weili, Li, Yiming, Yi, Zhang, Wang, Jianyong, Chen, Mao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2701_paper.pdf)<br/>

---

## [NODER: Image Sequence Regression Based on Neural Ordinary Differential Equations](https://arxiv.org/abs/2407.13241)<br/>
**Authors:** Bai, Hao, Hong, Yi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1899_paper.pdf)<br/>
**arXiv:** [2407.13241](https://arxiv.org/abs/2407.13241)<br/>

---

## Assessing Risk of Stealing Proprietary Models for Medical Imaging Tasks<br/>
**Authors:** Raj, Ankita, Swaika, Harsh, Varma, Deepankar, Arora, Chetan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2993_paper.pdf)<br/>

---

## PASSION for Dermatology: Bridging the Diversity Gap with Pigmented Skin Images from Sub-Saharan Africa<br/>
**Authors:** Gottfrois, Philippe, Gröger, Fabian, Andriambololoniaina, Faly Herizo, Amruthalingam, Ludovic, Gonzalez-Jimenez, Alvaro, Hsu, Christophe, Kessy, Agnes, Lionetti, Simone, Mavura, Daudi, Ng’ambi, Wingston, Ngongonda, Dingase Faith, Pouly, Marc, Rakotoarisaona, Mendrika Fifaliana, Rapelanoro Rabenja, Fahafahantsoa, Traoré, Ibrahima, Navarini, Alexander A.<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3722_paper.pdf)<br/>

---

## Quest for Clone: Test-time Domain Adaptation for Medical Image Segmentation by Searching the Closest Clone in Latent Space<br/>
**Authors:** Basak, Hritam, Yin, Zhaozheng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0297_paper.pdf)<br/>

---

## Enhancing Whole Slide Image Classification with Discriminative and Contrastive Learning<br/>
**Authors:** Liang, Peixian, Zheng, Hao, Li, Hongming, Gong, Yuxin, Bakas, Spyridon, Fan, Yong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1644_paper.pdf)<br/>

---

## [Gait Patterns as Biomarkers: A Video-Based Approach for Classifying Scoliosis](https://arxiv.org/abs/2407.05726)<br/>
**Authors:** Zhou, Zirui, Liang, Junhao, Peng, Zizhao, Fan, Chao, An, Fengwei, Yu, Shiqi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1763_paper.pdf)<br/>
**arXiv:** [2407.05726](https://arxiv.org/abs/2407.05726)<br/>

---

## [Position-Guided Prompt Learning for Anomaly Detection in Chest X-Rays](https://arxiv.org/abs/2405.11976)<br/>
**Authors:** Sun, Zhichao, Gu, Yuliang, Liu, Yepeng, Zhang, Zerui, Zhao, Zhou, Xu, Yongchao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0578_paper.pdf)<br/>
**arXiv:** [2405.11976](https://arxiv.org/abs/2405.11976)<br/>

---

## [Region Attention Transformer for Medical Image Restoration](https://arxiv.org/abs/2407.09268)<br/>
**Authors:** Yang, Zhiwen, Chen, Haowei, Qian, Ziniu, Zhou, Yang, Zhang, Hui, Zhao, Dan, Wei, Bingzheng, Xu, Yan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0515_paper.pdf)<br/>
**arXiv:** [2407.09268](https://arxiv.org/abs/2407.09268)<br/>

---

## From Static to Dynamic Diagnostics: Boosting Medical Image Analysis via Motion-Informed Generative Videos<br/>
**Authors:** Li, Wuyang, Liu, Xinyu, Yang, Qiushi, Yuan, Yixuan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0931_paper.pdf)<br/>

---

## [FedMRL: Data Heterogeneity Aware Federated Multi-agent Deep Reinforcement Learning for Medical Imaging](https://arxiv.org/abs/2407.05800)<br/>
**Authors:** Sahoo, Pranab, Tripathi, Ashutosh, Saha, Sriparna, Mondal, Samrat<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2368_paper.pdf)<br/>
**arXiv:** [2407.05800](https://arxiv.org/abs/2407.05800)<br/>

---

## ThyGraph: A Graph-Based Approach for Thyroid Nodule Diagnosis from Ultrasound Studies<br/>
**Authors:** Radhachandran, Ashwath, Vittalam, Alekhya, Ivezic, Vedrana, Sant, Vivek, Athreya, Shreeram, Moleta, Chace, Patel, Maitraya, Masamed, Rinat, Arnold, Corey, Speier, William<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3759_paper.pdf)<br/>

---

## [Generalizing to Unseen Domains in Diabetic Retinopathy with Disentangled Representations](https://huggingface.co/papers/2406.06384)<br/>
**Authors:** Xia, Peng, Hu, Ming, Tang, Feilong, Li, Wenxue, Zheng, Wenhao, Ju, Lie, Duan, Peibo, Yao, Huaxiu, Ge, Zongyuan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0781_paper.pdf)<br/>
**arXiv:** [2406.06384](https://arxiv.org/abs/2406.06384)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2406.06384](https://huggingface.co/papers/2406.06384)<br/>

---

## On predicting 3D bone locations inside the human body<br/>
**Authors:** Dakri, Abdelmouttaleb, Arora, Vaibhav, Challier, Léo, Keller, Marilyn, Black, Michael J., Pujades, Sergi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0588_paper.pdf)<br/>

---

## [DB-SAM: Delving into High Quality Universal Medical Image Segmentation](https://arxiv.org/abs/2410.04172)<br/>
**Authors:** Qin, Chao, Cao, Jiale, Fu, Huazhu, Shahbaz Khan, Fahad, Anwer, Rao Muhammad<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1489_paper.pdf)<br/>
**arXiv:** [2410.04172](https://arxiv.org/abs/2410.04172)<br/>

---

## Trans-Window Panoramic Impasto for Online Tissue Deformation Recovery<br/>
**Authors:** Chen, Jiahe, Kobayashi, Etsuko, Sakuma, Ichiro, Tomii, Naoki<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/4075_paper.pdf)<br/>

---

## [When 3D Partial Points Meets SAM: Tooth Point Cloud Segmentation with Sparse Labels](https://arxiv.org/abs/2409.01691)<br/>
**Authors:** Liu, Yifan, Li, Wuyang, Wang, Cheng, Chen, Hui, Yuan, Yixuan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0843_paper.pdf)<br/>
**arXiv:** [2409.01691](https://arxiv.org/abs/2409.01691)<br/>

---

## Semi-supervised Tubular Structure Segmentation with Cross Geometry and Hausdorff Distance Consistency<br/>
**Authors:** Zhu, Ruiyun, Oda, Masahiro, Hayashi, Yuichiro, Kitasaka, Takayuki, Mori, Kensaku<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0651_paper.pdf)<br/>

---

## [LoCI-DiffCom: Longitudinal Consistency-Informed Diffusion Model for 3D Infant Brain Image Completion](https://arxiv.org/abs/2405.10691)<br/>
**Authors:** Zhu, Zihao, Tao, Tianli, Tao, Yitian, Deng, Haowen, Cai, Xinyi, Wu, Gaofeng, Wang, Kaidong, Tang, Haifeng, Zhu, Lixuan, Gu, Zhuoyang, Shen, Dinggang, Zhang, Han<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1964_paper.pdf)<br/>
**arXiv:** [2405.10691](https://arxiv.org/abs/2405.10691)<br/>

---

## [Unsupervised Training of Neural Cellular Automata on Edge Devices](https://arxiv.org/abs/2407.18114)<br/>
**Authors:** Kalkhof, John, Ranem, Amin, Mukhopadhyay, Anirban<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1060_paper.pdf)<br/>
**arXiv:** [2407.18114](https://arxiv.org/abs/2407.18114)<br/>

---

## [SimTxtSeg: Weakly-Supervised Medical Image Segmentation with Simple Text Cues](https://arxiv.org/abs/2406.19364)<br/>
**Authors:** Xie, Yuxin, Zhou, Tao, Zhou, Yi, Chen, Geng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0802_paper.pdf)<br/>
**arXiv:** [2406.19364](https://arxiv.org/abs/2406.19364)<br/>

---

## Progressively Correcting Soft Labels via Teacher Team for Knowledge Distillation in Medical Image Segmentation<br/>
**Authors:** Wang, Yaqi, Cao, Peng, Hou, Qingshan, Lan, Linqi, Yang, Jinzhu, Liu, Xiaoli, Zaiane, Osmar R.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2751_paper.pdf)<br/>

---

## Uncertainty-aware Diffusion-based Adversarial Attack for Realistic Colonoscopy Image Synthesis<br/>
**Authors:** Jeong, Minjae, Cho, Hyuna, Jung, Sungyoon, Kim, Won Hwa<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2811_paper.pdf)<br/>

---

## Spatial Context Awareness in Surgery through Sound Source Localization<br/>
**Authors:** Seibold, Matthias, Bahari Malayeri, Ali, Fürnstahl, Philipp<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0236_paper.pdf)<br/>

---

## [Perspective+ Unet: Enhancing Segmentation with Bi-Path Fusion and Efficient Non-Local Attention for Superior Receptive Fields](https://arxiv.org/abs/2406.14052)<br/>
**Authors:** Hu, Jintong, Chen, Siyan, Pan, Zhiyi, Zeng, Sen, Yang, Wenming<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3008_paper.pdf)<br/>
**arXiv:** [2406.14052](https://arxiv.org/abs/2406.14052)<br/>

---

## HDilemma: Are Open-Source Hausdorff Distance Implementations Equivalent?<br/>
**Authors:** Podobnik, Gašper, Vrtovec, Tomaž<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2469_paper.pdf)<br/>

---

## FALFormer: Feature-aware Landmarks self-attention for Whole-slide Image Classification<br/>
**Authors:** Bui, Doanh C., Vuong, Trinh Thi Le, Kwak, Jin Tae<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2447_paper.pdf)<br/>

---

## [Beyond Adapting SAM: Towards End-to-End Ultrasound Image Segmentation via Auto Prompting](https://arxiv.org/abs/2309.06824)<br/>
**Authors:** Lin, Xian, Xiang, Yangyang, Yu, Li, Yan, Zengqiang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1336_paper.pdf)<br/>
**arXiv:** [2309.06824](https://arxiv.org/abs/2309.06824)<br/>

---

## [RadiomicsFill-Mammo: Synthetic Mammogram Mass Manipulation with Radiomics Features](https://arxiv.org/abs/2407.05683)<br/>
**Authors:** Na, Inye, Kim, Jonghun, Ko, Eun Sook, Park, Hyunjin<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1807_paper.pdf)<br/>
**arXiv:** [2407.05683](https://arxiv.org/abs/2407.05683)<br/>

---

## MedSynth: Leveraging Generative Model for Healthcare Data Sharing<br/>
**Authors:** Kanagavelu, Renuga, Walia, Madhav, Wang, Yuan, Fu, Huazhu, Wei, Qingsong, Liu, Yong, Goh, Rick Siow Mong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2872_paper.pdf)<br/>

---

## HiA: Towards Chinese Multimodal LLMs for Comparative High-Resolution Joint Diagnosis<br/>
**Authors:** Ding, Xinpeng, Chu, Yongqiang, Pi, Renjie, Wang, Hualiang, Li, Xiaomeng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1207_paper.pdf)<br/>

---

## [Simulation-Based Segmentation of Blood Vessels in Cerebral 3D OCTA Images](https://huggingface.co/papers/2403.07116)<br/>
**Authors:** Wittmann, Bastian, Glandorf, Lukas, Paetzold, Johannes C., Amiranashvili, Tamaz, Wälchli, Thomas, Razansky, Daniel, Menze, Bjoern<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1494_paper.pdf)<br/>
**arXiv:** [2403.07116](https://arxiv.org/abs/2403.07116)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2403.07116](https://huggingface.co/papers/2403.07116)<br/>
**🤗 Datasets:** [bwittmann/syn-cerebral-octa-seg](https://huggingface.co/datasets/bwittmann/syn-cerebral-octa-seg)<br/>

---

## Confidence-guided Semi-supervised Learning for Generalized Lesion Localization in X-ray Images<br/>
**Authors:** Das, Abhijit, Gorade, Vandan, Kumar, Komal, Chakraborty, Snehashis, Mahapatra, Dwarikanath, Roy, Sudipta<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3485_paper.pdf)<br/>

---

## [3DGR-CAR: Coronary artery reconstruction from ultra-sparse 2D X-ray views with a 3D Gaussians representation](https://arxiv.org/abs/2410.00404)<br/>
**Authors:** Fu, Xueming, Li, Yingtai, Tang, Fenghe, Li, Jun, Zhao, Mingyue, Teng, Gao-Jun, Zhou, S. Kevin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1015_paper.pdf)<br/>
**arXiv:** [2410.00404](https://arxiv.org/abs/2410.00404)<br/>

---

## Glioblastoma segmentation from early post-operative MRI: challenges and clinical impact<br/>
**Authors:** Holden Helland, Ragnhild, Bouget, David, Eijgelaar, Roelant S., De Witt Hamer, Philip C., Barkhof, Frederik, Solheim, Ole, Reinertsen, Ingerid<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3387_paper.pdf)<br/>

---

## [EchoNet-Synthetic: Privacy-preserving Video Generation for Safe Medical Data Sharing](https://arxiv.org/abs/2406.00808)<br/>
**Authors:** Reynaud, Hadrien, Meng, Qingjie, Dombrowski, Mischa, Ghosh, Arijit, Day, Thomas, Gomez, Alberto, Leeson, Paul, Kainz, Bernhard<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0158_paper.pdf)<br/>
**arXiv:** [2406.00808](https://arxiv.org/abs/2406.00808)<br/>

---

## Consecutive-Contrastive Spherical U-net: Enhancing Reliability of Individualized Functional Brain Parcellation for Short-duration fMRI Scans<br/>
**Authors:** Hu, Dan, Han, Kangfu, Cheng, Jiale, Li, Gang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3653_paper.pdf)<br/>

---

## Multi-scale Region-aware Implicit Neural Network for Medical Images Matting<br/>
**Authors:** Xu, Yanyu, Xia, Yingzhi, Fu, Huazhu, Goh, Rick Siow Mong, Liu, Yong, Xu, Xinxing<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1619_paper.pdf)<br/>

---

## EchoMEN: Combating Data Imbalance in Ejection Fraction Regression via Multi-Expert Network<br/>
**Authors:** Lai, Song, Zhao, Mingyang, Zhao, Zhe, Chang, Shi, Yuan, Xiaohua, Liu, Hongbin, Zhang, Qingfu, Meng, Gaofeng<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1328_paper.pdf)<br/>

---

## [SCMIL: Sparse Context-aware Multiple Instance Learning for Predicting Cancer Survival Probability Distribution in Whole Slide Images](https://arxiv.org/abs/2407.00664)<br/>
**Authors:** Yang, Zekang, Liu, Hong, Wang, Xiangdong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2991_paper.pdf)<br/>
**arXiv:** [2407.00664](https://arxiv.org/abs/2407.00664)<br/>

---

## Coarse-Grained Mask Regularization for Microvascular Obstruction Identification from non-contrast Cardiac Magnetic Resonance<br/>
**Authors:** Yan, Yige, Cheng, Jun, Yang, Xulei, Gu, Zaiwang, Leng, Shuang, Tan, Ru San, Zhong, Liang, Rajapakse, Jagath C.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0670_paper.pdf)<br/>

---

## [MBA-Net: SAM-driven Bidirectional Aggregation Network for Ovarian Tumor Segmentation](https://arxiv.org/abs/2407.05984)<br/>
**Authors:** Gao, Yifan, Xia, Wei, Wang, Wenkui, Gao, Xin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1538_paper.pdf)<br/>
**arXiv:** [2407.05984](https://arxiv.org/abs/2407.05984)<br/>

---

## PathMamba: Weakly Supervised State Space Model for Multi-class Segmentation of Pathology Images<br/>
**Authors:** Fan, Jiansong, Lv, Tianxu, Di, Yicheng, Li, Lihua, Pan, Xiang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1354_paper.pdf)<br/>

---

## Double-tier Attention based Multi-label Learning Network for Predicting Biomarkers from Whole Slide Images of Breast Cancer<br/>
**Authors:** Wang, Mingkang, Wang, Tong, Cong, Fengyu, Lu, Cheng, Xu, Hongming<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3214_paper.pdf)<br/>

---

## [On Instabilities of Unsupervised Denoising Diffusion Models in Magnetic Resonance Imaging Reconstruction](https://arxiv.org/abs/2406.16983)<br/>
**Authors:** Han, Tianyu, Nebelung, Sven, Khader, Firas, Kather, Jakob Nikolas, Truhn, Daniel<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1977_paper.pdf)<br/>
**arXiv:** [2406.16983](https://arxiv.org/abs/2406.16983)<br/>

---

## [BAPLe: Backdoor Attacks on Medical Foundational Models using Prompt Learning](https://arxiv.org/abs/2408.07440)<br/>
**Authors:** Hanif, Asif, Shamshad, Fahad, Awais, Muhammad, Naseer, Muzammal, Shahbaz Khan, Fahad, Nandakumar, Karthik, Khan, Salman, Anwer, Rao Muhammad<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3117_paper.pdf)<br/>
**arXiv:** [2408.07440](https://arxiv.org/abs/2408.07440)<br/>

---

## FastSAM3D: An Efficient Segment Anything Model for 3D Volumetric Medical Images<br/>
**Authors:** Shen, Yiqing, Li, Jingxing, Shao, Xinyuan, Inigo Romillo, Blanca, Jindal, Ankush, Dreizin, David, Unberath, Mathias<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2456_paper.pdf)<br/>

---

## RDD-Net: Randomized Joint Data-Feature Augmentation and Deep-Shallow Feature Fusion Networks for Automated Diagnosis of Glaucoma<br/>
**Authors:** Tang, Yilin, Zhang, Min, Feng, Jun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3922_paper.pdf)<br/>

---

## [Multimodal Variational Autoencoder for Low-cost Cardiac Hemodynamics Instability Detection](https://arxiv.org/abs/2403.13658)<br/>
**Authors:** Suvon, Mohammod N. I., Tripathi, Prasun C., Fan, Wenrui, Zhou, Shuo, Liu, Xianyuan, Alabed, Samer, Osmani, Venet, Swift, Andrew J., Chen, Chen, Lu, Haiping<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1503_paper.pdf)<br/>
**arXiv:** [2403.13658](https://arxiv.org/abs/2403.13658)<br/>

---

## MAdapter: A Better Interaction between Image and Language for Medical Image Segmentation<br/>
**Authors:** Zhang, Xu, Ni, Bo, Yang, Yang, Zhang, Lefei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2097_paper.pdf)<br/>

---

## Deep Volume Reconstruction from Multi-focus Microscopic Images<br/>
**Authors:** Azevedo, Caio, Santra, Sanchayan, Kumawat, Sudhakar, Nagahara, Hajime, Morooka, Ken'ichi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0551_paper.pdf)<br/>

---

## Online learning in motion modeling for intra-interventional image sequences<br/>
**Authors:** Gunnarsson, Niklas, Sjölund, Jens, Kimstrand, Peter, Schön, Thomas B.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1838_paper.pdf)<br/>

---

## [Unsupervised Latent Stain Adaptation for Computational Pathology](https://arxiv.org/abs/2406.19081)<br/>
**Authors:** Reisenbüchler, Daniel, Luttner, Lucas, Schaadt, Nadine S., Feuerhake, Friedrich, Merhof, Dorit<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2012_paper.pdf)<br/>
**arXiv:** [2406.19081](https://arxiv.org/abs/2406.19081)<br/>

---

## Disease-informed Adaptation of Vision-Language Models<br/>
**Authors:** Zhang, Jiajin, Wang, Ge, Kalra, Mannudeep K., Yan, Pingkun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0383_paper.pdf)<br/>

---

## [Cross Prompting Consistency with Segment Anything Model for Semi-supervised Medical Image Segmentation](https://arxiv.org/abs/2407.05416)<br/>
**Authors:** Miao, Juzheng, Chen, Cheng, Zhang, Keli, Chuai, Jie, Li, Quanzheng, Heng, Pheng-Ann<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0321_paper.pdf)<br/>
**arXiv:** [2407.05416](https://arxiv.org/abs/2407.05416)<br/>

---

## An MR-Compatible Virtual Reality System for Assessing Neuronal Plasticity of Sensorimotor Neurons and Mirror Neurons<br/>
**Authors:** Wang, Xiaocheng, Mekbib, D. B., Zhou, Tian, Zhu, Junming, Zhang, Li, Cheng, Ruidong, Zhang, Jianmin, Ye, Xiangming, Xu, Dongrong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3035_paper.pdf)<br/>

---

## [3D Vessel Graph Generation Using Denoising Diffusion](https://arxiv.org/abs/2407.05842)<br/>
**Authors:** Prabhakar, Chinmay, Shit, Suprosanna, Musio, Fabio, Yang, Kaiyuan, Amiranashvili, Tamaz, Paetzold, Johannes C., Li, Hongwei Bran, Menze, Bjoern<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1908_paper.pdf)<br/>
**arXiv:** [2407.05842](https://arxiv.org/abs/2407.05842)<br/>

---

## [EgoSurgery-Phase: A Dataset of Surgical Phase Recognition from Egocentric Open Surgery Videos](https://arxiv.org/abs/2405.19644)<br/>
**Authors:** Fujii, Ryo, Hatano, Masashi, Saito, Hideo, Kajita, Hiroki<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0627_paper.pdf)<br/>
**arXiv:** [2405.19644](https://arxiv.org/abs/2405.19644)<br/>

---

## [A Foundation Model for Brain Lesion Segmentation with Mixture of Modality Experts](https://arxiv.org/abs/2405.10246)<br/>
**Authors:** Zhang, Xinru, Ou, Ni, Basaran, Berke Doga, Visentin, Marco, Qiao, Mengyun, Gu, Renyang, Ouyang, Cheng, Liu, Yaou, Matthews, Paul M., Ye, Chuyang, Bai, Wenjia<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0143_paper.pdf)<br/>
**arXiv:** [2405.10246](https://arxiv.org/abs/2405.10246)<br/>

---

## Multimodal Learning for Embryo Viability Prediction in Clinical IVF<br/>
**Authors:** Kim, Junsik, Shi, Zhiyi, Jeong, Davin, Knittel, Johannes, Yang, Helen Y., Song, Yonghyun, Li, Wanhua, Li, Yicong, Ben-Yosef, Dalit, Needleman, Daniel, Pfister, Hanspeter<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2517_paper.pdf)<br/>

---

## Airway segmentation based on topological structure enhancement using multi-task learning<br/>
**Authors:** Yang, Xuan, Chen, Lingyu, Zheng, Yuchao, Ma, Longfei, Chen, Fang, Ning, Guochen, Liao, Hongen<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3005_paper.pdf)<br/>

---

## [MM-Retinal: Knowledge-Enhanced Foundational Pretraining with Fundus Image-Text Expertise](https://arxiv.org/abs/2405.11793)<br/>
**Authors:** Wu, Ruiqi, Zhang, Chenran, Zhang, Jianle, Zhou, Yi, Zhou, Tao, Fu, Huazhu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0375_paper.pdf)<br/>
**arXiv:** [2405.11793](https://arxiv.org/abs/2405.11793)<br/>

---

## A New Non-Invasive AI-Based Diagnostic System for Automated Diagnosis of Acute Renal Rejection in Kidney Transplantation: Analysis of ADC Maps Extracted from Matched 3D Iso-Regions of the Transplanted Kidney<br/>
**Authors:** Abdelhalim, Ibrahim, Abou El-Ghar, Mohamed, Dwyer, Amy, Ouseph, Rosemary, Contractor, Sohail, El-Baz, Ayman<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3658_paper.pdf)<br/>

---

## SiFT: A Serial Framework with Textual Guidance for Federated Learning<br/>
**Authors:** Li, Xuyang, Zhang, Weizhuo, Yu, Yue, Zheng, Wei-Shi, Zhang, Tong, Wang, Ruixuan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2156_paper.pdf)<br/>

---

## Label merge-and-split: A graph-colouring approach for memory-efficient brain parcellation<br/>
**Authors:** Kujawa, Aaron, Dorent, Reuben, Ourselin, Sebastien, Vercauteren, Tom<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2217_paper.pdf)<br/>

---

## XTranPrune: eXplainability-aware Transformer Pruning for Bias Mitigation in Dermatological Disease Classification<br/>
**Authors:** Ghadiri, Ali, Pagnucco, Maurice, Song, Yang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1201_paper.pdf)<br/>

---

## [Curriculum Prompting Foundation Models for Medical Image Segmentation](https://arxiv.org/abs/2409.00695)<br/>
**Authors:** Zheng, Xiuqi, Zhang, Yuhang, Zhang, Haoran, Liang, Hongrui, Bao, Xueqi, Jiang, Zhuqing, Lao, Qicheng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2832_paper.pdf)<br/>
**arXiv:** [2409.00695](https://arxiv.org/abs/2409.00695)<br/>

---

## Hemodynamic-Driven Multi-Prototypes Learning for One-Shot Segmentation in Breast Cancer DCE-MRI<br/>
**Authors:** Pan, Xiang, Nie, Shiyun, Lv, Tianxu, Li, Lihua<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1682_paper.pdf)<br/>

---

## Learning Temporally Equivariance for Degenerative Disease Progression in OCT by Predicting Future Representations<br/>
**Authors:** Emre, Taha, Chakravarty, Arunava, Lachinov, Dmitrii, Rivail, Antoine, Schmidt-Erfurth, Ursula, Bogunović, Hrvoje<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3246_paper.pdf)<br/>

---

## [Phy-Diff: Physics-guided Hourglass Diffusion Model for Diffusion MRI Synthesis](https://arxiv.org/abs/2406.03002)<br/>
**Authors:** Zhang, Juanhua, Yan, Ruodan, Perelli, Alessandro, Chen, Xi, Li, Chao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2374_paper.pdf)<br/>
**arXiv:** [2406.03002](https://arxiv.org/abs/2406.03002)<br/>

---

## CryoSAM: Training-free CryoET Tomogram Segmentation with Foundation Models<br/>
**Authors:** Zhao, Yizhou, Bian, Hengwei, Mu, Michael, Uddin, Mostofa R., Li, Zhenyang, Li, Xiang, Wang, Tianyang, Xu, Min<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0532_paper.pdf)<br/>

---

## [UrFound: Towards Universal Retinal Foundation Models via Knowledge-Guided Masked Modeling](https://arxiv.org/abs/2408.05618)<br/>
**Authors:** Yu, Kai, Zhou, Yang, Bai, Yang, Soh, Zhi Da, Xu, Xinxing, Goh, Rick Siow Mong, Cheng, Ching-Yu, Liu, Yong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1942_paper.pdf)<br/>
**arXiv:** [2408.05618](https://arxiv.org/abs/2408.05618)<br/>

---

## Lobar Lung Density Embeddings with a Transformer encoder (LobTe) to predict emphysema progression in COPD<br/>
**Authors:** Curiale, Ariel H., San José Estépar, Raúl<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2275_paper.pdf)<br/>

---

## Automated Spinal MRI Labelling from Reports Using a Large Language Model<br/>
**Authors:** Park, Robin Y., Windsor, Rhydian, Jamaludin, Amir, Zisserman, Andrew<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1510_paper.pdf)<br/>

---

## [Cardiac Copilot: Automatic Probe Guidance for Echocardiography with World Model](https://arxiv.org/abs/2406.13165)<br/>
**Authors:** Jiang, Haojun, Sun, Zhenguo, Jia, Ning, Li, Meng, Sun, Yu, Luo, Shaqi, Song, Shiji, Huang, Gao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0053_paper.pdf)<br/>
**arXiv:** [2406.13165](https://arxiv.org/abs/2406.13165)<br/>

---

## Fair and Accurate Skin Disease Image Classification by Alignment with Clinical Labels<br/>
**Authors:** Aayushman, Gaddey, Hemanth, Mittal, Vidhi, Chawla, Manisha, Gupta, Gagan Raj<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2609_paper.pdf)<br/>

---

## PASTA: Pathology-Aware MRI to PET CroSs-modal TrAnslation with Diffusion Models<br/>
**Authors:** Li, Yitong, Yakushev, Igor, Hedderich, Dennis M., Wachinger, Christian<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0501_paper.pdf)<br/>

---

## EchoTracker: Advancing Myocardial Point Tracking in Echocardiography<br/>
**Authors:** Azad, Md Abulkalam, Chernyshov, Artem, Nyberg, John, Tveten, Ingrid, Lovstakken, Lasse, Dalen, Håvard, Grenne, Bjørnar, Østvik, Andreas<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1980_paper.pdf)<br/>

---

## [HAMIL-QA: Hierarchical Approach to Multiple Instance Learning for Atrial LGE MRI Quality Assessment](https://arxiv.org/abs/2407.07254)<br/>
**Authors:** Sultan, K. M. Arefeen, Hisham, Md Hasibul Husain, Orkild, Benjamin, Morris, Alan, Kholmovski, Eugene, Bieging, Erik, Kwan, Eugene, Ranjan, Ravi, DiBella, Ed, Elhabian, Shireen Y.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3535_paper.pdf)<br/>
**arXiv:** [2407.07254](https://arxiv.org/abs/2407.07254)<br/>

---

## [MediCLIP: Adapting CLIP for Few-shot Medical Image Anomaly Detection](https://arxiv.org/abs/2405.11315)<br/>
**Authors:** Zhang, Ximiao, Xu, Min, Qiu, Dehui, Yan, Ruixin, Lang, Ning, Zhou, Xiuzhuang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0333_paper.pdf)<br/>
**arXiv:** [2405.11315](https://arxiv.org/abs/2405.11315)<br/>

---

## [Stable Diffusion Segmentation for Biomedical Images with Single-step Reverse Process](https://arxiv.org/abs/2406.18361)<br/>
**Authors:** Lin, Tianyu, Chen, Zhiguang, Yan, Zhonghao, Yu, Weijiang, Zheng, Fudan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1007_paper.pdf)<br/>
**arXiv:** [2406.18361](https://arxiv.org/abs/2406.18361)<br/>

---

## The Centerline-Cross Entropy Loss for Vessel-Like Structure Segmentation: Better Topology Consistency Without Sacrificing Accuracy<br/>
**Authors:** Acebes, Cesar, Moustafa, Abdel Hakim, Camara, Oscar, Galdran, Adrian<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1081_paper.pdf)<br/>

---

## [LaB-GATr: geometric algebra transformers for large biomedical surface and volume meshes](https://arxiv.org/abs/2403.07536)<br/>
**Authors:** Suk, Julian, Imre, Baris, Wolterink, Jelmer M.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2377_paper.pdf)<br/>
**arXiv:** [2403.07536](https://arxiv.org/abs/2403.07536)<br/>

---

## [Symmetry Awareness Encoded Deep Learning Framework for Brain Imaging Analysis](https://arxiv.org/abs/2407.08948)<br/>
**Authors:** Ma, Yang, Wang, Dongang, Liu, Peilin, Masters, Lynette, Barnett, Michael, Cai, Weidong, Wang, Chenyu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2579_paper.pdf)<br/>
**arXiv:** [2407.08948](https://arxiv.org/abs/2407.08948)<br/>

---

## [SinoSynth: A Physics-based Domain Randomization Approach for Generalizable CBCT Image Enhancement](https://arxiv.org/abs/2409.18355)<br/>
**Authors:** Pang, Yunkui, Liu, Yilin, Chen, Xu, Yap, Pew-Thian, Lian, Jun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1155_paper.pdf)<br/>
**arXiv:** [2409.18355](https://arxiv.org/abs/2409.18355)<br/>

---

## [TADM: Temporally-Aware Diffusion Model for Neurodegenerative Progression on Brain MRI](https://arxiv.org/abs/2406.12411)<br/>
**Authors:** Litrico, Mattia, Guarnera, Francesco, Giuffrida, Mario Valerio, Ravì, Daniele, Battiato, Sebastiano<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2281_paper.pdf)<br/>
**arXiv:** [2406.12411](https://arxiv.org/abs/2406.12411)<br/>

---

## Vision-Based Neurosurgical Guidance: Unsupervised Localization and Camera-Pose Prediction<br/>
**Authors:** Sarwin, Gary, Carretta, Alessandro, Staartjes, Victor, Zoli, Matteo, Mazzatenta, Diego, Regli, Luca, Serra, Carlo, Konukoglu, Ender<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0376_paper.pdf)<br/>

---

## Confidence intervals uncovered: Are we ready for real-world medical imaging AI?<br/>
**Authors:** Christodoulou, Evangelia, Reinke, Annika, Houhou, Rola, Kalinowski, Piotr, Erkan, Selen, Sudre, Carole H., Burgos, Ninon, Boutaj, Sofiène, Loizillon, Sophie, Solal, Maëlys, Rieke, Nicola, Cheplygina, Veronika, Antonelli, Michela, Mayer, Leon D., Tizabi, Minu D., Cardoso, M. Jorge, Simpson, Amber, Jäger, Paul F., Kopp-Schneider, Annette, Varoquaux, Gaël, Colliot, Olivier, Maier-Hein, Lena<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3400_paper.pdf)<br/>

---

## Pathological Semantics-Preserving Learning for H   E-to-IHC Virtual Staining<br/>
**Authors:** Chen, Fuqiang, Zhang, Ranran, Zheng, Boyun, Sun, Yiwen, He, Jiahui, Qin, Wenjian<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2078_paper.pdf)<br/>

---

## Revisiting Self-Attention in Medical Transformers via Dependency Sparsification<br/>
**Authors:** Lin, Xian, Wang, Zhehao, Yan, Zengqiang, Yu, Li<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1620_paper.pdf)<br/>

---

## [Generalized Robust Fundus Photography-based Vision Loss Estimation for High Myopia](https://arxiv.org/abs/2407.03699)<br/>
**Authors:** Yan, Zipei, Liang, Zhile, Liu, Zhengji, Wang, Shuai, Chun, Rachel Ka-Man, Li, Jizhou, Kee, Chea-su, Liang, Dong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1834_paper.pdf)<br/>
**arXiv:** [2407.03699](https://arxiv.org/abs/2407.03699)<br/>

---

## Loose Lesion Location Self-supervision Enhanced Colorectal Cancer Diagnosis<br/>
**Authors:** Gao, Tianhong, Song, Jie, Yu, Xiaotian, Zhang, Shengxuming, Liang, Wenjie, Zhang, Hongbin, Li, Ziqian, Zhang, Wenzhuo, Zhang, Xiuming, Zhong, Zipeng, Song, Mingli, Feng, Zunlei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1379_paper.pdf)<br/>

---

## [CS3: Cascade SAM for Sperm Segmentation](https://arxiv.org/abs/2407.03772)<br/>
**Authors:** Shi, Yi, Tian, Xu-Peng, Wang, Yun-Kai, Zhang, Tie-Yi, Yao, Bing, Wang, Hui, Shao, Yong, Wang, Cen-Cen, Zeng, Rong, Zhan, De-Chuan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0747_paper.pdf)<br/>
**arXiv:** [2407.03772](https://arxiv.org/abs/2407.03772)<br/>

---

## HyperSpace: Hypernetworks for spacing-adaptive image segmentation<br/>
**Authors:** Joutard, Samuel, Pietsch, Maximilian, Prevost, Raphael<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2109_paper.pdf)<br/>

---

## [SALI: Short-term Alignment and Long-term Interaction Network for Colonoscopy Video Polyp Segmentation](https://arxiv.org/abs/2406.13532)<br/>
**Authors:** Hu, Qiang, Yi, Zhenyu, Zhou, Ying, Peng, Fang, Liu, Mei, Li, Qiang, Wang, Zhiwei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2092_paper.pdf)<br/>
**arXiv:** [2406.13532](https://arxiv.org/abs/2406.13532)<br/>

---

## Towards tDCS Digital Twins using Deep Learning-based Direct Estimation of Personalized Electrical Field Maps from T1-Weighted MRI<br/>
**Authors:** Stolte, Skylar E., Indahlastari, Aprinda, Albizu, Alejandro, Woods, Adam J., Fang, Ruogu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1533_paper.pdf)<br/>

---

## MuST: Multi-Scale Transformers for Surgical Phase Recognition<br/>
**Authors:** Pérez, Alejandra, Rodríguez, Santiago, Ayobi, Nicolás, Aparicio, Nicolás, Dessevres, Eugénie, Arbeláez, Pablo<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3730_paper.pdf)<br/>

---

## Convex Segments for Convex Objects using DNN Boundary Tracing and Graduated Optimization<br/>
**Authors:** Pal, Jimut B., Awate, Suyash P.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0850_paper.pdf)<br/>

---

## [Universal Topology Refinement for Medical Image Segmentation with Polynomial Feature Synthesis](https://arxiv.org/abs/2409.09796)<br/>
**Authors:** Li, Liu, Wang, Hanchun, Baugh, Matthew, Ma, Qiang, Zhang, Weitong, Ouyang, Cheng, Rueckert, Daniel, Kainz, Bernhard<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2215_paper.pdf)<br/>
**arXiv:** [2409.09796](https://arxiv.org/abs/2409.09796)<br/>

---

## SHAN: Shape Guided Network for Thyroid Nodule Ultrasound Cross-Domain Segmentation<br/>
**Authors:** Zhang, Ruixuan, Lu, Wenhuan, Guan, Cuntai, Gao, Jie, Wei, Xi, Li, Xuewei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0407_paper.pdf)<br/>

---

## DnFPlane For Efficient and High-Quality 4D Reconstruction of Deformable Tissues<br/>
**Authors:** Bu, Ran, Xu, Chenwei, Shan, Jiwei, Li, Hao, Wang, Guangming, Miao, Yanzi, Wang, Hesheng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2081_paper.pdf)<br/>

---

## [RET-CLIP: A Retinal Image Foundation Model Pre-trained with Clinical Diagnostic Reports](https://arxiv.org/abs/2405.14137)<br/>
**Authors:** Du, Jiawei, Guo, Jia, Zhang, Weihang, Yang, Shengzhu, Liu, Hanruo, Li, Huiqi, Wang, Ningli<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1812_paper.pdf)<br/>
**arXiv:** [2405.14137](https://arxiv.org/abs/2405.14137)<br/>

---

## InstaSAM: Instance-aware Segment Any Nuclei Model with Point Annotations<br/>
**Authors:** Nam, Siwoo, Namgung, Hyun, Jeong, Jaehoon, Luna, Miguel, Kim, Soopil, Chikontwe, Philip, Park, Sang Hyun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2694_paper.pdf)<br/>

---

## Data Augmentation with Multi-armed Bandit on Image Deformations Improves Fluorescence Glioma Boundary Recognition<br/>
**Authors:** Xiao, Anqi, Han, Keyi, Shi, Xiaojing, Tian, Jie, Hu, Zhenhua<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0141_paper.pdf)<br/>

---

## Tail-Enhanced Representation Learning for Surgical Triplet Recognition<br/>
**Authors:** Gui, Shuangchun, Wang, Zhenkun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0026_paper.pdf)<br/>

---

## Follow the Radiologist: Clinically Relevant Multi-View Cues for Breast Cancer Detection from Mammograms<br/>
**Authors:** Jain, Kshitiz, Rangarajan, Krithika, Arora, Chetan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1306_paper.pdf)<br/>

---

## [ShapeMamba-EM: Fine-Tuning Foundation Model with Local Shape Descriptors and Mamba Blocks for 3D EM Image Segmentation](https://arxiv.org/abs/2408.14114)<br/>
**Authors:** Shi, Ruohua, Pang, Qiufan, Ma, Lei, Duan, Lingyu, Huang, Tiejun, Jiang, Tingting<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0151_paper.pdf)<br/>
**arXiv:** [2408.14114](https://arxiv.org/abs/2408.14114)<br/>

---

## [TLRN: Temporal Latent Residual Networks For Large Deformation Image Registration](https://arxiv.org/abs/2407.11219)<br/>
**Authors:** Wu, Nian, Xing, Jiarui, Zhang, Miaomiao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3610_paper.pdf)<br/>
**arXiv:** [2407.11219](https://arxiv.org/abs/2407.11219)<br/>

---

## Prompt-based Segmentation Model of Anatomical Structures and Lesions in CT Images<br/>
**Authors:** Ouyang, Xi, Gu, Dongdong, Li, Xuejian, Zhou, Wenqi, Chen, Qianqian, Zhan, Yiqiang, Zhou, Xiang, Shi, Feng, Xue, Zhong, Shen, Dinggang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0930_paper.pdf)<br/>

---

## [Active Label Refinement for Robust Training of Imbalanced Medical Image Classification Tasks in the Presence of High Label Noise](https://arxiv.org/abs/2407.05973)<br/>
**Authors:** Khanal, Bidur, Dai, Tianhong, Bhattarai, Binod, Linte, Cristian<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3963_paper.pdf)<br/>
**arXiv:** [2407.05973](https://arxiv.org/abs/2407.05973)<br/>

---

## [CriDiff: Criss-cross Injection Diffusion Framework via Generative Pre-train for Prostate Segmentation](https://arxiv.org/abs/2406.14186)<br/>
**Authors:** Liu, Tingwei, Zhang, Miao, Liu, Leiye, Zhong, Jialong, Wang, Shuyao, Piao, Yongri, Lu, Huchuan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0339_paper.pdf)<br/>
**arXiv:** [2406.14186](https://arxiv.org/abs/2406.14186)<br/>

---

## ASA: Learning Anatomical Consistency, Sub-volume Spatial Relationships and Fine-grained Appearance for CT Images<br/>
**Authors:** Pang, Jiaxuan, Ma, DongAo, Zhou, Ziyu, Gotway, Michael B., Liang, Jianming<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0271_paper.pdf)<br/>

---

## [An Uncertainty-guided Tiered Self-training Framework for Active Source-free Domain Adaptation in Prostate Segmentation](https://arxiv.org/abs/2407.02893)<br/>
**Authors:** Luo, Zihao, Luo, Xiangde, Gao, Zijun, Wang, Guotai<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1781_paper.pdf)<br/>
**arXiv:** [2407.02893](https://arxiv.org/abs/2407.02893)<br/>

---

## [Weakly-supervised Medical Image Segmentation with Gaze Annotations](https://arxiv.org/abs/2407.07406)<br/>
**Authors:** Zhong, Yuan, Tang, Chenhui, Yang, Yumeng, Qi, Ruoxi, Zhou, Kang, Gong, Yuqi, Heng, Pheng-Ann, Hsiao, Janet H., Dou, Qi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1675_paper.pdf)<br/>
**arXiv:** [2407.07406](https://arxiv.org/abs/2407.07406)<br/>

---

## Low-Rank Mixture-of-Experts for Continual Medical Image Segmentation<br/>
**Authors:** Chen, Qian, Zhu, Lei, He, Hangzhou, Zhang, Xinliang, Zeng, Shuang, Ren, Qiushi, Lu, Yanye<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1160_paper.pdf)<br/>

---

## [H2ASeg: Hierarchical Adaptive Interaction and Weighting Network for Tumor Segmentation in PET/CT Images](https://arxiv.org/abs/2403.18339)<br/>
**Authors:** Lu, Jinpeng, Chen, Jingyun, Cai, Linghan, Jiang, Songhan, Zhang, Yongbing<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0500_paper.pdf)<br/>
**arXiv:** [2403.18339](https://arxiv.org/abs/2403.18339)<br/>

---

## TARDRL: Task-Aware Reconstruction for Dynamic Representation Learning of fMRI<br/>
**Authors:** Zhao, Yunxi, Nie, Dong, Chen, Geng, Wu, Xia, Zhang, Daoqiang, Wen, Xuyun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0249_paper.pdf)<br/>

---

## Differentiable Soft Morphological Filters for Medical Image Segmentation<br/>
**Authors:** Guzzi, Lisa, Zuluaga, Maria A., Lareyre, Fabien, Di Lorenzo, Gilles, Goffart, Sébastien, Chierici, Andrea, Raffort, Juliette, Delingette, Hervé<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0322_paper.pdf)<br/>

---

## [EndoUIC: Promptable Diffusion Transformer for Unified Illumination Correction in Capsule Endoscopy](https://arxiv.org/abs/2406.13705)<br/>
**Authors:** Bai, Long, Chen, Tong, Tan, Qiaozhi, Nah, Wan Jun, Li, Yanheng, He, Zhicheng, Yuan, Sishen, Chen, Zhen, Wu, Jinlin, Islam, Mobarakol, Li, Zhen, Liu, Hongbin, Ren, Hongliang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0221_paper.pdf)<br/>
**arXiv:** [2406.13705](https://arxiv.org/abs/2406.13705)<br/>

---

## [Improved Esophageal Varices Assessment from Non-Contrast CT Scans](https://arxiv.org/abs/2407.13210)<br/>
**Authors:** Li, Chunli, Zhang, Xiaoming, Gao, Yuan, Yin, Xiaoli, Lu, Le, Zhang, Ling, Yan, Ke, Shi, Yu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0915_paper.pdf)<br/>
**arXiv:** [2407.13210](https://arxiv.org/abs/2407.13210)<br/>

---

## Interpretable phenotypic profiling of 3D cellular morphodynamics<br/>
**Authors:** De Vries, Matt, Naidoo, Reed, Fourkioti, Olga, Dent, Lucas G., Curry, Nathan, Dunsby, Christopher, Bakal, Chris<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3839_paper.pdf)<br/>

---

## MetaAD: Metabolism-Aware Anomaly Detection for Parkinson’s Disease in 3D 18F-FDG PET<br/>
**Authors:** Huang, Haolin, Shen, Zhenrong, Wang, Jing, Wang, Xinyu, Lu, Jiaying, Lin, Huamei, Ge, Jingjie, Zuo, Chuantao, Wang, Qian<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1687_paper.pdf)<br/>

---

## Vertex Proportion Loss for Multi-Class Cell Detection from Label Proportions<br/>
**Authors:** Pacheco, Carolina, Yellin, Florence, Vidal, René, Haeffele, Benjamin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3997_paper.pdf)<br/>

---

## Enhancing Model Generalisability through Sampling Diverse and Balanced Retinal Images<br/>
**Authors:** Zhou, Tianfeng, Zhou, Yukun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2889_paper.pdf)<br/>

---

## Self-guided Knowledge-injected Graph Neural Network for Alzheimer’s Diseases<br/>
**Authors:** Wang, Zhepeng, Bao, Runxue, Wu, Yawen, Liu, Guodong, Yang, Lei, Zhan, Liang, Zheng, Feng, Jiang, Weiwen, Zhang, Yanfu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0869_paper.pdf)<br/>

---

## [SurgicalGaussian: Deformable 3D Gaussians for High-Fidelity Surgical Scene Reconstruction](https://huggingface.co/papers/2407.05023)<br/>
**Authors:** Xie, Weixing, Yao, Junfeng, Cao, Xianpeng, Lin, Qiqin, Tang, Zerui, Dong, Xiao, Guo, Xiaohu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3077_paper.pdf)<br/>
**arXiv:** [2407.05023](https://arxiv.org/abs/2407.05023)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2407.05023](https://huggingface.co/papers/2407.05023)<br/>

---

## WiNet: Wavelet-based Incremental Learning for Efficient Medical Image Registration<br/>
**Authors:** Cheng, Xinxing, Jia, Xi, Lu, Wenqi, Li, Qiufu, Shen, Linlin, Krull, Alexander, Duan, Jinming<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2384_paper.pdf)<br/>

---

## [Cephalometric Landmark Detection across Ages with Prototypical Network](https://arxiv.org/abs/2406.12577)<br/>
**Authors:** Wu, Han, Wang, Chong, Mei, Lanzhuju, Yang, Tong, Zhu, Min, Shen, Dinggang, Cui, Zhiming<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0737_paper.pdf)<br/>
**arXiv:** [2406.12577](https://arxiv.org/abs/2406.12577)<br/>

---

## Simultaneous Monocular Endoscopic Dense Depth and Odometry Estimation Using Local-Global Integration Networks<br/>
**Authors:** Fan, Wenkang, Jiang, Wenjing, Fang, Hao, Shi, Hong, Chen, Jianhua, Luo, Xiongbiao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2617_paper.pdf)<br/>

---

## Few Slices Suffice: Multi-Faceted Consistency Learning with Active Cross-Annotation for Barely-supervised 3D Medical Image Segmentation<br/>
**Authors:** Wu, Xinyao, Xu, Zhe, Tong, Raymond Kai-yu<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0102_paper.pdf)<br/>

---

## Self-Supervised k-Space Regularization for Motion-Resolved Abdominal MRI Using Neural Implicit k-Space Representations<br/>
**Authors:** Spieker, Veronika, Eichhorn, Hannah, Stelter, Jonathan K., Huang, Wenqi, Braren, Rickmer F., Rueckert, Daniel, Sahli Costabal, Francisco, Hammernik, Kerstin, Prieto, Claudia, Karampinos, Dimitrios C., Schnabel, Julia A.<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3260_paper.pdf)<br/>

---

## MedMLP: An Efficient MLP-like Network for Zero-shot Retinal Image Classification<br/>
**Authors:** Zhou, Menghan, Xu, Yanyu, Soh, Zhi Da, Fu, Huazhu, Goh, Rick Siow Mong, Cheng, Ching-Yu, Liu, Yong, Zhen, Liangli<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1626_paper.pdf)<br/>

---

## [3DPX: Progressive 2D-to-3D Oral Image Reconstruction with Hybrid MLP-CNN Networks](https://arxiv.org/abs/2408.01292)<br/>
**Authors:** Li, Xiaoshuang, Meng, Mingyuan, Huang, Zimo, Bi, Lei, Delamare, Eduardo, Feng, Dagan, Sheng, Bin, Kim, Jinman<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2442_paper.pdf)<br/>
**arXiv:** [2408.01292](https://arxiv.org/abs/2408.01292)<br/>

---

## A Weakly-supervised Multi-lesion Segmentation Framework Based on Target-level Incomplete Annotations<br/>
**Authors:** Ju, Jianguo, Ren, Shumin, Qiu, Dandan, Tu, Huijuan, Yin, Juanjuan, Xu, Pengfei, Guan, Ziyu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1747_paper.pdf)<br/>

---

## Self-supervised 3D Skeleton Completion for Vascular Structures<br/>
**Authors:** Ren, Jiaxiang, Li, Zhenghong, Cheng, Wensheng, Zou, Zhilin, Park, Kicheon, Pan, Yingtian, Ling, Haibin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0862_paper.pdf)<br/>

---

## [LGRNet: Local-Global Reciprocal Network for Uterine Fibroid Segmentation in Ultrasound Videos](https://arxiv.org/abs/2407.05703)<br/>
**Authors:** Xu, Huihui, Yang, Yijun, Aviles-Rivero, Angelica I, Yang, Guang, Qin, Jing, Zhu, Lei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0813_paper.pdf)<br/>
**arXiv:** [2407.05703](https://arxiv.org/abs/2407.05703)<br/>

---

## Uncertainty-aware meta-weighted optimization framework for domain-generalized medical image segmentation<br/>
**Authors:** Oh, Seok-Hwan, Jung, Guil, Kim, Sang-Yun, Kim, Myeong-Gee, Kim, Young-Min, Lee, Hyeon-Jik, Kwon, Hyuk-Sool, Bae, Hyeon-Min<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0708_paper.pdf)<br/>

---

## DomainAdapt: Leveraging Multitask Learning and Domain Insights for Children’s Nutritional Status Assessment<br/>
**Authors:** Khan, Misaal, Singh, Richa, Vatsa, Mayank, Singh, Kuldeep<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/4215_paper.pdf)<br/>

---

## ORCGT: Ollivier-Ricci Curvature-based Graph Model for Lung STAS Prediction<br/>
**Authors:** Cen, Min, Wang, Zheng, Zhuang, Zhenfeng, Zhang, Hong, Su, Dan, Bao, Zhen, Wei, Weiwei, Magnier, Baptiste, Yu, Lequan, Wang, Liansheng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2860_paper.pdf)<br/>

---

## [A Refer-and-Ground Multimodal Large Language Model for Biomedicine](https://arxiv.org/abs/2406.18146)<br/>
**Authors:** Huang, Xiaoshuang, Huang, Haifeng, Shen, Lingdong, Yang, Yehui, Shang, Fangxin, Liu, Junwei, Liu, Jia<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1279_paper.pdf)<br/>
**arXiv:** [2406.18146](https://arxiv.org/abs/2406.18146)<br/>

---

## Distributionally-Adaptive Variational Meta Learning for Brain Graph Classification<br/>
**Authors:** Du, Jing, Dong, Guangwei, Ma, Congbo, Xue, Shan, Wu, Jia, Yang, Jian, Beheshti, Amin, Sheng, Quan Z., Giral, Alexis<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2429_paper.pdf)<br/>

---

## [FedMedICL: Towards Holistic Evaluation of Distribution Shifts in Federated Medical Imaging](https://arxiv.org/abs/2407.08822)<br/>
**Authors:** Alhamoud, Kumail, Ghunaim, Yasir, Alfarra, Motasem, Hartvigsen, Thomas, Torr, Philip, Ghanem, Bernard, Bibi, Adel, Ghassemi, Marzyeh<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2266_paper.pdf)<br/>
**arXiv:** [2407.08822](https://arxiv.org/abs/2407.08822)<br/>

---

## Development of Effective Connectome from Infancy to Adolescence<br/>
**Authors:** Li, Guoshi, Thung, Kim-Han, Taylor, Hoyt, Wu, Zhengwang, Li, Gang, Wang, Li, Lin, Weili, Ahmad, Sahar, Yap, Pew-Thian<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3736_paper.pdf)<br/>

---

## Multi-Frequency and Smoke Attention-aware Learning based Diffusion Model for Removing Surgical Smoke<br/>
**Authors:** Li, Hao, Zhai, Xiangyu, Xue, Jie, Gu, Changming, Tian, Baolong, Hong, Tingxuan, Jin, Bin, Li, Dengwang, Huang, Pu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2720_paper.pdf)<br/>

---

## Letting Osteocytes Teach SR-microCT Bone Lacunae Segmentation: A Feature Variation Distillation Method via Diffusion Denoising<br/>
**Authors:** Poles, Isabella, Santambrogio, Marco D., D’Arnese, Eleonora<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3328_paper.pdf)<br/>

---

## A Wasserstein Recipe for Replicable Machine Learning on Functional Neuroimages<br/>
**Authors:** Ding, Jiaqi, Dan, Tingting, Wei, Ziquan, Laurienti, Paul, Wu, Guorong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2322_paper.pdf)<br/>

---

## [Evidential Concept Embedding Models: Towards Reliable Concept Explanations for Skin Disease Diagnosis](https://arxiv.org/abs/2406.19130)<br/>
**Authors:** Gao, Yibo, Gao, Zheyao, Gao, Xin, Liu, Yuanye, Wang, Bomin, Zhuang, Xiahai<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2142_paper.pdf)<br/>
**arXiv:** [2406.19130](https://arxiv.org/abs/2406.19130)<br/>

---

## [AdaCBM: An Adaptive Concept Bottleneck Model for Explainable and Accurate Diagnosis](https://arxiv.org/abs/2408.02001)<br/>
**Authors:** Chowdhury, Townim F., Phan, Vu Minh Hieu, Liao, Kewen, To, Minh-Son, Xie, Yutong, van den Hengel, Anton, Verjans, Johan W., Liao, Zhibin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3895_paper.pdf)<br/>
**arXiv:** [2408.02001](https://arxiv.org/abs/2408.02001)<br/>

---

## Self-supervised Learning with Adaptive Graph Structure and Function Representation For Cross-Dataset Brain Disorder Diagnosis<br/>
**Authors:** Chen, Dongdong, Yao, Linlin, Liu, Mengjun, Shen, Zhenrong, Hu, Yuqi, Song, Zhiyun, Wang, Qian, Zhang, Lichi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0719_paper.pdf)<br/>

---

## STAN-LOC: Visual Query-based Video Clip Localization for Fetal Ultrasound Sweep Videos<br/>
**Authors:** Mishra, Divyanshu, Saha, Pramit, Zhao, He, Patey, Olga, Papageorghiou, Aris T., Noble, J. Alison<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0870_paper.pdf)<br/>

---

## SkinCON: Towards consensus for the uncertainty of skin cancer sub-typing through distribution regularized adaptive predictive sets (DRAPS)<br/>
**Authors:** Ren, Zhihang, Li, Yunqi, Li, Xinyu, Xie, Xinrong, Duhaime, Erik P., Fang, Kathy, Chakraborty, Tapabrata, Guo, Yunhui, Yu, Stella X., Whitney, David<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/4090_paper.pdf)<br/>

---

## Contrast Representation Learning from Imaging Parameters for Magnetic Resonance Image Synthesis<br/>
**Authors:** Xiong, Honglin, Fang, Yu, Sun, Kaicong, Wang, Yulin, Zong, Xiaopeng, Zhang, Weijun, Wang, Qian<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1236_paper.pdf)<br/>

---

## [Spatiotemporal Representation Learning for Short and Long Medical Image Time Series](https://arxiv.org/abs/2403.07513)<br/>
**Authors:** Shen, Chengzhi, Menten, Martin J., Bogunović, Hrvoje, Schmidt-Erfurth, Ursula, Scholl, Hendrik P. N., Sivaprasad, Sobha, Lotery, Andrew, Rueckert, Daniel, Hager, Paul, Holland, Robbie<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1006_paper.pdf)<br/>
**arXiv:** [2403.07513](https://arxiv.org/abs/2403.07513)<br/>

---

## Surface-based and Shape-informed U-fiber Atlasing for Robust Superficial White Matter Connectivity Analysis<br/>
**Authors:** Li, Yuan, Nie, Xinyu, Zhang, Jianwei, Shi, Yonggang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0213_paper.pdf)<br/>

---

## Keypoint Matching for Instrument-Free 3D Registration in Video-based Surgical Navigation<br/>
**Authors:** Baptista, Tânia, Raposo, Carolina, Marques, Miguel, Antunes, Michel, Barreto, Joao P.<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3454_paper.pdf)<br/>

---

## [Spatial Transcriptomics Analysis of Zero-shot Gene Expression Prediction](https://arxiv.org/abs/2401.14772)<br/>
**Authors:** Yang, Yan, Hossain, Md Zakir, Li, Xuesong, Rahman, Shafin, Stone, Eric<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2573_paper.pdf)<br/>
**arXiv:** [2401.14772](https://arxiv.org/abs/2401.14772)<br/>

---

## [Mammo-CLIP: A Vision Language Foundation Model to Enhance Data Efficiency and Robustness in Mammography](https://huggingface.co/papers/2405.12255)<br/>
**Authors:** Ghosh, Shantanu, Poynton, Clare B., Visweswaran, Shyam, Batmanghelich, Kayhan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0926_paper.pdf)<br/>
**arXiv:** [2405.12255](https://arxiv.org/abs/2405.12255)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2405.12255](https://huggingface.co/papers/2405.12255)<br/>
**🤗 Models:** [shawn24/Mammo-CLIP](https://huggingface.co/shawn24/Mammo-CLIP)<br/>

---

## Multi-modality 3D CNN Transformer for Assisting Clinical Decision in Intracerebral Hemorrhage<br/>
**Authors:** Xiong, Zicheng, Zhao, Kai, Ji, Like, Shu, Xujun, Long, Dazhi, Chen, Shengbo, Yang, Fuxing<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2046_paper.pdf)<br/>

---

## [When Diffusion MRI Meets Diffusion Model: A Novel Deep Generative Model for Diffusion MRI Generation](https://arxiv.org/abs/2408.12897)<br/>
**Authors:** Zhu, Xi, Zhang, Wei, Li, Yijie, O’Donnell, Lauren J., Zhang, Fan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2842_paper.pdf)<br/>
**arXiv:** [2408.12897](https://arxiv.org/abs/2408.12897)<br/>

---

## [Towards a text-based quantitative and explainable histopathology image analysis](https://arxiv.org/abs/2407.07360)<br/>
**Authors:** Nguyen, Anh Tien, Vuong, Trinh Thi Le, Kwak, Jin Tae<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2481_paper.pdf)<br/>
**arXiv:** [2407.07360](https://arxiv.org/abs/2407.07360)<br/>

---

## CLIP-DR: Textual Knowledge-Guided Diabetic Retinopathy Grading with Ranking-aware Prompting<br/>
**Authors:** Yu, Qinkai, Xie, Jianyang, Nguyen, Anh, Zhao, He, Zhang, Jiong, Fu, Huazhu, Zhao, Yitian, Zheng, Yalin, Meng, Yanda<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1493_paper.pdf)<br/>

---

## [D-MASTER: Mask Annealed Transformer for Unsupervised Domain Adaptation in Breast Cancer Detection from Mammograms](https://arxiv.org/abs/2407.06585)<br/>
**Authors:** Ashraf, Tajamul, Rangarajan, Krithika, Gambhir, Mohit, Gauba, Richa, Arora, Chetan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1343_paper.pdf)<br/>
**arXiv:** [2407.06585](https://arxiv.org/abs/2407.06585)<br/>

---

## Prompting Vision-Language Models for Dental Notation Aware Abnormality Detection<br/>
**Authors:** Du, Chenlin, Chen, Xiaoxuan, Wang, Jingyi, Wang, Junjie, Li, Zhongsen, Zhang, Zongjiu, Lao, Qicheng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2968_paper.pdf)<br/>

---

## Cross-modal Diffusion Modelling for Super-resolved Spatial Transcriptomics<br/>
**Authors:** Wang, Xiaofei, Huang, Xingxu, Price, Stephen, Li, Chao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2317_paper.pdf)<br/>

---

## A Multi-Information Dual-Layer Cross-Attention Model for Esophageal Fistula Prognosis<br/>
**Authors:** Zhang, Jianqiao, Xiong, Hao, Jin, Qiangguo, Feng, Tian, Ma, Jiquan, Xuan, Ping, Cheng, Peng, Ning, Zhiyuan, Ning, Zhiyu, Li, Changyang, Wang, Linlin, Cui, Hui<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0148_paper.pdf)<br/>

---

## Stochastic Anomaly Simulation for Maxilla Completion from Cone-Beam Computed Tomography<br/>
**Authors:** Guo, Yixiao, Pei, Yuru, Chen, Si, Zhou, Zhi-bo, Xu, Tianmin, Zha, Hongbin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1091_paper.pdf)<br/>

---

## VDPF: Enhancing DVT Staging Performance Using a Global-Local Feature Fusion Network<br/>
**Authors:** Xie, Xiaotong, Ye, Yufeng, Yang, Tingting, Huang, Bin, Huang, Bingsheng, Huang, Yi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2909_paper.pdf)<br/>

---

## [Knowledge-Guided Prompt Learning for Lifespan Brain MR Image Segmentation](https://arxiv.org/abs/2407.21328)<br/>
**Authors:** Teng, Lin, Zhao, Zihao, Huang, Jiawei, Cao, Zehong, Meng, Runqi, Shi, Feng, Shen, Dinggang<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1321_paper.pdf)<br/>
**arXiv:** [2407.21328](https://arxiv.org/abs/2407.21328)<br/>

---

## Understanding Brain Dynamics Through Neural Koopman Operator with Structure-Function Coupling<br/>
**Authors:** Chow, Chiyuen, Dan, Tingting, Styner, Martin, Wu, Guorong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2162_paper.pdf)<br/>

---

## [Topological Cycle Graph Attention Network for Brain Functional Connectivity](https://arxiv.org/abs/2403.19149)<br/>
**Authors:** Huang, Jinghan, Chen, Nanguang, Qiu, Anqi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1737_paper.pdf)<br/>
**arXiv:** [2403.19149](https://arxiv.org/abs/2403.19149)<br/>

---

## Zoom Pattern Signatures for Fetal Ultrasound Structures<br/>
**Authors:** Alsharid, Mohammad, Yasrab, Robail, Drukker, Lior, Papageorghiou, Aris T., Noble, J. Alison<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1820_paper.pdf)<br/>

---

## [MambaMIL: Enhancing Long Sequence Modeling with Sequence Reordering in Computational Pathology](https://arxiv.org/abs/2403.06800)<br/>
**Authors:** Yang, Shu, Wang, Yihui, Chen, Hao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3255_paper.pdf)<br/>
**arXiv:** [2403.06800](https://arxiv.org/abs/2403.06800)<br/>

---

## [LighTDiff: Surgical Endoscopic Image Low-Light Enhancement with T-Diffusion](https://arxiv.org/abs/2405.10550)<br/>
**Authors:** Chen, Tong, Lyu, Qingcheng, Bai, Long, Guo, Erjian, Gao, Huxin, Yang, Xiaoxiao, Ren, Hongliang, Zhou, Luping<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0771_paper.pdf)<br/>
**arXiv:** [2405.10550](https://arxiv.org/abs/2405.10550)<br/>

---

## PEMMA: Parameter-Efficient Multi-Modal Adaptation for Medical Image Segmentation<br/>
**Authors:** Saadi, Nada, Saeed, Numan, Yaqub, Mohammad, Nandakumar, Karthik<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3528_paper.pdf)<br/>

---

## [HySparK: Hybrid Sparse Masking for Large Scale Medical Image Pre-Training](https://arxiv.org/abs/2408.05815)<br/>
**Authors:** Tang, Fenghe, Xu, Ronghao, Yao, Qingsong, Fu, Xueming, Quan, Quan, Zhu, Heqin, Liu, Zaiyi, Zhou, S. Kevin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0897_paper.pdf)<br/>
**arXiv:** [2408.05815](https://arxiv.org/abs/2408.05815)<br/>

---

## Temporal Neighboring Multi-Modal Transformer with Missingness-Aware Prompt for Hepatocellular Carcinoma Prediction<br/>
**Authors:** Xu, Jingwen, Zhu, Ye, Lyu, Fei, Wong, Grace Lai-Hung, Yuen, Pong C.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0728_paper.pdf)<br/>

---

## Rethinking Cell Counting Methods: Decoupling Counting and Localization<br/>
**Authors:** Zheng, Zixuan, Shi, Yilei, Li, Chunlei, Hu, Jingliang, Zhu, Xiao Xiang, Mou, Lichao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2995_paper.pdf)<br/>

---

## Advancing Text-Driven Chest X-Ray Generation with Policy-Based Reinforcement Learning<br/>
**Authors:** Han, Woojung, Kim, Chanyoung, Ju, Dayun, Shim, Yumin, Hwang, Seong Jae<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0165_paper.pdf)<br/>

---

## BiasPruner: Debiased Continual Learning for Medical Image Classification<br/>
**Authors:** Bayasi, Nourhan, Fayyad, Jamil, Bissoto, Alceu, Hamarneh, Ghassan, Garbi, Rafeef<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2799_paper.pdf)<br/>

---

## [IterMask2: Iterative Unsupervised Anomaly Segmentation via Spatial and Frequency Masking for Brain Lesions in MRI](https://arxiv.org/abs/2406.02422)<br/>
**Authors:** Liang, Ziyun, Guo, Xiaoqing, Noble, J. Alison, Kamnitsas, Konstantinos<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1365_paper.pdf)<br/>
**arXiv:** [2406.02422](https://arxiv.org/abs/2406.02422)<br/>

---

## [Topological GCN for Improving Detection of Hip Landmarks from B-Mode Ultrasound Images](https://arxiv.org/abs/2408.13495)<br/>
**Authors:** Huang, Tianxiang, Shi, Jing, Jin, Ge, Li, Juncheng, Wang, Jun, Du, Jun, Shi, Jun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3284_paper.pdf)<br/>
**arXiv:** [2408.13495](https://arxiv.org/abs/2408.13495)<br/>

---

## SelfReg-UNet: Self-Regularized UNet for Medical Image Segmentation<br/>
**Authors:** Zhu, Wenhui, Chen, Xiwen, Qiu, Peijie, Farazi, Mohammad, Sotiras, Aristeidis, Razi, Abolfazl, Wang, Yalin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0712_paper.pdf)<br/>

---

## Dynamic Hybrid Unrolled Multi-Scale Network for Accelerated MRI Reconstruction<br/>
**Authors:** Li, Xiao-Xin, Zhu, Fang-Zheng, Yang, Junwei, Chen, Yong, Shen, Dinggang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1197_paper.pdf)<br/>

---

## Class-Balancing Deep Active Learning with Auto-Feature Mixing and Minority Push-Pull Sampling<br/>
**Authors:** Lin, Hongxin, Zhang, Chu, Wang, Mingyu, Huang, Bin, Shao, Jingjing, Zhang, Jinxiang, Gao, Zhenhua, Diao, Xianfen, Huang, Bingsheng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2541_paper.pdf)<br/>

---

## Diversified and Structure-realistic Fundus Image Synthesis for Diabetic Retinopathy Lesion Segmentation<br/>
**Authors:** Feng, Xiaoyi, Zhang, Minqing, He, Mengxian, Gao, Mengdi, Wei, Hao, Yuan, Wu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/4059_paper.pdf)<br/>

---

## [Robust Semi-supervised Multimodal Medical Image Segmentation via Cross Modality Collaboration](https://arxiv.org/abs/2408.07341)<br/>
**Authors:** Zhou, Xiaogen, Sun, Yiyou, Deng, Min, Chu, Winnie Chiu Wing, Dou, Qi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2001_paper.pdf)<br/>
**arXiv:** [2408.07341](https://arxiv.org/abs/2408.07341)<br/>

---

## [Image Distillation for Safe Data Sharing in Histopathology](https://arxiv.org/abs/2406.13536)<br/>
**Authors:** Li, Zhe, Kainz, Bernhard<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0484_paper.pdf)<br/>
**arXiv:** [2406.13536](https://arxiv.org/abs/2406.13536)<br/>

---

## Ensemble of Prior-guided Expert Graph Models for Survival Prediction in Digital Pathology<br/>
**Authors:** Ramanathan, Vishwesh, Pati, Pushpak, McNeil, Matthew, Martel, Anne L.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2280_paper.pdf)<br/>

---

## [Reliable Multi-View Learning with Conformal Prediction for Aortic Stenosis Classification in Echocardiography](https://arxiv.org/abs/2409.09680)<br/>
**Authors:** Gu, Ang Nan, Tsang, Michael, Vaseli, Hooman, Tsang, Teresa, Abolmaesumi, Purang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2346_paper.pdf)<br/>
**arXiv:** [2409.09680](https://arxiv.org/abs/2409.09680)<br/>

---

## [DRIM: Learning Disentangled Representations from Incomplete Multimodal Healthcare Data](https://arxiv.org/abs/2409.17055)<br/>
**Authors:** Robinet, Lucas, Berjaoui, Ahmad, Kheil, Ziad, Cohen-Jonathan Moyal, Elizabeth<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1276_paper.pdf)<br/>
**arXiv:** [2409.17055](https://arxiv.org/abs/2409.17055)<br/>

---

## [Resolving Variable Respiratory Motion From Unsorted 4D Computed Tomography](https://arxiv.org/abs/2407.00665)<br/>
**Authors:** Huang, Yuliang, Eiben, Bjoern, Thielemans, Kris, McClelland, Jamie R.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3437_paper.pdf)<br/>
**arXiv:** [2407.00665](https://arxiv.org/abs/2407.00665)<br/>

---

## Epileptic Seizure Detection in SEEG Signals using a Unified Multi-scale Temporal-Spatial-Spectral Transformer Model<br/>
**Authors:** Li, Zhuoyi, Li, Wenjun, Zhu, Ning, Han, Junwei, Liu, Tianming, Chen, Beibei, Yan, Zhiqiang, Zhang, Tuo<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1378_paper.pdf)<br/>

---

## [HeartBeat: Towards Controllable Echocardiography Video Synthesis with Multimodal Conditions-Guided Diffusion Models](https://arxiv.org/abs/2406.14098)<br/>
**Authors:** Zhou, Xinrui, Huang, Yuhao, Xue, Wufeng, Dou, Haoran, Cheng, Jun, Zhou, Han, Ni, Dong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1453_paper.pdf)<br/>
**arXiv:** [2406.14098](https://arxiv.org/abs/2406.14098)<br/>

---

## Context-guided Continual Reinforcement Learning for Landmark Detection with Incomplete Data<br/>
**Authors:** Wan, Kaiwen, Wang, Bomin, Wu, Fuping, Gong, Haiyu, Zhuang, Xiahai<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1410_paper.pdf)<br/>

---

## 3D-SAutoMed: Automatic Segment Anything Model for 3D Medical Image Segmentation from Local-Global Perspective<br/>
**Authors:** Liang, Junjie, Cao, Peng, Yang, Wenju, Yang, Jinzhu, Zaiane, Osmar R.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2090_paper.pdf)<br/>

---

## [Brain Cortical Functional Gradients Predict Cortical Folding Patterns via Attention Mesh Convolution](https://arxiv.org/abs/2205.10605)<br/>
**Authors:** Yang, Li, He, Zhibin, Zhong, Tianyang, Li, Changhe, Zhu, Dajiang, Han, Junwei, Liu, Tianming, Zhang, Tuo<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2888_paper.pdf)<br/>
**arXiv:** [2205.10605](https://arxiv.org/abs/2205.10605)<br/>

---

## [Ordinal Learning: Longitudinal Attention Alignment Model for Predicting Time to Future Breast Cancer Events from Mammograms](https://arxiv.org/abs/2409.06887)<br/>
**Authors:** Wang, Xin, Tan, Tao, Gao, Yuan, Marcus, Eric, Han, Luyi, Portaluri, Antonio, Zhang, Tianyu, Lu, Chunyao, Liang, Xinglong, Beets-Tan, Regina, Teuwen, Jonas, Mann, Ritse<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1554_paper.pdf)<br/>
**arXiv:** [2409.06887](https://arxiv.org/abs/2409.06887)<br/>

---

## [Privacy Protection in MRI Scans Using 3D Masked Autoencoders](https://arxiv.org/abs/2310.15778)<br/>
**Authors:** Van der Goten, Lennart A., Smith, Kevin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3076_paper.pdf)<br/>
**arXiv:** [2310.15778](https://arxiv.org/abs/2310.15778)<br/>

---

## [Leveraging Image Captions for Selective Whole Slide Image Annotation](https://arxiv.org/abs/2407.06363)<br/>
**Authors:** Qiu, Jingna, Aubreville, Marc, Wilm, Frauke, Öttl, Mathias, Utz, Jonas, Schlereth, Maja, Breininger, Katharina<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2268_paper.pdf)<br/>
**arXiv:** [2407.06363](https://arxiv.org/abs/2407.06363)<br/>

---

## [Latent Spaces Enable Transformer-Based Dose Prediction in Complex Radiotherapy Plans](https://arxiv.org/abs/2407.08650)<br/>
**Authors:** Wang, Edward, Au, Ryan, Lang, Pencilla, Mattonen, Sarah A.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0380_paper.pdf)<br/>
**arXiv:** [2407.08650](https://arxiv.org/abs/2407.08650)<br/>

---

## Seeing the Invisible: On Aortic Valve Reconstruction in Non-Contrast CT<br/>
**Authors:** Bujny, Mariusz, Jesionek, Katarzyna, Nalepa, Jakub, Bartczak, Tomasz, Miszalski-Jamka, Karol, Kostur, Marcin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3643_paper.pdf)<br/>

---

## Misjudging the Machine: Gaze May Forecast Human-Machine Team Performance in Surgery<br/>
**Authors:** Cho, Sue Min, Taylor, Russell H., Unberath, Mathias<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3852_paper.pdf)<br/>

---

## [Reliable Source Approximation: Source-Free Unsupervised Domain Adaptation for Vestibular Schwannoma MRI Segmentation](https://arxiv.org/abs/2405.16102)<br/>
**Authors:** Zeng, Hongye, Zou, Ke, Chen, Zhihao, Zheng, Rui, Fu, Huazhu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2349_paper.pdf)<br/>
**arXiv:** [2405.16102](https://arxiv.org/abs/2405.16102)<br/>

---

## [LGS: A Light-weight 4D Gaussian Splatting for Efficient Surgical Scene Reconstruction](https://arxiv.org/abs/2406.16073)<br/>
**Authors:** Liu, Hengyu, Liu, Yifan, Li, Chenxin, Li, Wuyang, Yuan, Yixuan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0827_paper.pdf)<br/>
**arXiv:** [2406.16073](https://arxiv.org/abs/2406.16073)<br/>

---

## [Differentiable Score-Based Likelihoods: Learning CT Motion Compensation From Clean Images](https://arxiv.org/abs/2404.14747)<br/>
**Authors:** Thies, Mareike, Maul, Noah, Mei, Siyuan, Pfaff, Laura, Vysotskaya, Nastassia, Gu, Mingxuan, Utz, Jonas, Possart, Dennis, Folle, Lukas, Wagner, Fabian, Maier, Andreas<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1486_paper.pdf)<br/>
**arXiv:** [2404.14747](https://arxiv.org/abs/2404.14747)<br/>

---

## [MMSummary: Multimodal Summary Generation for Fetal Ultrasound Video](https://arxiv.org/abs/2408.03761)<br/>
**Authors:** Guo, Xiaoqing, Men, Qianhui, Noble, J. Alison<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0399_paper.pdf)<br/>
**arXiv:** [2408.03761](https://arxiv.org/abs/2408.03761)<br/>

---

## [Depth-Driven Geometric Prompt Learning for Laparoscopic Liver Landmark Detection](https://arxiv.org/abs/2406.17858)<br/>
**Authors:** Pei, Jialun, Cui, Ruize, Li, Yaoqian, Si, Weixin, Qin, Jing, Heng, Pheng-Ann<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0310_paper.pdf)<br/>
**arXiv:** [2406.17858](https://arxiv.org/abs/2406.17858)<br/>

---

## mQSM: Multitask Learning-based Quantitative Susceptibility Mapping for Iron Analysis in Brain<br/>
**Authors:** He, Junjie, Fu, Bangkang, Xiong, Zhenliang, Peng, Yunsong, Wang, Rongpin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2723_paper.pdf)<br/>

---

## A Curvature-Guided Coarse-to-Fine Framework for Enhanced Whole Brain Segmentation<br/>
**Authors:** Zhao, Fenqiang, Tang, Yuxing, Lu, Le, Zhang, Ling<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2514_paper.pdf)<br/>

---

## DeepRepViz: Identifying potential confounders in deep learning model predictions<br/>
**Authors:** Rane, Roshan Prakash, Kim, JiHoon, Umesha, Arjun, Stark, Didem, Schulz, Marc-André, Ritter, Kerstin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2088_paper.pdf)<br/>

---

## Class and Region-Adaptive Constraints for Network Calibration<br/>
**Authors:** Murugesan, Balamurali, Silva-Rodriguez, Julio, Ben Ayed, Ismail, Dolz, Jose<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1527_paper.pdf)<br/>

---

## [Fuzzy Attention-based Border Rendering Network for Lung Organ Segmentation](https://arxiv.org/abs/2406.16189)<br/>
**Authors:** Zhang, Sheng, Nan, Yang, Fang, Yingying, Wang, Shiyi, Xing, Xiaodan, Gao, Zhifan, Yang, Guang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2376_paper.pdf)<br/>
**arXiv:** [2406.16189](https://arxiv.org/abs/2406.16189)<br/>

---

## Quality-Aware Fuzzy Min-Max Neural Networks for Dynamic Brain Network Analysis<br/>
**Authors:** Hou, Tao, Huang, Jiashuang, Jiang, Shu, Ding, Weiping<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2558_paper.pdf)<br/>

---

## Tri-Plane Mamba: Efficiently Adapting Segment Anything Model for 3D Medical Images<br/>
**Authors:** Wang, Hualiang, Lin, Yiqun, Ding, Xinpeng, Li, Xiaomeng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2184_paper.pdf)<br/>

---

## Multi-order Simplex-based Graph Neural Network for Brain Network Analysis<br/>
**Authors:** Hwang, Yechan, Hwang, Soojin, Wu, Guorong, Kim, Won Hwa<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2758_paper.pdf)<br/>

---

## LLM-guided Multi-modal Multiple Instance Learning for 5-year Overall Survival Prediction of Lung Cancer<br/>
**Authors:** Kim, Kyungwon, Lee, Yongmoon, Park, Doohyun, Eo, Taejoon, Youn, Daemyung, Lee, Hyesang, Hwang, Dosik<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2173_paper.pdf)<br/>

---

## [Parameter Efficient Fine Tuning for Multi-scanner PET to PET Reconstruction](https://arxiv.org/abs/2407.07517)<br/>
**Authors:** Kim, Yumin, Choi, Gayoon, Hwang, Seong Jae<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0560_paper.pdf)<br/>
**arXiv:** [2407.07517](https://arxiv.org/abs/2407.07517)<br/>

---

## [Force Sensing Guided Artery-Vein Segmentation via Sequential Ultrasound Images](https://arxiv.org/abs/2407.21394)<br/>
**Authors:** Geng, Yimeng, Meng, Gaofeng, Chen, Mingcong, Cao, Guanglin, Zhao, Mingyang, Zhao, Jianbo, Liu, Hongbin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3161_paper.pdf)<br/>
**arXiv:** [2407.21394](https://arxiv.org/abs/2407.21394)<br/>

---

## OSAL-ND: Open-set Active Learning for Nucleus Detection<br/>
**Authors:** Tang, Jiao, Yue, Yagao, Wan, Peng, Wang, Mingliang, Zhang, Daoqiang, Shao, Wei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0661_paper.pdf)<br/>

---

## [TabMixer: Noninvasive Estimation of the Mean Pulmonary Artery Pressure via Imaging and Tabular Data Mixing](https://arxiv.org/abs/2409.07564)<br/>
**Authors:** Grzeszczyk, Michal K., Korzeniowski, Przemysław, Alabed, Samer, Swift, Andrew J., Trzciński, Tomasz, Sitek, Arkadiusz<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2329_paper.pdf)<br/>
**arXiv:** [2409.07564](https://arxiv.org/abs/2409.07564)<br/>

---

## ProstNFound: Integrating Foundation Models with Ultrasound Domain Knowledge and Clinical Context for Robust Prostate Cancer Detection<br/>
**Authors:** Wilson, Paul F. R., To, Minh Nguyen Nhat, Jamzad, Amoon, Gilany, Mahdi, Harmanani, Mohamed, Elghareb, Tarek, Fooladgar, Fahimeh, Wodlinger, Brian, Abolmaesumi, Purang, Mousavi, Parvin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2644_paper.pdf)<br/>

---

## Automated Robust Muscle Segmentation in Multi-level Contexts using a Probabilistic Inference Framework<br/>
**Authors:** Wang, Jinge, Chen, Guilin, Wang, Xuefeng, Wu, Nan, Zhang, Terry Jianguo<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1932_paper.pdf)<br/>

---

## [PhenDiff: Revealing Subtle Phenotypes with Diffusion Models in Real Images](https://huggingface.co/papers/2312.08290)<br/>
**Authors:** Bourou, Anis, Boyer, Thomas, Gheisari, Marzieh, Daupin, Kévin, Dubreuil, Véronique, De Thonel, Aurélie, Mezger, Valérie, Genovesio, Auguste<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1948_paper.pdf)<br/>
**arXiv:** [2312.08290](https://arxiv.org/abs/2312.08290)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2312.08290](https://huggingface.co/papers/2312.08290)<br/>

---

## Endo-4DGS: Endoscopic Monocular Scene Reconstruction with 4D Gaussian Splatting<br/>
**Authors:** Huang, Yiming, Cui, Beilei, Bai, Long, Guo, Ziqi, Xu, Mengya, Islam, Mobarakol, Ren, Hongliang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0223_paper.pdf)<br/>

---

## [Domain Adaptation of Echocardiography Segmentation Via Reinforcement Learning](https://arxiv.org/abs/2406.17902)<br/>
**Authors:** Judge, Arnaud, Judge, Thierry, Duchateau, Nicolas, Sandler, Roman A., Sokol, Joseph Z., Bernard, Olivier, Jodoin, Pierre-Marc<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2284_paper.pdf)<br/>
**arXiv:** [2406.17902](https://arxiv.org/abs/2406.17902)<br/>

---

## Mining Gold from the Sand: Weakly Supervised Histological Tissue Segmentation with Activation Relocalization and Mutual Learning<br/>
**Authors:** Feng, Siyang, Chen, Jiale, Liu, Zhenbing, Liu, Wentao, Wang, Zimin, Lan, Rushi, Pan, Xipeng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1156_paper.pdf)<br/>

---

## [Towards Learning Contrast Kinetics with Multi-Condition Latent Diffusion Models](https://arxiv.org/abs/2403.13890)<br/>
**Authors:** Osuala, Richard, Lang, Daniel M., Verma, Preeti, Joshi, Smriti, Tsirikoglou, Apostolia, Skorupko, Grzegorz, Kushibar, Kaisar, Garrucho, Lidia, Pinaya, Walter H. L., Diaz, Oliver, Schnabel, Julia A., Lekadir, Karim<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3434_paper.pdf)<br/>
**arXiv:** [2403.13890](https://arxiv.org/abs/2403.13890)<br/>

---

## [Spatial Diffusion for Cell Layout Generation](https://arxiv.org/abs/2409.03106)<br/>
**Authors:** Li, Chen, Hu, Xiaoling, Abousamra, Shahira, Xu, Meilong, Chen, Chao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2613_paper.pdf)<br/>
**arXiv:** [2409.03106](https://arxiv.org/abs/2409.03106)<br/>

---

## [Simplify Implant Depth Prediction as Video Grounding: A Texture Perceive Implant Depth Prediction Network](https://arxiv.org/abs/2406.04603)<br/>
**Authors:** Yang, Xinquan, Li, Xuguang, Luo, Xiaoling, Zeng, Leilei, Zhang, Yudi, Shen, Linlin, Deng, Yongqiang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2491_paper.pdf)<br/>
**arXiv:** [2406.04603](https://arxiv.org/abs/2406.04603)<br/>

---

## [Masks and Manuscripts: Advancing Medical Pre-training with End-to-End Masking and Narrative Structuring](https://arxiv.org/abs/2407.16264)<br/>
**Authors:** Gowda, Shreyank N., Clifton, David A.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0290_paper.pdf)<br/>
**arXiv:** [2407.16264](https://arxiv.org/abs/2407.16264)<br/>

---

## A task-conditional mixture-of-experts model for missing modality segmentation<br/>
**Authors:** Novosad, Philip, Carano, Richard A. D., Krishnan, Anitha Priya<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2509_paper.pdf)<br/>

---

## Unsupervised Domain Adaptation using Soft-Labeled Contrastive Learning with Reversed Monte Carlo Method for Cardiac Image Segmentation<br/>
**Authors:** Gu, Mingxuan, Thies, Mareike, Mei, Siyuan, Wagner, Fabian, Fan, Mingcheng, Sun, Yipeng, Pan, Zhaoya, Vesal, Sulaiman, Kosti, Ronak, Possart, Dennis, Utz, Jonas, Maier, Andreas<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1593_paper.pdf)<br/>

---

## Advancing Sensorless Freehand 3D Ultrasound Reconstruction with a Novel Coupling Pad<br/>
**Authors:** Dai, Ling, Zhao, Kaitao, Li, Zhongyu, Zhu, Jihua, Liang, Libin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1045_paper.pdf)<br/>

---

## Physics-Informed Deep Learning for Motion-Corrected Reconstruction of Quantitative Brain MRI<br/>
**Authors:** Eichhorn, Hannah, Spieker, Veronika, Hammernik, Kerstin, Saks, Elisa, Weiss, Kilian, Preibisch, Christine, Schnabel, Julia A.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1914_paper.pdf)<br/>

---

## SIX-Net: Spatial-context Information miX-up for Electrode Landmark Detection<br/>
**Authors:** Wang, Xinyi, Xu, Zikang, Zhu, Heqin, Yao, Qingsong, Sun, Yiyong, Zhou, S. Kevin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2762_paper.pdf)<br/>

---

## MoCo-Diff: Adaptive Conditional Prior on Diffusion Network for MRI Motion Correction<br/>
**Authors:** Li, Feng, Zhou, Zijian, Fang, Yu, Cai, Jiangdong, Wang, Qian<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1678_paper.pdf)<br/>

---

## Mixed Integer Linear Programming for Discrete Sampling Scheme Design in Diffusion MRI<br/>
**Authors:** Zhang, Si-Miao, Wang, Jing, Wang, Yi-Xuan, Liu, Tao, Zhu, Haogang, Zhang, Han, Cheng, Jian<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2540_paper.pdf)<br/>

---

## [Intraoperative Registration by Cross-Modal Inverse Neural Rendering](https://arxiv.org/abs/2409.11983)<br/>
**Authors:** Fehrentz, Maximilian, Azampour, Mohammad Farid, Dorent, Reuben, Rasheed, Hassan, Galvin, Colin, Golby, Alexandra, Wells III, William M., Frisken, Sarah, Navab, Nassir, Haouchine, Nazim<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3581_paper.pdf)<br/>
**arXiv:** [2409.11983](https://arxiv.org/abs/2409.11983)<br/>

---

## Feature Selection Gates with Gradient Routing for Endoscopic Image Computing<br/>
**Authors:** Roffo, Giorgio, Biffi, Carlo, Salvagnini, Pietro, Cherubini, Andrea<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0410_paper.pdf)<br/>

---

## [CAR-MFL: Cross-Modal Augmentation by Retrieval for Multimodal Federated Learning with Missing Modalities](https://arxiv.org/abs/2407.08648)<br/>
**Authors:** Poudel, Pranav, Shrestha, Prashant, Amgain, Sanskar, Shrestha, Yash Raj, Gyawali, Prashnna, Bhattarai, Binod<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0391_paper.pdf)<br/>
**arXiv:** [2407.08648](https://arxiv.org/abs/2407.08648)<br/>

---

## An approach to building foundation models for brain image analysis<br/>
**Authors:** Karimi, Davood<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3820_paper.pdf)<br/>

---

## [Insight: A Multi-Modal Diagnostic Pipeline using LLMs for Ocular Surface Disease Diagnosis](https://arxiv.org/abs/2410.00292)<br/>
**Authors:** Yeh, Chun-Hsiao, Wang, Jiayun, Graham, Andrew D., Liu, Andrea J., Tan, Bo, Chen, Yubei, Ma, Yi, Lin, Meng C.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0298_paper.pdf)<br/>
**arXiv:** [2410.00292](https://arxiv.org/abs/2410.00292)<br/>

---

## Efficient Cortical Surface Parcellation via Full-Band Diffusion Learning at Individual Space<br/>
**Authors:** Zhu, Yuanzhuo, Lian, Chunfeng, Li, Xianjun, Wang, Fan, Ma, Jianhua<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2548_paper.pdf)<br/>

---

## [LIBR+: Improving Intraoperative Liver Registration by Learning the Residual of Biomechanics-Based Deformable Registration](https://arxiv.org/abs/2403.06901)<br/>
**Authors:** Wang, Dingrong, Azadvar, Soheil, Heiselman, Jon, Jiang, Xiajun, Miga, Michael, Wang, Linwei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3351_paper.pdf)<br/>
**arXiv:** [2403.06901](https://arxiv.org/abs/2403.06901)<br/>

---

## A Hybrid CNN-Transformer Feature Pyramid Network for Granular Abdominal Aortic Calcification Detection from DXA Images<br/>
**Authors:** Ilyas, Zaid, Saleem, Afsah, Suter, David, Schousboe, John T., Leslie, William D., Lewis, Joshua R., Gilani, Syed Zulqarnain<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1214_paper.pdf)<br/>

---

## Adaptive Smooth Activation Function for Improved Organ Segmentation and Disease Diagnosis<br/>
**Authors:** Biswas, Koushik, Jha, Debesh, Tomar, Nikhil Kumar, Karri, Meghana, Reza, Amit, Durak, Gorkem, Medetalibeyoglu, Alpay, Antalek, Matthew, Velichko, Yury, Ladner, Daniela, Borhani, Amir, Bagci, Ulas<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3846_paper.pdf)<br/>

---

## [Towards a Benchmark for Colorectal Cancer Segmentation in Endorectal Ultrasound Videos: Dataset and Model Development](https://huggingface.co/papers/2408.10067)<br/>
**Authors:** Jiang, Yuncheng, Hu, Yiwen, Zhang, Zixun, Wei, Jun, Feng, Chun-Mei, Tang, Xuemei, Wan, Xiang, Liu, Yong, Cui, Shuguang, Li, Zhen<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0073_paper.pdf)<br/>
**arXiv:** [2408.10067](https://arxiv.org/abs/2408.10067)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2408.10067](https://huggingface.co/papers/2408.10067)<br/>

---

## RetMIL: Retentive Multiple Instance Learning for Histopathological Whole Slide Image Classification<br/>
**Authors:** Chu, Hongbo, Sun, Qiehe, Li, Jiawen, Chen, Yuxuan, Zhang, Lizhong, Guan, Tian, Han, Anjia, He, Yonghong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1723_paper.pdf)<br/>

---

## [Multimodal Cross-Task Interaction for Survival Analysis in Whole Slide Pathological Images](https://arxiv.org/abs/2406.17225)<br/>
**Authors:** Jiang, Songhan, Gan, Zhengyu, Cai, Linghan, Wang, Yifeng, Zhang, Yongbing<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1280_paper.pdf)<br/>
**arXiv:** [2406.17225](https://arxiv.org/abs/2406.17225)<br/>

---

## Anatomically-Controllable Medical Image Generation with Segmentation-Guided Diffusion Models<br/>
**Authors:** Konz, Nicholas, Chen, Yuwen, Dong, Haoyu, Mazurowski, Maciej A.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0584_paper.pdf)<br/>

---

## [Advancing UWF-SLO Vessel Segmentation with Source-Free Active Domain Adaptation and a Novel Multi-Center Dataset](https://arxiv.org/abs/2406.13645)<br/>
**Authors:** Wang, Hongqiu, Luo, Xiangde, Chen, Wu, Tang, Qingqing, Xin, Mei, Wang, Qiong, Zhu, Lei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2030_paper.pdf)<br/>
**arXiv:** [2406.13645](https://arxiv.org/abs/2406.13645)<br/>

---

## [Robust Conformal Volume Estimation in 3D Medical Images](https://arxiv.org/abs/2407.19938)<br/>
**Authors:** Lambert, Benjamin, Forbes, Florence, Doyle, Senan, Dojat, Michel<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3051_paper.pdf)<br/>
**arXiv:** [2407.19938](https://arxiv.org/abs/2407.19938)<br/>

---

## [Leveraging the Mahalanobis Distance to enhance Unsupervised Brain MRI Anomaly Detection](https://arxiv.org/abs/2407.12474)<br/>
**Authors:** Behrendt, Finn, Bhattacharya, Debayan, Mieling, Robin, Maack, Lennart, Krüger, Julia, Opfer, Roland, Schlaefer, Alexander<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1502_paper.pdf)<br/>
**arXiv:** [2407.12474](https://arxiv.org/abs/2407.12474)<br/>

---

## The MRI Scanner as a Diagnostic: Image-less Active Sampling<br/>
**Authors:** Du, Yuning, Dharmakumar, Rohan, Tsaftaris, Sotirios A.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2052_paper.pdf)<br/>

---

## 3D Spine Shape Estimation from Single 2D DXA<br/>
**Authors:** Bourigault, Emmanuelle, Jamaludin, Amir, Zisserman, Andrew<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1861_paper.pdf)<br/>

---

## Can LLMs’ Tuning Methods Work in Medical Multimodal Domain?<br/>
**Authors:** Chen, Jiawei, Jiang, Yue, Yang, Dingkang, Li, Mingcheng, Wei, Jinjie, Qian, Ziyun, Zhang, Lihua<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0640_paper.pdf)<br/>

---

## [HecVL: Hierarchical Video-Language Pretraining for Zero-shot Surgical Phase Recognition](https://arxiv.org/abs/2405.10075)<br/>
**Authors:** Yuan, Kun, Srivastav, Vinkle, Navab, Nassir, Padoy, Nicolas<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1025_paper.pdf)<br/>
**arXiv:** [2405.10075](https://arxiv.org/abs/2405.10075)<br/>

---

## [Achieving Fairness Through Channel Pruning for Dermatological Disease Diagnosis](https://arxiv.org/abs/2405.08681)<br/>
**Authors:** Kong, Qingpeng, Chiu, Ching-Hao, Zeng, Dewen, Chen, Yu-Jen, Ho, Tsung-Yi, Hu, Jingtong, Shi, Yiyu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2133_paper.pdf)<br/>
**arXiv:** [2405.08681](https://arxiv.org/abs/2405.08681)<br/>

---

## [WsiCaption: Multiple Instance Generation of Pathology Reports for Gigapixel Whole-Slide Images](https://arxiv.org/abs/2311.16480)<br/>
**Authors:** Chen, Pingyi, Li, Honglin, Zhu, Chenglu, Zheng, Sunyi, Shui, Zhongyi, Yang, Lin<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0761_paper.pdf)<br/>
**arXiv:** [2311.16480](https://arxiv.org/abs/2311.16480)<br/>

---

## Adaptive Curriculum Query Strategy for Active Learning in Medical Image Classification<br/>
**Authors:** Ma, Siteng, Du, Honghui, Curran, Kathleen M., Lawlor, Aonghus, Dong, Ruihai<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1423_paper.pdf)<br/>

---

## GMoD: Graph-driven Momentum Distillation Framework with Active Perception of Disease Severity for Radiology Report Generation<br/>
**Authors:** Xiang, ZhiPeng, Cui, ShaoGuo, Shang, CaoZhi, Jiang, Jingfeng, Zhang, Liqiang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1733_paper.pdf)<br/>

---

## Integrative Graph-Transformer Framework for Histopathology Whole Slide Image Representation and Classification<br/>
**Authors:** Shi, Zhan, Zhang, Jingwei, Kong, Jun, Wang, Fusheng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2165_paper.pdf)<br/>

---

## PX2Tooth: Reconstructing the 3D Point Cloud Teeth from a Single Panoramic X-ray<br/>
**Authors:** Ma, Wen, Wu, Huikai, Xiao, Zikai, Feng, Yang, Wu, Jian, Liu, Zuozhu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1637_paper.pdf)<br/>

---

## M4oE: A Foundation Model for Medical Multimodal Image Segmentation with Mixture of Experts<br/>
**Authors:** Jiang, Yufeng, Shen, Yiqing<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1472_paper.pdf)<br/>

---

## [Concept-Attention Whitening for Interpretable Skin Lesion Diagnosis](https://arxiv.org/abs/2404.05997)<br/>
**Authors:** Hou, Junlin, Xu, Jilan, Chen, Hao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1272_paper.pdf)<br/>
**arXiv:** [2404.05997](https://arxiv.org/abs/2404.05997)<br/>

---

## Anatomical Structure-Guided Medical Vision-Language Pre-training<br/>
**Authors:** Li, Qingqiu, Yan, Xiaohan, Xu, Jilan, Yuan, Runtian, Zhang, Yuejie, Feng, Rui, Shen, Quanli, Zhang, Xiaobo, Wang, Shujun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2014_paper.pdf)<br/>

---

## [Feature-prompting GBMSeg: One-Shot Reference Guided Training-Free Prompt Engineering for Glomerular Basement Membrane Segmentation](https://arxiv.org/abs/2406.16271)<br/>
**Authors:** Liu, Xueyu, Shi, Guangze, Wang, Rui, Lai, Yexin, Zhang, Jianan, Sun, Lele, Yang, Quan, Wu, Yongfei, Li, Ming, Han, Weixia, Zheng, Wen<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1841_paper.pdf)<br/>
**arXiv:** [2406.16271](https://arxiv.org/abs/2406.16271)<br/>

---

## Adapting Pre-trained Generative Model to Medical Image for Data Augmentation<br/>
**Authors:** Yuan, Zhouhang, Fang, Zhengqing, Huang, Zhengxing, Wu, Fei, Yao, Yu-Feng, Li, Yingming<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2585_paper.pdf)<br/>

---

## Data-Algorithm-Architecture Co-Optimization for Fair Neural Networks on Skin Lesion Dataset<br/>
**Authors:** Sheng, Yi, Yang, Junhuan, Li, Jinyang, Alaina, James, Xu, Xiaowei, Shi, Yiyu, Hu, Jingtong, Jiang, Weiwen, Yang, Lei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1123_paper.pdf)<br/>

---

## [A Unified Model for Longitudinal Multi-Modal Multi-View Prediction with Missingness](https://arxiv.org/abs/2403.12211)<br/>
**Authors:** Chen, Boqi, Oliva, Junier, Niethammer, Marc<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2390_paper.pdf)<br/>
**arXiv:** [2403.12211](https://arxiv.org/abs/2403.12211)<br/>

---

## Decoupled Training for Semi-supervised Medical Image Segmentation with Worst-Case-Aware Learning<br/>
**Authors:** Das, Ankit, Gautam, Chandan, Cholakkal, Hisham, Agrawal, Pritee, Yang, Feng, Savitha, Ramasamy, Liu, Yong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2247_paper.pdf)<br/>

---

## CAPTURE-GAN: Conditional Attribute Preservation through Unveiling Realistic GAN for artifact removal in dual-energy CT imaging<br/>
**Authors:** Park, Chunsu, Kim, Seonho, Lee, DongEon, Lee, SiYeoul, Kambaluru, Ashok, Park, Chankue, Kim, MinWoo<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3097_paper.pdf)<br/>

---

## MetaUNETR: Rethinking Token Mixer Encoding for Efficient Multi-Organ Segmentation<br/>
**Authors:** Lyu, Pengju, Zhang, Jie, Zhang, Lei, Liu, Wenjian, Wang, Cheng, Zhu, Jianjun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2749_paper.pdf)<br/>

---

## [Robustly Optimized Deep Feature Decoupling Network for Fatty Liver Diseases Detection](https://arxiv.org/abs/2406.17338)<br/>
**Authors:** Huang, Peng, Hu, Shu, Peng, Bo, Zhang, Jiashu, Wu, Xi, Wang, Xin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3325_paper.pdf)<br/>
**arXiv:** [2406.17338](https://arxiv.org/abs/2406.17338)<br/>

---

## Uncovering Cortical Pathways of Prion-like Pathology Spreading in Alzheimer’s Disease by Neural Optimal Mass Transport<br/>
**Authors:** Huang, Yanquan, Dan, Tingting, Kim, Won Hwa, Wu, Guorong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2276_paper.pdf)<br/>

---

## Enhancing Label-efficient Medical Image Segmentation with Text-guided Diffusion Models<br/>
**Authors:** Feng, Chun-Mei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0703_paper.pdf)<br/>

---

## PET Image Denoising Based on 3D Denoising Diffusion Probabilistic Model: Evaluations on Total-Body Datasets<br/>
**Authors:** Yu, Boxiao, Ozdemir, Savas, Dong, Yafei, Shao, Wei, Shi, Kuangyu, Gong, Kuang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3664_paper.pdf)<br/>

---

## [Aligning Human Knowledge with Visual Concepts Towards Explainable Medical Image Classification](https://arxiv.org/abs/2406.05596)<br/>
**Authors:** Gao, Yunhe, Gu, Difei, Zhou, Mu, Metaxas, Dimitris<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0117_paper.pdf)<br/>
**arXiv:** [2406.05596](https://arxiv.org/abs/2406.05596)<br/>

---

## EchoNarrator: Generating natural text explanations for ejection fraction predictions<br/>
**Authors:** Thomas, Sarina, Cao, Qing, Novikova, Anna, Kulikova, Daria, Ben-Yosef, Guy<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1027_paper.pdf)<br/>

---

## CLEFT: Language-Image Contrastive Learning with Efficient Large Language Model and Prompt Fine-Tuning<br/>
**Authors:** Du, Yuexi, Chang, Brian, Dvornek, Nicha C.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0704_paper.pdf)<br/>

---

## S-SAM: SVD-based Fine-Tuning of Segment Anything Model for Medical Image Segmentation<br/>
**Authors:** Paranjape, Jay N., Sikder, Shameema, Vedula, S. Swaroop, Patel, Vishal M.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0669_paper.pdf)<br/>

---

## Customized Relationship Graph Neural Network for Brain Disorder Identification<br/>
**Authors:** Xia, Zhengwang, Wang, Huan, Zhou, Tao, Jiao, Zhuqing, Lu, Jianfeng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1009_paper.pdf)<br/>

---

## TrIND: Representing Anatomical Trees by Denoising Diffusion of Implicit Neural Fields<br/>
**Authors:** Sinha, Ashish, Hamarneh, Ghassan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2477_paper.pdf)<br/>

---

## Coarse-to-Fine Latent Diffusion Model for Glaucoma Forecast on Sequential Fundus Images<br/>
**Authors:** Zhang, Yuhan, Huang, Kun, Yang, Xikai, Ma, Xiao, Wu, Jian, Wang, Ningli, Wang, Xi, Heng, Pheng-Ann<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0498_paper.pdf)<br/>

---

## [Laplacian Segmentation Networks Improve Epistemic Uncertainty Quantification](https://arxiv.org/abs/2303.13123)<br/>
**Authors:** Zepf, Kilian, Wanna, Selma, Miani, Marco, Moore, Juston, Frellsen, Jes, Hauberg, Søren, Warburg, Frederik, Feragen, Aasa<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1339_paper.pdf)<br/>
**arXiv:** [2303.13123](https://arxiv.org/abs/2303.13123)<br/>

---

## Free-SurGS: SfM-Free 3D Gaussian Splatting for Surgical Scene Reconstruction<br/>
**Authors:** Guo, Jiaxin, Wang, Jiangliu, Kang, Di, Dong, Wenzhen, Wang, Wenting, Liu, Yun-hui<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1818_paper.pdf)<br/>

---

## [Tackling Data Heterogeneity in Federated Learning via Loss Decomposition](https://huggingface.co/papers/2408.12300)<br/>
**Authors:** Zeng, Shuang, Guo, Pengxin, Wang, Shuai, Wang, Jianbo, Zhou, Yuyin, Qu, Liangqiong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1348_paper.pdf)<br/>
**arXiv:** [2408.12300](https://arxiv.org/abs/2408.12300)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2408.12300](https://huggingface.co/papers/2408.12300)<br/>

---

## [Intrapartum Ultrasound Image Segmentation of Pubic Symphysis and Fetal Head Using Dual Student-Teacher Framework with CNN-ViT Collaborative Learning](https://arxiv.org/abs/2409.06928)<br/>
**Authors:** Jiang, Jianmei, Wang, Huijin, Bai, Jieyun, Long, Shun, Chen, Shuangping, Campello, Victor M., Lekadir, Karim<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2798_paper.pdf)<br/>
**arXiv:** [2409.06928](https://arxiv.org/abs/2409.06928)<br/>

---

## Variational Field Constraint Learning for Degree of Coronary Artery Ischemia Assessment<br/>
**Authors:** Zhang, Qi, Liu, Xiujian, Zhang, Heye, Xu, Chenchu, Yang, Guang, Yuan, Yixuan, Tan, Tao, Gao, Zhifan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0134_paper.pdf)<br/>

---

## [APS-USCT: Ultrasound Computed Tomography on Sparse Data via AI-Physic Synergy](https://arxiv.org/abs/2407.14564)<br/>
**Authors:** Sheng, Yi, Wang, Hanchen, Liu, Yipei, Yang, Junhuan, Jiang, Weiwen, Lin, Youzuo, Yang, Lei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1595_paper.pdf)<br/>
**arXiv:** [2407.14564](https://arxiv.org/abs/2407.14564)<br/>

---

## Aligning Medical Images with General Knowledge from Large Language Models<br/>
**Authors:** Fang, Xiao, Lin, Yi, Zhang, Dong, Cheng, Kwang-Ting, Chen, Hao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1358_paper.pdf)<br/>

---

## [Explainable vertebral fracture analysis with uncertainty estimation using differentiable rule-based classification](https://arxiv.org/abs/2407.02926)<br/>
**Authors:** Wåhlstrand Skärström, Victor, Johansson, Lisa, Alvén, Jennifer, Lorentzon, Mattias, Häggström, Ida<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1871_paper.pdf)<br/>
**arXiv:** [2407.02926](https://arxiv.org/abs/2407.02926)<br/>

---

## VideoCutMix: Temporal Segmentation of Surgical Videos in Scarce Data Scenarios<br/>
**Authors:** Dhanakshirur, Rohan Raju, Tyagi, Mrinal, Baby, Britty, Suri, Ashish, Kalra, Prem, Arora, Chetan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3401_paper.pdf)<br/>

---

## [Low-Rank Continual Pyramid Vision Transformer: Incrementally Segment Whole-Body Organs in CT with Light-Weighted Adaptation](https://arxiv.org/abs/2410.04689)<br/>
**Authors:** Zhu, Vince, Ji, Zhanghexuan, Guo, Dazhou, Wang, Puyang, Xia, Yingda, Lu, Le, Ye, Xianghua, Zhu, Wei, Jin, Dakai<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0900_paper.pdf)<br/>
**arXiv:** [2410.04689](https://arxiv.org/abs/2410.04689)<br/>

---

## [Auxiliary Input in Training: Incorporating Catheter Features into Deep Learning Models for ECG-Free Dynamic Coronary Roadmapping](https://arxiv.org/abs/2408.15947)<br/>
**Authors:** Liu, Yikang, Zhao, Lin, Chen, Eric Z., Chen, Xiao, Chen, Terrence, Sun, Shanhui<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1135_paper.pdf)<br/>
**arXiv:** [2408.15947](https://arxiv.org/abs/2408.15947)<br/>

---

## A Clinical-oriented Lightweight Network for High-resolution Medical Image Enhancement<br/>
**Authors:** Wang, Yaqi, Chen, Leqi, Hou, Qingshan, Cao, Peng, Yang, Jinzhu, Liu, Xiaoli, Zaiane, Osmar R.<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2774_paper.pdf)<br/>

---

## [Mask-Free Neuron Concept Annotation for Interpreting Neural Networks in Medical Domain](https://arxiv.org/abs/2407.11375)<br/>
**Authors:** Kim, Hyeon Bae, Ahn, Yong Hyun, Kim, Seong Tae<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0914_paper.pdf)<br/>
**arXiv:** [2407.11375](https://arxiv.org/abs/2407.11375)<br/>

---

## [Mask-Enhanced Segment Anything Model for Tumor Lesion Semantic Segmentation](https://arxiv.org/abs/2403.05912)<br/>
**Authors:** Shi, Hairong, Han, Songhao, Huang, Shaofei, Liao, Yue, Li, Guanbin, Kong, Xiangxing, Zhu, Hua, Wang, Xiaomu, Liu, Si<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0762_paper.pdf)<br/>
**arXiv:** [2403.05912](https://arxiv.org/abs/2403.05912)<br/>

---

## Cross-Dimensional Medical Self-Supervised Representation Learning Based on a Pseudo-3D Transformation<br/>
**Authors:** Gao, Fei, Wang, Siwen, Zhang, Fandong, Zhou, Hong-Yu, Wang, Yizhou, Wang, Churan, Yu, Gang, Yu, Yizhou<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0308_paper.pdf)<br/>

---

## EchoFM: A View-Independent Echocardiogram Model for the Detection of Pulmonary Hypertension<br/>
**Authors:** Fadnavis, Shreyas, Parmar, Chaitanya, Emaminejad, Nastaran, Ulloa Cerna, Alvaro, Malik, Areez, Selej, Mona, Mansi, Tommaso, Dunnmon, Preston, Yardibi, Tarik, Standish, Kristopher, Damasceno, Pablo F.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2686_paper.pdf)<br/>

---

## Self-supervised Vision Transformer are Scalable Generative Models for Domain Generalization<br/>
**Authors:** Doerrich, Sebastian, Di Salvo, Francesco, Ledig, Christian<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0740_paper.pdf)<br/>

---

## Best of Both Modalities: Fusing CBCT and Intraoral Scan Data into a Single Tooth Image<br/>
**Authors:** Kim, SaeHyun, Choi, Yongjin, Na, Jincheol, Song, In-Seok, Lee, You-Sun, Hwang, Bo-Yeon, Lim, Ho-Kyung, Baek, Seung Jun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2796_paper.pdf)<br/>

---

## ACLNet: A Deep Learning Model for ACL Rupture Classification Combined with Bone Morphology<br/>
**Authors:** Liu, Chao, Yu, Xueqing, Wang, Dingyu, Jiang, Tingting<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3065_paper.pdf)<br/>

---

## [From Pixel to Cancer: Cellular Automata in Computed Tomography](https://arxiv.org/abs/2403.06459)<br/>
**Authors:** Lai, Yuxiang, Chen, Xiaoxi, Wang, Angtian, Yuille, Alan, Zhou, Zongwei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1596_paper.pdf)<br/>
**arXiv:** [2403.06459](https://arxiv.org/abs/2403.06459)<br/>

---

## [Training-Free Condition Video Diffusion Models for single frame Spatial-Semantic Echocardiogram Synthesis](https://arxiv.org/abs/2408.03035)<br/>
**Authors:** Nguyen, Van Phi, Luong Ha, Tri Nhan, Pham, Huy Hieu, Tran, Quoc Long<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1171_paper.pdf)<br/>
**arXiv:** [2408.03035](https://arxiv.org/abs/2408.03035)<br/>

---

## [FUNAvg: Federated Uncertainty Weighted Averaging for Datasets with Diverse Labels](https://arxiv.org/abs/2407.07488)<br/>
**Authors:** Tölle, Malte, Navarro, Fernando, Eble, Sebastian, Wolf, Ivo, Menze, Bjoern, Engelhardt, Sandy<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1396_paper.pdf)<br/>
**arXiv:** [2407.07488](https://arxiv.org/abs/2407.07488)<br/>

---

## [Diff-VPS: Video Polyp Segmentation via a Multi-task Diffusion Network with Adversarial Temporal Reasoning](https://arxiv.org/abs/2409.07238)<br/>
**Authors:** Lu, Yingling, Yang, Yijun, Xing, Zhaohu, Wang, Qiong, Zhu, Lei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1334_paper.pdf)<br/>
**arXiv:** [2409.07238](https://arxiv.org/abs/2409.07238)<br/>

---

## CP-CLIP: Core-Periphery Feature Alignment CLIP for Zero-Shot Medical Image Analysis<br/>
**Authors:** Yu, Xiaowei, Wu, Zihao, Zhang, Lu, Zhang, Jing, Lyu, Yanjun, Zhu, Dajiang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3750_paper.pdf)<br/>

---

## [FD-SOS: Vision-Language Open-Set Detectors for Bone Fenestration and Dehiscence Detection from Intraoral Images](https://arxiv.org/abs/2407.09088)<br/>
**Authors:** Elbatel, Marawan, Liu, Keyuan, Yang, Yanqi, Li, Xiaomeng<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0234_paper.pdf)<br/>
**arXiv:** [2407.09088](https://arxiv.org/abs/2407.09088)<br/>

---

## Gradient Guided Co-Retention Feature Pyramid Network for LDCT Image Denoising<br/>
**Authors:** Zhou, Li, Wang, Dayang, Xu, Yongshun, Han, Shuo, Morovati, Bahareh, Fan, Shuyi, Yu, Hengyong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3737_paper.pdf)<br/>

---

## Anatomy-Aware Gating Network for Explainable Alzheimer’s Disease Diagnosis<br/>
**Authors:** Jiang, Hongchao, Miao, Chunyan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2553_paper.pdf)<br/>

---

## [Diffusion Models with Implicit Guidance for Medical Anomaly Detection](https://arxiv.org/abs/2403.08464)<br/>
**Authors:** Bercea, Cosmin I., Wiestler, Benedikt, Rueckert, Daniel, Schnabel, Julia A.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1315_paper.pdf)<br/>
**arXiv:** [2403.08464](https://arxiv.org/abs/2403.08464)<br/>

---

## [TSBP: Improving Object Detection in Histology Images via Test-time Self-guided Bounding-box Propagation](https://arxiv.org/abs/2409.16678)<br/>
**Authors:** Yang, Tingting, Xiao, Liang, Zhang, Yizhe<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1242_paper.pdf)<br/>
**arXiv:** [2409.16678](https://arxiv.org/abs/2409.16678)<br/>

---

## [A Large-scale Multi Domain Leukemia Dataset for the White Blood Cells Detection with Morphological Attributes for Explainability](https://arxiv.org/abs/2405.10803)<br/>
**Authors:** Rehman, Abdul, Meraj, Talha, Minhas, Aiman Mahmood, Imran, Ayisha, Ali, Mohsen, Sultani, Waqas<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/4180_paper.pdf)<br/>
**arXiv:** [2405.10803](https://arxiv.org/abs/2405.10803)<br/>

---

## Few-Shot Lymph Node Metastasis Classification Meets High Performance on Whole Slide Images via the Informative Non-Parametric Classifier<br/>
**Authors:** Li, Yi, Zhang, Qixiang, Xiang, Tianqi, Lin, Yiqun, Zhang, Qingling, Li, Xiaomeng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2187_paper.pdf)<br/>

---

## [Prompting Segment Anything Model with Domain-Adaptive Prototype for Generalizable Medical Image Segmentation](https://arxiv.org/abs/2409.12522)<br/>
**Authors:** Wei, Zhikai, Dong, Wenhui, Zhou, Peilin, Gu, Yuliang, Zhao, Zhou, Xu, Yongchao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0929_paper.pdf)<br/>
**arXiv:** [2409.12522](https://arxiv.org/abs/2409.12522)<br/>

---

## [BGF-YOLO: Enhanced YOLOv8 with Multiscale Attentional Feature Fusion for Brain Tumor Detection](https://huggingface.co/papers/2309.12585)<br/>
**Authors:** Kang, Ming, Ting, Chee-Ming, Ting, Fung Fung, Phan, Raphaël C.-W.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0908_paper.pdf)<br/>
**arXiv:** [2309.12585](https://arxiv.org/abs/2309.12585)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2309.12585](https://huggingface.co/papers/2309.12585)<br/>

---

## I2Net: Exploiting Misaligned Contexts Orthogonally with Implicit-Parameterized Implicit Functions for Medical Image Segmentation<br/>
**Authors:** Yu, Jiahao, Duan, Fan, Chen, Li<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1184_paper.pdf)<br/>

---

## [EndoSparse: Real-Time Sparse View Synthesis of Endoscopic Scenes using Gaussian Splatting](https://arxiv.org/abs/2407.01029)<br/>
**Authors:** Li, Chenxin, Feng, Brandon Y., Liu, Yifan, Liu, Hengyu, Wang, Cheng, Yu, Weihao, Yuan, Yixuan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0791_paper.pdf)<br/>
**arXiv:** [2407.01029](https://arxiv.org/abs/2407.01029)<br/>

---

## [Surgformer: Surgical Transformer with Hierarchical Temporal Attention for Surgical Phase Recognition](https://arxiv.org/abs/2408.03867)<br/>
**Authors:** Yang, Shu, Luo, Luyang, Wang, Qiong, Chen, Hao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1220_paper.pdf)<br/>
**arXiv:** [2408.03867](https://arxiv.org/abs/2408.03867)<br/>

---

## [Deep Learning for Cancer Prognosis Prediction Using Portrait Photos by StyleGAN Embedding](https://arxiv.org/abs/2306.14596)<br/>
**Authors:** Hagag, Amr, Gomaa, Ahmed, Kornek, Dominik, Maier, Andreas, Fietkau, Rainer, Bert, Christoph, Huang, Yixing, Putz, Florian<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0658_paper.pdf)<br/>
**arXiv:** [2306.14596](https://arxiv.org/abs/2306.14596)<br/>

---

## Training ViT with Limited Data for Alzheimer’s Disease Classification: an Empirical Study<br/>
**Authors:** Kunanbayev, Kassymzhomart, Shen, Vyacheslav, Kim, Dae-Shik<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2724_paper.pdf)<br/>

---

## ORacle: Large Vision-Language Models for Knowledge-Guided Holistic OR Domain Modeling<br/>
**Authors:** Özsoy, Ege, Pellegrini, Chantal, Keicher, Matthias, Navab, Nassir<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0311_paper.pdf)<br/>

---

## [Jumpstarting Surgical Computer Vision](https://arxiv.org/abs/2312.05968)<br/>
**Authors:** Alapatt, Deepak, Murali, Aditya, Srivastav, Vinkle, AI4SafeChole Consortium, Mascagni, Pietro, Padoy, Nicolas<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1998_paper.pdf)<br/>
**arXiv:** [2312.05968](https://arxiv.org/abs/2312.05968)<br/>

---

## [Let Me DeCode You: Decoder Conditioning with Tabular Data](https://arxiv.org/abs/2407.09437)<br/>
**Authors:** Szczepański, Tomasz, Grzeszczyk, Michal K., Płotka, Szymon, Adamowicz, Arleta, Fudalej, Piotr, Korzeniowski, Przemysław, Trzciński, Tomasz, Sitek, Arkadiusz<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3398_paper.pdf)<br/>
**arXiv:** [2407.09437](https://arxiv.org/abs/2407.09437)<br/>

---

## Structure-preserving Image Translation for Depth Estimation in Colonoscopy<br/>
**Authors:** Wang, Shuxian, Paruchuri, Akshay, Zhang, Zhaoxi, McGill, Sarah, Sengupta, Roni<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1520_paper.pdf)<br/>

---

## [Dynamic Position Transformation and Boundary Refinement Network for Left Atrial Segmentation](https://arxiv.org/abs/2407.05505)<br/>
**Authors:** Xu, Fangqiang, Tu, Wenxuan, Feng, Fan, Gunawardhana, Malitha, Yang, Jiayuan, Gu, Yun, Zhao, Jichao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0950_paper.pdf)<br/>
**arXiv:** [2407.05505](https://arxiv.org/abs/2407.05505)<br/>

---

## [uniGradICON: A Foundation Model for Medical Image Registration](https://arxiv.org/abs/2403.05780)<br/>
**Authors:** Tian, Lin, Greer, Hastings, Kwitt, Roland, Vialard, François-Xavier, San José Estépar, Raúl, Bouix, Sylvain, Rushmore, Richard, Niethammer, Marc<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0527_paper.pdf)<br/>
**arXiv:** [2403.05780](https://arxiv.org/abs/2403.05780)<br/>

---

## Enhancing Federated Learning Performance Fairness via Collaboration Graph-based Reinforcement Learning<br/>
**Authors:** Xia, Yuexuan, Ma, Benteng, Dou, Qi, Xia, Yong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0845_paper.pdf)<br/>

---

## LM-UNet: Whole-body PET-CT Lesion Segmentation with Dual-Modality-based Annotations Driven by Latent Mamba U-Net<br/>
**Authors:** Liu, Anglin, Jia, Dengqiang, Sun, Kaicong, Meng, Runqi, Zhao, Meixin, Jiang, Yongluo, Dong, Zhijian, Gao, Yaozong, Shen, Dinggang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1851_paper.pdf)<br/>

---

## FairQuantize: Achieving Fairness Through Weight Quantization for Dermatological Disease Diagnosis<br/>
**Authors:** Guo, Yuanbo, Jia, Zhenge, Hu, Jingtong, Shi, Yiyu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3697_paper.pdf)<br/>

---

## [FissionFusion: Fast Geometric Generation and Hierarchical Souping for Medical Image Analysis](https://arxiv.org/abs/2403.13341)<br/>
**Authors:** Sanjeev, Santosh, Zhaksylyk, Nuren, Almakky, Ibrahim, Hashmi, Anees Ur Rehman, Qazi, Mohammad Areeb, Yaqub, Mohammad<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3154_paper.pdf)<br/>
**arXiv:** [2403.13341](https://arxiv.org/abs/2403.13341)<br/>

---

## 3DGPS: A 3D Differentiable-Gaussian-based Planning Strategy for Liver Tumor Cryoablation<br/>
**Authors:** Wang, Ce, Huang, Xiaoyu, Kong, Yaqing, Li, Qian, Hao, You, Zhou, Xiang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0132_paper.pdf)<br/>

---

## [SRE-CNN: A Spatiotemporal Rotation-Equivariant CNN for Cardiac Cine MR Imaging](https://arxiv.org/abs/2409.08537)<br/>
**Authors:** Zhu, Yuliang, Cheng, Jing, Cui, Zhuo-Xu, Ren, Jianfeng, Wang, Chengbo, Liang, Dong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0893_paper.pdf)<br/>
**arXiv:** [2409.08537](https://arxiv.org/abs/2409.08537)<br/>

---

## MultiVarNet - Predicting Tumour Mutational status at the Protein Level<br/>
**Authors:** Morel, Louis-Oscar, Muzammel, Muhammad, Vinçon, Nathan, Derangère, Valentin, Ladoire, Sylvain, Rittscher, Jens<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3289_paper.pdf)<br/>

---

## Myocardial Scar Enhancement in LGE Cardiac MRI using Localized Diffusion<br/>
**Authors:** Hasny, Marta, Demirel, Omer B., Amyar, Amine, Faghihroohi, Shahrooz, Nezafat, Reza<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3611_paper.pdf)<br/>

---

## [Efficient In-Context Medical Segmentation with Meta-driven Visual Prompt Selection](https://arxiv.org/abs/2407.11188)<br/>
**Authors:** Wu, Chenwei, Restrepo, David, Shuai, Zitao, Liu, Zhongming, Shen, Liyue<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3444_paper.pdf)<br/>
**arXiv:** [2407.11188](https://arxiv.org/abs/2407.11188)<br/>

---

## Interpretable-by-design Deep Survival Analysis for Disease Progression Modeling<br/>
**Authors:** Gervelmeyer, Julius, Müller, Sarah, Djoumessi, Kerol, Merle, David, Clark, Simon J., Koch, Lisa, Berens, Philipp<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1325_paper.pdf)<br/>

---

## [Spatio-temporal neural distance fields for conditional generative modeling of the heart](https://arxiv.org/abs/2407.10663)<br/>
**Authors:** Sørensen, Kristine, Diez, Paula, Margeta, Jan, El Youssef, Yasmin, Pham, Michael, Pedersen, Jonas Jalili, Kühl, Tobias, de Backer, Ole, Kofoed, Klaus, Camara, Oscar, Paulsen, Rasmus<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1946_paper.pdf)<br/>
**arXiv:** [2407.10663](https://arxiv.org/abs/2407.10663)<br/>

---

## A Universal and Flexible Framework for Unsupervised Statistical Shape Model Learning<br/>
**Authors:** El Amrani, Nafie, Cao, Dongliang, Bernard, Florian<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1005_paper.pdf)<br/>

---

## Towards Precise Pose Estimation in Robotic Surgery: Introducing Occlusion-Aware Loss<br/>
**Authors:** Park, Jihun, Hong, Jiuk, Yoon, Jihun, Park, Bokyung, Choi, Min-Kook, Jung, Heechul<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0338_paper.pdf)<br/>

---

## Ocular Stethoscope: Auditory Support for Retinal Membrane Peeling<br/>
**Authors:** Matinfar, Sasan, Dehghani, Shervin, Sommersperger, Michael, Faridpooya, Koorosh, Fairhurst, Merle, Navab, Nassir<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3700_paper.pdf)<br/>

---

## IM-MoCo: Self-supervised MRI Motion Correction using Motion-Guided Implicit Neural Representations<br/>
**Authors:** Al-Haj Hemidi, Ziad, Weihsbach, Christian, Heinrich, Mattias P.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3212_paper.pdf)<br/>

---

## SpeChrOmics: A Biomarker Characterization Framework for Medical Hyperspectral Imaging<br/>
**Authors:** Oladokun, Ajibola S., Malila, Bessie, Campello, Victor M., Shey, Muki, Mutsvangwa, Tinashe E. M.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1551_paper.pdf)<br/>

---

## [Evaluating the Fairness of Neural Collapse in Medical Image Classification](https://arxiv.org/abs/2407.05843)<br/>
**Authors:** Mouheb, Kaouther, Elbatel, Marawan, Klein, Stefan, Bron, Esther E.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3085_paper.pdf)<br/>
**arXiv:** [2407.05843](https://arxiv.org/abs/2407.05843)<br/>

---

## PAMIL: Prototype Attention-based Multiple Instance Learning for Whole Slide Image Classification<br/>
**Authors:** Liu, Jiashuai, Mao, Anyu, Niu, Yi, Zhang, Xianli, Gong, Tieliang, Li, Chen, Gao, Zeyu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1022_paper.pdf)<br/>

---

## [PitVQA: Image-grounded Text Embedding LLM for Visual Question Answering in Pituitary Surgery](https://arxiv.org/abs/2405.13949)<br/>
**Authors:** He, Runlong, Xu, Mengya, Das, Adrito, Khan, Danyal Z., Bano, Sophia, Marcus, Hani J., Stoyanov, Danail, Clarkson, Matthew J., Islam, Mobarakol<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3403_paper.pdf)<br/>
**arXiv:** [2405.13949](https://arxiv.org/abs/2405.13949)<br/>

---

## Representing Functional Connectivity with Structural Detour: A New Perspective to Decipher Structure-Function Coupling Mechanism<br/>
**Authors:** Wei, Ziquan, Dan, Tingting, Ding, Jiaqi, Laurienti, Paul, Wu, Guorong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1549_paper.pdf)<br/>

---

## [Heteroscedastic Uncertainty Estimation Framework for Unsupervised Registration](https://arxiv.org/abs/2312.00836)<br/>
**Authors:** Zhang, Xiaoran, Pak, Daniel H., Ahn, Shawn S., Li, Xiaoxiao, You, Chenyu, Staib, Lawrence H., Sinusas, Albert J., Wong, Alex, Duncan, James S.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1085_paper.pdf)<br/>
**arXiv:** [2312.00836](https://arxiv.org/abs/2312.00836)<br/>

---

## A New Cine-MRI Segmentation Method of Tongue Dorsum for Postoperative Swallowing Function Analysis<br/>
**Authors:** Sun, Minghao, Zhou, Tian, Jiang, Chenghui, Lv, Xiaodan, Yu, Han<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2715_paper.pdf)<br/>

---

## High-resolution Medical Image Translation via Patch Alignment-Based Bidirectional Contrastive Learning<br/>
**Authors:** Zhang, Wei, Hui, Tik Ho, Tse, Pui Ying, Hill, Fraser, Lau, Condon, Li, Xinyue<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0817_paper.pdf)<br/>

---

## Analyzing Adjacent B-Scans to Localize Sickle Cell Retinopathy In OCTs<br/>
**Authors:** Bhattarai, Ashuta, Jin, Jing, Kambhamettu, Chandra<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3665_paper.pdf)<br/>

---

## Gaussian Pancakes: Geometrically-Regularized 3D Gaussian Splatting for Realistic Endoscopic Reconstruction<br/>
**Authors:** Bonilla, Sierra, Zhang, Shuai, Psychogyios, Dimitrios, Stoyanov, Danail, Vasconcelos, Francisco, Bano, Sophia<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2298_paper.pdf)<br/>

---

## LOMIA-T: A Transformer-based LOngitudinal Medical Image Analysis framework for predicting treatment response of esophageal cancer<br/>
**Authors:** Sun, Yuchen, Li, Kunwei, Chen, Duanduan, Hu, Yi, Zhang, Shuaitong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2565_paper.pdf)<br/>

---

## FairDiff: Fair Segmentation with Point-Image Diffusion<br/>
**Authors:** Li, Wenyi, Xu, Haoran, Zhang, Guiyu, Gao, Huan-ang, Gao, Mingju, Wang, Mengyu, Zhao, Hao<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3105_paper.pdf)<br/>

---

## [Epicardium Prompt-guided Real-time Cardiac Ultrasound Frame-to-volume Registration](https://arxiv.org/abs/2406.14534)<br/>
**Authors:** Lei, Long, Zhou, Jun, Pei, Jialun, Zhao, Baoliang, Jin, Yueming, Teoh, Yuen-Chun Jeremy, Qin, Jing, Heng, Pheng-Ann<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0300_paper.pdf)<br/>
**arXiv:** [2406.14534](https://arxiv.org/abs/2406.14534)<br/>

---

## Enhancing Gene Expression Prediction from Histology Images with Spatial Transcriptomics Completion<br/>
**Authors:** Mejia, Gabriel, Ruiz, Daniela, Cárdenas, Paula, Manrique, Leonardo, Vega, Daniela, Arbeláez, Pablo<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2459_paper.pdf)<br/>

---

## [BackMix: Mitigating Shortcut Learning in Echocardiography with Minimal Supervision](https://arxiv.org/abs/2406.19148)<br/>
**Authors:** Bransby, Kit M., Beqiri, Arian, Cho Kim, Woo-Jin, Oliveira, Jorge, Chartsias, Agisilaos, Gomez, Alberto<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2248_paper.pdf)<br/>
**arXiv:** [2406.19148](https://arxiv.org/abs/2406.19148)<br/>

---

## Boosting FFPE-to-HE Virtual Staining with Cell Semantics from Pretrained Segmentation Model<br/>
**Authors:** Hu, Yihuang, Peng, Qiong, Du, Zhicheng, Zhang, Guojun, Wu, Huisi, Liu, Jingxin, Chen, Hao, Wang, Liansheng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3335_paper.pdf)<br/>

---

## Baikal: Unpaired Denoising of Fluorescence Microscopy Images using Diffusion Models<br/>
**Authors:** Chaudhary, Shivesh, Sankarapandian, Sivaramakrishnan, Sooknah, Matt, Pai, Joy, McCue, Caroline, Chen, Zhenghao, Xu, Jun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3885_paper.pdf)<br/>

---

## On-the-Fly Guidance Training for Medical Image Registration<br/>
**Authors:** Xin, Yuelin, Chen, Yicheng, Ji, Shengxiang, Han, Kun, Xie, Xiaohui<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0519_paper.pdf)<br/>

---

## [Multi-modal Data Binding for Survival Analysis Modeling with Incomplete Data and Annotations](https://arxiv.org/abs/2407.17726)<br/>
**Authors:** Qu, Linhao, Huang, Dan, Zhang, Shaoting, Wang, Xiaosong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0334_paper.pdf)<br/>
**arXiv:** [2407.17726](https://arxiv.org/abs/2407.17726)<br/>

---

## Learning a Clinically-Relevant Concept Bottleneck for Lesion Detection in Breast Ultrasound<br/>
**Authors:** Bunnell, Arianna, Glaser, Yannik, Valdez, Dustin, Wolfgruber, Thomas, Altamirano, Aleen, Zamora González, Carol, Hernandez, Brenda Y., Sadowski, Peter, Shepherd, John A.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/4008_paper.pdf)<br/>

---

## Hallucinated Style Distillation for Single Domain Generalization in Medical Image Segmentation<br/>
**Authors:** Yi, Jingjun, Bi, Qi, Zheng, Hao, Zhan, Haolan, Ji, Wei, Huang, Yawen, Li, Shaoxin, Li, Yuexiang, Zheng, Yefeng, Huang, Feiyue<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3893_paper.pdf)<br/>

---

## [Rethinking Autoencoders for Medical Anomaly Detection from A Theoretical Perspective](https://arxiv.org/abs/2403.09303)<br/>
**Authors:** Cai, Yu, Chen, Hao, Cheng, Kwang-Ting<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0616_paper.pdf)<br/>
**arXiv:** [2403.09303](https://arxiv.org/abs/2403.09303)<br/>

---

## [CINA: Conditional Implicit Neural Atlas for Spatio-Temporal Representation of Fetal Brains](https://arxiv.org/abs/2403.08550)<br/>
**Authors:** Dannecker, Maik, Kyriakopoulou, Vanessa, Cordero-Grande, Lucilio, Price, Anthony N., Hajnal, Joseph V., Rueckert, Daniel<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2095_paper.pdf)<br/>
**arXiv:** [2403.08550](https://arxiv.org/abs/2403.08550)<br/>

---

## [Average Calibration Error: A Differentiable Loss for Improved Reliability in Image Segmentation](https://arxiv.org/abs/2403.06759)<br/>
**Authors:** Barfoot, Theodore, Garcia Peraza Herrera, Luis C., Glocker, Ben, Vercauteren, Tom<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3075_paper.pdf)<br/>
**arXiv:** [2403.06759](https://arxiv.org/abs/2403.06759)<br/>

---

## Quantitative Assessment of Thyroid Nodules through Ultrasound Imaging Analysis<br/>
**Authors:** Kim, Young-Min, Kim, Myeong-Gee, Oh, Seok-Hwan, Jung, Guil, Lee, Hyeon-Jik, Kim, Sang-Yun, Kwon, Hyuk-Sool, Choi, Sang-Il, Bae, Hyeon-Min<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0306_paper.pdf)<br/>

---

## [An Organism Starts with a Single Pix-Cell: A Neural Cellular Diffusion for High-Resolution Image Synthesis](https://arxiv.org/abs/2407.03018)<br/>
**Authors:** Elbatel, Marawan, Kamnitsas, Konstantinos, Li, Xiaomeng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0233_paper.pdf)<br/>
**arXiv:** [2407.03018](https://arxiv.org/abs/2407.03018)<br/>

---

## [PULPo: Probabilistic Unsupervised Laplacian Pyramid Registration](https://arxiv.org/abs/2407.10567)<br/>
**Authors:** Siegert, Leonard, Fischer, Paul, Heinrich, Mattias P., Baumgartner, Christian F.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1433_paper.pdf)<br/>
**arXiv:** [2407.10567](https://arxiv.org/abs/2407.10567)<br/>

---

## [FedMLP: Federated Multi-Label Medical Image Classification under Task Heterogeneity](https://arxiv.org/abs/2406.18995)<br/>
**Authors:** Sun, Zhaobin, Wu, Nannan, Shi, Junjie, Yu, Li, Cheng, Kwang-Ting, Yan, Zengqiang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1176_paper.pdf)<br/>
**arXiv:** [2406.18995](https://arxiv.org/abs/2406.18995)<br/>

---

## Ultrasound Image-to-Video Synthesis via Latent Dynamic Diffusion Models<br/>
**Authors:** Chen, Tingxiu, Shi, Yilei, Zheng, Zixuan, Yan, Bingcong, Hu, Jingliang, Zhu, Xiao Xiang, Mou, Lichao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3070_paper.pdf)<br/>

---

## [Sparsity- and Hybridity-Inspired Visual Parameter-Efficient Fine-Tuning for Medical Diagnosis](https://arxiv.org/abs/2405.17877)<br/>
**Authors:** Liu, Mingyuan, Xu, Lu, Liu, Shengnan, Zhang, Jicong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1676_paper.pdf)<br/>
**arXiv:** [2405.17877](https://arxiv.org/abs/2405.17877)<br/>

---

## [7T MRI Synthesization from 3T Acquisitions](https://arxiv.org/abs/2403.08979)<br/>
**Authors:** Cui, Qiming, Tosun, Duygu, Mukherjee, Pratik, Abbasi-Asl, Reza<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3648_paper.pdf)<br/>
**arXiv:** [2403.08979](https://arxiv.org/abs/2403.08979)<br/>

---

## Towards a Deeper insight into Face Detection in Neonatal wards<br/>
**Authors:** Zhao, Yisheng, Zhu, Huaiyu, Shu, Qi, Huan, Ruohong, Chen, Shuohui, Pan, Yun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2862_paper.pdf)<br/>

---

## Diffusion-Enhanced Transformation Consistency Learning for Retinal Image Segmentation<br/>
**Authors:** Li, Xiang, Fang, Huihui, Liu, Mingsi, Xu, Yanwu, Duan, Lixin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1467_paper.pdf)<br/>

---

## [Pose-GuideNet: Automatic Scanning Guidance for Fetal Head Ultrasound from Pose Estimation](https://arxiv.org/abs/2408.09931)<br/>
**Authors:** Men, Qianhui, Guo, Xiaoqing, Papageorghiou, Aris T., Noble, J. Alison<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3555_paper.pdf)<br/>
**arXiv:** [2408.09931](https://arxiv.org/abs/2408.09931)<br/>

---

## Explanation-driven Cyclic Learning for High-Quality Brain MRI Reconstruction from Unknown Degradation<br/>
**Authors:** Jiang, Ning, Huang, Zhengyong, Sui, Yao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2315_paper.pdf)<br/>

---

## k-t Self-Consistency Diffusion: A Physics-Informed Model for Dynamic MR Imaging<br/>
**Authors:** Liu, Ye, Cui, Zhuo-Xu, Sun, Kaicong, Zhao, Ting, Cheng, Jing, Zhu, Yuliang, Shen, Dinggang, Liang, Dong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3796_paper.pdf)<br/>

---

## Large-Scale 3D Infant Face Model<br/>
**Authors:** Schnabel, Till N., Lill, Yoriko, Benitez, Benito K., Nalabothu, Prasad, Metzler, Philipp, Mueller, Andreas A., Gross, Markus, Gözcü, Baran, Solenthaler, Barbara<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2260_paper.pdf)<br/>

---

## DeSAM: Decoupled Segment Anything Model for Generalizable Medical Image Segmentation<br/>
**Authors:** Gao, Yifan, Xia, Wei, Hu, Dingdu, Wang, Wenkui, Gao, Xin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1496_paper.pdf)<br/>

---

## [Brain-Shift: Unsupervised Pseudo-Healthy Brain Synthesis for Novel Biomarker Extraction in Chronic Subdural Hematoma](https://arxiv.org/abs/2403.19415)<br/>
**Authors:** Imre, Baris, Thibeau-Sutre, Elina, Reimer, Jorieke, Kho, Kuan, Wolterink, Jelmer M.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1955_paper.pdf)<br/>
**arXiv:** [2403.19415](https://arxiv.org/abs/2403.19415)<br/>

---

## Novelty Detection Based Discriminative Multiple Instance Feature Mining to Classify NSCLC PD-L1 Status on HE-Stained Histopathological Images<br/>
**Authors:** Xu, Rui, Yu, Dan, Yang, Xuan, Ye, Xinchen, Wang, Zhihui, Wang, Yi, Wang, Hongkai, Li, Haojie, Huang, Dingpin, Xu, Fangyi, Gan, Yi, Tu, Yuan, Hu, Hongjie<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2571_paper.pdf)<br/>

---

## QueryNet: A Unified Framework for Accurate Polyp Segmentation and Detection<br/>
**Authors:** Chai, Jiaxing, Luo, Zhiming, Gao, Jianzhe, Dai, Licun, Lai, Yingxin, Li, Shaozi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1037_paper.pdf)<br/>

---

## Are We Ready for Out-of-Distribution Detection in Digital Pathology?<br/>
**Authors:** Oh, Ji-Hun, Falahkheirkhah, Kianoush, Bhargava, Rohit<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2427_paper.pdf)<br/>

---

## [Reprogramming Distillation for Medical Foundation Models](https://arxiv.org/abs/2407.06504)<br/>
**Authors:** Zhou, Yuhang, Du, Siyuan, Li, Haolin, Yao, Jiangchao, Zhang, Ya, Wang, Yanfeng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0912_paper.pdf)<br/>
**arXiv:** [2407.06504](https://arxiv.org/abs/2407.06504)<br/>

---

## [Spatiotemporal Graph Neural Network Modelling Perfusion MRI](https://arxiv.org/abs/2406.06434)<br/>
**Authors:** Yan, Ruodan, Schönlieb, Carola-Bibiane, Li, Chao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1068_paper.pdf)<br/>
**arXiv:** [2406.06434](https://arxiv.org/abs/2406.06434)<br/>

---

## nnU-Net Revisited: A Call for Rigorous Validation in 3D Medical Image Segmentation<br/>
**Authors:** Isensee, Fabian, Wald, Tassilo, Ulrich, Constantin, Baumgartner, Michael, Roy, Saikat, Maier-Hein, Klaus, Jäger, Paul F.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2847_paper.pdf)<br/>

---

## A Region-Based Approach to Diabetic Retinopathy Classification with Superpixel Tokenization<br/>
**Authors:** Playout, Clément, Legault, Zacharie, Duval, Renaud, Boucher, Marie Carole, Cheriet, Farida<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3756_paper.pdf)<br/>

---

## MGDR: Multi-Modal Graph Disentangled Representation for Brain Disease Prediction<br/>
**Authors:** Jiang, Bo, Li, Yapeng, Wan, Xixi, Chen, Yuan, Tu, Zhengzheng, Zhao, Yumiao, Tang, Jin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2494_paper.pdf)<br/>

---

## Weakly Supervised Tooth Instance Segmentation on 3D Dental Models with Multi-Label Learning<br/>
**Authors:** Wang, Haoyu, Li, Kehan, Zhu, Jihua, Wang, Fan, Lian, Chunfeng, Ma, Jianhua<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1757_paper.pdf)<br/>

---

## [Progressive Growing of Patch Size: Resource-Efficient Curriculum Learning for Dense Prediction Tasks](https://arxiv.org/abs/2407.07853)<br/>
**Authors:** Fischer, Stefan M., Felsner, Lina, Osuala, Richard, Kiechle, Johannes, Lang, Daniel M., Peeken, Jan C., Schnabel, Julia A.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2008_paper.pdf)<br/>
**arXiv:** [2407.07853](https://arxiv.org/abs/2407.07853)<br/>

---

## [CT2Rep: Automated Radiology Report Generation for 3D Medical Imaging](https://arxiv.org/abs/2403.06801)<br/>
**Authors:** Hamamci, Ibrahim Ethem, Er, Sezgin, Menze, Bjoern<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2185_paper.pdf)<br/>
**arXiv:** [2403.06801](https://arxiv.org/abs/2403.06801)<br/>

---

## [DiffRect: Latent Diffusion Label Rectification for Semi-supervised Medical Image Segmentation](https://arxiv.org/abs/2407.09918)<br/>
**Authors:** Liu, Xinyu, Li, Wuyang, Yuan, Yixuan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3391_paper.pdf)<br/>
**arXiv:** [2407.09918](https://arxiv.org/abs/2407.09918)<br/>

---

## [TractOracle: towards an anatomically-informed reward function for RL-based tractography](https://arxiv.org/abs/2403.17845)<br/>
**Authors:** Théberge, Antoine, Descoteaux, Maxime, Jodoin, Pierre-Marc<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1898_paper.pdf)<br/>
**arXiv:** [2403.17845](https://arxiv.org/abs/2403.17845)<br/>

---

## [Longitudinal Mammogram Risk Prediction](https://arxiv.org/abs/2404.19083)<br/>
**Authors:** Karaman, Batuhan K., Dodelzon, Katerina, Akar, Gozde B., Sabuncu, Mert R.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3369_paper.pdf)<br/>
**arXiv:** [2404.19083](https://arxiv.org/abs/2404.19083)<br/>

---

## AcneAI: A new acne severity assessment method using digital images and deep learning<br/>
**Authors:** Gazeau, Léa, Nguyen, Hang, Nguyen, Zung, Lebedeva, Mariia, Nguyen, Thanh, To, Tat-Dat, Le Digabel, Jimmy, Filiol, Jérome, Josse, Gwendal, Perlis, Clifford, Wolfe, Jonathan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2216_paper.pdf)<br/>

---

## [Enhancing Gait Video Analysis in Neurodegenerative Diseases by Knowledge Augmentation in Vision Language Model](https://arxiv.org/abs/2403.13756)<br/>
**Authors:** Wang, Diwei, Yuan, Kun, Muller, Candice, Blanc, Frédéric, Padoy, Nicolas, Seo, Hyewon<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2283_paper.pdf)<br/>
**arXiv:** [2403.13756](https://arxiv.org/abs/2403.13756)<br/>

---

## Fine-grained Context and Multi-modal Alignment for Freehand 3D Ultrasound Reconstruction<br/>
**Authors:** Yan, Zhongnuo, Yang, Xin, Luo, Mingyuan, Chen, Jiongquan, Chen, Rusi, Liu, Lian, Ni, Dong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2611_paper.pdf)<br/>

---

## [Gaze-DETR: Using Expert Gaze to Reduce False Positives in Vulvovaginal Candidiasis Screening](https://arxiv.org/abs/2405.09463)<br/>
**Authors:** Kong, Yan, Wang, Sheng, Cai, Jiangdong, Zhao, Zihao, Shen, Zhenrong, Li, Yonghao, Fei, Manman, Wang, Qian<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0974_paper.pdf)<br/>
**arXiv:** [2405.09463](https://arxiv.org/abs/2405.09463)<br/>

---

## IOSSAM: Label Efficient Multi-View Prompt-Driven Tooth Segmentation<br/>
**Authors:** Huang, Xinrui, He, Dongming, Li, Zhenming, Zhang, Xiaofan, Wang, Xudong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2519_paper.pdf)<br/>

---

## [Centerline Boundary Dice Loss for Vascular Segmentation](https://arxiv.org/abs/2407.01517)<br/>
**Authors:** Shi, Pengcheng, Hu, Jiesi, Yang, Yanwu, Gao, Zilve, Liu, Wei, Ma, Ting<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0458_paper.pdf)<br/>
**arXiv:** [2407.01517](https://arxiv.org/abs/2407.01517)<br/>

---

## Two Projections Suffice for Cerebral Vascular Reconstruction<br/>
**Authors:** Cafaro, Alexandre, Dorent, Reuben, Haouchine, Nazim, Lepetit, Vincent, Paragios, Nikos, Wells III, William M., Frisken, Sarah<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1481_paper.pdf)<br/>

---

## Conditional Diffusion Model for Versatile Temporal Inpainting in 4D Cerebral CT Perfusion Imaging<br/>
**Authors:** Bae, Juyoung, Tong, Elizabeth, Chen, Hao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3196_paper.pdf)<br/>

---

## SAM Guided Task-Specific Enhanced Nuclei Segmentation in Digital Pathology<br/>
**Authors:** Swain, Bishal R., Cheoi, Kyung J., Ko, Jaepil<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3533_paper.pdf)<br/>

---

## Multi-category Graph Reasoning for Multi-modal Brain Tumor Segmentation<br/>
**Authors:** Li, Dongzhe, Yang, Baoyao, Zhan, Weide, He, Xiaochen<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1255_paper.pdf)<br/>

---

## Enhancing New Multiple Sclerosis Lesion Segmentation via Self-supervised Pre-training and Synthetic Lesion Integration<br/>
**Authors:** Tahghighi, Peyman, Zhang, Yunyan, Souza, Roberto, Komeili, Amin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0920_paper.pdf)<br/>

---

## Symptom Disentanglement in Chest X-ray Images for Fine-Grained Progression Learning<br/>
**Authors:** Zhu, Ye, Xu, Jingwen, Lyu, Fei, Yuen, Pong C.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3074_paper.pdf)<br/>

---

## [SAM-Med3D-MoE: Towards a Non-Forgetting Segment Anything Model via Mixture of Experts for 3D Medical Image Segmentation](https://arxiv.org/abs/2407.04938)<br/>
**Authors:** Wang, Guoan, Ye, Jin, Cheng, Junlong, Li, Tianbin, Chen, Zhaolin, Cai, Jianfei, He, Junjun, Zhuang, Bohan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3979_paper.pdf)<br/>
**arXiv:** [2407.04938](https://arxiv.org/abs/2407.04938)<br/>

---

## Synchronous Image-Label Diffusion with Anisotropic Noise for Stroke Lesion Segmentation on Non-contrast CT<br/>
**Authors:** Zhang, Jianhai, Wan, Tonghua, MacDonald, M. Ethan, Menon, Bijoy K., Qiu, Wu, Ganesh, Aravind<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1208_paper.pdf)<br/>

---

## DiffExplainer: Unveiling Black Box Models Via Counterfactual Generation<br/>
**Authors:** Fang, Yingying, Wu, Shuang, Jin, Zihao, Wang, Shiyi, Xu, Caiwen, Walsh, Simon, Yang, Guang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0078_paper.pdf)<br/>

---

## Class-aware Mutual Mixup with Triple Alignments for Semi-Supervised Cross-domain Segmentation<br/>
**Authors:** Cai, Zhuotong, Xin, Jingmin, Zeng, Tianyi, Dong, Siyuan, Zheng, Nanning, Duncan, James S.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0494_paper.pdf)<br/>

---

## [Transferring Relative Monocular Depth to Surgical Vision with Temporal Consistency](https://arxiv.org/abs/2403.06683)<br/>
**Authors:** Budd, Charlie, Vercauteren, Tom<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1332_paper.pdf)<br/>
**arXiv:** [2403.06683](https://arxiv.org/abs/2403.06683)<br/>

---

## A Novel Adaptive Hypergraph Neural Network for Enhancing Medical Image Segmentation<br/>
**Authors:** Chai, Shurong, Jain, Rahul K., Mo, Shaocong, Liu, Jiaqing, Yang, Yulin, Li, Yinhao, Tateyama, Tomoko, Lin, Lanfen, Chen, Yen-Wei<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2689_paper.pdf)<br/>

---

## [Structural Entities Extraction and Patient Indications Incorporation for Chest X-ray Report Generation](https://huggingface.co/papers/2405.14905)<br/>
**Authors:** Liu, Kang, Ma, Zhuoqi, Kang, Xiaolu, Zhong, Zhusi, Jiao, Zhicheng, Baird, Grayson, Bai, Harrison, Miao, Qiguang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1768_paper.pdf)<br/>
**arXiv:** [2405.14905](https://arxiv.org/abs/2405.14905)<br/>
**🤗 Paper Page:** [https://huggingface.co/papers/2405.14905](https://huggingface.co/papers/2405.14905)<br/>
**🤗 Models:** [MK-runner/SEI](https://huggingface.co/MK-runner/SEI)<br/>

---

## [Semi-Supervised Contrastive VAE for Disentanglement of Digital Pathology Images](https://arxiv.org/abs/2410.02012)<br/>
**Authors:** Hasan, Mahmudul, Hu, Xiaoling, Abousamra, Shahira, Prasanna, Prateek, Saltz, Joel, Chen, Chao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3843_paper.pdf)<br/>
**arXiv:** [2410.02012](https://arxiv.org/abs/2410.02012)<br/>

---

## Reducing Annotation Burden: Exploiting Image Knowledge for Few-Shot Medical Video Object Segmentation via Spatiotemporal Consistency Relearning<br/>
**Authors:** Zheng, Zixuan, Shi, Yilei, Li, Chunlei, Hu, Jingliang, Zhu, Xiao Xiang, Mou, Lichao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3024_paper.pdf)<br/>

---

## Physics informed neural networks for estimation of tissue properties from multi-echo configuration state MRI<br/>
**Authors:** Adams-Tew, Samuel I., Odéen, Henrik, Parker, Dennis L., Cheng, Cheng-Chieh, Madore, Bruno, Payne, Allison, Joshi, Sarang<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0605_paper.pdf)<br/>

---

## Knowledge-grounded Adaptation Strategy for Vision-language Models: Building a Unique Case-set for Screening Mammograms for Residents Training<br/>
**Authors:** Urooj Khan, Aisha, Garrett, John, Bradshaw, Tyler, Salkowski, Lonie, Jeong, Jiwoong, Tariq, Amara, Banerjee, Imon<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3702_paper.pdf)<br/>

---

## [pFLFE: Cross-silo Personalized Federated Learning via Feature Enhancement on Medical Image Segmentation](https://arxiv.org/abs/2407.00462)<br/>
**Authors:** Xie, Luyuan, Lin, Manqing, Liu, Siyuan, Xu, ChenMing, Luan, Tianyu, Li, Cong, Fang, Yuejian, Shen, Qingni, Wu, Zhonghai<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0563_paper.pdf)<br/>
**arXiv:** [2407.00462](https://arxiv.org/abs/2407.00462)<br/>

---

## Masked Residual Diffusion Probabilistic Model with Regional Asymmetry Prior for Generating Perfusion Maps from Multi-phase CTA<br/>
**Authors:** Cai, Yuxin, Zhang, Jianhai, He, Lei, Ganesh, Aravind, Qiu, Wu<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1246_paper.pdf)<br/>

---

## Spot the Difference: Difference Visual Question Answering with Residual Alignment<br/>
**Authors:** Lu, Zilin, Xie, Yutong, Zeng, Qingjie, Lu, Mengkang, Wu, Qi, Xia, Yong<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2957_paper.pdf)<br/>

---

## Towards Graph Neural Networks with Domain-Generalizable Explainability for fMRI-Based Brain Disorder Diagnosis<br/>
**Authors:** Qiu, Xinmei, Wang, Fan, Sun, Yongheng, Lian, Chunfeng, Ma, Jianhua<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1756_paper.pdf)<br/>

---

## DiRecT: Diagnosis and Reconstruction Transformer for Mandibular Deformity Assessment<br/>
**Authors:** Xu, Xuanang, Lee, Jungwook, Lampen, Nathan, Kim, Daeseung, Kuang, Tianshu, Deng, Hannah H., Liebschner, Michael A. K., Gateno, Jaime, Yan, Pingkun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1074_paper.pdf)<br/>

---

## Progressive Knowledge Distillation for Automatic Perfusion Parameter Maps Generation from Low Temporal Resolution CT Perfusion Images<br/>
**Authors:** Son, Moo Hyun, Bae, Juyoung, Tong, Elizabeth, Chen, Hao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1885_paper.pdf)<br/>

---

## HuLP: Human-in-the-Loop for Prognosis<br/>
**Authors:** Ridzuan, Muhammad, Shaaban, Mai A., Saeed, Numan, Sobirov, Ikboljon, Yaqub, Mohammad<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3209_paper.pdf)<br/>

---

## Longitudinally Consistent Individualized Prediction of Infant Cortical Morphological Development<br/>
**Authors:** Yuan, Xinrui, Cheng, Jiale, Hu, Dan, Wu, Zhengwang, Wang, Li, Lin, Weili, Li, Gang<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3725_paper.pdf)<br/>

---

## Physical-priors-guided Aortic Dissection Detection using Non-Contrast-Enhanced CT images<br/>
**Authors:** Ding, Zhengyao, Hu, Yujian, Zhang, Hongkun, Wu, Fei, Yang, Shifeng, Du, Xiaolong, Xiang, Yilang, Li, Tian, Chu, Xuesen, Huang, Zhengxing<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0345_paper.pdf)<br/>

---

## KARGEN: Knowledge-enhanced Automated Radiology Report Generation Using Large Language Models<br/>
**Authors:** Li, Yingshu, Wang, Zhanyu, Liu, Yunyi, Wang, Lei, Liu, Lingqiao, Zhou, Luping<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0877_paper.pdf)<br/>

---

## [Cross-Slice Attention and Evidential Critical Loss for Uncertainty-Aware Prostate Cancer Detection](https://arxiv.org/abs/2407.01146)<br/>
**Authors:** Hung, Alex Ling Yu, Zheng, Haoxin, Zhao, Kai, Pang, Kaifeng, Terzopoulos, Demetri, Sung, Kyunghyun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0441_paper.pdf)<br/>
**arXiv:** [2407.01146](https://arxiv.org/abs/2407.01146)<br/>

---

## [Cardiovascular Disease Detection from Multi-View Chest X-rays with BI-Mamba](https://arxiv.org/abs/2405.18533)<br/>
**Authors:** Yang, Zefan, Zhang, Jiajin, Wang, Ge, Kalra, Mannudeep K., Yan, Pingkun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1149_paper.pdf)<br/>
**arXiv:** [2405.18533](https://arxiv.org/abs/2405.18533)<br/>

---

## Stealing Knowledge from Pre-trained Language Models for Federated Classifier Debiasing<br/>
**Authors:** Zhu, Meilu, Yang, Qiushi, Gao, Zhifan, Liu, Jun, Yuan, Yixuan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3064_paper.pdf)<br/>

---

## [CoBooM: Codebook Guided Bootstrapping for Medical Image Representation Learning](https://arxiv.org/abs/2408.04262)<br/>
**Authors:** Singh, Azad, Mishra, Deepak<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3580_paper.pdf)<br/>
**arXiv:** [2408.04262](https://arxiv.org/abs/2408.04262)<br/>

---

## [LIDIA: Precise Liver Tumor Diagnosis on Multi-Phase Contrast-Enhanced CT via Iterative Fusion and Asymmetric Contrastive Learning](https://arxiv.org/abs/2407.13217)<br/>
**Authors:** Huang, Wei, Liu, Wei, Zhang, Xiaoming, Yin, Xiaoli, Han, Xu, Li, Chunli, Gao, Yuan, Shi, Yu, Lu, Le, Zhang, Ling, Zhang, Lei, Yan, Ke<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1629_paper.pdf)<br/>
**arXiv:** [2407.13217](https://arxiv.org/abs/2407.13217)<br/>

---

## Detecting noisy labels with repeated cross-validations<br/>
**Authors:** Chen, Jianan, Ramanathan, Vishwesh, Xu, Tony, Martel, Anne L.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0372_paper.pdf)<br/>

---

## Patch-Slide Discriminative Joint Learning for Weakly-Supervised Whole Slide Image Representation and Classification<br/>
**Authors:** Yu, Jiahui, Wang, Xuna, Ma, Tianyu, Li, Xiaoxiao, Xu, Yingke<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0962_paper.pdf)<br/>

---

## Centerline-Diameters Data Structure for Interactive Segmentation of Tube-shaped Objects<br/>
**Authors:** Sirazitdinov, Ilyas, Dylov, Dmitry V.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2874_paper.pdf)<br/>

---

## [Advancing Brain Imaging Analysis Step-by-step via Progressive Self-paced Learning](https://arxiv.org/abs/2407.16128)<br/>
**Authors:** Yang, Yanwu, Chen, Hairui, Hu, Jiesi, Guo, Xutao, Ma, Ting<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0173_paper.pdf)<br/>
**arXiv:** [2407.16128](https://arxiv.org/abs/2407.16128)<br/>

---

## Confidence Matters: Enhancing Medical Image Classification Through Uncertainty-Driven Contrastive Self-Distillation<br/>
**Authors:** Sharma, Saurabh, Kumar, Atul, Chandra, Joydeep<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1765_paper.pdf)<br/>

---

## [Knowledge-driven Subspace Fusion and Gradient Coordination for Multi-modal Learning](https://arxiv.org/abs/2406.13979)<br/>
**Authors:** Zhang, Yupei, Wang, Xiaofei, Meng, Fangliangzi, Tang, Jin, Li, Chao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3080_paper.pdf)<br/>
**arXiv:** [2406.13979](https://arxiv.org/abs/2406.13979)<br/>

---

## Disentangled Attention Graph Neural Network for Alzheimer’s Disease Diagnosis<br/>
**Authors:** Gamgam, Gurur, Kabakcioglu, Alkan, Yüksel Dal, Demet, Acar, Burak<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2861_paper.pdf)<br/>

---

## Visual-Textual Matching Attention for Lesion Segmentation in Chest Images<br/>
**Authors:** Bui, Phuoc-Nguyen, Le, Duc-Tai, Choo, Hyunseung<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2773_paper.pdf)<br/>

---

## Convolutional Implicit Neural Representation of pathology whole-slide images<br/>
**Authors:** Lee, DongEon, Park, Chunsu, Lee, SeonYeong, Lee, SiYeoul, Kim, MinWoo<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/4034_paper.pdf)<br/>

---

## [Rethinking Abdominal Organ Segmentation (RAOS) in the clinical scenario: A robustness evaluation benchmark with challenging cases](https://arxiv.org/abs/2406.13674)<br/>
**Authors:** Luo, Xiangde, Li, Zihan, Zhang, Shaoting, Liao, Wenjun, Wang, Guotai<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1633_paper.pdf)<br/>
**arXiv:** [2406.13674](https://arxiv.org/abs/2406.13674)<br/>

---

## Single-source Domain Generalization in Deep Learning Segmentation via Lipschitz Regularization<br/>
**Authors:** Arslan, Mazlum Ferhat, Guo, Weihong, Li, Shuo<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3740_paper.pdf)<br/>

---

## Cryotrack: Planning and Navigation for Computer Assisted Cryoablation<br/>
**Authors:** Krumb, Henry J., Mehtali, Jonas, Verde, Juan, Mukhopadhyay, Anirban, Essert, Caroline<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1240_paper.pdf)<br/>

---

## A framework for assessing joint human-AI systems based on uncertainty estimation<br/>
**Authors:** Konuk, Emir, Welch, Robert, Christiansen, Filip, Epstein, Elisabeth, Smith, Kevin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1535_paper.pdf)<br/>

---

## Center-to-Edge Denoising Diffusion Probabilistic Models with Cross-domain Attention for Undersampled MRI Reconstruction<br/>
**Authors:** Zhao, Jianfeng, Li, Shuo<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0748_paper.pdf)<br/>

---

## Few-Shot 3D Volumetric Segmentation with Multi-Surrogate Fusion<br/>
**Authors:** Zheng, Meng, Planche, Benjamin, Gao, Zhongpai, Chen, Terrence, Radke, Richard J., Wu, Ziyan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3732_paper.pdf)<br/>

---

## Hierarchical Graph Learning with Small-World Brain Connectomes for Cognitive Prediction<br/>
**Authors:** Jiang, Yu, He, Zhibin, Peng, Zhihao, Yuan, Yixuan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2707_paper.pdf)<br/>

---

## TextPolyp: Point-supervised Polyp Segmentation with Text Cues<br/>
**Authors:** Zhao, Yiming, Zhou, Yi, Zhang, Yizhe, Wu, Ye, Zhou, Tao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1293_paper.pdf)<br/>

---

## [MeshBrush: Painting the Anatomical Mesh with Neural Stylization for Endoscopy](https://arxiv.org/abs/2404.02999)<br/>
**Authors:** Han, John J., Acar, Ayberk, Kavoussi, Nicholas, Wu, Jie Ying<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2259_paper.pdf)<br/>
**arXiv:** [2404.02999](https://arxiv.org/abs/2404.02999)<br/>

---

## [Transforming Surgical Interventions with Embodied Intelligence for Ultrasound Robotics](https://arxiv.org/abs/2406.12651)<br/>
**Authors:** Xu, Huan, Wu, Jinlin, Cao, Guanglin, Chen, Zhen, Lei, Zhen, Liu, Hongbin<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0242_paper.pdf)<br/>
**arXiv:** [2406.12651](https://arxiv.org/abs/2406.12651)<br/>

---

## Car-Dcros: A Dataset and Benchmark for Enhancing Cardiovascular Artery Segmentation through Disconnected Components Repair and Open Curve Snake<br/>
**Authors:** Wang, Yuli, Hsu, Wen-Chi, Shi, Victoria, Lin, Gigin, Lin, Cheng Ting, Feng, Xue, Bai, Harrison<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3954_paper.pdf)<br/>

---

## Affinity Learning Based Brain Function Representation for Disease Diagnosis<br/>
**Authors:** Liu, Mengjun, Song, Zhiyun, Chen, Dongdong, Wang, Xin, Zhuang, Zixu, Fei, Manman, Zhang, Lichi, Wang, Qian<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0803_paper.pdf)<br/>

---

## [FedIA: Federated Medical Image Segmentation with Heterogeneous Annotation Completeness](https://arxiv.org/abs/2407.02280)<br/>
**Authors:** Xiang, Yangyang, Wu, Nannan, Yu, Li, Yang, Xin, Cheng, Kwang-Ting, Yan, Zengqiang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1182_paper.pdf)<br/>
**arXiv:** [2407.02280](https://arxiv.org/abs/2407.02280)<br/>

---

## [EndoFinder: Online Image Retrieval for Explainable Colorectal Polyp Diagnosis](https://arxiv.org/abs/2407.11401)<br/>
**Authors:** Yang, Ruijie, Zhu, Yan, Fu, Peiyao, Zhang, Yizhe, Wang, Zhihua, Li, Quanlin, Zhou, Pinghong, Yang, Xian, Wang, Shuo<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1282_paper.pdf)<br/>
**arXiv:** [2407.11401](https://arxiv.org/abs/2407.11401)<br/>

---

## Slice-Consistent Lymph Nodes Detection Transformer in CT Scans via Cross-slice Query Contrastive Learning<br/>
**Authors:** Yu, Qinji, Wang, Yirui, Yan, Ke, Lu, Le, Shen, Na, Ye, Xianghua, Ding, Xiaowei, Jin, Dakai<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0362_paper.pdf)<br/>

---

## A New Benchmark In Vivo Paired Dataset for Laparoscopic Image De-smoking<br/>
**Authors:** Xia, Wenyao, Fan, Victoria, Peters, Terry, Chen, Elvis C. S.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1213_paper.pdf)<br/>

---

## [Data-Driven Tissue- and Subject-Specific Elastic Regularization for Medical Image Registration](https://arxiv.org/abs/2407.04355)<br/>
**Authors:** Reithmeir, Anna, Felsner, Lina, Braren, Rickmer F., Schnabel, Julia A., Zimmer, Veronika A.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3303_paper.pdf)<br/>
**arXiv:** [2407.04355](https://arxiv.org/abs/2407.04355)<br/>

---

## Multi-Modal Graph Neural Network with Transformer-Guided Adaptive Diffusion for Preclinical Alzheimer Classification<br/>
**Authors:** Sim, Jaeyoon, Lee, Minjae, Wu, Guorong, Kim, Won Hwa<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1153_paper.pdf)<br/>

---

## A Clinical-oriented Multi-level Contrastive Learning Method for Disease Diagnosis in Low-quality Medical Images<br/>
**Authors:** Hou, Qingshan, Cheng, Shuai, Cao, Peng, Yang, Jinzhu, Liu, Xiaoli, Tham, Yih Chung, Zaiane, Osmar R.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2364_paper.pdf)<br/>

---

## Exploiting Latent Classes for Medical Image Segmentation from Partially Labeled Datasets<br/>
**Authors:** Zhao, Xiangyu, Ouyang, Xi, Zhang, Lichi, Xue, Zhong, Shen, Dinggang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1324_paper.pdf)<br/>

---

## [Evaluating the Quality of Brain MRI Generators](https://arxiv.org/abs/2409.08463)<br/>
**Authors:** Wu, Jiaqi, Peng, Wei, Li, Binxu, Zhang, Yu, Pohl, Kilian M.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0689_paper.pdf)<br/>
**arXiv:** [2409.08463](https://arxiv.org/abs/2409.08463)<br/>

---

## Survival analysis of histopathological image based on a pretrained hypergraph model of spatial transcriptomics data<br/>
**Authors:** Cai, Shangyan, Huang, Weitian, Yi, Weiting, Zhang, Bin, Liao, Yi, Wang, Qiu, Cai, Hongmin, Chen, Luonan, Su, Weifeng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/4136_paper.pdf)<br/>

---

## Cardiac Physiology Knowledge-driven Diffusion Model for Contrast-free Synthesis Myocardial Infarction Enhancement<br/>
**Authors:** Qi, Ronghui, Li, Xiaohu, Xu, Lei, Zhang, Jie, Zhang, Yanping, Xu, Chenchu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0918_paper.pdf)<br/>

---

## Federated Multi-Centric Image Segmentation with Uneven Label Distribution<br/>
**Authors:** Galati, Francesco, Cortese, Rosa, Prados, Ferran, Lorenzi, Marco, Zuluaga, Maria A.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0368_paper.pdf)<br/>

---

## Learning Representations by Maximizing Mutual Information Across Views for Medical Image Segmentation<br/>
**Authors:** Weng, Weihao, Zhu, Xin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0103_paper.pdf)<br/>

---

## CausCLIP: Causality-Adapting Visual Scoring of Visual Language Models for Few-Shot Learning in Portable Echocardiography Quality Assessment<br/>
**Authors:** Li, Yiran, Cui, Xiaoxiao, Cao, Yankun, Zhang, Yuezhong, Wang, Huihui, Cui, Lizhen, Liu, Zhi, Li, Shuo<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0745_paper.pdf)<br/>

---

## [Hard Negative Sample Mining for Whole Slide Image Classification](https://arxiv.org/abs/2410.02212)<br/>
**Authors:** Huang, Wentao, Hu, Xiaoling, Abousamra, Shahira, Prasanna, Prateek, Chen, Chao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3822_paper.pdf)<br/>
**arXiv:** [2410.02212](https://arxiv.org/abs/2410.02212)<br/>

---

## NeuroLink: Bridging Weak Signals in Neuronal Imaging with Morphology Learning<br/>
**Authors:** Yan, Haiyang, Zhai, Hao, Guo, Jinyue, Li, Linlin, Han, Hua<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0811_paper.pdf)<br/>

---

## Exploring Spatio-Temporal Interpretable Dynamic Brain Function with Transformer for Brain Disorder Diagnosis<br/>
**Authors:** Li, Lanting, Zhang, Liuzeng, Cao, Peng, Yang, Jinzhu, Wang, Fei, Zaiane, Osmar R.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1874_paper.pdf)<br/>

---

## [Groupwise Deformable Registration of Diffusion Tensor Cardiovascular Magnetic Resonance: Disentangling Diffusion Contrast, Respiratory and Cardiac Motions](https://arxiv.org/abs/2406.13788)<br/>
**Authors:** Wang, Fanwen, Luo, Yihao, Wen, Ke, Huang, Jiahao, Ferreira, Pedro F., Luo, Yaqing, Wu, Yinzhe, Munoz, Camila, Pennell, Dudley J., Scott, Andrew D., Nielles-Vallespin, Sonia, Yang, Guang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2286_paper.pdf)<br/>
**arXiv:** [2406.13788](https://arxiv.org/abs/2406.13788)<br/>

---

## [Ensembled Cold-Diffusion Restorations for Unsupervised Anomaly Detection](https://arxiv.org/abs/2407.06635)<br/>
**Authors:** Naval Marimont, Sergio, Siomos, Vasilis, Baugh, Matthew, Tzelepis, Christos, Kainz, Bernhard, Tarroni, Giacomo<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1928_paper.pdf)<br/>
**arXiv:** [2407.06635](https://arxiv.org/abs/2407.06635)<br/>

---

## [Gaze-directed Vision GNN for Mitigating Shortcut Learning in Medical Image](https://arxiv.org/abs/2406.14050)<br/>
**Authors:** Wu, Shaoxuan, Zhang, Xiao, Wang, Bin, Jin, Zhuo, Li, Hansheng, Feng, Jun<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1797_paper.pdf)<br/>
**arXiv:** [2406.14050](https://arxiv.org/abs/2406.14050)<br/>

---

## Design as Desired: Utilizing Visual Question Answering for Multimodal Pre-training<br/>
**Authors:** Su, Tongkun, Li, Jun, Zhang, Xi, Jin, Haibo, Chen, Hao, Wang, Qiong, Lv, Faqin, Zhao, Baoliang, Hu, Ying<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0889_paper.pdf)<br/>

---

## Vestibular schwannoma growth prediction from longitudinal MRI by time-conditioned neural fields<br/>
**Authors:** Chen, Yunjie, Wolterink, Jelmer M., Neve, Olaf M., Romeijn, Stephan R., Verbist, Berit M., Hensen, Erik F., Tao, Qian, Staring, Marius<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2068_paper.pdf)<br/>

---

## Gyri vs. Sulci: Core-Periphery Organization in Functional Brain Networks<br/>
**Authors:** Yu, Xiaowei, Zhang, Lu, Cao, Chao, Chen, Tong, Lyu, Yanjun, Zhang, Jing, Liu, Tianming, Zhu, Dajiang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3934_paper.pdf)<br/>

---

## Language-Enhanced Local-Global Aggregation Network for Multi-Organ Trauma Detection<br/>
**Authors:** Yu, Jianxun, Hu, Qixin, Jiang, Meirui, Wang, Yaning, Wong, Chin Ting, Wang, Jing, Zhang, Huimao, Dou, Qi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1056_paper.pdf)<br/>

---

## [Joint multi-task learning improves weakly-supervised biomarker prediction in computational pathology](https://arxiv.org/abs/2403.03891)<br/>
**Authors:** El Nahhas, Omar S. M., Wölflein, Georg, Ligero, Marta, Lenz, Tim, van Treeck, Marko, Khader, Firas, Truhn, Daniel, Kather, Jakob Nikolas<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1368_paper.pdf)<br/>
**arXiv:** [2403.03891](https://arxiv.org/abs/2403.03891)<br/>

---

## Algorithmic Fairness in Lesion Classification by Mitigating Class Imbalance and Skin Tone Bias<br/>
**Authors:** Ansari, Faizanuddin, Chakraborti, Tapabrata, Das, Swagatam<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2178_paper.pdf)<br/>

---

## [PANS: Probabilistic Airway Navigation System for Real-time Robust Bronchoscope Localization](https://arxiv.org/abs/2407.05554)<br/>
**Authors:** Tian, Qingyao, Chen, Zhen, Liao, Huai, Huang, Xinyan, Yang, Bingyu, Li, Lujie, Liu, Hongbin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0928_paper.pdf)<br/>
**arXiv:** [2407.05554](https://arxiv.org/abs/2407.05554)<br/>

---

## [Volume-optimal persistence homological scaffolds of hemodynamic networks covary with MEG theta-alpha aperiodic dynamics](https://arxiv.org/abs/2407.05060)<br/>
**Authors:** Nguyen, Nghi, Hou, Tao, Amico, Enrico, Zheng, Jingyi, Huang, Huajun, Kaplan, Alan D., Petri, Giovanni, Goñi, Joaqúın, Kaufmann, Ralph, Zhao, Yize, Duong-Tran, Duy, Shen, Li<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3894_paper.pdf)<br/>
**arXiv:** [2407.05060](https://arxiv.org/abs/2407.05060)<br/>

---

## [Poisson Ordinal Network for Gleason Group Estimation Using Bi-Parametric MRI](https://arxiv.org/abs/2407.05796)<br/>
**Authors:** Xu, Yinsong, Wang, Yipei, Shen, Ziyi, Gayo, Iani J. M. B., Thorley, Natasha, Punwani, Shonit, Men, Aidong, Barratt, Dean C., Chen, Qingchao, Hu, Yipeng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0193_paper.pdf)<br/>
**arXiv:** [2407.05796](https://arxiv.org/abs/2407.05796)<br/>

---

## Improved Classification Learning from Highly Imbalanced Multi-Label Datasets of Inflamed Joints in [99mTc]Maraciclatide Imaging of Arthritic Patients by Natural Image and Diffusion Model Augmentation<br/>
**Authors:** Cobb, Robert, Cook, Gary J. R., Reader, Andrew J.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3427_paper.pdf)<br/>

---

## Unified Multi-Modal Learning for Any Modality Combinations in Alzheimer’s Disease Diagnosis<br/>
**Authors:** Feng, Yidan, Gao, Bingchen, Deng, Sen, Qiu, Anqi, Qin, Jing<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1760_paper.pdf)<br/>

---

## Cortical Surface Reconstruction from 2D MRI with Segmentation-Constrained Super-Resolution and Representation Learning<br/>
**Authors:** Wu, Wenxuan, Qu, Ruowen, Shi, Dongzi, Xiong, Tong, Xu, Xiangmin, Xing, Xiaofen, Zhang, Xin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2321_paper.pdf)<br/>

---

## Semi-Supervised Learning for Deep Causal Generative Models<br/>
**Authors:** Ibrahim, Yasin, Warr, Hermione, Kamnitsas, Konstantinos<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3457_paper.pdf)<br/>

---

## Inject Backdoor in Measured Data to Jeopardize Full-Stack Medical Image Analysis System<br/>
**Authors:** Yang, Ziyuan, Chen, Yingyu, Sun, Mengyu, Zhang, Yi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0983_paper.pdf)<br/>

---

## VCLIPSeg: Voxel-wise CLIP-Enhanced model for Semi-Supervised Medical Image Segmentation<br/>
**Authors:** Li, Lei, Lian, Sheng, Luo, Zhiming, Wang, Beizhan, Li, Shaozi<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1949_paper.pdf)<br/>

---

## SDFPlane: Explicit Neural Surface Reconstruction of Deformable Tissues<br/>
**Authors:** Li, Hao, Shan, Jiwei, Wang, Hesheng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2098_paper.pdf)<br/>

---

## [MoreStyle: Relax Low-frequency Constraint of Fourier-based Image Reconstruction in Generalizable Medical Image Segmentation](https://arxiv.org/abs/2403.11689)<br/>
**Authors:** Zhao, Haoyu, Dong, Wenhui, Yu, Rui, Zhao, Zhou, Du, Bo, Xu, Yongchao<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0782_paper.pdf)<br/>
**arXiv:** [2403.11689](https://arxiv.org/abs/2403.11689)<br/>

---

## [3DDX: Bone Surface Reconstruction from a Single Standard-Geometry Radiograph via Dual-Face Depth Estimation](https://arxiv.org/abs/2409.16702)<br/>
**Authors:** Gu, Yi, Otake, Yoshito, Uemura, Keisuke, Takao, Masaki, Soufi, Mazen, Okada, Seiji, Sugano, Nobuhiko, Talbot, Hugues, Sato, Yoshinobu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1001_paper.pdf)<br/>
**arXiv:** [2409.16702](https://arxiv.org/abs/2409.16702)<br/>

---

## Few-shot Adaptation of Medical Vision-Language Models<br/>
**Authors:** Shakeri, Fereshteh, Huang, Yunshi, Silva-Rodriguez, Julio, Bahig, Houda, Tang, An, Dolz, Jose, Ben Ayed, Ismail<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2320_paper.pdf)<br/>

---

## VLSM-Adapter: Finetuning Vision-Language Segmentation Efficiently with Lightweight Blocks<br/>
**Authors:** Dhakal, Manish, Adhikari, Rabin, Thapaliya, Safal, Khanal, Bishesh<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/4190_paper.pdf)<br/>

---

## Multivariate Cooperative Game for Image-Report Pairs: Hierarchical Semantic Alignment for Medical Report Generation<br/>
**Authors:** Zhu, Zhihong, Cheng, Xuxin, Zhang, Yunyan, Chen, Zhaorun, Long, Qingqing, Li, Hongxiang, Huang, Zhiqi, Wu, Xian, Zheng, Yefeng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1475_paper.pdf)<br/>

---

## Diffusion-based Domain Adaptation for Medical Image Segmentation using Stochastic Step Alignment<br/>
**Authors:** Ji, Wen, Chung, Albert C. S.<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0195_paper.pdf)<br/>

---

## Death by Retrospective Undersampling - Caveats and Solutions for Learning-Based MRI Reconstructions<br/>
**Authors:** Rajput, Junaid R., Weinmueller, Simon, Endres, Jonathan, Dawood, Peter, Knoll, Florian, Maier, Andreas, Zaiss, Moritz<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3200_paper.pdf)<br/>

---

## MMQL: Multi-Question Learning for Medical Visual Question Answering<br/>
**Authors:** Chen, Qishen, Bian, Minjie, Xu, Huahu<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1159_paper.pdf)<br/>

---

## [Depth-Aware Endoscopic Video Inpainting](https://arxiv.org/abs/2407.02675)<br/>
**Authors:** Zhang, Francis Xiatian, Chen, Shuang, Xie, Xianghua, Shum, Hubert P. H.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0179_paper.pdf)<br/>
**arXiv:** [2407.02675](https://arxiv.org/abs/2407.02675)<br/>

---

## Leveraging Coarse-to-Fine Grained Representations in Contrastive Learning for Differential Medical Visual Question Answering<br/>
**Authors:** Liang, Xiao, Wang, Yin, Wang, Di, Jiao, Zhicheng, Zhong, Haodi, Yang, Mengyu, Wang, Quan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1957_paper.pdf)<br/>

---

## [Sparse Bayesian Networks: Efficient Uncertainty Quantification in Medical Image Analysis](https://arxiv.org/abs/2406.06946)<br/>
**Authors:** Abboud, Zeinab, Lombaert, Herve, Kadoury, Samuel<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0608_paper.pdf)<br/>
**arXiv:** [2406.06946](https://arxiv.org/abs/2406.06946)<br/>

---

## Blind Proximal Diffusion Model for Joint Image and Sensitivity Estimation in Parallel MRI<br/>
**Authors:** Li, Xing, Yang, Yan, Zheng, Hairong, Xu, Zongben<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2563_paper.pdf)<br/>

---

## Hierarchical multiple instance learning for COPD grading with relatively specific similarity<br/>
**Authors:** Zhang, Hao, Zhao, Mingyue, Liu, Mingzhu, Luo, Jiejun, Guan, Yu, Zhang, Jin, Xia, Yi, Zhang, Di, Zhou, Xiuxiu, Fan, Li, Liu, Shiyuan, Zhou, S. Kevin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1863_paper.pdf)<br/>

---

## SANGRE: a Shallow Attention Network Guided by Resolution Expansion for MR Image Segmentation<br/>
**Authors:** He, Ying, Miquel, Marc E., Zhang, Qianni<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3565_paper.pdf)<br/>

---

## [Volumetric Conditional Score-based Residual Diffusion Model for PET/MR Denoising](https://arxiv.org/abs/2410.00184)<br/>
**Authors:** Yoon, Siyeop, Tivnan, Matthew, Hu, Rui, Wang, Yuang, Son, Young-don, Wu, Dufan, Li, Xiang, Kim, Kyungsang, Li, Quanzheng<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2347_paper.pdf)<br/>
**arXiv:** [2410.00184](https://arxiv.org/abs/2410.00184)<br/>

---

## [TAKT: Target-Aware Knowledge Transfer for Whole Slide Image Classification](https://arxiv.org/abs/2303.05780)<br/>
**Authors:** Xiong, Conghao, Lin, Yi, Chen, Hao, Zheng, Hao, Wei, Dong, Zheng, Yefeng, Sung, Joseph J. Y., King, Irwin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2121_paper.pdf)<br/>
**arXiv:** [2303.05780](https://arxiv.org/abs/2303.05780)<br/>

---

## [Decoding the visual attention of pathologists to reveal their level of expertise](https://arxiv.org/abs/2403.17255)<br/>
**Authors:** Chakraborty, Souradeep, Gupta, Rajarsi, Yaskiv, Oksana, Friedman, Constantin, Sheuka, Natallia, Perez, Dana, Friedman, Paul, Zelinsky, Gregory, Saltz, Joel, Samaras, Dimitris<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0394_paper.pdf)<br/>
**arXiv:** [2403.17255](https://arxiv.org/abs/2403.17255)<br/>

---

## SimBrainNet: Evaluating Brain Network Similarity for Attention Disorders<br/>
**Authors:** Das Chakladar, Debashis, Simistira Liwicki, Foteini, Saini, Rajkumar<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2277_paper.pdf)<br/>

---

## Dynamic Single-Pixel Imaging on an Extended Field of View without Warping the Patterns<br/>
**Authors:** Maitre, Thomas, Bretin, Elie, Phan, Romain, Ducros, Nicolas, Sdika, Michaël<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1903_paper.pdf)<br/>

---

## Learnable Skeleton-Based Medical Landmark Estimation with Graph Sparsity and Fiedler Regularizations<br/>
**Authors:** Wang, Yao, Chen, Jiahao, Huang, Wenjian, Dong, Pei, Qian, Zhen<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1602_paper.pdf)<br/>

---

## Pixel2Mechanics: Automated biomechanical simulations of high-resolution intervertebral discs from anisotropic MRIs<br/>
**Authors:** Natarajan, Sai, Muñoz-Moya, Estefano, Ruiz Wills, Carlos, Piella, Gemma, Noailly, Jérôme, Humbert, Ludovic, González Ballester, Miguel A.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/4115_paper.pdf)<br/>

---

## Hierarchical Symmetric Normalization Registration using Deformation-Inverse Network<br/>
**Authors:** Sha, Qingrui, Sun, Kaicong, Xu, Mingze, Li, Yonghao, Xue, Zhong, Cao, Xiaohuan, Shen, Dinggang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3036_paper.pdf)<br/>

---

## [Towards Real-time Intrahepatic Vessel Identification in Intraoperative Ultrasound-Guided Liver Surgery](https://arxiv.org/abs/2410.03420)<br/>
**Authors:** Beaudet, Karl-Philippe, Karargyris, Alexandros, El Hadramy, Sidaty, Cotin, Stéphane, Mazellier, Jean-Paul, Padoy, Nicolas, Verde, Juan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/4218_paper.pdf)<br/>
**arXiv:** [2410.03420](https://arxiv.org/abs/2410.03420)<br/>

---

## LS+: Informed Label Smoothing for Improving Calibration in Medical Image Classification<br/>
**Authors:** Sambyal, Abhishek Singh, Niyaz, Usma, Shrivastava, Saksham, Krishnan, Narayanan C., Bathula, Deepti R.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3276_paper.pdf)<br/>

---

## OCL: Ordinal Contrastive Learning for Imputating Features with Progressive Labels<br/>
**Authors:** Baek, Seunghun, Sim, Jaeyoon, Wu, Guorong, Kim, Won Hwa<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1615_paper.pdf)<br/>

---

## [Topologically faithful multi-class segmentation in medical images](https://arxiv.org/abs/2403.11001)<br/>
**Authors:** Berger, Alexander H., Lux, Laurin, Stucki, Nico, Bürgin, Vincent, Shit, Suprosanna, Banaszak, Anna, Rueckert, Daniel, Bauer, Ulrich, Paetzold, Johannes C.<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0582_paper.pdf)<br/>
**arXiv:** [2403.11001](https://arxiv.org/abs/2403.11001)<br/>

---

## NeuroConText: Contrastive Text-to-Brain Mapping for Neuroscientific Literature<br/>
**Authors:** Meudec, Raphaël, Ghayem, Fateme, Dockès, Jérôme, Wassermann, Demian, Thirion, Bertrand<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3550_paper.pdf)<br/>

---

## [Improving cross-domain brain tissue segmentation in fetal MRI with synthetic data](https://arxiv.org/abs/2403.15103)<br/>
**Authors:** Zalevskyi, Vladyslav, Sanchez, Thomas, Roulet, Margaux, Aviles Verdera, Jordina, Hutter, Jana, Kebiri, Hamza, Bach Cuadra, Meritxell<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3487_paper.pdf)<br/>
**arXiv:** [2403.15103](https://arxiv.org/abs/2403.15103)<br/>

---

## BGDiffSeg: a Fast Diffusion Model for Skin Lesion Segmentation via Boundary Enhancement and Global Recognition Guidance<br/>
**Authors:** Guo, Yilin, Cai, Qingling<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3253_paper.pdf)<br/>

---

## [Prompting Whole Slide Image Based Genetic Biomarker Prediction](https://arxiv.org/abs/2407.09540)<br/>
**Authors:** Zhang, Ling, Yun, Boxiang, Xie, Xingran, Li, Qingli, Li, Xinxing, Wang, Yan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0622_paper.pdf)<br/>
**arXiv:** [2407.09540](https://arxiv.org/abs/2407.09540)<br/>

---

## [SlicerTMS: Real-Time Visualization of Transcranial Magnetic Stimulation for Mental Health Treatment](https://arxiv.org/abs/2305.06459)<br/>
**Authors:** Franke, Loraine, Luo, Jie, Park, Tae Young, Kim, Nam Wook, Rathi, Yogesh, Pieper, Steve, Ning, Lipeng, Haehn, Daniel<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/2402_paper.pdf)<br/>
**arXiv:** [2305.06459](https://arxiv.org/abs/2305.06459)<br/>

---

## Multi-Dataset Multi-Task Learning for COVID-19 Prognosis<br/>
**Authors:** Ruffini, Filippo, Tronchin, Lorenzo, Wu, Zhuoru, Chen, Wenting, Soda, Paolo, Shen, Linlin, Guarrasi, Valerio<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/4049_paper.pdf)<br/>

---

## [Deform3DGS: Flexible Deformation for Fast Surgical Scene Reconstruction with Gaussian Splatting](https://arxiv.org/abs/2405.17835)<br/>
**Authors:** Yang, Shuojue, Li, Qian, Shen, Daiyun, Gong, Bingchen, Dou, Qi, Jin, Yueming<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3887_paper.pdf)<br/>
**arXiv:** [2405.17835](https://arxiv.org/abs/2405.17835)<br/>

---

## [MMFusion: Multi-modality Diffusion Model for Lymph Node Metastasis Diagnosis in Esophageal Cancer](https://arxiv.org/abs/2405.09539)<br/>
**Authors:** Wu, Chengyu, Wang, Chengkai, Zhou, Huiyu, Zhang, Yatao, Wang, Qifeng, Wang, Yaqi, Wang, Shuai<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1370_paper.pdf)<br/>
**arXiv:** [2405.09539](https://arxiv.org/abs/2405.09539)<br/>

---

## Zero-shot Low-field MRI Enhancement via Denoising Diffusion Driven Neural Representation<br/>
**Authors:** Lin, Xiyue, Du, Chenhe, Wu, Qing, Tian, Xuanyu, Yu, Jingyi, Zhang, Yuyao, Wei, Hongjiang<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3647_paper.pdf)<br/>

---

## MMBCD: Multimodal Breast Cancer Detection from Mammograms with Clinical History<br/>
**Authors:** Jain, Kshitiz, Bansal, Aditya, Rangarajan, Krithika, Arora, Chetan<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1311_paper.pdf)<br/>

---

## SegNeuron: 3D Neuron Instance Segmentation in Any EM Volume with a Generalist Model<br/>
**Authors:** Zhang, Yanchao, Guo, Jinyue, Zhai, Hao, Liu, Jing, Han, Hua<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0518_paper.pdf)<br/>

---

## [Hierarchical Text-to-Vision Self Supervised Alignment for Improved Histopathology Representation Learning](https://arxiv.org/abs/2403.14616)<br/>
**Authors:** Watawana, Hasindri, Ranasinghe, Kanchana, Mahmood, Tariq, Naseer, Muzammal, Khan, Salman, Shahbaz Khan, Fahad<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0460_paper.pdf)<br/>
**arXiv:** [2403.14616](https://arxiv.org/abs/2403.14616)<br/>

---

## [GEM: Context-Aware Gaze EstiMation with Visual Search Behavior Matching for Chest Radiograph](https://arxiv.org/abs/2408.05502)<br/>
**Authors:** Liu, Shaonan, Chen, Wenting, Liu, Jie, Luo, Xiaoling, Shen, Linlin<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1951_paper.pdf)<br/>
**arXiv:** [2408.05502](https://arxiv.org/abs/2408.05502)<br/>

---

## [Voxel Scene Graph for Intracranial Hemorrhage](https://arxiv.org/abs/2407.21580)<br/>
**Authors:** Sanner, Antoine P., Grauhan, Nils F., Brockmann, Marc A., Othman, Ahmed E., Mukhopadhyay, Anirban<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/0751_paper.pdf)<br/>
**arXiv:** [2407.21580](https://arxiv.org/abs/2407.21580)<br/>

---

## [Probabilistic Temporal Prediction of Continuous Disease Trajectories and Treatment Effects Using Neural SDEs](https://arxiv.org/abs/2406.12807)<br/>
**Authors:** Durso-Finley, Joshua, Barile, Berardino, Falet, Jean-Pierre, Arnold, Douglas L., Pawlowski, Nick, Arbel, Tal<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3431_paper.pdf)<br/>
**arXiv:** [2406.12807](https://arxiv.org/abs/2406.12807)<br/>

---

## Cross-graph Interaction and Diffusion Probability Models for Lung Nodule Segmentation<br/>
**Authors:** Su, Huaqiang, Lei, Haijun, Guoliang, Chen, Lei, Baiying<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1228_paper.pdf)<br/>

---

## VertFound: Synergizing Semantic and Spatial Understanding for Fine-grained Vertebrae Classification via Foundation Models<br/>
**Authors:** Tang, Jinzhou, Wu, Yinhao, Yao, Zequan, Li, Mingjie, Hong, Yuan, Yu, Dongdong, Gao, Zhifan, Chen, Bin, Zhao, Shen<br/>
**Type:** Poster<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/3978_paper.pdf)<br/>

---

## Hybrid-Structure-Oriented Transformer for Arm Musculoskeletal Ultrasound Segmentation<br/>
**Authors:** Chen, Lingyu, Wang, Yue, Zhao, Zhe, Liao, Hongen, Zhang, Daoqiang, Han, Haojie, Chen, Fang<br/>
**Type:** Oral<br/>
**Proceedings:** [Link](https://papers.miccai.org/miccai-2024/paper/1638_paper.pdf)<br/>

---
