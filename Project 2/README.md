# CS672 Deep Learning Project #2

Perform an explanatory data analysis (EDA) on Breast Cancer (Wisconsin) Diagnostic Classification obtained from 442 diabetes patients. Besides the need to build a model based on the data provided, you are asked to look for issues in the data and find correlation among the various variables in order to improve breast cancer classifications.

Write Python/R (or on any language contained within a notebook) scripts in order to complete the following tasks along with their output. All work should be done and submitted in a single Notebook (Jupyter or Colab). 

1) Prep the data in order to be ready to be fed to a model. Look for missing, null, NaN records. Find outliers. Transform data – all entries should be numeric.
2) List all types of data, numeric, categorical, etc. 
3) Perform EDA on data 
Utilize both:
- Classic approach in EDA (Pandas, Numpy libraries)
- The TFDV (TensorFlow Data Validation) module with the powerful graphical statistics generated (apache beam library...)

Present dependencies and correlations among the various features in the data. List the most variables (Feature Importance) that will affect the target label.

Build a Deep Learning model (based on PyTorch’s classification modeling approaches) that provides reliable and improved accuracy on classifying the correct class of a patient with cancer. Typical architecture of a classification neural network The word typical is on purpose. Because the architecture of a classification neural network can widely vary depending on the problem you're working on. However, there are some fundamentals all deep neural networks contain: 
➢ An input layer.
➢ Some hidden layers.
➢ An output layer.

Perform binary-class classification modeling analysis on the ready-to-be-fed data.

Perform the following tasks:
• Evaluating and improving our classification model
• Split the dataset to 80%/20% ratio (training vs test)
• Evaluate your model on the test dataset.
• Plot the graphs of loss vs accuracy curves
• Print the Confusion Matrix

Tune your model on the following parameters:
The activation parameter - "relu" & "sigmoid".

The learning_rate (also lr) parameter – Set a proper range of values for learning rate, usually from 0.1 down to 0.001 or less.

Important Note: You can think of the learning rate as how quickly a model learns. The higher the learning rate, the faster the model's capacity to learn, however, there's such a thing as a too high learning rate, where a model tries to learn too fast and doesn't learn anything. We'll see a trick to find the ideal learning rate soon.

The number of epochs - Remember a single epoch is the model trying to learn patterns in the data by looking at it once. Try several sizes: 500, 1000, 2000, etc...

Dataset / Content

The data could be obtained from within scikit-learn library: https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html#. The columns are as follows; their names are pretty self-explanatory.