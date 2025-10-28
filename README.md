# Next-Word-Predictor
Next Word Predictor for Famous Quotes

Project Description:
The project involves building a next word predictor using LSTM (Long Short-Term Memory) neural networks, specifically trained on a dataset of famous quotes by well-known individuals. The quotes dataset includes a diverse collection of sayings from historical figures, authors, philosophers, scientists, and public personalities. This dataset is rich in language patterns, stylistic nuances, and context-specific word usage, making it ideal for training a language model. The model will be designed to predict the most likely next word in a given quote based on the preceding sequence of words. This capability will not only help in auto-completing quotes but also in enhancing text generation tasks where stylistic accuracy and context relevance are important.

Steps to Follow:
1. Import libraries 📚
2. Load data 🔃
3. Remove punctuations
4. Tokenize the data
5. Creating padded sequence
6. Splitting input sequences into X and y
7. Converting y (label) to one-hot encoded format
8. Model Building
9. Creating Sequential model
10. Model Compilation
11. Model Traning
12. Plotting the graph of Accuracy and Loss
13. Prediction

Conclusion:
The next word predictor using LSTM has been tested on five sentences, yielding 100% accuracy in three instances, while the predictions for the other two were less precise. This outcome demonstrates the model's capability in some scenarios, though further improvements are necessary to ensure more consistent performance across a wider range of sentence types.
