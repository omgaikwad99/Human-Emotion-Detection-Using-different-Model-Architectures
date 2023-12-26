# Human Emotion Recognition Model Report

#### Authors: Om Gaikwad, Ameya Deshmukh
#### University of Cincinnati

### Abstract

This research explores the comparative performance of four prominent deep learning architectures—CNN, LSTM, VGG-Net, and ResNet50—in the context of human emotion recognition. Each architecture brings unique advantages, such as temporal dependency handling, spatial feature extraction, solving vanishing gradient issues, and recognizing complex visual patterns. Performance metrics, including accuracy, precision, recall, and F1 score, are employed to evaluate these models using established emotion detection datasets. The study aims to provide insights into the distinctive contributions of each model, aiding in informed decision-making for specific applications.

### Introduction

Recognizing human emotions is crucial for artificial intelligence applications and human-computer interaction. This study compares CNN, LSTM, VGG-Net, and ResNet50 to understand their strengths and weaknesses in emotion recognition. Motivated by the distinct advantages of each architecture, the objective is to determine the most effective model or combination of models for recognizing a diverse range of emotions.

### Objectives

1. Conduct a comprehensive comparative study of CNN, LSTM, VGG-Net, and ResNet50 for human emotion recognition.
2. Evaluate each model's performance using accuracy, precision, recall, and F1 score on well-established emotion detection datasets.
3. Assess the unique contributions and limitations of each architecture in emotion recognition.
4. Translate knowledge gained from performance measurements into practical applications, considering factors like processing efficiency, scalability, and adaptability to various datasets.

### Related Studies

Previous research has highlighted the strengths of individual architectures. VGG-Net captures complex patterns, ResNet50 addresses vanishing gradient problems, LSTM models temporal dependencies, and CNNs excel in spatial feature extraction. Integration of models, such as VGG-Net with LSTM, has shown improved performance. Comparative studies stress the importance of understanding each architecture's advantages.

### Gap in Literature

While individual architecture studies exist, a comprehensive review comparing CNN 4 layers, LSTM, VGG-Net, and ResNet50 is lacking. This study aims to bridge this gap, offering insights into each architecture's contributions in identifying a wide range of human emotions.

### Method and Dataset

#### Dataset: Facial Expression Recognition 2013 (FER2013)

- Diverse dataset with 35,887 grayscale images categorized into seven emotions.
- Well-balanced categories enhance model training and evaluation.
- Challenges include visual quality and resolution affecting fine-grained characteristics.

#### Preprocessing

1. Image data scaled to 48 by 48 pixels, converted to grayscale, and reshaped into three-dimensional arrays.
2. Labels processed into category format.
3. Dataset split into 80% training and 20% testing sets.
4. Normalization using Min-Max scaling for efficient model training.

### Results

#### 1. VGGNet

- Accuracy: 73.23%
- Strengths: Consistency, simplicity, and effective capture of complex facial expression patterns.

#### 2. ResNet50

- Accuracy: 58.69%
- Strengths: Ability to handle complex gradients and patterns, addressing vanishing gradient issues.

#### 3. CNN (4 layers)

- Accuracy: 53.13%
- Strengths: Spatial feature extraction, relevant in tasks requiring nuanced facial expression analysis.

#### 4. LSTM

- Accuracy: 54.01%
- Strengths: Capturing temporal dependencies, suitable for sequential data like changing facial expressions over time.

### Discussions and Conclusions

- Each model demonstrated unique contributions.
- VGGNet stood out with an accuracy of 73.23%, emphasizing the importance of a streamlined and balanced architecture.
- Prospective courses include exploring ensemble models and fine-tuning hyperparameters for enhanced performance.
- In conclusion, understanding the advantages and disadvantages of each model aids practitioners and academics in choosing and optimizing models for emotion recognition applications.

### Citations

1. [Facial Expression Recognition 2013 (FER2013) dataset](https://dataport.ieee.org/docs/fer2013/1).
2. [DigitalScreeni, A. (2021, October 13). "239 - Deep Learning training for facial emotion detection"](https://www.youtube.com/watch?v=P4OevrwTq78&t=547s&ab_channel=DigitalSreeni)

   # Dataset
   [https://1drv.ms/u/s!AprPvJsuY4ejlR_za_BPjaeo9QsF?e=axlSgk]
