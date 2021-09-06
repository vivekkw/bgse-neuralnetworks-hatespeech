# Hate Speech Detection on Twitter using RNNs
By Alexandro Pappas, I Vivek Kai-wen and Yabra Muvdi

Using two publicly available datasets, we attempt to use RNNs to predict the presence of hate speech in tweets. The tweets had been pre-screened and only tweets that contained hate speech-related words were included in the dataset. Amazon Turk was used to get labels on the dataset, which we codified as 1 for hate speech and 0 for non-hate speech. In this notebook, we present our attempts in using several different embeddings and models.

After selecting the best architecture, we perform a PCA in order to visualize how well the neural networks discriminates between various types of words in a two dimension plot. 
