# Sentiment Analyser
This repository contains the work to perform sentiment analysis on user app rating and produce a valid JSON structure for downstream processing.

### Pre-requisites
- Python 3 installed on your machine.
- OPENAI API Key

### Installation
1. `python -m venv .venv`
2. `source .venv/bin/activate`
3. `pip install -r requirements.txt`
4. `cp .env-example .env` and add your OPENAI API Key
5. Open `output-parser.ipynb`
6. Look for `customer_review` variable and add the text