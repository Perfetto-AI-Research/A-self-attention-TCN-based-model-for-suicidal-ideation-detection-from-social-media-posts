# A-self-attention-TCN-based-model-for-suicidal-ideation-detection-from-social-media-post
## Introduction
This repository contains the implementation of the proposed method and experimental analysis of the paper “A self-attention TCN-based model for suicidal ideation detection from social media posts”, published in Expert Systems with Applications, 2024. 
In this paper, we created a novel deep-learning model that can find suicidal thoughts in social media posts, and a thorough analysis using a combination of different techniques to analyze the posts. The experimental results demonstrate the high accuracy results of our model at identifying when someone might exhibit signs of suicidal thoughts. This research could help people who are struggling with mental health by providing an early warning system.

## Practical Guideline: Proposed Model
The implementations of the proposed model, as well as the experimented state-of-the-art approaches to which we have compared our presented model, are all included in this repository. 
Executing the codes is pretty straightforward. To run the code, you should follow these steps:

    1- Installation and Importing of the required libraries, Such as Tensorflow, Scikit-Learn, NLKT, …
    
    2— Loading the dataset and preprocessing texts to remove URLs, Email addresses, Hashtags, and Punctuations, and balancing the dataset.
    
    3- Importing and loading the BERT pre-trained model.
    
    4- Defining the model
    
    5- Training the model on the training and validation dataset
    
    6- Evaluating the model on the test dataset

## Data Analysis
The analyses conducted on the suicidal tweets used in our paper include semantic analysis, sentiment analysis, and topic prediction. These analyses are all included in the Data Analysis folder. You can refer to these implementations for further analyzing the datasets, in particular suicidal tweets. Such analyses can provide a proper insight regarding the differences between a suicidal note and a typical non-suicidal tweet. 

## State-of-the-art Baselines
The recently published baselines are presented in the State of the Art Baselines folder. The execution of these models is principally similar to the practical guideline written above. Following the same process of loading, preprocessing, and balancing the datasets, defining the models, and training and evaluating these models, the mere difference is related to the model definition which is based on the architectures presented in referenced papers [[1]](#1) [[2]](#2). 

## References
<a id="1">[1]</a> 
Renjith, Shini, et al. "An ensemble deep learning technique for detecting suicidal ideation from posts in social media platforms." Journal of King Saud University-Computer and Information Sciences 34.10 (2022): 9564-9575.

<a id="2">[2]</a> 
Ghosh, Tapotosh, et al. "An attention-based hybrid architecture with explainability for depressive social media text detection in Bangla." Expert Systems with Applications 213 (2023): 119007.
