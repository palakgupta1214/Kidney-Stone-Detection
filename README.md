# Kidney-Stone-Detection
This project focuses on the automated detection of kidney stones using deep learning and image processing techniques. We utilize Convolutional Neural Networks (CNNs) to analyze non-contrast abdominal CT scan images, which can identify kidney stones with minimal manual intervention.

Key Features:
CT Scan Image Analysis: The model is trained on a dataset of over 1600 CT scan images, labeled for kidney stone presence.
Deep Learning Approach: CNNs are employed for image classification, extracting hierarchical features to detect kidney stones.
Random Search Optimization: Random search is used to optimize hyperparameters for better performance.
Preprocessing Techniques: Includes image resizing, median filtering for noise reduction, and histogram equalization for enhanced contrast.
Accuracy: The model achieves an impressive accuracy of 98.1% on test data, demonstrating its effectiveness in detecting kidney stones.

# Dataset

For the Kidney Stone Detection System, the dataset was sourced from open platforms such as Kaggle and GitHub. It contains over 1600 non-contrast abdominal CT scan images, categorized into two groups: one with kidney stones and the other without. These images were captured from patients who were suspected of having kidney-related issues, and they were annotated by experienced medical professionals.

The dataset was preprocessed by resizing the images to a uniform dimension of 128x128 pixels. It was further divided into training (90%) and testing (10%) sets, ensuring a balanced representation of both categories. This structured dataset facilitated effective training of the deep learning model for accurate kidney stone detection.

# Result 
The system achieved 98.1% accuracy in identifying kidney stones.
It reduced the need for manual analysis of CT scans, minimizing radiologist workload and improving turnaround times for diagnosis.
This project demonstrates the potential of machine learning in medical imaging, providing a robust solution for early kidney stone detection, which is crucial for preventing severe complications.
