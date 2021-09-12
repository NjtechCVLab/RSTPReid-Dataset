# RSTPReid-Dataset
RSTPReid Dataset for our ACMMM2021 accepted paper DSSL: Deep Surroundings-person Separation Learning for Text-based Person Retrieval.  

![Dataset](https://github.com/NjtechCVLab/RSTPReid-Dataset/blob/main/Imgs/MM2021Dataset.png)

## Introduction

To properly handle real scenarios, we construct a new dataset called Real Scenario Text-based Person Re-identification (RSTPReid) based on [MSMT17](https://openaccess.thecvf.com/content_cvpr_2018/papers/Wei_Person_Transfer_GAN_CVPR_2018_paper.pdf) [2]. RSTPReid contains 20505 images of 4,101 persons from 15 cameras. Each person has 5 corresponding images taken by different cameras with complex both indoor and outdoor scene transformations and backgrounds in various periods of time, which makes RSTPReid much more challenging and more adaptable to real scenarios. Each image is annotated with 2 textual descriptions. For data division, 3701, 200 and 200 identities are utilized for training, validation and testing, respectively. Each sentence is no shorter than 23 words. After dropping words that appear less than twice, the word number is 2204.

## Dataset Access

### Google Drive
Link: [https://drive.google.com/file/d/1mngN3jZz4BI6PyGNZMKsvRR9JbvLSlg9/view?usp=sharing](https://drive.google.com/file/d/1mngN3jZz4BI6PyGNZMKsvRR9JbvLSlg9/view?usp=sharing)

### Baidu Netdisk
Link: [https://pan.baidu.com/s/11osRxEV8cnS5SXDXTEtIQg](https://pan.baidu.com/s/11osRxEV8cnS5SXDXTEtIQg)  
Password: 8qw0  

## Reference

[1] Aichun Zhu, Zijie Wang, Yifeng Li, et al. DSSL: Deep Surroundings-person Separation Learning for Text-based Person Retrieval[C]. The 29th ACM International Conference on
Multimedia, 2021. 

[2] Longhui Wei, Shiliang Zhang, Wen Gao, and Qi Tian. 2018. Person transfer gan to bridge domain gap for person re-identification. In Proceedings of the IEEE conference on computer vision and pattern recognition. 79–88.
