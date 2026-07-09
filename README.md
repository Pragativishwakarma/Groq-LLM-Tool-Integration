# 🚀 Groq LLM Tool Integration

A Python-based project demonstrating **Groq LLM Tool Calling (Function Calling)** by integrating external Python functions with Groq's powerful Large Language Models. This project showcases how AI models can intelligently invoke custom tools to perform real-world tasks and return structured responses.

---

## 📌 Features

- ✅ Groq LLM Integration
- ✅ Function (Tool) Calling
- ✅ Modular Python Architecture
- ✅ Environment Variable Configuration
- ✅ Structured JSON Responses
- ✅ Fast Inference using Groq API
- ✅ Easy to Extend with Custom Tools
- ✅ Beginner-Friendly Project Structure

---

## 📂 Project Structure

```
groq_tool_calling/
│
├── main.py                 # Main application
├── tool.py                 # Custom tool definitions
├── client.py               # Client implementation (if applicable)
├── requirements.txt        # Python dependencies
├── .env                    # API Keys (Not uploaded)
├── .gitignore
└── README.md
```

> **Note:** The actual project structure may vary slightly depending on your implementation.

---

## 🛠️ Technologies Used

- Python 3.x
- Groq API
- LLM Tool Calling
- Environment Variables (.env)
- Virtual Environment (venv)

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Pragativishwakarma/Groq-LLM-Tool-Integration.git
```

### 2. Navigate to the Project

```bash
cd Groq-LLM-Tool-Integration
```

### 3. Create a Virtual Environment

**Mac/Linux**

```bash
python3 -m venv venv
```

**Windows**

```bash
python -m venv venv
```

---

### 4. Activate the Virtual Environment

**Mac/Linux**

```bash
source venv/bin/activate
```

**Windows**

```bash
venv\Scripts\activate
```

---

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file in the project root.

```env
GROQ_API_KEY=your_groq_api_key_here
```

> Never upload your `.env` file to GitHub.

---

## ▶️ Run the Project

```bash
python main.py
```

or

```bash
python client.py
```

depending on your project entry point.

---

## 💡 How Tool Calling Works

1. User sends a prompt.
2. Groq LLM analyzes the request.
3. The model decides whether a tool is required.
4. Appropriate Python function is called.
5. Tool output is returned to the model.
6. The model generates the final response.

---

## 📸 Example Workflow

```
User Query
      │
      ▼
 Groq LLM
      │
      ▼
 Tool Calling
      │
      ▼
 Python Function
      │
      ▼
 Function Output
      │
      ▼
 Final AI Response
```

---

## 📖 Learning Objectives

This project demonstrates:

- Large Language Model Integration
- Function Calling
- Tool Execution
- API Integration
- Prompt Engineering
- Modular Python Development
- Environment Variable Management
- AI Workflow Automation

---

## 🚀 Future Improvements

- Multiple Tool Support
- Weather API Integration
- Database Connectivity
- Web Search Tool
- Calculator Tool
- Email Automation
- File Operations
- Agentic AI Workflows
- RAG Integration
- Multi-Agent Architecture


---

## 📄 License

This project is licensed under the MIT License.

---

## 👩‍💻 Author

**Pragati Vishwakarma**

AI & Data Science Engineer | Python Developer | Generative AI Enthusiast

- GitHub: https://github.com/Pragativishwakarma
- LinkedIn: www.linkedin.com/in/pragati-vishwakarma-893ba8284

---

⭐ If you found this project useful, don't forget to **Star** the repository!
