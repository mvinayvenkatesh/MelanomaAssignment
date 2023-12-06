# Project Name
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## General Info
- Images loaded from Google drive
- Different approaches configured and tested


**Finding on the first base model**
- The model is overfitting because we can also see difference in loss functions in training & test around the 10-11th epoch
- The accuracy is just around 75-80% because there are enough features to remember the pattern.
- But again, it's too early to comment on the overfitting & underfitting debate

**Finding from Second Model**
- There is no improvement in accuracy but we can definitely see the overfitting problem has solved due to data augmentation 
- We can increase the epochs to increase the accuracy so it's too early for judgement 

**Finding from Third Model**
- Accuracy on training data has increased by using Augmentor library
- Model is still overfitting
- The problem of overfitting can be solved by add more layer,neurons or adding dropout layers.
- The Model can be further improved by tuning the hyperparameter


## Technologies Used
- Jupyter Notebook 6.5.2
- GitHub 
- colab.research.google.com


## Acknowledgements
Give credit here.
- Upgrad tutorials


## Contact
Created by [@mvinayvenkatesh] - feel free to contact me!

