📂 Gemini Text Response Generator
A Python-based automation tool that generates AI responses using Google's Gemini API with automatic API key rotation.
🚀 Features
🔑 Multiple API key support
🔄 Automatic key switching on quota exhaustion
🧠 Structured prompt system
📄 Output saved to file
⚡ Fast response using Gemini Flash model
🏗️ Project Structure

├── main.py        # Core execution logic
├── config.py      # API keys & model config
├── prompts.py     # All prompts
├── output.txt     # Generated results
⚙️ Setup Instructions
1. Install Dependencies
Bash
pip install google-generativeai
2. Add API Keys
Edit config.py:
Python
API_KEYS = [
    "YOUR_API_KEY_1",
    "YOUR_API_KEY_2"
]
3. Run the Project
Bash
python main.py
🔄 API Key Rotation Logic
If API quota is exceeded:
Automatically switches to next key
If all keys exhausted:
Raises error
📥 Output
Results are saved in:

output.txt
Includes:
Prompt
Role
Task
Response
Status
🧠 Example Use Cases
AI prompt automation
Bulk content generation
Learning & experimentation
Data science explanations# Text_generator
