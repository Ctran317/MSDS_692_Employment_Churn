# MSDS_692_Employment_Churn
Project Description:

I identified the problem as big and small businesses having a labor shortage. I questioned what factors correlate to employee churn? The big picture or long time goal is to determine how we could use the data collected and analyzed to improve employee retention.

The dataset I used came from Kaggle and it consisted of 15,000 employees. The dataset had each employee's last evaluation score, satisfaction level, average monthly hours, and workload.

In the first part of the project I used four supervised learning classification algorithms including gradient boosting, logistic regression (L1 and L2), and random forest. 

Since the dataset is imblanced, I used AUROC as the chief evaluation metric. Accuracy measurements suggested random forests as being the winning model. However, the gradient boosting model had the highest AUROC score. 

In result, based ont the gradient boosting model, the strongest predictors to employment churn incldue satisfaction level, number of projects, tenure, and average monthly hours. I also engineered features 'overachievers' and 'overwoked' for indivuals who are highly satisfied and work multiple hours as well as the disatisfied and working too many hours. 
In the future, I would like to look into small businesses' data because the practice or culture differ, perhaps resulting in different predictors.

In the second part of the project, I analyzed subreddit 'antiwork' to determine how people felt before or when they contemplated on quitting their job. This particular subreddit has over 1.7 million subscribers who feel inclined to quit working and want more information or to share their thoughts.

I performed unsupervised machine learning with LInear Discriminant Analysis (LDA). LDA is a classification algorithm that analyzes unstructured text data. It counts words and groups similar word patterns to infer topics within usnrctured data.

Some challenges I ran into include having errors while loading the pyLDA package. When I load certain chunks of code below, the content runs fine. Another challenge involved sentiment analysis where the context of some words does not seem positive to me yet the model suugests they are positive. Overall, I would like to continue working with NLP and investigate employee churn in small businesses or other countries (i.e., culture and practices may differ.
