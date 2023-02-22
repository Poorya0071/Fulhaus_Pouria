# Project Description
This project is about image classification of 3 classes - Bed, Chair, Sofa. For this purpose, I used two deep learning models. One is a Conv2D model, and another one is a pre-trained MobileNetV3 from TensorFlow Hub. To preprocess the images, I used ImageDataGenerator in TensorFlow. I divided the dataset into train and test directories for training and evaluation purposes.
### API, Docker, and CI/CD
I have limited knowledge of API, Docker, and CI/CD, but I have attempted to conduct some research and provide basic code snippets based on my best efforts. The FastAPI framework is used for building the API, and the Docker containerization technique is used to package the application and its dependencies. For implementing the CI/CD pipeline, I have utilized the Github Actions.
### Data Visualization
[!myimage](output.png)
### Results
The results of the project show that both the Conv2D model and MobileNetV3 perform well, achieving accuracies of around 92% and 98%, respectively. It is possible to improve the accuracy on the validation data by increasing the number of epochs, tuning hyperparameters, and adding more data to the dataset. However, it should be noted that the current dataset is relatively small, with only 100 images in each class for a total of train and test images. Therefore, the models' performance could potentially improve even further with a larger and more diverse dataset.
