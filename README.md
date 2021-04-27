# FlappyBirdAI

## TLDR (How it works/What is it?):

An AI that learns how to play flappy bird, using NEAT (NeuroEvolution of Augmenting Topologies).
Essentially, we spawn birds, they try different things, and we take attributes from the 'species' that go the furthest. 
By doing so, we favor specific attributes, and more birds have that attribute, and get better.

## NEAT:

![Two Birds playing](/imgs/"Birds Playing.PNG")

"NEAT (NeuroEvolution of Augmenting Topologies) is an evolutionary algorithm that creates artificial neural networks. For a detailed description of the algorithm, you should probably go read some of Stanley’s papers on his website.....

To evolve a solution to a problem, the user must provide a fitness function which computes a single real number indicating the quality of an individual genome: better ability to solve the problem means a higher score. The algorithm progresses through a user-specified number of generations, with each generation being produced by reproduction (either sexual or asexual) and mutation of the most fit individuals of the previous generation." [NEAT Overview](https://neat-python.readthedocs.io/en/latest/neat_overview.html)

## Pygame:

I used Pygame to make the game. I first made the game from scratch using a Youtube Video, and some good old OOP.

### Classes: 
* Bird 
* Pipe
* Base

Something I learned when making this game is that instead of the bird moving towards the pipes, 
we make the illusion that the Bird moves by moving everyhing towards the bird!


