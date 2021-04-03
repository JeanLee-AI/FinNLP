# FinNLP
Research sources for NLP in Finance

## stock market prediction 
### tasks related with text analysis
- Classification : stock market movement prediction (Accuracy : around 0.6) 
- Regression : make time series (Mean prediction accuracy 0.97-0.98)
- Multimodal : combination of time series and text analysis

### Papers (to be organised)
- [Stock Movement Prediction from Tweets and Historical Prices](https://www.aclweb.org/anthology/P18-1183.pdf){:target="_blank"} (ACL 2018)| [code](https://github.com/yumoxu/stocknet-code) (Python 2.7.11, Tensorflow 1.4.0) -  StockNet dataset (window 5)
- [Stock Embeddings Acquired from News Articles and Price History, and an Application to Portfolio Optimization](https://www.aclweb.org/anthology/2020.acl-main.307.pdf) (ACL 2020) - No code (aligned with ACL 2018, predict market, window 5)
- [DP-LSTM: Differential Privacy-inspired LSTM for Stock Prediction Using Financial News](https://arxiv.org/pdf/1912.10806.pdf) (NIPS 2019 Workshop AI in Financial Services) - [Code](https://github.com/AI4Finance-LLC/Financial-News-for-Stock-Prediction-using-DP-LSTM-NIPS-2019) (Python 3.6, Keras, Only using VADER -> able to upgrade, window size 10, the impact of text is very little)
- [Listening to Chaotic Whispers: A Deep Learning Framework for News-oriented Stock Trend Prediction](https://arxiv.org/pdf/1712.02136.pdf) (WSDM 2018) - No Code from authors (Good visualisation)
- [Deep Attentive Learning for Stock Movement Prediction From Social Media Text and Company Correlations](https://www.aclweb.org/anthology/2020.emnlp-main.676.pdf) (EMNLP 2020) - No code, GCN

- [Twitter mood predicts the stock market](https://arxiv.org/pdf/1010.3003.pdf) (2010)
- [Buzzwords build momentum: Global financial Twitter sentiment and the aggregate stock market](https://www.sciencedirect.com/science/article/pii/S0957417419304270) (Expert Systems with Applications 2019)

### Stock Recommendation System (Github  demo)
- [StockSight](https://github.com/shirosaidev/stocksight) (1.1k star) - TextBlob, Vader
- [BulBea](https://github.com/achillesrasquinha/bulbea) (1.4k star) - TextBlob
