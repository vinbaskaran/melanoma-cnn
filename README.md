# Melanoma Detection Assignment
> To build a multiclass classification model using a custom convolutional neural network in TensorFlow, which can accurately detect melanoma. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
- Dataset used : https://drive.google.com/file/d/1xLfSQUGDl8ezNNbUkpuHOYvSpTyxVhCs/view
- There were 9 categories in the data.
![image](https://github.com/user-attachments/assets/2ce6f6bb-e552-4839-9ed9-4977b19e5f66)



## Conclusions
Final Model Details : 
- Due to Class Imbalance, Data Augmentation technique has been used to increase the records with help of augmentor. 
- Dropout layers were added to address regularization. 
- Rescaling used for Normalization. 
- Due to GPU restrictions, simple network has been used instead of deeper network which could have helped model to learn features better.
- Validation accuracy has improved due to data augmentation addressing class imbalance.
- The validation accuracy is close to training accuracy, indicating that overfitting is reduced.
- Accuracy is still below 70%: The model might be underfitting and can be further optimized.
  
<img width="746" alt="image" src="https://github.com/user-attachments/assets/61b93c6b-283b-4d74-90d9-16958b7d168a" />

![image](https://github.com/user-attachments/assets/35c26a3f-3587-40fd-8251-bbd688a0cd53)


## Technologies Used
- tensorflow: 2.18.0
- matplotlib: 3.10.0
- numpy: 1.26.4
- pandas: 2.2.2
- PIL: 11.1.0
- Augmentor: 0.2.12
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@vinbaskaram] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
