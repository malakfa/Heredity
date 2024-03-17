# Heredity

## Overview

Heredity is a project that utilizes Bayesian Network modeling to make inferences about the probability distribution of genes and observable traits within a population. Specifically, it focuses on understanding the inheritance patterns of mutated versions of the GJB2 gene, a leading cause of hearing impairment in newborns.

## Problem Statement

Mutated versions of the GJB2 gene can lead to hearing impairment in individuals. However, determining the number of mutated copies of the gene in a person is not always straightforward. This creates a "hidden state" where the presence of the mutation may not directly correlate with the observable trait of hearing impairment.

## Bayesian Network

The project utilizes a Bayesian Network to model relationships between gene copies and observable traits within a family. Each individual in the family is represented by random variables for their gene copies (0, 1, or 2) and their trait (yes or no for hearing impairment). Arrows in the network indicate dependencies between these variables, capturing the influence of parental genes on the child's genes and traits.

## Inference

Using the Bayesian Network model, the AI makes inferences about the probability distribution of genes and observable traits in the population. It takes into account information about individuals, their parents, and observed traits to estimate the likelihood of different gene copies and trait expressions.

## Future Enhancements

- Implement more sophisticated algorithms for inference, such as belief propagation or Markov chain Monte Carlo (MCMC) methods.
- Extend the model to consider additional factors influencing trait expression, such as environmental factors or interactions with other genes.
- Develop a user-friendly interface for inputting data and visualizing inference results.
.
