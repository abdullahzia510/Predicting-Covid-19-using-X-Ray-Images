# MSDS19087_COVID19_DLSpring2020
This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.

### Dataset Link: 
You can download dataset from [here](https://drive.google.com/open?id=1-HQQciKYfwAO3oH7ci6zhg45DduvkpnK "Dataset Link")
### Trained Models Link: 
* You can download all trained models from [here](https://drive.google.com/open?id=13udumKPezxW8bQp4LJc1HoToKzhp4_OR)
* Experiment # 1 (Only Fully-connected on VGG-16): You can download model from [here](https://drive.google.com/open?id=1xKddrC4ONzry7hKutvkCgl3H-s5dJvuZ)
* Experiment # 2 (Only Fully-connected on ResNet-18): You can download model from [here](https://drive.google.com/open?id=1-7X0q8F_xqOAdHz-8jVleRm60_78-Gfq)
* Experiment # 3 (Fully Connected + 1 Convolution Layer on VGG-16): You can download model from [here](https://drive.google.com/open?id=1pPuYMLkKqgl6zEQpVM-zI0TsXr_dYZ6X`)
* Experiment # 4 (Fully Connected + 1 Convolution Layer on ResNet-18): You can download model from [here](https://drive.google.com/open?id=1--ZyzQe-bS0F0uzsrlfb96cjqF9pI_kr)
* Experiment # 5 (Fully Connected + few Convolution Layers on VGG-16): You can download model from [here](https://drive.google.com/open?id=1-F72FiZtLWKSLl3s_MvEHMrZAIJjEojd)
* Experiment # 6 (Fully Connected + few Convolution Layers on ResNet-18): You can download model from [here](https://drive.google.com/open?id=1-N1MitglygKWw7ZwqY-Q-nNhjtCco45u)
* Experiment # 7 (Training entire VGG-16 newtwork): You can download model from [here](https://drive.google.com/open?id=1-N6Lg4MxLf9bnxNcNufQkJ0BHavTkG8W)
* Experiment # 8 (Training entire ResNet-18 newtwork): You can download model from [here](https://drive.google.com/open?id=1-QJ40o5zTgLkY_ZqwLS8z5VSasYbO7xz)

## Task description and approach used:
  World is suffering from a global pandemic caused by a virus named Covid-19. Its symptoms are much similar to other diseases like viral flu, or SARS, or pneumonia. In this assignment we were given a dataset of 15,000 X-Ray images. These images are labeled as ‘Normal’ and ‘Infected’. What we have to do is to train a model that learn normal X-Ray images and differentiate it with Infected X-Ray images. For this task we used well known deep learning library named as ‘Pytorch’. We also used pre-trained VGG-16 and ResNet-18 models, trained on ImageNet for training of model.

## Results:
### Training only Fully connected Layers
#### VGG-16 
##### Accuracy 
Testing	Accuracy = 93.46
##### Confusion Matrix
![](images/confusion matrix exp 1.png )
