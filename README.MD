# AI Telegram Chatbot

This project is a simple Telegram chatbot that integrates with Cohere AI to generate responses to user messages. The bot listens for any text messages, sends them to the AI model, and returns the generated response.

## Features
- Responds to any text message in the chat
- Uses Cohere's AI model to generate intelligent responses
- Easy to set up and customize

## Prerequisites

To run this bot, you will need:

- Python 3.6+
- A Cohere API key
- A Telegram Bot API token

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/derssen/AI-Telegram-Chatbot.git
    cd your-repo-name
    ```

2. Install the required Python libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Create a `.env` file (optional) to store your API keys:
    ```bash
    echo "AI_API_KEY=your-cohere-api-key" > .env
    echo "API_TOKEN=your-telegram-bot-token" >> .env
    ```

4. Update the script with your API keys:
    - Replace `'your-cohere-api-key-here'` with your Cohere API key.
    - Replace `'your-telegram-bot-token-here'` with your Telegram Bot API token.

## Usage

1. Run the bot:
    ```bash
    python bot.py
    ```

2. Start a conversation with your bot in Telegram. Any message you send will be processed by the AI, and it will generate a response.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
