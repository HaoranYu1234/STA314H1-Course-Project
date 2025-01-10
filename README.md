# Detection of YouTube Spam Comments

This project, **Detection of YouTube Spam Comments**, addresses the pervasive issue of spam in YouTube's comment sections. As one of the world's most popular video-sharing platforms, YouTube facilitates dynamic interactions between users through its comment section. However, this openness invites spam comments, which can degrade user experience, mislead viewers, and even expose users to harmful content.

Our team—**Marta Gonczar, Arnav Nambiar, Haoran (Alex) Yu, and Ian Zhang**—undertook this project to build a machine learning solution capable of identifying and mitigating spam comments. Competing under the Kaggle team, we developed a robust Random Forest-based classifier that achieved an impressive **accuracy of 96%** on validation data and ranked **15th** in the competition with private and public scores of **94.718%** and **94.059%**, respectively.

## Project Workflow

- **Data Processing**: The dataset comprises 1,369 labeled YouTube comments. We processed the data by removing irrelevant features, vectorizing text data using TF-IDF, and handling missing values to ensure clean input.
- **Feature Engineering**: We introduced additional features, such as the presence of URLs, emojis, punctuation patterns, and spam-related keywords, to enhance the model's predictive power.
- **Model Selection and Validation**: A Random Forest model was chosen for its interpretability and robustness. Various evaluation metrics, including precision, recall, and the AUC-ROC score, validated the model's effectiveness in distinguishing spam from non-spam comments.
- **Discussion and Future Work**: While the results are promising, we acknowledge limitations such as the dataset size and the evolving nature of spam techniques. Future iterations could benefit from larger datasets, more advanced models, and real-time detection capabilities.

## Highlights

- **Accuracy**: 96% on validation data
- **Kaggle Ranking**: 15th place
- **Public Score**: 94.059%
- **Private Score**: 94.718%

This repository serves as a comprehensive guide to our project, including the codebase, data processing pipeline, model training scripts, and performance evaluations. We hope it contributes to combating spam on digital platforms and inspires further advancements in automated spam detection.
