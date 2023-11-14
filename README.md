# assignment3CAP6776
Image Classification using Tensorflow MobileNet

Assignment steps:
-	Select and load an image for classification.
-	Pre-process the image.
-	Create MobileNet model.
-	Classify image with MobileNet model.
-	Create MobileNetV2 model.
-	Classify image with MobileNetV2 model.
-	Report the top predictions of both models.
-	
Classifiers:
The classifiers used in this assignment are MobileNet and MobileNetV2. These classifiers are previously trained Convolutional Neural Network models used in image classification and mobile vision. These models contain a reduced number of parameters and layers, when compared to other classifiers, resulting in a lightweight network.

Data:
For this experiment, two different images were used for classification.
Image 1 -> German shepherd
Image 2 -> Lion

Image pre-processing: 
The images were processed before being fed into the models for classification. This process was as follow:
-	Converting image to array using the image library from tensorflow.
-	Expanding the dimensions of the array to 4 (previously 3 dimensions for RBG) as needed by the model.
-	Using the tensorflow library preprocess_input on the expanded array.
