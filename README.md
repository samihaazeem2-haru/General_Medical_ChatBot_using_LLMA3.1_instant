# General_Medical_ChatBot_using_LLMA3.1_instant

A ready-to-use **Health Information Chatbot** powered by **Llama-3.1-8B-Instant (via Groq API)** and deployed through **Gradio**.  
This chatbot provides general, educational health information with built-in safety filters, risk detection, and non-medical-advice rules.


###  General Health Information  
The chatbot gives simple, easy-to-understand explanations about:
- Symptoms  
- Common illnesses  
- Preventive health  
- Lifestyle guidance  
- General medication *information* (not advice)

### Safety Layer  
The chatbot includes:
- High-risk phrase detection (self-harm, suicidal intent, etc.)  
- Medical advice detection  
- Automatic safe-response handling  
- Strict non-diagnostic behavior

### Gradio Web Interface  
- Clean UI  
- Public sharing link (valid for 72 hours on Colab)  
- Chat history  
- Example prompts  

### Optional Testing Mode  
A quick function to test the chatbot without launching Gradio.


## Requirements

- Python 3.9+
- Groq API Key (Get from here: https://console.groq.com/)
- Google Colab (Recommended)


## Setup & Usage (Google Colab)

### 1️.Open a new Colab Notebook

### 2️.Copy the entire .ipynb content into your notebook

### 3️.Run the cells in order
Installs dependencies  
Prompts for or loads API key  
Loads the chatbot and builds UI  
Launches the web app  

### 4️.Get Your Public URL
Once launched, Gradio gives you:
- A **local link**
- A **public link** → you can share with anyone



