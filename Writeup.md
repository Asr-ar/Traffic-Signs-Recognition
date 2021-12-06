# Traffic Signs Recognition

## Abstract
Given a various traffic signs along with images dataset,
we are challenged to classify traffic signs present in the image into different categories.

## Data
- For this project, we are using the public dataset available at Kaggle: [Traffic Signs Dataset](https://www.kaggle.com/shanmukh05/traffic-sign-cropped)

- The dataset contains around 50,000 images of different traffic signs. 
It is further classified into 43 different classes.
- The dataset is quite varying, some of the classes have many images while some classes have few images. 
- The size of the dataset is 44 MB.
- The dataset has a train folder which contains images inside each class and a test folder which we will use for testing our model.




## Design and Algorithms

 **Extraction, Formatting & Type Conversion**

   - All of the data was loaded from sorted folders as images (Pixels) and needs extraction, formatting, and type conversion.


 **Normalization**

  - Scaling of training data (Divide by 255).
  - Labels Encoding, for all the 43 categories. 

 **Spliting The Data to (Train, Valdation and Test) datasets**

  - Splitting the Data with shuffling , to make sure our model with capture all the patterns.

 **Reshape**
  - Reshape the image size to be in 2d array, to applying baseline model(Logistic Regression)

 **Hyperprameter Setting over Deep learning model**

  - Set the Dropout to handle any Overfitting.
  - Set the Classes Weight to handling the class Imbalance struggle 
  - Set Activation Function to be "Relu" for the hidden layer and "Softmax" for the output layer.

.


## Tools
- Software Platform:
    - Jupyter Notebook
- Programming Language:
    - Python
- Python Libraries:
    - Modeling libraries:
        - Sci-Kit Learn
        - Tensorflow (keras)
    - Data manipulation libraries:
        - Pandas
        - Numpy
    - Visualization libraries
        - Matplotlib
        - Seaborn
    - Storage libraries
        - Pickle
        - SQLAlchemy
        
## Communication
Slides containing visualizations
