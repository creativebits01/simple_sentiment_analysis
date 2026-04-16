# Sentiment Analysis on Amazon Reviews

A machine learning project for analyzing sentiment in Amazon product reviews using natural language processing techniques.

## Features

- Data preprocessing and cleaning of Amazon reviews
- Feature engineering for NLP tasks
- Sentiment classification models
- Jupyter notebooks for exploratory data analysis and model development

## Installation

1. Install Python 3.11 (or your preferred version):
   ```
   uv python install 3.11
   ```

2. Create and activate virtual environment:
   ```
   uv venv nlpvenv --python 3.11
   nlpvenv\Scripts\activate  # On Windows
   ```

3. Install dependencies:
   ```
   uv pip install -r requirement.txt
   ```

## Usage

1. Run the preprocessing notebook:
   ```
   jupyter notebook notebooks/reviews_preprocessing.ipynb
   ```

2. Perform feature engineering:
   ```
   jupyter notebook notebooks/nlp_feature_engineering.ipynb
   ```

3. Explore web scraping (if needed):
   ```
   jupyter notebook notebooks/webscapping.ipynb
   ```

## Project Structure

```
├── data/
│   ├── amazon_reviews.csv      # Raw Amazon reviews data
│   └── cleaned_reviews.csv     # Preprocessed reviews
├── notebooks/
│   ├── reviews_preprocessing.ipynb    # Data cleaning and preprocessing
│   ├── nlp_feature_engineering.ipynb  # Feature extraction and engineering
│   └── webscapping.ipynb              # Web scraping utilities
├── nlpvenv/                    # Python virtual environment
├── commands.txt                # Setup and usage commands
├── requirement.txt             # Python dependencies
└── README.md                   # Project documentation
```

## Data

The project uses Amazon product reviews dataset for sentiment analysis. Raw data is stored in `data/amazon_reviews.csv` and preprocessed data in `data/cleaned_reviews.csv`.

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License.