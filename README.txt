Assignment 3: Word Vectorization
This README file contains code for two different methods of word vectorization: Singular Value Decomposition (SVD) and Skip-gram.

Singular Value Decomposition (SVD)
Files:
svd.py: Python script to train word embeddings using the SVD method and save the word vectors as "svd-word-vectors.pt".
svd-classification.py: Python script to train a Recurrent Neural Network (RNN) on a classification task using the SVD word vectors and save the model as "svd-classification-model.pt".
svd-classification-model.pt: Pre-trained RNN model for classification task using SVD word vectors.
svd-word-vectors.pt: Pre-trained word vectors obtained using the SVD method. (https://drive.google.com/file/d/1IqbX5pgVPBsoke5t_dnfoJUiPhQUcUDX/view?usp=sharing)
Download SVD files

Skip-gram
Files:
skip-gram.py: Python script to train word embeddings using the Skip-gram method with negative sampling and save the word vectors as "skip-gram-vectors.pt".
skip-gram-classification.py: Python script to train an RNN (LSTM) on a classification task using the Skip-gram word vectors and save the model as "skip-gram-classification-model.pt".
skip-gram-classification-model.pt: Pre-trained RNN (LSTM) model for classification task using Skip-gram word vectors.
skip-gram-word-vectors.pt: Pre-trained word vectors obtained using the Skip-gram method. (https://drive.google.com/file/d/121Ub54b6DP-VnGtkrkkPiqVyfq-pTuna/view?usp=sharing)
Download Skip-gram files

Usage:
Clone the repository or download the files from the provided Google Drive links.
Run the respective Python scripts (svd.py, skip-gram.py, svd-classification.py, skip-gram-classification.py) to train word embeddings or classification models.
Ensure you have the required dependencies installed.
Feel free to modify the code according to your needs and experiment with different parameters.
Dependencies:
Python 3.x
PyTorch
NumPy
Other dependencies as mentioned in the scripts.