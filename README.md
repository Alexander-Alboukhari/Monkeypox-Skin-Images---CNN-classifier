# Monkeypox Skin Images CNN classifier
Monkeypox (Mpox) appear similar too ther skin diseases while presenting diagnostic challenges. This
study develops and evaluates deep learning models for the early detection for monkeypox classification
using digital skin lesion images and uses the publicly available Monkeypox Skin Image Dataset to
develop and evaluate multiple convolutional neural network (CNN) architectures, including ResNet50,
DenseNet169,EfficientNetB7,InceptionV3,VGG16,MobileNetV2,Xception and ensemble methods, for
identifying skin illnesses as monkeypox, chickenpox, measles, and normal skin.
A comprehensive machine learning pipeline has been developed with including transfer learning,
data augmentation, stratified k-fold cross-validation, and class weighting . The top performing individual
model ResNet50, attained an accuracy of 96.9% and an F1-score of 96.0%, but an ensemble
method enhanced performance to 98.0% accuracy. Grad-CAM visualizations were employed to improve
model explainability, allowing for the validation that classifications have a basis in clinically
pertinent image features. Additional the final model was implemented via a Gradio interface, providing
an accessible interface for clinical use.This study highlights the viability of CNN based approaches
for early detection of monkeypox, providing an opportunity for more accessible and efficient diagnosis
in environments with limited resources.
