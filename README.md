# Punjabi Question Answering System 🇮🇳🤖
This is a multilingual extractive QA system for Punjabi (Gurmukhi script), developed using the `xlm-roberta-large-squad2` model from Hugging Face Transformers.
It allows users to input Punjabi text and get answers to their questions in real-time.

## 📝 Description
- Built as part of the **Conversational AI (UCS664)** course at Thapar Institute of Engineering & Technology.
- Real-time interface developed using **Gradio**.
- Uses **zero-shot inference** to answer questions in Punjabi using a model trained on English SQuAD2.0.

## 📄 Files Included
- `NLP_FinalProj.ipynb` – Main code
- `NLP Project Punjabi QnA.pdf` – Full academic report
- `requirements.txt` – Python dependencies

## ▶️ How to Run
```bash
pip install -r requirements.txt
python punjabi_qa.py

## ▶️ Sample Input
📝 Context:
"ਕ੍ਰਿਤ੍ਰਿਮ ਬੁੱਧੀ ਜਾਂ ਆਰਟੀਫੀਸ਼ਲ ਇੰਟੈਲੀਜੈਂਸ (AI) ਇੱਕ ਤਕਨਾਲੋਜੀ ਹੈ ਜੋ ਕੰਪਿਊਟਰਾਂ ਨੂੰ ਮਨੁੱਖੀ ਬੁੱਧੀ ਵਰਗਾ ਸੋਚਣ ਅਤੇ ਫੈਸਲੇ ਲੈਣ ਯੋਗ ਬਣਾਉਂਦੀ ਹੈ।
ਇਸ ਵਿਚ ਮਸ਼ੀਨ ਲਰਨਿੰਗ, ਡੀਪ ਲਰਨਿੰਗ, ਨੈਚਰਲ ਲੈਂਗਵਿਜ ਪ੍ਰੋਸੈਸਿੰਗ ਅਤੇ ਕੰਪਿਊਟਰ ਵਿਜ਼ਨ ਵਰਗੀਆਂ ਵਿਧੀਆਂ ਸ਼ਾਮਲ ਹਨ।
AI ਦਾ ਉਦੇਸ਼ ਐਸੀਆਂ ਮਸ਼ੀਨਾਂ ਤਿਆਰ ਕਰਨਾ ਹੈ ਜੋ ਸਵੈ-ਸੀਖਣ, ਸਵੈ-ਨਿਰਣੈ ਅਤੇ ਮਨੁੱਖੀ ਤਰ੍ਹਾਂ ਕੰਮ ਕਰਨ ਵਿੱਚ ਸਮਰਥ ਹੋਣ।
AI ਦੀ ਵਰਤੋਂ ਅੱਜਕੱਲ੍ਹ ਹੈਲਥਕੇਅਰ, ਆਟੋਮੋਬਾਈਲ, ਫਾਈਨੈਂਸ, ਖੇਤੀਬਾੜੀ ਅਤੇ ਸਿੱਖਿਆ ਵਿਚ ਹੋ ਰਹੀ ਹੈ।"

❓ Question:
"ਕ੍ਰਿਤ੍ਰਿਮ ਬੁੱਧੀ ਦੇ ਮੁੱਖ ਹਿੱਸੇ ਕਿਹੜੇ ਹਨ?"

✅ Expected Answer: ਮਸ਼ੀਨ ਲਰਨਿੰਗ, ਡੀਪ ਲਰਨਿੰਗ, ਨੈਚਰਲ ਲੈਂਗਵਿਜ ਪ੍ਰੋਸੈਸਿੰਗ, ਕੰਪਿਊਟਰ ਵਿਜ਼ਨ
