# SMS Spam Detection

SMS spam detection model built with Python and machine learning.

## Overview

This repository contains code and resources for training and evaluating a machine learning model to classify SMS messages as spam or ham (not spam). The project covers data preprocessing, feature extraction, model training, evaluation, and basic inference.

## Contents

- data/: Datasets and data processing scripts
- src/: Source code for training, evaluation, and inference
- notebooks/: Exploratory notebooks
- models/: Saved trained models

## Getting Started

1. Clone the repository:

   git clone https://github.com/uchegreat/sms-spam-detection.git

2. Create and activate a Python virtual environment (recommended):

   python -m venv .venv
   source .venv/bin/activate  # macOS/Linux
   .venv\Scripts\activate     # Windows

3. Install dependencies:

   pip install -r requirements.txt

4. Prepare the data and run training scripts in `src/`.

## Dataset

A common dataset for SMS spam detection is the "SMS Spam Collection" dataset. Place datasets in the `data/` directory and update data paths in the scripts.

## Contributing

Contributions are welcome. Please open issues or pull requests for bug fixes and enhancements.

## License

Specify a license for the project (e.g., MIT).