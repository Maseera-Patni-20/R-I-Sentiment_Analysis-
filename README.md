# R-I-Sentiment_Analysis-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>YouTube Comments Sentiment Analysis</title>
</head>
<body>
    <h1>YouTube Comments Sentiment Analysis</h1>

    <h2>Introduction</h2>
    <p>This project demonstrates how to fetch comments from a YouTube video using the YouTube Data API, perform sentiment analysis on those comments, and visualize the sentiment distribution. The project utilizes Python libraries such as <code>googleapiclient</code>, <code>pandas</code>, and <code>TextBlob</code> for data processing and sentiment analysis, and <code>matplotlib</code> for visualization.</p>

    <h2>Prerequisites</h2>
    <ul>
        <li>Python 3.x</li>
        <li>YouTube Data API Key</li>
    </ul>

    <h2>Installation</h2>
    <ol>
        <li>Clone the repository:
            <pre><code>git clone https://github.com/yourusername/youtube-comments-sentiment-analysis.git
cd youtube-comments-sentiment-analysis
            </code></pre>
        </li>
        <li>Install the required Python packages:
            <pre><code>pip install google-api-python-client pandas textblob matplotlib
            </code></pre>
        </li>
        <li>Obtain a YouTube Data API key from the <a href="https://console.cloud.google.com/" target="_blank">Google Cloud Console</a>.</li>
    </ol>

    <h2>Usage</h2>
    <ol>
        <li>Open the Jupyter Notebook (<code>YouTube_Comments_Sentiment_Analysis.ipynb</code>) in your preferred environment (e.g., Jupyter Notebook, JupyterLab).</li>
        <li>Replace the placeholder <code>"YOUR_API_KEY"</code> with your actual YouTube Data API key.</li>
        <li>Replace the placeholder <code>"xKVy4NgZF-w"</code> with the ID of the YouTube video you want to analyze.</li>
        <li>Run the cells in the notebook sequentially to fetch comments, perform sentiment analysis, and visualize the results.</li>
    </ol>

    <h2>Results</h2>
    <p>The notebook will output various visualizations, including:</p>
    <ul>
        <li>A pie chart showing the sentiment distribution (positive, neutral, negative) of the comments.</li>
        <li>Histograms showing the distribution of polarity and subjectivity scores.</li>
        <li>A scatter plot of polarity vs. subjectivity.</li>
    </ul>

    <h2>License</h2>
    <p>This project is licensed under the MIT License. See the <code>LICENSE</code> file for details.</p>
</body>
</html>

