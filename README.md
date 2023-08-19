# DBN_receptive_fields
The objective of this project is to implement simulations to explore computational models of visual concept learning. The idea is to explore unsupervised learning in generative model with a Deep Belief Network and try to make sense of the rappresentation with our discoveries.

In the notebook, we will exploit the EMNIST dataset from [aurelienduarte/emnist](https://github.com/aurelienduarte/emnist) to study what the hidden states of the DBN taken from the repository [flavio2018/Deep-Belief-Network-pytorch](https://github.com/flavio2018/Deep-Belief-Network-pytorch) do or "recognise".


In particular we will:

- Visualize receptive fields
- Visualize clustering representation
- Add Linear-ReadOut to check performance in each layer
- Compare DBN with a Feed-Forward NN
- Understand robustness to sensory perturbation by injecting noisy data
- Use adversarial attack and compare models
