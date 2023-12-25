# Metaphor Detection Using BERT Embedding and Bi-directional LSTM
This is a Machine Learning class project which focuses on the task of metaphor identification by associating metaphor IDs with words in natural language text. With the aid of advanced natural language processing techniques and machine learning algorithms, specifically BI Directional LSTM with BERT embeddings, we construct a robust framework for discerning whether a given word is used metaphorically or literally based on its corresponding metaphor ID.
# Task Description
In this project, our main focus revolves around the intricate task of Metaphor Identification in natural language text. We aim to create a robust system that can discern whether a given word, associated with a unique Metaphor ID, is used metaphorically or literally. The dataset at our disposal has 1870 comments recorded which include specific words like "road," "light," "ride," "boat," and "train," each linked to a corresponding Metaphor ID along with binary labels indicating their metaphorical (TRUE) or literal (FALSE) usage.
# Methodology
In this notebook, we experiment with statistical models and deep learning models to help classify text into Metaphors and Non-Metaphors.
1) We use statistical models such as Logistic regression and XG boost for the task
2) We experiment with Bi-Directional LSTM as they are known to capture contextual understaanding effectively
3) We then experiment with BERT embeddings and combine it with Bi-Directional LSTM's
4) We observe that the effect of class imbalance and then later balance the data set with some examples
5) We repeaat 2 and 3 and observe the result
# Conclusion
Downstream tasks of BERT including embeddings can be very useful in tasks such as text classification. Here, we could observe significant improvement in accuracy, precision and recall.

