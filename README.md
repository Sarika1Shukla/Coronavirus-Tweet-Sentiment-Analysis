# Coronavirus-Tweet-Sentiment-Analysis
The project task involves constructing a classification model to determine the sentiment of corona virus tweets. The dataset comprises tweets gathered from Twitter, which have undergone manual tagging for sentiment analysis. 

# Problem Statement
The project entails the development of a classification model aimed at predicting the sentiment expressed in COVID-19-related tweets. The dataset comprises tweets sourced from Twitter, which have undergone manual sentiment tagging. To ensure privacy protection, both names and usernames have been anonymized through encoding.

The primary objective is to leverage machine learning techniques to accurately classify the sentiment conveyed in COVID-19 tweets. By building and deploying a robust classification model, we aim to gain insights into public sentiment surrounding the pandemic, enabling organizations to better understand public perception, sentiment trends, and potential areas of concern or positivity. Through this analysis, we seek to contribute to a deeper understanding of the public discourse surrounding COVID-19 on social media platforms.

# Dataset Information 
The dataset given contains coronavirus tweet information. We need to analyze the important factors in the dataset for tweet sentiment analysis.

The dataset has 41157 rows and 6 columns. The dataset contains 8590 missing/null values and 0 duplicate values. The null values are in column 'Location'. Using seaborn library, we have visualized the following missing/null values.

# Data Visualization
The researcher utilized data visualization techniques employing libraries such as seaborn and matplotlib. Various types of graphs, including bar graphs, count plots, line charts, box plots, histogram plots, correlation heatmaps, and pair plots, were employed. These visualizations played a crucial role in simplifying complex data and enhancing its interpretability.

# ML Model Implementation
The researcher explored five machine learning models, including Logistic Regression, Naive Bayes Classifier, Random Forest, KNN(K-Nearest Neighbors), and Decision Tree. 'Logistic Regression' is statistical method for binary classification tasks, 'Naive Bayes Classifier' is a probabilistic classifier based on Bayes' theorem, 'Random Forest' is an ensemble learning method using multiple decision trees, 'KNN (K-Nearest Neighbors)' is a non-parametric classification algorithm and 'Decision Tree' is a tree-like structure used for classification and regression tasks. Despite employing grid search cross-validation to optimize these models, we observed minimal improvements in test accuracy across all models.

The accuracy score and classification report are crucial metrics influencing analysis. They offer insights into a model's performance and its ability to correctly classify instances, aiding in real-world applications. 

# Conclusion
The primary objective is to leverage machine learning techniques to accurately classify the sentiment conveyed in COVID-19 tweets. We focused our analysis solely on the "OriginalTweet" and "Sentiment" columns, as columns like "UserName" and "ScreenName" do not provide meaningful insights for our analysis. These two columns contain the primary data we need to analyze sentiments expressed in the tweets, thereby streamlining our data processing and analysis pipeline. We used stemming and lemmatizing for text normalization. In our analysis of COVID-19 tweets, we explored five machine learning models, including Logistic Regression, Naive Bayes Classifier, Random Forest, KNN, and Decision Tree. Despite implementing grid search cross-validation to optimize the models, we did not observe significant improvements in the test accuracy across all models.

However, the Logistic Regression model with Grid Search CV and count vectorization stood out, achieving an accuracy of 79.51%. This model demonstrated robust performance without signs of overfitting, indicating its suitability for deployment.

Our analysis revealed that despite the challenging circumstances of the COVID-19 pandemic, positive sentiments outweighed negative ones in the tweets. Nonetheless, a substantial portion of negative sentiments persists, presenting opportunities for government agencies, NGOs, and other entities to implement initiatives aimed at boosting public morale and addressing concerns.

Looking ahead, repeating the analysis in the future and comparing it with the present sentiment analysis could provide valuable insights into the effectiveness of such initiatives over time. This iterative approach allows for ongoing assessment and adjustment of strategies to better address evolving sentiments and needs during unprecedented situations like the COVID-19 pandemic.

