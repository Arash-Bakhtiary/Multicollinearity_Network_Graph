# Interactive Multicollinearity Network Graph

This project demonstrates how to visualize multicollinearity in high-dimensional datasets using interactive network graphs with Plotly and NetworkX. The tool also allows dynamic thresholding of feature correlations.

## Features
- Visualizes multicollinearity with a Maximum Spanning Tree (MST) of feature correlations.
- Interactive slider to adjust the correlation threshold dynamically.
- Uses synthetic data for demonstration purposes, but can be adapted for real datasets.

## Getting Started

### Prerequisites
- Python 3.x
- Install the required packages:
  ```bash
  pip install numpy pandas networkx plotly scikit-learn ipywidgets
