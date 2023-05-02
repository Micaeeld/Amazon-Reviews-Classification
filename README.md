# Amazon Shopping Reviews Classification

This notebook presents an example of sorting Amazon shopping reviews using the TensorFlow library.
This dataset contains 3,594,782 training samples and 399,916 testing samples in each polarity sentiment, but in this example, only a subset with 100,000 reviews will be used.

## Libraries Used
The libraries used in this notebook are:

- tensorflow
- nltk
- re
- string
- collections
- matplotlib
- pandas

## Notebook Steps
- Data pre-processing, including tokenization and stopwords removal.
- Division of dataset into training set and test set.
- Creation of the classification model using the TensorFlow library.
- Model training and results evaluation.
- Model testing with new review samples.

## Results
The model created in this notebook obtained an accuracy of 88% in the validation set.

## Execution from Notebook
To run this notebook, it is necessary to install the libraries used. This can be done using the pip package manager. Also, you must have the dataset file "amazon_reviews.csv" in the same folder as this notebook.
After installing the libraries and dataset file, just run the notebook cells in order.

## References
Kaggle dataset: https://www.kaggle.com/datasets/kritanjalijain/amazon-reviews?select=train.csv

## Contribution
Contributions are welcome! If you find any bugs or have any suggestions for improvement, please open an issue in the repository or submit a pull request. the pull request.
