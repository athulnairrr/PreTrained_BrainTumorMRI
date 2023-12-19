# PreTrained_BrainTumorMRI.ipynb

Dataset Description:

Brain Tumor MRI dataset with four classes: glioma, meningioma, notumor, and pituitary.
Number of files per class: glioma (300), meningioma (306), notumor (405), pituitary (300).
Images are in JPEG format, grayscale, and consistent size of 512x512 pixels.
Objective:

Build a project using Convolutional Neural Network (CNN) and Random Forest for brain tumor classification.
Preprocessing Steps:
Dataset Characteristics:

Image Format: JPEG
Image Color: Grayscale
Image Size: Consistent at 512x512 pixels
Labels: Represented by folder names
Checking Image Sizes:

Images are consistent at 512x512 pixels.
Data Generator Configuration:

Utilizing Keras ImageDataGenerator for data augmentation and loading.
Class Mode: Categorical (multi-class classification)
CNN Model Development:
VGG Model Integration:

Integrated VGG-16 model for brain tumor classification.
Alternative Pre-trained Models (Optional):

Provided code snippets for using AlexNet and ResNet-50, allowing user choice. Currently, VGG-16 is implemented.
Model Training:

Training the CNN model using the specified data generators.
Model architecture includes convolutional layers, max pooling, fully connected layers, and dropout.
Model Evaluation:
Model Accuracy:

Evaluated CNN model accuracy.
Utilized Weights and Biases (WandB) for tracking and visualizing model performance.
Random Forest Integration:

Implemented Random Forest for feature extraction and classification.
Evaluated Random Forest model accuracy.
TensorBoard and WandB Integration:
TensorBoard Usage:

Running TensorBoard using the tensorboard command with specified log directory.
Some issues reported but TensorBoard seems to be working.
Weights and Biases (WandB):

Successfully integrated WandB for model tracking and visualization.
Challenges and Next Steps:
Remaining Challenges:

TensorBoard has reported issues, but functionality is observed. Further investigation may be needed.
Additional exploration of TensorBoard accessibility issue.
Future Improvements:

Consideration for using other pre-trained models (e.g., AlexNet, ResNet).
Ongoing monitoring and improvement of TensorBoard integration.
