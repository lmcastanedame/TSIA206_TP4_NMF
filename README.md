# Non-negative Matrix Factorization (TSIA206)

This project is part of the TSIA206 course and focuses on the implementation and application of Non-negative Matrix Factorization (NMF) for data decomposition. NMF is widely used for applications such as audio source separation, image processing, and dimensionality reduction.

## Project Description

NMF is a factorization technique that decomposes a matrix into two smaller non-negative matrices, allowing for the extraction of meaningful features from the original data. In this project, NMF is applied to different datasets, such as audio signals, to separate distinct components (e.g., vocals and instruments). This project demonstrates the power of NMF for analyzing and extracting features from complex data.

## Project Structure

The repository contains the following files and directories:

- **main.py**: The main script for applying NMF to various datasets.
- **datasets/**: A directory containing the datasets used for testing the NMF algorithm, such as audio signals or images.
- **nmf.py**: A module implementing the NMF algorithm and related utility functions.
- **notebooks/**: Jupyter notebooks for experimenting with NMF and visualizing the results.
- **requirements.txt**: A file listing the required dependencies for running the project.
- **README.md**: This file, providing an overview of the project.

## How to Use

### Prerequisites

- Python 3.x
- Libraries: NumPy, SciPy, librosa, scikit-learn, Matplotlib

Install the necessary dependencies using:

```bash
pip install -r requirements.txt
```

### Running the Project

To apply NMF to a dataset and view the results, follow these steps:

1. Select a dataset from the `datasets/` directory (e.g., audio files or images).
2. Run the main script to apply the NMF algorithm:

    ```bash
    python main.py
    ```

3. The output will be the separated components of the dataset, saved in the `output/` directory, along with visualizations of the factorized matrices.

### Key Steps in the Process

1. **Load Dataset**: Load the input data (e.g., audio or image) from the `datasets/` directory.
2. **Apply NMF**: Factorize the input data into two non-negative matrices.
3. **Reconstruct Components**: Use the factorized matrices to reconstruct and analyze the individual components of the original data.
4. **Visualize Results**: Plot the components and visualize the factorized matrices to interpret the results.

## Purpose

The purpose of this project is to explore how NMF can be used to separate and analyze components from complex datasets. NMF is particularly useful for tasks like audio source separation, image decomposition, and feature extraction, providing insights into the structure of the data.

## Technologies

- **Language**: Python
- **Libraries**: NumPy, SciPy, librosa, scikit-learn, Matplotlib
- **Tools**: Jupyter Notebooks for testing and visualizing results
