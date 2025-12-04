# Spotted-Cat-Image-Classifier
The Spotted Cat Image Classifier is a deep learning project focused on identifying and classifying images of spotted cats, specifically leopards, jaguars, and cheetahs. Using computer vision techniques, this tool automates the detection and differentiation of these species.
![image](https://github.com/user-attachments/assets/816e99e0-bee6-4fb4-b3e5-8db5415a1979)

<!-- Grad-CAM placeholder -->
![Grad-CAM: model focus visualization](https://github.com/user-attachments/assets/962c3a66-f9d0-4b7b-bca0-a06fe50d4ab5")

**Motivation**

As an enthusiast of wildlife and machine learning, I created the Spotted Cat Image Classifier to address a unique challenge: distinguishing between leopards, jaguars, and cheetahs. Even humans often struggle to differentiate these yellow-spotted creatures due to their similar appearances. This project leverages deep learning to automate and refine this classification, supporting conservationists, researchers, and animal lovers in accurately identifying these majestic big cats.

**Dataset:**
[https://www.kaggle.com/datasets/sonilnegi/spotted-cats-images/data](https://www.kaggle.com/datasets/sonilnegi/spotted-cats-images/data)

**Features**
1. Complete Workflow: Includes data preprocessing, model training, fine-tuning, evaluation, and prediction.
2. Technical Implementation: Uses transfer learning with a MobileNetV2 backbone plus a CBAM-style attention module to focus on discriminative spot and facial patterns, and strong data augmentation to improve generalization.
3. Explainability: Grad-CAM visualizations show where the model “looks” when predicting each species.

**Methods Used**

• Convolutional Neural Networks  
• Transfer learning (MobileNetV2)  
• Attention mechanisms (CBAM-style channel + spatial attention)  
• Data Augmentation  
• Grad-CAM for model interpretability  

**Technologies**

• Python  
• Pandas, matplotlib, tensorflow, pathlib  
• mobilenet_v2, OpenCV (for Grad-CAM visualization)

Contact: [sonilnegi12@gmail.com](mailto:sonilnegi12@gmail.com)
