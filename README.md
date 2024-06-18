# YouTube Comments Sentiment Analysis

## Introduction

This project demonstrates how to fetch comments from a YouTube video using the YouTube Data API, perform sentiment analysis on those comments, and visualize the sentiment distribution. The project utilizes Python libraries such as `googleapiclient`, `pandas`, and `TextBlob` for data processing and sentiment analysis, and `matplotlib` for visualization.

## Prerequisites

- Python 3.x
- YouTube Data API Key

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/youtube-comments-sentiment-analysis.git
    cd youtube-comments-sentiment-analysis
    ```

2. Install the required Python packages:

    ```bash
    pip install google-api-python-client pandas textblob matplotlib
    ```

3. Obtain a YouTube Data API key from the [Google Cloud Console](https://console.cloud.google.com/).

## Usage

1. Open the Jupyter Notebook (`YouTube_Comments_Sentiment_Analysis.ipynb`) in your preferred environment (e.g., Jupyter Notebook, JupyterLab).

2. Replace the placeholder `"YOUR_API_KEY"` with your actual YouTube Data API key.

3. Replace the placeholder `"xKVy4NgZF-w"` with the ID of the YouTube video you want to analyze.

4. Run the cells in the notebook sequentially to fetch comments, perform sentiment analysis, and visualize the results.

## Results

The notebook will output various visualizations, including:

- A pie chart showing the sentiment distribution (positive, neutral, negative) of the comments.
- Histograms showing the distribution of polarity and subjectivity scores.
- A scatter plot of polarity vs. subjectivity.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
