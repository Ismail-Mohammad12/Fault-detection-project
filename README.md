# fault-detection-project

In this project, I have developed a fault detection model which takes sensor data of temperature, pressure, humidity, and vibration of machine data and predicts whether that aprticular observation of all the 4 mentioned sensor values are faulty where the mahcine has gone fault or not.


The dataset is aquired from kaggle, called as Industrial equipment monitoring dataset. It contains a total of 2000 observations, where 1400 are the normal readings and 600 are faulty readings. For training, 80% data of the normal class has been used and the rest 20 percent has been merged with the 600 observations of the faulty class as a test dataset.

The intitalization of models are as the follows:

For isolation forest a contamination of 0.05 has been used and for one class SVM, the sensittivity parametzer has been set for 0.05.

The following are the results:

Heatmap comparison:
Both the models have delivered similar kind of performance. One class SVM has a little edge with the recall of the faulty class but it is minimal.


