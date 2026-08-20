[Stock Market Prediction with Future News](https://github.com/ertali/340project)
- Extracted text from 10 years of NYT front-page PDFs using PyTesseract OCR and generated embeddings via Nomic/Ollama.
- Engineered features with RoBERTa to quantify article agreement with stock market–related statements.
- Merged news embeddings with historical AlphaVantage stock data to model prior-day market movement using TensorFlow/Keras dense-dropout networks.
- Evaluated predictive performance across multiple datasets (full pages, individual articles, similarity metrics)