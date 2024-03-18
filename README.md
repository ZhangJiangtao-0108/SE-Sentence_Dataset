# SE-Sentence Dataset

## Introduction
---
SE-Sentence is a sign language Enotion recognition (SLER) dataset, which is based on **sEMG (200Hz)** and **IMU (50Hz)** sensor signals, and includes five emotions: **high-positive (HP), low-positive(LP), neutral (N), low-negative (LN), and high-negative (HN)**. 50 sentences are selected from daily conversation textbooks for the hearing impaired. 18 participants (9 male and 9 female) are invited to collect the SE-Sentence dataset, including 11 hearing-impaired people (students, employees, etc.), and 7 able-bodied people with professional training. The age of the volunteers ranged from 18-40 years old.

### Emotion Stimuli
---
SE-Sentence co-opted the emotional stimulation method of the [SEED dataset]() to elicit volunteers’ emotions. Fifteen clips from six Chinese movies were selected to evoke different emotions. After the emotional stimuli generated, the volunteers were asked to complete self-assessment manikin system questionnaire to ensure the current emotion category and assess the degree of valence and arousal.

### Data Collection
---
Volunteers were only asked to perform the provided sign language sentences when they were under the target emotion. Each sentence was performed five times. If the volunteer’s emotion weakened or disappeared afterward, it stopped the collection of sign language data and re-stimulated the
emotion.

Each instance in this datasets contains **sEMG and IMU** information of the signer.


## Download
---
The SE-Sentence database is released to universities and research institutes for research purpose only. To request the access right to the data resources, please follow the instructions below:
- Download the [SE-Sentence Dataset Release Agreement](https://github.com/ZhangJiangtao-0108/MM-Sentence_Dataset/blob/main/MM-Sentence%20_Dataset%20_Release%20_Agreement.pdf);
- Read all items and conditions carefully;
- Complete it appropriately. Note that the agreement should be signed by a full-time staff member (that is, the student is not acceptable).
- Please scan the signed agreement, send it to (zhangjiangtao@mail.hfut.edu.cn) and CC to Prof. Wang (qswang@hfut.edu.cn). If you are a student, please also CC to the full-time staff member who sign the agreement.


## Reference
---
Please cite the following papers if you use MM-Sentence dataset for your research:


  
Besides, you can refer to the following papers for continuous SLR published by our group:
- J. Zhang, Q. Wang, Q. Wang, and Z. Zheng, “Multimodal fusion framework based on statistical attention and contrastive attention for sign language recognition,” IEEE Transactions on Mobile Computing, pp. 1–13, 2023, doi:10.1109/TMC.2023.3235935
- J. Zhang, Q. Wang, and Q. Wang, “HDTSLR: A framework based on hierarchical dynamic positional encoding for sign language recognition,” IEEE Transactions on Mobile Computing, pp. 1–13, 2023, doi:10.1109/TMC.2023.3310712
- J. Zhang, Q. Wang, and Q. Wang, “A Sign Language Recognition Framework Based on Cross-Modal Complementary Information Fusion,” IEEE Transactions on Multimedia, pp. 1–13, 2024, doi:10.1109/TMM.2024.3377095


SEED Dataset Reference：
- W. L. Zheng and B. L. Lu, “Investigating critical frequency bands and channels for eeg-based emotion recognition with deep neural networks,” IEEE Transactions on Autonomous Mental Development, vol. 7, no. 3, pp. 162–175, 2015.
