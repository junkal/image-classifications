# Image Classifications
 
Collection of transfer learning scripts and fine tuning scripts using the [flowers dataset](https://www.kaggle.com/datasets/alxmamaev/flowers-recognition) as the training & test data. Data set has 4317 images distributed across 5 classes. The data is split up using train_test_split with 80:20 split ratio.
* Train Data: 3453 images
* Test Data: 864 images

![tulip](https://user-images.githubusercontent.com/6497242/166263485-a145e7f2-8854-4674-8cd3-8556d210acef.jpeg)

## Models

|**Model** | **Transfer Learning** | **Fine Tuning** | **Optimiser** |**Precision** | **Recall** |**F1 Score** |**Inference Time (s)** |
|:---: | :---: | :---:| :---:| :---:| :---:|:---:|:---:|
|InceptionV3 | 10 Epochs | 5 Epochs| Adam | 0.86| 0.85| 0.85|0.62 |
|VGG16 |TBD |TBD |TBD | TBD|TBD|TBD|TBD|TBD|

