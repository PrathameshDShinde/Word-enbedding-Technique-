# Natural Language Processing(NLP)
## The provided code demonstrates how to use word embedding techniques with the embedding layer in Keras. Here are the steps outlined in the code:

- Import necessary libraries, including TensorFlow and Keras.
- Define sentences as a list of strings.
- Specify the vocabulary size (voc_size) and use the one_hot function from Keras to perform one-hot encoding on the sentences.
- Import additional necessary modules from Keras for word embedding.
- Define the maximum length of sentences (sent_length) and pad the sequences using pad_sequences.
- Define the dimension of the embedding space (dim) and create a Sequential model in Keras.
- Add an Embedding layer to the model with the specified vocabulary size, dimension, and input length.
- Compile the model using an optimizer and a loss function.
- Print the summary of the model.
- Test the model by predicting the output for one of the embedded documents.
- This code snippet demonstrates the process of converting words into dense vectors using word embedding techniques, allowing neural networks to process textual data effectively.
