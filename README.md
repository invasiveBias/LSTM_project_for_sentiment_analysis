# LSTM_project_for_financial_news_sentiment
This is a project to develop a Long-Short Term Memory Model to track sentiment(positive,negative and neutral) from financial news data. The model runs the data through an embeddimg layer,which goes through two LSTM layers before feeding the output through a linear layer.
The project is split into Data analysis, pre_processing, model training & evaluation.
The model was developed with the Keras library & notable sub-modules are Sequential,Layers and Callbacks, libraries used for Data analysis & feature engineering include, Pandas,seaborn,re,Keras.preprocessing & sklean.model_selection(for train_test_split).
The training dataset (lstm_main) was a combination of smaller locally sourced datasets while the validation dataset(lstm_sub) was sourced from kaggle.
The project was ran on a local CPU machine, GPU/TPU power machines are recommended for faster trainning time.
