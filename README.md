
# Reddit Stock Analysis

This project analyzes Reddit discussions to gain insights into stock market trends using machine learning and natural language processing.

## Features
- Scrapes data from Reddit using the `praw` library.
- Fetches stock price data using `yfinance`.
- Performs sentiment analysis with `textblob`.
- Implements machine learning models using `scikit-learn`.

## Requirements
Make sure you have the following installed on your system:
- Python 3.7 or above
- Jupyter Notebook

### Python Libraries
Install the required libraries by running:
```bash
pip install pandas praw yfinance textblob scikit-learn
```

## How to Run the Project
1. Clone this repository or download the notebook file.
2. Navigate to the directory containing the notebook.
3. Open the notebook with Jupyter:
    ```bash
    jupyter notebook Reddit\ Stock\ Analysis.ipynb
    ```
4. Execute the cells sequentially to analyze Reddit data and stock trends.

## Setup Instructions
1. **Reddit API Credentials**:
   - Obtain API credentials by creating an app on [Reddit's Developer Portal](https://www.reddit.com/prefs/apps).
   - Add your `client_id`, `client_secret`, and `user_agent` in the notebook where specified.

2. **Data Sources**:
   - Stock data is fetched using the `yfinance` library. Ensure internet access for data retrieval.

## Notes
- This notebook requires an active internet connection to fetch Reddit and stock data.
- Ensure that the required API credentials are correctly set up before running the notebook.

## License
This project is licensed under the MIT License.
