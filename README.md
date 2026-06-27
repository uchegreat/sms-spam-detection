# SMS Spam Detection

A machine learning project that classifies SMS messages as **spam** or **ham** (not spam).

## Overview

This project uses natural language processing and machine learning to detect spam messages in SMS text. The model is trained on labeled SMS data and predicts whether a new message is spam or legitimate.

## Model Performance

The trained model achieved:
- Accuracy: 98%
- Precision: 98%
- Recall: 86% for the spam class
- F1-score: 92% for the spam class

## Features

- SMS message classification.
- Text preprocessing and cleaning.
- Machine learning model training and evaluation.
- Confusion matrix visualization.
- Performance metrics comparison chart.
- Prediction on custom messages.

## Project Files

```text
.
├── Colab-SMS-spam-source-code.ipynb
├── README.md
└── requirements.txt
```

## Requirements

- Python 3.10+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- nltk

## Installation

Clone the repository:
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

Create a virtual environment:
```bash
python -m venv venv
```

Activate it:

Windows:
```bash
venv\Scripts\activate
```

macOS/Linux:
```bash
source venv/bin/activate
```

Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

Open the notebook in Google Colab or Jupyter Notebook and run the cells step by step.

If you want to run the project locally:
```bash
jupyter notebook
```

## Dataset

The project uses a labeled SMS dataset with two classes:
- Ham
- Spam

## Visualization

The notebook includes:
- a confusion matrix heatmap,
- a bar chart showing model performance metrics.

## Notes

- Keep large dataset files out of the repository if possible.
- Make sure the notebook cells are run in order.
- Update the GitHub repository name in the clone command before uploading.

## Author

Uche Great
