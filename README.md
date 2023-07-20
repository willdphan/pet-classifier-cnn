# Pet Classifier CNN

## Description
This code implements a deep learning model based on the ResNet-50 architecture for image classification. The model is trained and tested on a dataset containing images of cats and dogs. Dataset from Kaggle. The training process involves iterating over mini-batches of images, calculating losses, and updating the model parameters using the Adam optimizer. After training, the model is evaluated on a separate test dataset to measure its accuracy.

During the testing phase, the code loads the test dataset and iterates over the images. Each image is passed through the trained model, which predicts whether the image contains a cat or a dog. The predicted class (cat or dog) is then printed for each image.

[Code](Pet_Classifier_CNN.ipynb)

## License

This script is open-source and licensed under the MIT License. For more details, check the [LICENSE](LICENSE) file.
