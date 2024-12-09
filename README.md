# Sentiment_Analysis_with_BERT

## Project Overview
This project implements a sentiment analysis model using BERT (Bidirectional Encoder Representations from Transformers) to classify user reviews from the Google Play Store into three sentiment categories: negative, neutral, and positive. The model leverages the power of BERT to understand the context of words in sentences, providing accurate sentiment predictions.

## Objectives
- Build a sentiment analysis model using BERT.
- Evaluate the model's performance on a dataset of Google Play app reviews.
- Provide insights into the model's predictions and potential applications.

## Table of Contents
1. [Installation](#installation)
2. [Usage Instructions](#usage-instructions)
3. [Model Training](#model-training)
4. [Evaluation](#evaluation)
5. [Results](#results)
6. [Future Work](#future-work)
7. [Contributing](#contributing)
8. [License](#license)

## Installation
To run this project, you need to have Python installed along with the required libraries. You can install the necessary libraries using pip:

```bash
pip install -q -U transformers torch pandas seaborn matplotlib
```
## Usage Instructions
1. Clone the Repository: Clone this repository to your local machine using the following command:

```
git clone https://github.com/yourusername/sentiment-analysis-bert.git
cd sentiment-analysis-bert
```
2. Download the Dataset: The dataset can be downloaded using the provided script. Ensure you have internet access when running the script.

3. Run the Model: To run the sentiment analysis model, execute the following command:
```
python nlp_final__prjt.py
```
4. Predict Sentiment: You can input your own text for sentiment prediction. Modify the review_text variable in the script to test different reviews.

## Model Training
The model is trained using the Google Play app reviews dataset. The training process involves:

## Tokenizing the reviews using BERT's tokenizer.
- Creating a PyTorch dataset and data loaders.
- Training the model using the AdamW optimizer and cross-entropy loss function.

## Evaluation
After training, the model is evaluated on a test dataset. Key performance metrics include:

- Accuracy
- F1 Score
- Confusion Matrix

You can view the evaluation results in the output of the script.

## Results
The model achieves a high accuracy on the test set, demonstrating its effectiveness in classifying sentiments. The confusion matrix provides insights into the model's performance across different sentiment classes.

## Future Work

- Data Augmentation: Implement techniques to balance the dataset and improve model performance.
- Model Fine-tuning: Experiment with different hyperparameters and architectures to enhance accuracy.

## Contributing
Contributions are welcome! If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.


