## Fine-tuning through training
### Training Arguments

<img width="540" height="472" alt="image" src="https://github.com/user-attachments/assets/b1019d8a-5490-4608-9114-48e22e455592" />

* **TrainingArguments():** customize training settings
* See documentation for all parameters
* Values depend on use, dataset, speed
* **output_dir:** output directory
* **eval_strategy:** when to evaluate "epoch", "steps", or "none"
* **num_train_epochs:** number of training epochs
* **learnung_rate:** for optimizer
* **per_device_train_batch_size** and **per_device_eval_batch_size** define the batch size
* **weight_decay:** applied to the optimizer to avoid overfitting

### Trainer class

<img width="542" height="495" alt="image" src="https://github.com/user-attachments/assets/62d61dfe-90e9-4ba2-b9eb-2c025c73b450" />

* **model:** the model to fine-tune
* **args:** the training arguments
* **train_dataset:** the data used for training
* **eval_dataset:** the data used for evaluation
* **tokenizer:** the tokenizer

Number of training loops: Dataset size, **num_train_epochs**, **per_device_train_batch_size** and **per_device_eval_batch_size**

### Trainer output

<img width="1110" height="432" alt="image" src="https://github.com/user-attachments/assets/1dbf126e-0168-4ecc-97ac-ced56eb34f6c" />

### Using the fine-tuned model

<img width="1107" height="466" alt="image" src="https://github.com/user-attachments/assets/3b45c950-6fc7-4ccb-a2a6-a31d9452ee87" />

### Fine-tuning results

<img width="1106" height="210" alt="image" src="https://github.com/user-attachments/assets/2d7b49e8-b74c-498b-abd4-cb5c421c1419" />

### Saving models and tokenizers

<img width="615" height="205" alt="image" src="https://github.com/user-attachments/assets/2f3a46f6-a404-4b82-8a98-a6223b96ef16" />

### Loading a saved model

<img width="1012" height="123" alt="image" src="https://github.com/user-attachments/assets/c3a934cf-a840-49c8-8848-04309f2a054b" />
