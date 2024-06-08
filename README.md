# Deep Learning - Transfer Learning

## Official hand in to run in a Google colab notebook

[Link to Notebook file](deep_learning_colab.ipynb) or already
uploaded [Notebook here](https://colab.research.google.com/drive/10XeYGhHIiUxkFvVNVVcEXvoJOUAzlPwg?usp=sharing)

### Quick Start

First, install the dependencies:

```bash
pip install -r requirements.txt
```

### Local version

Then, execute all the cells in the notebook [`preprocess.ipynb`](preprocess.ipynb) in order to do parts of the
preprocessing.

Finally, execute all the cells in the notebook [`deep_learning.ipynb`](deep_learning_local.ipynb).

### Overview of the project

Source data is in [`images`](images).

Training data is in [`training_data`](training_data) and testing data is in [`testing_data`](testing_data) each split up
in folders which are used as their labels.

Some extra data for the 'breaking the model' part is in [`breaking_data`](breaking_data). Images inside the folder
directly are the source images, and the folders inside hold the preprocessed images, again with the directory name
serving as the label.