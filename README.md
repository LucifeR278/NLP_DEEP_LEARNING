# SkimLit: NLP for Medical Abstracts

## Overview
SkimLit is a project focused on building an NLP model to simplify the process of reading and extracting insights from medical abstracts. The goal is to automate and enhance the understanding of scientific literature, especially in the medical domain.

This project is inspired by and replicates methods from a research paper that proposes effective NLP techniques for analyzing medical abstracts. The dataset and model architecture are derived from the referenced sources.

- **Dataset Source**: [arXiv:1710.06071](https://arxiv.org/abs/1710.06071)
- **Best Model Architecture**: [arXiv:1612.05251](https://arxiv.org/abs/1612.05251)

## Key Features
- Implements state-of-the-art NLP techniques for medical text classification.
- Processes medical abstracts to extract useful sections and information.
- Recreates a proven architecture for optimal results.

## Project Structure

- **Data Loading**: Includes scripts and utilities for loading and preprocessing the medical abstracts dataset.
- **Model Implementation**: Contains the model architecture as described in the referenced papers.
- **Evaluation**: Includes metrics and analysis for evaluating model performance.

## Prerequisites

### Tools and Libraries
The project requires the following libraries:
- Python (>=3.7)
- TensorFlow
- Pandas
- NumPy
- Matplotlib

### Data
Ensure you have access to the dataset linked in the source paper ([Dataset](https://arxiv.org/abs/1710.06071)).

## How to Run
1. Clone the repository to your local machine.
   ```bash
   git clone <repository_url>
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook SkimLit_Project.ipynb
   ```
4. Follow the steps in the notebook to train and evaluate the model.

## References
- Dataset Paper: [arXiv:1710.06071](https://arxiv.org/abs/1710.06071)
- Model Architecture: [arXiv:1612.05251](https://arxiv.org/abs/1612.05251)

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

**Note**: This README is a starting point based on the notebook content. Additional details can be added as the project evolves.
