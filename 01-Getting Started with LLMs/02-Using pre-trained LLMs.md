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
