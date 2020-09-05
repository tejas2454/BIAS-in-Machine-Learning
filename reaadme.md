# INTRODUCTION
The assignment focuses on bias in Artificial Intelligence. The sources of bias, detection, and mitigation are the key points covered under this assignment. The assignment is divided into 2 parts, the first one focuses on evaluation metrics and detection of bias in the system. This is performed on MNIST data, and bias detection is done for ‘1’ and ‘7’ in the dataset. The former one focuses on neural network performance for detecting the bias and mitigating the bias via Data addition and multitasking techniques.
# MATERIALS
1. Data Sets
1. http://yann.lecun.com/exdb/mnist/
2. https://drive.google.com/file/d/1WYb3Xonb52ZPOpyN58t0WTQPXUnwDg0U/view?usp=sharing
1. Google Colab
2. Libraries
1. Sklearn
2. Numpy
3. Matplotlib
4. OpenCV
# PROCEDURE
## Question 1
1. access MNIST Dataset and create Training-Testing Dataset(randomizing data)
2. Segregate 1’s(6000) and 7’s(500) data and labels
3. Take 3 different 7’s samples of 500
4. Train SVM and Neural Network Model for 3 different training sets
5. Test respective models and find confusion matrix and Prediction probability
6. Find Mean Accuracy and standard deviation
7. Plot ROC and Precision-Recall for different training set
## Question 2
1. Access the images from provided folders, create training and testing dataset from folders (1) “.\specs_train”, (2) “.\specs_test”, (3) “.\nonSpecs_train”, (4) .\nonSpecs_test”, and (5) “.\data”
2. Resizing images to 32*32
3. Training neural network of architecture [ 128 -- 128 -- 128 -- 64 -- 1 ], activation function ‘sigmoid’ used
4. Finding out bias with the help of the confusion matrix
5. Mitigating the bias by:
e. 1. DATA method (Training using more data): You may use more data for training. Use (5) “.\data” folder for extra images.
e. 2. ALGORITHMIC method: Alter loss function to incorporate more challenges. Use a multi-tasking approach to achieve your aim.
# DATA
Dataset
	URL
	MNIST Data Set
	http://yann.lecun.com/exdb/mnist/
	Face Image Dataset
	https://drive.google.com/file/d/1WYb3Xonb52ZPOpyN58t0WTQPXUnwDg0U/view?usp=sharing


	









-----------------------FOR DETAILS REFER MNIST and FACE DATASET PDF’s----------------------