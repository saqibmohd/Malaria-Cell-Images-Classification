# Malaria-Cell-Images-Classification
Prediction of whether a person is affected with Malaria or not with Deep learning (Keras).
I used Malaria cell images dataset from kaggle and implemented the model on kaggle kernel. I am also providing my Kaggle Kernel link
here.

https://www.kaggle.com/mesaqib/malaria-classification

Dataset has two classes- Parasitized and Normal and we have to classify between them that whether a person is affected with Malaria (Parasitized) or he is normal. I used Keras framework to implement this deep learning model. The dataset has 27,558 total number of images of both class.

I splitted the data into training, validation and test set. Training set, validation set and test set comprise of 22046,2756 and 2756 number of images respectively. I used Keras callbacks (EarlyStopping and ReduceLRonPlateau) to control the training process. You can learn about these on Keras docs.

Finally, the model starts with 60 epochs, but at 19th epoch the process was stopped by earlystopping callback with 93 % training accuracy
and 95% test accuracy which is quite well. 
