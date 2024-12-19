# Problem Statement

In today's digital age, hate speech on online platforms is a growing concern that impacts individuals and communities globally. Social media platform like Twitter host billions of users who generate a vast amount of content daily. The business problem we are addressing is the need for an efficient, scalable, and accurate system to automatically detect and mitigate hate speech in user-generated content on Twitter platform Solution Description To address the problem of hate speech on Twitter platform, we propose developing a machine learning model that can automatically detect and categorize user-generated content into hate speech/offensive language and neutral content. The solution involves the following steps:

Data Collection: Gather a diverse and comprehensive dataset of user-generated content from Twitter platforms.

Data Labeling: Ensure accurate labeling of content into the categories of hate speech/offensive language, or neutral.

Model Training: Use the labeled dataset to train a robust machine learning model.

Evaluation: Test and validate the model to ensure high accuracy and reliability in detecting hate speech.

Deployment: Integrate the model into online platforms to assist in real-time content moderation.

Dataset Selected Davidson dataset has over 24,000 entries, covering a wide range of hate speech scenarios and user-generated content from Tweeter platform. Each tweet is labeled as hate speech, offensive language, or neutral content. Dataset Size:

Hate speech -20609

Non Hate speech- 4159

Origianl Dataset link : https://drive.google.com/drive/folders/1sCNO7onQ-kzQJUYitV-PtZzQtGrnD7jh?usp=sharing Data Preprocessing Data preprocessing is a process of preparing the raw data and making it suitable for a machine learning model. It is the first and crucial step while creating a machine learning model.

Recategorization: Labeled Hate speech and offensive language as 0, non-hate speech as 1

Handling abbreviations: Replaced with full forms

HTML entity decoding: Decoded HTML entities

Contraction expansion: Expanded contractions

Normalization: Applied normalization to the data

Preprocessed Dataset link : https://drive.google.com/drive/folders/1sCNO7onQ-kzQJUYitV-PtZzQtGrnD7jh?usp=sharing

Tokenization and Embedding

Tokenization : Word Tokenization

Word tokenization divides the text into individual words. In this tokenization technique, words are treated as the basic units of meaning.

Embedding technique : TF – IDF Encoding

TF-IDF is a numerical statistic that reflects the importance of a word in a document. The TF-IDF algorithm takes into account two main factors: the frequency of a word in a document (TF) and the frequency of the word across all documents in the corpus (IDF).

Modeling Implemented various Machine Learning models and Deep Learning models including:

Machine Learning Model:

Random Forest Model

Logistic Regression Model

Deep Learning Models:

Artificial Neural Network (ANN)

Convolutional Neural Networks (CNN)

Long short-term memory (LSTM)

Finalized Deep Learning Model :Artificial Neural Network (ANN)

Ability to learn complex patterns. Handle large-scale data effectively. Achieve state-of-the-art performance in various domains, and support end-to-end learning.

Evaluation Matrix Key Matrix for Evaluation: F1 Score The F1 score is the harmonic mean of precision and recall, providing a single metric to assess the balance between the two.

The individual implementations of the models can be found in separate branches of the repository. Each team member experimented with different approaches and models, and we decided to use the best methods from these individual efforts.
