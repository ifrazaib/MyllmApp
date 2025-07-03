# 🧠 Fine-Tuned GPT-2 Chatbot with Streamlit

This project fine-tunes the `GPT-2` language model on a short, custom instruction-response dataset using LoRA (Low-Rank Adaptation) and deploys it using Streamlit Cloud.

---

## 🚀 Features

- Fine-tunes GPT-2 with a small dataset using Hugging Face + LoRA
- Interactive chatbot UI built with Streamlit
- Easily deployable via Streamlit Cloud

---

## 📂 Project Structure

my-llm-app/
- ├── app.py # Streamlit app
- ├── requirements.txt # Required Python libraries
- └── llm-finetuned/ # Fine-tuned model directory
- ├── config.json
- ├── pytorch_model.bin
- ├── tokenizer_config.json
- ├── tokenizer.json
- └── vocab.json

---

## 🛠️ How to Use

1. **Train model in Colab** and save `llm-finetuned/`
2. **Push all files to GitHub**
3. **Deploy on : https://myllmapp-gpt2.streamlit.app/**:
   - Repo: https://github.com/ifrazaib/MyllmApp
   - File: `app.py`

---

## 📥 Install Locally (Optional)

```bash
pip install -r requirements.txt
streamlit run app.py
