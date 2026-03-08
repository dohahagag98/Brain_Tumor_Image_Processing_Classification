# Brain_Tumor_Image_Processing_Classification
📝 Project Overview
An End-to-End Deep Learning pipeline for classifying Brain Tumors from MRI scans. This project converts raw medical imaging data (.mat) into optimized datasets, applies advanced data augmentation, and uses a Transfer Learning approach (ResNet18) to achieve high-accuracy classification across four categories: Glioma, Meningioma, Pituitary, and No Tumor.

🚀 Key Features
Data Engineering: Scripts to handle the conversion of .mat files to .jpg for standardized processing.
Advanced Augmentation: Implemented RandomHorizontalFlip and RandomRotation to prevent overfitting and improve model robustness.
Transfer Learning: Utilized a pre-trained ResNet18 architecture, fine-tuned for medical image features.
Optimized Training: Used the Adam Optimizer and Cross-Entropy Loss with a dynamic validation check to save the best-performing model weights.

📂 Dataset Structure
The model is trained on the Brain Tumor MRI Dataset. The data is organized into:
Training/: Images used to teach the model.
Testing/: Unseen images used to evaluate final performance.
Classes: Glioma, Meningioma, No Tumor, Pituitary.

