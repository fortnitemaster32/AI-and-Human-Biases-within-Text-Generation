# HumanAi: AI vs Human Text Analysis

This project analyzes biases and differences between AI-generated and human-generated text using a dataset from Kaggle. It focuses on lexical diversity, average word length, and average sentence length to compare the characteristics of both text types.

## Dataset

- Source: [Kaggle - Human vs AI Text Classification](https://www.kaggle.com/code/sumedh1507/human-vs-ai-text-classification)
- File used: `ai_human_content_detection_dataset.csv`

## Features Analyzed

- **Lexical Diversity**: Measures the variety of words used.
- **Average Word Length**: Compares the typical word length in AI vs human text.
- **Average Sentence Length**: Compares sentence length distributions.

## Key Findings

- AI-generated text tends to have word and sentence lengths near the median of the dataset.
- Human-generated text is biased towards shorter average word lengths.
- Human texts are more prevalent in sentence lengths just outside the median bins.
- Lexical diversity shows no significant bias, though the lower range is slightly skewed towards AI.

## Usage

1. Clone the repository and place the dataset in the project folder.
2. Open `main.ipynb` in VS Code or Jupyter Notebook.
3. Run the notebook cells to see data analysis and visualizations.

## Requirements

- Python 3.x
- pandas
- matplotlib

Install dependencies with:
```
pip install pandas matplotlib
```

## License

This project is for educational purposes. Dataset copyright belongs to the original Kaggle