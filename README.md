# 🔬 AI Research Assistant

> **A powerful multi-agent research system built with CrewAI**  
> *Automate your research workflow with intelligent AI agents working together*

---

## 🌟 Overview

AI Research Assistant is an intelligent research automation tool that leverages CrewAI's multi-agent system to conduct comprehensive research on any topic. Three specialized AI agents collaborate to gather information, analyze data, and generate detailed reports.

---

## ✨ Features

- 🤖 **Multi-Agent System**: Three specialized agents working in harmony
  - 🔍 **Research Specialist**: Gathers comprehensive information
  - 📊 **Data Analyst**: Analyzes and processes findings
  - ✍️ **Content Writer**: Creates well-structured reports

- 🎨 **Streamlit Web Interface**: Beautiful and intuitive UI
- 📄 **Multiple Report Formats**: Research findings, analysis reports, and final reports
- ⚡ **Real-time Progress Tracking**: Watch your research unfold
- 🔒 **Secure API Management**: Environment-based configuration

---

## 🛠️ Tech Stack

- **CrewAI** - Multi-agent orchestration framework
- **Streamlit** - Web application interface
- **LiteLLM** - LLM integration layer
- **Python** - Core programming language

---

## 🚀 Quick Start

### Prerequisites

- Python 3.8+
- API Keys:
  - `SERPER_API_KEY` (for web search)
  - `OPENAI_API_KEY` (for AI models)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/widushan/AI-Research-Assistant.git
   cd AI-Research-Assistant
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv .venv
   .venv\Scripts\activate  # Windows
   # source .venv/bin/activate  # Linux/Mac
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure environment variables**
   
   Create a `.env` file in the project root:
   ```env
   SERPER_API_KEY=your_serper_api_key_here
   OPENAI_API_KEY=your_openai_api_key_here
   ```

### Usage

**Option 1: Streamlit Web App (Recommended)**
```bash
streamlit run app.py
```

**Option 2: Command Line**
```bash
python main.py
```

### Screenshots

<img width="1918" height="1030" alt="Image" src="https://github.com/user-attachments/assets/adbd7b19-1b72-456f-a62b-1bb777a35257" />

<img width="1916" height="1025" alt="Image" src="https://github.com/user-attachments/assets/bcf2fab2-1de9-4097-bbb9-12a353a5f53b" />

<img width="1915" height="1028" alt="Image" src="https://github.com/user-attachments/assets/83ef4f24-303a-4895-81f7-e82cfe5d60fe" />

<img width="1913" height="1028" alt="Image" src="https://github.com/user-attachments/assets/e76120b8-00eb-490d-bebb-a0e90fd96671" />

<img width="1909" height="1034" alt="Image" src="https://github.com/user-attachments/assets/42cbc69f-9002-4c8a-a593-3d5e3a78a981" />

---

## 📁 Project Structure

```
AI-Research-Assistant/
├── agents/          # AI agent definitions
├── tasks/           # Task definitions
├── app.py          # Streamlit web interface
├── main.py         # CLI entry point
├── crew.py         # Crew orchestration
└── requirements.txt # Dependencies
```

---

## 🔗 Repository

**GitHub**: [https://github.com/widushan/AI-Research-Assistant](https://github.com/widushan/AI-Research-Assistant)

---

## 📝 License

This project is open source and available for personal and educational use.

---

## 👤 Author

**C.A Pasindu K W**

---

<div align="center">

*Built with ❤️ using CrewAI, Streamlit, and modern AI technologies*

**⭐ Star this repo if you find it helpful! ⭐**

</div>
