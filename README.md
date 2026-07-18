# DL — Deep Learning Curriculum Notebooks

Topic-by-topic deep learning study notebooks — the `dl` phase of the [ML-DL-Roadmap](https://github.com/QuantumWebber/ML-DL-Roadmap) tracker, continuing on from the [ML](https://github.com/QuantumWebber/ML) curriculum repo.

Like `ML`, this is a learning/reference repo of independent topic notebooks, not a single deployed project.

---

## Curriculum Covered

### 1. ANN (`01. ANN/`)
- Perceptron introduction, backpropagation (worked through for both classification and regression, with a from-scratch MLP memoization notebook)
- Gradient descent, data scaling, the vanishing gradient problem
- NN improvement techniques: activation function choice, regularization
- ANN techniques: batch normalization, weight initialization, Xavier/Glorot/He initialization
- Optimizers: momentum, NAG, AdaGrad/RMSProp/Adam, exponential weighted averages
- Applied: a churn-modelling ANN example end to end

### 2. CNN (`02.CNN/`)
- CNN biological motivation, CNN vs. ANN, how convolution works, padding/strides/pooling
- Data augmentation
- LeNet architecture from scratch
- Transfer learning and pretrained models (Keras Functional API)
- Applied: Dogs vs. Cats classifier

### 3. RNN (`03.RNN/`)
- Deep RNNs, RNN fundamentals demo
- Applied: sentiment analysis with an RNN

### 4. Encoder–Decoder (`04.Encoders Decoders/`)
- Sequence-to-sequence architecture

---

## Format

Same pattern as the ML repo: each concept is a standalone Jupyter notebook, with small datasets committed alongside where needed (e.g. `Churn_Modelling.csv`, `DailyDelhiClimate.csv`, synthetic concentric-circle/u-shape data for visualizing decision boundaries).

---

## How This Connects to the Roadmap

Topics here are referenced by the [ML-DL-Roadmap](https://github.com/QuantumWebber/ML-DL-Roadmap) app's `dl` phase (Neural Networks, CNNs, RNNs/LSTMs, Transformers topic nodes), which links out to these folders as the actual study material.

---
