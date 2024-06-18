# YouTube Comments Sentiment Analysis

## Introduction

This project demonstrates how to fetch comments from a YouTube video using the YouTube Data API, perform sentiment analysis on those comments, and visualize the sentiment distribution. The project utilizes Python libraries such as `googleapiclient`, `pandas`, and `TextBlob` for data processing and sentiment analysis, and `matplotlib` for visualization.

## Background

The background of the Israel-Iran conflict is complex and rooted in geopolitical, historical, and ideological differences. Initially, Israel and Iran had good relations, sharing common concerns over Arab powers. However, this changed drastically after the Iranian Revolution in 1979. Since then, Iran has supported groups like Hezbollah in Lebanon and Hamas in Palestine, which oppose Israel. On the other hand, Israel supports rebels in Iran and attacks Iran’s allies in Syria.

Iran supports Palestinian groups because it views them as oppressed and seeks to maintain influence in the region. Additionally, Iran advocates for a one-state solution, aiming to replace Israel with a single state. Conversely, Israel perceives Iran as a significant threat, particularly over concerns about Iran obtaining nuclear weapons. To counteract this, Israel has engaged in military strikes and supported sanctions against Iran, escalating tensions.

In recent events, on April 1, 2024, Israel bombed an Iranian target in Damascus, Syria, injuring multiple officials. In response, Iran and its proxies seized the Israeli-linked ship MSC Aries and struck Israel on April 13, 2024. Subsequently, Israel conducted retaliatory strikes in Iran and Syria on April 19, 2024, further intensifying the conflict.

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
