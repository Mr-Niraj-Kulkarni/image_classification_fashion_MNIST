#Image Classification using Fashion MNIST Dataset 

#Fashion MNIST Dataset
for this project i have used fashion mnist dataset which consist of grayscale images of size 28*28 .
It consist of 60,000 training  examples and a testing set   of 10,000 examples.
Labels are as follows :
0 T-shirt/top
1 Trouser
2 Pullover
3 Dress
4 Coat
5 Sandal
6 Shirt
7 Sneaker
8 Bag
9 Ankle boot


#steps to reproduce python files 
1.download the dataset from the following link -https://www.kaggle.com/zalando-research/fashionmnist
2.Extract the dataset into data folder inside the research folder.
3.Rename the training and testing files as  train.csv and test.csv.
4.Run the train.py file for training the model (you can change the hyperparameters inside the file)
5.Run the inference.py file the to evaluate the trained model on test set and get the latency and accuracy .
6.Run the converttoonnx.py file to convert the serialized model  to onn. form .
6.the trained model file - image_classification_model.pth is in  the models folder.
7.the onnx file- imageclassifier.onnx is in the models folder. 



#Running the TensorRT Inference Model 
1.Compile this sample by running `cmake "CMakeList.txt" in the `inference directory.
2.run the ImageClassification.sln file 
3.directly run exe file from inference\x64\Debug\ImageClassification.exe 
4.include the cuda include files and cuda libraries 
	(C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v10.2\include)
	(C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v10.2\lib\*.lib)
5. also add the tensorRT lib files 
	
 
#Personal Information
Name: Niraj Rajendra Kulkarni 
phone: 8975333826
Email: nirajkulkarni2609@gmail.com
Address: Sinhagad Road, Pune .
Date of Birth: 26-09-1998
College:PVG's College of Engineering and Technology Pune 
Qualification: B.E Computer Engineering (2016-2020)


