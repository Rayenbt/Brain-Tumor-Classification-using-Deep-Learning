# Brain Tumor Classification Using Deep Learning

## Project Overview  
This project was completed as my **Capstone Project** for the **BSc in Computing in IT (4th year)** degree at **CCT College Dublin**. It focuses on developing a deep learning system to classify brain tumors from MRI images, leveraging the power of artificial intelligence to support medical imaging and diagnostic decision-making.

Following a structured CRISP-DM methodology, two convolutional neural networks (CNNs) were designed and evaluated: a **custom-built CNN** and a **transfer learning-based ResNet50**. Both models were trained on a dataset of 7,023 MRI images across four diagnostic categories.

## Key Findings  
- The **custom CNN** reached a high test accuracy of **99.0%**, but interpretability analysis using Grad-CAM revealed it sometimes focused on irrelevant image features, indicating shortcut learning.  
- The **ResNet50** model achieved **98.4% accuracy** while consistently focusing on meaningful tumor regions, demonstrating better generalization and reliability.

## Final Model and Deployment  
Due to its interpretability and robustness, **ResNet50** was chosen as the final model. It was deployed using **Gradio**, creating an interactive web-based interface that allows users to upload MRI scans and receive real-time tumor classification results paired with visual explanations via Grad-CAM heatmaps.

This project highlights the importance of combining model performance with explainability—especially in clinical settings where transparency is critical for trust and adoption.

## Project Highlights  
- Application of deep learning for multi-class brain tumor classification  
- Comparison between a custom CNN and ResNet50 transfer learning model  
- Use of advanced model interpretability techniques (Grad-CAM) to validate predictions  
- Interactive deployment enabling accessible and explainable AI-powered diagnosis support  

## Academic Context  
This work was submitted in partial fulfillment of the requirements for the **Bachelor of Science in Computing in IT (4th year)** at **CCT College Dublin**.
