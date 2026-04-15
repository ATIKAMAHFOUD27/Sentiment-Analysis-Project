# Sentiment Analysis & Semantic Segmentation for E-Commerce
📌 Project Overview:
This project focuses on automating the understanding of customer feedback using Natural Language Processing (NLP). By analyzing over 23,000 authentic reviews from the "Womens Clothing E-Commerce Reviews" dataset , we transform unstructured text into actionable business insights.  🛠️ Tech StackLanguage: 
Python Libraries: Pandas, Scikit-learn, NLTK, Matplotlib, Seaborn Techniques: TF-IDF Vectorization, PCA (Dimensionality Reduction), NLP Preprocessing (Tokenization, Lemmatization)  
📊 Key Results:
1. Predictive Modeling (Supervised Learning)Algorithm: Multinomial Naive Bayes Accuracy: 86.44% Analysis: The model is extremely robust in identifying positive reviews with an F1-score of 0.92. However, it highlights a structural challenge with class imbalance, achieving a recall of 0.27 for negative feedback.  
2. Thematic Segmentation (Unsupervised Learning)Using K-Means Clustering and the Elbow Method ($K=3$) , I identified three major customer concern areas:Cluster 0 (Satisfaction & Aesthetics): Focused on positive visual feedback and global satisfaction.Cluster 1 (Fit & Size Issues): Technical feedback regarding sizing, dimensions, and comfort.Cluster 2 (Product Attributes): Descriptive reviews focused on specific product types like dresses or shirts.  
📈 Visualizations:
The project includes a semantic mapping of reviews using Principal Component Analysis (PCA) to validate the distinct structures of our customer segments in a 2D space.
