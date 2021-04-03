# FinNLP
Research sources for NLP in Finance

## Stock market prediction 
### Tasks related with text analysis
- Classification : stock market movement prediction (Accuracy : around 0.6) 
- Regression : make time series (Mean prediction accuracy 0.97-0.98)
- Multimodal : combination of time series and text analysis

### Papers (to be organised)
#### Focus on modelling 
- [Stock Movement Prediction from Tweets and Historical Prices](https://www.aclweb.org/anthology/P18-1183.pdf)(ACL 2018)| [code](https://github.com/yumoxu/stocknet-code) (Python 2.7.11, Tensorflow 1.4.0) -  StockNet dataset (window 5)
- [Stock Embeddings Acquired from News Articles and Price History, and an Application to Portfolio Optimization](https://www.aclweb.org/anthology/2020.acl-main.307.pdf) (ACL 2020) - No code (aligned with ACL 2018, predict market, window 5)
- [DP-LSTM: Differential Privacy-inspired LSTM for Stock Prediction Using Financial News](https://arxiv.org/pdf/1912.10806.pdf) (NIPS 2019 Workshop AI in Financial Services) - [Code](https://github.com/AI4Finance-LLC/Financial-News-for-Stock-Prediction-using-DP-LSTM-NIPS-2019) (Python 3.6, Keras, Only using VADER -> able to upgrade, window size 10, the impact of text is very little)
- [Listening to Chaotic Whispers: A Deep Learning Framework for News-oriented Stock Trend Prediction](https://arxiv.org/pdf/1712.02136.pdf) (WSDM 2018) - No Code from authors (Good visualisation)
- [Deep Attentive Learning for Stock Movement Prediction From Social Media Text and Company Correlations](https://www.aclweb.org/anthology/2020.emnlp-main.676.pdf) (EMNLP 2020) - No code, GCN
- [Coupling Macro-Sector-Micro Financial Indicators for Learning Stock Representations with Less Uncertainty](https://www.aaai.org/AAAI21Papers/AAAI-7228.WangG.pdf) (AAAI 2021)
- [Applications of deep learning in stock market prediction: recent progress](https://arxiv.org/pdf/2003.01859v1.pdf) - (2020) well summarized | [review](https://paperswithcode.com/paper/applications-of-deep-learning-in-stock-market/review/)

#### Focus on social media text / sentiment analysis
- [Twitter mood predicts the stock market](https://arxiv.org/pdf/1010.3003.pdf) (2010)
- [Buzzwords build momentum: Global financial Twitter sentiment and the aggregate stock market](https://www.sciencedirect.com/science/article/pii/S0957417419304270) (Expert Systems with Applications 2019)
- [Beyond negative and positive: Exploring the effects of emotions in social media during the stock market crash](https://www.sciencedirect.com/science/article/abs/pii/S0306457319309057) (Information Processing and Management 2020)
- [Issues and Perspectives from 10,000 Annotated Financial Social Media Data](https://www.aclweb.org/anthology/2020.lrec-1.749/) (LREC 2020) - Fin-Some (per request)
- [NTUSD-Fin: A Market Sentiment Dictionary for Financial Social Media Data Applications](http://nlg.csie.ntu.edu.tw/~hhhuang/docs/fnp2018.pdf) (Proceedings of the 1st Financial Narrative Processing Workshop (FNP 2018))
- [Learning Stock Market Sentiment Lexicon and Sentiment-Oriented Word Vector from StockTwits] (https://www.aclweb.org/anthology/K17-1031/) (CoNLL 2017)
- [Financial Sentiment Analysis: An Investigation into Common Mistakes and Silver Bullets] (https://www.aclweb.org/anthology/2020.coling-main.85/) (ICCL 2020)

### Github  demos 
- [list-stock-prediction](https://github.com/topics/stock-prediction?l=python)
- [list-stock-price-prediction](https://github.com/topics/stock-price-prediction?o=desc&s=stars)
- [StockSight](https://github.com/shirosaidev/stocksight) (1.1k star) - TextBlob, Vader
- [BulBea](https://github.com/achillesrasquinha/bulbea) (1.4k star) - TextBlob
- [stock market prediction webapp](https://github.com/kaushikjadhav01/Stock-Market-Prediction-Web-App-using-Machine-Learning-And-Sentiment-Analysis) - most recent
- [stock recommend](https://github.com/alvarobartt/twitter-stock-recommendation) - Python >=2.7, TextBlob
- [Machine Learning Stocks in python](https://github.com/robertmartin8/MachineLearningStocks) - Good readme
- [CNN stock market pytorch](https://github.com/hardyqr/CNN-for-Stock-Market-Prediction-PyTorch) - outdated code, using tensorboard is good approach
- [stock-trading-bot](https://github.com/pskrunner14/trading-bot) - using deep reinforcement learning
- [stock market prediction using nlp](https://github.com/SATHVIKRAJU/Stock-Market-Prediction-using-Natural-Language-Processing) - simple MLs

### Github repositories 
- [Deep learning for finance](https://github.com/sangyx/deep-finance)

### Industy applications
- Qlib : An AI-oriented Quantitative Investment Platform - Microsoft - [Paper](https://arxiv.org/pdf/2009.11189v1.pdf)| [Github](https://github.com/microsoft/qlib) : check framework and infrastructure
- FinRL: A Deep Reinforcement Learning Library for Quantitative Finance - [Paper](https://arxiv.org/pdf/2011.09607.pdf) | [Github](https://github.com/AI4Finance-LLC/FinRL-Library)
- Microsoft (2017) - [blogpost](https://devblogs.microsoft.com/cse/2017/12/04/predicting-stock-performance-deep-learning/)
- Google patent - [webpage](https://patents.google.com/patent/US20030135445A1/en) | [patent](https://patentimages.storage.googleapis.com/df/93/5d/4cc361daa8ee8c/US20030135445A1.pdf) 
