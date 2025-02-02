# LLM - Detect AI Generated Text

## Project Overview

This project builds and trains a model to classify text as either **AI-generated** by **Large Language Models (LLMs)** or written by humans. The implementation demonstrates the use of **Natural Language Processing (NLP)** and **probabilistic modeling** techniques to achieve high accuracy in authorship detection.

All steps, including data preprocessing, model building, evaluation, and visualization, are implemented in a single Jupyter Notebook.

## Key Features

- **Preprocessing**: Cleaned and tokenized text data to prepare it for analysis.
- **Classification**: Used a probability-based approach with Laplace smoothing to distinguish between human and AI-generated text.
- **Analysis**: Identified top words contributing to classification for both human and AI-generated content.
- **Visualization**: Explored the effect of vocabulary size on model performance.

## Technologies Used

- **Python**: Core programming language for the project.
- **Jupyter Notebook**: For development, experimentation, and visualization.
- **NLTK**: For tokenization and text preprocessing.
- **Pandas and NumPy**: For data manipulation and numerical computations.
- **Matplotlib**: For visualizing trends in model accuracy.

## Installation and Setup

### Prerequisites
- Python 3.8+
- Jupyter Notebook (or a similar environment like JupyterLab or Kaggle Notebooks)

### Steps to Run
1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/llm-detect-ai-generated-text.git
    cd llm-detect-ai-generated-text
    ```

2. **Launch the Notebook**:
    ```bash
    jupyter notebook detect_ai_text.ipynb
    ```

3. **Follow the Notebook**:
    - The notebook is divided into clear sections for preprocessing, model training, and evaluation.

4. **Save Outputs**:
    - Predictions and visualizations are generated directly in the notebook.

## Dataset

The dataset includes:
- **Human-Written Text**: Essays authored by humans.
- **AI-Generated Text**: Text generated by Large Language Models (LLMs).

The data is preprocessed and analyzed within the notebook.

## Results

- Achieved ~89% accuracy in distinguishing between human and AI-generated text.
- Identified top predictive words for both human and AI text classes.

## Future Scope

- Expand the dataset with additional samples of human and LLM-generated text.
- Explore transformer-based models (e.g., BERT) for improved classification performance.
- Develop a web-based interface for real-time text classification.
