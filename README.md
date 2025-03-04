Overview:
- This project focuses on detecting and classifying brain tumors (Glioma, Meningioma, Pituitary) using Machine Learning (ML) and Deep Learning (DL) models. We implemented EfficientNetV2L, VGG16 with SVM for feature extraction, and a hybrid model combining DenseNet, EfficientNetV2L, and VGG19.

Dataset:
- Source: MRI images dataset
- Size: 2400 images (Train: 1669, Validation: 502, Test: 243)

Methodology:
1) Preprocessing: Image resizing, data augmentation, normalization, and blur detection
2) Model Training:
- EfficientNetV2L
- VGG16 + SVM (Feature Extraction)
- Hybrid Model (DenseNet, EfficientNetV2L, VGG19)
3) Evaluation Metrics: Accuracy, F1-score, Confusion Matrix, ROC

Results:
- Hybrid Model: 95% Accuracy ✅
- EfficientNetV2L: 94% Accuracy
- VGG16 + SVM: 93% Accuracy
