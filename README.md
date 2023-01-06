# AI-Optimal-Flappy-Bird

An AI is training itself how to play the game "Flappy Bird". The way it works is that while the pipes are randomly generated, the AI repeatedly makes the effort to learn how the game works by having many generations until it slowly gets to a point where it does not fail. This uses something that is called a genetic algorithm called *NEAT* (NeuroEvolution of Augmenting Topologies). With every new generation the algorithm takes the best outcome from the many of birds from the game and produces new evolved versions of that said best outcome.
<p align="center">
  <img src="https://user-images.githubusercontent.com/90230330/210989828-3b5f6214-ab08-4d9c-aa76-c418ff338c8d.gif"/>
</p>

## Requirements
* pygame
* neat-python
* os
* random

## Instructions
* Download  ```config-feedforward.txt```, ```imgs``` folder and ```flappy.py``` 
* run ```flappy.py```
* That's it! Now watch how the algorithm works!
