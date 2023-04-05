# Tomato-Plant-Disease-Detection-Using-Machine-Learning
I have created a machine learning model using MobileNetV1 to classify healthy and unhealthy tomato plants.  This allows the model application to run efficiently and in a timely manner on limited hardware devices such as Arduino.



🔥 (Face recognition for smart attendance system using deep learning, published in November 2021) implemented (MobileNet trained on single GPU) an run in microcontroller arduino. This is an Documentation Implementation.🔥

This study explores and proposes a model of machine learning algorithm namely CNN MobileNet, to run on small IoT-based devices. After some experiments, it was found that MobileNet can be used for this particular purpose. Furthermore, this research also shows a new contribution regarding the implementation of machine learning for disease detection into an IoT microcontroller commonly used for irrigation and soil moisture observation. The proposed model in this study has been tested in real-world experiments for Tomato plant disease detection with an approximate accuracy of 91.45%.

Link Paper: [Journal of Theoretical and Applied Information Technology (JATIT)](http://www.jatit.org/volumes/Vol100No21/12Vol100No21.pdf)


## Data Preparation

Download the data from here : [Dataset]()

After you download the dataset from the link above you can change the directory based on your local or your files in google colab (i recomendded to run or do experiment in google colab)

### IPYNB Files
-The first IPYNB file is the MobileNetV1 code without augmentation in dark or light conditions.
-The second IPYNB file is the MobileNetV1 code with augmentation in dark conditions.
-The third IPYNB file is the MobileNetV1 code with augmentation in bright conditions.


After the model has been trained for evaluation and testing, the model to be used is converted into .json to be used as an API on the website below

[UI Website for capture, receive the result of the classfication and soil moisture percentage] (https://github.com/galuhputraa/johfarrell.github.io)

![Screenshot 2023-04-05 115404](https://user-images.githubusercontent.com/79509420/229984356-255795fe-bd44-41c8-9bfa-938e9f4c5e2e.png)
