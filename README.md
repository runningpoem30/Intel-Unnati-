# Intel-Unnati
Team - Tensor Titans 
Project - Introduction to GenAI and Simple LLM Inference on CPU and Finetuning of LLM Model to Create a Custom Chatbot 
# Project README: Inference on CPU and Fine-Tuning of LLM Model to Create a Custom Chatbot

## Team Name: Tensor Titans

---

### Project Overview

This project focuses on performing inference on a CPU and fine-tuning a large language model (LLM) to create a custom chatbot. The primary goal is to leverage the capabilities of the sshleifer/distilbart-cnn-6-6 model to handle sequence-to-sequence tasks efficiently while ensuring robust performance in text generation and summarization.

---

### Model Details

Model Used: [sshleifer/distilbart-cnn-6-6](https://huggingface.co/sshleifer/distilbart-cnn-6-6)**

The sshleifer/distilbart-cnn-6-6 model, part of the DistilBART family, is a variant of BART (Bidirectional and Auto-Regressive Transformers). This model has been distilled to enhance efficiency, making it lightweight and faster, while maintaining strong performance in sequence-to-sequence tasks such as text generation and summarization. The DistilBART model is particularly well-suited for applications requiring quick and accurate text processing.

---

### Dataset Details

**Dataset Used: [samsum](https://huggingface.co/datasets/samsum)**

The "samsum" dataset is derived from WhatsApp conversations and is specifically designed for dialogue summarization tasks. It comprises pairs of conversational dialogues alongside corresponding summaries, making it ideal for training and evaluating models aimed at generating concise summaries from informal, conversational text. This dataset is valuable in natural language processing research for its realistic depiction of everyday language use in messaging applications, challenging models to handle slang, abbreviations, and incomplete sentences. Researchers and developers utilize samsum to benchmark and advance techniques in sequence-to-sequence learning, aiming to produce summaries that effectively capture the main points and nuances of informal dialogues.

---

### Fine-Tuning Process

The method of fine-tuning used in this project is referred to as sequence-to-sequence (seq2seq) fine-tuning. This approach involves training the model to map input sequences (dialogues) to output sequences (summaries). Fine-tuning the sshleifer/distilbart-cnn-6-6 model with the samsum dataset allows the model to learn the nuances of conversational text and produce accurate and concise summaries, enhancing its capability to function as a custom chatbot.

---

### How to Run the Project

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/your-repo/project-name.git
   cd project-name
   ```

2. **Install Dependencies**:
   ```sh
   pip install -r requirements.txt
   ```

3. **Prepare the Dataset**:
   Ensure you have access to the samsum dataset and place it in the appropriate directory as specified in the code.

4. **Fine-Tune the Model**:
   ```sh
   python fine_tune.py
   ```

5. **Run Inference on CPU**:
   ```sh
   python inference.py
   ```

---

### Results and Evaluation

After fine-tuning, the model is evaluated based on its ability to generate accurate and concise summaries of dialogues. The performance is measured using standard metrics for summarization tasks, ensuring that the chatbot can effectively understand and respond to informal conversational text.

---

### Conclusion

The Tensor Titans team has successfully implemented a sequence-to-sequence fine-tuning process on the sshleifer/distilbart-cnn-6-6 model using the samsum dataset. This project demonstrates the model's capability to handle informal dialogue summarization, providing a foundation for creating efficient and effective custom chatbots.

---

For any questions or further information, please contact the Tensor Titans team at [your-email@example.com].

---

Thank you for exploring our project!

