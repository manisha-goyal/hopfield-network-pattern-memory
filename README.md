# Hopfield Network for Pattern Memory

This repository demonstrates the use of a Hopfield network to remember and recall patterns. The Hopfield network is trained to recognize binary patterns and can recover original patterns even when they are occluded or noisy.

## Project Structure

- **Hopfield_Network_Pattern_Memory.ipynb** - Notebook that includes the implementation, training, and testing of the Hopfield network for pattern memory.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/manisha-goyal/hopfield-network-pattern-memory.git
    cd hopfield-network-pattern-memory
    ```
    
## Usage

Open the notebook in Jupyter or Google Colab and execute the cells to experiment with pattern occlusion, noise addition, and recovery using the Hopfield network.

## Key Components

- **Binary Pattern Memory**: Stores and recalls binary patterns using associative memory.
- **Occlusion and Noise Handling**: Supports occluding parts of the pattern and adding Gaussian and salt-and-pepper noise.
- **Pattern Recall**: Recovers the original patterns based on network weights and initial inputs.
