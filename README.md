# CNN Tutorial

Tutorial materials explaining convolutional neural networks.

The tutorial is currently composed of two notebooks: 

  - `exercise-1_keras.ipynb` explains how to make basic neural networks in Keras
  - `exercise-2_cnn.ipynb` explains how CNNs work, and how to make one with Keras
  
## Using the Notebooks

The notebooks are designed to be easy to use on the cloud or on your own systems.

### Running Locally

The environment needed for the notebook is described in [`environment.yml`](./environment.yml)

First, install [Anaconda](https://docs.anaconda.com/anaconda/install/) then use Anaconda's command line tool to build the environment:

```bash
conda env create --file environment.yml
```

### Running on Google Colab

You can also run these notebooks on Google Colaboratory, either by searching for `AIScienceTutorial` in their GitHub extension or directly using these links:

- [Exercise 1: Keras](https://colab.research.google.com/github/AIScienceTutorial/cnn-tutorial/blob/main/exercise-1_keras.ipynb)
- [Exercise 2: CNNs](https://colab.research.google.com/github/AIScienceTutorial/cnn-tutorial/blob/main/exercise-2_cnns.ipynb)

Note that you may want to use a GPU for exercise 2, which you can change from the "Runtime->Change runtime type" menu.
