# Keras_Tutorial
A basic overview of Keras for my reference

### Keras Tutorial Part - 1
- Preprocessing Data
- Creating an Artificial Neural Network
- Creating a Validation Set
- Making Predictions
- Creating Confusion Matrix (Introduction to fast.ai's plots() function)
- Saving and Loading Keras Model
    - Saving and Loading Model               (in models folder)
    - Saving and Loading Architecture only
    - Saving and Loading Weights only        (in models folder)
    
### Keras Tutorial Part - 2
- Organising Image Data
- Processing the data (intro to ImageDataGenerator() )
- Creating andTraining CNN image Classifier
- Predicting

### Keras Tutorial Part - 3
- As we saw the CNN model we made in part 2 was not so good
- We use VGG-16 model for our prediction
- VGG-16 won 2015 imagenet competition
- We import the VGG16 model
- We create our model and copy all the layers and parameters of Vgg16 leaving out the last layer
- We create the last layer according to our problem
- We train only the parameters of last layer
- We  get awesome results

### Keras Tutorial Part - 4
- Data Augmentation with Keras
- The Result is in Images folder

### cats-and-dogs directory:
- Subset of Kaggle cats-and-dogs 
- 3 directories containing train, test and validation set images

### images
- A meme image called architect.jpg
- augmented_architect contains 10 augmented images of architect.jpg


**credits to [deeplizard](https://deeplizard.com/)**

**Tensorflow Version - 1.15**
