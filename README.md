# Human Perception of Navigational Affordances in Real-World Scenes

This repository contains the python code used for the ECVP Poster it contains code to visualize the used stimuli set and the reprsentational similarity analysis (RSA).


![Poster](/poster.png)

## Abstract

** Human Perception of Navigational Affordances in Real-World Scenes**

*Clemens G. Bartnik & Iris I.A. Groen*  
*Video & Image Sense Lab, Institute for Informatics, University of Amsterdam, The Netherlands*

In daily life, we move with ease through our immediate environment: We can choose different paths through the same environment, and use a variety of navigational actions, such as walking, swimming or climbing. How do we represent navigational affordances of our immediate environment and which visual features drive these representations? Recent work, focusing on walking through indoor scenes, suggests that scene layout is an important determinant. Here, we investigated which scene properties predict a larger range of navigational affordances in both indoor and outdoor environments. To address this, we curated a diverse set of 231 naturalistic real-world stimuli and collected human annotations of readily identifiable qualitative scene properties (e.g., possible navigational actions, scene layout, material properties, contained objects, scene category and possible paths) in an online experiment (*N* = 152). Using representational similarity analysis, we find that previously used properties are highly intercorrelated and only account for a small part of the navigational affordance representations (R2 < .21). Similarly, while CNNs trained for scene recognition are reasonably good at predicting human perception of objects (R2  = .41) and scene categories (R2 = .34), they perform rather poorly at predicting the navigational affordances of scenes (R2 = .21). While a visual inspection of the paths that participants drew, confirms that layout is a driving factor for consistent path annotations through the environment, this dimension alone does not seem to capture the affordances of different actions. Consequently, future models need to incorporate multiple relevant features that humans use to perceive the navigational affordances of natural scenes.




## Open notebook in jupyter nbviewer 
[![Open jupyter nbviewer](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1uFKK00fDlxtTfBLNjLTpDl37Vs5HgGwo?usp=sharing)

## About the repo 

This repo contains the notebook to run & reproduce the results form the poster:

+ **Stimuli** (t-SNE visulizations comparing our 231 naturalistic real-world stimuli set to previous datasets)
+ **Overview Gorilla Experiment**
  + Path Drawing 
  + Goal point localization
+ **Representational Similarity Anaylsis (RSA):**
  + Create RDMS for all tasks
  + Computational models
  + Correlations



## Dataset

Stimuli were 132 colored high resolution photographs depicting a diverse variety of real-world scenes viewed at eye level with unobstructed space that can be used to move through the environment using different actions. Natural real world scenes where used because they represent an ecological set of paths and action possibilities that may occur in the daily lives of the participants.
