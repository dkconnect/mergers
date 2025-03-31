# Sentiment Analysis Using Transformers

## Overview
This project utilizes **Hugging Face's Transformers** library to perform **sentiment analysis** on financial news headlines. The model predicts the sentiment of given text and provides a confidence score for its classification.

## Features
- Uses **Hugging Face Transformers** to analyze sentiment.
- Implements the **BERT-based multilingual sentiment model** (`nlptown/bert-base-multilingual-uncased-sentiment`).
- Processes a list of financial news headlines and classifies their sentiment.
- Outputs the predicted sentiment label and confidence score.

## Technologies Used
- **Python**
- **Hugging Face Transformers**

## Installation
### Prerequisites
Ensure you have Python (version 3.x) installed on your system.

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/sentiment-analysis.git
   ```
2. Navigate to the project directory:
   ```sh
   cd sentiment-analysis
   ```
3. Install the required dependencies:
   ```sh
   pip install transformers
   ```
4. Run the script:
   ```sh
   python sentiment_analysis.py
   ```

## Usage
- The script contains a predefined list of financial headlines.
- It processes each headline using the sentiment analysis model.
- The predicted label and confidence score are displayed in the console.

## Example Output
```
Headline 1: Predicted Label - 4 stars, Confidence Score - 0.85 - Microsoft-Activision deal back in hands of UK regulator after court pauses appeal
Headline 2: Predicted Label - 2 stars, Confidence Score - 0.76 - SBB, Brookfield end talks on EduCo stake sale, shares tumble
...
```

## Customization
- You can modify the `model_name` variable to use a different sentiment analysis model from Hugging Face.
- Update the `headlines` list with your own text inputs.

## License
MIT License © 2024 Your Name

