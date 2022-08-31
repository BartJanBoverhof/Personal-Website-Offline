+++
title = "Projects"
description = "Projects"
date = "2021"
author = "Bart-Jan Boverhof"
+++



Listed here are my recent projects. For a more comprehensive overview see my [CV](https://bartjanboverhof.github.io/cv/cv.pdf).

---
# PhD Health Technology Assessment of Artificial Intelligence 
###### May 2020 - present 
![Erasmus](/images/erasmus.png)
The objective of my PhD project is to improve the HTA methodology in order to evaluate medical artificial intelligence (AI). There are many AI applications with the potential to personalize prevention and treatment and improve the quality of the healthcare system. AI applications have some distinctive features that call for an adaptation of the standard HTA methodology. The term AI does not refer to just a single intervention but a complex package of data collection tools, data analysis methods, algorithms, and decision rules that trigger further action. In cases where the AI application is self-learning, its performance can improve over time. AI applications may present issues with transparency and explainability. Moreover, AI applications may have far-reaching impacts on the clinical and administrative activities of organizations and health systems.
 
The focus of this project is to develop a comprehensive evaluation methodology that takes these distinctive features into account and helps to assess the broad societal value of AI applications, to support their use in a responsible way. This methodology is tested in several case studies.

---

# Masterthesis Project 
###### September 2020 - May 2021 
![Thesis](/images/thesis.png)
<br>  

*Abstract*  
The approach of using physiological sensors for the assessment of mental workload has gained in popularity in recent years. We utilized three physiological sensors in predicting mental workload, being electroencephalography (EEG), photoplethysmography (PPG) and galvanic skin response (GSR). Deep learning poses a promising, yet novel, approach towards the modeling of such sensory data. Four deep neural network architectures were created and contrasted in their performance. Three out of four were specified to predict workload based on on a single of the aforementioned physiological sensors, whilst the fourth architecture was a joint neural network combining all physiological signals into a single model. In this study we investigated 1) which physiological sensor individually constitutes the most adequate predictor of mental workload, and 2) whether an approach utilizing multiple sensors simultaneously (i.e. multimodal) is preferable over the approaches utilizing just one. Altogether the EEG-only architecture was found to perform best displaying a mean absolute error of 0.110. We thus conclude that EEG may be considered the most adequate predictor of workload. A mean absolute error of 0.119 was found for the GSR-only architecture. Against expectations, the multimodal approach was outperformed by both aforementioned architectures, displaying a mean absolute error of 0.128. The PPG-only architecture was found to perform worst, displaying a mean absolute error of 0.136. We posed several explanations that help rationalize why the multimodal architecture was found to perform suboptimal, one being an imperfect model architecture, and another being overfitting as resulting from a limited amount of data. Regardless, we demonstrated that the differences in performance across the four network architectures were rather small, i.e. all four neural network architectures performed adequately. 

The thesis as well as accompanying code can be found on my GitHub page, via [this link](https://github.com/BartJanBoverhof/Masterthesis).

---


<br>  
<br>  
<br>  

# [ASReview](https://www.asreview.nl) Internship 
###### May 2021 - August 2021

![ASReview](/images/asreview.png)


Systematic Reviews are “top of the bill” in research. The number of scientific studies are increasing exponentially in many scholarly fields. Performing a sound systematic review is a time-consuming and sometimes boring task. The ASReview software is designed to accelerate the step of screening abstracts and titles with a minimum of papers to be read by a human with no or very few false negatives. The Active learning for Systematic Reviews [ASReview](https://www.asreview.nl) project, publised in Nature Machine Intelligence, implements machine learning algorithms that interactively query the researcher. This way of interactive machine learning is known as Active Learning. ASReview offers support for classical learning algorithms and state-of-the-art learning algorithms like neural networks.

In this project I developed various deep-learning models usable with the ASReviews software. The convolutional neural network plug-in is published on [GitHub](https://github.com/BartJanBoverhof/asreview-cnn-hpo) as well as [Zenodo](https://zenodo.org/record/5482149#.Yw9UFi8RrUI). A report of the accompanied simulation study can be found by following [this link](https://github.com/BartJanBoverhof/asreview-cnn-hpo/blob/main/report/simulation_report.pdf).
	