# ChatBot-Using-MIstral-Model

# 🤖 LangChain Local Chatbot with CTransformers, Streamlit & LocalTunnel

This project demonstrates how to create a simple **chatbot powered by a local LLM (LLaMA 2)** using **LangChain**, **CTransformers**, and **Streamlit**. The chatbot runs locally and can be shared online via **LocalTunnel**.

---

## 🚀 Features

- Load local LLM using `ctransformers` (e.g., LLaMA 2)
- Interactive UI built with `streamlit`
- Public sharing via `localtunnel`
- Runs on Google Colab or any local machine

---

## 🛠️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/langchain-local-chatbot.git
cd langchain-local-chatbot
2. Install Required Libraries
Install all Python dependencies:

bash
Copy
Edit
pip install langchain streamlit ctransformers
3. Download a Local Model
Download a .bin file compatible with CTransformers (e.g., llama-2-7b-chat.ggmlv3.q4_0.bin) and place it in the project root directory.

Example sources: TheBloke on Hugging Face

📄 File Structure
graphql
Copy
Edit
langchain-local-chatbot/
├── app.py               # Streamlit frontend
├── llm_config.py        # Loads local LLM
├── README.md            # This file
└── llama-2-model.bin    # Your downloaded GGML model file (name as required)
▶️ How to Run
Locally:
bash
Copy
Edit
streamlit run app.py
On Google Colab + LocalTunnel:
Mount Google Drive

Run setup code

Use LocalTunnel to expose the Streamlit port:

bash
Copy
Edit
npx localtunnel --port 8501
Copy the generated public URL to share your chatbot!


📚 License
This project is licensed under the MIT License. You are free to use and modify it.

🙌 Acknowledgements
LangChain

CTransformers

Streamlit

LocalTunnel
