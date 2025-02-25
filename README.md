# SENTIMENT-ANALYSIS

## COMPANY : CODTECH IT SOLUTIONS

## NAME: SRIRAM GOPALAN G

## INTERN ID: CT08QAH

## DOMAIN: DATA ANALYSIS

## DURATION: 4 WEEKS

## MENTOR: NEELA SANTHOSH

### DESCRIPTION:

This project involves performing sentiment analysis on the IMDb dataset. The primary goal is to build a machine learning model capable of classifying movie reviews into positive or negative sentiment categories. The process begins with loading and exploring the IMDb dataset, which consists of textual movie reviews labeled as either positive or negative.The initial step involves data preprocessing to prepare the textual reviews for analysis. This preprocessing includes converting all text to lowercase, thereby normalizing the data and reducing the vocabulary complexity. Additionally, stopwords—commonly used words in the English language that do not significantly contribute to the meaning or sentiment of sentences (such as "the," "is," "at")—are removed from the reviews. This step helps improve the accuracy and efficiency of the subsequent feature extraction and classification processes.Once preprocessing is complete, the textual data is transformed into numerical features that can be utilized by machine learning algorithms. This transformation is performed using the Term Frequency-Inverse Document Frequency (TF-IDF) vectorizer, a statistical measure that evaluates the importance of a word relative to the corpus of documents (in this case, reviews). The TF-IDF vectorizer generates a matrix where each row corresponds to a review and each column corresponds to a word, with cell values representing the significance of each word within the specific review. A limitation is set to use only the top 5000 most significant words to maintain computational efficiency.The resulting numerical feature matrix is then used as input for a supervised learning classification model. Specifically, the model employs the Multinomial Naive Bayes algorithm, a probabilistic classifier based on Bayes’ theorem and particularly effective for text classification tasks involving large vocabularies. The dataset is split into training and testing subsets to evaluate the model's performance. After training the model with the training subset, its predictive accuracy and effectiveness are assessed using metrics such as accuracy score, confusion matrix, and a detailed classification report containing precision, recall, and F1-score.The notebook integrates visual analytics as part of the evaluation process, using libraries such as Seaborn and Matplotlib. Visual representations such as heatmaps of confusion matrices help in understanding the performance and identifying potential areas for improvement in the classification model.Overall, this project illustrates a complete workflow for sentiment analysis, encompassing data cleaning, feature engineering, model training, evaluation, and visualization of results. Such sentiment analysis models have broad applicability, including analyzing user reviews, gauging public opinion, and enhancing recommendation systems. ​

### OUTPUT:
![{B4A7BFC8-0212-4A44-8844-E62A7D6DC0BE}](https://github.com/user-attachments/assets/98e0620f-31c1-4e89-86e0-53e481540415)
![{31C00C67-223E-4698-8AD9-611A21064602}](https://github.com/user-attachments/assets/cd711f51-048c-4164-9847-23d381417165)
![{4369B7A9-26FC-4930-8041-91D515B1E1E4}](https://github.com/user-attachments/assets/5672c186-01b3-406b-84ec-270787e6798d)
![{D6AB7539-0EFC-47F4-848D-BA6AC9AE0253}](https://github.com/user-attachments/assets/63100526-2fff-4ec6-9c45-7d6d50e89f54)

