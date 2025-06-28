# GPT4 LangChain Agents

A comprehensive Python Streamlit web application that leverages OpenAI GPT-4 and LangChain agents to create intelligent research assistants. The application can access multiple data sources including PubMed, Wikipedia, and DuckDuckGo to generate detailed research reports.

## 🚀 Features

- **Multi-Source Research**: Access PubMed, Wikipedia, and DuckDuckGo for comprehensive information gathering
- **AI-Powered Reports**: Generate detailed research reports with introductions, quantitative facts, publications, books, and YouTube links
- **Interactive Chat**: Chat with a GPT-4 powered chatbot about research findings and previous studies
- **Data Persistence**: Store research data in SQLite database and vectorize into ChromaDB for efficient retrieval
- **Version Evolution**: Three progressive versions with increasing functionality

## 📋 Versions Overview

### V1 - Basic Implementation
- Initial Streamlit interface
- Basic research functionality
- Simple data storage

### V2 - Enhanced Features
- Improved UI/UX
- Better research report formatting
- Enhanced data management
- Requirements file added

### V3 - Advanced Vector Database Integration
- **ChromaDB Vector Database** implementation
- LangChain agents with vector search capabilities
- Advanced retrieval and storage mechanisms
- Optimized performance

## 🛠️ Installation

### Prerequisites
- Python 3.8 or higher
- OpenAI API key
- Git

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/kittysoftpaw0510/GPT4-LangChain-Agents.git
   cd GPT4-LangChain-Agents
   ```

2. **Choose your version**
   - Navigate to `AppV1/`, `AppV2/`, or `AppV3/` directory
   - Each version has different requirements and features

3. **Install dependencies** (for V2 and V3)
   ```bash
   cd AppV3  # or AppV2
   pip install -r requirements.txt
   ```

4. **Set up environment variables**
   ```bash
   # Create a .env file in your chosen app directory
   echo "OPENAI_API_KEY=your_openai_api_key_here" > .env
   ```

5. **Run the application**
   ```bash
   streamlit run main.py
   ```

## 🎯 Usage

1. **Research Generation**:
   - Enter your research topic in the input field
   - The application will gather information from multiple sources
   - Review the generated comprehensive report

2. **Chat Interface**:
   - Ask questions about your research findings
   - Discuss previous research stored in the database
   - Get AI-powered insights and explanations

3. **Data Management**:
   - All research is automatically saved to the database
   - Access previous research through the interface
   - Vector search enables efficient information retrieval

## 📁 Project Structure

```
GPT4-LangChain-Agents/
├── AppV1/
│   └── main.py                 # Basic implementation
├── AppV2/
│   ├── main.py                 # Enhanced features
│   └── requirements.txt        # Dependencies
├── AppV3/
│   ├── main.py                 # Advanced with ChromaDB
│   └── requirements.txt        # Dependencies
└── README.md                   # This file
```

## 🔧 Technologies Used

- **Frontend**: Streamlit
- **AI/ML**: OpenAI GPT-4, LangChain
- **Database**: SQLite, ChromaDB (Vector Database)
- **Data Sources**: PubMed, Wikipedia, DuckDuckGo
- **Language**: Python

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- OpenAI for providing the GPT-4 API
- LangChain for the agent framework
- Streamlit for the web application framework
- ChromaDB for vector database capabilities

## 📞 Support

If you encounter any issues or have questions, please open an issue on the GitHub repository.

---

**Note**: Make sure to have a valid OpenAI API key and sufficient credits for using the GPT-4 model.

