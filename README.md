# DDLS 2024 Course Project
This repository contains the final project for the Data-Driven Life Science (DDLS) Course 2024.

## Overview
The project aims to apply deep learning approaches, using the Geneformer model, to perform cell classification and in-silico gene perturbations to study Type 1 and Type 2 diabetes. 

## Notebook
The notebook `DDLS_2024_final_project_OF_new.ipynb` contains the following:
- Tokenizing of single-cell RNA-seq data.
- Fine-tuning of the Geneformer model for cell state classification.
- Evaluation metrics (accuracy, confusion matrix, clustered heatmap).
- In-silico gene perturbation analysis influence on cell states.

## Requirements
To run this notebook, you need:
- Google Colab or a local Python environment.
- Packages such as `transformers`, `scanpy`, and `torch`.

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/ddls_course_2024_project.git
   ```
2. Open the notebook and run it in a Colab environment or Jupyter.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
This project was guided by the DDLS 2024 course, and special thanks to ChatGPT for assisting with the implementation.
