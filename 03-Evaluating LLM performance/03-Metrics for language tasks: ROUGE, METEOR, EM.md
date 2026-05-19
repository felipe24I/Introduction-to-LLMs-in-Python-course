## Metrics for language tasks: ROUGE, METEOR, EM
### Metrics for Summarization tasks

<img width="212" height="408" alt="image" src="https://github.com/user-attachments/assets/ff7758b2-40eb-49d0-8116-78ba2f7c93c9" />

### Metrics for Translation tasks

<img width="228" height="407" alt="image" src="https://github.com/user-attachments/assets/067233ae-3f04-4ea1-9c2c-08cf898d6fe1" />

### Metrics for Question - answering

<img width="255" height="415" alt="image" src="https://github.com/user-attachments/assets/211468d2-6890-4b78-bda7-07403ee91d64" />

### ROUGE
Similarity between generated a summary and reference summaries

* Looks at n-grams and overlapping
* **predictions:** LLM outputs
* **references:** human-provided summaries

<img width="886" height="280" alt="image" src="https://github.com/user-attachments/assets/ad52bb9a-c730-4f1a-9b20-228665b6b7f7" />

<img width="1206" height="231" alt="image" src="https://github.com/user-attachments/assets/1be83b16-cabd-4868-b302-515f42514a8e" />

#### ROUGE scores:
* **rouge1:** unigram overlap
* **rouge2:** bigram overlap
* **rougeL:** long overlapping subsequences

#### ROUGE outputs

<img width="593" height="368" alt="image" src="https://github.com/user-attachments/assets/bde4ed18-0f6b-4ecb-ae72-cd619bb36d58" />

* Scores between 0-1: higher score indicates higher similarity

### METEOR
* **METEOR:** more linguistic features like word variations, similar meanings, and word order

<img width="1207" height="440" alt="image" src="https://github.com/user-attachments/assets/29a6abb2-173b-489d-b998-3c6ba837a2d9" />

<img width="937" height="313" alt="image" src="https://github.com/user-attachments/assets/49dee973-8392-4da3-9ab3-ea28cc91d96e" />

* **0-1** METEOR score: higher is better

### Exact Match (EM)
* **Exact Match (EM):** 1 if an LLM's output exactly matches its reference answer

<img width="585" height="533" alt="image" src="https://github.com/user-attachments/assets/ca5c4108-14fc-4fd1-8c66-0f654195e20b" />

* Normally used in conjunction with **F1 score**
