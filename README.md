

# Spam link detection system

System that is able to automatically detect whether a web page contains spam or not based on its URL.

#### Step 1: Loaded the dataset

The dataset can be found in this project folder under the name `url_spam.csv`. You can load it into the code directly from the link:

```text
https://raw.githubusercontent.com/4GeeksAcademy/NLP-project-tutorial/main/url_spam.csv
```

Or download it and add it by hand in your repository.

#### Step 2: Preprocessed the links

Transformed the data to make it compatible with the model we want to train. 
Segmented the URLs into parts according to their punctuation marks, remove stopwords, lemmatize, and so on.

Make sure to conveniently split the dataset into `train` and `test`.

#### Step 3: Built an SVM

Start solving the problem by implementing an SVM with the default parameters. Trained it and analyzed its results.

#### Step 4: Optimized the previous model

After training the SVM, I optimized its hyperparameters using a grid search or a random search.

#### Step 5: Saved the model

Store the model in the corresponding folder.

