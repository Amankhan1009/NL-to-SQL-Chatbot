# 🦜 Chat with SQL Database using LangChain & Streamlit

An AI-powered chatbot that lets you query your SQL databases using **natural language**.  
Built with **LangChain**, **Groq LLM (LLaMA 3.3 – 70B)**, and **Streamlit**, this app converts user questions into SQL queries and returns results from **SQLite** or **MySQL (MySQL Workbench)**.

---

## 🚀 Features

- 💬 Chat with your database using plain English  
- 🗄️ SQLite support (student.db included)  
- 🛢️ MySQL support (Connect your MySQL Workbench database)  
- ⚡ Groq LLM (LLaMA 3.3 – 70B) for fast responses  
- 🖥️ Streamlit UI  
- 🔐 Secure API key input  
- 🔄 Real-time streaming responses  
- 🤖 LangChain SQL Agent  
- 🧹 Clear chat history  
- 🧠 Handles SQL parsing errors gracefully  

---

## 🛠️ Tech Stack

- Python  
- LangChain  
- Streamlit  
- Groq LLM  
- SQLite  
- MySQL (MySQL Workbench)  
- SQLAlchemy  

---

## 📂 Project Structure

├── app.py # Streamlit app (main entry point)
├── sqlite.py # Script to create and populate SQLite DB
├── student.db # Sample SQLite database
├── requirements.txt # Project dependencies
└── README.md


---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Amankhan1009/Search-Engine-With-Langchain.git
cd Search-Engine-With-Langchain
```

### 2️⃣ Create Virtual Environment (Recommended)
```bash
python -m venv venv
venv\Scripts\activate        # Windows
source venv/bin/activate    # Linux / Mac
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Create SQLite Database (Optional)
```bash
python sqlite.py
```
This will create student.db with sample student records.

### ▶️ Run the Application
```bash
streamlit run app.py
```

### 🔑 Groq API Key Setup

- 1.Visit 👉 https://console.groq.com
- 2.Generate your API key
- 3.Paste the key in the Streamlit sidebar
⚠️ Without the API key, the app will not run.

### 🛢️ Connect Your MySQL Workbench Database

You can connect your MySQL Workbench database directly:

- 1.Start MySQL Server
- 2.Open MySQL Workbench
- 3.Create or select a database
- 4.In the Streamlit sidebar, choose:
    "Connect to your MySQL Database"
- 5.Enter:

- Host
- Username
- Password
- Database name

✅ Now you can chat with your MySQL database.