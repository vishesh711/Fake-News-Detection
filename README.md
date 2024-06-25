# Fake News Detection Using Logistic Regression

## Overview
This project aims to build a machine learning model using logistic regression to accurately detect whether a given news article is real or fake. The dataset consists of various news articles, each labeled as 'Fake' or 'Real'. The model uses natural language processing techniques to preprocess text data, convert text to numerical vectors using TF-IDF, and then applies logistic regression for classification.

## Dataset Description
The dataset contains the following fields:
- `id`: Unique identifier for each news article.
- `title`: Title of the news article.
- `author`: Author of the news article.
- `text`: Main text of the article; may be incomplete.
- `label`: Binary label indicating whether the news is fake (`1`) or real (`0`).

## Dependencies
This project requires Python and the following Python libraries installed:
- NumPy
- Pandas
- NLTK
- scikit-learn

You can install these libraries using `pip`:
```bash
pip install numpy pandas nltk scikit-learn
```

## Usage
1. Clone this repository:
   ```bash
   git clone [URL-to-your-repository]
   cd [repository-name]
   ```
2. Download the dataset and place it in the project directory, typically under a subdirectory like `/data`.
3. Run the Jupyter notebook:
   ```bash
   jupyter notebook fake_news_detection.ipynb
   ```

## Model Training and Evaluation
The logistic regression model is trained on the preprocessed dataset. Evaluation metrics used include accuracy score, which is printed for both the training and testing datasets.

## Results
- Training accuracy: 98.66%
- Testing accuracy: 97.91%

## Predictive System
The model can predict new instances once it is trained. An example setup for making predictions is included in the notebook.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue if you have suggestions or improvements.

## License
This project is open source and available under the [MIT License](LICENSE).
