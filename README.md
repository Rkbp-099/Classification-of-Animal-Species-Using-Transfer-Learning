# Classification-of-Animal-Species-Using-Transfer-Learning
Transfer learning Project

1. Implemented transfer learning with state of the art neural network architectures like ResNet50, InceptionV3, VGG16 to identify and  categorize images of 10 different animal species.
2. Image Augmentation is done to reduce overfitting and improve overall model validation accuracy
3. Technologies used: Python, Keras, tensorflow

### Results
| Model                    	| Training Data 	| Accuracy 	|
|--------------------------	|---------------	|----------	|
| vgg16                    	| Img1000       	| 82.92%   	|
| ResNet50                 	| Img1000       	| 92.8%    	|
| ResNet50 + Fine Tuning   	| Img5000       	| 96.09%   	|
| InceptionV3              	| Img1000       	| 96.66%   	|
| InceptionV3 + FineTuning 	| Img5000       	| 97.81%   	|

This repository only contains the test results and Codes of the separate models. For detailed files and models please visit https://drive.google.com/drive/folders/13Cl3aQ5qnSDtmp0uMGLr7yK96_j2DvEI?usp=sharing