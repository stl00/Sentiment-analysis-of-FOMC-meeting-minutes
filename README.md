# Sentiment analysis of FOMC meeting minutes - A neural network approach

In this paper, we explore the application of Long Short-Term Memory (LSTM) networks for sentiment
analysis of documents published by the Federal Open Market Committee (FOMC). FOMC meeting
minutes play a crucial role in influencing economic assessments and beliefs about future policy, impacting
the global economy and financial markets. LSTM networks, with their ability to capture long-range
dependencies in sequential data, are well-suited for this task. We demonstrate the efficacy of LSTM
networks in sentiment analysis of FOMC meeting minutes. Furthermore, we attempt to extend the
model to predict financial market movements based on the sentiment analysis results.

File structure:

- `Paper.pdf` contains the model implementation details and the main result.
- `Sentiment Classification.ipynb` contains the LSTM calssification model.
- `Dataset Construction.ipynb` contains the code to construct the dictionary-method-based labels for FOMC sentences. Please refer to the paper for details.
- `Wordcloud.ipynb` is used to generate the wordcloud of most frequent words in the FOMC minutes.
- `Pred on S&P500/VIX.ipynb` are used to build prediction model of financial indicators based on the previous classfication result.
