# Sentiment_analysis_DL

## Overview
This repository contains code for sentiment analysis using deep learning techniques. The model is designed to analyze and classify the sentiment (positive or negative) of text data.

## Contents
- `notebook.ipynb`: Jupyter Notebook containing the main code for sentiment analysis.
- `data/`: Directory for storing dataset files.
- `models/`: Directory for saving trained models.
- `requirements.txt`: List of dependencies for reproducing the environment.

## Prerequisites
Ensure you have the required dependencies installed. You can install them using the following command:
```bash
pip install -r requirements.txt
```
## Dataset
The sentiment analysis model is trained on the Twitter Sentiment140 dataset. To use the dataset, follow these steps:

1. **Download Dataset:**
   Download the dataset from [Twitter Sentiment140](https://www.kaggle.com/kazanova/sentiment140).

3. **File Structure:**
   Ensure the dataset files are organized with the following structure:
   data/
   ├── training.1600000.processed.noemoticon.csv
   └── other_dataset_files...
   Now you're ready to use the dataset for training and evaluating the sentiment analysis model.

## Usage
1. **Run the Jupyter Notebook:**
   Open the Jupyter Notebook `SentimentAnalysis.ipynb` to train and evaluate the sentiment analysis model.

2. **Adjust Hyperparameters:**
   Experiment with hyperparameters, model architecture, and preprocessing techniques based on your requirements.

3. **Save Trained Model:**
   Save the trained model in the directory for later use.

## Model Optimization
Feel free to experiment with different architectures, hyperparameters, and preprocessing techniques to optimize the performance of the sentiment analysis model.

## Issues and Contributions
- If you encounter any problems or have suggestions for improvement, please open an issue.
- Contributions are welcome! Fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License - see the [MIT](LICENSE) file for details.

## Acknowledgments
Citation: Go, A., Bhayani, R. and Huang, L., 2009. Twitter sentiment classification using distant supervision. CS224N Project Report, Stanford, 1(2009), p.12..

