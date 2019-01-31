
# Section Recap

## Introduction

This short lesson summarizes key takeaways from section 48.

## Objectives
You will be able to:
* Understand and explain what was covered in this section
* Understand and explain why this section will help you become a data scientist

## Key Takeaways

The key takeaways from this section include:

* Generative models have several applications in the areas of image processing and text analysis, and also have the property that they have the ability to automatically learn the natural features of a dataset
* Generative Models learn the joint probability distribution $ P(x,y)$, where Discriminative  Models learn the conditional probability distribution $ P(y|x)$
* Where "standard" AEs build generative models to exactly replicate the same data, variational autoencoders generate "variations" on the input image
* Variational Autoencoders (VAEs) are powerful generative models that produce excellent results for complex applications from generating (fake) human faces, to producing music
* Unlike Variational Autoencoders (VAEs), Generative Adversarial Networks  (GANs) do not work by calculating probability density estimations like VAEs, but are based on a Game Theoretic approach with an objective to find the Nash equilibrium between the two networks
