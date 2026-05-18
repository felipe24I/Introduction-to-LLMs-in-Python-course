## Using pre-trained LLMs
LLMs can perform a variety of language tasks

**Language understanding tasks**

* Summarization
* text calssification
* Sentiment Analysis
* Question & Answer

**Language genertion tasks**

* Text Generation
* Translation

### Text generation
Text generation involves producing coherent, meaningful and human-like text

#### Text generation pipeline

<img width="1793" height="306" alt="image" src="https://github.com/user-attachments/assets/d8670299-3bd6-41af-853c-d22716a2117f" />

* **pad_token_id:** is a unique numerical identifier assigned to a special "padding" token in an LLM’s vocabulary. It acts as filler space so that shorter prompts in a batch can match the length of the longest prompt, forming a uniform rectangular matrix required for GPU processing
* **eos_token_id:** end-of-sequence token ID

<img width="1206" height="342" alt="image" src="https://github.com/user-attachments/assets/7aaeef71-2f9c-4068-875d-ef370ae1ab10" />

* **pad_token_id:** fills in extra space up to **max_length**
* **Padding:** adding tokens
* Setting to **generator.tokenizer.eos_token_id** marks the end of meaningful text, learned through training
* Model generates up to **max_length** or **pad_token_id**
* **truncation = True** This parameter can be added if the input is longer than the maximum lenght we have set

#### Example

<img width="1805" height="776" alt="image" src="https://github.com/user-attachments/assets/33a7d297-46ea-46de-aa2f-2dab45fcd9c6" />

#### Guiding the output

<img width="1806" height="802" alt="image" src="https://github.com/user-attachments/assets/4a965f12-8ac3-45e1-8e10-8c7befa239f9" />

* review and response into a single prompt, using a f string to guide the model
  
### Language translation
* Generate new text based on the input, we generate the text in other language while preserving the original meaning}
* Hugging Face has a complete list of translation tasks and models

#### Example: translation english to spanish

<img width="1802" height="582" alt="image" src="https://github.com/user-attachments/assets/538f2ed4-a314-4809-ade4-390abc41dff2" />
