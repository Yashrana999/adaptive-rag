# 🧠 Adaptive RAG - Intelligent Retrieval System  
### 🚀 Customized & Documented by Yash Rana

---

## 📌 Overview

Adaptive RAG is an advanced Retrieval-Augmented Generation (RAG) system that dynamically adjusts its retrieval strategy based on query complexity. Instead of blindly retrieving documents for every query, the system intelligently decides:

- ❌ No Retrieval → for simple/general queries  
- 📄 Single-Step Retrieval → for moderate queries  
- 🔁 Multi-Step Retrieval → for complex reasoning queries  

This makes the system more **efficient, scalable, and closer to real-world AI systems**.

---

## 🎯 Key Features

- 🧠 **Adaptive Query Routing**
- 📚 **Dynamic Retrieval Strategy**
- ⚡ **Optimized Performance (cost + speed)**
- 🔍 **Context-Aware Answer Generation**
- 🏗️ **Modular AI Architecture (LangGraph-based)**

---

## 🏗️ Architecture

The system follows a decision-based pipeline:

1. Query Analysis  
2. Complexity Classification  
3. Routing Decision  
4. Retrieval (if needed)  
5. Answer Generation  

📌 This approach improves both:
- Accuracy  
- Efficiency  

---

## 📂 Project Structure


Adaptive-Rag/
├── src/ # Core logic
├── streamlit_app/ # UI interface
├── requirements.txt # Dependencies
├── README.md
├── documentation files


---

## 🧹 Cleanup Before Upload (Important)

Before pushing this project to GitHub, unnecessary files were removed to keep the repository clean:

- `.idea/` → IDE config files  
- `__pycache__/` → Python cache files  
- `.ipynb_checkpoints/` → Notebook temp files  

This ensures:
- Clean repo structure  
- No unnecessary files  
- Professional appearance  

---

## ⚙️ Setup (Optional)

> ⚠️ Note: This project is uploaded for portfolio and learning purposes.  
> Running locally is optional.

If needed:

```bash
pip install -r requirements.txt
💡 My Contribution
📌 Cloned and structured the project
🧹 Cleaned unnecessary files
📝 Rewrote and improved documentation
🎯 Presented it as a portfolio-ready AI project
📚 Learning Outcome

Through this project, I explored:

Adaptive Retrieval-Augmented Generation (RAG)
Query routing strategies
Efficient LLM pipeline design
Real-world AI system architecture
🙌 Acknowledgment / Original Source

This project is based on the original work:

👉 https://github.com/dhruvsinghal09/Adaptive-Rag

Full credit goes to the original author for the implementation.
This version includes customization, documentation, and structuring for learning and portfolio purposes.

👨‍💻 Author

Yash Rana
B.Tech AIML Student | AI/ML Enthusiast

⭐ Final Note

This project demonstrates a strong understanding of modern AI systems like RAG, making it highly relevant for roles such as:

AI Engineer
ML Engineer
GenAI Engineer
