## Natural language Processing(MNIST dataset)
This [notebook](https://github.com/swalehmwadime/NLP-Beginners-guide/blob/main/Models/NLP_Notebook1.ipynb) is for training a simple neural network using the [tensorflow](https://www.tensorflow.org/) library to distinguish handwritten digits from the MNIST dataset.<br> Description of each component and the necessary details :</p><br>
<ol>
<li>TensorFlow: For building and training the neural network.</li>
<li>Math: For mathematics .</li>
<li>Seaborn and Matplotlib: For data visualization</li>
<li>NumPy: For numerical operations, especially array manipulations.</li>
<li>Pandas: For data manipulation and analysis </li>
<li>OS: For interacting with the operating system, like file handling.</li>
</ol>

### Explanation:
- **Data Loading and Preprocessing**:
  - The MNIST dataset is loaded, and the pixel values of the images are normalized to be between 0 and 1 by dividing by 255.0.

- **Model Building**:
  - **Flatten Layer**: Converts each 28x28 image into a 1D array of 784 elements.
  - **Dense Layer**: Fully connected layer with 128 neurons and ReLU activation.
  - **Dropout Layer**: Dropout with a rate of 0.2 for regularization to prevent overfitting.
  - **Output Layer**: Fully connected layer with 10 neurons (one for each digit) and softmax activation to output probabilities for each class.

- **Model Compilation**:
  - The model is compiled with the Adam optimizer, sparse categorical cross-entropy loss, and accuracy as a metric.

- **Model Training**:
  - The model is trained for 5 epochs on the training data.

- **Model Evaluation**:
  - The trained model is evaluated on the test data to determine its accuracy.

