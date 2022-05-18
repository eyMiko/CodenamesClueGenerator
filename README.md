# CodenamesClueGenerator

This project is a clue generator for the popular party game, Codenames. It utilizes various NLP Techniques on the pre-trained FastText model to generate the best clues possible. The tools used were Python, Jupyter Notebook, Gensim, NLTK, PyGame, and more.

## Initial Set Up

- Clone the repo
- Run [src/initialize.ipynb](/src/initialize.ipynb). This file will:
  - install the necessary python modules
  - load in the FastText model
  - save the model to [data/fasttext_vectors.kv](/data) for faster load in future
  - create a similarity matrix for hint words and save to [data/similarity_matrix.csv](/data)

## How to Run

There are two modes to run in:

### UI Mode

Play with the UI by running [src/ui.ipynb](/src/ui.ipynb). Press on the board to make your guesses. Press 'S' to skip your turn, 'ESC' to close the window, and 'R' to reload a new game.

### Testing Mode

Test the functionality by running [src/test.ipynb](/src/test.ipynb). This mode will give a very barebones output for easier testing of the implementation.
