# Twitter Sentiment Analysis WebApp

The objective of this Project is to detect hate speech in tweets. For the sake of simplicity, we say a tweet contains hate speech if it has a racist or sexist sentiment associated with it. So, the task is to classify racist or sexist tweets from other tweets.

![GitHub stars](https://img.shields.io/github/stars/Ahmad10Raza/Twitter-Sentiment-Analysis-WebApp?style=social)		![GitHub forks](https://img.shields.io/github/forks/Ahmad10Raza/Twitter-Sentiment-Analysis-WebApp?style=social) 	![GitHub issues](https://img.shields.io/github/issues/Ahmad10Raza/Twitter-Sentiment-Analysis-WebApp)	![GitHub license](https://img.shields.io/github/license/Ahmad10Raza/Twitter-Sentiment-Analysis-WebApp)

A web application for performing sentiment analysis on Twitter data. This project uses Python, Tweepy, and a sentiment analysis model to analyze tweets and determine their sentiment.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Twitter Integration**: Connects to the Twitter API to fetch real-time tweets.
- **Sentiment Analysis**: Utilizes a sentiment analysis model to determine the sentiment of each tweet.
- **Web Interface**: Provides a user-friendly web interface for interacting with the application.
- **Customization**: Easily configurable for different analysis parameters.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Ahmad10Raza/Twitter-Sentiment-Analysis-WebApp.git
   cd Twitter-Sentiment-Analysis-WebApp
   ```
2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Configure your Twitter API keys as mentioned in the [Configuration](#configuration) section.

## Usage

1. Run the web application:

   ```bash
   python app.py
   ```
2. Open your web browser and navigate to `http://localhost:5000` to access the web interface.
3. Enter the required search parameters and analyze Twitter sentiments.

## Configuration

Before running the application, you need to configure your Twitter API keys. Edit the `config.py` file and replace the placeholders with your API keys:

```python
# config.py

API_KEY = 'your_twitter_api_key'
API_KEY_SECRET = 'your_twitter_api_key_secret'
```

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the [MIT License](https://chat.openai.com/c/LICENSE).
