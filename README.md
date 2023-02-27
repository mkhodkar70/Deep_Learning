Applications of Deep Neural Networks:

1) Churn Propensity (ChurnModeling): <br>
Propensity to churn modeling of the customers of a financial institutions, using their properties such as age, 
geography, gender, credit score and balance. <br>
Key tools: Artificial Neural Networks, weighting imbalanced classes <br>
Libraries: tensorflow, keras, scikit-learn, seaborn, matplotlib, numpy, pandas


2) Image Classification (FruitClassifier): <br>
Leveraging CNNs with ResNet50V2 being set as the backbone of the neural network, to distinguish 131 different fruits 
from each other. <br>
Key tools: Convolutional Neural Networks, Transfer Learning (ResNet) <br>
Libraries: tensorflow, keras, pathlib, scikit-learn, matplotlib, numpy, pandas

3) Pneumonia Detection (Pneumonia Detection): <br>
Employing a dataset of ~ 6,000 chest X-rays, to develop a CNN model built on top of a ResNet50V2 neural network, capable
of identifying healthy (normal) X-rays from those affected by pneumonia. <br>
Key tools: Convolutional Neural Networks, Transfer Learning (ResNet), weighting imbalanced classes <br>
Libraries: tensorflow, keras, pathlib, scikit-learn, matplotlib, numpy, pandas

4) Sentiment Analysis (MovieReviews_NLP_LSTM): <br>
Deploying various architectures of recurrent neural networks along with NLP tools to classify movie reviews into 
positive and negative, using a dataset of 50,000 reviews. <br>
Key tools: Natural Language Processing (Text Vectorization), Simple RNN, (Bidirectional) RNN/LSTM, (Bidirectional) RNN/GRU <br>
Libraries: tensorflow, keras, numpy, pandas

5) Facial Expression Recognition (FacialExpressionRecognizer): <br>
Detecting seven different types of human feelings (happiness, disgust, sadness, etc.) from an imbalanced dataset of
35,000+ facial expressions, by adopting an EfficientNetB2-based convolutional neural network. <br>
Key tools: Convolutional Neural Networks, Transfer Learning (EfficientNet), weighting imbalanced classes <br>
Libraries: tensorflow, keras, pathlib, scikit-learn, matplotlib, numpy, pandas

6) Stock Moreket Forecasting (StockMarketLSTM): <br>
Time-series prediction of Google's stock price using Yahoo finance data from 2018 to 2022. The data for the second 
half of 2022 was leveraged for testing the neural-network-based model, while the remainder was used for building
it. <br>
Key tools: RNN/LSTM, Time-Series Analysis <br>
Libraries: tensorflow, keras, yfinance, sklearn, numpy, pandas
