<h1>SVHN Image Classification using Neural Network </h1>
<h2> Overview </h2>
Recognizing multi-digit numbers in photographs captured at street level is an important component of modern-day map making. A classic example of such street-level photographs is Google’s Street View imagery comprised of hundreds of millions of geo-located 360-degree panoramic images. The ability to automatically transcribe an address number from a geo-located patch of pixels and associate the transcribed number with a known street address helps pinpoint, with a high degree of accuracy, the location of the building it represents.Recognizing numbers in photographs through OCR is limited due to the wide variability in the visual appearance of text in the wild on account of a large range of fonts, colours, styles, orientations, and character arrangements. The recognition problem is further complicated by environmental factors such as lighting, shadows, specularities, and occlusions as well as by image acquisition factors such as resolution, motion, and focus blurs.  
<h2> Objective </h2>
The objective of the project is to learn how to implement a simple image classification pipeline based on a deep neural network and understand the basics of Image Classification.

The goals of this project are as follows:

1. Read the data from the h5py file and understand the train/test splits <br>
2. Reshape and normalize the train and test features <br>
3. One hot encode the labels for train and test data <br>
4. Define the model architecture using TensorFlow with a flatten layer followed by dense layers with activation as ReLu and softmax <br>
5. Compile the model with loss as categorical cross-entropy and adam optimizers. Use accuracy as the metric for evaluation <br>
6. Fit and evaluate the model. Print the loss and accuracy for the test data <br>
<h2> Data Set: </h2>
SVHN is a real-world image dataset for developing machine learning and object recognition algorithms with the minimal requirement on data formatting but comes from a significantly harder, unsolved, real-world problem (recognizing digits and numbers in natural scene images). SVHN is obtained from house numbers in Google Street View images.
