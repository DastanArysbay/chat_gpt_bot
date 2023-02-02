# OpenAI Telegram Bot(chat_gpt_bot)

This is a Telegram bot that uses the OpenAI API to answer questions submitted by users. The bot was built using the pyTelegramBotApi library.

## Prerequisites

Before you begin, make sure you have the following tools installed on your system:

    Python 3.7 or later
    pip (Python package manager)

## Installation

1. Clone the repository to your local machine using the following command:

`$ git clone https://github.com/DastanArysbay/chat_gpt_bot`

2. Change into the project directory:


`$ cd OpenAITelegramBot`

3.Create a virtual environment and activate it:


`$ python3 -m venv venv`
`$ source venv/bin/activate`

4.Install the required packages:

`$ pip install -r requirements.txt`

5. Create a Telegram bot and obtain the API key.

6. Store the API key in an environment variable named TELEGRAM_BOT_API_KEY.

7. Replace the placeholder in the code with your OpenAI API key:

```python```
`openai.api_key = "YOUR_OPENAI_API_KEY"`

8. Run the bot:

`$ python bot.py`

## Usage

9. Start a conversation with your bot in Telegram.

10. Send it a question.

11. The bot will reply with an answer.

## Conclusion

That's it! Your OpenAI Telegram Bot is now ready to use. Enjoy!


