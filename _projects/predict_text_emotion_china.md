---
layout: page
title: "Develop a predictor for detecting sentiments toward China in online texts"
---

## Develop a predictor for detecting sentiments toward China in online texts

---

### Background
Understanding foreign public sentiment toward China is strategically important. Social media short texts offer real-time insights but pose challenges due to brevity, colloquial language, and cultural nuance. This study leverages large-scale pre-trained language models to predict and model overseas sentiments toward China, providing a robust tool for public opinion analysis and policy evaluation.

---

### Tasks
This study comprises two classification tasks:  
1. **Topic Classification of online texts from Platform X**  
2. **Sentiment Classification toward China in online texts from Platform X**  

Considering the inherent characteristics of the data and the complexity of the tasks, we have designed distinct technical implementation approaches for each task.

---

### Methods

#### Topic Classification Task
**Step 1:** Collect online text data.  
**Step 2:** Extract features from the collected texts and construct the text dataset.  
**Step 3:** Using the inherent topic labels of the data, train and fine-tune different pre-trained BERT models.  
**Step 4:** Conduct experiments on the validation set using **Accuracy** to compare models and select the best-performing one.  
**Step 5:** Evaluate the selected model comprehensively on the test set using **Accuracy**, **Precision**, **Recall**, and **F1-score**.

#### Sentiment Prediction Task Toward China
The sentiment prediction task involves processes such as text encoding, LLM-based data augmentation, and fine-tuning of different pre-trained BERT models, making it relatively complex. A simplified diagram is shown below:

<div align="center">
<img src="https://github.com/user-attachments/assets/1b2499a8-66b1-4bad-91e6-a7f336df8fcb" alt="predict_emotion_for_china" width="800"/>
</div>

---

### Results and Future Directions
After tuning, in the **topic classification task**, the optimal model was **BERTweet-base** with a learning rate of **5e-5**, achieving a test set accuracy of **0.936**.  
For the **China-sentiment prediction task**, the best model was **BERTweet-base** with a learning rate of **2e-5**, reaching a test set accuracy of **0.786**.

**Future directions:** For the online text China-sentiment classification task, improving the consistency of human annotations and enhancing the model’s performance in fine-grained category discrimination will enable more accurate and stable automated sentiment detection.







