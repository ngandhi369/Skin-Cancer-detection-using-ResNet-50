# Skin Cancer Detection using CNN

This project focuses on the development of a skin cancer detector using Convolutional Neural Networks (CNN). By leveraging the power of TensorFlow and Keras, a skin cancer detection model was built using the ResNet-50 architecture. The model achieved a high accuracy of 92.4% in accurately identifying malignant cancer cells in images.

## Description

Skin cancer is a prevalent and potentially life-threatening disease. Early detection plays a crucial role in improving patient outcomes. This project addresses the need for an automated skin cancer detection system using deep learning techniques.

The key features of this project are as follows:

- Utilization of the ResNet-50 model: The ResNet-50 architecture, a well-known and highly effective CNN model, was employed to detect skin cancer cells in images.
- TensorFlow and Keras: The implementation of the skin cancer detector was carried out using the TensorFlow and Keras libraries, providing a robust and efficient framework for deep learning.
- High Accuracy: The developed model achieved an impressive accuracy of 92.4% in accurately identifying malignant cancer cells in images, demonstrating its effectiveness in assisting dermatologists and healthcare professionals in diagnosing skin cancer.

![skin cancer](https://github.com/ngandhi369/Skin-Cancer-detection-using-ResNet-50/assets/49865067/0df335cd-bc2f-44a3-8a40-b42fdaf70aa7)

## Dataset

The skin cancer detector was trained on a large dataset of skin lesion images. The dataset consisted of various classes, including benign and malignant skin lesions. It encompassed a diverse range of skin cancer types, ensuring the model's ability to generalize to different skin cancer cases.

## Workflow

The project's workflow involved the following steps:

1. Data Preprocessing:
   - Loading and preprocessing the skin lesion images.
   - Splitting the dataset into training and testing sets.
   - Applying data augmentation techniques, such as rotation, scaling, and flipping, to enhance the model's ability to generalize.

2. Model Training:
   - Constructing the ResNet-50 model using TensorFlow and Keras.
   - Compiling the model with appropriate loss functions and optimization algorithms.
   - Training the model on the preprocessed dataset, leveraging the power of GPUs if available.

3. Model Evaluation:
   - Evaluating the trained model on the testing set to assess its performance.
   - Calculating relevant metrics such as accuracy, precision, recall, and F1 score.
   - Fine-tuning the model based on the evaluation results, if necessary.

4. Skin Cancer Detection:
   - Utilizing the trained model to predict skin cancer cells in new, unseen images.
   - Generating predictions with associated probabilities indicating the likelihood of malignancy.

## Results

The skin cancer detection model achieved a high accuracy of 92.4% in accurately identifying malignant cancer cells in images. This level of accuracy demonstrates the potential of deep learning models in assisting dermatologists and healthcare professionals in diagnosing skin cancer.

The trained model can be deployed as an application or integrated into existing healthcare systems to provide a reliable and efficient tool for skin cancer detection. Early and accurate detection of skin cancer can significantly improve patient outcomes by enabling timely treatment and intervention.

## Conclusion

This project successfully developed a skin cancer detector using the ResNet-50 model implemented with TensorFlow and Keras. The achieved accuracy of 92.4% in accurately identifying malignant cancer cells in images showcases the effectiveness of deep learning techniques in the field of dermatology. The developed model has the potential to assist healthcare professionals in early detection and diagnosis, leading to improved patient care and outcomes in the fight against skin cancer.
