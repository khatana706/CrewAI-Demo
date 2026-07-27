# AI Content Research & Writing Assistant

A powerful content generation system built with CrewAI that combines research, analysis, and writing capabilities to produce high-quality blog posts on any topic.

## ✨ Features

- Automated research using Wikipedia and WolframAlpha
- AI-powered content writing and analysis
- Sentiment analysis and keyword extraction
- Streamlit web interface for easy interaction
- Downloadable Markdown output

## 📋 Prerequisites

- Python 3.9+
- GROQ API Key
- WolframAlpha API Key

## 🛠️ Installation

### Clone the repository

```bash
git clone https://github.com/khatana706/CrewAI-Demo.git
cd CrewAI-Demo
```

### Create and activate a virtual environment

```bash
conda create -n crewai python=3.12 -y
conda activate crewai
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Set up Environment Variables

Create a `.env` file and add your API keys:

```env
GROQ_API_KEY=your_openai_api_key
WOLFRAMALPHA_API_KEY=your_wolframalpha_api_key
```

## 🚀 Running the Application

### Command Line Version

Run the basic version using:

```bash
python app.py
```

### Web Interface

Launch the Streamlit web interface:

```bash
streamlit run streamlit_app.py
```

Then open your browser and navigate to:

```text
http://localhost:8501
```

## 💻 Usage

1. Launch the application.
2. Enter the topic you want to research.
3. The AI agents will perform research, analysis, and content generation.
4. Review the generated blog post.
5. Download the output as a Markdown file if needed.