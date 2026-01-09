# Custom-Image-Classifier-for-CIFAR-10

## Project Overview
This project focuses on developing a custom image classification model using the CIFAR-10 dataset to explore the fundamentals of deep learning with PyTorch. The objective was to build a neural network capable of achieving approximately 70% accuracy on the CIFAR-10 dataset, which serves as a standard benchmark for image classification tasks.
Before committing to a commercial solution, management sought to evaluate the feasibility of building an in-house image classifier. The task was to design and train a custom neural network that can classify generic objects, with the potential for future enhancement through transfer learning on larger datasets.
The CIFAR-10 dataset has driven extensive progress in neural network research, with current state-of-the-art performance reaching ~99% accuracy using models such as GPipe (557 million parameters, developed in late 2018). While GPipe and similar architectures involve advanced methods beyond the scope of this project, any suitable architecture could be employed to achieve competitive performance.
The dataset includes ten object categories:
Key Steps
	1.	Explore and prepare the dataset for training and testing.
	2.	Design and implement a custom neural network.
	3.	Train the model on the training dataset.
	4.	Evaluate its performance on the test dataset.
	5.	Provide insights for the “build vs. buy” decision.

## Set up
The CIFAR-10 dataset is conveniently available through the  torchvision  module, allowing the project to be executed without additional downloads. The implementation requires CUDA support for GPU-accelerated training.

## Results
The custom convolutional neural network achieved a test accuracy of 71.6% using optimized hyperparameters, including the structure of convolutional layers and the number of hidden units.
While the model demonstrated solid performance, signs of overfitting were observed, as the validation loss exceeded the training loss. Further tuning of the architecture or application of transfer learning techniques could likely improve accuracy beyond the current result.
