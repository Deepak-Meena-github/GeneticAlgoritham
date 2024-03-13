# Genetic Algorithm Classifier in Python

This project implements both binary and real-coded genetic algorithms in Python, which can be used as functional classifiers.

## Features

- **Binary Tournament Selection**: This feature is used to select two parents for the next generation. It works by randomly selecting two individuals from the population and choosing the one with the best fitness.

- **Single Point Crossover**: This function is applied over binary-coded parent chromosomes to generate a set of optimal datasets. These datasets can classify the optimal value for further generations.

- **Simulated Binary Crossover**: This is used for real-coded genetic data. It predicts the optimal values following a deterministic statistical approach.

## Usage

To use this project, you need to have Python installed on your machine. You can then run the `RealCodedGeneticALgo.py` script to start the genetic algorithm.

# Binary Coded Genetic Algorithm in Python

This project implements a binary coded genetic algorithm in Python.

## Features

- **Mutation**: The algorithm includes a mutation operation that randomly flips bits in the binary string representation of the individuals in the population. The mutation probability determines the likelihood of each bit being flipped.

- **Decoding**: The binary string representation of each individual is decoded into a real number within a specified range. This is done using the `decode` function, which takes the binary string, its length, and the lower and upper bounds of the range as arguments.

## Usage

To use this project, you need to have Python installed on your machine. You can then run the `binaryCodedGeneticALgo.py` script to start the genetic algorithm.

## Contribution

Contributions are welcome! Please feel free to submit a Pull Request.
