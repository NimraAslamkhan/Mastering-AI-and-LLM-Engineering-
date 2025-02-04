# 🧠 How can I run large language models (LLMs) on my local computer?

# 🧠 LM Studio - Run LLMs Locally  

LM Studio allows you to run Large Language Models (LLMs) on your **local machine** without relying on cloud services.  

## ✅ Why Use LM Studio?  
- **🔒 Privacy & Security** – No data leaves your device.  
- **⚡ Faster Performance** – No API latency, runs on your hardware.  
- **💰 Cost-Free** – No API fees, use open-source models for free.  
- **🌐 Offline Mode** – Works without an internet connection.  
- **🛠 Customizable** – Choose, fine-tune, and optimize models as needed.  

---

## 🔽 List of Available Models  

LM Studio supports a variety of **powerful open-source models**. You can download and run them locally.  

### 🔥 Popular Models  

1. **[Granite 3.1 8B](https://huggingface.co/lmstudio-community/granite-3.1-8b)**
   - A dense LLM from IBM supporting up to **128K context length**, trained on **500B tokens**.  
   - Best for **general instruction following** and **AI assistants**.

2. **[Qwen2.5 Coder 14B](https://huggingface.co/lmstudio-community/qwen2.5-coder-14b)**
   - **14B parameters** model optimized for **code generation, reasoning, and debugging**.  
   - Supports **128K context length**.

3. **[Hermes 3 Llama 3.2 3B](https://huggingface.co/lmstudio-community/hermes-3-llama-3.2-3b)**
   - **Agentic model** with enhanced **role-playing, reasoning, and multi-turn conversations**.  
   - Maintains **long context coherence**.

4. **[Phi-4](https://huggingface.co/lmstudio-community/phi-4)**
   - The latest in the **Phi model series**, optimized for **chat and reasoning**.  
   - Supports **16K context tokens**.

5. **[InternLM 2.5 20B](https://huggingface.co/lmstudio-community/internlm-2.5-20b)**
   - Strong **reasoning** and **tool use** capabilities for developers.  
   - Requires at least a **24GB GPU**.

For a **full list of models**, visit the **[LM Studio Model Catalog](https://lmstudio.ai/models)**.  

---

## 🚀 Installation Guide  

1. Download **LM Studio** from: [LM Studio Official Site](https://lmstudio.ai/)  
2. Install it on Windows/Mac/Linux.  

---

## 🏃 How to Use LM Studio  

1. **Open LM Studio** → Go to **"Model Catalog"**.  
2. Search and **Download** the model you need.  
3. Go to **"Local Models"** → Click **Load Model**.  
4. Start chatting or use the **API** to integrate with your apps.  

---

## 🖥️ API Usage (Python)  

Enable the **Local Server** in LM Studio and use the following Python script:  

```python
import requests

url = "http://localhost:1234/v1/completions"  # Adjust if needed

payload = {
    "model": "your_model_name",
    "prompt": "Hello, how are you?",
    "max_tokens": 50
}

response = requests.post(url, json=payload)
print(response.json())


