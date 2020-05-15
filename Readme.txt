Image captioning Using TensorFlow and Keras

- We are using 3 model Resnet50, Inception V3 and Exception CNN model along with LSTM language model.
- The code is developed using Google Colab. The Flicker8k dataset is used for image captioning.Download the dataset using this link https://www.kaggle.com/shadabhussain/flickr8k. 
- The dataset contains two folder Fliker8k_dataset which contains images and Flicker8k_text which contains captions.

Given three .ipynb notebook file
	- ResNet50LSTM_image_caption.ipynb
	- InceptionV3LSTM_image_caption.ipynb
	- ExceptionLSTM_image_caption.ipynb

One way to run model using google Colab. 
1. Download the Flicker8k dataset and upload in google drive 
2. Open the notebook through google colab.
3. Change the path in notebook according to the directory structure.
4. Run and evalaute the captions.

Another way to run model using jupyter notebook. 
1. Download the Flicker8k dataset.
2. Open the code in jupyter notebook and change the path in notebook according to the directory structure.
3. Omit the drive mount cell (first cell) in the notebook.
4. Run and evalaute the captions.


NOTE: Download the dataset and change the path of images and captions text files according to the directory.

 