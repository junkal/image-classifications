# Image Classifications
 
Collection of transfer learning scripts and fine tuning scripts using the [flowers dataset](www.kaggle.com/dataset/e0b99652b32fe1797032b4b8a9f1d1c7ebfeb44ce03ffe9bd0695c9fd913235d) as the training & test data. Data set has 11,531 images distributed across 7 classes [daisy, dandelion, lily, orchid, rose, sunflower, tulip]. The data is split up using train\_val\_test split with 70:20:10 split ratio. All the models are trained using images resized to dimension 224 x 224.

* Train Data: 8069 images
* Validation Data: 2306 images
* Test Data: 1156 images

![tulip](https://user-images.githubusercontent.com/6497242/166263485-a145e7f2-8854-4674-8cd3-8556d210acef.jpeg)

## Transfer Learning Comparisons
|**Model**| **Accuracy Score @ 10 epochs (%)**| **Optimiser** |**Precision** | **Recall** |**F1 Score** |
|:---: | :---: | :---:| :---:| :---:| :---:|
|VGG16|93.77|Adam |0.94| 0.94|0.94|
|InceptionV3|96.80|Adam|0.97|0.97|0.97|
|InceptionResnetV2|97.58|Adam|0.98|0.98|0.98|
|Densenet121|98.62|Adam|0.99|0.99|0.99|
|MobileNetv2|97.75|Adam|0.98|0.98|0.98|
|ResNet101|98.88|Adam|0.99|0.99|0.99|

*note: the evaluations are done on the 1156 test images
