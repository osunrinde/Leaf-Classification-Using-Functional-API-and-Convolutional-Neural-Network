# Leaf-Classification-Using-Functional-API-and-Convolutional-Neural-Network
The objective of this project is to use binary leaf images and extracted features, including shape, margin &amp; texture, to accurately identify 99 species of plants using Functional API and Convolutional Neural Network

# Leaf Classification Using Functional API and Convolutional Neural Network

There are estimated to be nearly half a million species of plant in the world. Classification of species has been historically problematic and often results in duplicate identifications.
# Project Objective
The objective of this project is to use binary leaf images and extracted features, including shape, margin & texture, to accurately identify 99 species of plants. Leaves, due to their volume, prevalence, and unique characteristics, are an effective means of differentiating plant species. They also provide a fun introduction to applying techniques that involve image-based features.

As a first step, try building a classifier that uses the provided pre-extracted features. To successfuly solve this problem, I developed a machine learning model using the functional api and convolutional neural network techniques. The functional api was developed to classify the leaves into their respective species based on the leaf images and their corresponding features (margin, shape, texture, etc). The convolutional neural network classified the leaves into their respective species based on their images
## Acknowledgements

 - https://www.kaggle.com/
-  James Cope, Thibaut Beghin, Paolo Remagnino, & Sarah Barman of the Royal Botanic Gardens, Kew, UK
- Charles Mallah, James Cope, James Orwell. Plant Leaf Classification Using Probabilistic Integration of Shape, Texture and Margin Features. Signal Processing, Pattern Recognition and Applications, in press. 2013.

## Authors

- [@osunrinde](https://github.com/osunrinde)






## Installation

The following libraries are needed for this project:

Pandas

Numpy

Seaborn

Mathplotlib

Scikit Learn

```bash
  import Pandas
  import Numpy
  import Mathplotlib
  import Seaborn
  import sklearn
  
```
    
## Datasets
The DATASET used for this analysis can be find here: https://www.kaggle.com/c/leaf-classification

## Results
The goal of this project is to built an Image Classifier model. Hence, I compared the convolutional neural network model which is designed strictly to accept imaages as input with the functional api model. 

The Functional API which takes both images and the features from the CSV files as input has an accurracy of 86% while the convolutional neural network (Images alone) has an accuracy of 70%.

The functional API performed better because than the convolutional network beacuse it accepts features that describes each leaves as one of its input (CSV file). The Convolutional neural network can be improved if data augumentation is carried out.

Hence, based on the analysis, the **FUNCTIONAL API** as the best model to make further predictions.

## Further analysis
Data Augumentation can be carried out to improve the accuracy of the CNN. Also, more hidden layers can be added (Overfitting/Underfitting of the model should be watched out for when doing this.)
## License
Copyright: 2022 [@osunrinde](https://github.com/osunrinde)



DATA ACCESS AND USE:The use of the dataset for any research is licensed by [Creative Commons Attribution-NonCommercial-ShareAlike](https://creativecommons.org/licenses/by/4.0/)
