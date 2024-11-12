# Multiclass-classification-using-animal-dataset
1. Dataset Collection
  Use a dataset with images of animals, each labeled with a class. You can use public datasets like:
  Kaggle: Search for "animal classification" datasets.
  ImageNet: Filter by animals.
  Custom Data: If creating a small dataset, structure it with folders named after each animal class, e.g., /data/dogs, /data/cats, /data/birds.
2. Data Preprocessing
  Load the images and resize them to a fixed size (e.g., 128x128 pixels) for consistent input dimensions.
  Normalize the pixel values (scale from 0 to 1).
  Split the dataset into training, validation, and test sets.
3. Setting Up Libraries
  Install necessary libraries:
  pip install tensorflow numpy matplotlib
4. Building the Model
  For this example, we’ll use TensorFlow and Keras to create a Convolutional Neural Network (CNN) model.
  Alternatively, we can use a pre-trained model like MobileNet or ResNet for better accuracy if data is limited.
