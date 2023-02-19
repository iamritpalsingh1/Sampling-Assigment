## Sampling-Assigment

The focus of this project is to study how different sampling techniques can help create a balanced dataset that is suitable for a machine learning model. The starting dataset is imbalanced, so to address this, random over-sampling and under-sampling techniques are utilized to balance it out. Afterward, five different sampling techniques are applied to the balanced dataset, and the accuracy of each resulting sample is assessed using five distinct machine learning models.

## Result

Provided in the table below are the accuracy results for each sampling technique across five different machine learning models. It's important to note that the dataset employed for all models has been balanced using random over-sampling and under-sampling methods from the original unbalanced dataset.

| Sampling Technique | Decision Tree | SVM | Logistic Resgression | KNN | Naive Bayes |
|:---------------:|:---------------:|:---------------:|:---------------:|:---------------:|:---------------:|
| Simple Random Sampling | 0.9778 | 0.8954 | 0.8917 | 0.8915 | 0.7275 |
| Systematic Sampling | 0.9813 | 0.8989 | 0.9213 | 0.9493 | 0.6854 |
| Stratified Sampling | 0.9851 | 0.8937 | 0.9217 | 0.9498 | 0.6890 |
| Cluster Sampling | **0.9868** | 0.9000 | 0.9088 | 0.9691 | 0.9235 |

The results indicate that Cluster Sampling outperforms all other sampling techniques across all five machine learning models, while Simple Random Sampling yields the poorest results for all five models. The remaining sampling techniques exhibit varying levels of performance depending on the model. Notably, the Decision Tree model produces the highest accuracy across all five samples. Therefore, it can be concluded that Cluster Sampling is the most effective technique for the given balanced dataset and Decision Tree is the most suitable model for the classification task.
