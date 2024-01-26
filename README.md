# Natural Language Processing(NLP)
## The provided code demonstrates how to use word embedding techniques with the embedding layer in Keras. Here are the steps outlined in the code:

1.Import necessary libraries, including TensorFlow and Keras.
2.Define sentences as a list of strings.
3.Specify the vocabulary size (voc_size) and use the one_hot function from Keras to perform one-hot encoding on the sentences.
4.Import additional necessary modules from Keras for word embedding.
5.Define the maximum length of sentences (sent_length) and pad the sequences using pad_sequences.
6.Define the dimension of the embedding space (dim) and create a Sequential model in Keras.
7.Add an Embedding layer to the model with the specified vocabulary size, dimension, and input length.
8.Compile the model using an optimizer and a loss function.
9.Print the summary of the model.
10.Test the model by predicting the output for one of the embedded documents.
11.This code snippet demonstrates the process of converting words into dense vectors using word embedding techniques, allowing neural networks to process textual data effectively.
