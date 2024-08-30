## Esther
Good afternoon, everyone. This is SOS Pi Group 4. Today, we will be presenting our findings on breast cancer prediction using Fine Needle Aspiration (FNA) of breast masses.
Let’s start with the basics. Breast masses are evaluated through FNA, which allows us to collect cells for analysis. These cells serve as the tiny building blocks of our understanding, particularly focusing on their nuclei. In our study, we categorized the diagnosis into two groups: malignant, denoted as 'M', and benign, represented as 'B'.
---

## Vincent
Next, we examined the real-valued features of the nucleus that contribute to our predictive model. These features include radius, texture, perimeter, area, smoothness, compactness, concave points, symmetry, and fractal dimension. Each of these characteristics plays a crucial role in distinguishing between malignant and benign cases.

Moving on to our dataset description, we analyzed a total of 33 columns, which included 10 features for each case. We performed data cleaning to ensure accuracy in our analysis. This involved checking for missing values, converting the diagnosis column into a binary format, and identifying any duplicate rows.
To understand the relationship between diagnosis and the various features, we conducted a correlation analysis. This analysis revealed how each feature, such as radius and texture, correlates with the likelihood of malignancy.

Now, let’s discuss the training models we employed. We tested several algorithms, and our results showed that Logistic Regression achieved an impressive accuracy of 97%. Other models, including Support Vector Machine, Gradient Boosting Classifier, and Artificial Neural Networks, also performed well, each with accuracies around 96%.

Specifically, we examined the nuclear features associated with benign and malignant cases. For benign cases, the worst radius was 13.38, while for malignant cases, it was significantly higher at 21.135. This stark difference underscores the importance of these features in our predictive analysis.
---
## Nicholas
Finally, We would like to acknowledge our team, the SOS Pi Group 4, and especially our head tutor, Mavis, for her guidance throughout this project.
Thank you for your attention. We look forward to any questions you may have.