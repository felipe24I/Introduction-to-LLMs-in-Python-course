## Safeguarding LLMs
### LLM challenges
* **Multi-language support:** language diversity, resource availability, adaptability
* **Open vs closed LLMs dilemma:** collaboration vs responsible use
* **Model scalability:** representation capabilities, computational demand, training requirements
* **Biases:** biased training data, unfair language understanding and generation

### Another major challenge: Truthfulness and hallucinations
* **Hallucinations:** generated text contains false or nonsensical information as if it were accurate

<img width="1027" height="138" alt="image" src="https://github.com/user-attachments/assets/c4f63740-ff9a-40de-9b54-ff6f71c096ea" />

* **Strategies to reduce LLM hallucinations:**

1. Exposure to diverse and representative **training data**
2. **Bias** audits on model outputs + bias removal techniques
3. **Fine-tune** to specific use cases in sensitive applications
4. **Prompt engineering:** carefully crafting and refining prompts

<img width="1152" height="247" alt="image" src="https://github.com/user-attachments/assets/dd152f8f-0b55-4403-a359-764cb24a7ee2" />

### Metrics for analyzing LLM bias: toxicity
* **Toxicity:** quantifies text toxicity using pre-trained hate speech classifier

<img width="1027" height="357" alt="image" src="https://github.com/user-attachments/assets/99b550b9-8a78-481f-ab7e-2830a5c62b37" />

* **aggregation= "maximum"** returns maximum toxicity score across inputs
* **aggregation= "ratio"** returns the % predictions with toxicity above 0.5

### Metrics for analyzing LLM bias: regard
* **Regard:** language polarity and biased perception towards certain demographic(s)
* Evaluate regard scores on **LLM outputs associated to two groups** separately

<img width="883" height="368" alt="image" src="https://github.com/user-attachments/assets/55c9c094-47e1-4bfb-ab8e-fdc9681a8ef8" />

<img width="1205" height="397" alt="image" src="https://github.com/user-attachments/assets/34524845-3b28-444c-b30f-8766eb6b96ee" />
