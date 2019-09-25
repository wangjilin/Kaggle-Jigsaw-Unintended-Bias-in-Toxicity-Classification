# Kaggle-Jigsaw-Unintended-Bias-in-Toxicity-Classification
Kaggle Compitition Jigsaw Unintended Bias in Toxicity Classification https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/overview

Hi,

In this project, we were challenged to build a model that recognizes toxicity and minimizes this type of unintended bias with respect to mentions of identities. We used a dataset labeled for identity mentions and optimizing a metric designed to measure unintended bias.

To solve this problem, I cleaned the text before training and used GLOVE and CRAWL two words embeddings. I built a LSTM type of RNN and also used transfer learning with a pretrained BERT model. Finally, bagging from these to models to predict and minimize unintended bias of the toxic texts.

