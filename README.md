# Fake-News-Detection
The growing dissemination of fake news poses a threat to public trust and informed decision-making. This project addresses the challenge by building a semantic classification model to distinguish between fake and true news articles. The primary goals are:
•	To identify recurring linguistic and semantic patterns in news texts.
•	To accurately classify news using supervised learning techniques.
•	To compare different models and choose the most effective one based on relevant evaluation metrics.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
The objective of this case study is to develop Semantic Classification model using Word2Vec method to extract the semantic relations from the text.Supervised models will be used categorise text based on its meaning, rather than just syntax. Textual meaning plays a critical role in making accurate and efficient decisions.

The target is to create a fake news detection system using semantic classification techniques. By leveraging the Word2Vec model and traditional supervised learning algorithms like Logistic Regression, Decision Tree, and Random Forest, the system aims to classify news articles as either true or fake based on their textual content. The analysis is supported by extensive data preprocessing, exploratory data analysis, and model evaluation to ensure reliability and performance.
## Conclusions
**Key Observations:**
•	True news articles tend to use formal, institutional language, while fake news often relies on emotionally charged, dramatic, or sensational wording.
•	N-gram analysis highlights that true news focuses on structured governance and policy related words, whereas fake news frequently includes visual and viral terms like "image" and "video."

**Best Model:**
•	Logistic Regression delivered the strongest performance, with high evaluation metrics making it useful for identification of true news articles.
•	It not only has balanced evaluation metrics but also is interpretable, allowing insights into which features influence predictions - a valuable trait in domains requiring transparency.
  
**Impact:**
•	The semantic classification approach, using Word2Vec embeddings and robust preprocessing, effectively captures linguistic patterns to distinguish fake from true news.
•	The solution is scalable and adaptable to other misinformation domains and suitable for integration into real-time platforms - helping to enhance public trust and reduce misinformation.

## Technologies Used
- Python - version 3.12.4
- Matplotlib - version 3.9.2
- Numpy -version 1.26.4
- Pandas - version 2.2.2
- Seaborn - version 0.13.2
- Nltk - version 3.9.1
- Spacy - version 3.7.5
- Wordcloud - version 1.9.4

## Acknowledgements
- Upgrad Tutorials on Semantic Processing.

## Contact
Created by [Priyanka Gulati](https://github.com/pgulati9)
