# SNU_NLP_Lecture
## Overview
![image](https://user-images.githubusercontent.com/70995074/207805883-e116b323-897b-407c-bb1d-3baa7c8d6c2d.png)
- **Topic**: Text classification data augmentation methods
- **Hypothesis**: Using class information when augmenting text classification training data will help improve the classification performance of the model 
- **Data**: [TREC-Dataset](https://emilhvitfeldt.github.io/textdata/reference/dataset_trec.html) (Question classification)
- **Baseline**: [Pretrained-BERT](https://arxiv.org/abs/1810.04805) & [EDA (Easy Data Augmentation)](https://arxiv.org/abs/1901.11196)

<br>

## Codes
### 1️⃣ Train_BERT-Triplet.ipynb
-  objective: sentence vectors of the same class are closely distributed in vector space


### 2️⃣ Data_Augmentation.ipynb
- N candidate data is augmented by previous augmentation method, and M data is selected as augmented data (𝑁>𝑀)

### 3️⃣ Finetune_BERT-Triplet.ipynb
- Fine-tune pretrained-BERT using both original and augmented data


### 4️⃣ Test_BERT-Triplet.ipynb
- Evaluate classification performance
