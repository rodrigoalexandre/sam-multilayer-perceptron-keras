Project developed to improve the project available in the sam-multilayer-perceptron-sklearn repository.

This project presents a Multilayer Perceptron model developed in Tensorflow/Keras for processing the SAM dataset.

The Multilayer Perceptron reached an accuracy rate of 94.14% in predictions. This accuracy rate is lower than the accuracy reached in the original project (98.60%), but this implementation has the following advantages:

- Only 6 features were selected for trainning, which reduced the dataset size to be processed.
- The use of the Tensorflow framework allowed the training to be performed on GPU, reducing processing time.

The libraries used in the project were: Tensorflow, Keras, scikit-learn, Pandas, Imbalanced-learn, scipy, Matplotlib and Seaborn. 
