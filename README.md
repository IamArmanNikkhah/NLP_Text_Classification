# NLP_Text_Classification

This project implements a basic Natural Language Processing (NLP) pipeline for sentiment analysis on the IMDB movie reviews dataset. It demonstrates text preprocessing, feature extraction, model training, and evaluation for binary classification (positive vs. negative sentiment).

## Features

- Data loading and cleaning for IMDB movie reviews
- Text preprocessing: tokenization, stopword removal, and stemming/lemmatization
- Feature extraction using techniques such as bag-of-words and TF-IDF
- Training of supervised machine learning models (e.g., Logistic Regression, SVM, Naive Bayes)
- Jupyter notebook (`Homework_3_Text_Classification_1_NLP.ipynb`) illustrating exploratory data analysis, model training, and evaluation
- Standalone script (`text_classification.py`) to train and evaluate models from the command line

## Project Structure

```
┌─ Homework_3_Text_Classification_1_NLP.ipynb  # Jupyter notebook with analysis and experiments
├─ README.md                                   # This documentation
└─ text_classification.py                      # Python script for training and evaluating models
```

## Getting Started

Clone the repository and install the required dependencies (e.g., `numpy`, `pandas`, `scikit-learn`, `nltk`).

```bash
git clone https://github.com/IamArmanNikkhah/NLP_Text_Classification.git
cd NLP_Text_Classification
# Install dependencies
pip install numpy pandas scikit-learn nltk jupyter
```

The notebook can be run in Jupyter to explore the pipeline and results:

```bash
jupyter notebook Homework_3_Text_Classification_1_NLP.ipynb
```

To train and evaluate a model from the command line:

```bash
python text_classification.py --model logistic_regression --dataset_path path/to/imdb_dataset.csv
```

## Contributions

Contributions are welcome! Please open an issue or pull request to propose improvements or additional features.

## License

This project is released under the MIT License. See the [LICENSE](LICENSE) file for details.
