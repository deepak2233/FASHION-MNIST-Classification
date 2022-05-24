# FASHION-MNIST-Classification

## Task 1
Download the Fashion-MNIST dataset (https://github.com/zalandoresearch/fashion-mnist). It contains 28x28 single-channel images of clothes grouped into ten classes. There are 60000 examples in the training dataset and 10000 examples in the test dataset. Each training and test example has one of the following labels assigned:


We will focus on detecting shoes. Labels 5, 7 and 9 (Sandal, Sneaker and Ankle boot) should be treated as positive and all others (such as Trouser, Dress and so on) should be negative.

Please prepare a CNN model for binary classification in PyTorch. You should propose a custom architecture instead of using pretrained models. Train it on samples from Fashion-MNIST’s train dataset and evaluate the quality of the proposed model on samples from Fashion-MNIST’s test dataset.

## Task 2
After finishing the first task you should have a pre-trained CNN model. Your second task will be to classify shoes into two groups - Heels and Flats. Download the attached Shoes dataset. There are two samples in the training split: one sample of Heels and one sample of Flats. Your solution can only use these examples and the model from the previous task. Evaluate the quality of your model on a provided test dataset.
