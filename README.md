# Project README: Inference on CPU and Fine-Tuning of LLM Model to Create a Custom Chatbot

## Team Name: Tensor Titans

---

### Project Overview

This project focuses on performing inference on a CPU and fine-tuning a large language model (LLM) to create a custom chatbot. The primary goal is to leverage the capabilities of the sshleifer/distilbart-cnn-6-6 model to handle sequence-to-sequence tasks efficiently while ensuring robust performance in summarization.

---

### Model Details

**Model Used: [sshleifer/distilbart-cnn-6-6](https://huggingface.co/sshleifer/distilbart-cnn-6-6)**

The sshleifer/distilbart-cnn-6-6 model, part of the DistilBART family, is a variant of BART (Bidirectional and Auto-Regressive Transformers). This model has been distilled to enhance efficiency, making it lightweight and faster, while maintaining strong performance in sequence-to-sequence tasks such as text generation and summarization. The DistilBART model is particularly well-suited for applications requiring quick and accurate text processing.

---

### Dataset Details

**Dataset Used: [samsum](https://huggingface.co/datasets/samsum)**

The "samsum" dataset is derived from WhatsApp conversations and is specifically designed for dialogue summarization tasks. It comprises pairs of conversational dialogues alongside corresponding summaries, making it ideal for training and evaluating models aimed at generating concise summaries from informal, conversational text. This dataset is valuable in natural language processing research for its realistic depiction of everyday language use in messaging applications, challenging models to handle slang, abbreviations, and incomplete sentences. Researchers and developers utilize samsum to benchmark and advance techniques in sequence-to-sequence learning, aiming to produce summaries that effectively capture the main points and nuances of informal dialogues.

---

### Fine-Tuning Process

The method of fine-tuning used in this project is referred to as sequence-to-sequence (seq2seq) fine-tuning. This approach involves training the model to map input sequences (dialogues) to output sequences (summaries). Fine-tuning the sshleifer/distilbart-cnn-6-6 model with the samsum dataset allows the model to learn the nuances of conversational text and produce accurate and concise summaries, enhancing its capability to function as a custom chatbot.

---


### Warnings and Considerations

**UserWarning: `as_target_tokenizer` is deprecated and will be removed in v5 of Transformers.**  
You can tokenize your labels by using the argument `text_target` of the regular `__call__` method (either in the same call as your input texts if you use the same keyword arguments, or in a separate call).

**FutureWarning: `evaluation_strategy` is deprecated and will be removed in version 4.46 of 🤗 Transformers.**  
Use `eval_strategy` instead.

**Generation Parameters Warning:**  
Some non-default generation parameters are set in the model config. These should go into a GenerationConfig file ([more details here](https://huggingface.co/docs/transformers/generation_strategies#save-a-custom-decoding-strategy-with-your-model)). This warning will be raised to an exception in v4.41.  


### Results and Evaluation

After fine-tuning, the model is evaluated based on its ability to generate accurate and concise summaries of dialogues. The performance is measured using standard metrics for summarization tasks, ensuring that the chatbot can effectively understand and respond to informal conversational text. Note that larger datasets often result in lower validation losses because the model has more diverse examples to learn from, whereas smaller datasets can lead to higher validation losses due to the model's struggle to generalize well.

---

### Few Outputs :
<img width="1239" alt="image" src="https://github.com/user-attachments/assets/9940649d-eae2-4594-97f5-7b77a476ea34">
<img width="1275" alt="image" src="https://github.com/user-attachments/assets/b80e9d08-6c5d-4a47-8983-edeee076f305">




### Conclusion

The Tensor Titans team has successfully implemented a sequence-to-sequence fine-tuning process on the sshleifer/distilbart-cnn-6-6 model using the samsum dataset. This project demonstrates the model's capability to handle informal dialogue summarization, providing a foundation for creating efficient and effective custom chatbots.

---

For any questions or further information, please contact the Tensor Titans team at :
Arya Anand Pathak - 1nt23ec022.arya@nmit.ac.in
L Tejas - 1nt23ec072.tejas@nmit.ac.in
Praveen Raj Srivastav - 1nt23ec110.praveen@nmit.ac.in

Github Accounts : 
Arya Anand Pathak - https://github.com/runningpoem30
L Tejas - https://github.com/tejas-54 
Praveen Raj Srivastav - https://github.com/praveen24sriv 


---

Thank you for exploring our project!
