# MVOSLab ChatBot  

<img src="lab_logo.PNG" alt="MVOS Lab Logo" width="120" align="left">

## 🚀 Overview  
**MVOSLab ChatBot** is a locally running AI chatbot powered by **DeepSeek-R1**, developed at **South Dakota State University's MVOS Lab**. The chatbot utilizes the **Ollama** framework to run AI models efficiently on your local machine.  

---

## 📥 Installation & Setup  

### 1️⃣ **Download Ollama**  
Ollama is required to run DeepSeek-R1. Download and install it based on your OS from the following link:  
🔗 [Ollama Official GitHub](https://github.com/ollama/ollama)  

### 2️⃣ **Download DeepSeek-R1 Model**  
After installing Ollama, open a command window and **download the DeepSeek-R1 model** of your choice.  

> **Note:** The model version you choose depends on your system's computing power. The **DeepSeek-R1:7B** model has been tested on a laptop with an **NVIDIA RTX 4070**.  

Run the following command in **Command Prompt (cmd)**:  

```bash
ollama run deepseek-r1:7b
```

## 🎯 Features
✅ Runs locally without an internet connection.
✅ Supports DeepSeek-R1 models via Ollama.
✅ Fast & Efficient on supported GPUs.
✅ Standalone executable for easy access.
✅ No cloud dependency – everything runs on your local machine.
✅ Simple installation with minimal dependencies. 

## 📌 Notes
GPU Recommended: Running DeepSeek-R1:7B requires a dedicated GPU (RTX 4070 or higher recommended).
If you face issues, ensure Ollama is installed correctly and that the model weights have been downloaded.
The .exe version is a lightweight alternative but requires PNG assets in the same folder.
The chatbot runs an API on localhost:11434, which can be accessed via compatible applications.

## 🔗  Acknowledgments
DeepSeek-R1: A high-performance open-source LLM.
Ollama: A framework for running local AI models.

#### 🧑‍💻 Developed by: MVOS Lab, Department of Agricultural & Biosystems Engineering, South Dakota State University, Brookings, SD
🚀 Contributing to AI & Precision Agriculture Research



