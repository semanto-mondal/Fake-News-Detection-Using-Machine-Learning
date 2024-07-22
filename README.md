# Fake-News-Detection-Using-Machine-Learning
# Fake News Detection: A Comparative Study of Machine Learning Techniques
The paper has also published in IEEE and can be accessed from the following link:
[PAPER LINK](https://ieeexplore.ieee.org/document/10450148)

![Flowchart (4)](https://github.com/user-attachments/assets/3022a7af-971e-4a95-a409-008416067847)


# PROBLEM STATEMENT: Fake News Detection
The spread of misinformation and fake news has become a significant challenge in today's digital age. The dissemination of false information can have severe consequences on individuals, communities, and society as a whole. Detecting and combating fake news is crucial for maintaining the integrity of information and ensuring informed decision-making. The objective of this project is to develop a model for fake news detection. The system aims to automatically classify news articles as either real or fake based on their content and linguistic features. By accurately identifying fake news, the system can assist users in making informed judgments and help prevent the further spread of false information. The project will involve collecting a diverse dataset of news articles, including both real and fake examples. Various natural language processing (NLP) techniques will be applied to preprocess and extract meaningful features from the text data. Overall, this project aims to contribute to the development of effective techniques and tools for fake news detection, ultimately fostering a more informed and trustworthy information ecosystem.

# Introduction
Due to the advancement of technology, we all have the flavor of ICT. ICT has made a new informational world or environment where all of us are connected via different digital means. This new environment is called the infosphere. Now we are just one click away from any information which is freely available on the internet. Now we are flooded with common knowledge and there is an abundant amount of news articles being published every day. When we open social media, we see different news. Not only these but also every day we receive hundreds of emails in our mailbox. But sometimes we can't believe different news or get confused by different articles as we don’t have surety about the authenticity of this news. The problem of fake news has become one of the most challenging issues having an impact on societies. Nowadays, false information may spread quickly through social media. In that regard, fake news needs to be detected as fast as possible to avoid negative influence on people who may rely on such information while making important decisions. Here fake news detection algorithms come into the picture. Our goal is to use different machine-learning algorithms to detect or classify a piece of news as fake or real. In recent years, different NLP (Natural Language Processing) methods have been proposed to solve the fake news detection problem. There are several algorithms such as LSTM, and the transformer-based model which use self-attention mechanisms to find semantic relationships or meanings of different words in any document. We can also use the power of LSA (Latent semantic analysis) to find latent features and to identify similarities and differences between genuine and fake news articles based on the language used in the text.

# Result & Conclusion
![image](https://github.com/user-attachments/assets/eab5569a-a7c3-4083-85d6-bed74835cc81)

According to the comparison table Support Vector Machine with RBF kernel outperforms all other models in terms of different metrics whereas random forest is also having almost similar types of performance with 100 estimators (individual trees). 

![image](https://github.com/user-attachments/assets/a7f04e90-29db-4323-9f63-1c137b34881c)

LSTM models process input sequentially which means word by word and one word at a time whereas Transformer architecture enables parallel computation, processing the entire input text simultaneously. This parallelism significantly speeds up computation, making it more efficient. For longer sequences of text, the transformer model gives better performance as it can hold long-term dependencies with the help of a self-attention mechanism. On the contrary, interpretable machine learning models are also performing better as the SVM model also gives an accuracy of 91% which is close to the performance of the LSTM model. The gist is for shorter sequences of text LSTM and interpretable machine learning models give outstanding performance whereas for longer sequences transformer-based network could be an ideal choice.




