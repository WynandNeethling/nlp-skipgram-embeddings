# Skipgram Word Embedding Model

This project involves training a Skipgram word embedding model using the AG-news dataset. 
The model is implemented from scratch using standard Python libraries and PyTorch, and it can be trained on both GPU and CPU. 
The project includes code for data preprocessing, model training, evaluation, and visualisation.

## File

- `Wynand_Neethling_Assignment2_Code.ipynb`: The main Jupyter Notebook containing the entire code for the project.

## Libraries Used

The following libraries are used in this project:

- [numpy]
- [re]
- [collections]
- [matplotlib.pyplot]
- [seaborn]
- [itertools]
- [pandas]
- [torch]
- [torchvision]
- [scikit-learn]
- [scipy]

## Pre-trained Embeddings

Two pre-trained embedding files are provided:
- `center_embeddings_10.npy`
- `center_embeddings_100.npy`

Note that these pre-trained embeddings are trained using the provided code and is only included to speed up the marking process (code evaluation). 

## How to Run the Code
- Ensure all necessary libraries are installed.
- Open and run the `Wynand_Neethling_Assignment2_Code.ipynb` notebook.
- Optionally, load pre-trained embeddings to skip training.

## Notes
- Ensure you have the AG-news dataset available.
- Adjust file paths as necessary.
- For GPU training, use Google Colab or a suitable environment.
