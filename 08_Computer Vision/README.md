<h1> Face Mask Segmentation </h1>
<h2> Project Description: </h2>
In this hands-on project, the goal is to build a Face Mask Segmentation model which includes building a face detector to locate the position of a face in an image.
<h2> Data Description: </h2>
<b> WIDER Face Dataset </b> <br>
WIDER FACE dataset is a Face Mask Segmentation benchmark dataset, of which images are selected from the publicly available WIDER dataset. 
This data have 32,203 images and 393,703 faces are labeled with a high degree of variability in scale, pose and occlusion as depicted in the sample images.
In this project, we are using 409 images and around 1000 faces for ease of computation. <br> <br>
We will be using transfer learning on an already trained model to build our segmenter. We will perform transfer learning on the MobileNet model which is already trained to perform image segmentation. 
We will need to train the last 6-7 layers and freeze the remaining layers to train the model for face mask segmentation. To be able to train the MobileNet model for face mask segmentation, 
we will be using the WIDER FACE dataset for various images with a single face and multiple faces. 
The output of the model is the face mask segmented data which masks the face in an image. We learn to build a face mask segmentation model using Keras supported by Tensorflow.
<h2> Objective </h2>
In this problem, we use "Transfer Learning" of an Image Segmentation model to detect any object according to the problem in hand.
Here, we are particularly interested in segmenting faces in a given image
<h2> Project Steps </h2>
● Load the dataset given in form .npy format. <br>
  ○ We have already extracted the images from wider face-dataset and added it in the file images.npy. You can directly use this file for this project.<br>
  ○ “images.npy” contains details about the image and it’s masks, there is no separate CSV file for that<br>
  ○ There is no separate train and test data given<br>
● Create Features(images) and labels(mask) using that data.<br>
● Load the pre-trained model and weights.<br>
● Create a model using the above model.<br>
● Define the Dice Coefficient and Loss function.<br>
● Compile and fit the model.<br>
● Evaluate the model.<br>
