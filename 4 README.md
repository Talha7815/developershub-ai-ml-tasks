<div align="center">
  
  # 🏥 HealthBuddy - AI-Powered Health Information Assistant
  
  [![Groq](https://img.shields.io/badge/Groq-00A67E?style=for-the-badge&logo=groq&logoColor=white)](https://groq.com)
  [![Llama](https://img.shields.io/badge/Llama_3-FF6F00?style=for-the-badge&logo=meta&logoColor=white)](https://ai.meta.com/llama/)
  [![Gradio](https://img.shields.io/badge/Gradio-FF6B6B?style=for-the-badge&logo=gradio&logoColor=white)](https://gradio.app)
  [![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
  [![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org)
  
  ### *Your Intelligent General Health Information Assistant*
  
  [![GitHub stars](https://img.shields.io/github/stars/yourusername/healthbuddy?style=social)](https://github.com/yourusername/healthbuddy)
  [![GitHub forks](https://img.shields.io/github/forks/yourusername/healthbuddy?style=social)](https://github.com/yourusername/healthbuddy)
  [![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  
  <img src="screenshots/demo.gif" alt="HealthBuddy Demo" width="600"/>
  
</div>

---

## 📋 **Table of Contents**
- [Overview](#-overview)
- [Features](#-features)
- [Technology Stack](#-technology-stack)
- [Architecture](#-architecture)
- [Installation](#-installation)
- [Usage](#-usage)
- [Safety Features](#-safety-features)
- [API Configuration](#-api-configuration)
- [Screenshots](#-screenshots)
- [Project Structure](#-project-structure)
- [Performance Metrics](#-performance-metrics)
- [Troubleshooting](#-troubleshooting)
- [Future Enhancements](#-future-enhancements)
- [Contributing](#-contributing)
- [License](#-license)
- [Acknowledgements](#-acknowledgements)
- [Contact](#-contact)

---

## 🔍 **Overview**

**HealthBuddy** is a sophisticated AI-powered health information assistant built for the DevelopersHub Corporation AI/ML Engineering Internship (Task 4). It leverages **Groq's ultra-fast inference** with **Meta's Llama 3 model** to provide general health information in a safe, controlled manner.

### 🎯 **Purpose**
This project demonstrates the practical application of Large Language Models (LLMs) in healthcare contexts, with a strong emphasis on **safety, accuracy, and user experience**. It serves as a proof-of-concept for AI-assisted health information systems.

### 🏥 **Use Case**
HealthBuddy helps users get quick answers to general health questions, understand symptoms (without diagnosis), learn about wellness practices, and know when to seek professional medical help.

---

## ✨ **Features**

| Feature | Description | Status |
|---------|-------------|--------|
| 🚀 **Groq Integration** | 10x faster inference using Groq's custom LPU chips | ✅ |
| 🦙 **Llama 3 Model** | State-of-the-art 70B parameter model for accurate responses | ✅ |
| 🛡️ **Emergency Detection** | Real-time detection of medical emergencies with immediate response | ✅ |
| 💬 **Conversation Memory** | Maintains context throughout the conversation | ✅ |
| 🎨 **Professional UI** | Clean, modern Gradio interface with responsive design | ✅ |
| 🔑 **Secure API Handling** | API keys entered securely, never exposed in code | ✅ |
| ⚕️ **Medical Disclaimers** | Automatic inclusion of appropriate medical disclaimers | ✅ |
| 📝 **Example Questions** | 8 pre-configured health questions for quick testing | ✅ |
| 🧹 **Chat Management** | Clear chat functionality and history management | ✅ |
| 📊 **Usage Statistics** | Track interactions and performance metrics | ✅ |

---

## 🛠️ **Technology Stack**

<div align="center">

| **Layer** | **Technology** | **Purpose** |
|:---------:|:--------------:|:-----------:|
| **Frontend** | ![Gradio](https://img.shields.io/badge/Gradio-FF6B6B?style=flat-square&logo=gradio&logoColor=white) | Web interface & UI components |
| **Backend** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | Core logic & API integration |
| **AI Model** | ![Llama](https://img.shields.io/badge/Llama_3-FF6F00?style=flat-square&logo=meta&logoColor=white) | Language model for responses |
| **Inference** | ![Groq](https://img.shields.io/badge/Groq-00A67E?style=flat-square&logo=groq&logoColor=white) | Ultra-fast model inference |
| **Development** | ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) | Interactive development |

</div>

### **Key Dependencies**
```python
groq==0.9.0        # Groq API client
gradio==4.31.0     # Web interface framework
python-dotenv==1.0.0  # Environment management


