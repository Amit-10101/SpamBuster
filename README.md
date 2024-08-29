# SpamBuster

SpamBuster is an advanced Email/SMS Spam Classifier that leverages AI and Machine Learning to accurately detect and filter out spam messages. This project utilizes natural language processing (NLP) techniques and machine learning models to classify messages in real-time, ensuring robust protection against spam.
>Live Link: https://spambuster.streamlit.app/

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

Spam messages are a growing threat, causing significant harm to individuals and businesses. Traditional spam detection methods are no longer sufficient to combat the evolving tactics of spammers. SpamBuster addresses this issue by using state-of-the-art AI and machine learning techniques to provide a reliable and adaptive solution for spam detection.

## Features

- **Real-Time Detection**: Classify messages as spam or not spam in real-time.
- **Advanced NLP**: Utilizes natural language processing techniques for text preprocessing.
- **Machine Learning Models**: Employs pre-trained models for accurate spam detection.
- **User-Friendly Interface**: Built with Streamlit for easy interaction and message classification.
- **Scalable**: Powered by Azure ML Studio for scalable deployment and management.

## Installation

To install and run SpamBuster application, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/Amit-10101/SpamBuster.git
    cd SpamBuster
    ```

2. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

3. Download NLTK data:
    ```python
    import nltk
    nltk.download('stopwords')
    nltk.download('punkt_tab')
    ```

> For model training and building, refer to the jupyter notebook from the repository.

## Usage

To start the SpamBuster application, run the following command:
```sh
streamlit run app.py
```
This will launch the Streamlit interface where you can input messages and receive real-time spam classification results.

## Contributing
We welcome contributions to SpamBuster! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request. Make sure to follow the contribution guidelines.
