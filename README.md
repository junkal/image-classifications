# Image Classifications
 
Collection of transfer learning scripts and fine tuning scripts using the [flowers dataset](www.kaggle.com/dataset/e0b99652b32fe1797032b4b8a9f1d1c7ebfeb44ce03ffe9bd0695c9fd913235d) as the training & test data. Data set has 11,531 images distributed across 7 classes [daisy, dandelion, lily, orchid, rose, sunflower, tulip]. The data is split up using train\_val\_test split with 70:20:10 split ratio.

* Train Data: 8069 images
* Validation Data: 2306 images
* Test Data: 1156 images

![tulip](https://user-images.githubusercontent.com/6497242/166263485-a145e7f2-8854-4674-8cd3-8556d210acef.jpeg)

## Models
|**Model**| **Dimension**|**Accuracy Score @ 10 epochs**| **Accuracy Score @ 10 epochs** | **Optimiser** |**Precision** | **Recall** |**F1 Score** |**Inference Time (s)** |
|:---: | :---: | :---:| :---:| :---:| :---:|:---:|:---:|:---:|
|VGG16|224x224|0.939|0.987| Adam |0.99| 0.99|0.99|0.195|
|InceptionV3|224x224|0.971|0.986|Adam|0.99|0.99|0.99|1.055|
|InceptionResnetV2|224x224|0.975|0.981|Adam|0.98|0.98|0.98|3.073|
|Densenet121|224x224|0.984|0.994|Adam|0.99|0.99|0.99|1.466|
|MobileNetv2|224x224|0.974|0.984|Adam|0.98|0.98|0.98|0.675|
|ResNet101|224x224|0.988|0.988|Adam|0.99|0.99|0.99|1.465|

*note: the evaluations are done on the 1156 test images
