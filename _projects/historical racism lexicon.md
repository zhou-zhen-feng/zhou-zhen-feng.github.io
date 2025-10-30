---
layout: page
title: "Developed a historical racism lexicon from 60 million U.S. newspaper texts"
---

### The main steps

**Step 1: Obtain the seed words.**  
We collect the target words from prior research on racial stereotypes and racism. We asked external judges to evaluate and validate the semantic relevance of these words to the corresponding racial rhetoric (i.e., expressions of racial superiority or inferiority). After the evaluation, we obtained two validated word lists, consisting of 32 inferiority words and 22 superiority words, respectively. We refer to these validated words as our seed words.

**Step 2: Expand the seed word lists.**  
We obtained more than 60 million newspaper articles from the Chronicling America dataset, covering the period 1800–1910. Based on these texts, we trained a word embedding model. For each seed word, we identified the 20 words/bigrams that are most semantically similar to it in the embedding space.

**Step 3: External judges inspected the expanded seed word lists.**  
We asked the external judges to evaluate whether words in the expanded lists expressed racial superiority or inferiority. Based on the aggregated judgments, we classified the expanded words into superiority and inferiority categories. Thereafter, we obtained a racism lexicon consisting of 295 superiority words and 118 inferiority words.

**Step 4: Identifying the superiority and inferiority words most closely associated with Black and white groups.**  
According to historical scholarship, we divide 1800–1920 into four distinct periods and train separate word embedding models for each period. Based on the total weighted cosine similarity scores, we selected the top 20 superiority and inferiority words most closely associated with the Black/white groups in each period, see Table B3 of Appendix B4. Finally, we merged the results across all periods to construct the sets of white superiority, white inferiority, Black superiority, and Black inferiority keywords used in our analysis, see Table B4 of Appendix B4.

---

**For full details, please refer to Appendix B of my working paper:**  
https://zhou-zhen-feng.github.io/assets/pdf/resume.pdf

<img width="281" height="469" alt="image" src="https://github.com/user-attachments/assets/fb05f60b-8858-428a-93a0-e8c127a31d65" />



