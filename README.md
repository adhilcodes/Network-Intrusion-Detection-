# Network Intrusion Detection approach using Machine Learning and Deep Learning 

Comparing the efficiency of several machine learning models in detecting jamming signals. We investigated the types of signal features that identify jamming signals, and generated a large dataset using these parameters. Using this dataset, the machine learning algorithms were trained, evaluated, and tested. These algorithms are random forest, support vector machine, and neural network.

## Dataset
The [NSL-KDD dataset](https://www.unb.ca/cic/datasets/nsl.html) from the Canadian Institute for Cybersecurity (updated version of the original KDD Cup 1999 Data (KDD99). It was created using a cyber range, which is a small network that is created specifically for cybersecurity professionals to practice attacks against realistic targets. Network packet data was captured from the cyber range and processed using an intrusion detection system, called Bro-IDS

![image](https://user-images.githubusercontent.com/65992809/181878247-57c817d1-b3e0-415a-a36d-33e43225daa2.png)


## Machine Learning Models used

 - Linear Support Vector Machine (LSVM)

 - Random Forest Classifier(RFC)

 - Multi-Layer Perceptron (MLP)
 
# Project Pipeline

 - **Data Preprocessing**
 - **Data Normalization**
 - **One-hot-encoding**
 - **Feature Extraction**
 - **Splitting the Dataset**
 - **Multi-class Classification:** Attack label (‘label’ attribute) is classified into five categories ‘normal’, ‘U2R’, ‘R2L’, ‘Probe’, ‘Dos’.


# Results

 - **Linear Support Vector Machine (LSVM)**
 
 Support vector Classifier accuracy is **94.58309519273513**

![image](https://user-images.githubusercontent.com/65992809/181593352-d2e6ef7c-04a7-42f1-9917-070da6e4a535.png)

 - **Random Forest Classifier(RFC)**

Random Forest Classifier accuracy is  **96.9994284625643**

![image](https://user-images.githubusercontent.com/65992809/181593654-055cabb7-1bf1-46d1-b6d2-57c543a608e6.png)

 - **Multi-Layer Perceptron (MLP)**
 
 Multi-Layer Perceptron - Accuracy: **86.7530345916748**
 
![image](https://user-images.githubusercontent.com/65992809/181593970-32b0a1b7-cc04-4dea-9068-b9cbd677c9b1.png)
![image](https://user-images.githubusercontent.com/65992809/181593986-f4c65364-a6fd-4aeb-96a4-8c2ffddf8010.png)


