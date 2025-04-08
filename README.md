**Gemini Telegram Bot**

**Description**  
This project is a Python-based Telegram bot that integrates with Google Generative AI to provide intelligent, context-aware responses to user messages. Using the Gemini 1.5 Flash model, the bot delivers human-like replies in real-time, making it a powerful tool for conversational automation.

**Features**  
- Real-time message handling via Telegram.  
- Integration with Google Generative AI for smart responses.  
- Secure API key management using environment variables.

**Installation**  
Follow these steps to set up the project locally:  

1. Clone the repository:  
   ```
   git clone https://github.com/usmanovabdulaziz/ChatBot.git
   ```

2. Navigate to the project directory:  
   ```
   cd gemini-telegram-bot
   ```

3. Create a virtual environment (optional but recommended):  
   ```
   python -m venv venv
   source venv/bin/activate
   # On Windows: venv\Scripts\activate
   ```

4. Install the required dependencies:  
   ```
   pip install -r requirements.txt
   ```

5. Run the bot:  
   ```
   python gemini.py
   ```

**Usage**  
1. Start the bot by running the script as shown above.  
2. Open Telegram and search for your bot using its username (configured via your Telegram API key).  
3. Send a message to the bot, and it will respond with a generated reply from the Gemini AI model.  

**Example Interaction**  
- **User**: "What is the weather like today?"  
- **Bot**: [AI-generated response based on the prompt]

**Configuration**  
The bot requires API keys for Telegram and Google Generative AI. These are managed securely using a `.env` file:  

1. Create a `.env` file in the project root with the following content:  
   ```
   TELEGRAM_API_KEY=your_telegram_bot_api_key
   GEMINAI_API_KEY=your_google_generative_ai_key
   ```

2. Replace `your_telegram_bot_api_key` with the token provided by BotFather on Telegram.  
3. Replace `your_google_generative_ai_key` with your Google Generative AI API key.  

The `.env` file is automatically loaded when you run `gemini.py`.

**Dependencies**  
- Python 3.8+  
- `pyTelegramBotAPI` - For Telegram bot functionality.  
- `google-generativeai` - For interacting with Google’s Generative AI API.  
- `python-dotenv` - For loading environment variables from `.env`.  

Install these dependencies with:  
```
pip install pyTelegramBotAPI google-generativeai python-dotenv
```

A full list of dependencies is available in `requirements.txt`.

**Contributing**  
Contributions are welcome! Feel free to submit a pull request or open an issue on GitHub. Please ensure your code follows PEP 8 style guidelines.

**License**  
This project is licensed under the MIT License.

**Contact**  
For questions or feedback find me on GitHub: https://github.com/usmanovabdulaziz/
