## 1. Which machine learning methods did you choose to apply in the application?
* Supervised Learning: Applied a Decision Tree Classifier to predict employee attrition.
* Unsupervised Learning: Used K-Means Clustering to segment employees into distinct clusters based on their features.

## 2. How accurate is your solution of prediction?
* The accuracy of the Decision Tree model was approximately 75.5%. However, the performance for predicting employee attrition (the minority class) was lower, particularly in terms of recall and precision.
  
## 3. Which are the most decisive factors for quitting a job?
* The most decisive factors for attrition included overtime, years at the company, monthly income, and work-life balance.

## 4. Which work positions and departments are at higher risk of losing employees?
* Roles in Sales and certain technical positions in Research & Development were observed to have a higher attrition rate based on the clustering and model insights.

## 5. Are employees of different gender paid equally in all departments?
* We analyzed the dataset to compare the Monthly Income across departments by gender to evaluate pay equality. However, this analysis wasn't explicitly part of the provided output.
  
## 6. Do family status and distance from work influence the work-life balance?
* Employees living further away from work and those with a single marital status were observed to have a slightly lower work-life balance, though this correlation needs further validation.

## 7. Does education make people happy (satisfied with their work)?
* Higher education levels showed a weak positive correlation with job satisfaction, but it was not the strongest predictor of job satisfaction.

## 8. Which were the challenges in the project development?
* Key challenges included handling class imbalance in attrition prediction, ensuring proper feature selection and encoding, and scaling for clustering. Additionally, interpreting the clusters meaningfully required careful analysis.
