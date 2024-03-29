# README for Real or Fake News Classification Project

## Introduction

This project focuses on the development of models to classify news articles into clickbait vs. non-clickbait and real vs. fake. Utilizing advanced Natural Language Processing (NLP) techniques and Machine Learning algorithms, the system provides an efficient solution to identify and categorize news content, aiding in the fight against misinformation.

## Classification Results Overview

### Clickbait vs. Non-clickbait Model:

- **Accuracy**: Achieved an accuracy of 93% with the Naive Bayes model.
- **Recall**: Attained a recall rate of 94%, indicating a high true positive rate.
- **Comparison**: The Multinomial Naive Bayes algorithm showed a lower accuracy of 81.8%. This is attributed to its focus on term frequency within specific instances, leading to potential bias towards certain topics like finance, even when other significant non-clickbait content is present.

### Real vs. Fake Model:

- **Accuracy**: The model achieved an accuracy of 91.9%, a result of comprehensive cross-validation across all models to ensure reliability and reduce overfitting.
- **Evaluation**: The project involved assessing various models to determine the most effective classifier for distinguishing between real and fake news.

## System Workflow

1. **News Article Input**: Users can input the URL of the news article for classification.
2. **Content Analysis**: The system processes the article content, applying NLP preprocessing techniques for data cleansing and preparation.
3. **Model Classification**: Implements Naive Bayes and Multinomial Naive Bayes algorithms for classification into clickbait/non-clickbait and real/fake.
4. **Result Display**: The classification results, along with the model's accuracy and recall metrics, are presented to the user.

## Technical Details

- **Data Preprocessing**: Involves converting text to lowercase, removing punctuation, stop words, and applying stemming to reduce words to their base or root form.
- **Feature Extraction**: Uses Term Frequency-Inverse Document Frequency (TF-IDF) to convert text into a numerical format for the machine learning models.
- **Machine Learning Algorithms**: Employs Naive Bayes for its probability-based approach and Multinomial Naive Bayes for its focus on frequency of terms.

## Implementation and Tools

- **IDE**: PyCharm 2021.1, tailored for Python development and system layout design.
- **Machine Learning Frameworks**: Utilizes Scikit-learn for implementing the classification models.
- **NLP Libraries**: Employs NLTK for natural language processing tasks, such as tokenization and stemming.
- **Cross-Validation**: Applied to all models to ensure their robustness and generalizability.

## Usage

1. Navigate to the project's web interface.
2. Enter the URL of the news article you wish to analyze into the designated field.
3. Submit the URL for processing and wait for the system to display the results.
4. Review the classification outcome along with detailed accuracy and recall information for each model.

## Contributing

Contributions are welcome to enhance the project's functionality and accuracy. Please adhere to standard coding practices and submit pull requests for any proposed changes.

## Future Work

The project aims for continuous improvement in classification accuracy and recall rates. Future updates may include integrating more diverse datasets, refining NLP preprocessing steps, and exploring additional machine learning algorithms for better performance.
