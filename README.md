# Financial Headlines Sentiment Analysis
## Overview

This project leverages the News API to fetch financial stock headlines, analyzes the sentiment of these headlines using TextBlob, and provides insights into how sentiment might correlate with stock performance. The project includes a search feature to filter headlines based on specific stock symbols or keywords.
## Features

* Fetch financial headlines using the News API
* Perform sentiment analysis on headlines with TextBlob
* Search and filter headlines based on stock symbols or keywords
* Display sentiment analysis results and insights

## Prerequisites

* Python 3.7 or higher
* pip (Python package installer)
* An API key for the News API

## Installation

1. Clone the repository:

        git clone https://github.com/yourusername/sgfin_sentiment.git

2. Navigate to the project directory:

        cd sgfin_sentiment

3. Create a virtual environment (optional but recommended):

        python -m venv venv

4. Activate the virtual environment:

        Windows: venv\Scripts\activate

        MacOS/Linux: source venv/bin/activate

5. Install the required packages:

         pip install -r requirements.txt

7. Obtain a News API key:

* Sign up at News API and get your API key. 


## Results

* Sentiment Analysis Output: Display of sentiment scores for each headline, indicating positive, neutral, or negative sentiment.
* Filtered Headlines: Results based on search queries, providing insights into specific stock-related news.


## License

This project is licensed under the MIT License. See the LICENSE file for details.
## Acknowledgments

* News API for providing financial headlines.
* TextBlob for sentiment analysis.
* Requests for handling HTTP requests.
