# Outline
*v1*

- Going through the Fast Gradient Sign Method with examples and explaining why it works
- Discussing the notion of 'real' images occupying only a slim manifold in the space of all possible images, surrounded by adversarial images
- Going through the Boundary Attack algorithm with examples and explaining why it works
- Discussing the idea that adversarial examples can be attributed to linearity of the models and comparing relu vs tanh models
- Brief discussion of defence mechanisms

### History of Adversarial Examples

Begin with [Szegedy](https://arxiv.org/pdf/1312.6199.pdf), followed by [Goodfellow](https://arxiv.org/pdf/1412.6572.pdf).

### Fast Gradient Sign Method

Use a toy example for illustrating FGSM. Try to use as shallow/small a network as possible so it is intuitive to understand how the gradients and weights affect the output. Use MNIST or shapes dataset.

### Linearity of Models

Visualize the boundaries for classifier to illustrate linearity of models.

### Boundary Attack

Similar to above section.

### The Ideal Classifier

What would an ideal ((super)human-level) classifier do when faced with adversarial examples? Manifold of 'valid' images.

### Adversarial Examples for Humans

Yanny vs Laurel meme