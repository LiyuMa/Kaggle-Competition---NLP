This project is a Kaggle Competition: Natural Language Processing with Disaster Tweets
This project can be divided into four parts:

part 1: Exploratory data analysis
part 2: Data preprocessing
part 3: Feature Selection
Part 4: Model training and testing

Achievements
Before starting on my project, I studied a kaggle competitor's work because I think he did an excellent work in data preprocessing and most of data preprocessing in my project are from his work. However, this project is not a duplicate of his. Here are something that can differetiate my work from his:
1. Before data preprocessing, inconsistent records (the same Xs with different y labels) are deleted from  
training data and duplicating  records are deduplicated.
2.  Among all of techniques of data preprocessing, a different feature extraction method (TFDIF) is used to generate features
3. Pincipal Component Analysis, GridSearchCV are used to find the optimal model performance
4. Two feature selection methods were applied to improve SVC model performance

Future Improvement
1. dimension reduction - backward elimination or forward selection or t-SNE can be tried
2. Feature engineering - N-grams can be tried
3. Other model: Deep learning models can be tried
