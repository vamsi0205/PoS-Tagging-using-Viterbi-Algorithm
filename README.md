# PoS-Tagging-using-Viterbi-Algorithm

This project demonstrates the implementation of Part-of-Speech (POS) tagging using a Hidden Markov Model (HMM) and the Viterbi algorithm. The dataset used for this project is the Penn Treebank, which consists of 3914 sentences along with their corresponding POS tags. A bigram model is employed to create the HMM, and the Viterbi algorithm is used to decode the most likely sequence of tags for a given sentence.

# Dataset
The Penn Treebank dataset, included in the NLTK library, is used for training and testing the HMM. This dataset provides a set of sentences with words and their corresponding POS tags.

# Script Details
## Training:

The script uses the Penn Treebank dataset to train a bigram HMM. The HMM parameters (initial probabilities, transition probabilities, and emission probabilities) are computed from the training data.

## Tagging:

The Viterbi algorithm is implemented to predict the POS tags for sentences in the test data.

## Evaluation:

The accuracy of the model is evaluated by comparing the predicted tags with the actual tags in the test data.

  
