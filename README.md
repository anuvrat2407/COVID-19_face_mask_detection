# **Real Time COVID-19 Face Mask Detection**

---


A real time COVID-19 face mask detection using webcam and fine tuning the VGG16 keras model.
### **Abstract**

---
This projects aims to automatically detect whether a person is wearing a mask or not in real time using webcam. To accomplish this task, we fine tuned the VGG16 keras model. The webcam detect the frontal faces using the Viola Jones Haar Cascade Classifier ***("haarcascade_frontalface_alt2.xml")*** and then resize the croped face detected from original frame into 224x224 BGR image. This 224x224 BGR image is then inputted to the fine tuned VGG16 keras model which classify the face as masked or not-masked with certain accuracy.
### **Dataset**

---
I have used [Face Mask 12k image dataset](https://www.kaggle.com/ashishjangra27/face-mask-12k-images-dataset) from kaggle to train VGG16 classification model.
### **Environment**

---


I used the google colab gpu to train the classification model(VGG16) with tensorflow version 2.2.0 but for real time detection I load the model files and used them in my jupyter notebook as webcam(hardware) can not be mounted with google colab for real time detection or atleast I do not know.
### **Software**

---
In my Jupyter Notebook I have -

*   Tensorflow CPU version 2.1.0
*   keras version 2.2.4-tf

*   Open CV version 3.4.2
*   Python version 3.7.7

installed.
### **Result**

---
I am here attaching some of the screenshots captured during the real time testing.

![Screenshot (1075)](https://user-images.githubusercontent.com/60260268/90012421-f7f3c100-dcc0-11ea-806b-ffbd99394e8f.png)


![Screenshot (1077)](https://user-images.githubusercontent.com/60260268/90012645-6769b080-dcc1-11ea-808e-0f222e3acbe6.png)
