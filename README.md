# Facial_emotion_recognition

Facial expression for emotion detection has always been an easy task for humans, but achieving the same task with a computer algorithm is quite challenging. With the recent advancement in computer vision and machine learning, it is possible to detect emotions from images. In this report we represent a facial emotion recognition system using convolutional neural networks (CNN). The CNN is explained in details in the following sections. The current approaches primarily focus on facial investigation keeping background intact and hence built up a lot of unnecessary and misleading features that confuse CNN training process. The current manuscript focuses on six essential facial expression classes reported, which are anger, sad, happy, feared, surprised, and neutral. The CNN algorithm presented in this manuscript aims for expressional examination and to characterize the given image into these Six essential emotion classes. Supervisory data were obtained from the stored database of around 28,000 images of different people’s faces.

## Step: Training CNN model. 
Once the datasets for training and testing have been loaded, we can now train a convolutional neural network (CNN) model.
This step when triggered, will train the model using the loaded training face images and it will perform validation using 20% of the training set. The CNN is mainly composed of 4 convolutional layers, 1 max pooling layers, and 1 dropout layer.  The first convolution layer uses 15 filters output volume. Then it is followed by a 2D maxpooling layers to subsample the data which is 5x5 common dimensions or the kernel size.  The next layer is another convolutional layer of 15 filters with 5x5 for kernel size. Afterward, we placed a dropout layer to remove some redundant neurons and immediately followed by two convolutional layers of 10 filters, 5-by-5 kernel size and 5 filters,
3-by-3 kernel size.  The final layer is fully connected with 1000 filters and softmax layer is used for mapping the probability of classification.  All layers preceding the softmax layer to make use of relu activation function.


## More infomation 

Artificial Intelligence  can  be  used to  solve  intriguing  tasks such  as   emotion   detection,   although   this   task   was  quite convolute even more when using a great  number of images. We   humans   also   sometimes   make   a   mistake   while  recognizing   someone’s   emotion   so   is   our   program.   The optimum accuracy was nearly 89.6%.



