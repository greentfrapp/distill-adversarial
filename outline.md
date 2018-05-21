# Outline
*v1*

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

### Defence Approaches

Brief overview of defence approaches

### Adversarial Examples for Humans

Yanny vs Laurel meme

# Code ToDo

- Implement FGSM with shallow network on simple dataset (MNIST / shapes)
- Implement Boundary Attack with tSNE/PCA for visualizing path of generated samples
