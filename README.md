# Text Analytics App

Welcome to the Text Analytics App! This application allows you to perform comprehensive text analysis on text data from CSV or plain text files. The app provides sentiment analysis using the VADER library, as well as various visualizations and data insights.

## Features

- **File Upload**: Upload a CSV file or plain text file containing the text data you want to analyze.
- **Sentiment Analysis**: Perform sentiment analysis using the VADER library to get negative, neutral, and positive sentiment scores.
- **Word Clouds**: Generate and display word clouds for positive and negative sentiment words in the text.
- **Word Frequencies Table**: Display a table showing the frequencies of words in the text along with their sentiment scores.
- **Sentiment Histogram**: View a histogram showing the distribution of sentiment scores in the text.

## Installation

1. **Clone the repository**:

    ```shell
    git clone https://github.com/skappal7/TextAnalytics.git
    ```

2. **Navigate to the project directory**:

    ```shell
    cd TextAnalytics
    ```

3. **Create a virtual environment (optional but recommended)**:

    ```shell
    python3 -m venv venv
    source venv/bin/activate
    ```

4. **Install the required packages**:

    ```shell
    pip install -r requirements.txt
    ```

## Usage

1. **Run the app**:

    ```shell
    streamlit run app.py
    ```

2. **Upload a CSV or text file**:
    - In the app, use the file uploader to select and upload your CSV or plain text file containing the text data.
    - If you upload a CSV file, you will be prompted to select the text column you want to analyze.

3. **View the analysis**:
    - The app will perform sentiment analysis on the text and display the results in various visualizations such as bar graphs, word clouds, and histograms.
    - You can also view a table with word frequencies and sentiment scores.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute the code as per the license terms.

## Acknowledgements

- The app uses the [Streamlit](https://streamlit.io/) library for creating the interactive web application.
- Sentiment analysis is powered by the [VADER](https://github.com/cjhutto/vaderSentiment) library.
- Word cloud generation is handled by the [WordCloud](https://github.com/amueller/word_cloud) library.

