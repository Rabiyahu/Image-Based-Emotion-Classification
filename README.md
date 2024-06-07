# Image-Based-Emotion-Classification
In this project, we investigated the effectiveness of various deep learning models—MLP, CNN, VGG19, and Inception V3—in classifying emotions from images.  Our dataset, sourced from Kaggle, included 1200 images evenly distributed across six primary emotions: happiness, anger, fear, disgust, pain, and sadness. Despite initial challenges with the CNN model, which achieved an accuracy of 0.22 and improved slightly to 0.26 with data augmentation, it struggled to distinguish between similar emotions. The MLP model initially performed better with an accuracy of 0.32, but performance decreased to 0.29 and further to 0.25 with data augmentation and hyperparameter tuning, suggesting overfitting. The VGG19 model, after fine-tuning and optimizing dropout rates, achieved the highest accuracy of 0.55, demonstrating robustness in emotion recognition. However, data augmentation reduced its performance to 0.44. The Inception V3 model, after reducing complexity and increasing dropout rates, achieved the highest overall accuracy of 0.62, indicating it was the most effective in capturing the nuances of emotional expressions. Overall, the VGG19 and Inception V3 models showed significant promise, with Inception V3 emerging as the best-performing model for this emotion classification task.







