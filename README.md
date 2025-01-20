# Pre-trained-Image-Classifier-To-Identify-Dog-Breeds


## Overview
This project aims to develop a robust image classifier using three pre-trained Convolutional Neural Networks (CNNs)—ResNet18, AlexNet, and VGG. The goal is to accurately identify whether an image contains a dog and, if so, classify the specific breed of the dog. This project forms part of the Udacity AI Programming with Python Nanodegree program, under the AWS AI/ML Scholarship, focusing on assessing and comparing the performance of the three CNN models on a provided dog image dataset.

## Technologies Used
- **Python**
- **Convolutional Neural Networks (CNNs)**: ResNet18, AlexNet, VGG
- **Pre-trained Models on ImageNet**

## Aim
The project aims to:
1. **Identify whether the image is of a dog or not** using a pre-trained CNN classifier.
2. **Classify the breed of the dog** if the image contains a dog.
3. **Evaluate the performance** of three pre-trained CNN models (ResNet18, AlexNet, and VGG) in terms of accuracy and runtime.

## Briefing on Architectures
- **AlexNet**: The AlexNet architecture is known for its simplicity and efficiency, consisting of eight layers with five convolutional layers followed by three fully connected layers. It was designed to run on GPUs and utilizes ReLU activations for nonlinear transformations.
- **ResNet18**: The ResNet18 architecture introduces residual learning with 18 layers, which helps in training very deep networks by solving the vanishing gradient problem through shortcut connections.
- **VGG**: The VGG architecture is characterized by its simplicity, using very small (3x3) convolution filters throughout the entire network. It's deeper with 16-19 weight layers and emphasizes depth over width.

## Results
| Model     | % Match | % Correct Dogs | % Correct Breed | % Correct Not-Dogs |
|-----------|---------|----------------|-----------------|-------------------|
| **ResNet18** | 80.00%  | 100.00%        | 90.00%          | 100.00%           |
| **AlexNet** | 75.00%  | 100.00%        | 80.00%          | 100.00%           |
| **VGG**    | 87.50%  | 100.00%        | 93.33%          | 100.00%           |


## How It Works
1. **Input Images**: Users submit images of their dogs.
2. **Create Pet Image Labels**: Labels are generated using the filenames of the submitted images.
3. **Classify Images**: Use the provided classifier function to generate labels and compare them with the pet image labels.
4. **Classify as "Dogs" or "Not Dogs"**: Utilize a list of known dog names (`dognames.txt`) to help with this classification.
5. **Evaluate Performance**: Assess the accuracy and runtime of the models.


## Conclusion
Based on the results, the **VGG** architecture performs the best among the three pre-trained models. It achieves the highest overall match percentage (87.50%) and the highest percentage of correctly identified dog breeds (93.33%).
By accurately identifying and classifying dog breeds, this project showcases the practical applications of CNNs and Python in image classification tasks.

---


