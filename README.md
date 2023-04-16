# Pet-Pawpularity-Score-Prediction-CNNs-


## Enhanced adoption rate by identifying parts of pet photo that contribute most towards its cuteness using transfer learning techniques in Convolution neural networks and Attention Mechanism, Transformers

## Problem statement – 
  Given an image of a pet and tabular data about some features about it, determine a cuteness index by analyzing the previous popularity scores and provide what part of the image contributes most to the score.
## Approach – 
  We stacked transfer learning approaches in CNN like ResNet 50 to process the image data and Regression models to process the tabular data to train a model that predicts a popularity score for each image.
  
  To obtain the parts of an image that make it popular, we used Attention mechanism model called Vision Transformer. ViT assigns weights to all section of images according to their importance to the score. Through our analysis we found out that generally, the pet photos which were candid (where the eyes of the pet were not looking at the camera), which showed paws, ears gathered more popularity than others.
