# LLM based Finance Agent
An intelligent agent utilizing Large Language Models (LLMs) for automated financial news retrieval and stock price prediction.

## Introduction

LLM based Finance Agent is a powerful tool that leverages large language models (LLMs) to automatically fetch news and predict historical stock prices to forecast future prices. This repository is designed to provide financial insights using state-of-the-art natural language processing (NLP) and machine learning techniques.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/GURPREETKAURJETHRA/LLM-based-Finance-Agent.git
    ```
2. Navigate to the project directory:
    ```sh
    cd LLM-based-Finance-Agent
    ```
3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Configuration

Configure the agent by editing the `config.json` file with your API keys and desired settings:
```json
{
    "news_api_key": "your_news_api_key",
    "genai_api_key": "your_genai_api_key",
    "model_name": "gemini-1.5-pro",
    "stock_symbol": "2330.tw",
    "days": 30
}
```

- `news_api_key`: Your API key for the news data provider (Apply [here](https://newsapi.org/)).
- `genai_api_key`: Your API key for Google Generative AI (Apply [here](https://aistudio.google.com/app/u/1/apikey?hl=zh-tw)).
- `model_name`: The name of the Google Generative AI model to be used.
- `stock_symbol`: The stock symbol to analyze.
- `days`: The number of days to consider for the analysis.

## Usage

1. Ensure that you have configured the config.json file as described in the [Configuration](#configuration) section.

2. Run the project using the following command:
    ```python
    python main.py
    ```



---
## ©️ License 🪪 

Distributed under the MIT License. See `LICENSE` for more information.

---

#### **If you like this LLM Project do drop ⭐ to this repo**
#### Follow me on [![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gurpreetkaurjethra/) &nbsp; [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/GURPREETKAURJETHRA/)

---
