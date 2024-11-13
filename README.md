## LUNG TUMOR SEGMENTATION USING DEEP LEARNING

The classification of lung tumors is essential for determining personalized treatment plans and improving patient prognosis. Non-small cell lung cancer (NSCLC), which accounts for the majority of cases, includes subtypes like adenocarcinoma, squamous cell carcinoma, and large cell carcinoma. Small cell lung cancer (SCLC), although less common, is known for its rapid growth and early spread. Advances in imaging and molecular diagnostics have improved the identification of these subtypes. Machine learning techniques are now being applied to automate tumor classification, utilizing vast amounts of data for more precise and rapid diagnosis. Early and accurate classification of lung tumors can significantly impact survival rates by enabling tailored therapeutic strategies and prompt intervention.

## About
<!--Detailed Description about the project-->

The brain tumor segmentation project focuses on developing an advanced deep learning model to accurately identify and delineate brain tumors from MRI scans.
Utilizing state-of-the-art algorithms, such as U-Net and CNNs, the model aims to enhance diagnostic accuracy and efficiency in clinical settings.
The project leverages various machine learning and image processing techniques to automate the segmentation process, minimizing human error and expediting diagnosis. 
By providing precise tumor segmentation, this project not only supports medical professionals in making informed treatment decisions but also contributes to the ongoing research in medical imaging and artificial intelligence applications in healthcare.

## Features
<!--List the features of the project as shown below-->
- Automated Tumor Identification  
- High Accuracy  
- Adaptability  
- Tumor Tracking  
- User-Friendly Interface  

## Requirements
* Operating System: Requires a 64-bit OS (Windows 10 or Ubuntu) for compatibility with deep learning frameworks.
* Development Environment: Python 3.6 or later is necessary for coding.
* Deep Learning Frameworks: PyTorch, PyTorch Lightning, and Torchvision for model training, along with Numpy and visualization libraries for efficient data handling and results analysis.
* Image Processing Libraries: OpenCV for image manipulation and PIL for handling and converting images, enabling efficient pre-processing and augmentation of MRI scans.
* Version Control: Implementation of Git for collaborative development and effective code management.
* IDE: Use of Google Colab as the Integrated Development Environment for coding, debugging, and version control integration.
* Additional Dependencies: Includes NumPy, Matplotlib, scikit-learn, Pandas, TorchMetrics for deep learning tasks.

## System Architecture

![image](https://github.com/user-attachments/assets/72f7dbad-4cf6-4cdd-a669-d74a7f85325b)


## Output

####  Shape of the mask :

![image](https://github.com/user-attachments/assets/4e9b385d-8f42-4381-9939-a55c7c9949ad)


#### Tumor segmentation using axial view :

![image](https://github.com/user-attachments/assets/c3a9899c-05d2-4d27-9b60-e74e91a0abda)


Detection Accuracy: 90%
Note: These metrics can be customized based on your actual performance evaluations.


## Results and Impact

The brain tumor segmentation model achieves an accuracy of **85-90% Dice Similarity Coefficient (DSC)**, effectively identifying and delineating tumor regions in MRI scans with high precision and recall.
This high accuracy validates the model’s reliability, making it a valuable diagnostic aid for medical professionals. 
It demonstrates promise in enhancing efficiency and accuracy in brain tumor detection.
The model enhances diagnostic support and treatment planning by providing precise brain tumor segmentation, aiding faster diagnoses and tailored care. 
Additionally, it supports research, increases accessibility, and holds potential for early tumor detection, improving overall healthcare outcomes.

## Articles published / References
1.Manikandan T., Devi B., Helanvidhya T. A Computer-Aided Diagnosis System for Lung Cancer Detection with Automatic Region Growing, Multistage Feature Selection and Neural Network Classifier. Int. J. Innov. Technol. Explor. Eng. 2019;9:409–413.

2.Han, S., Park, S., Kim, Y., Jang, J., & Song, S. H. (2023). A deep learning approach for lung tumor segmentation in CT scans using 3D CNN with hybrid loss functions. Bioengineering, 10(8), 981. https://doi.org/10.3390/bioengineering10080981 

3.Sun, W., Zheng, B., & Qian, W. (2017). Computer aided lung cancer diagnosis with deep learning algorithms. IEEE Transactions on Medical Imaging, 36(5), 1189–1199. 






