# Text Analysis

## Overview
This project performs sentiment analysis on a large dataset of tweets using text preprocessing and machine learning techniques. The dataset is processed to classify sentiments as positive or negative.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Preprocessing](#preprocessing)
- [Modeling](#modeling)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Installation
To run this project, you'll need to have Python installed along with the following libraries:
- `numpy`
- `pandas`
- `nltk`
- `matplotlib`
- `seaborn`
- `sklearn`
- `gensim`
- `wordcloud`

You can install the required libraries using pip


## Usage
Clone the repository:

git clone https://github.com/Lamar-yasir18/text-analysis.git
cd text-analysis

Run the script: Execute your Jupyter notebook or Python script that contains the analysis code.

## Data
The dataset used in this project is the Twitter Sentiment Analysis Dataset, which can be found here.

The dataset includes the following columns:
sentiment: The sentiment label (0 for negative, 4 for positive).
text: The tweet text.

## Preprocessing
The preprocessing steps include:

-Dropping unnecessary columns.

-Mapping sentiment labels to positive and negative.

-Removing duplicates.

-Shuffling and sampling the dataset for balanced classes.

-Lowercasing the text.

-Removing stop words, emails, URLs, punctuations, and numbers.

-Tokenization and lemmatization.

-Visualizing sentiment distribution using bar plots.

-Generating word clouds for positive and negative sentiments.

-Modeling

The project uses the following models:

Bag of Words (BOW):
-Initialized a CountVectorizer to convert text data into a matrix of token counts.
-Fit a Logistic Regression model and evaluated its accuracy.
TF-IDF:
-Used TfidfVectorizer for feature extraction.
-Fit another Logistic Regression model and evaluated its accuracy.

## Results
Accuracy using Bag of Words: 75.63%

Accuracy using TF-IDF: 76.04%

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For questions or feedback, please reach out to:

Lamar 
Deeema
Email: Lamar.28859@gmail.com
