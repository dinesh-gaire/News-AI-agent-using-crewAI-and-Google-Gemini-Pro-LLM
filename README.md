# 🤖 News AI Agent: Intelligent Research & Writing Automation

## 🌟 Project Overview

Introducing an groundbreaking AI-powered research and content generation system that transforms how we discover and communicate complex technological insights. Powered by CrewAI and Google Gemini Pro, this intelligent agent automates in-depth research and storytelling.

## ✨ Key Features

- 🕵️ **Intelligent Research Agent**: Uncover cutting-edge trends and technologies
- ✍️ **Adaptive Writing Agent**: Generate compelling, insightful narratives
- 🌐 **Real-Time Internet Search**: Leverage Serper API for up-to-the-minute information
- 🧩 **Modular & Flexible Design**: Easily customizable for diverse research domains

## 🛠 Technology Stack

- **Agent Framework**: CrewAI
- **Language Model**: Google Gemini Pro LLM
- **Search Integration**: Serper API
- **Programming Language**: Python 3.x

## 🚀 Quick Start Guide

### Prerequisites

Before you begin, ensure you have:
- Python 3.x
- pip (Python package manager)
- Google API Key
- Serper API Key

### Installation Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/dinesh-gaire/News-AI-agent-using-crewAI-and-Google-Gemini-Pro-LLM.git
   cd News-AI-agent-using-crewAI-and-Google-Gemini-Pro-LLM
   ```

2. **Create Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure Environment Variables**
   Create a `.env` file in the project root:
   ```
   GOOGLE_API_KEY=your_google_api_key_here
   SERPER_API_KEY=your_serper_api_key_here
   ```

## 💡 Usage Examples

### Basic Execution
```bash
python crew.py
```

### Customized Research
Modify the `crew.py` script to specify your research topic:
```python
result = crew.kickoff(inputs={'topic': 'AI in healthcare'})
```

## 📝 Writing Task Details

### Output Specification
- Four-paragraph markdown article
- Focus on latest trends and industry impact
- Saved as `new-blog-post.md`

## 🔍 How It Works

### Research Workflow
1. 🌐 Internet Search
2. 📊 Data Collection
3. 🧠 Intelligent Analysis
4. ✍️ Narrative Generation

## 🤝 Contribution Guidelines

### Ways to Contribute
- Report Bugs
- Suggest Enhancements
- Submit Pull Requests

### Contribution Steps
1. Fork the Repository
2. Create a Feature Branch
3. Implement Your Changes
4. Submit a Pull Request

## 🌈 Potential Use Cases

- Technology Trend Analysis
- Industry Research
- Automated Journalism
- Market Intelligence
- Academic Research Assistance

## 🏆 Key Advantages

- 🚀 Rapid Information Gathering
- 📈 Consistent Quality
- 🌐 Wide Research Scope
- 💡 Innovative Storytelling

## 📄 License

Open-source project. Check the LICENSE file for details.

## 🙏 Acknowledgments

Special thanks to:
- CrewAI Developers
- Google Gemini Pro LLM Team
- Serper API
- Open-Source Community

---

**Disclaimer**: This is an AI-assisted research tool. Always verify critical information from authoritative sources.

## 📞 Support

Need help? [Open an Issue](https://github.com/dinesh-gaire/News-AI-agent-using-crewAI-and-Google-Gemini-Pro-LLM/issues)
