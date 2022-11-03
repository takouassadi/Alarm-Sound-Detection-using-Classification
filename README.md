# Alarm-Sound-Detection-using-Classification
 Desinging an alarm sound classification model and later on adapt it to each need either implemented in the car, or a bike or maybe having a mobile app that notifies 
 you while listening to music that an alarm sound is occurring.
 
 Dataset Source :
 
 Urbansound8k, there are 8732 labeled audio clips from urban sounds across 10 classes in this dataset: air conditioner, car horn, children playing, dog barking, drilling, rolling machine, gunshot, jackhammer,
 siren, and street music.
 link: https://urbansounddataset.weebly.com/urbansound8k.html
 
 Data Visualisation:
 
 ![image](https://user-images.githubusercontent.com/91010908/199801636-c4b00080-37a0-4033-831f-84600db13264.png)


 ANN Architecture:
 
 An artificial neural network (ANN) is a multi-layer fully connected neural network, as shown in the figure below.
They consist of an input layer, several hidden layers and an output layer. Every node in one layer is connected to every
other node in the next layer. We deepen the network by increasing the number of hidden layers.

![image](https://user-images.githubusercontent.com/91010908/199801831-7cae7867-c2a2-46ba-9bc7-22becc2d4f7e.png)


 Transfer Learning:
 
 we used a neural networks called VGG16 which is a transfer learning CNN model that was trained on the
ImageNet dataset, containing more than 14 million high-resolution images belonging to 1000 different labels.
To get a successful use of this CNN model, we have to reshape our input data to the dimensions that suit VGG16 input
layer. Besides, we have to make sure that we use the exact preprocessing steps to get good results.

![image](https://user-images.githubusercontent.com/91010908/199801976-69f01ba5-ab0e-4ae5-b967-cfa1c42b8a4a.png)


Referneces :
Detecting alarm sound Daniel P.W. Ellis Department of Electrical Engineering, Columbia University, New York
NY the USA.

UrbanSound8K - Urban Sound Datasets (weebly.com)

Detection of Alarm Sounds in Noisy Environments: 2017 25th European Signal Processing Conference
(EUSIPCO).

Eleni Tsalera, Andreas Papadakis and Maria Samarakou, "Comparison of Pre-Trained CNNs for Audio

Classification Using Transfer Learning". J. Sens. Actuator Netw. 2021, 10, 72. https://doi.org/10.3390/jsan10040072

https://bicycleuniverse.com/legal-ride-bike-headphones


