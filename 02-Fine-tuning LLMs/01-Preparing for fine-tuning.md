## Preparing for fine-tuning
### Pipelines
**Pipelines:** pipeline()

* Streamlines tasks
* Automatic model and tokenizer selection
* Limited control

<img width="392" height="377" alt="image" src="https://github.com/user-attachments/assets/77b21957-5d8c-4db5-9717-a4db1dea3c65" />

### Auto classes
**Auto classes (AutoModel class)**

* Customization
* Manual adjustments
* Supports fine-tuning

<img width="435" height="370" alt="image" src="https://github.com/user-attachments/assets/edc3efbc-b75f-47e8-b8ef-6f335307467c" />

### LLM lifecycle
 
<img width="1427" height="371" alt="image" src="https://github.com/user-attachments/assets/373d9356-d92b-4d8d-bdbc-69d0b3345cf2" />

**Pre-training**

* Broad data
* Learn general patterns

**Fine-tuning**

* Domain specific
* Specialized tasks

### Loading a dataset for fine-tuning

<img width="882" height="397" alt="image" src="https://github.com/user-attachments/assets/39efdf32-be22-4072-a6b0-6ca659eb6aa1" />

* **load_dataset():** loads a dataset from Hugging Face hub
* **imdb:** review classification

### Auto classes

<img width="1687" height="337" alt="image" src="https://github.com/user-attachments/assets/e1a8c1e5-2809-4461-b13a-aca0512c1fda" />

### Tokenization

<img width="1715" height="787" alt="image" src="https://github.com/user-attachments/assets/26e9834d-24fe-46c9-8e9a-45ecff446d10" />

### Tokenization output

<img width="1797" height="348" alt="image" src="https://github.com/user-attachments/assets/6301017a-66cd-432b-a82c-db9befdced11" />

### Tokenizing row by row

<img width="1792" height="653" alt="image" src="https://github.com/user-attachments/assets/2eee5bc3-0487-4d32-935f-7108e925cf02" />

### Subword tokenization
* Common in modern tokenizers
* Words split into meaningful sub-parts

#### Example

<img width="1748" height="308" alt="image" src="https://github.com/user-attachments/assets/37e5c8fd-3b7f-4b1c-a7d1-b7ac696c0406" />
