# AI NLP Projects 🤖

A collection of Natural Language Processing (NLP) projects
built with HuggingFace Transformers and Python.

## Projects

### 1. AI Text Summarizer
Summarizes any long text into a concise version.
- Model: `sshleifer/distilbart-cnn-12-6`
- Input: Long paragraph or article
- Output: Clean, concise summary

### 2. Sentiment Analyzer
Detects whether a given text is positive or negative.
- Model: `distilbert-base-uncased-finetuned-sst-2-english`
- Input: Any text
- Output: Sentiment label + confidence score

## Technologies Used
- Python
- HuggingFace Transformers (v4.41.0)
- Google Colab

## How to Run
1. Open any notebook in Google Colab
2. Run all cells in order
3. Enter your text when prompted
4. Get results instantly

### 3. NLP Multi-Tool App
One app that runs three AI models together on any text.
- Summarizes the text
- Detects sentiment with confidence score
- Extracts keywords

Models used:
- `sshleifer/distilbart-cnn-12-6` → Summarization
- `distilbert-base-uncased-finetuned-sst-2-english` → Sentiment
- `yanekyuk/bert-uncased-keyword-extractor` → Keywords


### 4. Fake News Detector
Detects whether a news article is real or fake.
- Model: `hamzab/roberta-fake-news-classification`
- Input: Any news article text
- Output: TRUE/FAKE verdict + confidence score

## Author
Archana B | [GitHub](https://github.com/archana-b15)
