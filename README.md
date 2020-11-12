# Generative models with tensorflow version 2.0 style
* All right reserved @ Il Gu Yi, Soochul Park

This repository is a collection of various generative models (Normalizing flow, Autoregressive models)
implemented by TensorFlow version 2.0 style


## Getting Started

### Prerequisites
* [`TensorFlow`](https://www.tensorflow.org) 2.0
* Python 3.6
* Python libraries:
  * `numpy`, `matplotlib`, `PIL`, `imageio`
  * `urllib`, `zipfile`
* TensorFlow libraries & extensions:
  * [`tensorflow_probability`](https://www.tensorflow.org/probability/)
* Jupyter notebook
* OS X and Linux (Not validated on Windows OS)


## Contents

### AutoRegressive Models [with MNIST]

#### Fully Visible Sigmoid Belief Networks
* [fvsbn.ipynb](https://nbviewer.jupyter.org/github/ilguyi/generative.models.tensorflow.v2/blob/master/autoregressive/fvsbn.ipynb)

| *MNIST* | *Fashion MNIST* |
|---|---|
| <img src='https://user-images.githubusercontent.com/11681225/57566483-068d6180-7408-11e9-9b92-6781e6ceb4af.gif'> | <img src='https://user-images.githubusercontent.com/11681225/57566471-eb225680-7407-11e9-85f5-04b7258d9b83.gif'> |

#### LSTM with MNIST
* [lstm_mnist.ipynb](https://nbviewer.jupyter.org/github/scpark20/generative.models.tensorflow.v2/blob/master/autoregressive/lstm_mnist.ipynb)

| *MNIST* |
|---|
| <img src='pics/lstm_mnist.png'> |

#### Transformer with MNIST
* Attention is All You Need [arXiv:1706.03762](https://arxiv.org/abs/1706.03762)
* [transformer_mnist.ipynb](https://nbviewer.jupyter.org/github/scpark20/generative.models.tensorflow.v2/blob/master/autoregressive/transformer_mnist.ipynb)

| *MNIST* |
|---|
| <img src='pics/transformer_mnist.png'> |

### Normalizing Flow Models [with MNIST]

#### NICE: Non-Linear Independent Components Estimation
* [nice.ipynb](https://nbviewer.jupyter.org/github/ilguyi/generative.models.tensorflow.v2/blob/master/normalizing_flow/nice.ipynb)

## Author
Il Gu Yi, Soochul Park

### Slides
[Notion link](https://www.notion.so/soochul/Generative-Models-12-4-6-353a0bbc5e0847fab4c864fb4332d9af?showMoveTo=true)
