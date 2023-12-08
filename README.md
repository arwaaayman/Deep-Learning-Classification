# Deep-Learning-Classification
The goal is to classify the images and train a model to predict any unseen images with a good accuracy using Convolutional neural network(CNN)



#### **Dataset description**

- **25,000** image of size 150x150
- Training data 14,000 image
- Validation data 3,000 image 
- Testing data 7,000 image

**Target labels:**  (buildings, forest, glacier, mountain, sea, street)

```
📦Dataset
 ┣ 📂seg_pred
 ┃ ┗ 📂seg_pred
 ┣ 📂seg_test
 ┃ ┗ 📂seg_test
 ┃ ┃ ┣ 📂buildings
 ┃ ┃ ┣ 📂forest
 ┃ ┃ ┣ 📂glacier
 ┃ ┃ ┣ 📂mountain
 ┃ ┃ ┣ 📂sea
 ┃ ┃ ┗ 📂street
 ┗ 📂seg_train
 ┃ ┗ 📂seg_train
 ┃ ┃ ┣ 📂buildings
 ┃ ┃ ┣ 📂forest
 ┃ ┃ ┣ 📂glacier
 ┃ ┃ ┣ 📂mountain
 ┃ ┃ ┣ 📂sea
 ┃ ┃ ┗ 📂street
```

**Source of data:** [Intel Image Classification | Kaggle](https://www.kaggle.com/datasets/puneet6060/intel-image-classification)



#### **Data preprocessing**

- Apply data **augmentation** to increase the amount of data by generating new data points from existing data. This includes adding minor alterations to data or using machine learning models to generate new data points in the latent space of original data to amplify the dataset.



#### **Model**

- Classifying the images and train a model to predict any unseen images with a good accuracy using **Convolutional neural network(CNN)**
- Convolutional layer reduces the high dimensionality of images without losing its information. That is why CNNs are especially suited for this use case.
