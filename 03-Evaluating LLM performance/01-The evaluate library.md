## The evaluate library

<img width="537" height="467" alt="image" src="https://github.com/user-attachments/assets/58f93dd2-7b01-45e0-9476-761904032417" />

* **Metric:** evaluate model performance based on ground truth
* **Comparison:** compare two models
* **Measurement:** insight on dataset properties

### Features attribute

<img width="548" height="162" alt="image" src="https://github.com/user-attachments/assets/d8848839-d946-439b-a51e-1632fbfcbdb0" />

<img width="535" height="198" alt="image" src="https://github.com/user-attachments/assets/798d250e-1f0a-4ead-8042-fa2f5c900725" />

<img width="566" height="197" alt="image" src="https://github.com/user-attachments/assets/ffa21bb6-ad0a-46a1-b11d-c7b1294c789f" />

**Inspecting required inputs by a metric**

* **'predictions':** model outputs
* **'references':** ground truth
* **.features:** indicates the type supported for class labels, e.g. **'int32'** or **'float32'**

### LLM tasks and metrics

<img width="1042" height="400" alt="image" src="https://github.com/user-attachments/assets/7bb4788c-8fed-4560-8500-1d1400ca7e19" />

### Classification metrics

<img width="1106" height="462" alt="image" src="https://github.com/user-attachments/assets/28b11d1a-b79d-49ab-9200-fbd771041e73" />

### Metric outputs

<img width="1107" height="482" alt="image" src="https://github.com/user-attachments/assets/a143a2b8-0042-47d5-ba3c-e6acbaeb07d5" />

### Evaluating our fine-tuned model

<img width="542" height="497" alt="image" src="https://github.com/user-attachments/assets/84b2d057-d5c4-4dc8-8ba9-cb12c8ef38a3" />

<img width="548" height="425" alt="image" src="https://github.com/user-attachments/assets/007865ce-1f47-432c-8361-01fab4b42b51" />

### Choosing the right metric

* Be **aware:** each metric brings its own insights, but they also have their limitations
* Be **comprehensive:** use a combination of metrics (and domain-specific KPIs where possible)
