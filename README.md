# Natural-Language-Processing-in-TensorFlow
4 different examples of applying Natural Language Processing in TensorFlow

1. This exercise explores the BBC news archive and tokenize the dataset, removing common stopwords. A great source of these stop words can be found from https://github.com/Yoast/YoastSEO.js/blob/develop/src/config/stopwords.js

2. This is a continuation of the previous exercise. This dataset contains articles that are classified into a number of different categories. See if you can design a neural network that can be trained on this dataset to accurately determine what words determine what category. Create the vecs.tsv and meta.tsv files and load them into the embedding projector.

3. For this exercise, we are training on a large dataset, as well as using transfer learning of an existing set of embeddings. The dataset is from:  https://www.kaggle.com/kazanova/sentiment140. I’ve cleaned it up a little, in particular to make the file encoding work with Python CSV reader.
The embeddings that you will transfer learn from are called the GloVe, also known as Global Vectors for Word Representation, available at: https://nlp.stanford.edu/projects/glove/ . This exercise was to explore overfitting in NLP.

4. This exercise take a corpus of Shakespeare sonnets, and uses them to train a model using LSTMs. Then, see if that model can create poetry!

