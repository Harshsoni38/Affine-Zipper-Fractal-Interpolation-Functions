Affine Zipper Fractal Interpolation Functions (FIFs)

Overview

Affine Zipper Fractal Interpolation Functions (FIFs) combine a 'zipper' strategy with a binary signature and scaling functions to model complex datasets using Iterated Function Systems (IFS). This approach is particularly useful in applications such as:

Image Compression

Signal Processing

Computational Mechanics

Physics Simulations

By utilizing affine transformations and the zipper method, this project aims to improve fractal-based function approximations, including functions like the Weierstrass function.

Features

Zipper Strategy: A novel approach to fractal interpolation.

Binary Signature Encoding: Enhances function modeling accuracy.

Iterated Function System (IFS): Generates self-similar structures.

Function Approximation: Capable of approximating complex datasets.

Applications in Engineering & Physics: Useful for computational modeling.

Usage

Example usage of the project:

from zipper_fif import ZipperFIF

# Initialize parameters
params = {...}  # Define function parameters

# Create a fractal interpolation function
fif = ZipperFIF(params)

# Generate and visualize the fractal
fif.generate()
fif.plot()

Project Structure

├── src/               # Source code
│   ├── zipper_fif.py  # Main implementation
│   ├── utils.py       # Utility functions
├── examples/          # Example usage scripts
├── docs/              # Documentation
├── tests/             # Unit tests
├── README.md          # Project description
├── requirements.txt   # Dependencies

Contributing

Contributions are welcome! Please follow these steps:

Fork the repository.

Create a new branch (feature-branch).

Commit your changes.

Push to your fork.

Open a pull request.

