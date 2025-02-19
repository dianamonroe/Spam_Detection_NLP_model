

# Spam link detection system

We want to implement a system that is able to automatically detect whether a web page contains spam or not based on its URL.

#### Step 1: Loading the dataset

The dataset can be found in this project folder under the name `url_spam.csv`. You can load it into the code directly from the link:

```text
https://raw.githubusercontent.com/4GeeksAcademy/NLP-project-tutorial/main/url_spam.csv
```

Or download it and add it by hand in your repository.

#### Step 2: Preprocess the links

Use what we have seen in this module to transform the data to make it compatible with the model we want to train. Segment the URLs into parts according to their punctuation marks, remove stopwords, lemmatize, and so on.

Make sure to conveniently split the dataset into `train` and `test` as we have seen in previous lessons.

#### Step 3: Build an SVM

Start solving the problem by implementing an SVM with the default parameters. Train it and analyze its results.

#### Step 4: Optimize the previous model

After training the SVM, optimize its hyperparameters using a grid search or a random search.

#### Step 5: Save the model

Store the model in the corresponding folder.

> Note: We also incorporated the solution samples on `./solution.ipynb` that we strongly suggest you only use if you are stuck for more than 30 min or if you have already finished and want to compare it with your approach.
