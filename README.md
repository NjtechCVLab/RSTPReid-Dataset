# RSTPReid-Dataset
RSTPReid Dataset for our ACMMM2021 accepted paper [DSSL: Deep Surroundings-person Separation Learning for Text-based Person Retrieval](https://arxiv.org/abs/2109.05534) [1].  

![Dataset](https://github.com/NjtechCVLab/RSTPReid-Dataset/blob/main/MM2021Dataset.png)

## Introduction

To properly handle real scenarios, we construct a new dataset called Real Scenario Text-based Person Re-identification (RSTPReid) based on [MSMT17](https://openaccess.thecvf.com/content_cvpr_2018/papers/Wei_Person_Transfer_GAN_CVPR_2018_paper.pdf) [2]. RSTPReid contains 20505 images of 4,101 persons from 15 cameras. Each person has 5 corresponding images taken by different cameras with complex both indoor and outdoor scene transformations and backgrounds in various periods of time, which makes RSTPReid much more challenging and more adaptable to real scenarios. Each image is annotated with 2 textual descriptions. For data division, **3701 (index < 18505), 200 (18505 <= index < 19505) and 200 (index >= 19505)** identities are utilized for training, validation and testing, respectively **(Marked by item 'split' in the json file)**. Each sentence is no shorter than 23 words.

Considering that the RSTPReid dataset is newly constructed and is relatively small in data size comparing with CUHK-PEDES, we sepatarely trained each model for 10 times and reported the average results on the validation set in Table 1 to avoid occasional and unstable performance. Moreover, in this paper we only use RSTPReid to make a preliminary analysis of the five proposed alignment paradigms and take the results as a further proof of the validity of each component. Most of the experiments in this paper are still conducted using CHUK-PEDES, where the final results on the testing set are reported.

On the testing set of RSTPReid, DSSL achieves **39.05%**, **62.60%** and **73.95%** of top-1, top-5 and top-10 accuracies, respectively. More detailed experimental analysis will be conducted on RETPReid along with CUHK-PEDES, which will be reported in the extension of this paper.

## Dataset Access

### Google Drive
Link: [https://drive.google.com/file/d/1CQqDcquTq17FJ84IvXtzdxTqf6FyPSQv/view?usp=sharing](https://drive.google.com/file/d/1CQqDcquTq17FJ84IvXtzdxTqf6FyPSQv/view?usp=sharing)

### Baidu Netdisk
Link: [https://pan.baidu.com/s/1hAk5a3OhqkfvyJF876E7EQ?pwd=z2ow](https://pan.baidu.com/s/1hAk5a3OhqkfvyJF876E7EQ?pwd=z2ow)  
Password: z2ow  

## Reference

[1] Zhu A, Wang Z, Li Y, et al. DSSL: Deep Surroundings-person Separation Learning for Text-based Person Retrieval[C]//Proceedings of the 29th ACM International Conference on Multimedia. 2021: 209-217.

[2] Wei L, Zhang S, Gao W, et al. Person transfer gan to bridge domain gap for person re-identification[C]//Proceedings of the IEEE conference on computer vision and pattern recognition. 2018: 79-88.
