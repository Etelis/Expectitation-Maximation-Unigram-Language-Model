# EM Clustering of News Articles

## Project Overview
This project demonstrates the application of the Expectation-Maximization (EM) algorithm for the unsupervised clustering of news articles into thematic groups. The goal is to categorize large sets of news articles based on content, facilitating an understanding of the underlying themes without prior labeling.

## Introduction
Utilizing the EM algorithm, a probabilistic approach for maximum likelihood estimation in the presence of latent variables, this project categorizes news articles into thematically similar clusters. This approach enables the exploration and discovery of natural groupings within the data, shedding light on the diverse themes present in news content.

## Implementation Details
### Extraction of Documents
- **Preprocessing**: Documents are preprocessed using regex for format matching, CSR matrix for sparse representation, and tokenization for word encoding.

### EM Algorithm Implementation
- **Efficiency**: The implementation leverages NumPy for vectorization, achieving a runtime of approximately 5 seconds.
- **Analysis**: Focuses on applying the EM algorithm to the preprocessed data to identify thematic clusters.

### Optimization of Hyperparameters
- **Objective**: Achieving a target accuracy score by optimizing parameters such as `lambda` and `k` values.

## Requirements
- Python 3.x
- Libraries: NumPy, Pandas, Scikit-learn, Matplotlib

## Running the Analysis
To replicate the analysis:
1. Install dependencies: `pip install numpy pandas scikit-learn matplotlib`.
2. Execute the Jupyter Notebook (`Applied_probability_models_for_CS_Exercise_3.ipynb`) in a Jupyter environment.
