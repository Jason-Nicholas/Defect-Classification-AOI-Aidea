# Defect-Classification-AOI-Aidea
Automated Optical Inspection (AOI) [1] is a high-speed and high-precision optical image inspection system that uses machine vision as the standard inspection technology to improve the shortcomings of traditional manual inspection using optical instruments.\
\
In the training process I use the single CNN models using Efficient Net. I change the epochs and learning rate of the model manually, I don't use an automatic learning rate at the time. 

# Steps
1. Here we use the data from Industrial Technology Research Institute - Aidea to classify the defect. Unzip the file, it includes:

* train_images.zip： 2528 images.
* test_images.zip：10142 images.
* train.csv：two columns, ID and Label respectively.
* test.csv：two columns, ID and Label respectively.
* ID is for the name of the png file. Label is for the class
(0: normal, 1: void, 2: horizontal defect, 3: vertical defect, 4: edge defect, 5: particle)

2. Create a folder. Put the file inside the floder. And create
   
* Train_image
* Test_image
* Run the py file.

# Results
99.45745 % in accuracy (27th)
![Screenshot (421)](https://github.com/JasonNiicholas/Defect-Classification-AOI-Aidea/assets/147288344/29eec823-cd6f-42df-9410-5b272b4feb76)


# Reference
https://aidea-web.tw/topic/285ef3be-44eb-43dd-85cc-f0388bf85ea4?lang=en

# Special Thanks
Asia University Taiwan - AI Summer Program 2023\
Aidea 
