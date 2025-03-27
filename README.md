"""
# AI-Powered Bank FAQ Chatbot
This chatbot provides answers to frequently asked banking questions. It first checks a predefined FAQ dataset and, if no answer is found, queries the Groq AI API.

## Features
- Searches banking FAQs before reaching out to AI
- Uses the Groq API for dynamic responses
- Maintains conversation history for contextual replies
- Secures API key handling using `.env`

## Getting Started

### 1. Clone the Repository
```sh
git clone https://github.com/your-username/Bank-FAQ-Chatbot.git
cd Bank-FAQ-Chatbot
```

### 2. Set Up a Virtual Environment (Recommended)
```sh
python -m venv venv
source venv/bin/activate  # Windows users: `venv\Scripts\activate`
```

### 3. Install Dependencies
```sh
pip install -r requirements.txt
```

### 4. Configure API Key
Create a `.env` file and add your Groq API key:
```sh
echo "GROQ_API_KEY=your-api-key-here" > .env
```
Or set it in your terminal:
```sh
export GROQ_API_KEY="your-api-key-here"
```

### 5. Run the Chatbot
```sh
python chatbot.py
```
"""
