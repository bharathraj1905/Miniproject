# Stroke Detection from Brain MRI Using Swin Transformer
This project focuses on the automatic detection of stroke from brain MRI images using a Swin Transformer–based deep learning model. The system aims to assist medical professionals by providing a fast, accurate, and non-invasive approach for early stroke identification, thereby supporting timely diagnosis and improved patient outcomes.

## About
Stroke Detection from Brain MRI Using Swin Transformer is a deep learning–based medical imaging project designed to classify brain MRI scans into stroke and normal categories. Traditional stroke diagnosis relies heavily on manual analysis by radiologists, which can be time-consuming and subject to human error.

This project addresses these challenges by leveraging the Swin Transformer architecture, which uses hierarchical vision transformers and attention mechanisms to capture complex spatial features from MRI images. The model is trained and validated on preprocessed MRI datasets to ensure robust performance. The proposed system provides an automated decision-support tool that can aid clinicians in early stroke screening and diagnosis.

## Features

- Utilizes Swin Transformer, an advanced deep learning architecture for image classification
- High accuracy in stroke and normal brain MRI classification
- Non-invasive and automated diagnostic support system
- Scalable framework suitable for real-world medical deployment
- Efficient training and inference with reduced computational complexity
- Supports visualization through confusion matrices and performance metrics

## Requirements

*Operating System: 64-bit Windows 10 / Ubuntu Linux
*Programming Language: Python 3.8 or later
*Deep Learning Frameworks: PyTorch, timm
*Image Processing Libraries: OpenCV, torchvision
*Machine Learning Utilities: scikit-learn, NumPy, Pandas
*Visualization Tools: Matplotlib, Seaborn
*IDE: VS Code / Jupyter Notebook / Google Colab
*Hardware: GPU recommended for faster training (optional but preferred)
 
## System Architecture
The system architecture consists of MRI image input, preprocessing, thermal image transformation, feature extraction using Swin Transformer blocks, average pooling, and final classification through dense layers.

<img width="770" height="706" alt="image" src="https://github.com/user-attachments/assets/2a688a08-0bdb-4981-a6c9-d5f63330548f" />

## Output

#### Output 1 – Model Validation

<img width="1000" height="565" alt="image" src="https://github.com/user-attachments/assets/9f9e1ca6-c79a-4198-bc67-7e06537c0afd" />

#### Output 2 – Confusion Matrix

<img width="698" height="612" alt="image" src="https://github.com/user-attachments/assets/a7e57b47-853c-4826-b30d-d81a320f629f" />
<img width="716" height="607" alt="image" src="https://github.com/user-attachments/assets/7f47b3e0-55b8-41b5-927d-17597228f83e" />

Detection Accuracy: 97%
Note: Performance metrics may vary depending on dataset size and preprocessing techniques.

## Results and Impact

The proposed Stroke Detection System demonstrates high accuracy and reliability in classifying brain MRI images. By integrating transformer-based deep learning with medical imaging, the project highlights the potential of AI-assisted diagnosis in healthcare.
This system can serve as a supportive tool for radiologists, helping reduce diagnostic time and improving early stroke detection. The project also lays a foundation for future advancements in intelligent medical imaging systems.

## Articles published / References

1. Liu, Z., Lin, Y., Cao, Y., et al., “Swin Transformer: Hierarchical Vision Transformer using Shifted Windows,” IEEE International Conference on Computer Vision (ICCV), 2021.
2. Litjens, G., et al., “A Survey on Deep Learning in Medical Image Analysis,” Medical Image Analysis, Elsevier, 2017.
3.Esteva, A., et al., “A Guide to Deep Learning in Healthcare,” Nature Medicine, 2019.


