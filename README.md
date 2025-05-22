
# 💬 ChatGPT + Gradio Integration

This project demonstrates how to integrate **ChatGPT** with a **Gradio** interface using a custom model endpoint and API key. It supports both **CLI interaction** and a **web-based UI** for chatting with a language model.

## 🚀 Features

* 🌐 **Gradio Web UI** for interactive chat
* 🖥️ **Command-line Interface** for direct terminal chat
* ⚙️ Custom base URL support for self-hosted or proxy models
* 🔁 Continuous loop in CLI for back-and-forth conversation

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Install Dependencies

```bash
pip install openai gradio
```

### 3. Set Your Environment Variables

Set your API key and base URL in your system environment variables or directly in the script:

```python
api_key = "your_api_key_here"
base_url = "https://models.github.ai/inference"
```

### 4. Run the App

```bash
python app.py
```

* Visit the Gradio interface in your browser
* Or chat directly via terminal

---

## 🧠 Tech Stack

* **Python**
* **Gradio** – for creating the web interface
* **OpenAI SDK** – for calling the GPT model

---

## 📝 Example Prompt

Ask anything like:

> "Explain the difference between machine learning and deep learning."

---


