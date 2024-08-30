## Esther
Good afternoon, everyone. This is SOS Pi Group 4. Today, we will be presenting our findings on breast cancer prediction using Fine Needle Aspiration (FNA) of breast masses. Let’s start with the basics. [2] Breast masses are evaluated through FNA, which allows us to collect cells for analysis. [3] These cells serve as the tiny building blocks of our understanding, [4] particularly focusing on their nuclei. [5] In our study, we categorized the diagnosis into two groups: malignant, denoted as 'M,' and benign, represented as 'B'.

## Vincent
[6] Next, we examined the real-valued features of the nucleus that contribute to our predictive model. These features include radius, texture, perimeter, area, smoothness, compactness, concave points, symmetry, and fractal dimension. Each of these characteristics plays a crucial role in distinguishing between malignant and benign cases.

[7] Moving on to our dataset description, we analyzed a total of 33 columns, which included 10 features for each case. [8] We performed data cleaning to ensure accuracy in our analysis. This involved checking for missing values, converting the diagnosis column into a binary format, and identifying any duplicate rows. [9] To understand the relationship between diagnosis and the various features, we conducted a correlation analysis. This analysis revealed how each feature, such as radius and texture, correlates with the likelihood of malignancy.

[10] Now, let’s discuss the training models we employed. We tested several algorithms, and our results showed that Logistic Regression achieved an impressive accuracy of 97%. Other models, including Support Vector Machine, Gradient Boosting Classifier, and Artificial Neural Networks, also performed well, each with accuracies around 96%.

[11] Specifically, we examined the nuclear features associated with benign and malignant cases. For benign cases, the worst concave points were 0.182, the worst area was 1422.286, and the mean smoothness was 0.103. The mean texture was 21.605, with a radius standard error of 0.609 and a symmetry standard error of 0.02. For malignant cases, the worst concave points were 0.074, the worst area was 558.899, and the mean smoothness was 0.092. The mean texture was 17.915, with a radius standard error of 0.284 and a symmetry standard error of 0.021. These differences highlight the importance of these features in our predictive analysis.

[12]Recommendations: Based on our findings, we recommend implementing the Logistic Regression model due to its high accuracy and ease of interpretation. The firm should also focus on the key nuclear features we identified, such as concave points and area, in their diagnostic processes. Additionally, automating data processing and integrating these predictive tools into existing systems will streamline workflows and improve diagnostic accuracy.

## Nicholas
Finally, I would like to acknowledge our the great team behind this project, the SOS Pi Group 4, and especially our head tutor, Mavis, for her guidance throughout this project.

Thank you for your attention. We look forward to any questions you may have.