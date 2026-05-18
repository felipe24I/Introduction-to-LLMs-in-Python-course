## Understanding the transformer
Transformers are deep learning architectures that processing, understanding, and generating text, used in most LLMs because it can handle long text sequences in parallel

### Three common architectures

<img width="582" height="302" alt="image" src="https://github.com/user-attachments/assets/54255e40-1c9f-4196-80b5-067edf2a07ce" />

### Encoder-only

<img width="377" height="565" alt="image" src="https://github.com/user-attachments/assets/4aaa714e-0136-4762-a1dd-34f9b737290f" />

Focuses on encoding and understanding the input text without producing a sequential output

**Common tasks:**

* Text classification
* Sentiment analysis
* Extractive question-answering (extract or label)
* BERT-based models tend to use this structure

**Identify the architecture in python**

<img width="551" height="498" alt="image" src="https://github.com/user-attachments/assets/574d73e0-8c43-46a4-b725-178801911c27" />

<img width="553" height="260" alt="image" src="https://github.com/user-attachments/assets/1ff3e109-d3c5-4963-9ec5-b6bb31d3b2b1" />

### Decoder-only

<img width="368" height="561" alt="image" src="https://github.com/user-attachments/assets/07a65f6f-b893-4c7f-8fa2-2da88000ee92" />

Focus shifts to output

**Common tasks:**

* Text generation
* Generative question-answering (sentence(s) or paragraph(s))
* GPT models tend to use this architecture

<img width="550" height="367" alt="image" src="https://github.com/user-attachments/assets/b54f97c0-e4a1-4ecf-b853-a1bec7c052ba" />

### Encoder-deecoder

<img width="491" height="557" alt="image" src="https://github.com/user-attachments/assets/e718854e-8016-43c8-9819-393f4df0d6a9" />

Understand and process the input and output

**Common tasks:**

* Translation
* Summarization
* This is tipically found in T5 and BART models
  
<img width="550" height="328" alt="image" src="https://github.com/user-attachments/assets/46fe071d-798b-4145-b7ce-349eec9e2794" />

<img width="552" height="502" alt="image" src="https://github.com/user-attachments/assets/3951dcfb-b12a-4b00-998a-5dc5bf3e75d3" />
