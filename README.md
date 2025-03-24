**Brain Tumor Detection Using VGG16 and Random Forest/SVM**

This project implements a brain tumor classification model using transfer learning from the VGG16 architecture and classifies the extracted features using Random Forest and SVM (Support Vector Machine). The dataset consists of labeled brain MRI images with tumors and without tumors, and data augmentation techniques are applied to increase the dataset's size for training. The pipeline involves feature extraction from the VGG16 pre-trained model, followed by training both SVM and Random Forest classifiers to evaluate the performance of each.




**Prerequisites**

To run this project, you need the following libraries installed:

pip install tensorflow opencv-python scikit-learn matplotlib seaborn numpy pandas




**Steps**

Load Data: MRI images labeled as "Tumor" or "No Tumor."

Data Augmentation: Rotate, zoom, shift, and flip images for variety.

Feature Extraction: Use pre-trained VGG16 to extract features.

Classify: SVM and Random Forest classify the images.

Evaluate: Compare models' accuracy and performance.




**Results**

Model	Accuracy

SVM	97%

Random Forest	89%




**Visualization**

Feature Maps: Visualize 16 VGG16 filters.

Model Comparison: Bar chart comparing SVM vs Random Forest accuracies.




**Conclusion**

The SVM model outperforms Random Forest in detecting brain tumors with higher accuracy. This approach combines deep learning with traditional ML for effective medical image classification.

