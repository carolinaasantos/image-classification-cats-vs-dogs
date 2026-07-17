# Image Classification With CNN: Cats vs Dogs 🐱🐶

## About the Project

This project explores the development of an image classification model capable of distinguishing between cats and dogs using a **Convolutional Neural Network (CNN)**. The model was developed based on a [tutorial](https://www.kaggle.com/code/sachinpatil1280/cats-vs-dogs-image-classification-using-cnn-95/notebook) and a public [dataset](https://www.kaggle.com/competitions/dogs-vs-cats/data), with the objective of understanding the main steps involved in building a Deep Learning image classification system.

Image classification is one of the most common applications of Deep Learning and Computer Vision. The idea behind this project is to understand how a neural network can learn visual patterns from images and use these patterns to make predictions on new examples.

The Cats vs Dogs problem is a classic starting point for learning CNNs because, although the task seems simple for humans, it requires the model to identify important visual features such as shapes, textures, and patterns that differentiate the two classes.

Throughout this project, the complete workflow of a Deep Learning image classification problem was explored: from preparing the dataset and analyzing images to training, evaluating, and testing the final model.

## Objective

The main objective of this project was to build and evaluate a CNN model capable of classifying images as either **cat** or **dog**.

The project aimed to understand the main steps involved in creating a Deep Learning model, including:

- Preparing and organizing image datasets;
- Understanding how images are processed before being used by a neural network;
- Building a CNN architecture using Keras;
- Training the model and monitoring its learning process;
- Evaluating the model using different metrics;
- Making predictions on unseen images.

## What I Learned

During this project, I learned much more than just how to train a model. I was able to understand the complete process behind a Deep Learning application.

One of the main concepts learned was how **Convolutional Neural Networks (CNNs)** work. Instead of manually defining image features, CNNs are able to automatically learn important characteristics from images through convolutional layers. These layers gradually learn from simple patterns, such as edges and textures, to more complex features that help classify objects.

I also learned the importance of preparing the dataset before training. This included:

- Loading and organizing images;
- Exploring the dataset to understand its characteristics;
- Splitting the data into training, validation, and testing sets;
- Applying data augmentation to create image variations and improve generalization.

Another important learning point was understanding how the training process works. Concepts such as:

- **Epochs:** complete passes through the entire training dataset;
- **Batches:** smaller groups of images processed before updating the model;
- **Loss function:** measures how far the predictions are from the correct labels;
- **Accuracy:** measures the percentage of correct predictions.

I also explored how callbacks improve training. Techniques such as **Early Stopping** and **Reduce Learning Rate on Plateau** help prevent overfitting and allow the model to continue improving when necessary.

For model evaluation, I learned that accuracy alone is not enough to understand a model's performance. Using tools such as:

- Classification Report;
- Confusion Matrix;
- Loss and Accuracy curves;

helps analyze where the model is performing well and where it still makes mistakes.

Finally, I learned how predictions are generated. The model does not directly output "cat" or "dog"; instead, it produces probabilities for each class, and the class with the highest probability is selected as the final prediction.

## When the Model Gets Confused...

The CNN model was trained using the prepared dataset, with validation data being monitored throughout the training process and achieved a high accuracy in classifying cats and dogs, demonstrating that it was able to learn meaningful visual features from the dataset. But...

One important lesson from this project is that **a model does not need to be perfect to be useful**. Even with high accuracy, a CNN can sometimes make mistakes.

<img width="565" height="240" alt="image" src="https://github.com/user-attachments/assets/df909304-4b91-48cf-bf0e-752dabcc13cf" />

For example, in one prediction, the model classified a dog image as a cat, and the same happened with the cat classified as a dog. At first, it may seem like a failure, but this is actually an important part of understanding Machine Learning.

Since it only learns patterns from the examples it receives, if an image contains unusual features, different lighting, strange angles, or characteristics that are similar between classes, the model can make a wrong prediction. A 100% accuracy model is usually unrealistic, especially for real-world problems. The goal of Machine Learning is not always to eliminate every mistake, but to build models that learn useful patterns, generalize well, and continuously improve.

So yes, sometimes the model sees a dog and says "cat". And that's okay!
Because mistakes are part of the learning process (both for the model and for me while learning).

## Final Thoughts

Through this experience, I became more interested in image classification and neural networks and building this CNN helped me understand not only how to train a model, but also how to analyze its behavior, identify limitations, and think about possible improvements. This foundation will be useful for exploring more advanced Computer Vision applications and more complex Deep Learning architectures in the future and I am excited to keep learning different parts of Machine and Deep Learning! 😁
